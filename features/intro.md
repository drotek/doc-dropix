#Introduction to the Dropix autopilot

<p align="justify">The **Dropix** is an autopilot manufactured by the french technology company Drotek. Available since 2013, the autopilot is well reknown around the world for it is one of the most complete french autopilots available on the market. 

Developped and upgraded multiple times during the last years, it is built for anyone looking to provide its vehicle with a reliable, easy to use and powerful autopilot that's affordable and built with high standards of quality.</p> 

<p align="center">
  <img src="./images/ico1.png?raw=true" alt="Hardware"/>
</p>

<p align="justify">The FMU is an **STM32F427VIT6** microchip from _ST-Electronics_, picked for it's great versatility, offering great power and responsiveness with its ARM® 32-bit Cortex®-M4 CPU running a **real-time NuttX operating system**.

The IO processor is an **STM32F100C8T6B** microchip, interacting with all inputs and outputs on the board with its ARM®Cortex®-M3 32-bit RISC core. It allows a fast communication with the external devices and the FMU for the best performances. 

It comes with four sensors, an ST Micro **L3GD20** 3-axis 16-bit Gyroscope, an ST Micro **LSM303D** 3-axis 14-bit Accelerometer/Magnetometer, Invensense's **MPU 6000** 3-axis Accelerometer/Gyroscope, and an MEAS **MS5611** pressure sensor. All together, they provide the autopilot with two accelerometers, two gyroscopes, one magnetometer and one pressure sensor. This offers incredible performances when in flight, for autoguided missions, as well as manually controlled flights.

Its simple connectivity with pin headers allows great compatibility with most devices and easy connectivity to the motors, external sensors, and all other devices such as GPS receiver, airspeed sensor, arming switch, etc...</p>
