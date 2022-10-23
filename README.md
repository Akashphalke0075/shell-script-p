# linux command

* how to connect to server?

ssh username@ip

* touch (make empty files)

* ls -l /ls- ltr  (display long list)

* mkdir  (to make directory)

* cd   (change directory/ switch directory)

cd .. (one directory back)

cd - (goes to previous path)

* cat (command use to read the content of the file)

this is end


* rmdir (to delete directory)

rm  (delete file)

* mv (rename the file") or (it's like cut and paste)
mv 

* pwd  (present working directory)

* uptime (to check machine is running state from how much time)

* cat /proc/meminfo  (it gives memory related info)
* cat /proc/cpuinfo  (it gives cpu related info)

* fdisk -l   (It gives disk related info.)

* sudo su -  ( change from normal user to root user #)
 exit (command use to exit from root user to normal user $)

* sudo command gives administrative access for temporary use
 NOTE -Only root user has administrative permissions

* cd ~ (u will directly go to home directory )

* cp (copy the file/ for taking backup of the file)

* yum (package manager - redhat)
syntax = yum install/remove/update PackageName
example - tree , nginx

* how to download package like tree? nginx ? or anyuthing..
ex. sudo yum install tree -y
EX. sudo yum install nginx -y

* how to patch/update in your machine or server
syntax= sudo yum update -y  (it  will run for 10 to 15 minuts atleast as it is patching everything)

Note- in windows we call update but in linux we call patches

* how to list of user account present in machine?
syntax=  cat /etc/passwd

we can give numbering by cat -n /etc/passwd

* tac  (reverse order)
example=  tac /etc/passwd

* tail ( only last 10 line)
ex. tail /etc/passwd

* head (only top 10 line)
ex. head /etc/passwd

* how to print last 3 lines?
tail -n 3 filename

* how to print top 5 line?
head -n 5 filename

* how to print line between 7 t0 10?
by using sed command
ex sed -n -e "7,10p" filename

* how to print field separate from file?
ex. cut -d : -f1 /etc/passwd

* how to print field from 4 to 9 from file?
ex.  cut -d : -f4-9 /etc/passwd


* vim
i- insert mode
esc- escape mode
:wq!  (save the file)
:q!    (quit the file without saving)

* how to replace words in file?
:%s/word/newword  - (everyline 1st occurance)
:%s/word/newword/g - (every word in whole file)
:/s/word/newword    - (1st word on selected line)
:/s/word/newword/g  - (every word in selected line)

* how to add user?
sudo useradd name

* how to set passwd for user?
sudo passwd username

* how to check propertise of user?
syntax= id username

* /etc/sudoers (here you can give permission to users)
sudo vim /etc/sudoers

* how to make a group?
syntax= sudo groupadd groupname

* how to add user to group??
sudo usermod -a username -G groupname

* top
* ps -ef
* kill
* ip a  (privat ip)
* curl ifconfig.co (public ip)


* how to download anything from internet?
Syntax=  wget url
ex. tomcat

* how to untar the tar file?
syntax tar -xf filename

* pipe (|)
ex. cat /etc/passwd | head -n 4

* how to shutdown system ?
sudo init 0

* how to restart/reboot the machine?
sudo init 6

*how to start service?
sudo systemctl start/stop/restart serviceName

* how to check status of the service we started?
sudo systemctl status serviceName

* Ami backup term)




----------
