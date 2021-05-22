---
layout: home
permalink: index.html
repository-name: e15-3yp-Hydroponics-Automation-System
title: Hydroponics Automation System
---
# Hydroponics Automation System
---

## Team
-  E/15/299, L.M. Ranushka	, [e15299@eng.pdn.ac.lk](mailto:e15299@eng.pdn.ac.lk)
-  E/15/139, D.S. Ishanthi, [e15139@eng.pdn.ac.lk](mailto:e15139@eng.pdn.ac.lk)
-  E/15/249, W.A.D. Pamoda, [e15249@eng.pdn.ac.lk](mailto:e15249@eng.pdn.ac.lk)

## Table of Contents
1. [Introduction](#introduction)
2. [Solution Architecture](#solution-architecture )
3. [Hardware & Software Designs](#hardware-and-software-designs)
4. [Testing](#testing)
5. [Conclusion](#conclusion)
6. [Links](#links)

---

## Introduction

Hydroponics is the method of growing plants in a nutrient-rich water-based environment which uses artificial lighting. This method is widely used in modern agriculture because of less space and conservation of water. But the main disadvantage of this system is the need of constant monitoring to get the maximum benefits from it.

 With this Hydroponics Automation System, the plants are supplied automatically with enough water, proper amount of light intensity and proper nutrients depending on the sensors’ feedback. And also the data obtained from the sensors is accessible through a web application.
 ![image](https://user-images.githubusercontent.com/73756777/119202666-e7be0d00-baae-11eb-919a-6264dddfcfe2.png)



## Solution Architecture

![image](https://user-images.githubusercontent.com/73756777/119202729-0b815300-baaf-11eb-83a3-2bd9fb39d7ef.png)

## Hardware and Software Designs
### The modified final data flow  of the system
![image](https://user-images.githubusercontent.com/73756777/119202906-6c109000-baaf-11eb-9120-85f394b8879d.png)


## Testing

The data gathered from the sensors are sent to the NodeMCU and sent to a web server and stored in a database. User can access this data through a web application. The automatic control of the actuators is done by the webserver and the Node MCU. Also if the user wants to take the control decisions, he can control the system through the web application.



## Conclusion

For the demonstration purpose for now we have implemented the structure of the hydroponics system with water circulation. We are going to further improve and develop it.

### Links  
- <a href = "https://github.com/cepdnaclk/e15-3yp-Hydroponics-Automation-System" target = "_blank"> Project Repository </a>
- <a href = "https://cepdnaclk.github.io/e15-3yp-Hydroponics-Automation-System/" target = "_blank">Project Page</a>
- <a href = "http://www.ce.pdn.ac.lk/" target = "_blank">Department of Computer Engineering</a>
- <a href = "https://eng.pdn.ac.lk/" target = "_blank">University of Peradeniya</a>


[//]: # (Please refer this to learn more about Markdown syntax)
[//]: # (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
