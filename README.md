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

* pwd  (present working directory)

* uptime (to check machine is running state from how much time)

* cd ~ 

* cat /proc/meminfo  (it gives memory related info)

* fdisk -l   (to see disk related info.)

* sudo su -  ( change from normal user to root user #) 
-sudo command gives administrative task access
-only root user has administrative permissions

* cp (copy the file/ for taking backup of the file)

* yum (package manager - redhat)
syntax = yum install/remove/update packagename
example - tree , nginx

note- in windows we call update but in linux we call patches

* how to download package like tree? ngnix ? or anyuthing..
ex. sudo yum install tree -y

* how to patch/update in your machine or server
syntax= sudo yum update -y

* how to list of user account present in machine?
cat /etc/passwd

we can give numbering by cat -n /etc/passwd

* tac  (reverse order)

* tail
* head

* how to print last 3 lines?
tail -n 3 filename

* how to print line between 7 t0 10?
by using sed command
ex sed -n -e "7,10p" filename

* how to print field separate from file?
cut -d : -f1 /etc/passwd

* vim


* Ami backup term)


----------
