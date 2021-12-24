# AndroidControlledCar
 TABLE OF CONTENTS
CERTIFICATE ii DECLARATION iii ABSTRACT v GLOSSARY vii LIST OF FIGURES ix
PROJECT DESCRIPTION
  1.0 INTRODUCTION 2 2.0 PURPOSE OF THE PROJECT 2 3.0 SYSTEM DESIGN 3 4.0 ADVANTAGES OF THE PROPOSED SYSTEM 4 5.0 METHODOLOGY AND PLANNING 4
a. MODULES’ DESCRIPTION     4
 6.0 TEAMWISE DISRIBUTION OF WORK 5 7.0 INNOVATION IN THE PROJECT 5-9
 a. IDEA OF THE PROJECT 5 b. CIRCUIT DIAGRAM 6 c. CIRCUIT DIAGRAM WORKING PRINCIPLE 6
    8.0 CONCLUSION 7 9.0 IMPLEMENTATION 7-13
 a. Project Step Map   7-8 b. ANDROID APP 9-10
i. ApprunninginaSmartphone     9-10
i. NODE-MCU   11 ii. NODE-MCUFRONTVIEW   11 iii. AndroidControlledCarModel   12
c. HARDWARE SETUP     11-2
   10.0 SOFTWARE& HARDWARE REQUIREMENTS 12-14
 a. HARDWARE REQUIREMENTS 12-13 b. SOFTWARE REQUIREMENTS 14
c. POWER CONSUMPTION OF THIS DEVICE 14
    11.0 BIBLIOGRAPHY AND REFERENCES   15
vi![WhatsApp Image 2021-11-27 at 8 34 29 PM (1)](https://user-images.githubusercontent.com/78377154/147363671-fefa6bce-fa31-4004-97dd-876a77412a61.jpeg)
![WhatsApp Image 2021-11-27 at 8 34 29 PM](https://user-images.githubusercontent.com/78377154/147363675-d6eb03ad-b484-47cc-91f8-41dbc005c398.jpeg)
![WhatsApp Image 2021-11-27 at 8 37 08 PM](https://user-images.githubusercontent.com/78377154/147363676-674267b6-35f7-4f45-8523-16777b2477a3.jpeg)

 GLOSSARY
ANDROID STUDIO: Android Studio is the official Integrated Development Environment (IDE) for Google’s Android Operating System and Android App Development, based on JetBrains IntelliJ IDEA.
ARDUINO: Arduino is an open-source hardware and software company, project, and user community that designs and manufactures single-board microcontrollers and microcontroller kits for building digital devices.
AUTOMATION: Automation is the technique of making an apparatus, a process, or a system operate automatically. Automation is a term for technology applications where human input is minimized. This includes business process automation (BPA), IT automation, personal applications such as home automation, and more.
ESP8266: ESP8266 is a microcontroller with Wi-Fi capability. It requires external flash memory and some antenna to work. There are different modules and development boards with this system. Some development boards use basic esp8266 modules and some integrate the chip and flash memory on the PCB.
INTERNET: The Internet is a global wide area network that connects computer systems across the world. It includes several high-bandwidth data lines that comprise theInternet"backbone." These lines are connected to major Internet hubs that distribute data to other locations, such as web servers and ISPs.
JUMPER WIRES: Jumper wires are simply wires that have connector pins at each end, allowing them to be used to connect two points without
vii

 soldering. Jumper wires are typically used with breadboards and other
prototyping tools to make it easy to change a circuit as needed.
NODE-MCU: Node-MCUis an open-source development board that adds required circuits around the module - boot configuration pull-up and pull-down and enable pin pull-up. On the board is a USB chip to connect the esp8266 to USB and an auto-reset circuit to enable the upload tool to put the esp8266 into flashing mode. The 3.3 V power for the esp8266 is converted from the 5 V of USB. The name "NodeMCU" combines "node" and "MCU" (micro-controller unit).
PROTOTYPING BOARD: It is a thin, rigid sheet with holes pre-drilled at standard intervals across a grid, usually a square grid with spacing. These holes are ringed by round or square copper pads.
SENSOR: A sensor is a device that detects and responds to some type of input from the physical environment. The specific input could be light, heat, motion, moisture, pressure, or any one of a great number of other environmental phenomena.
SMARTPHONE: A Smartphone is a mobile phone that includes advanced functionality beyond making phone calls and sending text messages.
WIFI: Wi-Fi is a wireless networking technology that allows devices such as computers (laptops and desktops), mobile devices (smart phones and wearable’s), and other equipment (printers and video cameras) to interface with the Internet.
 viii

 LIST OF FIGURES INNOVATION IN THE PROJECT
   Fig.1: IDEA OF THE PROJECT 5
 Fig.2: CIRCUIT DIAGRAM 6
   ANDROID APP
  Fig.3-7: App running in a smart phone 9-10
  HARDWARE SETUP
  Fig.8 : Node MCU 11
 Fig.9 : Node MCU Front View 11
 Fig.10 : Android Controlled Car Model 12
  ix

   PROJECT DESCRIPTION
 
 1.0 INTRODUCTION
 Nowadays smart phones are becoming more powerful with reinforced processors, larger storage capacities, richer entertainment function and more communication methods. Wi-Fi is mainly used for data exchange to add new features to smart phones. Wi-Fi technology, created by telecom vendor Ericsson in 1994, shows its advantage by integrating with smart phones. It has changed how people use digital device at home or office, and has transferred traditional wired digital devices into wireless devices. A host considering its normal working area of within eight meters, it is especially useful in home environment. Thanks to technology and other similar techniques, with dramatic increase in Smartphone users, smart phones have gradually turned into an all-purpose portable device and provided people for their daily use. In recent years, an open-source platform Android has been widely used in smart phones. Android has complete software package consisting of an operating system, middleware layer and core applications. Different from other existing platform like iOS (iPhone OS), it comes with software development kit (SDK), which provides essential tools and Application. Using a Smartphone as the “brain” of a robot is already an active research field with several open opportunities and promising possibilities. In this report I present a review of current robots controlled by mobile phone and discuss a closed loop control systems using audio channels of mobile devices, such as phones and tablet computers. In my work, move the robot upward, backward, left and right side by the android application such as Arduino Wi-Fi Car.
2

 2.0 PURPOSE AND OBJECTIVES OF THE PROJECT
The main objective of this project is to present the overall design of an Android Controlled Car with a low-cost and wireless system, with an android interface, arduino bot and a program in to the arduino microprocessor.
Remote-controlled cars are one of the most popular toy products currently on the mass market. Each series of car has a specific remote-control unit. This presents the consumer with a critical problem; obtaining a substitution controller where the original control unit has broken down. In this work a robot based on an external Arduino microcontroller, controllable by an Android application via Wi-Fi, which can be recommended as a prototype for the combination of embedded systems with Android mobile devices is investigated.
3.0 PROJECT DESIGN OF THE PROPOSED SYSTEM
Nowadays, we have remote controls for our television sets and other electronic systems, which have made our lives easy. Have you ever wondered about android controlled cars that would give the facility of controlling a car using an android app? Off-course, Yes! But, are the available options cost-effective? If the answer is No, we have found a solution to it. We have come up with a new system called Android Controlled Car. This system is super-cost effective and can give the user, the ability to control any electronic device without even spending for remote control. This project helps the user to control the car using his/her Smartphone. Time is a very valuable thing. Everybody wants to save time as much as they can. New technologies are being introduced to save our time. To save people's time we are introducing car control using Wi-Fi.
  3

 4.0 ADVANTAGES OF THE PROPOSED SYSTEM
1. LesserMaintenancerequired.
2. Small parking area required to Reduce parking difficulties.
3. Reduce human effort.
4. Controlcarfromoutside.
5. Easy to control car in off-road
6. Easy to install and low cost.
7. Manuallyoperatable
8. This project can be modified quite easily
9. User-friendlyGUI
10.Open Source Software
11.Control: Guardians/parents can set an alarm on their phones which would help
to control the time spent by their kids while playing with the device. 12.Convenience: No requirement of a separate remote to use the car.
5.0 METHODOLOGY/ PLANNING OF WORK
Various smart ideas are used for implementing android control over cars such as directional controls, gears, views, movement controls, graphic instructions, and various sensors. A wireless network is used for controlling the sensors and the car from a mobile phone so that it becomes convenient for users to use and control the car without a specific car remote.
 a. MODULE AND TEAM MEMBER WISE DISTRIBUTION OF WORK
 MODULES’ DESCRIPTION:
 1. Android App: An android based app will be designed to control the car that would be connected to Node-MCU via Wi-Fi.
  2. Hardware Setup: A setup to connect the car with Arduino, Node MCU using Motor, and to set up a wireless network using Wi-Fi.
  3. Arduino Programming: To automate the functioning of the car from the commands through an Android cell phone.
4

 6.0 TEAM MEMBER WISE WORK DISTRIBUTION
  ⮚ Research and Analysis: Akash Rana
⮚ Android App: Arshi Nagpal
⮚ Hardware Setup: Saurabh Kumar
⮚ Arduino Coding: Akash Rana
⮚ Functional verification and Testing: Saurabh Kumar
7.0 INNOVATION IN PROJECT/DESIGN/SOLUTION
eatures. An ntroller and to supervise act with the ly complied after proper to create an the arduino the arduino for various
   a. The idea of the project
   Fig1. : Idea of the project
Arduino car contains arduino microcontroller with basic mobility f Arduino program contains instructions mediating between android co Arduino car. Android mobile controller uses different mobile sensors motion. An appropriate program in the arduino microprocessor to inter android controller has to be created. The program has been successful through arduino IDE to the arduino microprocessor & loaded in to it checking of logic to decrease any loss/damage of hardware. We have android application that will provide user an interface to interact with powered car. The interface is easy to use and provide feedback from microprocessor through Wi-Fi after giving instruction to arduino
  
 actions through interface via Wi-Fi module. The android application is to be created with the help of android.
 b. Circuit Diagram
  Fig.2: Circuit Diagram
 c. PROPOSED CIRCUIT WORKING PRINCIPLE
1. The whole apparatus connected to hand-off is controlled by Microcontroller.
2. ESP8266 is a Wi-Fi module interface to Microcontroller for remote
correspondence.
3. We have made a web server utilizing ESP8266 and screen all progressions
using controlling transfers.
4. There is a site page that can be accessed through any gadget associated with
home Wi-Fi .we can switch it by ON/OFF with that page can be accessed by putting the IP address of ESP8266.
6

 5. When we turn ON or OFF the catch from the web server Wi-Fi switch offers to summon to Wi-Fi module and after that, it offers charge to Microcontroller.
  8.0 CONCLUSION
 This has been a brief review of several wireless technology usages that might be used to control mobile robots. It is important to compare this technology and the bandwidth, frequency, data rate to transfer data among the devices for better development for mobile robot controller. All we need to do is to focus on how to bring the different characteristics of all the wireless technologies together in one portable application. Selection of wireless technologies depends on the type of application to be developed considering the following; range, frequency and data rate.
 9.0 IMPLEMENTATION
 a. Project Step-Map  Building the car
  The first step is to build the car. Basically, you have to assemble the chassis with 2 motors, connect the controller and the motor controller, and add battery.
This is the most interesting part because anyone can customize the car by adding new features.
 Upload the code into your controller
The second step is to program your microcontroller in order to serve an HTTP server. The microcontroller would be able to control the rotation of each motors according to the request received. We decided to implement GET instead of POST request because the server will not return the state of the car.
7

We have made 2 scripts AP and STA modes. In AP mode, the microcontroller will create its own Wi-Fi network and serve the HTTP server. In STA mode, the microcontroller will connect to an existing network and server the HTTP server. In both case, you need to know the IP Address of your microcontroller.
 Configure your mobile application
An android app to be developed to control the car, with customized commands.
Connect the Smartphone to the same Wi-Fi network as the car. Make sure that the application parameters are correct (IP, PORT, etc.).
How it works
  We are using HTTP protocol.
 The server is the ESP8266 and the client is the Smartphone. The client will send
HTTP requests to the server in order to control the car.
 ESP8266 chip is able to create its own WI-FI network (Access Point mode = AP) or to connect to an existing Wi-Fi network (Station Mode = STA). It is also possible to deploy a HTTP server.
 To make it simple, the Smartphone must be connected to the same Wi-Fi network as the chip and know its IP address and the port of its server.
 The user will interact with the buttons of the mobile application to control the car.
 To make it simple, the Smartphone must be connected to the same Wi-Fi network
as the chip and know its IP address and the port of its server.
 The user will interact with the buttons of the mobile application to control the car.
   8

 b. Android App
      9

      Fig.3-7: App running on a Smartphone
10

 c. Hardware Setup
      Fig.8: Node MCU Fig.9: Node MCU Front View
 11

   Fig.10: Android Controlled Car Model
10.0 HARDWARE AND SOFTWARE REQUIREMENTS
 a. HARDWARE REQUIREMENTS 1. NODE-MCU (lolin esp8266 v1.0)
  circuits around the module - boot configuration pull-up and pull-down and enable pin pull-up. On the board is a USB chip to connect the esp8266 to USB and an auto-reset circuit to enable the upload tool to put the esp8266 into flashing mode.
Node-MCU is an open-source development board. that adds required
 2. Prototyping board (Breadboard)
  grid, usually a square grid with spacing. These holes are ringed by round or square copper pads.
It is a thin, rigid sheet with holes pre-drilled at standard intervals across a
12

 3. Jumper Wires and Connecting wires
 Jumper wires are simply wires that have connector pins at each end,
allowing them to be used to connect two points without soldering. Jumper wires are typically used with breadboards and other prototyping tools to make it easy to change a circuit as needed.
  4. Smartphone or tablet (Wifi enabled)
  A smartphone is a mobile phone that includes advanced functionality
beyond making phone calls and sending text messages.
 5. 5V Power Source
  5V power supplies (or 5VDC power supplies) are one of the most
common power supplies in use today. In general, a 5VDC output is obtained from a 50VAC or 240VAC input using a combination of transformers,
diodes, and transistors.
 6. Sensors
  the physical environment. The specific input could be light, heat, motion, moisture, pressure, or any one of a great number of other environmental phenomena.
A sensor is a device that detects and responds to some type of input from
13

 b. SOFTWARE REQUIREMENTS  Arduino 1.8.5 compiler
 The Arduino Integrated Development Environment (IDE) is the main
text editing program used for Arduino programming. The IDE translates and compiles your sketches into code that Arduino can understand. Once your Arduino code is compiled it is then uploaded to the board's memory.
   Android Studio
 Android Studio is the official Integrated Development Environment (IDE) for Google’s Android Operating System and Android App Development, based on JetBrains IntelliJ IDEA.
 c. POWER CONSUMPTION OF THIS DEVICE:
 This device works between 5.09 Volt and 5.21 Volt
 And consume power between 0.07A and 0.30A
14

11.0 BIBLIOGRAPHY
1. http://developer.android.com/training/index.html
2. http://stackoverflow.com/
3. Awab Fakih, JovitaSerrao, “Cell Phone Operated Robotic Car” International
Journal of Scientific and EngineeringResearch, ISSN 2229-551.
4. Gupta, Sabuj Das, ArmanRiaz Ochi, Mohammad SakibHossain, and NahidAlamSiddiqi“Designing & Implementation of Mobile Operated Toy Car by DTMF” International Journal of Scientific & Research Publications,
Vol-3, Issue-1, 2013 ISSN 2250-3153.
5. Jadhav, Ashish, Mahesh Kumbhar and MeenakshiPawar” Cell Phone
Controlled Ground Combat Vehicle” International Journal of Computer and Communication Engineering, Vol.1, No.2, July 2012.
  
6. Bischoff, R., and Graefe, V., “HERMES - a versatile personal robotic assistant,” Proceedings of the IEEE, vol. 92, pp. 1759-1779, 2004.
7. Andrey A. Loukianov, Hidenori Kimura, Masanori Sugisaka. “Implementing distributed control system for intelligent mobile robot” 8th International Symposium on Artificial Life and Robotics, Oita, Japan, January 24– 26 2003,
8. Marcelo B. Perotoni , Beatriz E. Garibello, Silvio E. Barbin “ An IEEE802.11 Low Cost Planner Antenna for a Mobile Robot”, 2006.
15
