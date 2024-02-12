# ** Excersice **
| Question | Solution |
|---------------------------|
| Change directory to the tests directory using absolute pathname | cd /home/altschool/tests |
| Change directory to the tests directory using relative pathname | cd tests |
| Use echo command to create a file named fileA with text content ‘Hello A’ in the misc directory | echo "Hello A" > home altschool/misc/fileA |
| Create an empty file named fileB in the misc directory | touch /home/altschool/misc/fileB |
| Copy contents of fileA into fileC | cp /home/altschool/misc/fileA /home/altschool/misc/fileC |
| Move contents of fileB into fileD | mv /home/altschool/misc/fileB /home/altschool/misc/fileD |
| Create a tar archive called misc.tar for the contents of misc directory | tar -cvf misc.tar misc |
| Compress the tar archive to create a misc.tar.gz file | gzip misc.tar |
| Create a user and force the user to change his/her password upon login | i. create new user: mimi sudo useradd mimi ii. force mimi password change on login: sudo passwd -e mimi or sudo chage -d 0 mimi| 
| Lock a users password	| sudo passwd -l mimi | 
| Create a user with no login shell	| sudo useradd -s /usr/sbin/nologin shem |
| Disable password based authentication for ssh |	Use sudo vim /etc/ssh/sshd_config and set PasswordAuthentication no |
| Disable root login	| Use sudo vim /etc/ssh/sshd_config and set PermitRootLogin no | 