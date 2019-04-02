## Smart Glass


### Images:
![](Img_Video/images/img_1.jpeg)  
  
More Images and Videos in the Folder Img_Video itself.

### Abstract:
We made Smart Glass as a open project of Aries. It displays notifications and Caller ID details directly onto OLED display. It can also be used to Google search and then display results on monitor. 

### Motivation:
Many iterations of this project can be seen in movies such as James Bond, etc. Considering it to be fairly simple, it was decided to showcase a model such as this in the Hobbies Club Exhibition. The initial brainstorming  showed us that this was a complicated project and would take up upto 4 months if we start from start but as there was some info available as open source we were able to complete the project in far less time. The main challenge was how to integrate the data transmission from android device over to OLED display. 

### Mechanical Aspect:
- Most of the mechanical aspect comprises of 3-D modelling which you can find the designs in our Github profile
- If anyone wants to use it for future reference change the dimensions to 1.5X so every component can fit perfectly
  
Image of the 3D-model completed design:  

![](Img_Video/images/img_4.jpeg)  


### Electronic Aspect:
- It uses bluetooth module HC-05 to transmit data from mobile phone. An arduino microcontroller is used to connect bluetooth module and data sent is just a series of binary data which needs processing before it can be used as input for OLED display.
- The electronic design uses arduino nano for controlling and its small size specification helps achieve processing in a compact space.
- Bluetooth module sends SSI signal which is processed through arduino and data collected by OLED.
- An Android application is used to send notification and phone no of caller directly onto phone.

### Cost Structure:
|Sl. no.| Components                     | Cost(INR) |
|-------|--------------------------------|-----------|
|1.     | Arduino Nano                   | 320       |
|2.     | Bluetooth Module               | 300       |
|3.     | 280mA Lipo Akku                | 300       |
|4.     | OLED Display 32x128            | 400       |
|5.     | 3D- Modelling                  | 1000      |
|       | Total                          | 2320      |



### Applications:
- It can be used with improved camera unit to take pictures and videos as well as survilleance device in case of militiary and Defence applications  
- As the model is robust to surroundings hence can be used as a personal gadget to collect info and display caller ID's.

### Limitations:
- The only limitation is that it is opaque OLED and we were planning to display the reflection from OLED into a glass monitor
 
### Future Improvements:
- Increased no of notification that can be displayed.
- Using Reflection mechanism to make a transparent view.  
- Better mechanical design to make it more appealing.  

### Team Members:
1. Anmol Jain
2. Chirayu Garg  
3. Ritik Jain   
4. Gaurav Singla 

### Mentors:
1. Shahzeb Ata
![Google Glass](Img_Video/images/img_5.jpeg)

### References:
1.  Bluetooth Connectivity with OLED  
https://www.youtube.com/watch?v=BXXAcFOTnBo

2.  Sample model for mechanical structure.  
https://www.youtube.com/watch?v=IpJqzwXWg-k