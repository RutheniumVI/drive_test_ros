# drive_test_ros

Place the 2 folders above in you catkin workspace, seperately. After running a catkin_make, you can now try the simulation.
First launch the simulation world by typing this in your terminal:
```
roslaunch simulation test_world.launch 
```
then after making the python script in drive_test an executable by using:
```
chmod +x drive_cotnrol.py
```
launch it in the terminal similarly using:
```
rosrun drive_test drive_control.py
```

Note you need to have gazebo_ros package installed.
