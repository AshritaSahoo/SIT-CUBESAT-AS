# 🛰️ INTRODUCTION TO CubeSat AND SATELLITE COMMUNICATION
This is a repository for Summer Internship 2024 on CubeSat and satellite communication. 

![csli_compliation_gif](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/3820da19-6765-4852-aaad-118c62928095)

# ABSTRACT
- The Summer Internship of 2024 on "Introduction to CubeSats and Satellite Communication", serves as a comprehensive educational platform. Specifically targeting students and enthusiasts interested in CubeSat and satellite communication technologies. It provides a structured learning path through a series of practical labs and projects, each focusing on different aspects of satellite technology. We engaged in an intensive study on CubeSat fundamentals, satellite communication principles, LoRa protocol applications and antenna design. This was done through hands-on lab exercises dedicated to signal processing using Python, ESP32 platforms using Arduino IDE, configuring TinyGS ground stations, and simulating antenna designs using 4NEC2 software. This equipped us with essential skills in handling and analyzing signals, a critical component in satellite communications. The course aims to bridge the gap between theoretical knowledge and practical application, preparing the students for the field of satellite technology and communication.

# Introduction
**Introduction to CubeSat and Satellite Communication Internship Program**

Welcome to the CubeSat and Satellite Communication Internship Program at Silicon University. This program is designed to provide participants with comprehensive knowledge and practical skills in the rapidly evolving field of CubeSat technology and satellite communication.

Throughout this internship, we went through the following aspects of Satellite communication.

- **In-depth Understanding of CubeSat:** Learn about CubeSat, a revolutionary small satellite format, including its design principles, subsystem integration, and applications in space missions.

- **Fundamentals of Satellite Communication:** Acquire basic knowledge of satellite communication systems, including link budget analysis, modulation techniques, and protocols.

- **RF Communication with LoRa Protocol:** Explore the essentials of RF communication using the LoRa protocol, covering aspects such as signal modulation, data encoding, and network architecture.

- **Basics of Antenna Design:** Learn the fundamentals of antenna design, including antenna types, radiation patterns, impedance matching, and practical antenna testing.

- **Setting up TinyGS Ground Station:** Gain hands-on experience in setting up and operating a TinyGS ground station, including antenna deployment, satellite tracking, data reception, and analysis.



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
- His talk about Exploring PocketQube satellites gave off small satellites, big impact vibes.
- A PocketQube is a type of miniaturized satellite designed for space research. These tiny satellites typically have 
  a cube shape with 5 cm sides (one-eighth the volume of a CubeSat) and weigh no more than 250 grams. They often    
  use commercial off-the-shelf components for their electronics. Despite their small size, PocketQubes are capable 
   of performing various tasks, from Earth observation and amateur radio communications to scientific research and 
    technology demonstrations.

  **SCREENSHOTS:**

  ![Screenshot_6-7-2024_91325_www linkedin com](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/35ab75e4-1702-4950-8754-2b48848d3548)


# Cubesat Basics:
## Introduction to CubeSat : Basic concepts and processes
 - What is a CubeSat?

   A CubeSat is a class of small satellite with a form factor of 10 cm (3.9 in) cubes. These tiny satellites have a 
   mass of no more than 2 kg (4.4 lb) per unit and often use commercial off-the-shelf (COTS) components for their 
   electronics and structure. CubeSats are deployed into orbit from the International Space Station or launched as 
   secondary payloads on a launch vehicle. They’re employed for various purposes, including Earth observation, 
   testing new communications technology, and performing miniature experiments
  
- Why CubeSat?
  
   CubeSats began as a collaborative effort in 1999 between Jordi Puig-Suari, a professor at California Polytechnic 
   State University (Cal Poly), and Bob Twiggs, a professor at Stanford University’s Space Systems Development 
   Laboratory (SSDL). The original intent of the project was to provide affordable access to space for the university science community, and it has successfully done so. Now these are also used for various other experiments like testing instruments, enabling commercial applications,disaster response to climate monitoring.Supporting advanced mission concepts using constellations or swarms.

- CubeSat making procedure according to [NASA CubeSat-101 CSLI](https://www.bing.com/ck/a?!&&p=4d30e5cf239c36d9JmltdHM9MTcyMDU2OTYwMCZpZ3VpZD0yMTM2NjU1Yy00NTJhLTZkNWItMWNlOS03MWM4NDRmZjZjYjEmaW5zaWQ9NTIxMg&ptn=3&ver=2&hsh=3&fclid=2136655c-452a-6d5b-1ce9-71c844ff6cb1&psq=nasa+cubesat+pdf&u=a1aHR0cHM6Ly93d3cubmFzYS5nb3Yvd3AtY29udGVudC91cGxvYWRzLzIwMTcvMDMvbmFzYV9jc2xpX2N1YmVzYXRfMTAxXzUwOC5wZGY&ntb=1).
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

![Screenshot-(311)](https://github.com/user-attachments/assets/3e25349a-6f62-40ae-859c-becbc6567344)

   
   
   ii. Unipolar RZ:
   It represents binary 1 as a positive voltage (e.g., +V volts) and binary 0 represented by a zero voltage (0 volts). Return to zero- The signal returns to zero volts (or a reference voltage) at regular intervals, specifically at the midpoint of each bit period.

   ![Unipolar rz](https://github.com/user-attachments/assets/7f905a06-b4e3-4b02-9a18-d75628d51178)

  
   iii. Bi-phase-L (Manchester):
    There is a transition in the middle of each bit period, which allows for clock synchronization and improves reliability in noisy environments.Binary 1 is represented by a transition from a high to a low (or low to high) state in the middle of the bit period.Binary 0 is represented by a transition from a low to a high (or high to low) state in the middle of the bit period.

![Screenshot-(319)](https://github.com/user-attachments/assets/e131921f-229b-4046-8d97-dd5c6f5d0939)




- Basic Bandpass Modulation

1. What is bandpass modulation?
     Bandpass modulation refers to a type of modulation where the baseband signal (which typically carries the information to be transmitted) is modulated onto a carrier signal. This process effectively shifts the frequency spectrum of the baseband signal to a higher frequency range, known as the passband.

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

## Carrier Frequency Selection
- What is carrier signal?

    A carrier signal is a high-frequency signal that is modulated by the baseband signal. The carrier frequency is chosen such that it lies within a certain band of frequencies, known as the passband.
 
![OIP](https://github.com/user-attachments/assets/14702ef0-008f-4a71-9810-8597eead46cb)


- Carrier frequency selection
        In telecommunications, carrier frequency refers to the frequency of a carrier wave—a periodic waveform, usually sinusoidal—that carries no information itself. Instead, it’s modified by an information-bearing signal (the modulation signal) to convey information. The carrier wave typically has a much higher frequency than the message signal. This is done to ensure propagation efficiency. The factors of selecting the carrier frequency are:
  i. Power efficiency
  ii. bandwidth efficieny
  iii. system complexity
  iv. frequency allocation and regulations.
- The  CubeSats often use frequencies allocated for amateur satellites. These fall within the VHF(Very High Frequency) band (145.8 MHz – 146.0 MHz) and the UHF(Ultra High Frequency) band (435.0 MHz – 438.0 MHz).
- The choice of this frequency allows for relatively low-power communication, making it suitable for battery-operated devices like CubeSats. Additionally, it provides a long wireless ranExa- Hence we would be operating at 433MHz for this project.

  ## FFT
  - FFT analysis is one of the most used techniques when performing signal analysis across several application domains. FFT transforms signals from the time domain to the frequency domain. FFT is the abbreviation of Fast Fourier Transform.

Exam FFT analysis, numerous signal characteristics can be investigated to a much greater extent than when inspecting the time domain data. In the frequency domain, the signal characteristics are described by independent frequency components, wherein the time domain it is described by one waveform, containing the sum of all characteristics.

![freqtime-350x244](https://github.com/user-attachments/assets/9db5f2fb-8aa9-4fff-b6fb-a72d01a2c2c4)

## Bandwidth
- Bandwidth refers to the range of frequencies over which a signal, channel, or communication system can operate effectively. It represents the capacity for transmitting data within a given frequency range.
- In digital systems (e.g., internet connections), bandwidth affects data transfer rates. Higher bandwidth enables faster downloads and smoother streaming.
- Bandwidth is typically measured in hertz (Hz) or its multiples

## Bit Rate:
- Bit rate, also known as data rate, refers to the rate at which data is transmitted or processed.
It represents the number of bits (binary digits) transmitted per unit of time (usually seconds).

- Bit rate is typically measured in bits per second (bps) or its multiples

Exampat communication:
## Satellite orbital Fundamentals
  Upon launch, a satellite or spacecraft is most often placed in one of several particular orbits around Earth – or it might be sent on an interplanetary journey, meaning that it does not orbit Earth anymore, but instead orbits the Sun until its arrival at its final destination. They are of the following types : LEO (Low Earth Orbit), MEO(Medium Earth Orbit), GEO(Geostationary Orbit). Here are is the information you need to know before selecting the orbit: [ESA-TYPES OF ORBITS](https://www.esa.int/Enabling_Support/Space_Transportation/Types_of_orbits)

  ![GEO-MEO-and-LEO-orbits](https://github.com/user-attachments/assets/ad9ad07e-69b8-4b91-b7d3-27c2ea38d93e)

- CubeSats primarily operate in LEO. This is beacause lower energy requirements simplify deployment, LEO provides better communication coverage due to proximity to ground stations and CubeSats can transmit data more efficiently at shorter distances.
  
 ## Minimal payload (An example) 
   -  The payload of a satellite refers to the part that gives it its primary function or purpose. Essentially, the payload is what performs the specific tasks or functions desired from the satellite. For instance, in communication satellites, the payload includes antennas, receivers, and transmitters that facilitates communication.Given below is the minimal payload for a Cubesat.
      
   ![minimumpayload](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/3ebc7d27-b1f6-412e-ae19-192caabe2b92)

   - Here are the functions of the above shown parts.
     [FUNCTIONS](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fraw.githubusercontent.com%2FAshritaSahoo%2FSIT-CUBESAT-AS%2Fmain%2FCUBESAT%2520PARTS%2520AND%2520FUNCTIONS.docx&wdOrigin=BROWSELINK)
   - In general minimum payload consists of a power management system, an on-board computer and a communication system.

## CubeSat Architecture (An example) 

![Cubesat architecture](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/4f5c2992-2749-4cb4-93ea-7d2e4c85b45a)

 ## LoRa based communication system

 - LoRa (from "long range") is a physical proprietary radio communication technique. It is based on spread spectrum modulation techniques derived from chirp spread 
   spectrum (CSS) technology. It was developed by Cycleo, a company of Grenoble, France, and patented in 2014. Cycleo was later acquired by Semtech.
 -  Here is a brief information about LoRa provided by Semtech.[PDF](https://github.com/silicon-sat/SI-2024-CubeSat/blob/main/docs/AN1200_22_Semtech_LoRa_Basics_v2_STD.pdf)
### Spread Spectrum Principle
- Spread spectrum refers to a technique used in telecommunications and signal processing to spread the bandwidth of a signal over a much wider range than the minimum necessary for transmission.

  ![download1](https://github.com/user-attachments/assets/01af3e61-bcfd-4251-85f9-bbc32307e166)

  ![download2](https://github.com/user-attachments/assets/5930ed3c-5fe9-480f-a524-ac1f5c71f291)

- Spreading factor:
  The spreading factor is a critical parameter in LoRa-based communication systems.LoRa uses Chirp Spread Spectrum (CSS) technology, where chirps (symbols) carry data. The spreading factor controls the chirp rate, which, in turn, affects the speed of data transmission.
  ![download3](https://github.com/user-attachments/assets/17891ea6-80d0-4311-ad34-9c980174d388)

### SNR(Signal to Noise Ratio) and RSSI (Received signal strangth Indicator)
- SNR is the ratio of the signal power to the noise power. A higher SNR indicates a stronger signal relative to noise, leading to better communication quality.
- RSSI is a measurement of how well your device can hear a signal from an access point or router. The greater the RSSI value, the stronger the signal.
- For SNR>0: RSSI or Packet Strength (dBm)= -164+RSSI
- For SNR<0: RSSI= -164+ PacketRSSI+0.25*PacketSNR

### LoRa Architecture
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
### Properties of LoRa:

![LoRa](https://github.com/user-attachments/assets/34634962-4c3d-47c8-99e1-6c7914efd861)

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

![SPI](https://github.com/user-attachments/assets/d29ffd79-a61d-4ad9-86c3-96a23fdfb21d)

![SPI ACCESS](https://github.com/user-attachments/assets/41679ba7-34e9-4690-a8ac-cb47e000419a)

## Communication process
 - All those devices come together to form a communication system between the satellite(CubeSat) and the ground station consisting of the LoRa module and ESP32.
   
![Screenshot_6-7-2024_95120_github com](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/assets/174847576/48737ce6-c15b-4b47-a4f0-5b8680d6b9f1)

- The CubeSat collects data (telemetry or payload) and prepares it for transmission. Then its on board computer sends/ transmits data and communicates wirelessly with the LoRa RF module.The frequemcy at which the CubeSat sends the signal is 433MHz and so the ground station is designed in accordance with that to receive the signals, with a coverage of 110 degrees.
- The ESP32 Dev kit is connected to the LoRa RF module via SPI and uploads the data to the internet with WiFi.
- This data can be extracted from the Tiny GS website which is an open-source global satellite network that empowers space enthusiasts to become pioneers.

# Introduction to VLSI
- VLSI  stands for Very-Large-Scale Integration, a process of creating integrated circuits by combining thousands to millions of transistors onto a single chip. It revolutionized the field of electronics by making devices smaller, faster, and more energy-efficient. VLSI technology is the foundation for modern microprocessors, memory chips, and other complex integrated circuits used in a wide range of applications, from consumer electronics to advanced computing systems.

![vlsi](https://github.com/user-attachments/assets/8d8e3818-4c7f-4c72-b151-53ffc03a1fa2)

# CONCEPT OF ANTENNAS
- An antenna is a device used to transmit and receive electromagnetic waves. It is a critical component in communication systems, enabling the transmission of data over distances without the need for physical connections. Antennas operate based on the principle of electromagnetic wave propagation. When a current flows through the antenna, it generates an electromagnetic field that radiates outwards. Conversely, when electromagnetic waves impinge on the antenna, they induce a current that can be detected and processed by the receiver.

## Types of Antennas
 - Wire Antennas
   ![Screenshot_13-7-2024_11473_www dropbox com](https://github.com/user-attachments/assets/5a81bdf5-2165-43f2-9f56-df4e1d9c532f)
 - Aperture Antennas
    ![Screenshot_13-7-2024_114812_www dropbox com](https://github.com/user-attachments/assets/12382759-c2d9-4be8-8abf-0f442174fef9)
 - Microstrip Antennas
 ![Screenshot_13-7-2024_115214_www dropbox com](https://github.com/user-attachments/assets/93b10ec6-9575-4d12-8f76-9a28f1219db1)
 - Array antennas
![Screenshot_13-7-2024_115244_www dropbox com](https://github.com/user-attachments/assets/6e8ddbe7-47e8-493d-9bc6-16eed183ba00)


## Radiation Mechanism
- Primary mechanism of radiation is due to acceleration or decceleration of charges.
  ![Screenshot_13-7-2024_114453_www dropbox com](https://github.com/user-attachments/assets/73962d24-ffb9-4454-b42b-9e3daa8fa37c)

![WhatsApp Image 2024-07-13 at 11 59 52_42b7ee8e](https://github.com/user-attachments/assets/076735be-742a-4414-9213-3def2ef80876)
## Radiation Pattern
- The radiation pattern of an antenna describes how the antenna radiates energy into space or receives energy from space. It is a graphical representation of the distribution of power radiated by the antenna as a function of direction. The formation of the radiation pattern is influenced by several factors, including the antenna's physical structure, the current distribution along the antenna elements, and the operating frequency.
  
![WhatsApp Image 2024-07-13 at 12 00 32_0720917d](https://github.com/user-attachments/assets/6734ee57-9767-4a7c-acd5-62a8d1b66e1c)

## Polarization
- It is the orientation of the electric field of the radiated electromagnetic wave. It is a key parameter in antenna design and communication systems, as it affects how antennas transmit and receive signals. The polarization of an antenna must match the polarization of the incoming or outgoing signals for optimal performance.

![WhatsApp Image 2024-07-13 at 12 00 45_3e376da1](https://github.com/user-attachments/assets/ae00358f-40a4-4ca3-9696-70d33d078104)

## Antenna tuning
- Tuning an antenna involves adjusting its physical parameters or electronic components to ensure it resonates at the desired frequency or frequencies, providing optimal performance for transmitting and receiving signals. Proper tuning minimizes impedance mismatch, maximizes signal strength, and reduces standing wave ratio (SWR).

# Tiny GS
![OIP](https://github.com/user-attachments/assets/a675052c-db5d-4912-bb31-9e29cd82139b)
- TinyGS is an open-source global satellite network that empowers space enthusiasts to become pioneers. By building their own Tiny Ground Stations, users can collect vital data, prevent collisions, and join a community of citizen scientists.
![Screenshot_13-7-2024_121855_tinygs com](https://github.com/user-attachments/assets/4d330214-04c9-44df-bf55-3149a921bbee)


  
  

# Lab 1: Intro to ESP32 Programming

Install and configure Arduino IDE
![OIP (1)](https://github.com/user-attachments/assets/fafb3d14-e41e-40bb-b8c2-84806b7ccb2c)

Introduction to ESP32 development kit.
Write and execute a C-code to blink an LED on the dev board.

![WhatsApp Image 2024-07-13 at 11 11 49_1466db4e](https://github.com/user-attachments/assets/20a0eda7-afc3-4661-b1f4-7770e8d21ce3)

Code for the above: [Code](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/blob/main/LABS/ARDUINO/Lab1)

# Lab 2: Intro to GPIO programming

In this Lab exercise, students learn to configure a GPIO as an output and control an LED with it.
![Esp32-pin-description-Recommended-reading-ESP32-Pinout-Reference-Which-GPIO-pins-should_Q640](https://github.com/user-attachments/assets/f8ba5036-30ea-4cb7-913b-a693c809754e)
![WhatsApp Image 2024-07-13 at 11 11 49_e7fc46cb](https://github.com/user-attachments/assets/98ad1692-089e-41a2-ac9c-d09613b1d226)

Code for the above: [Code](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/blob/main/LABS/ARDUINO/Lab1) 

# Lab 3: Dimming LED using PWM

In this exercise we are going to use the ESP32 to control the light intensity of an external LED using PWM signal.
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

Write a program to control the LED intensity using Pulse-Width Modulation (PWM).


# Lab 4: Dimming multiple LEDs
![WhatsApp Image 2024-07-13 at 11 11 49_1466db4e](https://github.com/user-attachments/assets/43dfacc6-04e9-4e2f-a608-0137bfc2e2a0)

ESP32 GPIO pins were used to dim multiiple LEDs with different delays.
# Lab 5: Printing data in the serial monitor

The Serial Monitor is an essential tool when creating projects with Arduino. It can be used as a debugging tool, testing concepts, or communicating directly with the Arduino board.
The Arduino IDE 2 has the Serial Monitor tool integrated with the editor, which means that no external window is opened when using the Serial Monitor. This means that you can have multiple windows open, each with its own Serial Monitor.

# Lab 6: Controlling an LED through serial monitor

Controlling an LED connected to ESP32 by reading commands from the serial monitor and turning the LED on or off based on those commands.

# Lab 7: I2C-based OLED Display control
![WhatsApp Image 2024-07-13 at 11 11 50_ca4fb795](https://github.com/user-attachments/assets/0503d785-f6c4-42de-a8f1-20ba65bbfcb2)

I2C-based OLED pin details. Importing OLED libraries. Structure of the OLED. Displaying simple Text and Scrolling Text in different ways.
# Lab 8: Introduction Signal Processing using Python
![348232059-58df6f40-b9b0-467f-bd31-57e3e06bcbbb](https://github.com/user-attachments/assets/2bb94bf5-093f-4886-97f6-e46ce27893c1)
![348231785-b73f870f-4485-4439-9b65-15f2b836a168](https://github.com/user-attachments/assets/f2ff2a55-c6bc-4c4f-b516-d18590ab39c5)
```C
import numpy as np
import matplotlib.pyplot as plt

#Parameters
f_signal = 2e6  # 2 MHz signal frequency
fs = 0.5e9     # Sampling frequency (0.5 GHz)
num_samples = 256  # Number of samples
total_time = 500e-9  # Total time duration (500 ns)
time_period = 0.5e-6  # Time period of the signal (0.5 microseconds)

#Time vector
t = np.linspace(0, total_time, num_samples, endpoint=False)

#Generate sine wave
signal = np.sin(2 * np.pi * f_signal * t)

#Plotting
plt.figure(figsize=(10, 6))
plt.plot(t * 1e9, signal)  #, marker='o')
plt.title('2 MHz Sine Wave')
plt.xlabel('Time (ns)')
plt.ylabel('Amplitude')
plt.grid(True)
plt.show()

plt.tight_layout()
plt.show()
plt.savefig("lab-fsk.png")

```
Modulation
```python
#!/usr/bin/env python3

import numpy as np
import matplotlib.pyplot as plt
from scipy.fft import fft, fftfreq
## For saving plots to a file. Just couldn't get it to work from commandline
import matplotlib
matplotlib.use('Agg')

# Parameters
fc0 = 4e6        # 1 Carrier Frequency
fc1 = 2e6        # 0 Carrier Frequency
fs = 256*4e6    # Sampling frequency
ncycl = 512          # No of cycles of fc 
nfc0 = 8        # number of fc0 cycles for one symbol
Tsim = ncycl/fc0       # Total Simulation time
t = np.arange(0, Tsim, 1/fs)  # Time vector

# Message signal (binary data)
data = np.random.randint(0, 2, int(ncycl/nfc0))  # Random binary data
nupData = int(t.size/data.size) 
data = np.repeat(data, nupData)  # Upsample binary data

# FSK Modulation
modulated_signal = np.zeros_like(t)
for i in range(len(t)):
    if data[i] == 0:
        modulated_signal[i] = np.cos(2 * np.pi * fc0 * t[i])
    else:
        modulated_signal[i] = np.cos(2 * np.pi * fc1 * t[i])

# FFT of the modulated signal
N = len(modulated_signal)
yf = fft(modulated_signal)
xf = fftfreq(N, 1 / fs)

# modulation
# Parameters for modulation
threshold = 0  # Decision threshold for modulation

# modulated data array
modulated_data = np.zeros_like(data)

# modulation loop
for i in range(len(t)):
    if np.cos(2 * np.pi * fc0 * t[i]) > threshold:
        modulated_data[i] = 0
    else:
        modulated_data[i] = 1

# Ensure demodulated data has the correct length (may be longer due to upsampling)
modulated_data = modulated_data[:data.size]

# Plotting
fig, axs = plt.subplots(4, 1, figsize=(10, 16))

axs[0].plot(t, data)
axs[0].set_title('Original Binary Data')
axs[0].set_xlim([0, Tsim])
axs[0].set_ylim([-0.2, 1.2])

axs[1].plot(t, modulated_signal)
axs[1].set_title('FSK Modulated Signal')
axs[1].set_xlim([0, Tsim])

axs[2].plot(xf, np.abs(yf))
axs[2].set_title('FFT of Modulated Signal')
axs[2].set_xlim([0, 2*fc0])
axs[2].set_xlabel('Frequency (Hz)')

axs[3].plot(t, modulated_data, marker='o', linestyle='-', color='b')
axs[3].set_title('modulated Binary Data')
axs[3].set_xlabel('Time (s)')
axs[3].set_ylabel('Binary Value')
axs[3].set_xlim([0, Tsim])
axs[3].set_ylim([-0.2, 1.2])
axs[3].grid(True)

plt.tight_layout()
plt.savefig("fsk-lab2.png")
plt.show()
```
![348231902-f42470f5-bce1-44cc-8887-c178199f7a58](https://github.com/user-attachments/assets/29bd7b65-67b0-44d7-8d4c-8ec8e1d4056d)
Demodulation
```python

# Parameters
fc0 = 4e6        # 1 Carrier Frequency
fc1 = 2e6        # 0 Carrier Frequency
fs = 256*4e6    # Sampling frequency
ncycl = 512          # No of cycles of fc
nfc0 = 8        # number of fc0 cycles for one symbol
Tsim = ncycl/fc0       # Total Simulation time
t = np.arange(0, Tsim, 1/fs)  # Time vector

# Message signal (binary data)
data = np.random.randint(0, 2, int(ncycl/nfc0))  # Random binary data
nupData = int(t.size/data.size)
data = np.repeat(data, nupData)  # Upsample binary data

print(data.size, t.size)

# FSK Modulation
modulated_signal = np.zeros_like(t)
for i in range(len(t)):
    if data[i] == 0:
        modulated_signal[i] = np.cos(2 * np.pi * fc0 * t[i])*np.cos(2 * np.pi * fc0 * t[i])
    else:
        modulated_signal[i] = np.cos(2 * np.pi * fc1 * t[i])*np.cos(2 * np.pi * fc0 * t[i])

# FFT of the modulated signal
N = len(modulated_signal)
yf = fft(modulated_signal)
xf = fftfreq(N, 1 / fs)

# Plotting
fig, axs = plt.subplots(3, 1, figsize=(10, 12))

axs[0].plot(t, data)
axs[0].set_title('Original Binary Data')
axs[0].set_xlim([0, Tsim])
#axs[0].set_ylim([-0.2, 1.2])

axs[1].plot(t, modulated_signal)
axs[1].set_title('FSK DeModulation')
axs[1].set_xlim([0, Tsim])
                                                                                                                                                        axs[2].plot(xf, np.abs(yf))
axs[2].set_title('FFT of DeModulated Signal')
axs[2].set_xlim([0, 2*fc0])
axs[2].set_xlabel('Frequency (Hz)')

plt.tight_layout()
plt.savefig("fsk-demodulation-lab2.png")
plt.show()
```
![348231954-7835a516-0691-4310-8959-ea1308133588](https://github.com/user-attachments/assets/e90cb25f-9c7d-4e50-b0ac-f1ec86182f7a)

# Lab 9: I2C temperature sensor interface
![image](https://github.com/user-attachments/assets/504a7934-30dd-4400-8d51-bb5b624b3111)

Display of room temperature and humidity through OLED as well as serial monitor using DHT22 with ESP32.
# Lab 10: Introduction to LoRa module

Introduction to architecture and pin configuration of Ra-02 Lora transceiver module and SPI (Serial Peripheral Interface) communication.

| Module Pin | 	Arduino Pin |
| ---------- | ------------ |
| VCC |	3.3V |
| GND	| GND |
| SCK |	Pin 13 |
| MOSI	| Pin 11 |
| MISO	| Pin 12 |
| NSS	| Pin 10 |
| RESET	| Pin 9 |
| DIO0	| Pin 2 |
Ra-02 (SX1278)

Frequency: 433/868/915 MHz Range: Up to 15 km in rural areas Interface: SPI Commonly used with Arduino and ESP32.
# Lab 11: LoRa communication

Introduction to Lora communication using Ra-02 Lora transceiver module with ESP32.
# Lab 12: Communication between two LoRa nodes

Sending Text packets and receiving the text packets with *RSSI (Received Signal
Strength Indicator)* and SNR through Serial monitor.
Sending Temperature and humidity packets and receiving the same packets with RSSI (Received Signal Strength Indicator) and SNR through a Serial monitor as well as an OLED display.
Sender
```python
#include<SPI.h>
#include<LoRa.h>

//std configuration
//#define DIO0 2
//#define RST 14
//#define NSS 3
//#define MOSI 23
//#define MISO 19
//#define SCLK 18

#define DIO0 26
#define RST 14
#define NSS 18
#define MOSI 27
#define MISO 19
#define SCLK 5

int counter=0;

void setup(){
  //initiliazing serial monitor
  Serial.begin(115200);
  while(!Serial);
  Serial.println("LoRa Sender");

  //setup LoRa tranceiver module
  SPI.begin(SCLK,MISO,MOSI,NSS);
  LoRa.setPins(NSS,RST,DIO0);

  //replace the lora.begin(---E-)
  // 433E6 FOR ASIA
  // 866E6 FOR EUROPE
  // 915E6 FOR NORTH AMERICA
while(!LoRa.begin(433E6)){
  Serial.println(".");
  delay(500);
}
//change sync word 0xF3 to match reciever
//the sync word assures you dont gets LoRa message from other LoRa transceiver
//ranges from 0-0xFF
LoRa.setSyncWord(0XF3);
Serial.println("LoRa Initializing OK !");
}

void loop(){
  Serial.println("sending packet");
  Serial.println(counter);

  //send LoRa packet to recieve

  LoRa.beginPacket();
  LoRa.print("hello...");
  LoRa.print(counter);
  LoRa.endPacket();

  counter++;

  delay(1000);
}
```
Receiver
```python
#include<SPI.h>
#include<LoRa.h>

//std configuration
//#define DIO0 2
//#define RST 14
//#define NSS 3
//#define MOSI 23
//#define MISO 19
//#define SCLK 18

#define DIO0 26
#define RST 14
#define NSS 18
#define MOSI 27
#define MISO 19
#define SCLK 5


void setup(){
  //initiliazing serial monitor
  Serial.begin(115200);
  while(!Serial);
  Serial.println("LoRa Sender");

  //setup LoRa tranceiver module
  SPI.begin(SCLK,MISO,MOSI,NSS);
  LoRa.setPins(NSS,RST,DIO0);

  //replace the lora.begin(---E-)
  // 433E6 FOR ASIA
  // 866E6 FOR EUROPE
  // 915E6 FOR NORTH AMERICA
while(!LoRa.begin(433E6)){
  Serial.println(".");
  delay(5000);
}
//change sync word 0xF3 to match reciever
//the sync word assures you dont gets LoRa message from other LoRa transceiver
//ranges from 0-0xFF
LoRa.setSyncWord(0XF3);
Serial.println("LoRa Initializing OK !");
}

void loop() {
  // try to parse packet
  int packetsize = LoRa.parsePacket();
  if(packetsize){
    Serial.println("Recieving Packet:");
  }
  while(LoRa.available()){
    String LoRaData = LoRa.readString();
    Serial.print(LoRaData);
  }
    Serial.print("`with RSSI");
    // RSSI - recieved signal strength indicator
    Serial.print(LoRa.packetRssi());
    Serial.println("C");
  }
  ```

# Lab 13: LoRa one-to-many communication setup

Sending data packets from one Lora transmitter to multiple Lora receivers and retracing the same packets.

# Lab 14: Introduction to antenna modeling and simulation software 4NEC2.
4NEC2 is a popular antenna modeling and simulation tool based on the Numerical Electromagnetics Code (NEC). It allows users to design, analyze, and optimize antennas by simulating their performance in various configurations.

Key Features
Easy to Use: User-friendly interface suitable for beginners and experienced users alike.

Versatile Modeling: Supports various antenna types, including dipoles, Yagi-Uda, and more complex designs.

Visual Representation: Provides graphical visualization of antenna geometry and radiation patterns.

Post-Processing: Allows for in-depth analysis of results, including gain, radiation patterns, and impedance.

# Lab 15: Physical design of Dipole and V-dipole antennas
![WhatsApp Image 2024-07-05 at 15 33 26_f1340ef6](https://github.com/user-attachments/assets/8a7c26d3-d262-4b83-b1e1-44694de1d695)

Tune it to 433MHz with the help of NanoVNA-A Portable VNA Antenna Analyzer Kit with 10KHz-1.5GHz, 2.8 Inch Digital LCD Display Touching Screen Standing Wave Measuring Instrument.

CM Example new : Loaded dipole in free space CM antenna design.txt CE ' End of comment '

SY ylen=.1392 ' Symbol: Length for WL/2 SY zlen=.0975 SY ysma=.004095 SY zsma=.002867 '

GW 1 9 0 -ylen zlen 0 -ysma zsma .0001 ' Wire 1, 9 segments, halve wavelength long. GW 2 9 0 ysma zsma 0 ylen zlen .0001 ' Wire 2, 9 segments, halve wavelength long. GW 3 1 0 -ysma zsma 0 ysma zsma .0001 ' Wire 3, 9 segments, halve wavelength long GE 0 ' End of geometry '

LD 5 1 0 0 5.8001E7 ' Wire conductivity LD 5 2 0 0 5.8001E7 LD 5 3 0 0 5.8001E7

'

EX 0 3 1 0 1 0 ' Voltage source (1+j0) at wire 1 segment 5.

FR 0 1 0 0 433 0 ' Set design frequency (433 Mc).

EN ' End of NEC input

# Lab 16: Introduction to TinyGS
Tiny GS (Tiny Ground Station) is an open-source global network of ground stations designed to receive data from satellites. This network allows enthusiasts, researchers, and educational institutions to contribute and access satellite data, enhancing the ability to monitor and analyze various satellite signals and data transmissions.
![OIP](https://github.com/user-attachments/assets/9cd52177-94de-464a-9f69-3d91aea3afc2)

![Screenshot_13-7-2024_121855_tinygs com](https://github.com/user-attachments/assets/c85e07e5-4a1a-4cbd-9b77-d0a5f65bad20)

# Lab 17: Setting up a TinyGS ground station
![WhatsApp Image 2024-07-13 at 11 13 14_9e75c9f2](https://github.com/user-attachments/assets/05a82709-37f0-4955-9f01-fca33464c3fd)

![WhatsApp Image 2024-07-13 at 11 12 00_6ea4adc3](https://github.com/user-attachments/assets/56326bbc-88d8-49b2-a839-a1e7a082c498)

![WhatsApp Image 2024-07-13 at 11 11 59_883686fc](https://github.com/user-attachments/assets/4d911559-a3c2-42e4-aa52-2a656b3a4548)

Here is the information about all the packets we received.[Packets](https://github.com/AshritaSahoo/SIT-CUBESAT-AS/blob/main/PACKETS.xlsx)

