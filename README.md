<center><h1> Raspberry Pi Pico </h1> </center>

<center>
<img
src="./img/Screenshot from 2022-07-09 16-24-58.png"
width=600
>
</center>

## Summary
In this repo I am going to save and document my learning and my learning materials for using the raspbberry pi pico. 

The RPI pico is a microcontroller running the RP2040 processor. it runs a dual core arm cortex M0+ processor with a clock speed of 133 MHz

---

## Learning materials

- [Raspberry Pi Pico github](https://raspberrypi.github.io/pico-sdk-doxygen/group__hardware.html)  
- [Raspberry Pi Pico and Pico W Documentation](https://www.raspberrypi.com/documentation/microcontrollers/raspberry-pi-pico.html)
    - [Raspberry Pi Pic C/C++ SDK](https://datasheets.raspberrypi.com/pico/raspberry-pi-pico-c-sdk.pdf)
- [Getting started with Raspberry Pico and CMake](https://admantium.medium.com/getting-started-with-raspberry-pico-and-cmake-f536e18512e6)


#### videos:

- [An Operating System on a $4 Board? | Getting Started with FreeRTOS on the Raspberry Pi Pico](https://youtu.be/5pUY7xVE2gU)

---

## Notes 

#### Programming the RPI Pico

In order to program the Pico we must first make the computer recognize it. we do so by utilizing the following steps:

1. push and hold the `BOOTSEL` button on the Pico when the pico is not connected to the computer
2. connect to you computer using a micro USB cable. 
3. Release BOOTSEL once the drive RPI-RP2 appears on your computer.
    
After recognizing the pico we must copy the `.UF2` binary file which was created during the compilation of the code.

---

## micro_ros_raspberrypi_pico_sdk

- github repository: [micro-ROS/micro_ros_raspberrypi_pico_sdk
](https://github.com/micro-ROS/micro_ros_raspberrypi_pico_sdk)




