# Lab report 1 Week 2 

### How to remotely connect to a course specific account on ieng6 (For MacOS)


#### **Part 1**: 
The first thing to do is to download [VSCode](https://code. visualstudio.com/download) or install an IDE with a terminal

* After downloading it, open it and it should look something like this:


![VScode image](VSCODE.png)

There is a built in terminal in VScode, which can be opened by going to terminal -> new terminal. This will be used in order to remotely access the ieng6 server. 

#### **Part 2**: 
After installing the IDE, Lookup your ieng6 account [here.](https://sdacs.ucsd.edu/~icc/index.php) You may need to update your password so you can access the server. Go to the terminal and type in the command 'ssh cs15lsp22xxx@ieng6.ucsd.edu where xxx is a unique to you. There will be a password prompt where you enter your password. 


![RemoteAccess](Remoteaccess.png)
Note: there is no password prompt because there is an ssh key that automatically allows access (this will be covered later). 

#### **Part 3** 

After you have successfully connected to the secure remote server, you can manipulate the files with various commands. Some of the commands include ( *cd ~ *, *ls*, *cd*, *mv*, *cp*)


![trying terminal commands](TryingNewCommands.png)

### **Part 4**

In order to move a file from the local (your computer) to the remote server, you have to use the command *scp*. In order to do so, go to the console on your device and type in *scp <file name\> cse15lsp22xxx@ieng6.ucsd.edu:~/*







