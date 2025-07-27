# Microcontroller vs Microprocessor Notes

## Memory Requirements
- *Microcontroller:*
  - Very less memory required (from KBs to MBs).
- *Microprocessor:*
  - Requires more memory (MBs to GBs).

## Operating System
- *Microcontroller:*
  - No operating system (OS).
  - Note: Cannot run a full-fledged embedded OS on a microcontroller-based device.
- *Microprocessor:*
  - Supports OS like Windows, Linux, MacOS.

## Definitions
- Microcontroller in short is called *MCU*.

## Hardware Connections
- *Microcontrollers:*
  - All components are contained in a *single chip*.
- *Microprocessors:*
  - Components like memory, I/O controllers, and timers are connected through physical lines called *BUS*.

---

# Block Diagram of Microcontroller
- *Components:*
  - CPU (up to ~16 MHz)
  - Memory:
    - RAM
    - ROM (Settings)
  - I/O Ports (GPIO, USB, I2C, SPI, etc.)
  - Timers
  - A2D (Analog to Digital) / D2A (Digital to Analog) converters
- *Note:* All components are integrated into a *single chip*.

---



# Block Diagram of Microprocessor
- *CPU (High Speed ~1 GHz to 3.6 GHz)*
  - ALU (Arithmetic Logic Unit)
  - Registers
  - Timing
  - Control Unit
- *Interface through Buses:*
  - Address Bus
  - Data Bus
  - Control Bus
- *External Components:*
  - RAM
  - ROM
  - I/O Ports (SATA, USB, Serial I/O, etc.)
  - Timers/Counters

---

# Summary Differences
| Feature            | Microcontroller (MCU)         | Microprocessor           |
|--------------------|-------------------------------|--------------------------|
| Memory             | KBs to MBs                    | MBs to GBs               |
| OS                 | No OS                         | OS (Windows, Linux, Mac) |
| Clock Speed        | Up to 16 MHz                  | 1 GHz to 3.6 GHz         |
| Hardware Integration| All in one chip               | External components via bus|
| Applications       | Embedded systems, IoT, etc.   | Computers, servers, etc. |



# System on Chip (SoC) Notes

## What is SoC?
- *SoCs* are designed by combining some of the best features of *Microcontrollers* and *Microprocessors* into a single chip.

---

## System on Chip (SoC) Block Diagram

- *Processing Cores:*
  - Core 1
  - Core 2
  - Core 3
  - Core 4
- *Memory:* RAM/ROM
- *Bus System:* Connects all components internally
- *Peripherals:*
  - Audio
  - Bluetooth
  - Ethernet
  - I2C
  - SPI
  - UART
  - Universal Serial Bus (USB)
  - Timers
  - Analog to Digital Converters (ADC)

---

## Development Tools and OS Comparison

| Feature            | Microcontroller            | Microprocessor                          | SoC                                              |
|--------------------|----------------------------|------------------------------------------|--------------------------------------------------|
| *Development*    | - Arduino IDE<br>- Keil IDE | Full-fledged OS:<br>- Windows<br>- Linux<br>- macOS | - Arduino IDE<br>- Keil IDE<br>- Full OS (Embedded Linux variants) |
| *OS Support*     | No OS                      | Full-fledged OS                         | Embedded OS + Full OS                           |
| *Examples of OS* |                            |                                          | - Android (Linux)<br>- Tizen (Samsung Smart TV)<br>- webOS (LG)<br>- Android (Sony)<br>- OpenWRT (Routers) |
| *Description*    | All tools needed for embedded development are integrated into one software (IDE). | Runs desktop/server OS. | Combines embedded system flexibility with computing power of processors. |

---

## Notes
- SoCs use *Embedded Linux OS* (variant of Linux) for many consumer devices.
- Examples:
  - *Samsung Smart TV* → Tizen (Linux-based)
  - *LG Smart TV* → webOS (Linux-based)
  - *Sony Smart TV* → Android (Linux-based)
  - *Routers* → OpenWRT (Linux-based)

---

# Summary
- SoC combines:
  - The simplicity and integration of microcontrollers.
  - The processing power and OS capabilities of microprocessors.
- Suitable for smartphones, smart TVs, IoT devices, routers, etc.
