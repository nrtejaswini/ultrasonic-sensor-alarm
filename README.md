# Ultrasonic-Sensor-Alarm
This project uses an ultrasonic sensor which detects objects or individuals within a specific range with accuracy of 90%, triggering an alarm or alert for reliable intrusion detection or object monitoring in restricted areas. 

**Introduction:**

Population increase, lifestyle changes and economic development has led to increase in human 
activity and hence high demand of manpower and especially in cities all over the world. For example, 
there is an increasing need to employ security officers at the gates to monitor the movement of people 
which might be intruders, traffic police in highways to monitor traffic, automatic doors and many 
others. Use of human to sense motions and other human activities is prone to human error and many 
limitations.
This project introduces us to the HC-SR04 Ultrasonic Sensor. These sensors are designed for noncontact detection of solid or liquid objects. An ultrasonic sensor works by emitting sound waves at a 
frequency too high for humans to hear. They then wait for the sound to be reflected back, calculating 
distance based on time required. This is similar to how radar measures the time it takes a radio wave 
to return after hitting an object. We will understand how an ultrasonic sensor works and how to 
interact with it in code. This is a very handy addition to an IoT project for obstacle avoidance. This 
ultrasonic sensor can be found in automobile self-parking technology, Anti-collision safety systems, 
robotic obstacle detection systems, monitoring the level of water in a tank etc.
In this project we will be building an alarm circuit which incorporates a piezo buzzer and LEDs (red 
and green) to warn when an object has been detected or comes within a specified range of the 
ultrasonic sensor. When the object is too close, the buzzer will go ON and red light will be lit. Once 
no obstacle is detected, the grreen light tells us we are doing OK. We will be displaying the conditions 
in the serial monitor. We will also be introduced to pulse in function and how it is used in conjunction 
with the ultrasonic sensor to perform measurements critical to the operation of the circuit. The pulse 
function is used to measure the time between when a waveform is sent from the ultrasonic sensor 
until the time it is received.

**Objective:**

In this project we will learn about:

• How an ultrasonic sensor (HC-SR04) works?

• The pinout and how to connect an ultrasonic sensor in a circuit with Arduino.

• How the pulseln () function works?



**Software requirements:**

• Arduino IDE with included libraries.

**Hardware requirements:**

• Arduino UNO

• Ultrasonic Sensor (HC-SR04)

• Resistors- 220ohms

• LEDs

• Buzzer

• Jumper wires

• Breadboard

**Conclusion**
In this study, a tool to detect motion of objects, and produce a sound alarm by piezo buzzer and also 
light by LEDs are assembled. The circuit connection and program with Arduino microcontroller chip 
to run the circuit are performed. The ultrasonic sensor was able to send ultrasonic sound waves to the 
approaching object and the alarm sound from the piezo buzzer was produced by showing the warnings 
with the help of LEDs. This tool can be customized to fit various applications such as door alarms, 
to measure the level of waters in tank, for guiding the visually impaired person and so on.
