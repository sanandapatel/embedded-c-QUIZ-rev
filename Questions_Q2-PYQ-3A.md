# IIT Madras BS ES - Embedded C Programming
## Question Paper: Q2-PYQ-3A
**Exam:** Foundation Level - Embedded C Programming  
**Duration:** 120 minutes  
**Total Marks:** 540  
**Date:** March 2025

---

## **SECTION 1: EMBEDDED C PROGRAMMING**
**Section Marks:** 50  
**Total Questions:** 18

### Question 1
**Type:** Multiple Choice Question  
**Marks:** 0

THIS IS QUESTION PAPER FOR THE SUBJECT "FOUNDATION / DIPLOMA LEVEL : EMBEDDED C PROGRAMMING (COMPUTER BASED EXAM)"

ARE YOU SURE YOU HAVE TO WRITE EXAM FOR THIS SUBJECT?

CROSS CHECK YOUR HALL TICKET TO CONFIRM THE SUBJECTS TO BE WRITTEN.

(IF IT IS NOT THE CORRECT SUBJECT, PLS CHECK THE SECTION AT THE TOP FOR THE SUBJECTS REGISTERED BY YOU)

**Options:**
- YES
- NO

---

### Question 2
**Type:** Multiple Select Question  
**Marks:** 3

**Which of the following is/are not valid IPv4 addresses?**

**Options:**
- 300.25.50.100
- 172.16.254.1
- 10.0.300.5
- 192.168.0.256
- 203.120.45.60

---

### Question 3
**Type:** Multiple Choice Question  
**Marks:** 3

**Which of the following is NOT a characteristic of SPI communication?**

**Options:**
- Full-duplex data transmission
- Requires a clock signal (SCK)
- Uses start and stop bits for framing
- Supports multiple slave devices

---

### Question 4
**Type:** Multiple Choice Question  
**Marks:** 3

**Which of the following is an example of a connection-oriented communication protocol?**

**Options:**
- UDP
- TCP
- ICMP
- DHCP

---

### Question 5
**Type:** Multiple Choice Question  
**Marks:** 3

**Which of the following is a key advantage of using serial communication over parallel communication in embedded systems?**

**Options:**
- It eliminates the need for data synchronization
- It allows for simultaneous data transfer across multiple lines
- It reduces the number of required I/O pins
- It always provides higher data transfer rates

---

### Question 6
**Type:** Multiple Choice Question  
**Marks:** 3

**What are the final values of AX and BX registers after executing the following assembly code snippet?**

```
MOV AX, 25
MOV BX, 15
SUB AX, BX
MOV CX, 8
ADD BX, CX
```

**Options:**
- AX = 10, BX = 23
- AX = 10, BX = 8
- AX = 40, BX = 23
- AX = 40, BX = 8

---

### Question 7
**Type:** Multiple Choice Question  
**Marks:** 3

**What happens when a microcontroller receives an interrupt request?**

**Options:**
- The CPU immediately executes the main program loop
- The interrupt vector table is checked to find the appropriate ISR
- The microcontroller resets and restarts execution
- The interrupt request is ignored until the program finishes execution

---

### Question 8
**Type:** Multiple Choice Question  
**Marks:** 3

**What is the primary role of a linker in an embedded system?**

**Options:**
- It converts source code into machine code
- It loads the executable code into memory for execution
- It resolves symbol references and combines object files into a single executable
- It manages memory allocation during program execution

---

### Question 9
**Type:** Multiple Choice Question  
**Marks:** 3

**Which of the following design patterns is most suitable for decoupling a system's components and promoting communication through event-based mechanisms?**

**Options:**
- Observer Pattern
- Singleton Pattern
- Factory Pattern
- Command Pattern

---

### Question 10
**Type:** Multiple Choice Question  
**Marks:** 3

**Which of the following is the most effective method to manage power consumption in an embedded system during periods of inactivity?**

**Options:**
- Keep the system running at full speed
- Use sleep or low-power modes
- Turn off the system entirely
- Increase the processor clock frequency

---

### Question 11
**Type:** Multiple Choice Question  
**Marks:** 3

**What is the result of the expression 0xA5 & 0x3F?**

**Options:**
- 0x15
- 0x25
- 0x35
- 0x5A

---

### Question 12
**Type:** Multiple Choice Question  
**Marks:** 3

**What is the primary role of a makefile in a software project?**

**Options:**
- To provide code templates
- To manage code versioning
- To help compile and link code
- To improve runtime performance

---

### Question 13
**Type:** Multiple Choice Question  
**Marks:** 3

**What is the role of an Event Handler in an event-driven architecture?**

**Options:**
- To process user inputs from keyboards
- To manage power states of the system
- To define actions in response to specific events
- To synchronize tasks in a multi-threaded environment

---

### Question 14
**Type:** Multiple Choice Question  
**Marks:** 2

**Which wireless communication protocol is best suited for short-range, low-power applications such as smart home automation and sensor networks?**

**Options:**
- LoRa
- WiFi
- LTE
- Zigbee

---

### Question 15
**Type:** Multiple Choice Question  
**Marks:** 2

**Which communication protocol is widely used in both automotive and industrial applications due to its robustness, real-time capabilities, and fault tolerance?**

**Options:**
- CAN
- Profibus
- ModBus
- Ethernet/IP

---

### Question 16
**Type:** Multiple Choice Question  
**Marks:** 2

**What is the primary advantage of using interrupt-driven programming in embedded systems?**

**Options:**
- It reduces power consumption by allowing the CPU to sleep until needed
- It eliminates the need for a microcontroller in the system
- It ensures that all tasks run at a fixed time interval
- It increases CPU usage by continuously polling for events

---

### Question 17
**Type:** Multiple Choice Question  
**Marks:** 4

**Consider the following FSM controls a motor with four states:**

**States:**
1. STATE_STOPPED - The motor is stopped
2. STATE_RUNNING_LOW - The motor is running at low speed
3. STATE_RUNNING_HIGH - The motor is running at high speed
4. STATE_OVERSPEED - The motor has exceeded the safe speed limit

**Events:**
1. EVENT_BUTTON_PRESS - The button is pressed
2. EVENT_SPEED_THRESHOLD - The speed crosses a predefined threshold
3. EVENT_OVERSPEED_ALARM - The motor exceeds the safe speed limit
4. EVENT_RESET - A reset signal is received

**Code:**
```c
void handleEvent(Event_t event) {
    switch (currentState) {
        case STATE_STOPPED:
            if (event == EVENT_BUTTON_PRESS) {
                currentState = STATE_RUNNING_LOW;
            }
            break;
        case STATE_RUNNING_LOW:
            if (event == EVENT_BUTTON_PRESS) {
                currentState = STATE_RUNNING_HIGH;
            }
            break;
        case STATE_RUNNING_HIGH:
            if (event == EVENT_SPEED_THRESHOLD) {
                currentState = STATE_OVERSPEED;
            } else if (event == EVENT_BUTTON_PRESS) {
                currentState = STATE_STOPPED;
            }
            break;
        case STATE_OVERSPEED:
            if (event == EVENT_RESET) {
                currentState = STATE_RUNNING_LOW;
            } else if (event == EVENT_BUTTON_PRESS) {
                currentState = STATE_STOPPED;
            }
            break;
        default:
            currentState = STATE_STOPPED;
            break;
    }
}
```

**If the current state is STATE_RUNNING_HIGH, and two events occur in sequence:**
1. EVENT_SPEED_THRESHOLD
2. EVENT_BUTTON_PRESS

**What will be the final state after processing both events?**

**Options:**
- STATE_STOPPED
- STATE_RUNNING_LOW
- STATE_RUNNING_HIGH
- STATE_OVERSPEED

---

### Question 18
**Type:** Multiple Choice Question  
**Marks:** 4

**A system transmits 500 bytes of data using the 8N1 protocol at a baud rate of 115200 bps. What is the minimum time required to complete the transmission?**

**Options:**
- 34.72 milliseconds
- 43.40 milliseconds
- 52.08 milliseconds
- 67.50 milliseconds

---

## **SECTION 2: ELECTRONIC SYSTEMS THINKING AND CIRCUITS**
**Section Marks:** 40  
**Total Questions:** 19

### Question 19
**Type:** Multiple Choice Question  
**Marks:** 0

THIS IS QUESTION PAPER FOR THE SUBJECT "FOUNDATION LEVEL : ELECTRONIC SYSTEMS THINKING AND CIRCUITS (COMPUTER BASED EXAM)"

ARE YOU SURE YOU HAVE TO WRITE EXAM FOR THIS SUBJECT?

CROSS CHECK YOUR HALL TICKET TO CONFIRM THE SUBJECTS TO BE WRITTEN.

(IF IT IS NOT THE CORRECT SUBJECT, PLS CHECK THE SECTION AT THE TOP FOR THE SUBJECTS REGISTERED BY YOU)

---

**END OF QUESTION PAPER**
