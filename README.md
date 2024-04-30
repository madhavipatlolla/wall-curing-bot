# Wall_Curing_Bot

To automate the process of curing concrete. Curing plays an important role in the strength development and durability of concrete. The project provides an efficient way to cure concrete inside of the building during the construction which reduces the labour and time

## Introduction
Curing is the process of controlling moisture loss from concrete that has already been placed. Curing ensures the hydration of the cement, which in turn enhances its strength and durability. Curing takes place immediately after placing the concrete and deals with the maintenance of the desired temperature and moisture for extended periods. Proper curing helps to prevent grazing, dusting, surface disintegration and scaling. Adequate curing reduces shrinkage, gives better resistance to wear and improves long-term appearance. To automate this process of curing in the purpose of this project.

## Problem Statement
A lot of manpower and time is invested in curing concrete during construction. The time spent in curing can be directed elsewhere if the process of curing is automated. This project aims to automate the process of curing concrete. 

## Images of the Bot
|![PI-image1](https://github.com/Kbc981/Wall_curing_bot/assets/162048469/30ebd911-270d-45cf-a7b1-2d880ab8316e)
![PI-image2](https://github.com/Kbc981/Wall_curing_bot/assets/162048469/80836559-5434-4793-9f39-fe941d85cbb6)
|---|---|

|||

## Working Video

### During Setup we enter the dimensions and then set the bot with minimum distance to the wall.
https://github.com/Kbc981/Wall_curing_bot/assets/162048469/496c21ed-275e-4445-9ecd-15842b3c5741



### At the corner take a turn and spray Full Wall
https://github.com/Kbc981/Wall_curing_bot/assets/162048469/cac8f049-d224-43d9-9a1b-34a6d0223bcf



### When there is no Wall, it will spray only at the top
https://github.com/Kbc981/Wall_cur![schematic-diagram-PI](https://github.com/Kbc981/Wall_curing_bot/assets/162048469/8ffceb33-682c-462d-a40e-83e547eff310)
ing_bot/assets/162048469/c3737533-9077-4eb1-98ba-58202b16e200



## Circuit Diagram

## Working
The working of the Wall Curing Bot is simple. First, it takes input from the user about the number of sides in the room and the dimensions of each side. After taking the input, the bot starts moving using the ultrasonic sensors to sense the wall and while moving it cures the wall using the pipe attached to it by moving the water pipe vertically up and down twice. After a single revolution, the bot halts and its function is fulfilled.

## Source Code 
Check the file uploading in this repository

## Component List
|S.No|Name|Quantity|Price(in Rupees)|
|---|---|---|---|
|1|Arduino Mega|1|1000|
|2|Servo Motor|1|100|
|3|HCSR04 ultrasonic sensor|3|195|
|4|Holders for HCSR04|3|125|
|5|L298N motor driver|2|240|
|6|LCD DISPLAY 16X2|1|120|
|7|4x4 Keypad|1|70|
|8|12v DC motor|4|560|
|9|Chasis|1|220|
|10|Speed Measuring Sensor|1|40|
|11|5V 1 Channel Relay|1|80|
|12|Submersible Mini Water Pump 12v DC|1|70|
|13|Buzzer|1|20|
|14|Wheels|4|300|
|15|12V 1.2Ah Rechargeable Sealed Lead Acid Battery|1|600|

## Future Enhancements
1. We can Add a more powerful motor to that can cure the outer part of the building.
2. Replace the Ultrasonic Sensor with a sharp IR Sensor for faster sensor reading and add more sensors for better movement.
3. Add a LIDAR system for Mapping the room and use that for navigation.

## Project details:
This is the project titled **‘Wall Curing Bot’** by **P. Aarushraj, P. Madhavi, M. Ankitha, K. Bharath chandra and B. Rajmohan**. 
This is a record of the project work carried out by us, during the year **2022-2023** as part of **POST INDUCTION** under the guidance and supervision of **Mr D.P. Naga Ajay Kumar & Ms P. Tapaswini** (Technical Heads) and **Mr T. Bharat Kumar** (The President of THE ROBOTICS CLUB)
