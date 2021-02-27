# task0
tiyasa@tiyasa:~$ pwd
/home/tiyasa
tiyasa@tiyasa:~$ cd Desktop
tiyasa@tiyasa:~/Desktop$ pwd
/home/tiyasa/Desktop
tiyasa@tiyasa:~/Desktop$ mkdir practice
tiyasa@tiyasa:~/Desktop$ cd practice
tiyasa@tiyasa:~/Desktop/practice$ touch try.py
tiyasa@tiyasa:~/Desktop/practice$ sudo nano try.py
[sudo] password for tiyasa: 
tiyasa@tiyasa:~/Desktop/practice$ sudo gedit try.py

(gedit:8577): Tepl-WARNING **: 01:15:38.062: GVfs metadata is not supported. Fallback to TeplMetadataManager. Either GVfs is not correctly installed or GVfs metadata are not supported on this platform. In the latter case, you should configure Tepl with --disable-gvfs-metadata.
^C
tiyasa@tiyasa:~/Desktop/practice$ python try.py
Enter number10
('Sum of first ', 10, 'number is: ', 55)
tiyasa@tiyasa:~/Desktop/practice$ sudo chmod +x try.py
tiyasa@tiyasa:~/Desktop/practice$ sudo chmod 777 try.py
tiyasa@tiyasa:~/Desktop/practice$ ls
try.py
tiyasa@tiyasa:~/Desktop/practice$ touch try.py
tiyasa@tiyasa:~/Desktop/practice$ ls
try.py
tiyasa@tiyasa:~/Desktop/practice$ roscore
... logging to /home/tiyasa/.ros/log/11997f4e-7935-11eb-88bc-a1d5410aa8a4/roslaunch-tiyasa-8792.log
Checking log directory for disk usage. This may take a while.
Press Ctrl-C to interrupt
Done checking log file disk usage. Usage is <1GB.

started roslaunch server http://tiyasa:42219/
ros_comm version 1.15.9


SUMMARY
========

PARAMETERS
 * /rosdistro: noetic
 * /rosversion: 1.15.9

NODES

auto-starting new master
process[master]: started with pid [8807]
ROS_MASTER_URI=http://tiyasa:11311/

setting /run_id to 11997f4e-7935-11eb-88bc-a1d5410aa8a4
process[rosout-1]: started with pid [8817]
started core service [/rosout]
^C[rosout-1] killing on exit
[master] killing on exit
shutting down processing monitor...
... shutting down processing monitor complete
done
tiyasa@tiyasa:~/Desktop/practice$ 
