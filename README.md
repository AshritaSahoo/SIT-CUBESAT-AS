# 🛰️ SIT-CUBESAT-AS
This is a repository for Summer Internship 2024 on Cubesat and satellite design.

![csli_compliation_gif](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/3820da19-6765-4852-aaad-118c62928095)

# ABSTRACT
- The Summer Internship of 2024 on "Introduction to Cubesats and Satellite Communication", serves as a comprehensive educational platform. Specifically targeting students and enthusiasts interested in CubeSat and satellite communication technologies. This repository provides a structured learning path through a series of practical labs and projects, each focusing on different aspects of satellite technology. We engaged in an intensive study on CubeSat fundamentals, satellite communication principles, LoRa protocol applications and antenna design. This was done through hands-on lab exercises dedicated to signal processing using Python, ESP32 platforms using Arduino IDE, configuring TinyGS ground stations, and simulating antenna designs using 4NEC2 software. This equipped us with essential skills in handling and analyzing signals, a critical component in satellite communications. The course aims to bridge the gap between theoretical knowledge and practical application, preparing the students for the field of satellite technology and communication.
# Introduction:
- The Summer Internship program aims at fostering expertise in the field of CubeSat and satellite communication. CubeSats, or miniature satellites, have become an essential tool in modern space exploration and communication due to their cost-effectiveness and versatility. 


# Introductory talk by Dr. Chinmoy Saha 
 - He is a Professor at the Department of Avionics in the Indian Institute of Space Science and Technology.
 - His Talk was about Small form factor satellites and satellite communication.
 - A CubeSat is a class of small satellite with a form factor of 10 cm (3.9 in) cubes. These tiny satellites have a 
   mass of no more than 2 kg (4.4 lb) per unit and often use commercial off-the-shelf (COTS) components for their 
   electronics and structure. CubeSats are deployed into orbit from the International Space Station or launched as 
   secondary payloads on a launch vehicle. They’re employed for various purposes, including Earth observation, 
   testing new communications technology, and performing miniature experiments


**SCREENSHOTS:**

 ![cubesat](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/116be5ff-a8a5-4448-9efc-a251865767d0)


#  Introductory talk by Harrish Kesavan:
- He is a core team member of To Space.
- His talk about Exploring pocket cube satellites gave off small satellites, big impact vibes.
- A PocketCube is a type of miniaturized satellite designed for space research. These tiny satellites typically have 
  a cube shape with 5 cm sides (one-eighth the volume of a CubeSat) and weigh no more than 250 grams. They often    
  use commercial off-the-shelf components for their electronics. Despite their small size, PocketQubes are capable 
   of performing various tasks, from Earth observation and amateur radio communications to scientific research and 
    technology demonstrations.

  **SCREENSHOTS:**

  ![Screenshot_6-7-2024_91325_www linkedin com](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/35ab75e4-1702-4950-8754-2b48848d3548)


# Cubesat Basics:
## Introduction to CUBESAT : Basic concepts and processes
 - What is a cubesat?

   A CubeSat is a class of small satellite with a form factor of 10 cm (3.9 in) cubes. These tiny satellites have a 
   mass of no more than 2 kg (4.4 lb) per unit and often use commercial off-the-shelf (COTS) components for their 
   electronics and structure. CubeSats are deployed into orbit from the International Space Station or launched as 
   secondary payloads on a launch vehicle. They’re employed for various purposes, including Earth observation, 
   testing new communications technology, and performing miniature experiments
  
- Why CUBESAT?
  
   CubeSats began as a collaborative effort in 1999 between Jordi Puig-Suari, a professor at California Polytechnic 
   State University (Cal Poly), and Bob Twiggs, a professor at Stanford University’s Space Systems Development 
   Laboratory (SSDL). The original intent of the project was to provide affordable access to space for the university science community, and it has successfully done so. Now these are also used for various other experiments like testing instruments, enabling commercial applications,disaster response to climate monitoring.Supporting advanced mission concepts using constellations or swarms.

- Cubesat making procedure according to [NASA CubeSat-101 CSLI](https://www.bing.com/ck/a?!&&p=4d30e5cf239c36d9JmltdHM9MTcyMDU2OTYwMCZpZ3VpZD0yMTM2NjU1Yy00NTJhLTZkNWItMWNlOS03MWM4NDRmZjZjYjEmaW5zaWQ9NTIxMg&ptn=3&ver=2&hsh=3&fclid=2136655c-452a-6d5b-1ce9-71c844ff6cb1&psq=nasa+cubesat+pdf&u=a1aHR0cHM6Ly93d3cubmFzYS5nb3Yvd3AtY29udGVudC91cGxvYWRzLzIwMTcvMDMvbmFzYV9jc2xpX2N1YmVzYXRfMTAxXzUwOC5wZGY&ntb=1).
   The following are the step by step procedure that needs to be followed while building a CubeSat to the point of launching it into the space, provided by NASA CSLI(CubeSat Launch Initiative):
  
   1. Concept Development
  
   2. Securing Funding
  
   3. Merit and Feasibility Reviews
     

   4. CubeSat Design
  
   5. Development and Submittal of Proposal in Response to CSLI Call

   6. Selection and Manifesting
  
   7. Mission Coordination
   
   8. Regulatory Licensing

   9. Flight Specific Documentation Development and Submittal

   10. Ground Station Design, Development, and Testing
   
   11. CubeSat Hardware Fabrication and Testing

   12. Mission Readiness Reviews
 
   13. CubeSat-to-Dispenser Integration and Testing

   14. Dispenser-to-Launch Vehicle Integration

   15. Launch

   16. Mission Operation
 
  **SCREENSHOTS**
  
![Screenshot_6-7-2024_92241_](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/13460e20-78ae-46b0-bcf1-f3ce54885e21)

 - The above picture shows the first dispenser for CubeSats was the Poly-Picosatellite Orbital Deployer (P-POD). It was developed by Cal Poly and San Luis Obispo. 

![R](https://github.com/user-attachments/assets/9fff755a-930e-4408-8ef1-0732e9009854)

# Signal Processing
 ## Digital Modulation 
 - Basic digital modulation:
    1. What is digital modulation? 
    Modulation is The process of superimposing high-frequency carrier signals with low-frequency message signals resulting in a modulated wave.  In modulation, one of the three parameters of the carrier wave is changed i.e. amplitude, frequency or phase according to the amplitude of the message signal at a given time instant. It is an important technique used to increase the range of communication, increase the signal-to-noise ratio, and decrease the size of the antenna. In this process the binary data is modulated to a carrier sinusoidal wave.

2. What are the basic digital modulation methods?
   i. Non-return to zero level:
    It represents binary 1 as a high voltage level (often positive) and binary 0 as a low voltage level (often zero). It maintains the signal level constant for the duration of the bit time.
 ![NZR](https://github.com/user-attachments/assets/845994e8-62b9-4a41-8d7c-c185830c4851)
   ii. Unipolar RZ:
   It represents binary 1 as a positive voltage (e.g., +V volts) and binary 0 represented by a zero voltage (0 volts). Return to zero- The signal returns to zero volts (or a reference voltage) at regular intervals, specifically at the midpoint of each bit period.
   ![Unipolar rz](https://github.com/user-attachments/assets/7f905a06-b4e3-4b02-9a18-d75628d51178)

   iii. Bi-phase-L (Manchester):
    There is a transition in the middle of each bit period, which allows for clock synchronization and improves reliability in noisy environments.Binary 1is represented by a transition from a high to a low (or low to high) state in the middle of the bit period.Binary 0 
 is represented by a transition from a low to a high (or high to low) state in the middle of the bit period.
![Screenshot_13-7-2024_72517_github com](https://github.com/user-attachments/assets/aaacfb4b-cc24-4b8a-acc0-074e0b1fc5eb)

- Basic Bandpass Modulation
  1.
 2.What are the basic bandpass types? 
  i. Amplitude Shift Keying (ASK):
  Varies the amplitude of the carrier wave to represent binary data.
Binary 1 might be a high amplitude, while binary 0 might be a low or zero amplitude.

 ii. Frequency Shift Keying (FSK):
 Changes the frequency of the carrier wave to represent binary data.
Binary 1 could be a high frequency, and binary 0 could be a low frequency.

iii. Phase Shift Keying (PSK):
Alters the phase of the carrier wave to represent binary data.
Binary 1 and binary 0 are represented by different phase shifts (e.g. 0°and 180° for Binary PSK).

![Screenshot_13-7-2024_72631_github com](https://github.com/user-attachments/assets/d63643db-6b46-4e50-a9f0-e39885d2be2b)

 



- Carrier frequency selection
        In telecommunications, carrier frequency refers to the frequency of a carrier wave—a periodic waveform, usually sinusoidal—that carries no information itself. Instead, it’s modified by an information-bearing signal (the modulation signal) to convey information. The carrier wave typically has a much higher frequency than the message signal. This is done to ensure propagation efficiency. The factors of selecting the carrier frequency are: Power efficiency, bandwidth efficieny, system complexity, frequency allocation and regulations.


# Cubesat communication:
## Satellite orbital Fundamentals
  Upon launch, a satellite or spacecraft is most often placed in one of several particular orbits around Earth – or it might be sent on an interplanetary journey, meaning that it does not orbit Earth anymore, but instead orbits the Sun until its arrival at its final destination. They are of the following types : LEO (Low Earth Orbit), MEO(Medium Earth Orbit), GEO(Geostationary Orbit). Here are is the information you need to know before selecting the orbit: [ESA-TYPES OF ORBITS](https://www.esa.int/Enabling_Support/Space_Transportation/Types_of_orbits)

 ## Minimum payload
   -  The payload of a satellite refers to the part that gives it its primary function or purpose. Essentially, the payload is what performs the specific tasks or functions desired from the satellite. For instance, in communication satellites, the payload includes antennas, receivers, and transmitters that facilitates communication.Given below is the minimal payload for a Cubesat.
      
   ![minimumpayload](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/3ebc7d27-b1f6-412e-ae19-192caabe2b92)

   - Here are the functions of the above shown parts.
     [FUNCTIONS](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fraw.githubusercontent.com%2FAshritaSahoo%2FSIT-CUBESAT-AS%2Fmain%2FCUBESAT%2520PARTS%2520AND%2520FUNCTIONS.docx&wdOrigin=BROWSELINK)
   - In general minimum payload consists of a power management system, an on-board computer and a communication system.

## CubeSat Architecture

![Cubesat architecture](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/4f5c2992-2749-4cb4-93ea-7d2e4c85b45a)

 ## LoRa based communication system

 - LoRa (from "long range") is a physical proprietary radio communication technique. It is based on spread spectrum modulation techniques derived from chirp spread 
   spectrum (CSS) technology. It was developed by Cycleo, a company of Grenoble, France, and patented in 2014. Cycleo was later acquired by Semtech.
 -  Here is a brief information about LoRa provided by Semtech.[PDF](https://github.com/silicon-sat/SI-2024-CubeSat/blob/main/docs/AN1200_22_Semtech_LoRa_Basics_v2_STD.pdf)

![lora_archtct](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/c50f5b96-2edc-4804-ac7b-1214b8ddda79)

1. **Analog Front End & Data Conversion:**
   - **Matching:** This component ensures impedance matching between the antenna and the receiver.
   - **LNA (Low Noise Amplifier):** Amplifies weak incoming signals from the antenna.
   - **LPF (Low Pass Filter):** Filters out unwanted high-frequency noise.
   - **ADC (Analog to Digital Converter):** Converts analog signals to digital for further processing.

2. **LoRa™ Modem:**
   - Processes digital signals using LoRa technology for long-range communication.

3. **Protocol Engine:**
   - Manages communication protocols and data packet handling.

4. **FSK Modem:**
   - Handles Frequency Shift Keying modulation and demodulation.

5. **Power Management:**
   - **DC-DC Converter:** Regulates voltage levels.
   - **LDO (Low Dropout Regulator):** Provides stable power supply.

6. **SPI (Serial Peripheral Interface):**
   - Used for communication between microcontrollers and other devices.

7. **Data Buffer:**
   - Temporarily stores data during processing or transmission.

8. **PA (Power Amplifier), PLL (Phase-Locked Loop), and OSC (Oscillator):**
   - **PA:** Boosts signal strength before transmission.
   - **PLL:** Used in frequency synthesis and clock generation.
   - **OSC:** Generates periodic signals.

## ESP32
- The ESP32 is a versatile System on Chip (SoC) microcontroller developed by Espressif Systems. [ESP32 REFERENCE MANUAL](https://github.com/silicon-sat/SI-2024-CubeSat/blob/main/docs/Datasheet-ESP32.pdf)
- [ESP32 DATASHEET](https://github.com/silicon-sat/SI-2024-CubeSat/blob/main/docs/Datasheet-ESP32.pdf)
-  It is a microcontroller, with built-in wifi and bluetooth, it features a dual-core processor, extensive GPIO (General-Purpose Input/Output) pins, and support for various peripherals.
-  These are also widely used in IoT applications.
-   The ESP32's versatility is enhanced by its compatibility with popular development environments like the Arduino IDE and Espressif's own ESP-IDF. In this program, further on, we use the Arduino IDE for various experiments on ESP32.
  
![ESP32](https://github.com/user-attachments/assets/bcd8925d-297e-4101-a7ee-f9ba505d663d)

  ## SPI protocol (Serial Peripheral Interface)
  - It is a synchronous communication protocol. SPI is a fast, efficient protocol for communication between a master device and multiple slaves, commonly used in microcontroller-based projects for interfacing with peripherals like sensors, displays, and memory devices. Understanding SPI is crucial for developing embedded systems that require reliable, high-speed data transfer.
  - It allows a full duplex communication: i.e it can transmit and receive signals at the same time.
  -  SPI uses four wires:
     MOSI (Master Out, Slave In): Main (master) sends data to the sub (slave).
     MISO (Master In, Slave Out): Sub sends data to the main.
     SCLK (Serial Clock): Clock signal from the main.
     CS (Chip Select): Active-low signal to select a specific sub device.
 - Every device connected requires a wire of its own.
 - Working od SPI:
   Initialization: The master configures the clock speed and selects the slave by pulling the Chip Select line low.
   Data Transfer: Data is shifted out of the master to the slave via MOSI, while data from the slave is shifted into the master via MISO, synchronized by the clock.
   End Communication: The master deselects the slave by pulling the Chip Select line high.  

## Communication process
 - All those devices come together to form a communication system between the satellite(CubeSat) and the ground station consisting of the LoRa module and ESP32.
   
![Screenshot_6-7-2024_95120_github com](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/48737ce6-c15b-4b47-a4f0-5b8680d6b9f1)

- The CubeSat collects data (telemetry or payload) and prepares it for transmission. Then its on board computer sends/ transmits data and communicates wirelessly with the LoRa RF module.The frequemcy at which the CubeSat sends the signal is 433MHz and so the ground station is designed in accordance with that to receive the signals, with a coverage of 110 degrees.
- The ESP32 Dev kit is connected to the LoRa RF module via SPI and uploads the data to the internet with WiFi.
- This data can be extracted from the Tiny GS website which is an open-source global satellite network that empowers space enthusiasts to become pioneers.




# DAY5 (29/06/2024)
## Python programming
- Topics covered
  1. Plotting graphs for FFT and FSK
  2. Conversion of FSK to ASK
  3. SNR(Signal to noise ratio)
  4. Modulation to Demodulation conversion



# DAY6 (01/07/2024):
## CMOS VLSI design
- Topics covered
  1. Introduction to CMOS VLSI design
  2. Anatomy of ELectronic System: Mobile Phone
  3. Capacitive MEMS microphone
  4. Piezoelectric MEMS microphone
  5. IMU and gyroscope
  6. AFE
  7. Custom (Analog/Digital) IC design flow


# DAY7 (02/07/2024):
## LoRa Basics
- Topics Covered
  1. Spread-Spectrum Modem
  2. LoRa Basics
  3. Spreading factor
  4. BW
  5. SNR
  6. Bit Rate


# DAY8 (03/07/2024):
## Antenna Basics
- Topics covered
  1. Radiation mechanism
  2. Equivalent circuit
  3. Radiation pattern
  4. Polarization
  5. Types of antenna
  6. Antenna tuning

# DAY9 (04/07/2024):
## Antenna Design
- Topics covered
  1. VSWR
  2. Find the ideal length of the antenna with angle 110 degree angle 433Hz
  3. Impedance
  4. Voltage
  5. Current
 ## Antenna design Practical
  1. Board preparation
  2. Antenna tunning

# DAY10 (05/07/2024):
## Antenna making
## Antenna 
# LABS
 ## 💡 Arduino (LAB1):
 ### Intro to ESP32
 ### LED BLINKING:
 1. EMBEDDED LED BLINKING
 2. EXTERNAL LED (1) BLINKING
 3. EXTERNAL LED (MULTIPLE) BLINKING

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

     ## ARDUINO (LAB3):
1. Serial monitor print function
2. OLED print function

    ## ARDUINO (LAB4)
 1. Humidity and temperature sensor (DHT) using serial monitor
 2. Humidity and temperature sensor (DHT) using OLED

    ## ARDUINO (LAB5):
1. LoRa Sender
2. LoRa Receiver

 ## 4nec2 (LAB1):
  1. Dipole in free space
  2. Loaded dipole in free space

   ## 4nec2 (LAB2):
1. Inverted V over ground
2. V dipole simulation

# Lab 1: Intro to ESP32 Programming

Install and configure Arduino IDE
Introduction to ESP32 development kit.
Write and execute a C-code to blink an LED on the dev board.

# Lab 2: Intro to GPIO programming

In this Lab exercise, students learn to configure a GPIO as an output and control an LED with it.

# Lab 3: Dimming LED using PWM

In this exercise we are going to use the ESP32 to control the light intensity of an external LED using PWM signal.
From the LED Datasheet tabulate the following data:
Maximum Forward current (If)
Typical Forward Voltage (Vf)
Dominant Wavelength (lambdaD)
Estimate the color (RGB) from the above wavelength
Typical Cacpacitance (pF)
Operating temperature range
From the ESP32 Datasheet find and tabulate:
the maximum output voltage of the GPIO pins, and
the maximum current that the GPIO can source from supply to the load.
Calculate the value of the resistance to pass half of the Maximum forward current (If) when ON.
Make sure this current can be sourced by the output port.
Find the closest E12 standardized resistors value available in the market to use for the above limiter.
See this guide on resistor standardization.
Calculate the maximum frequency you can switch the LED such that, the RC time-constant of the LED-cap-resitor is at least 1/25 of the switching period.
Find out what is the minimum frequency you can switch the LED.
Decide on a frequency which is safely in between the minimum and maximum.
Write a program for ESP32:
Assign an output port for the LED
Assign an input port for 2-step dimmer control.
1: Full intensity, 0: 25-percent intensity.
Write a program to control the LED intensity using Pulse-Width Modulation (PWM).
# Lab 4: Dimming multiple LEDs

ESP32 GPIO pins were used to dim multiiple LEDs with different delays.
# Lab 5: Printing data in the serial monitor

The Serial Monitor is an essential tool when creating projects with Arduino. It can be used as a debugging tool, testing concepts, or communicating directly with the Arduino board.
The Arduino IDE 2 has the Serial Monitor tool integrated with the editor, which means that no external window is opened when using the Serial Monitor. This means that you can have multiple windows open, each with its own Serial Monitor.

# Lab 6: Controlling an LED through serial monitor

Controlling an LED connected to ESP32 by reading commands from the serial monitor and turning the LED on or off based on those commands.

# Lab 7: I2C-based OLED Display control

I2C-based OLED pin details. Importing OLED libraries. Structure of the OLED. Displaying simple Text and Scrolling Text in different ways.
# Lab 8: Introduction Signal Processing using Python

You can use lab1-fft.py and lab2-fsk.py as reference for the following exercises:
Write a python program to create a cosine wave of frequency 2MHz with 256 samples per cycle.
Plot it with proper annonation and axis labeling.
Compute the FFT of the above signal and plot it.
You will notice the FFT resolution is very limited for a single cycle.
Create another a signal of frequency 3MHz, add it to above signal and do FFT for the resultant signal.
Simulate lab2-fsk.py and anlayze the plot to understand FSK modulation.
Change the code such that the modulation frequency for 1 is 4MHz and for 0 it is 3MHz.
Change the above code to simulate ASK modulation.
Add demodulation to the above code and plot the time-domain waveform, as well as the FFT of the demodulated signal.
Add a moving average filter to remove the high-frequency component from the demodulated signal.
# Lab 9: I2C temperature sensor interface

Display of room temperature and humidity through OLED as well as serial monitor using DHT22 with ESP32.
# Lab 10: Introduction to LoRa module

Introduction to architecture and pin configuration of Ra-02 Lora transceiver module and SPI (Serial Peripheral Interface) communication.
# Lab 11: LoRa communication

Introduction to Lora communication using Ra-02 Lora transceiver module with ESP32.
# Lab 12: Communication between two LoRa nodes

Sending Text packets and receiving the text packets with *RSSI (Received Signal
Strength Indicator)* and SNR through Serial monitor.
Sending Temperature and humidity packets and receiving the same packets with RSSI (Received Signal Strength Indicator) and SNR through a Serial monitor as well as an OLED display.
# Lab 13: LoRa one-to-many communication setup

Sending data packets from one Lora transmitter to multiple Lora receivers and retracing the same packets.
# Lab 14: Introduction to antenna modeling and simulation software 4NEC2.

# Lab 15: Physical design of Dipole and V-dipole antennas

Tune it to 433MHz with the help of NanoVNA-A Portable VNA Antenna Analyzer Kit with 10KHz-1.5GHz, 2.8 Inch Digital LCD Display Touching Screen Standing Wave Measuring Instrument.
# Lab 16: Introduction to TinyGS

# Lab 17: Setting up a TinyGS ground station
