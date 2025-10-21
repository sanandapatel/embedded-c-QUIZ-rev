# Embedded C Programming - Questions Only

---

 *24 Jul*

---


---

### Question 222 (3 marks) - MSQ
Which of the following is/are NOT typical components of an embedded system?

**Options:**
- Processor
- Memory
- Integrated development environment (IDE)
- Sensors
- Input/Output (I/O) ports
- Compiler

---

### Question 223 (3 marks) - MSQ
Consider a dataframe with the parameters: **7N2 @9600**

Choose the correct option(s) according to the given dataframe parameters.

**Options:**
- The data frame uses even parity for error detection.
- The data frame uses odd parity for error detection.
- No parity is used.
- Two stop bits are used.
- One stop bit is used.

---

### Question 224 (2 marks) - MCQ
What is the main advantage of using flash memory in embedded systems?

**Options:**
- Low data storage capacity
- Faster read/write speeds than RAM
- Retains data even after power loss (non-volatile)
- None of these

---

### Question 225 (2 marks) - MCQ
What is the primary purpose of a real-time operating system (RTOS) in an embedded system?

**Options:**
- To manage power consumption
- To provide a user interface
- To ensure timely and deterministic task execution
- To handle multimedia processing

---

### Question 226 (2 marks) - MCQ
Which bitwise operator is used to invert all the bits in a byte?

**Options:**
- &
- |
- ^
- ~

---

### Question 227 (2 marks) - MCQ
How does the CPU interact with memory to perform read and write operations?

**Options:**
- By using dedicated I/O pins
- Through an address and control signals
- Via the ALU
- By directly manipulating registers

---

### Question 228 (2 marks) - MCQ
What is the primary function of an ADC in a microcontroller?

**Options:**
- To convert digital signals into analog signals
- To convert analog signals into digital signals
- To store digital data in memory
- To generate PWM signals

---

### Question 229 (2 marks) - MCQ
What is a primary use of timers in microcontrollers?

**Options:**
- To store large amounts of data
- To generate precise time delays
- To convert analog signals to digital
- To manage power consumption

---

### Question 230 (3 marks) - MCQ
What is the role of peripherals in an embedded system?

**Options:**
- Perform central processing tasks
- Interface with the external environment
- Store large amounts of data
- Perform Arithmetic and Logical operations

---

### Question 231 (3 marks) - MCQ
Which of the following typecasts is needed to assign a void pointer v to an integer pointer p in C?

**Options:**
- p = (int)v;
- p = (int*)&v;
- p = (int*)v;
- p = (void*)v;

---

### Question 232 (3 marks) - MCQ
What is the result of 6^3?

**Options:**
- 5
- 7
- 2
- 4

---

### Question 233 (3 marks) - MCQ
What should be the mask to check if the 3rd index bit (from the right) of a byte x is set to 1?

Consider 0-based indexing from right to left.

**Options:**
- 0x04
- 0x08
- 0x0C
- 0x10

---

### Question 234 (3 marks) - MCQ
What is the effect of the delay(1000); function call in the following Arduino code snippet?

```c
#define LED 13
void setup() {
pinMode(LED, OUTPUT);
}
void loop() {
digitalWrite(LED, HIGH);
delay(1000);
digitalWrite(LED, LOW);
delay(1000);
}
```

**Options:**
- It turns the LED off
- It waits for 1 second
- It sets the pin mode of the LED
- It toggles the state of the LED

---

### Question 235 (3 marks) - MCQ
What is a typical method to generate PWM signals in microcontrollers?

**Options:**
- Using analog comparators
- Using digital-to-analog converters
- Using timer/counter peripherals
- Using serial communication interface

---

### Question 236 (3 marks) - MCQ
What is the function of the prescaler in a timer module?

**Options:**
- To divide the input frequency to a lower frequency
- To amplify the input signal
- To convert digital signals to analog
- To generate a reset signal for the microcontroller

---

### Question 237 (4 marks) - MCQ
What is the result of the following bitwise XOR operation in embedded C?

```c
unsigned char a = 0x0F; // 00001111 in binary
unsigned char b = 0x3C; // 00111100 in binary
unsigned char result = a^ b;
```

**Options:**
- 0x23 (00100011 in binary)
- 0x33 (00110011 in binary)
- 0x1F (00011111 in binary)
- 0xCF (11001111 in binary)

---

### Question 238 (4 marks) - MCQ
Control registers for a GPIO peripheral start at address 0x40000000. There are 4 control registers, each of 32 bits each. What is the address of the last register?

**Options:**
- 0x40000004
- 0x4000000C
- 0x40000127
- 0x4000001F

---

### Question 239 (3 marks) - Short Answer
Consider a dataframe with 8 bits represented as **111X0101**, where X is a corrupted bit. The dataframe uses odd parity for error detection. What should be the value of X?

**Answer Type:** Numeric

---

**24 J EC Total: 19 Questions | 50 Marks**

---
---

*25-Feb*

---


**Options:**
- YES
- NO

---

### Question 223 (2 marks) - MCQ
What is a primary characteristic of embedded systems that distinguishes them from general-purpose computing systems?

**Options:**
- Task-specific functionality and reliability
- High scalability and multitasking capabilities
- Large storage and memory capacity
- Ability to run complex user applications

---

### Question 224 (2 marks) - MCQ
Which bitwise operator is used to shift the bits of a number to the left?

**Options:**
- <<
- >>
- &
- |

---

### Question 225 (3 marks) - MCQ
Which of the following data types would be most memory-efficient for storing an array of small integer numbers, given that the maximum magnitude of the numbers is 1023?

**Options:**
- int
- unsigned int
- uint16_t
- uint8_t

---

### Question 226 (3 marks) - MCQ
What is the result of 5 | 3 in context of C programming?

**Options:**
- 5
- 3
- 7
- 1

---

### Question 227 (3 marks) - MCQ
What should be the mask to check if the 3rd index bit (from the right) of a byte x is set to 1?

Consider 0-based indexing from right to left.

**Options:**
- 0x04
- 0x08
- 0x0C
- 0x10

---

### Question 228 (3 marks) - MCQ
What is the effect of the delay(2000); function call in the following Arduino code snippet?

```c
#define LED 13
void setup() {
pinMode(LED, OUTPUT);
}
void loop() {
digitalWrite(LED, HIGH);
delay(2000);
digitalWrite(LED, LOW);
delay(1000);
}
```

**Options:**
- It turns the LED off
- It waits for 2 second
- It sets the pin mode of the LED
- It toggles the state of the LED

---

### Question 229 (3 marks) - MCQ
If you use a 12-bit ADC to digitize a signal in the range of 0 to 5V, what is the minimum difference (approx) between two voltages that you can measure?

**Options:**
- 1.22 mV
- 3.50 mV
- 2.10 mV
- 0.25 mV

---

### Question 230 (3 marks) - MCQ
What is the primary function of a prescaler in a timer or counter module?

**Options:**
- To divide the input clock frequency by a fixed factor
- To multiply the input frequency for faster counting
- To convert analog input into digital signals for counting
- To automatically reset the timer when it overflows

---

### Question 231 (3 marks) - MCQ
Which of the following determines the operation that the Control Unit (CU) of a microcontroller performs?

**Options:**
- Clock
- Registers
- Instruction
- Temperature

---

### Question 232 (3 marks) - MCQ
Which of the following is NOT a characteristic of an embedded system?

**Options:**
- Performs a dedicated function
- Limited resources
- Designed for high scalability and multitasking like general-purpose systems
- Real-time operation

---

### Question 233 (4 marks) - MCQ
What is the result of the following bitwise XOR operation in embedded C?

```c
unsigned char x = 0xA5; // 10100101 in binary
unsigned char y = 0x5A; // 01011010 in binary
unsigned char result = x ^ y;
```

**Options:**
- 0xFF (11111111 in binary)
- 0x1F (00011111 in binary)
- 0xF0 (11110000 in binary)
- 0x5F (01011111 in binary)

---

### Question 234 (4 marks) - MCQ
The control registers for a UART peripheral start at address 0x50000000. There are 6 control registers, each of 32 bits. What is the address of the last register?

**Options:**
- 0x50000018
- 0x5000001C
- 0x50000014
- 0x50000010

---

### Question 235 (2 marks) - MSQ
For which of the following reasons are microcontrollers commonly chosen over microprocessors in embedded system applications?

**Options:**
- Integration of peripherals
- High clock speeds
- Advanced multitasking capabilities
- Low cost

---

### Question 236 (3 marks) - MSQ
How does the CPU communicate with peripherals to perform input/output operations?

**Options:**
- By using direct memory access (DMA)
- Through the use of address, data, and control buses
- By directly accessing the system clock
- By executing only arithmetic operations

---

### Question 237 (3 marks) - MSQ
Consider a dataframe with the parameters: **8E1 @4800**

Choose the correct option(s) according to the given dataframe parameters.

**Options:**
- The data frame uses even parity for error detection.
- The data frame uses odd parity for error detection.
- No parity is used.
- Two stop bits are used.
- One stop bit is used.

---

### Question 238 (3 marks) - MSQ
In which of the following scenarios would you typically choose a microcontroller (MCU) over a microprocessor (MPU)?

**Options:**
- Developing a smart thermostat to control home temperature.
- Designing a high-speed gaming console.
- Building a machine-learning algorithm for financial predictions.
- Creating a simple automated irrigation system for a garden.

---

### Question 239 (3 marks) - Short Answer
Consider a dataframe with 8 bits represented as **1X110101**, where X is a corrupted bit. The dataframe uses odd parity for error detection. What should be the value of X?

**Answer Type:** Numeric

---

