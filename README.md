baxter_task1
============

baxter_task1
============

Output image: http://oi58.tinypic.com/bfl3z9.jpg
Demo Video: http://youtu.be/qluz3UOxYwg

The pose I choose is: 
position:
    x=0.599453313685
    y=-0.503064859716
    z=0.651817908576
Quaternion:
    x=0.232936069273
    y=0.0267983109097
    z=0.141009983728
    w=0.961841370837

I hardcoded this at line 80. The code then sends this pose to the inverse kinematic solver. It returns the joint solutions which is then use to move the arm to the input pose. It then returns to netural position. Forward kinematics is then called to move to the position using the following joint angles:

s0=1.1483870854498484
s1=-1.0868966198865189
e0=-1.004439818229912
e1=1.736092327168013
w0=0.6814574341307748
w1=-1.5707963705062866
w2=1.109226793287657

I subscribed to the end-effector topic to get the position outputs of the end-effector.
