# teleop_twist_wiimote
Wiimote Teleop revised from Generic Keyboard Teleop for ROS  

#Install

To run:  
```
        sudo apt-get update    
        sudo apt-get install python-cwiid   
        mkdir -p ~/catkin_ws/src  
        cd catkin_ws/src  
        git clone https://github.com/bennergarrett/teleop_twist_wiimote
        cd ~/catkin_ws/src/teleop_twist_wiimote
        chmod +x teleop_twist_wiimote.py
        cd ~/catkin_ws  
        catkin_make
```
#Launch  
You need to make sure you have a roscore running.  


To run:  
```
         cd ~/catkin_ws  
         . devel/setup.bash  
         rosrun teleop_twist_wiimote teleop_twist_wiimote.py  
```
#Usage  

How to use wiimote button
push
```
Reading from the wiimote and Publishing to Twist!
This section needs updating....
---------------------------
Moving around:
   u    i    o
   j    k    l
   m    ,    .

For Holonomic mode (strafing), hold down the shift key:
---------------------------
   U    I    O
   J    K    L
   M    <    >

t : up (+z)
b : down (-z)

anything else : stop

q/z : increase/decrease max speeds by 10%
w/x : increase/decrease only linear speed by 10%
e/c : increase/decrease only angular speed by 10%

CTRL-C to quit
```

