# Lab 2 Command Lines
## Hostname
This command fetches the hostname of the device the terminal is running on which is confirmed by checking the computer system settings.
![image](https://github.com/user-attachments/assets/ed87a7f0-f2bf-40df-96e2-0761c51770e2)
![image](https://github.com/user-attachments/assets/15b93927-0bde-4ef6-9af9-cec3ab0b2d11)
## env
This command fetches the environment variables of the device which can be crossed checked on the environment variable control panel.
![image](https://github.com/user-attachments/assets/9846ead9-f122-47db-9940-a4c512ea2498)
## ps
![image](https://github.com/user-attachments/assets/f2ffb4d1-ab02-4bd4-ba6a-f7a9280d2888)
This command displays information about what processes are currently running. 
- PID- process identification number
- PPID- the parent process ID
- PGID- process group ID of parent and children
- WINPID- a process identify for the operating system
- TTY- the terminal where the process is stored
- UID- user id
- STIME- the starting time for a process
- COMMAND- name of the process
## pwd
![image](https://github.com/user-attachments/assets/c03d2a68-afbd-4832-b40c-c4e0390f0c8e)\
This command prints the current working directory path of the command terminal.
## git clone
![image](https://github.com/user-attachments/assets/e3914af7-22b1-45d1-b01f-fe4ca5d593df)\
In order for this command to be used git must be downloaded on the device. Once git is open, this command will clone a directory given the source link.
## cd iot
![image](https://github.com/user-attachments/assets/25a0bbc7-51bd-443e-b5f0-a277e48cf963)\
This command moves the current working directory path of the command terminal, in this case to iot.
## ls
![image](https://github.com/user-attachments/assets/bcda9122-3988-482a-a49d-7bec501c99ca)\
This command prints the files in the directory we moved to in this case iot in the cloned repository.
## cd
![image](https://github.com/user-attachments/assets/85758b90-04dd-4b18-9e6f-6c4d93332c36)\
Now that we are using git, this command returns us to the home directory when we do not specify unlike the ` cd iot ` command.
## df
![image](https://github.com/user-attachments/assets/6357a86f-09a5-4987-b6fe-d6344d8370ca)\
This command displays information about the file system like what is used, available, the percent used, and storage used in terms of 1K-blocks which are 1024 byte units.
## mkdir demo and cd demo
![image](https://github.com/user-attachments/assets/09205b97-35d1-44d2-8fce-63699ce24727)\
Creates a new file in iot called demo `cd demo` moves current directory to the new file demo.
## nano file
![image](https://github.com/user-attachments/assets/e1cc6b3c-109b-4538-81bd-5ac723eac91c)\
Creates a new nano file in our current directory iot/demo
## cat file
![image](https://github.com/user-attachments/assets/3f03e6e3-5bf8-4f13-8e75-463439785edb)\
After saving the nano file and exiting back to the command prompt, `cat file` prints out the contents of file which I saved test
## cp file file1
![image](https://github.com/user-attachments/assets/b5da47d6-de5e-4417-a916-e5594e91655c)\
This command copys the first argument giving it the name of the second argument. In this case our nano file was copyed to make file1. Using the cat command again on our new file `cat file1` results in the same contents.
## mv file file2
![image](https://github.com/user-attachments/assets/fdbb1378-3da2-4eb2-9bbe-d51f4d4a1bee)\
This command moves the first argument to a new file named the second argument. mv acts as a cut/paste while mov acts as a copy/paste. This is illustrated by trying to read the contents of file and file2 where file no longer exists.  
## rm file2
![image](https://github.com/user-attachments/assets/fcdb47a7-5ef4-44d9-ba88-b2f77cd2b2f9)\
This command removes the file in the argument. When trying to access the contents of file2 now, it can no longer be found.
## clear
![image](https://github.com/user-attachments/assets/cd674227-41c1-4127-8986-9313cb7cdf00)\
This command clears the history and outputs in the command prompt.
## man uname
This command isn't usable on Windows systems. It is similar to the `help` command in this case it would give information on uname.
## uname -a
![image](https://github.com/user-attachments/assets/d58c8df6-940f-4c82-9f78-779ba9e2db3d)\
This command prints information about the operating system of the device including the hostname, version, release date, and processor type.
## ifconfig
This command isn't usable on Windows systems. When no arguments are given, this command would display the status of active interfaces.
## ping localhost
![image](https://github.com/user-attachments/assets/077b77eb-2d31-449c-accf-00cc948a88cb)\
This command tests the network connection of local host by sending 4 packets and measuring the time until they are received. Statistics on loss percent, response minimum, maximum, and average are also printed.
## netstat
![image](https://github.com/user-attachments/assets/1a1721c5-0640-46d5-8031-8272cab4f652)\
This command prints information about the devices current network connections including, the protocol type, addresses, and current state.
