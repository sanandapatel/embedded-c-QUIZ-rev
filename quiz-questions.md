# Embedded C Programming Quiz - Questions


---

## Question 232 (3 marks)
**Which of the following is a key requirement of embedded systems?**

- A. Real-time operation and compact design
- B. Extensive memory capacity
- C. Flexibility in interaction mechanisms
- D. Unlimited processing power

---

## Question 233 (3 marks)
**What is the primary purpose of a real-time operating system (RTOS) in an embedded system?**

- A. To manage power consumption
- B. To provide a user interface
- C. To ensure timely and deterministic task execution
- D. To handle multimedia processing

---

## Question 234 (3 marks)
**You need to store the number of milliseconds elapsed in a microcontroller program. The value can go up to 100,000 ms. Which of the following data types is most appropriate?**

- A. uint8_t
- B. int8_t
- C. uint32_t
- D. int16_t

---

## Question 235 (3 marks)
**What is the result of shifting the 8-bit number 0x12 (00010010 in binary) 2 bits to the left in C?**

- A. 0x04
- B. 0x08
- C. 0x48
- D. 0x24

---

## Question 236 (3 marks)
**What is the result of the expression `6 | 3` in C programming?**

- A. 7
- B. 2
- C. 1
- D. 0

---

## Question 237 (3 marks)
**What does the following C expression do, assuming x and mask are 8-bit unsigned integers?**

```c
x | mask
```

- A. It clears the bits specified in mask in x
- B. It sets the bits specified in mask in x
- C. It toggles the bits specified in mask in x
- D. It leaves x unchanged

---

## Question 238 (3 marks)
**In the following Arduino code, what is the purpose of `digitalWrite(13, HIGH);`?**

```c
void setup() {
  pinMode(13, OUTPUT);
}

void loop() {
  digitalWrite(13, HIGH);
  delay(500);
  digitalWrite(13, LOW);
  delay(500);
}
```

- A. It reads the digital value from pin 13
- B. It sets pin 13 to HIGH, turning on the LED
- C. It sets pin 13 as an input
- D. It writes an analog value to pin 13

---

## Question 239 (3 marks)
**Which communication protocol is commonly used for asynchronous serial communication between a microcontroller and a computer, using separate lines for transmitting (TX) and receiving (RX) data?**

- A. SPI (Serial Peripheral Interface)
- B. I2C (Inter-Integrated Circuit)
- C. UART (Universal Asynchronous Receiver-Transmitter)
- D. CAN (Controller Area Network)

---

## Question 240 (3 marks)
**In a microcontroller, if you want a timer to trigger an interrupt every 0.5 seconds but the timer's maximum count is limited, which technique can you use?**

- A. Reduce the system clock frequency
- B. Use a prescaler to divide the timer clock
- C. Change the timer's output polarity
- D. Increase the RAM size

---

## Question 241 (3 marks)
**Which component of a microcontroller is responsible for decoding instructions and controlling the operation of other units?**

- A. Arithmetic Logic Unit (ALU)
- B. RAM
- C. Control Unit (CU)
- D. Flash Memory

---

## Question 242 (2 marks)
**Which of the following features makes a microcontroller suitable for low-power embedded applications?**

- A. Integrated peripherals and low-power modes
- B. High-end graphics processing capability
- C. Ability to run multiple desktop applications
- D. Requires a full-featured operating system

---

## Question 243 (2 marks)
**In which of the following scenarios would a microprocessor (MPU) be more appropriate than a microcontroller (MCU)?**

- A. Designing a temperature sensor for an oven
- B. Controlling an automatic irrigation system
- C. Running a desktop operating system for a personal computer
- D. Managing a simple LED display panel

---

## Question 244 (2 marks)
**If you use a 10-bit ADC to digitize a signal in the range of 0 to 5V, what is the minimum difference (approx) between two voltages that you can measure?**

- A. 0.002V
- B. 0.007V
- C. 0.005V
- D. 0.01V

---

## Question 245 (4 marks)
**What is the result of the following bitwise AND operation in embedded C?**

```c
unsigned char a = 0xF0; // 11110000 in binary
unsigned char b = 0x3C; // 00111100 in binary
unsigned char result = a & b;
```

- A. 0x30 (00110000 in binary)
- B. 0xFC (11111100 in binary)
- C. 0x0C (00001100 in binary)
- D. 0xFF (11111111 in binary)

---

## Question 246 (4 marks)
**You are programming a microcontroller and want to configure a GPIO port. The base address of the GPIO port is `0x50000000`, and each GPIO register is 32 bits (4 bytes) wide. If there are 10 consecutive registers, what is the address of the 5th register (counting from index 0)?**

- A. 0x50000008
- B. 0x50000012
- C. 0x50000010
- D. 0x5000001

---

## Question 247 (3 marks - Short Answer)
**Consider an 8-bit data frame with even parity:**

```
Data + Parity: 1 X 1 1 0 1 0 1 0
```

- X is a corrupted bit in the data.
- 0 at the end is the **even parity** bit for the frame.

If the received frame has correct parity, what should be the value of X?

**Answer Type:** Numeric

---

## Question 248 (3 marks - Multiple Select)
**Which of the following UART configurations would correspond to a data frame with 8 data bits, no parity, and 1 stop bit?**

- A. 7O2 @9600
- B. 7E1 @19200
- C. 8N1 @115200
- D. 8N1 @9600
- E. 8E2 @480