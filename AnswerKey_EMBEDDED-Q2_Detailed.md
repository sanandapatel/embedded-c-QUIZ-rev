# IIT Madras BS ES - Embedded C Programming
## ANSWER KEY: EMBEDDED-Q2



---




---

### Q2 – CAN Protocol
- Correct Answer: C  
- Short Theory: CAN is a multi‑master, message‑oriented protocol. Any node can try to send messages on the bus, and messages are identified by IDs rather than fixed source–destination pairs.

---

### Q3 – TCP/IP Layer for Addressing and Routing
- Correct Answer: B (Network Layer)  
- Short Theory: The Network layer handles logical IP addressing and routing of packets between different networks.

---

### Q4 – Transmission Mode (Send and Receive at Same Time)
- Correct Answer: B (Full‑duplex)  
- Short Theory: Full‑duplex mode allows data to be sent and received simultaneously over the communication channel.

---

### Q5 – Assembly Registers Result
- Correct Answer: A (AX = 105, BX = −15)  
- Short Theory: AX is increased by adding 80 and 25. BX is decreased by subtracting 40 from 25, giving a negative result stored in two’s‑complement form.

---

### Q6 – ISR Not Managing Stack
- Correct Answer: C  
- Short Theory: If an ISR does not save and restore the registers it uses, it corrupts the main program’s register values, which can cause unpredictable behaviour or a crash when the ISR returns.

---

### Q7 – Stage Combining Object Files
- Correct Answer: A (Linking)  
- Short Theory: The linker takes multiple object files and combines them into a single executable, resolving symbol references between them.

---

### Q8 – Non‑Volatile Memory
- Correct Answer: B (Flash Memory)  
- Short Theory: Flash memory keeps its contents even when power is removed, so program code and configuration are usually stored there. SRAM, DRAM, and cache lose data on power‑off.

---

### Q9 – Recovering from Main Loop Hang
- Correct Answer: C (Watchdog timer)  
- Short Theory: A watchdog timer resets the system if the software stops “kicking” it, which allows automatic recovery when the main loop hangs.

---

### Q10 – Bitwise XOR Result
- Correct Answer: A (0x66)  
- Short Theory: XOR outputs 1 where the bits of the two operands differ and 0 where they are the same. Applying this to 0x5A and 0x3C gives 0x66.

---

### Q11 – Tool for Step‑by‑Step Debugging
- Correct Answer: C (Debugger)  
- Short Theory: A debugger lets you run the program step‑by‑step, inspect variables, and set breakpoints, which is exactly what is needed for interactive debugging.

---

### Q12 – Short ISR in Real‑Time Systems
- Correct Answer: B  
- Short Theory: Keeping ISRs short reduces the time interrupts are blocked, so other interrupts can be handled quickly and the system remains responsive.

---

### Q13 – Wireless for Smart Parking
- Correct Answer: C (Zigbee)  
- Short Theory: Zigbee is designed for many low‑power nodes in a small area, like sensors in a building, and supports reliable mesh networking with low energy use.

---

### Q14 – UART vs SPI
- Correct Answer: B  
- Short Theory: UART is asynchronous and does not use a shared clock line. SPI is synchronous and requires a clock signal from the master.

---

### Q15 – Interrupt‑Driven I/O vs Polling
- Correct Answer: C  
- Short Theory: With interrupt‑driven I/O, the CPU can stay idle or in a low‑power mode until an event occurs, instead of continuously polling and wasting power.

---

### Q16 – Temperature FSM Next State
- Correct Answer: A (STATE_IDLE)  
- Short Theory: When the system is in STATE_COOLING and the temperature falls below the lower threshold, the fan can be turned off and the FSM returns to the idle state.

---

### Q17 – UART Transmission Time
- Correct Answer: C (≈ 520 ms)  
- Short Theory: With 8N1, each byte uses 10 bits (1 start + 8 data + 1 stop). For 500 bytes, that is 5000 bits. At 9600 bits per second, the time is a little over 0.5 seconds (about 520 ms).

---

### Q18 – Invalid IPv4 Addresses
- Correct Answers: A and D  
- Short Theory: Each IPv4 octet must be in the range 0–255. Addresses with 300 or 256 in any position are invalid; the others have all octets in the valid range.

---
