# Python 3 for System Administrators

The scripts written throughout the Python 3 for Systems Administrators
course videos. This repository also includes the helper script to
easily create a database server to follow along with the final section of the
course.

* [Helper files](/helpers)
* [Course Scripts](/scripts)
* [Final Project (pgbackup)](/pgbackup)



Packages to Install on a Custom Remote Python Server for development 

$ sudo su -
$ yum update
$ yum groupinstall -y "development tools"
$ yum install -y \
  lsof \
  wget \
  vim-enhanced \
  words \
  which
$ exit

$ curl https://raw.githubusercontent.com/linuxacademy/content-python3-sysadmin/master/helpers/bashrc -o ~/.bashrc

$ curl https://raw.githubusercontent.com/linuxacademy/content-python3-sysadmin/master/helpers/vimrc -o ~/.vimrc
