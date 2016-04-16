---
layout: page
permalink: /projects/
---

# Projects

| [**Face expression detector using Support Vector Machine**](#face-expression-detector-using-support-vector-machine) |
| [**Design and Implementation of Soft processor on FPGA**](#design-and-implementation-of-soft-processor-on-fpga) |
| [**DSO Art (aka) Digital painter**](#dso-art-aka-digital-painter) |
| [**Magnetic Levitation System**](#magnetic-levitation-system) |
| [**LOCK**](#lock) |
| [**AeroThrust Pendullum using Arduino**](#aerothrust-pendullum-using-arduino) |
| [**Kiduino**](#kiduino) |

---

## **Face expression detector using Support Vector Machine**

<iframe width="560" height="315" src="https://www.youtube.com/embed/2ky_W649G-Q" frameborder="0" allowfullscreen></iframe>

<br />

* Facial landmarks were detected using dlib library and feature set was extracted from several face datasets.
* Training was done with the obtained feature set using several supervised learning models and their performances were analysed.
* An application was developed to identify the face expression of the person in an image using the trained model.

---

## **Design and Implementation of Soft processor on FPGA**
<h6> <em>Mentor - Prof. M.Senthil Kumaran (EEE/SSNCE) <br /> 
 Adithya S</em> </h6>

<iframe width="560" height="315" src="https://www.youtube.com/embed/f4_ktr4lO60" frameborder="0" allowfullscreen></iframe>

<br />

* Developed a soft microprocessor starting from a simple NAND gate with the help Xilinx system generator toolbox using matlab and implemented the design on Spartan 3E FPGA.
* Developed all the necessary sub-modules for programming and debugging the soft processor such as, the assembler, VGA interface driver, PS2 Keyboard interface driver.

---


## **DSO-ART (aka) Digital Painter**
<h6> <em>Mentor - Prof. M.Senthil Kumaran (EEE/SSNCE) <br /> 
 Adithya S, Mervin JB, Sibi Sankar, Sanjay Shreedharan</em> </h6>


![placeholder](/assets/images/dsoart.gif)



* Implemented mathematical functions on Spartan 3E FPGA and used PWM technique to display basic shapes
in a DSO.
* Developed a technique to display any given image in DSO with the help of image processing and python.

##### *Checkout the blog post about this project [here](https://adithyaselv.quora.com/Engineering-Art-and-Python-Connecting-the-Dots)* .

---

## **Magnetic Levitation System**
<h6> <em>Mentor - Prof. M.Senthil Kumaran (EEE/SSNCE) <br /> 
 Sibi Sankar, Sanjay Shreedharan, Adithya S</em> </h6>


<iframe width="560" height="315" src="https://www.youtube.com/embed/DL33ijUAX18" frameborder="0" allowfullscreen></iframe>

<br />

* Designed a Prototype of Magnetic Levitation System.
* Implemented Hysteresis Control to achieve magnetic levitation using Spartan 3E FPGA.


---

<h3 id="lock"> <strong>LOCK</strong> </h3>
 
##### *(Localization, Obstacle avoidance , Control and Kinematic framework)* 
<h6> <em>Mentor - Prof. M.Senthil Kumaran (EEE/SSNCE) <br /> 
 Sibi Sankar, Sanjay Shreedharan, Adithya S</em> </h6>

<iframe width="560" height="315" src="https://www.youtube.com/embed/1ySnonQtAqg" frameborder="0" allowfullscreen></iframe>

* Implemented Localization and Pose estimation based on arbitrary defined color contours detection using
OpenCV C++ library.
* Implemented A* based search on the image to find the optimal path through a obstacle maze.
* Implemented a PID based control system based on the kinematics of the differential driving system.

##### *To know more about the implementation and algorithm which was developed, checkout [this blog post](http://sibisankar.me/articles/LOCK-part1/) by [sibi sankar](http://sibisankar.me/)* .

---

## **AeroThrust Pendulum using Arduino**



<iframe width="560" height="315" src="https://www.youtube.com/embed/Lsm37dsPO0k" frameborder="0" allowfullscreen></iframe>

<br />

* Designed a Prototype of Aero- Thrust Pendulum.
* Implemented PI and PID Control Algorithms to achieve stable control of the system using Arduino Uno Microcontroller.
* Implementation is available on [Github](https://github.com/adithyaselv/Aerothrust-Pendulum)

---

## **Kiduino**


![placeholder](/assets/images/kiduino.png)



* Developed a library for Arduino that would help the kids learn Arduino with a simple Object Oriented
approach.
* Developed classes for several Sensor modules like HC- SR04,GP2Y0A02YK0F etc and Protocols like SIRC.
* Implementation is available on [Github](https://github.com/adithyaselv/Kiduino)


---
