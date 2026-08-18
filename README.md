<p align='center'>
    <img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=300&section=header&text=Alex%20Barba&fontSize=90&animation=fadeIn&fontAlignY=38&desc=Portfolio,%20Projects,%20and%20Skills&descAlignY=51&descAlign=62"/>
</p>

## Contact

- Email: barbaa@umich.edu
- LinkedIn: [linkedin.com/in/alexandru-barba](https://www.linkedin.com/in/alexandru-barba)
---

# About Me
I am a sophomore studying Computer Engineering at the University of Michigan.

---

## Technical Skills

**Languages:** C++, Python, C, Java, Verilog  
**Frameworks & Tools:** ROS2, Git, Docker, SwiftUI  
**Systems:** CAN Protocols, Camera Calibration, Real-Time Systems  
**Concepts:** Data Structures, Linear Algebra, Embedded Systems  

---

# Featured Projects
## Monster8 Swerve Controller

I developed custom firmware for the **MKS Monster8**, an STM32F407-based controller, to independently control **eight stepper motors and four encoders** for low-cost swerve-drive prototyping. The firmware runs on **FreeRTOS** and uses interrupt-driven step generation for reliable real-time motor control, with commands accepted over both **USB serial and CAN**.

The controller follows the **FIRST Robotics CAN addressing scheme**, exposing each motor as an individual FRC motor-controller device. I also developed a **WPILib vendor library** that allows each motor to be controlled through the standard `MotorController` interface. Together, these tools let students prototype and test real swerve-drive software using inexpensive stepper motors and a single development board instead of purchasing eight proprietary smart motor controllers.

The project began as an attempt to adapt Klipper and G-code for robotic motion, but I ultimately rewrote the firmware around FreeRTOS after determining that a continuously re-commanded robot required a fundamentally different real-time architecture than a pre-planned 3D-printer motion system.

**Repositories:**
[Motor Controller Firmware](https://www.github.com/AlexBarba24/monster8swerve) · [WPILib Vendor Library](https://github.com/AlexBarba24/MonsterControllerVendorlib)


[Motor Controller Firmware](https://www.github.com/AlexBarba24/monster8swerve) [Vendor Library](https://github.com/AlexBarba24/MonsterControllerVendorlib.git)

## VOIP Client

I designed a custom VOIP client with a simple Electron frontend and a C++ backend.

<img width="1131" height="674" alt="image" src="https://github.com/user-attachments/assets/f2ecd678-32a4-4d6a-aefc-e930fb44bc42" />

This project was created to strengthen my understanding of networking concepts, particularly UDP communication, as well as integration between Electron applications and compiled child processes.

[Repository](https://www.github.com/AlexBarba24/teamspeak-clone)

---

## Homework Organization App

An Electron application designed to help students keep track of assignments and exams. Users can upload syllabus PDF files, and the application parses them using OpenAI to automatically detect key events and add them to Google Calendar.

I built this application to better manage my own coursework and deadlines.

[Repository](https://github.com/AlexBarba24/homework-organizer)

---

## Dining Hall Mobile App

I am currently developing an application for University of Michigan dining halls where students can rate dishes served across campus. Users can view both personal and community ratings to help decide where to eat.

This application uses a SwiftUI frontend, a Python Flask API backend, and a SQLite database for storing user data.

<p align="center">
<img width="373" height="785" alt="image" src="https://github.com/user-attachments/assets/165b5093-25ba-41ec-91be-ae438708627a" />
</p>

This project is still in progress. Most of the backend is complete, and I plan to finish it before the Fall 2026 semester.

[Repository](https://github.com/AlexBarba24/MichiganMeals/tree/main)

---

## Contributions

### Robotic Arm Control System (Michigan Mars Rover)

**Tech:** ROS2, C++, Python

Designed and implemented a modular ROS2 action server to convert user click inputs into robotic arm movements.

- Translated UI click inputs into arm-space coordinates using point cloud data  
- Integrated coordinate frame transformations for accurate targeting  
- Collaborated in a multi-developer ROS2 codebase using Git workflows  

**Impact:** Improved the reliability and usability of operator-controlled arm movement in a complex robotics system.

---

## Coursework Disclaimer

While my public GitHub repositories include many of my personal projects, coursework completed for classes is required to remain private. These projects include:

- LC2K assembler, linker, and simulator  
- Verilog FPGA traffic light controller  
- Verilog FPGA calculator  
- Optimal route calculator for a delivery drone  
- Simple in-terminal text editor  
- and more
