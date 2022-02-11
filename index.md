# LAB Report 3



## my config file
I used below command to create a config file in the hidden folder:
```
cd ~/.ssh
touch config 
```
Then I used nano to put the below code into the config:

```
Host ieng6
    HostName ieng6.ucsd.edu
    User cs15lwi22auv
```

To use nano, I used the below code: 
```
nano ~/.ssh/config
```

It looks like this:
![image](config.png)



## SSH command login

Now I can just use ssh ieng6 to log in to the server!
```
ssh ieng6
```


![image](ieng6.png)

## SCP command
I created a file named la_file on the server and I used the below scp command to copy it to my computer:
```
scp ieng6:la_file ~/desktop
```
Here is the result:
![image](scp.png)


