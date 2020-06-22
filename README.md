# ywj_turtlebot3
毕业设计仿真启动部分

#编译<br>
```
cd ywj_turtlebot3/<br>
catkin_make<br>
```

#运行<br>
```
source devel/setup.bash<br>
roslaunch turtlebot3_gazebo turtlebot3_stage_3.launch<br>
```
![image](https://github.com/seedjack/ywj_drl/blob/master/images/2020-06-22%2012-21-34%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE.png)

**注意:**

在turtlebot3/turtlebot3_description/urdf/turtlebot3_burger.gazebo.xacro文件中可以通过修改
***samples、min_angle***来修改激光的范围和维数
