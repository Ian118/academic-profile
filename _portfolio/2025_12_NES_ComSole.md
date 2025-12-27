---
title: NES Lab ComSole (Capstone)
excerpt: Smart insole for detecting and mitigating Freezing of Gait in Parkinson's Patients<br/><img src='/images/ComSole/ComSole.jpg' style='height:300px'/>
collection: portfolio
---

|                 ![ComSole](/images/ComSole/ComSole.jpg)                  |                ![CAD](/images/ComSole/CAD.png)                 | ![PCB](/images/ComSole/PCB.svg) |
| :----------------------------------------------------------------------: | :------------------------------------------------------------: | :-----------------------------: |
| *ComSole System including 3D-Printed Insoles, PCB, and Electronics Case* | *Insole CAD model showing Haptic Disc and IMU in Right Insole* |          *PCB Diagram*          |

Resources: [Final Presentation](/files/COMSOLE_Final_Presentation.pdf), [Final Report](/files/COMSOLE_Final_Report.pdf)  
Sponsor: [Dr. Ya Wang](https://engineering.tamu.edu/mechanical/profiles/wang-ya.html) (NES Lab)  
Studio Instructors: [Dr. Ni Wang](https://engineering.tamu.edu/mechanical/profiles/wang-ni.html), [Dr. Astrid Layton](https://engineering.tamu.edu/mechanical/profiles/layton-astrid.html)

ComSole is a smart insole designed to mitigate effects of Parkinson's Disease, particularly [Freezing of Gait](https://www.apdaparkinson.org/what-is-parkinsons/symptoms/freezing-of-gait/) (FoG). Conventional methods for mitigating FoG include Deep Brain Stimulation and
ComSole is designed to improve on wearable insole technology, including [MONI](https://doi.org/10.1109/JSEN.2019.2910105)

To treat FoG, the device recognizes when the wearer experiences a freezing event and administers a cue for them to restart walking in the form of a vibration under their first metatarsal. ComSole uses an IMU to track walking patterns, collects gait data on an ESP32 Microcontroller, and classifies FoG events with a random forest machine learning model. The
 
