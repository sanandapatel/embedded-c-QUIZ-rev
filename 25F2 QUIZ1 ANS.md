# Embedded C Programming - Answers Only
## Combined Answer Key

---

# 24 july 

### Question 222 (3 marks)
**Answer:** Integrated development environment (IDE), Compiler

**Explanation:** IDE and Compiler are development tools, not components of the embedded system itself.

---

### Question 223 (3 marks)
**Answer:** No parity is used, Two stop bits are used

**Explanation:** In the dataframe parameter 7N2 @9600:
- 7 = 7 data bits
- N = No parity
- 2 = 2 stop bits
- @9600 = baud rate

---

### Question 224 (2 marks)
**Answer:** Retains data even after power loss (non-volatile)

**Explanation:** Flash memory is non-volatile, making it ideal for storing program code and data that must persist after power-off.

---

### Question 225 (2 marks)
**Answer:** To ensure timely and deterministic task execution

**Explanation:** RTOS provides real-time task scheduling with predictable execution times.

---

### Question 226 (2 marks)
**Answer:** ~ (tilde/NOT operator)

**Explanation:** The bitwise NOT operator (~) inverts all bits in a byte.

---

### Question 227 (2 marks)
**Answer:** Through an address and control signals

**Explanation:** CPU uses address bus to specify memory location and control signals (read/write) to perform operations.

---

### Question 228 (2 marks)
**Answer:** To convert analog signals into digital signals

**Explanation:** ADC (Analog-to-Digital Converter) converts continuous analog signals to discrete digital values.

---

### Question 229 (2 marks)
**Answer:** To generate precise time delays

**Explanation:** Timers are commonly used for generating accurate time delays and timing events.

---

### Question 230 (3 marks)
**Answer:** Interface with the external environment

**Explanation:** Peripherals (sensors, actuators, communication interfaces) allow the embedded system to interact with external devices.

---

### Question 231 (3 marks)
**Answer:** p = (int*)v;

**Explanation:** To assign a void pointer to an integer pointer, typecast the void pointer to int pointer type.

---

### Question 232 (3 marks)
**Answer:** 5

**Explanation:** 
- 6 in binary = 0110
- 3 in binary = 0011
- 6 XOR 3 = 0110 XOR 0011 = 0101 = 5

---

### Question 233 (3 marks)
**Answer:** 0x08

**Explanation:** 
- 3rd index bit (0-based from right) = bit position 3
- 2^3 = 8 = 0x08
- Mask = 0b00001000 = 0x08

---

### Question 234 (3 marks)
**Answer:** It waits for 1 second

**Explanation:** The delay() function pauses program execution for the specified milliseconds (1000 ms = 1 second).

---

### Question 235 (3 marks)
**Answer:** Using timer/counter peripherals

**Explanation:** PWM signals are typically generated using timer/counter hardware with compare registers.

---

### Question 236 (3 marks)
**Answer:** To divide the input frequency to a lower frequency

**Explanation:** A prescaler divides the system clock to generate slower clock signals for the timer.

---

### Question 237 (4 marks)
**Answer:** 0x33 (00110011 in binary)

**Explanation:**
- a = 0x0F = 00001111
- b = 0x3C = 00111100
- a XOR b = 00110011 = 0x33

---

### Question 238 (4 marks)
**Answer:** 0x4000000C

**Explanation:**
- Base address = 0x40000000
- Each register is 32 bits = 4 bytes
- Register addresses: 0x40000000, 0x40000004, 0x40000008, 0x4000000C
- Last (4th) register = 0x40000000 + (3 × 4) = 0x40000000 + 0x0C = 0x4000000C

---

### Question 239 (3 marks)
**Answer:** 0

**Explanation:**
- Dataframe: 111X0101
- Odd parity requires an odd number of 1s
- Current 1s (excluding X): 1+1+1+0+1+0+1 = 5
- If X = 0: total 1s = 5 (odd) ✓
- If X = 1: total 1s = 6 (even) ✗
- Therefore, X = 0

---

**24 J EC Total: 19 Questions | 50 Marks**

---
---

# 25-F-EC Answer Key

---

### Question 222 (0 marks)
**Answer:** YES (Confirmation question)

---

### Question 223 (2 marks)
**Answer:** Task-specific functionality and reliability

**Explanation:** Embedded systems are designed for specific dedicated tasks with high reliability requirements, unlike general-purpose systems.

---

### Question 224 (2 marks)
**Answer:** << (left shift operator)

**Explanation:** The << operator shifts bits to the left. Example: 5 << 1 = 10 (binary: 0101 << 1 = 1010)

---

### Question 225 (3 marks)
**Answer:** uint16_t

**Explanation:** 
- Maximum value = 1023 requires 10 bits (2^10 = 1024)
- uint8_t can only hold up to 255 (too small)
- uint16_t can hold up to 65535 (sufficient and memory-efficient)
- int and unsigned int typically use 32 bits (wasteful)

---

### Question 226 (3 marks)
**Answer:** 7

**Explanation:**
- 5 in binary = 0101
- 3 in binary = 0011
- 5 OR 3 = 0101 OR 0011 = 0111 = 7

---

### Question 227 (3 marks)
**Answer:** 0x08

**Explanation:**
- 3rd index bit (0-based from right) = bit position 3
- 2^3 = 8 = 0x08
- Mask = 0b00001000 = 0x08

---

### Question 228 (3 marks)
**Answer:** It waits for 2 second

**Explanation:** The delay() function pauses program execution for the specified milliseconds (2000 ms = 2 seconds).

---

### Question 229 (3 marks)
**Answer:** 1.22 mV

**Explanation:**
- Resolution = Full Range / 2^n
- Resolution = 5V / 2^12 = 5V / 4096 ≈ 1.22 mV
- This is the minimum voltage difference the ADC can distinguish.

---

### Question 230 (3 marks)
**Answer:** To divide the input clock frequency by a fixed factor

**Explanation:** A prescaler reduces the clock frequency to slow down the timer/counter, allowing longer timing periods.

---

### Question 231 (3 marks)
**Answer:** Instruction

**Explanation:** The Control Unit decodes and executes instructions fetched from memory, determining what operations to perform.

---

### Question 232 (3 marks)
**Answer:** Designed for high scalability and multitasking like general-purpose systems

**Explanation:** Embedded systems are typically designed for specific tasks with limited resources, not for high scalability and general-purpose multitasking.

---

### Question 233 (4 marks)
**Answer:** 0xFF (11111111 in binary)

**Explanation:**
- x = 0xA5 = 10100101
- y = 0x5A = 01011010
- x XOR y = 11111111 = 0xFF

---

### Question 234 (4 marks)
**Answer:** 0x50000014

**Explanation:**
- Base address = 0x50000000
- Each register is 32 bits = 4 bytes
- 6 registers: addresses from 0x50000000 to 0x50000014
- Register 0: 0x50000000
- Register 1: 0x50000004
- Register 2: 0x50000008
- Register 3: 0x5000000C
- Register 4: 0x50000010
- Register 5 (last): 0x50000014 = 0x50000000 + (5 × 4)

---

### Question 235 (2 marks)
**Answer:** Integration of peripherals, Low cost

**Explanation:** Microcontrollers integrate CPU, memory, and peripherals on a single chip, making them cost-effective and ideal for embedded applications.

---

### Question 236 (3 marks)
**Answer:** By using direct memory access (DMA), Through the use of address, data, and control buses

**Explanation:** The CPU uses buses for standard I/O operations and DMA for efficient data transfers without CPU intervention.

---

### Question 237 (3 marks)
**Answer:** The data frame uses even parity for error detection, One stop bit is used

**Explanation:** In the dataframe parameter 8E1 @4800:
- 8 = 8 data bits
- E = Even parity
- 1 = 1 stop bit
- @4800 = baud rate

---

### Question 238 (3 marks)
**Answer:** Developing a smart thermostat to control home temperature, Creating a simple automated irrigation system for a garden

**Explanation:** These are dedicated, resource-constrained applications ideal for microcontrollers. Gaming consoles and ML algorithms require the processing power of microprocessors.

---

### Question 239 (3 marks)
**Answer:** 0

**Explanation:**
- Dataframe: 1X110101
- Odd parity requires an odd number of 1s
- Current 1s (excluding X): 1+1+1+0+1+0+1 = 5
- If X = 0: total 1s = 5 (odd) ✓
- If X = 1: total 1s = 6 (even) ✗
- Therefore, X = 0

---



---

