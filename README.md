# Bluetooth-RC-car
This project focuses on exploring motor drivers and integrating various electronics such as the motor driver, arduino, sensors, bluetooth module, etc.<br/><br/>
Project video link : https://www.youtube.com/watch?v=uCdktF-sXIw

**Parts used :** <br/>
1. 2x L298N motor driver
2. 1x Arduino
3. Jumper wires
4. 1x Ultrasonic sensor
5. 4x DC motors
6. 1x HC-05 bluetooth module
7. 2x 9V batteries (or 3x, one to power arduino)
8. Suitable chassis for the project

Additional feature : Car has obstacle detection and automatically breaks when it is less than 10cm from an obstacle. only allows reverse and turning in this situation

# L298N - Working principle 
<img width="750" height="500" alt="image" src="https://github.com/user-attachments/assets/43704595-77e1-411b-a9e3-f6df02c8e356" /><br/>
L298N motor driver works on dual H-Bridge concept. The H-bridge allows for current to flow in both directions through the motor thus allowing you to control direction of rotation through a signal.<br/><br/>
<img width="761" height="1024" alt="image" src="https://github.com/user-attachments/assets/9a9a7e60-98f2-4940-9b93-4be4d28acf8b" /><br/>
The signal controls which switches are on and off in the H-Bridge. Giving a signal through IN1 will switch on both S1 and S4, whereas giving a signal through IN2 will trigger both S2 and S3, thus changing direction of flow of current and hence changing the motor rotation (In practice these switches are MOSFETs, two P type and two N type).

# Project Showcase 
![0](https://github.com/user-attachments/assets/05f28be9-fddc-40df-8195-fdaf5e03836f)<br/><br/>

![0](https://github.com/user-attachments/assets/1bcc30cf-64ef-49e0-aac4-d3839ea1f97c)<br/><br/>

![0](https://github.com/user-attachments/assets/18b98e93-b091-4e29-b0c2-45370b0a8f39)<br/><br/>
