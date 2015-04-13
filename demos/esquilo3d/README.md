Esquilo 3D Demo
===============
This demo expands on the [IMU demo](../imu/README.md) with a 3D Esquilo logo
that is controlled with movements of an Esquilo board. The logo responds in
real-time the rotations you give the board in all three dimensions, using WebGL.

The demo consists of three files:

  * imu.nut - Squirrel nut that contains the squirrel code that continuously
    reads the sensors and calculates the orientation.
  * esquilo3d.html - Contains the HTML for the web interface.
  * d3-threeD.js - JavaScript library using D3 for 3 dimensional rendering.

To run the demo, follow the instructions [IMU demo](../imu/README.md), including
running imu.nut and calibrating the IMU.

After the squirrel nut is running, open the html file from your browser either
from it's local IP address:

    http://<Local Esquilo IP>/sd/lib/demos/esquilo3d/esquilo3d.html

or from the Esquilo Nest:

    http://<Esquilo System ID>.esquilo.io/sd/lib/demos/esquilo3d/esquilo3d.html

License
-------
This work is released under the Creative Commons Zero (CC0) license.
See http://creativecommons.org/publicdomain/zero/1.0/
