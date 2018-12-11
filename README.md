# Paramotor Drone
# by: Emily Grau, Nicholas Restivo, Alex Valencia 
Georgia Institute of Technology - ECE 4180 Fall 2018

The goal of this project was to create a paramotor drone to simulate and collect data on the autonomous control of parafoils for future use in designing a system for the controlled landing of care packages.  

This paramotor drone is an mbed based project.  The payload was constructed to give forward thrust to the parafoil and create lift.

![alt text](https://github.com/emilygrau/Paramotor-Drone/blob/master/images/parafoil%20diagram.png?raw=true)

## Components
- [mbed](https://os.mbed.com/platforms/mbed-LPC1768)
- [IMU](https://www.sparkfun.com/products/13284)
- [Servos](http://www.towerpro.com.tw/product/mg996r/) 
- [RC receiver](https://hobbyking.com/en_us/turnigy-9x-2-4ghz-8ch-receiver-v2.html?___store=en_u)
- [Transmitter](https://hobbyking.com/en_us/turnigy-9x-9ch-transmitter-w-module-ia8-receiver-mode-2-afdhs-2a-system.html?___store=en_us)
- [Electronic Speed Controller](https://hobbyking.com/en_us/hobby-king-30a-esc-3a-ubec.html?___store=en_us)
- [Motor](https://hobbyking.com/en_us/turnigy-l2215j-900-brushless-motor-200w.html?___store=en_us)
- [Parafoil](https://www.amazon.com/Besra-Parachute-Parafoil-Kitesurfing-Training/dp/B07CXRHNGF/ref=sr_1_3?ie=UTF8&qid=1544071182&sr=8-3&keywords=2.5m+parafoil+kite)
- [Propellor](https://hobbyking.com/en_us/carbon-fiber-propeller-12x6-black-cw-ccw-2pcs.html?___store=en_us)


## Block Diagram
![alt text](https://github.com/emilygrau/Paramotor-Drone/blob/master/images/Flow%20diagram.jpeg?raw=true)

## Design Iterations

### Motor

### Propellor Cage
A circle piece of acrylic was 3-D printed and attached to the drone body to gaurd the lines of the parafoil from the propellor.  However, upond landing the acrylic hit the ground and snapped.  A new piece of acrylic was cut, this time with a flat bottom, as to prevent it from striking the ground first during landing.  The height of the propellor was also increased, casting the lowest point of the propellor above the ground, again to protect it from landing impact.  This new piece of acrylic also snapped during landing.  As of now, the acrylic gaurd has been replaced by a steel rod* bent into a semi circle shape and attached to the stabilizer bar*.  Initially, netting was attached to the rod, but during flight it became loose and was removed.  We discovered that the rod was enough to separate the parafoil lines and the propellor. 

### Landing Gear 
added wheels to help with take off... do we need wheels at all now??? 



## Photos

## Video

## Code 
