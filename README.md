# Smart Wearable Health Monitoring System
![cover](https://github.com/adhamaly/Smart-Wearable-Health-Monitoring-System/blob/main/images/cover.jpg)

The main purpose of the project is to help people to monitor main information about their heart health (BPM), to know whether they are suffering from any heart disease using smart wearable device that will collect basic data like heart rate, using the techniques of machine learning in an android app that help in determining the status of user Our project is oriented to normal users (especially old people) .

#  Demo
![enter image description here](https://github.com/adhamaly/Smart-Wearable-Health-Monitoring-System/blob/main/images/WhatsApp%20Image%202020-07-13%20at%204.43.17%20AM%20%282%29.jpeg)

# Used Software & Hardware



**1.  ATmega32 Microcontroller**

**1.1 Overview**

The Atmel AVR ATmega32 is a high-performance, low-power Microchip 8-bit AVR RISC-based microcontroller combines 32KB ISP flash memory with read-while-write capabilities, 1KB EEPROM, 2KB SRAM, 54/69 general purpose I/O lines, 32 general purpose working registers, a JTAG interface for boundary-scan and on-chip debugging/programming, three flexible timer/counters with compare modes, internal and external interrupts, serial programmable USART, a universal serial interface (USI) with start condition detector, an 8-channel 10-bit A/D converter, programmable watchdog timer with internal oscillator, SPI serial port, and five software selectable power saving modes. The device operates between 1.8-5.5 volts.

![enter image description here](https://github.com/adhamaly/Smart-Wearable-Health-Monitoring-System/blob/main/images/at_pins.jpg)




**2. Pulse Sensor**

**2.1 Pulse sensor working principle**

The working of the Pulse/Heart beat sensor is very simple. The sensor has two sides, on one side the LED is placed along with an ambient light sensor and on the other side we have some circuitry. This circuitry is responsible for the amplification and noise cancellation work. The LED on the front side of the sensor is placed over a vein in our human body. This can either be your Finger tip or you ear tips, but it should be placed directly on top of a vein.
Now the LED emits light which will fall on the vein directly. The veins will have blood flow inside them only when the heart is pumping, so if we monitor the flow of blood we can monitor the heart beats as well. If the flow of blood is detected then the ambient light sensor will pick up more lights since they will be reflected ted by the blood, this minor change in received light is analyzed over time to determine our heart beats.

![enter image description here](https://github.com/adhamaly/Smart-Wearable-Health-Monitoring-System/blob/main/images/11574-04_pulseSensor.jpg)


## Libraries support Embedded System (Implemented from Scratch using Embedded C)

**1. Software module ADC Library/Driver**
 it is a Software module ADC Driver which represent interface to ADC (Analog To Digital Converter) Hardware circuit in Microcontroller which is used for convert analog signals into digital signals to be proceeds by Micro-processor in Microcontroller
 
**2. LCD driver**
It is a software driver/library which developed for enabling Microcontroller interact with it LCD for sending data to LCD display.

**3.  Timer driver**
It is a software driver/library which represent interface for handling TIMER module in Microcontroller.

**4. UART (Bluetooth communication) Library/driver**
Bluetooth module based on UART communication module which used for Serial communication 

## Android Used API 

**1. Android Bluetooth APIs**
these APIs let applications wirelessly connect to other Bluetooth devices, enabling point-to-point and multipoint wireless features.
Using the Bluetooth APIs, an Android application can perform the following:
- Scan for other Bluetooth devices
- Query the local Bluetooth adapter for paired Bluetooth devices
- Transfer data to and from other devices
        
    Key classes and interfaces

[BluetoothAdapter](https://developer.android.com/reference/android/bluetooth/BluetoothAdapter) is the entry-point for all Bluetooth interaction. Using this, you can discover other Bluetooth devices, query a list of bonded (paired) devices

[BluetoothDevice](https://developer.android.com/reference/android/bluetooth/BluetoothDevice)
Represents a remote Bluetooth device. Use this to request a connection with a remote device through a [BluetoothSocket](https://developer.android.com/reference/android/bluetooth/BluetoothSocket) or query information about the device such as its name, address, class, and bonding state.

[BluetoothSocket](https://developer.android.com/reference/android/bluetooth/BluetoothSocket)
Represents the interface for a Bluetooth socket (similar to a TCP [Socket](https://developer.android.com/reference/java/net/Socket)). This is the connection point that allows an application to exchange data with another Bluetooth device using [InputStream](https://developer.android.com/reference/java/io/InputStream) and [OutputStream](https://developer.android.com/reference/java/io/OutputStream).
