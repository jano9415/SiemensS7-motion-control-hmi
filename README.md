# SiemensS7-motion-control-hmi
In this project I use a Siemens servo motor to move an axis.
The servo motor can be controlled manually in five different ways.

Home: controlling to the home position.

Jog: controlling forward or backward while pushing the button Jog+ or Jog-

Move with velocity: controlling with a constant velocity forward or backward.

Relative move: controlling with a value forward or backward from the previous position to the new position.

Absolute move: controlling forward or backward to a certain position.

The position of axis is 0:
![Image14](https://github.com/user-attachments/assets/e308db97-479c-4e3d-a04a-5b9698ad64f3)


The axis moves forward with velocity 18 after typing 18 in the velocity input field and clicking Velocity ON button:
![Image15](https://github.com/user-attachments/assets/7b5a9dcb-7d36-400b-be4c-ff9c6512960b)

The axis moves from home position to position 164 after typing 164 in the absolute input field and clicking Absolute ON button:
![Image16](https://github.com/user-attachments/assets/90cd8461-de28-4347-ac61-bc32c251b593)

The axis moves from position 164 to position 146 after typing -20 in the relative input field and clicking the Relative ON button:
![Image17](https://github.com/user-attachments/assets/28c3bb0f-5084-4a04-8f61-d2808bea6966)

Automatic mode:
![Image18](https://github.com/user-attachments/assets/10aeb422-a42d-450a-9ee3-4b3c5a0cbffc)
There is Sensor1 to detect the product on the conveyor and Cylinder1 attached to the axis to grab the product.

If the Sensor1 detects the product the axis is moved to position 251. The absolute value variable is set 251 and execute absolute move variable is set true.
![Image19](https://github.com/user-attachments/assets/51cce9f4-1409-4fe2-9178-9b82488aca2a)

If the axis reached position 251 and Sensor1 is active, Cylinder1 moves forward to grasp the product:
![Image20](https://github.com/user-attachments/assets/e0dba987-59e4-45c4-8a08-9560df5ccc04)

If the position of axis is 251 but Sensor1 is not active, Cylinder1 doesn't move:
![Image22](https://github.com/user-attachments/assets/08b97ac8-190f-48b7-964c-2bd51d5ed0fb)













