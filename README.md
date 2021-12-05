# Smart Wearable Health Monitoring System
![cover](https://github.com/adhamaly/Smart-Wearable-Health-Monitoring-System/blob/main/images/cover.jpg)

The main purpose of the project is to help people to monitor main information about their heart health (BPM), to know whether they are suffering from any heart disease using smart wearable device that will collect basic data like heart rate, using the techniques of machine learning in an android app that help in determining the status of user Our project is oriented to normal users (especially old people) .

#  Demo
![enter image description here](https://github.com/adhamaly/Smart-Wearable-Health-Monitoring-System/blob/main/images/WhatsApp%20Image%202020-07-13%20at%204.43.17%20AM%20%282%29.jpeg)

# Used Software & Hardware



**4.1 ATmega32 Microcontroller**

**4.1.1 Overview**

The Atmel AVR ATmega32 is a high-performance, low-power Microchip 8-bit AVR RISC-based microcontroller combines 32KB ISP flash memory with read-while-write capabilities, 1KB EEPROM, 2KB SRAM, 54/69 general purpose I/O lines, 32 general purpose working registers, a JTAG interface for boundary-scan and on-chip debugging/programming, three flexible timer/counters with compare modes, internal and external interrupts, serial programmable USART, a universal serial interface (USI) with start condition detector, an 8-channel 10-bit A/D converter, programmable watchdog timer with internal oscillator, SPI serial port, and five software selectable power saving modes. The device operates between 1.8-5.5 volts.

![enter image description here](https://github.com/adhamaly/Smart-Wearable-Health-Monitoring-System/blob/main/images/at_pins.jpg)



**4.2 Pulse Sensor**

**4.2.1 Pulse sensor working principle**

The working of the Pulse/Heart beat sensor is very simple. The sensor has two sides, on one side the LED is placed along with an ambient light sensor and on the other side we have some circuitry. This circuitry is responsible for the amplification and noise cancellation work. The LED on the front side of the sensor is placed over a vein in our human body. This can either be your Finger tip or you ear tips, but it should be placed directly on top of a vein.
Now the LED emits light which will fall on the vein directly. The veins will have blood flow inside them only when the heart is pumping, so if we monitor the flow of blood we can monitor the heart beats as well. If the flow of blood is detected then the ambient light sensor will pick up more lights since they will be reflected ted by the blood, this minor change in received light is analyzed over time to determine our heart beats.

![enter image description here](https://github.com/adhamaly/Smart-Wearable-Health-Monitoring-System/blob/main/images/11574-04_pulseSensor.jpg)
