# 6-DOF-Stamping-Robot

## utils.py
Includes function whose inputs are (X,Y,Z,THETA_DEG) coordinates measured from the center of the 1st joint axis on top of the motor
*THETA_DEG is the angle of the object detected with Object Detection methods

and then outputs the joint angles of all the motors put the end-effector onto that point

**Constraints:
- The stamping must be vertical. Hence end-effector direction should always point vertically downwards
- Some other geometrical constraints pertaining to the motor
