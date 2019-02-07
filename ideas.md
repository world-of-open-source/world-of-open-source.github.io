# Google Summer of Code 2019- Project Ideas


- [Capture and Replay](#capture-and-replay)
- [Data Skew Profiler](#data-skew-profiler)
- [WIFI support in ‘Intelligent Maze Solver’](#wifi-support-in-intelligent-maze-solver)
- [Port Verilog Code to MyHDL](#port-verilog-code-to-myhdl) 
- [Recommender System using Machine Learning in RVCE Connect](#recommender-system-using-machine-learning-in-rvce-connect)
- [Encrypted Centralized Projector System using RaspberryPi](#encrypted-centralized-projector-system-using-raspberrypi)
- [Write Code for WiNoC in BookSim2 network simulator](#write-code-for-winoc-in-booksim2-network-simulator)
- [Implementation of Odd-Even Routing of NoC on FPGA](#implementation-of-odd-even-routing-of-noc-on-fpga)
- [Aruco Marker Project](#aruco-marker-project)
- [New Idea Proposal](#your-idea)

## Capture and Replay ##

 Capture and Replay is a web-based network traffic capture and replay tool made using django and scapy powered by python. This tool can be used to upload, edit and play trace files inside live networks. You can refer to the [documentation here](https://github.com/world-of-open-source/Capture-and-Replay/blob/master/documentation.docx).  

Goal: To create an environment to replay the suspended malicious packet and to analyze the threat in Capture and Replay
 
Skill Level: Advanced  

Prerequisites: Experience with a web back-end framework, eg.Django/node.js, Python, and basics of Network and Security.  

Language/Tools: Python, Django, JavaScript, HTML, CSS  
Tags: Networking, Web Development, Malicious software  
  
[GitHub Link](https://github.com/world-of-open-source/Capture-and-Replay)  
  
Mentors: [Dr.Deepamala](mailto:deepamalan@rvce.edu.in), [Dr.Shobha](mailto:shobhag@rvce.edu.in)

## Data Skew Profiler ##

This project analyzes the execution graphs for various jobs and finds a correlation between the data skew and performance skew in HPC Systems/Clusters.

Goals:
- Upload data into the distributed environment using a database by creating clusters.
- Design a ML algorithm to work on the distributed database(implement algorithm and get result) and check with benchmark result.

Skill Level: Advanced   

Prerequisites: Python, Basic concepts of HPC(High Performance Computing), Machine Learning(simple regressions and Classifications).  
  
Language/Tools:ECL, Python  
Tags: HPC-Systems, Networking, Web Development, DBMS  

[GitHub Link](https://github.com/world-of-open-source/DataSkewProfiler)  
  
Mentors: [Prof.Jyoti](mailto:jyothis@rvce.edu.in)  , [Dr.Shobha](mailto:shobhag@rvce.edu.in)


## WIFI support in ‘Intelligent Maze Solver’ ##

Intelligent Maze Solver was developed by an RVCE Team during an IIT Kharagpur Competition-Pixelation in 2018. This project intelligently guides a robot wirelessly through a maze using an overhead camera. The student must have access to a webcam and an ESP8266 module(preferably NodeMCU 1.0). 

Goals:
- Smart maze detection with Deep Learning using overhead camera and write state of the art algorithms for maze traversal(with time complexity better than O(log n).
- Use Wi-Fi for wireless communications(using NodeMCU 1.0 ) rather than XBee/HC-05 Bluetooth Modules.
- Writing an API for NodeMCU in python for effective interface

Skill Level: Beginner/Intermediate  

Prerequisites: Physical access to Arduino, Car Chassis and Webcam; Arduino Programming, Python  

Language/Tools: Python, Arduino Programming  
Tags: Image Processing, Arduino, Hardware Programming, Bluetooth  

[GitHub Link](https://github.com/world-of-open-source/Intelligent-Maze-Solver)  


Mentors: [Dr.Anala](mailto:analamr@rvce.edu.in), [Dr.Hemawati](mailto:hemavathyr@rvce.edu.in)

## Port Verilog Code to MyHDL ##

Writing code in verilog/VHDL seems tedious and non-friendly for beginners. On the other hand, Python is gaining a lot of popularity amongst beginners. MyHDL is a beginner-friendly Python Library that can be used as an alternative to Verilog and other HDLs.
Our aim is to rewrite our existing verilog code in python.
You can refer to our already existing code [here](https://github.com/world-of-open-source/MyHDL-Collections).  

Prerequisites:
- Verilog/VHDL
- Python
- Basic Computer Architecture

Skill Level: Intermediate/Advanced   
Language/Tools:Verilog, VHDL, Python  
Tags: Hardware/FPGA Programming, MyHDL  

[GitHub Link](https://github.com/world-of-open-source/MyHDL-Collections)  

Mentors: [Prof.Namita](mailto:namitapalecha@rvce.edu.in), [Dr.Minal](mailto:minalmoharir@rvce.edu.in)

## Recommender System using Machine Learning in RVCE Connect ##

RVCE Connect is an Android app that allows RVCE students to view their Attendance, Test Scores, Timetable etc.

Goals:
- Connect alumni of RVCE(over 10000 people) with its current students for internship opportunities abroad.
- Create a Machine Learning model that suggests the Alumni for a specific research project/job completion based on the feature input given(Recommender System)

Skill Level: Intermediate/Advanced  

Prerequisites: Android App Development with JAVA, JavaScript, basics of Node.js, Machine Learning(Simple regressions and Classifications).  

Language/Tools: Java, CSS, JavaScript, Node.js  
Tags:Android App development, AI, Web Development  

[GitHub Link](https://github.com/world-of-open-source/RVCE-Connect)  

Mentors: [Dr.Vinay](mailto:vinayvhegde@rvce.edu.in), [Dr.Nagaraja](mailto:nagarajags@rvce.edu.in)  

## Encrypted Centralized Projector System using RaspberryPi ##

The goal of the project is to build a centralized and encrypted projector system with Raspberry Pi as the central server.

Skill Level: Intermediate/Advanced 
 
Prerequisites: Physical access to a Raspberry Pi, Python programming, familiarity with Raspbian OS in Raspberry Pi, basics of Network Security.  

Language/Tools:Python, Bash programming  
Tags: Raspberry Pi, Network Security, Networking  
Mentors: [Dr.Vinay](mailto:vinayvhegde@rvce.edu.in), [Prof.Jyoti](mailto:jyothis@rvce.edu.in) 

## Write Code for WiNoC in BookSim2 network simulator ##

BookSIm 2.0 is a cycle-accurate interconnection Network Simulator for Network on Chip Architectures,developed at Stanford. It generates synthetic traffic and is extensively being used by researchers.
The student must have a basic knowledge of Computer Architecture( Network on Chip Architecture in particular)

Goal: The goal is to write well-documented code for the proposed ‘Wireless Network on Chip’[WiNoC], and various other routing algorithms that are not already present in BookSIm 2.0.
Reproducing the research paper by Sunil, Sagar and Farhan, 'Low Latency and High Throughput NoC Architecture for multicore processors.', is our ultimate aim.  
The paper is on its way to IEEE XPlorer.  
  
Skill Level: Advanced  
Language/Tools: C++, Bash Programming,Makefiles  
Tags: NoC, Computer Architecture, Networking, Web Development  

Mentor: [Dr.Minal Moharir](mailto:minalmoharir@rvce.edu.in), [Dr.Anala](mailto:analamr@rvce.edu.in)

## Implementation of Odd-Even Routing of NoC on FPGA ##

[Network on Chip Architecture](https://en.wikipedia.org/wiki/Network_on_a_chip) is the word of tongue these days in Processor Architectures.  
NoCs are being extensively used in modern muticore SoCs, including the famous Intel Core i9 processor.  
Our goal is to implement the famous odd-even routing algorithm on hardware(FPGA). 

Prerequisites:
- Computer Architecture
- NoC Architecture
- Knowledge to use BookSim 2.0 Network Simulator
- FPGA Programming(verilog, VHDL or even MyHDL)
- Xilinx Vivado

Skill Level: Advanced  
Language/Tools: Verilog, VHDL  
Tags: FPGA Programming, Xilinx Vivado  

Mentors: [Prof.Namita](mailto:namitapalecha@rvce.edu.in), [Dr.Minal](mailto:minalmoharir@rvce.edu.in)


## Aruco Marker Project ##

[Aruco Markers](https://docs.opencv.org/3.1.0/d5/dae/tutorial_aruco_detection.html) are a special class of markers used in pose estimation, which is of great importance in many computer vision applications: robot navigation, augmented reality, and many more.  
This project aims to create a website that will determine the pose using aruco markers, thereby speeding up of aruco marker testing for augmented reality with Unity 3D.

Skill Level: Intermediate/Advanced  
Language/Tools:Python, Django, JavaScript, HTML, CSS  
Tags: Image Processing, Web Development, augmented reality    

[GitHub Link](https://github.com/world-of-open-source/ArucoMarkerPortal)

Mentors: [Dr.Anala](mailto:analamr@rvce.edu.in), [Dr.Hemavathy](mailto:hemavathyr@rvce.edu.in)  

## Your Idea ##
The above projects are strong suggestions for the students. 
We happily welcome all kinds of open source project ideas. Tell us your idea and we will pair you with a mentor from our pool of mentors available [here](https://world-of-open-source.github.io/mentors.html).  
Contact [us](mailto:syedfarhana.ec18@rvce.edu.in) for further details.  


