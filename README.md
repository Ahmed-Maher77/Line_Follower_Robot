![Line-Follower-Robot-Using-Arduino](https://github.com/Ahmed-Maher77/Line_Follower_Robot/assets/112467034/a40691a1-ee9a-449c-bcaa-9fada22d6df6)

# Line Follower Robot
The Line Follower, which utilizes Arduino, is a straightforward robot design. Its primary objective is to identify black lines with the aid of two IR sensors and navigate the robot by employing the L298N motor driver module.

The Line Follower is a robot built using Arduino. It functions by utilizing an IR sensor to navigate along a predetermined line. The IR sensor consists of two diodes: one diode emits infrared light, while the other diode receives the reflected light from the surface. When the emitted infrared rays encounter a white surface, they bounce back to the sensor. Conversely, when the infrared light hits a black surface, it is absorbed, leading to no reflected rays reaching the sensor's photodiode. The sensor measures the intensity of the reflected light and transmits this value to the Arduino. Additionally, the sensor includes a potentiometer that enables the adjustment of sensitivity.

Based on the data received from the sensor, the Arduino makes decisions to guide the robot's movements. If the sensor detects no black line, the robot continues moving forward. However, if the left sensor detects a black line, the robot turns right, and if the right sensor detects a black line, it turns left. The robot halts when both sensors simultaneously detect a black line.

#####Here is a list of the components required for this project:

* 1x Arduino Uno
* 1x L298N motor driver module
* 2x IR sensors
* 14x wires
* 1x Plexi (measuring 10cm x 17cm)
* 2x TT motors
* 6x AA batteries
* 1x Battery holder
* 8x 10mm metal spacers
