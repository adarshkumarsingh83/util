### to find the process on port and kill 
* $ lsof -i :<'port'>
* $ kill -9 <'pid'>

### to find the process based ont he process name
* $ ps -ax | grep <'processname'>

### to find any file dir in the system 
* $ sudo find / -name <'search term'>

### to delete forcefully and recursively 
* $ rm -rf <'dir name'>

### to provide the permission to the dir and recursively 
* $ chmod -R 777 <'dir name'>

### to export the path 
* export PATH=<----- path to export------>:$PATH

### to know the process id for 
* $ ps -A | grep -m1 <'process name'> | awk '{print $1}'

* $ lsof -nP -i4TCP:$8081 | grep LISTEN 
* $ ps -ef | grep tomcat


### to install tree cmd in mac 
* $ brew install tree