# Automatic-Insulin-Pump-System
## Introduction
* Diabetes Mellitus (DM), which is usually referred to Diabetes, is a worldwide chronic metabolic disorder that involves abnormal blood glucose levels, which can cause diverse health disorders that affect their heart, weakness, and dizziness, while too much can lead to vision and nerve problems, kidney disease, and strokes. Either situation can eventually lead to death Due to these conditions.
## Problem Defination
* With the high rates of diabetes and increasing the rates of health disorders that affect their heart, headaches, weakness, and dizziness, while too much can lead to vision problems and kidney disease. Either situation can eventually lead to death. 
* diabetes patients have traditionally checked blood glucose levels through self-monitoring of blood glucose techniques, like pricking their fingers multiple times per day. Such techniques involve a number of drawbacks
## System's Functionalities
* User can analyze data to monitor the glucose in blood by using the application.
* User takes suitable dose of insulin by the insulin pump
* Warning user when his glucose rate exceeds the normal range by the application
* The doctor monitors the blood glucose level of his patients weekly and sends them reports if possible.
* System can help type one diabetes only.
## System Architicture
### Hardware Architecture
![alt text](https://github.com/abdelrahmanbaher4/Automatic-Insulin-Pump-System/blob/main/Presentation/Picture1.jpg)
### Software Architecture
![alt text](https://github.com/abdelrahmanbaher4/Automatic-Insulin-Pump-System/blob/main/Presentation/SW.png)
### Class Diagram 
![alt text](https://github.com/abdelrahmanbaher4/Automatic-Insulin-Pump-System/blob/main/Presentation/ClassDIagram.jpg)
### Use Case
![alt text](https://github.com/abdelrahmanbaher4/Automatic-Insulin-Pump-System/blob/main/Presentation/Use%20Case.jpgg)
### DataBase 
* Firebase database is a set of collections
* Each collection has a set of documents andEach document contains a set of sub collections and fields, etc
* User and Doctor are collections , Glucose and Reports are sub collections in every user 
![image](https://github.com/abdelrahmanbaher4/Automatic-Insulin-Pump-System/blob/main/Presentation/DB.png)
## System Design & Implementation
###  Pumping Circuit Design
![image](https://github.com/abdelrahmanbaher4/Automatic-Insulin-Pump-System/blob/main/Presentation/PumpCircuit.png)
## Movement
![image](https://github.com/abdelrahmanbaher4/Automatic-Insulin-Pump-System/blob/main/Presentation/Gear.png)
* Y = RGear x θ 
* Area of cylinder = π x Rsy
* Volume = Area of cylinder x Y
* When the servo rotates the gear of radius RGear with angle θ, the gear will move distance Y on the rack.
As the syringe is a cylinder then its area is π x RSyringe2 and then the amount of the insulin dosage is equal to syringe area x.
So, to get the amount of the dosage required we will calculate the angle of servo rotation as the other constraints are constants.
## Application :-
![image](https://github.com/abdelrahmanbaher4/Automatic-Insulin-Pump-System/blob/main/Presentation/App_start.jpg)
* flutter application is connected to firebase database to make it easier for the user to monitor the level of sugar and units that have been taken in each measurement and warn him when his blood sugar is high or low.
## Tools 
### Software Tools
* Android Studio , Firebase                         
* Arduino IDE
* Solidworks!
### Hardware Tools
* Arduino Nano
* Servo motor
* LCD 16*2
* Buzzer
* Bluetooth Module
* Max471”Current & Voltage sensor”
* Battery & Im2596!
## In Conclusion This project aims to make a complete system for all the diabetes to make them deal with their problem in easier way by: 
calculating the appropriate dose for the patients by the insulin pump and the application can monitor their glucose in blood.
helping the diabetes to take their suitable dose of the insulin in  the correct time.

## Project Demo
### Sign Up and Login Pages 
![alt text](https://media.giphy.com/media/uK5bcZ36ol5UPcjzI6/giphy.gif)
### Handling Patient 3 Cases 
* Normal Case : if the Blood Sugar between 80 and 120 , Nothing Happens
* Very low case : if the Blood Sugar is less than 80 , a buzzer sound keeps beeping , and the app sends a notification to eat some sugars .
* High case : if the Blood Sugar is above 120 , a buzzer sound keeps beeping . 
![alt text](https://media.giphy.com/media/YLaIfQ2WAIOJCzVt03/giphy.gif)



