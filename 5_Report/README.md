# Wiper Control System
 
Windshield wipers plays a key role during adverse weather conditions by wiping the rain unceasingly over the windshield area and delivers a clear image to the driver. A windshield wiper is a very significant part that authorizations a driver to collect the visual data at the time of precipitation of rain from the vehicle components aspect that influences the driver's safety and comfort.

A wiper speed control system for an vehicle wiper orders the functioning speed of a wiper in accord with the total rain falling on the windshield. This is a very much essential component in each automobile as it avoids the risk of accidents during rainy conditions.

The goals of this project are to provide wiping systems for older cars, to improve the system by employing actuators and pull switches (using the same switch for multiple purposes by stepwise switching), and to regulate the engine and wiper speed with a single switch.

# Working Model :

- In this system, we will use a single switch to control the ignition button in the ACC position.

- Here the RED LED is considered at ACC position, once the push button is pressed this means the engine condition to be turned ON.
  The RED LED keeps glowing until the   engine ON.

- As press push button second time the RED,BLUE,GREEN LED's are flickering ,indicating that the wiper system turned ON.

- By pressing push button third time the speed of wiper system change. Now the RED,BLUE,GREEN LED's flickering more faster than previous.

- By pressing push button 4th  time the motor is turned off. And the LED glow pattern stops on the 4th press.

- If the push button is pressed for 2 seconds continuously, the RED light goes off and the pattern stops bringing it to default position which signifies the engine  is turned off.



# Features :

- The three LED indicating the wiping operation.
 
- Wiping system is easy to use.
 
- STM32F407xx is efficient and contains innovative peripherals.

- Push Button is to do operation turning on, turning off, change the speed of wiper system.

# SWOT Analysis 
<img width="641" alt="image" src="https://user-images.githubusercontent.com/102716839/168243386-35f8ed9a-b348-45ce-b5b1-49e9d652bb01.png">





# 4'W and 1'H
-  WHY - To keep the windsheild clean to get clear vision view at all times.

-  WHAT - It is wiper control system which is generally deployed in all the automobiles in order to ensure safety for the drivers during rainy conditions.

-  WHEN - It is used to operate during dust or rain.

-  WHERE -Anywhere the user wants to use the feautures provided..
 
-  HOW - It is implemented with the help of STM32 with the desired operation of changing  speeds according to the rainfall intensity.

# Requirements

# High Level Requirements
| High Level Requirements  | Description | Status |
| ----|-----------|--------------|
| HLR1  |ACC Mode Operation | Implemented |
| HLR2  | Wiper ON | Implemented |
| HLR3  | Control the speed of Wiper|Implemented |
| HLR4  |Wiper OFF|Implemented |


# Low Level Requirements
| Low Level Requirements	  | Description |Status |
| ------------- | ------------- |-----------|
| LLR1 | Pressed Button once for 2 secs| RED LED ON | Implemented |
| LLR2| Pressed Button second time|LED Blue, Green Orange blinking alternative|Implemented|
|LLR3| Pressed Button third time |LED Blue, Green Orange blinking faster | Implemented |
|LLR4| Pressed Button fourth time |LED Blue, Green Orange blinking STOP | Implemented |
|LLR5| Hold Button for 2 secs | Turn off all LED's|Implemented|

# Design
# Block Diagram
<img width="597" alt="Block Diagram draw io" src="https://user-images.githubusercontent.com/102716839/168271987-cb441250-0cc6-4f36-96c2-6f330d2b22a6.png">

# Flow Diagram
![image](https://user-images.githubusercontent.com/102716839/168272822-3f968e20-901b-4deb-b5dd-23249817e91b.png)

# UML Diagram
![JUB](https://user-images.githubusercontent.com/102716839/168284705-0a721608-ebec-4856-b483-d16413c45bce.jpg)


# Test Plan And Output

## High Level Requirements
ID  | High Level Requirements
------------- | -------------

HLR1  | System shall display Ignition status of the car
HLR2  | System shall display wiper State-1 of the car
HLR3  | System shall display wiper State-2 of the car
HLR4  | System shall display wiper State-3 of the car

## Low Level Requirements
ID  | Low Level Requirements for HL1
------------- | -------------
LLR1.1  | According to the press of Button for 2 seconds, Ignition LED_RED shall be on
LLR1.2  | According to the press of Button for 2 seconds, Ignition LED_RED shall be off

ID  | Low Level Requirements for HL2
------------- | -------------
LLR2.1  | According to the press of Button all LED's shall be on in alternate fashion in Frequency(1Hz) indicating wiper movement
LLR2.2  | According to the press of Button all LED's shall be on in alternate fashion in Frequency(4Hz) indicating wiper movement
LLR2.3  | According to the press of Button all LED's shall be on in alternate fashion in Frequency(8Hz) indicating wiper movement

# Video
https://user-images.githubusercontent.com/102716839/168489267-f095de5f-86fe-4682-9cb9-ccabca00c300.mp4



