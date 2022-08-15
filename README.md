# What is Dev Env & benefits
## Vagrant and Virual box
### Virtualistaion?



- how can we find out the name OS `uname` or `uname -a`
- how to creat a file in linux `touch filename` or `nano filename`
- how to check existing file/folders `ls` or `ls -a`
- how to creat a folder `mkdir foldername`
- how to navigate inside the folder `cd fodlername`
- how to come out of the folder or 1 step back `cd ..`
- Where am I  `pwd`
- whoami
- how to copy file ` cp filename_with_absolute_path destination_with_absolute_path
- how to remove file/folder `rm -rf file/folder_name`

- How to cut paste the file/move the test file inside linux_commands folder
- how to check all process `top`
and `ps aux`
- find out how to remove/delete/kill process 
- how to use root user `sudo su` or `sudo i`

- how to use `|` pipe
- how to check file permission `ll`
- change file permision `chmod permission filename`
- `r` or `w` or `rw` `all` also numbers `400` or `600` for all `700`
- update our ubuntu OS `apt-get update`
- upgrade our ubuntu os `apt-get upgrade` or `sudo apt-get upgrade -y`

- how to create automte tasks with provisioning scritps
- automate update and upgrade 
- `cat filename`
- run provision.sh `./prvision.sh
- Install nginx `sudo apt-get install nginx -y`
- how to check if it's installed/working `sudo systemctl status nginx`
- how to restart a process - in this case it's an NGINX
- restart or start `sudo systemctl restart nginx`
- enable the process ` sudo systemctl enable nginx`

### Monolith Deployment 
#### Nodejs - backend tool
##### by default Nodejs works on port 3000
- Q&A `What are the features of this app`
- `3 pages` 1   `sparta app page` 2 `fibonacci replacement` 3rd is ` 192.168.10.100:3000/posts` for `mongodb`
- mongodb default port is `27017` and Mongodb allows you to access - `mongod.conf` you need to allow the required ip
- what is nodejs - how to launch it
- what are the dependencies - install nodejs -> required version of that `version 6.0 or above`
- ` sudo apt-get install nodejs -y` centOS ` yum install nodejs -y`
- Which env is needed in order for us to deploy this app
- `linux ubuntu 16.04 or above
- `sudo apt-get update && sudo apt-get install yarn`