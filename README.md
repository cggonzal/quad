# quad
electrical layout for a small quadcopter that fits on a single board. 

Code will be coming soon. In the mean time check out: [Make: Drones -- Teach an Arduino to Fly](https://www.amazon.com/Make-Drones-Teach-Arduino-Fly/dp/1680451715#:~:text=DRONES%3A%20TEACH%20AN%20ARDUINO%20TO%20FLY%20is%20one%20of%20the,enough%20to%20require%20FAA%20registration).

Overall design:
- Brushed Motors
- Off the shelf radio (may tweak design to make a custom receiver + radio transmitter pair)
- State estimation done with BNO085
- MCU is a raspberry pi pico (RP2040)

The goal of this project is for the design to be:
- easy to understand
- easy to manufacture
- easy to extend
