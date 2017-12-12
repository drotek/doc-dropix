#XXL GPS Module

The XXL GPS module features a u-blox **Neo M8N** chip and a **HMC5983** magnetometer to give your system the ability to know its position and orientation.

These modules offer better satellite reception than the GNSS "Mushroom" and XL modules thanks to their larger ground plane.

You can find more information on [this page](https://drotek.com/shop/en/drotek-parts/680-ublox-neo-m8n-gps-hmc5983-compass-xxl.html?search_query=ublox&results=18).

<p align="center">
  <img src="./images/xxl.jpg?raw=true" alt="XXL GPS Module"/>
</p>

##Hardware

To connect your XXL GPS module to your Dropix autopilot, you'll need to use a 6 pin JST-GH to 6 * single header cable. Plug it into your XL GPS module and then connect it to your Dropix's GPS port on the accesories rail, taking care of the pinout. Take care of installing your GPS module heading the same way as the autopilot to reduce constraints and setup steps. 

<p align="center">
  <img src="./images/xxlcon.jpg?raw=true" alt="XL GPS connected"/>
</p>

##Software

After connecting your GPS module to your Dropix autopilot, you'll need to set it up using your favorite GCS, QGroundControl or Mission Planner.

Connect your autopilot to your GCS, and then go to the sensors settings. There, you should calibrate your compass (both external and autopilot) and setup the external compass's rotation in case you did not set the GPS board heading the same way as your autopilot. Do not forget to set your autopilot so that the exernal compass is used and active. 

<p align="center">
  <img src="./images/xl1.jpg?raw=true" alt="XXL GPS Conf"/>
</p>

For full informations concerning the setup of your GPS board within your machine, refer to your GCS's user manual ([QgroundControl](https://docs.qgroundcontrol.com/en/) / [Mission Planner](http://ardupilot.org/planner/docs/mission-planner-overview.html))