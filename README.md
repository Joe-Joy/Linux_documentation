# LINUX COMMANDS DETAILS:-

| command | descrtiption                                                             |
| ------- | ------------------------------------------------------------------------ |
| ls      | Use the "ls" command to know what files are in the directory you are in. |

> 1.**ls** => Use the "ls" command to know what files are in the directory you are in.

> **ls -la** => List out the items one by one. You can see all the hidden files

**cd** => Change directory.

**pwd** => Print working directory (exact directory).

**mkdir** => When you need to create a folder or a directory.

**rmdir** => Can only be used to delete an empty directory.

**rm** => rm command to delete files and directories.

**rm -r** => delete just the directory. It deletes both the folder and the files it contains when using only the rm command.

**touch** => The touch command is used to create a file.

**man & --help** => To know more about a command and how to use it, use the man command. It shows the manual pages of the command.

**cp** (copy) => Use the cp command to copy files through the command line. It takes two arguments: The first is the location of the
to be copied, the second is where to copy.

**mv** (move) => Use the mv command to move files through the command line. We can also use the mv command to rename a file. For example, if we want to rename the file “text” to “new”, we can use “mv text new”.

**locate** => The locate command is used to locate a file in a Linux system, just like the search command in Windows. This command is useful when you don't know where a file is saved or the actual name of the file. **~/Desktop$ locate test.txt**

**echo** => The "echo" command helps us insert some data into a file. **~/Desktop$ echo ashli, joe >> test.txt**

**cat** => Use the cat command to display the contents of a file. It is usually used to easily view programs. **~/Desktop$ cat test.txt**

**cat (filename) | grep (selected word)** => to show the selected file content and highlighted a ashli name within a file

**Kill -9 PID** => The most common command to terminate a process is kill command. You need to know the PID of the process you want to terminate.

**nano, vi, jed** =>nano and vi are already installed text editors in the Linux command line. The nano command is a good text editor that denotes keywords with color and can recognize most languages

**sudo** => A widely used command in the Linux command line, sudo stands for "SuperUser Do". So, if you want any command to be done with administrative or root privileges, you can use the sudo command.

**sudo bash** => You can enter the root line **root@HP-EliteBook-8570w:/home/crash#**

**sudo passwd** => Change in the new root password.

**df** => Use the df command to see the available disk space in each of the partitions in your system. You can just type in df in the command line and you can see each mounted partition and their used/available space in % and in Kbs.

**df -m** => Disk file system want it shown in megabytes.

**du** => Use du to know the disk usage of a file in your system. If you want to know the disk usage for a particular folder or file in Linux, you can type in the command df and the name of the folder or file.

**ls -lh** => to view the file sizes of all the files in a folder.

**zip, unzip** => Use zip to compress files into a zip archive, and unzip to extract files from a zip archive.

**uname** => Use uname to show the information about the system your Linux distro is running.

**name -a** => prints most of the information about the system. This prints the kernel release date, version, processor type, etc.

**sudo apt-get install (update && upgrade)** => to update and upgrade the system;

**hostname** => Use hostname to know your name in your host or network.

**hostname -I** => your IP address in your network.

**ip a** => find the ip address.

**getfacl (filename)** => getfacl displays the file name, owner, the group, and the Access Control List (ACL). If a directory has a default ACL, getfacl also displays the default ACL.

**setfacl -m group::rwx or rw- or --- (filename) (manual ACL)** => We can add ACL to these files using setfacl. ACL – Access Control List.

**shutdown -r (time)** => With option r, system will shutdown immediately and automatically reboot. **sudo shutdown -r 3**

**shutdown -P (time)** => To power-off the system option P is used.

**sudo mount /dev/sdd1 /mnt** => to mount into the disk

**sudo umount /mnt** => to unmount the disk

**lsblk** => to see all the disks and partitions on your system.

**blkid** => to gather UUID of the partition. UUID- Univeresal Unique Identification.

**su -** => open up the new shell of directory. **ashli**@Hp-EliteBook-8570w:~$

**chmod g+x (filename)** => execute(x) permission **group** in test.txt(your filename) filename.

**chmod o-r (filename)** => remove read permission **others** in text.txt(your filename) filename.

**chmod u-x (filename)** => remove execute permission on **user** in test.test.txt(your filename) filename.

**sudo apt-get remove (package_name)** => to remove the packages using this commands.

**sudo apt install package_name** => to install the new packeages.

**service --status-all** => List all services in Ubuntu.

**sudo systemctl stop service_name** => stop the service.

**sudo systemctl start service_name** => start the service.

**sudo systemctl restart service_name** => restart the service.

**sudo systemctl status service_name** => status of the service details.

**df -h** => shows disk space in human-readable format.

**df -i** => shows used and free inodes.
