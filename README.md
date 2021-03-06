# Ball_bot
* This reopsitory contains __Gazebo simulation of Ball_bot__, a shepere shaped throwable robot with compact size and radius-deforming wheels.
* Covered urdf and gazebo.

<center><img src="https://github.com/SeunghyunLim/Ball_bot/blob/master/img/design_ball.PNG" alt="drawing" width="720"/></center>
<center><img src="https://github.com/SeunghyunLim/Ball_bot/blob/master/img/design_wheel.PNG" alt="drawing" width="720"/></center>

| Ball_bot in Gazebo9 | Overcoming obstacle |
|---|---|
|<center><img src="https://github.com/SeunghyunLim/Ball_bot/blob/master/img/ball_bot.png" alt="drawing" width="285"/></center>|<center><img src="https://github.com/SeunghyunLim/Ball_bot/blob/master/gif/ball_bot.gif" alt="drawing" width="385"/></center>|

<center><img src="https://github.com/SeunghyunLim/Ball_bot/blob/master/img/variable_bots.png" alt="drawing" width="720"/></center>

## Dependencies
- Ubuntu 18.04
- ROS melodic
- Gazebo 9
- linux-headers-generic
- ros-melodic-turtlebot3-*


## Installing
On your catkin_ws/src,
```
git clone https://github.com/SeunghyunLim/Ball_bot.git
```
and 'cd ~/catkin_ws && catkin_make'

## Run
for launching Gazebo,
```
roslaunch Ball_bot ball_bot.launch
```
for teleop keyboard,
```
roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch
```

## Rviz visualization
```
rviz -d ball_bot_rviz.rviz
```
