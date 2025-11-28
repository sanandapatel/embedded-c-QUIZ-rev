# IIT Madras BS ES - Embedded C Programming
## QUESTION PAPER: EMBEDDED-Q2
**Exam:** Foundation Level - Embedded C Programming  
**Duration:** 120 minutes  
**Total Marks:** 90 (50 + 40)  
**Date:** November 2025

---

## **SECTION 1: EMBEDDED C PROGRAMMING**
**Section Marks:** 50  
**Number of Questions:** 18  
**Question Types:** MCQ, MSQ

---

### Question 1
**Type:** Multiple Choice Question  
**Marks:** 0  
**Question Label:** Confirmation Question

THIS IS QUESTION PAPER FOR THE SUBJECT "FOUNDATION / DIPLOMA LEVEL: EMBEDDED C PROGRAMMING (COMPUTER BASED EXAM)"

ARE YOU SURE YOU HAVE TO WRITE EXAM FOR THIS SUBJECT?

CROSS CHECK YOUR HALL TICKET TO CONFIRM THE SUBJECTS TO BE WRITTEN.

(IF IT IS NOT THE CORRECT SUBJECT, PLEASE CHECK THE SECTION AT THE TOP FOR THE SUBJECTS REGISTERED BY YOU)

**Options:**
- A) YES
- B) NO

---

### Question 2
**Type:** Multiple Choice Question  
**Marks:** 3  
**Question Label:** Controller Area Network (CAN) Protocol

Which of the following statements best describes the Controller Area Network (CAN) protocol?

**Options:**
- A) It uses a single master to control all communication on the bus
- B) It operates using point-to-point communication between devices
- C) It is a multi-master, message-oriented protocol that allows nodes to send and receive (not simultaneously)
- D) It does not support error detection or fault confinement

---

### Question 3
**Type:** Multiple Choice Question  
**Marks:** 3  
**Question Label:** TCP/IP Networking Layers

In TCP/IP networking, which layer is responsible for logical addressing and routing?

**Options:**
- A) Transport Layer
- B) Network Layer
- C) Data Link Layer
- D) Application Layer

---

### Question 4
**Type:** Multiple Choice Question  
**Marks:** 3  
**Question Label:** Data Transmission Modes

In which transmission mode can data be sent and received at the same time?

**Options:**
- A) Simplex
- B) Full-duplex
- C) Half-duplex
- D) Asynchronous

---

### Question 5
**Type:** Multiple Choice Question  
**Marks:** 3  
**Question Label:** Assembly Code - Register Values

What are the final values of AX and BX registers after executing the following assembly code snippet?

```
MOV AX, 80
MOV BX, 25
ADD AX, BX
MOV CX, 40
SUB BX, CX
```

**Options:**
- A) AX = 105, BX = -15
- B) AX = 120, BX = -15
- C) AX = 105, BX = 15
- D) AX = 120, BX = 15

---

### Question 6
**Type:** Multiple Choice Question  
**Marks:** 3  
**Question Label:** Interrupt Service Routine (ISR) Stack Management

If an interrupt service routine (ISR) fails to correctly manage the stack (e.g., not saving used registers), what is the most likely outcome?

**Options:**
- A) The ISR will execute faster
- B) The stack pointer will automatically reset
- C) The program may experience unpredictable behavior or crash after the ISR returns
- D) The ISR will execute multiple times

---

### Question 7
**Type:** Multiple Choice Question  
**Marks:** 3  
**Question Label:** Compilation Stage - Linking Object Files

Which compilation stage is responsible for combining multiple object files?

**Options:**
- A) Linking
- B) Preprocessing
- C) Compiling
- D) Assembling

---

### Question 8
**Type:** Multiple Choice Question  
**Marks:** 3  
**Question Label:** Non-Volatile Memory in Embedded Systems

In an embedded system, which of the following memory types is non-volatile and retains its contents even when the power is turned off?

**Options:**
- A) SRAM (Static Random Access Memory)
- B) Flash Memory
- C) DRAM (Dynamic Random Access Memory)
- D) Cache Memory

---

### Question 9
**Type:** Multiple Choice Question  
**Marks:** 3  
**Question Label:** Watchdog Timer - System Hang Detection

An embedded system occasionally becomes unresponsive due to a software bug that causes the main loop to hang. Which mechanism can automatically detect this condition and restore normal operation?

**Options:**
- A) Timer interrupt
- B) DMA Controller
- C) Watchdog timer
- D) Power-on reset circuit

---

### Question 10
**Type:** Multiple Choice Question  
**Marks:** 3  
**Question Label:** Bitwise XOR Operation

What is the result of the expression `0x5A ^ 0x3C`?

**Options:**
- A) 0x66
- B) 0x1A
- C) 0x7C
- D) 0x86

---

### Question 11
**Type:** Multiple Choice Question  
**Marks:** 3  
**Question Label:** Debugging Tools for Embedded Software

While developing embedded software, you want to find and fix bugs by running the program step-by-step, inspecting variables, and setting breakpoints. Which of the following tools is most appropriate for this task?

**Options:**
- A) Git
- B) Compiler
- C) Debugger
- D) None of these

---

### Question 12
**Type:** Multiple Choice Question  
**Marks:** 3  
**Question Label:** ISR Execution Time Optimization

In a real-time embedded system using an event-driven model, why is minimizing ISR execution time important?

**Options:**
- A) It increases flash memory endurance
- B) It reduces interrupt blocking and improves system responsiveness
- C) It allows the CPU to operate at a lower clock frequency
- D) It prevents hardware debouncing issues

---

### Question 13
**Type:** Multiple Choice Question  
**Marks:** 2  
**Question Label:** Wireless Protocol Selection - Smart Parking System

You are developing a smart parking system where each parking slot has a sensor that detects the presence of a car and transmits data to a nearby controller. The system should work within a single building, consume low power, and support many sensor nodes communicating reliably. Which wireless communication protocol would be most appropriate for this application?

**Options:**
- A) WiFi
- B) LTE
- C) Zigbee
- D) LoRa

---

### Question 14
**Type:** Multiple Choice Question  
**Marks:** 2  
**Question Label:** UART vs SPI Communication

Which of the following statements correctly differentiates UART communication from SPI?

**Options:**
- A) Both UART and SPI require a shared clock between master and slave
- B) UART is asynchronous and does not use a clock line, while SPI is synchronous and requires a clock signal
- C) UART supports multiple slaves directly, while SPI supports only one
- D) SPI transmits data only in one direction, while UART allows full-duplex communication

---

### Question 15
**Type:** Multiple Choice Question  
**Marks:** 2  
**Question Label:** Interrupt-Driven I/O vs Polling

Why do embedded systems frequently use interrupt-driven I/O instead of polling?

**Options:**
- A) It reduces clock frequency
- B) It increases code size
- C) It allows the CPU to remain in an idle or low-power state until an event occurs
- D) It disables multitasking

---

### Question 16
**Type:** Multiple Choice Question  
**Marks:** 4  
**Question Label:** Finite State Machine - Temperature Control System

A temperature monitoring embedded system uses a microcontroller connected to a temperature sensor through an ADC (Analog-to-Digital Converter). The system periodically reads the temperature every 2 seconds and triggers a cooling fan if the temperature exceeds 60°C. If the fan is ON and the temperature falls below 55°C, the fan is turned OFF.

**State Definitions:**
- STATE_IDLE: Fan OFF, waiting for temperature to rise
- STATE_COOLING: Fan ON, cooling in progress

**Event Definitions:**
- EVENT_TEMP_HIGH: Temperature ≥ 60°C
- EVENT_TEMP_LOW: Temperature ≤ 55°C

**Question:** If the current state is STATE_COOLING and EVENT_TEMP_LOW occurs, what will be the next state?

**Options:**
- A) STATE_IDLE
- B) STATE_FAULT
- C) STATE_SLEEP
- D) STATE_COOLING

---

### Question 17
**Type:** Multiple Choice Question  
**Marks:** 4  
**Question Label:** UART Transmission Time Calculation

A microcontroller transmits 500 bytes using 8N1 UART at 9600 bps. How long does the transmission take (approximate)?

**Options:**
- A) 380 ms
- B) 800 ms
- C) 520 ms
- D) 1.2 s

---

### Question 18
**Type:** Multiple Select Question  
**Marks:** 3  
**Question Label:** IPv4 Address Validation

Which of the following are invalid IPv4 addresses? (Select all that apply)

**Options:**
- A) 192.300.1.5
- B) 172.20.5.10
- C) 10.10.0.7
- D) 256.1.1.1
- E) 192.168.0.15

---

## **SECTION 2: ELECTRONIC SYSTEMS THINKING AND CIRCUITS**
**Section Marks:** 40  
**Number of Questions:** 19

*(Additional questions from Electronic Systems section would follow)*
*(Note: Only Section 1 questions provided in this document)*

---

**END OF QUESTION PAPER**

---

## **Document Information**

**Paper Structure:**
- Section 1: Embedded C Programming (18 questions, 50 marks)
- Section 2: Electronic Systems Thinking and Circuits (19 questions, 40 marks)
- Total: 37 questions, 90 marks
- Duration: 120 minutes

**Key Topics Tested:**
1. Communication Protocols (CAN, TCP/IP, UART, SPI)
2. Network Layers and Data Transmission
3. Assembly Language Programming
4. Interrupt Handling and Stack Management
5. Compilation Process and Linking
6. Memory Types (Volatile vs Non-Volatile)
7. System Reliability (Watchdog Timers)
8. Bitwise Operations
9. Debugging and Development Tools
10. Real-Time Systems and ISR Optimization
11. Wireless Communication Protocols
12. Finite State Machines
13. Serial Communication Calculations
14. IPv4 Addressing

**Question Distribution by Marks:**
- 0 marks (Confirmation): 1 question
- 2 marks: 2 questions
- 3 marks: 12 questions
- 4 marks: 3 questions
