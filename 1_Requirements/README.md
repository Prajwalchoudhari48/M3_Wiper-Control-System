# Wiper Control System

# Introduction :
 
Windshield wipers play a key role during adverse weather conditions by wiping the rain continuously over the windshield area and provides a clear vision to the driver.A windshield wiper is a very important part that permits a driver to collect the visual information at the time of precipitation of rain from the vehicle components aspect that influences the driver's safety and comfort.

A wiper speed control system for an automobile wiper regulates the operating speed of a wiper in accordance with the amount of rain falling on the windshield. This is a very much essential component in each automobile as it avoids the risk of accidents during rainy conditions.

The goals of this project are to provide wiping systems for older cars, to improve the system by employing actuators and pull switches (using the same switch for multiple purposes by stepwise switching), and to regulate the engine and wiper speed with a single switch.

# Working Model :

- In this system, we will use a single switch to control the ignition button (on the motor) in the ACC position.

- Here the RED LED is considered at ACC position,once the push button is pressed this means the engine condition to be turned ON.
  The RED LED keeps glowing until the   engine ON.

- As press push button second time the RED,BLUE,GREEN LED's are flickering,indicating that the wiper system turned ON.

- By pressing push button third time the speed of wiper system change.Now the RED,BLUE,GREEN LED's flickering more faster than earlier.

- By pressing push button fourth time the motor is turned OFF.And the LED glow pattern stops on the 4th press.

- If the push button is pressed for 2 seconds continuously, the RED light goes off and the pattern stops bringing it to default position which signifies the engine   is turned OFF.



# Features :

- The three LED indicating the wiping operation.
 
- Wiping system is easy to use.
 
- STM32F407xx is efficient and contains innovative peripherals.

- Push Button is to do operation turning on,turning off,change the speed of wiper system.

# SWOT Analysis 
<img width="641" alt="image" src="https://user-images.githubusercontent.com/102716839/168243386-35f8ed9a-b348-45ce-b5b1-49e9d652bb01.png">





# 4'W and 1'H
-  WHY - To keep the windsheild clean enough to get clear vision view at all times.

-  WHAT - It is wiper control system which is generally depployed in all the automobiles in order to ensure safety for the drivers during raniy          
          conditions.

-  WHEN - It is recommended to operate during dust or rain.

-  WHERE - It is an system which is present in the windsheild of the vehicle.
 
-  HOW - It is implemented with the help of STM32 with the desired operation of changing odf speeds according to the rainfall intensity.

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
| LLR2| Pressed Button second time|LED Blue, Green Orange flickering alternative|Implemented|
|LLR3| Pressed Button third time |LED Blue, Green Orange flickering faster | Implemented |
|LLR4| Pressed Button fourth time |LED Blue, Green Orange flickering STOP | Implemented |
|LLR5| Hold Button for 2 secs | Turn off all LED's|Implemented|




