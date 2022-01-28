# lab report week 1

lab-report-1-week-2.md

Haochen Jiang

A17011224

## Installing VScode
![image](pic1.png)

[vscode link](https://code.visualstudio.com/)
this is the link to download vscode.
I download vscode and this is my screenshot of it

## Remotely Connecting

then i have to remote connect to the server using my ucsd account
ssh cs15lwi22anv@ieng6.ucsd.edu


![image](pic2.png)

this is my first time log in and it has a lot of output here

i am going to try some command here

## Trying Some Commands
![image](pic3.png)

i tried `pwd` i think this command is to show my current path
things change when i was typing this command using my own computer or during the remote access.

![image](pic4.png)

## Moving Files with scp
scp WhereAmI.java cs15lwi22anv@ieng6.ucsd.edu:~/

![image](pic5.png)

as you can see, there is a difference between the first java command and the second one. because i am running the java and javac in different client, the first one is on my own computer so it shows winows 10 and jiang, then on the server it shows linux and my username of access.

## Setting an SSH Key
![image](pic6.png)

I set up a passphrase so that i can login with a simple passphrase but not using long complex password

![image](pic7.png)

i got some trouble using this command, it let me get stuck in this, so i have to type control+c to logout, this is quite useful.

## Optimizing Remote Running