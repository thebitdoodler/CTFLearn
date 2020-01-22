# CTFLearn
Solutions for CTFlearn Challenges 

**1.Challenge Name : Taking LS:**

As The name of the challenge sugget:We have to use `ls command`

***Steps to be followed:***

1.First we need to download the zip file from the given link.

2.Then we need to unzip it using

```root@root:-# unzip <file name>```

3.After unzipping the file we'll get directory named *'The FLag'*

4. Using ```ls``` command check for the content of the unzip directory. Here you'll find a pdf which may content the flag. If you try to open this pdf. It'll ask for a password. Now the question is where you'll get the password?
5.As per the challenge name suggested to find the flag ```ls``` command should play a great role. There must be somthing in this directory which will lead to any clue of the required password.
In this case file/directory may be hidden. To check hidden files :

```root@root:-# ls -al```

Here you'll get the password file which is a simple text file. 
Get the password from that and open the pdf file.
Here you'll get the password.

**Happy Hunting**
