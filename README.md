# MobileRobot-Openloopcontrol
## Aim:

To develop a python control code to move the mobilerobot along the predefined path.

## Equipments Required:
1. RoboMaster EP core
2. Python 3.7

## Procedure

Step1:
Take the Ep core robot insert the battery and check the battery percentage

Step2:
Turn on the robot and connect the robot to the computer through WIFI

Step3:
Open visual studio and import robomaster package and do all the code

Step4:
Take the measurement of the track on each and every turn and gives the values trhough code in (m)

Step5:
Run the program to see the roboto movement

## Program
```python
from robomaster import robot
import time

if __name__ == '__main__':
    ep_robot = robot.Robot()
    ep_robot.initialize(conn_type="ap")

    ep_chassis = ep_robot.chassis

    ## Write your code here



    
    ep_robot.close()
```

## MobileRobot Movement Image:

![IMG_3034](https://github.com/STANLEY-13/mobilerobot-openloopcontrol/assets/148198816/8b3b9430-c11b-4fdd-9501-2dddc3114b9e)
![IMG_3034](https://github.com/STANLEY-13/mobilerobot-openloopcontrol/assets/148198816/3bfc6402-4ae2-4f91-9fac-ea41be734898)





<br/>
<br/>
<br/>
<br/>

## MobileRobot Movement Video:


https://youtube.com/shorts/WErbTIDquM0?feature=shared

<br/>
<br/>
<br/>
<br/>

## Result:
Thus the python program code is developed to move the mobilerobot in the predefined path.


<br/>
<br/>

```
Mobile Robotics Laboratory
Department of Artificial Intelligence and Data Science/ Machine Learning
Saveetha Engineering College
```
