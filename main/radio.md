# Radio receiver

The radio receiver will allow you to control your machine using your favorite radio controller. Depending on your equipment, you'll have to connect your receiver to different connectors of the Dropix.

![](../.gitbook/assets/receivers.jpg)

## SBUS ready receiver

To use an SBUS receiver, you'll have to plug your receiver to the **RCIN** port of the Dropix, taking care of the orientation of the connector.

_Note: the **SBUS** port of the Dropix is an **output**. This can be useful to control servomotors that are controlled using the SBUS protocol._

![](../.gitbook/assets/dropix-radio-receiver.png)

## SPEKTRUM ready receiver

The Dropix has a Spektrum port in order to be able to use a Spektrum ready controller with it. You will find the **Spektrum receiver port** on the accesories rail of the Dropix board. Take care of the pinout of the Dropix and your receiver to connect it correctly.

![](../.gitbook/assets/spek.jpg)

## PWM output receiver

For classical \(PWM\) radio receivers that are neither SBUS or Spektrum ready, you will have to use a PPM Encoder. You can find one to buy on the Drotek shop by following [this link](https://drotek.com/shop/en/home/364-ppm-encoder-8-channels.html).

![](../.gitbook/assets/ppmencoder.jpg)

This module is meant to translate multiple PWM outputs from the radio receiver into a single PPM signal that will be compatible with the Dropix. To use it:

* Connect the PWM outputs from your radio receiver to the PPM encoder using the 10 cables connector, keeping the channels from the receiver corresponding to the order of the cables on the PPM encoder. 
* Connect the 3 wires cable on the **RCIN** of the Dropix autopilot.
* To get the PPM encoder board to get its power supply from the autopilot, leave the solder bridge unsoldered.

![](../.gitbook/assets/ppm.jpg)

