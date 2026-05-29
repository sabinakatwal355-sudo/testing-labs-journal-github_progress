# Part 4 – Raspberry Pi Hardware Identification
Upload:
```
images/raspberry-pi/pi-board.jpg
images/raspberry-pi/labelled-pi-board.jpg
```
---

| Component | Function |
|-----------|----------|
| SoC | System on a Chip; integrates the CPU, GPU, and main memory into a single chip to process all computing tasks efficiently.|
| GPIO |General Purpose Input/Output pins; used to connect and communicate with external hardware electronic components like sensors, LEDs, and motors. |
| USB | Universally connects peripheral devices such as a keyboard, mouse, or external storage drives to transfer data.|
| HDMI |High-Definition Multimedia Interface; transmits high-quality digital video and audio signals from the Pi to a monitor or TV. |
| Power |Supplies the necessary electrical current (usually via USB-C or Micro-USB) to power the board's electronics safely. |
| microSD |Acts as the primary storage drive; holds the Operating System (like Raspberry Pi OS), applications, and user files.   |
| Network |Provides an Ethernet port for a stable, wired local network and internet connection. |
| Wireless | Built-in chip that enables wireless internet connectivity (Wi-Fi) and short-range device pairing (Bluetooth).|

---
## Reflection
Why are many components integrated into a single board in embedded computers such as the Raspberry Pi?
Write **100 words**.
mbedded computers like the Raspberry Pi integrate components into a single board to optimize size, cost, and power efficiency. By using a System on a Chip (SoC) that combines the central processing unit, graphics processing unit, and system memory, the physical footprint is drastically reduced. This allows the device to fit into compact, portable projects where a traditional, modular computer setup would be way too bulky.

This single-board design also eliminates the need for large expansion slots, heavy sockets, and complex internal wiring connectors, which significantly lowers manufacturing and assembly costs. From a performance standpoint, placing the core components in close physical proximity to one another minimizes data latency because electrical signals have shorter distances to travel. It also reduces overall power consumption and limits heat generation. This makes single-board computers highly reliable, energy-efficient, and ideal for dedicated, small-scale computing tasks and smart hardware projects.
