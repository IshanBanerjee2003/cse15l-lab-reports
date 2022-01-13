1. Installing VScode:

Since I had taken CSE11 the previous quarter, I had installed it back then. However if one wishes to install it, one may simply follow the instructions as stated in the website. The step by step instructions on the website are very clear and easy to understand. Once installed, one should download the various extensions that come with it. 
The screenshot below shows an installed version of VScode on my computer:

The following program is one which we had to do for my other class, CSE12.
![image](https://user-images.githubusercontent.com/97653190/149305057-bd5e0c8d-fd6c-42ec-979c-639b5a66db08.png)

2. Remotely Connecting 

The next step is to remotely connect to the remote servers, which basically refers to the computers in the cse building. 
To do this I first log in to my cse15L account, in order to retrieve my username and change my password. Then I proceeded to install the SSH software on my computer
Next I entered my course-specific account and the password to connect to the remote server, as displayed below:
![image](https://user-images.githubusercontent.com/97653190/149305244-0b9aef64-a599-4b56-8337-8579bca20429.png)

3. Trying some commands

The next screenshot is about trying some commands, and testing the response they have:
![image](https://user-images.githubusercontent.com/97653190/149305365-64786fd8-0512-4303-aaec-dd4580c1e97e.png)

4. Moving files with scp:

The next step is to move files using the scp function.
The screenshot below illustrates using the getProperty function, the server in which the current program is running. The one below is my personal computer and hence shows Windows 10, and the user as Mikey.
![image](https://user-images.githubusercontent.com/97653190/149305474-611eb65e-88c1-4e60-9195-22ca19d98848.png)

However once I use the scp function to move it to the remote server, it does so and after that when i SSH into the server, the getProperty function gives me the location of the remote server which is Linux.
![image](https://user-images.githubusercontent.com/97653190/149305694-24b0bc4e-6c3b-462c-8998-f433709d3915.png)

5. Setting an SSHkey

The next step is to set up your SSHkey as follows:
![image](https://user-images.githubusercontent.com/97653190/149305909-ee685b97-f6e6-4dfa-8c2c-fdb1bdec8cc8.png)

6. Optimizing Remote Running
In order to make remote running an even more pleasant experience, we use what we’ve learned to make a local edit to WhereAmI,java and then copy it to the remote server and run it.
What I basically did was write a command in quotes at the end of an ssh command to directly run it on the remote server, then exit. For example, this command will log in and list the home directory on the remote server:
![image](https://user-images.githubusercontent.com/97653190/149306149-a01ae9f0-f5c2-4b3c-95be-2039ad14e63f.png)

Another thing which I did was use semicolons to run multiple commands on the same line in most terminals. For example,I tried:
![image](https://user-images.githubusercontent.com/97653190/149306244-8405ac86-cdd2-4233-84a4-09fd1db96756.png)


