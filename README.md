# 🛰️ SIT-CUBESAT-AS
This is a repository for Summer Internship 2024 on Cubesat and satellite design.
We're learning about satellite communication.
Follow me as we embark on an engaging and enthralling journey to buld a ground station to receive satellite signals.

# 🌞 DAY1 (25/06/2024):
## 🗣️ AN ENLIGHTENING TALK BY Dr. Chinmoy Saha 
 - He is a Professor at the Department of Avionics in the Indian Institute of Space Science and Technology.
 - The Talk was about Small form factor satellites and satellite communication.
 - A CubeSat is a class of small satellite with a form factor of 10 cm (3.9 in) cubes. These tiny satellites have a 
   mass of no more than 2 kg (4.4 lb) per unit and often use commercial off-the-shelf (COTS) components for their 
   electronics and structure. CubeSats are deployed into orbit from the International Space Station or launched as 
   secondary payloads on a launch vehicle. They’re employed for various purposes, including Earth observation, 
   testing new communications technology, and performing miniature experiments
   SCREENSHOTS:
   ![Screenshot_6-7-2024_85621_github com](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/e8049bbb-68ae-400d-9bed-5f9c0d32875d)
- The above picture shows CUBESATS of 1U and 3U
  ![Screenshot_6-7-2024_84257_](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/55023e71-f234-49d3-b09a-2bad5ca74493)

 ![Screenshot_6-7-2024_8451_](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/ac83ba6d-b4c8-46a3-9210-fac6f9cbe2b6)

## 🗣️ AN ADVENTUROUS JOURNEY WITH Harrish Kesavan:
- He is a core team member of To Space.
- The talk about Exploring pocket cube satellites gave off small satellites, big impact vibes.
- A PocketCube is a type of miniaturized satellite designed for space research. These tiny satellites typically have 
  a cube shape with 5 cm sides (one-eighth the volume of a CubeSat) and weigh no more than 250 grams. They often    
  use commercial off-the-shelf components for their electronics. Despite their small size, PocketQubes are capable 
   of performing various tasks, from Earth observation and amateur radio communications to scientific research and 
    technology demonstrations.
  SCREENSHOTS:
  ![Screenshot_6-7-2024_9419_github com](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/87d8384b-ca1b-4f3e-85e7-fc2017c46930)

  ![Screenshot_6-7-2024_91325_www linkedin com](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/35ab75e4-1702-4950-8754-2b48848d3548)

![Screenshot_6-7-2024_91447_www linkedin com](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/dd135e68-690e-4b68-b4a5-d6d677b8bd51)

# 🌞 DAY2 (26/06/2024):
## 🧑‍🚀 Introduction to CUBESAT : Basic concepts and processes
- CubeSats began as a collaborative effort in 1999 between Jordi Puig-Suari, a professor at California Polytechnic 
  State University (Cal Poly), and Bob Twiggs, a professor at Stanford University’s Space Systems Development 
  Laboratory (SSDL). The original intent of the project was to provide affordable access to space for the university 
  science community, and it has successfully done so.
- Topics covered:
  1. What is CUBESAT?
  2. Why CUBESAT?
  3. CUBESAT Architecture
  4. RC circuit problems

  **SCREENSHOTS**
   
![Screenshot_6-7-2024_92041_](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/161f3949-031c-43b2-958b-fffa545f4335)

![Screenshot_6-7-2024_92241_](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/13460e20-78ae-46b0-bcf1-f3ce54885e21)

- The above picture shows the first dispenser for CubeSats was the Poly-Picosatellite Orbital Deployer (P-POD). It was developed by Cal Poly and San Luis Obispo. 

## 💡 Arduino (LAB1):
 ### Intro to ESP32
 ### LED BLINKING:
 1. EMBEDDED LED BLINKING
 2. EXTERNAL LED (1) BLINKING
 3. EXTERNAL LED (MULTIPLE) BLINKING

# 🌞 DAY3 (27/06/2024):
## 📻 CUBESAT COMMUNICATION
- In this project we use the LoRa Transceiver module for satellite communication with the help of a ESP32 board.
- Topics covered:
   1. Basic digital modulation
   2. Basic bandpass (ASK,FSK,PSK)
   3. Electromagnetic Spectrum
   4. Carrier frequency selection
   5. Satellite orbital Fundamentals
   6. LoRa Radio architecture

**SCREENSHOTS**
 
![Screenshot_6-7-2024_193157_github com](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/b3241261-c8d3-4baa-a545-d6025d4f8aa9)

![Screenshot_6-7-2024_95120_github com](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/48737ce6-c15b-4b47-a4f0-5b8680d6b9f1)

![Screenshot_6-7-2024_9507_github com](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/9e74f745-aad3-4b78-9719-9f4147df6cbb)

![Screenshot_7-7-2024_75426_github com](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/a1e1effb-9a92-49df-8089-266265d5cd9d)


      
 ## 💡 Arduino(LAB2):
  ### Dimming LED using Pulse width modulation
  ### Switching LED on and off using serial monitor
  ### Finding the following from ESP32 and LED datasheet
  
   - [ESP 32 DATASHEET](https://github.com/silicon-sat/SI-2024-CubeSat/blob/main/docs/Datasheet-ESP32.pdf)
   - [LED DATASHEET](https://github.com/silicon-sat/SI-2024-CubeSat/blob/main/docs/Datasheet-LED-XLMR01DE.pdf)

      1. For LED:
       
      | Parameters | Values |
      | ---------- | ----------------------------------------- |
      | Maximum Forward current (If) | 20mA |
      | Typical forward voltage (Vf)| 1.85V |
      | Dominant wavelength | 640nm |
      | Color (RGB) from dominant wavelength | Red |
      | Typical capacitance | 45pF |
      | Operating temperature range | -25 to 50 degree Celcius |

      2. For ESP32:

     | Parametera | Values |
     | ---------- | ------ |
     | Maximum output voltage of GPIO pins | 3.3V |
     | Maximum current that GPIO can source from supply to load | 40mA |
     | Resistance in the circuit | 105 Ohms |

# 🌞 DAY4 (28/06/2024):

      
