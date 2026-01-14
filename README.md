# Two-Step Verification Smart Lock

This project presents a dual-factor embedded smart lock system that enhances physical access security by combining RFID-based identification with keypad-based PIN authentication. The system is designed on an STM32 Nucleo-F446RE microcontroller and ensures access is granted only when both authentication factors are successfully validated.

The smart lock integrates an MFRC522 RFID reader, a 4×4 matrix keypad, and a PWM-controlled servo motor to perform secure, real-time access control. Visual and audible feedback is provided through multicolor LEDs, a 16×2 I²C LCD, and a passive buzzer. All authentication events are time-stamped using an RTC and logged over UART for auditing and debugging purposes.

The firmware is implemented in C using direct register-level programming and follows a deterministic finite-state machine architecture, enabling predictable timing, low latency, and reliable peripheral coordination. Experimental evaluation demonstrates consistent RFID detection, accurate keypad input capture, stable servo actuation, and robust system behavior under repeated operation.

This project provides a low-cost, scalable, and secure embedded access-control solution suitable for laboratory doors, dormitories, equipment lockers, and small-scale IoT security applications.

Technologies: STM32 (ARM Cortex-M4), C, SPI, I²C, UART, PWM, RFID, Embedded Systems  
Course: CSE 5342 – Embedded Systems  
**Institution:** University of Texas at Arlington (2025)

**Authors:**  
Rezwana Karim Roza  
Andrew Weiler  
Juliet Cuin
