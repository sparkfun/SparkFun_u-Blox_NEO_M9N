SparkFun GPS NEO-M9N U.FL and Chip Antenna
========================================

<table class="table table-hover table-striped table-bordered">
  <tr align="center">
   <td><a href="https://www.sparkfun.com/products/15733"><img src="https://cdn.sparkfun.com/assets/parts/1/4/3/2/2/15733-SparkFun_GPS_Breakout_-_NEO-M9N__Chip_Antenna__Qwiic_-01.jpg"></a></td>
   <td><a href="https://www.sparkfun.com/products/15712"><img src="https://cdn.sparkfun.com/assets/parts/1/4/2/9/3/15712-SparkFun_GPS_Breakout_-_NEO-M9N__U.FL__Qwiic_-01.jpg"></a></td>
  </tr>
  <tr align="center">
    <td><a href="https://www.sparkfun.com/products/15733">SparkFun GPS NEO-M9N Chip Antenna (GPS-15733)</a></td>
    <td><a href="https://www.sparkfun.com/products/15712">SparkFun GPS NEO-M9N U.FL (GPS-15172)</a></td>
  </tr>
</table>

The SparkFun NEO-M9N GPS Breakout is a high quality, GPS board with equally impressive configuration options. The NEO-M9N module is a 92-channel u-blox M9 engine GNSS receiver, meaning it can receive signals from the GPS, GLONASS, Galileo, and BeiDou constellations with ~1.5 meter accuracy. This breakout supports concurrent reception of four GNSS maximizes position accuracy in challenging conditions increasing precision and decreases lock time and thanks to the onboard rechargeable battery, you'll have backup power enabling the GPS to get a hot lock within seconds! Additionally, this u-blox receiver supports I<sup>2</sup>C (u-blox calls this Display Data Channel) which made it perfect for the Qwiic compatibility so we don't have to use up our precious UART ports. Utilizing our handy Qwiic system, no soldering is required to connect it to the rest of your system. However, we still have broken out 0.1"-spaced pins in case you prefer to use a breadboard. 

The NEO-M9N module detects jamming and spoofing events and can reports them to the host, so that the system can react to such events. A SAW (Surface Acoustic Wave) filter combined with an LNA (Low Noise Amplifier) in the RF path is integrated into the NEO-M9N module which allows normal operation even under strong RF interferences.

U-blox based GPS products are configurable using the popular, but dense, windows program called u-center. Plenty of different functions can be configured on the SAM-M8Q: baud rates, update rates, geofencing, spoofing detection, external interrupts, SBAS/D-GPS, etc. All of this can be done within the SparkFun Arduino Library!

The SparkFun NEO-M9N GPS Breakout is also equipped with an on-board rechargeable battery that provides power to the RTC on the NEO-M9N.  This reduces the time-to-first fix from a cold start (~24s) to a hot start (~2s). The battery will maintain RTC and GNSS orbit data without being connected to power for plenty of time. 

Repository Contents
-------------------

* **/Documentation** - Data sheets for the NEO-M9N
* **/Hardware** - Eagle design files (.brd, .sch)
* **/Production** - Production panel files (.brd)

Documentation
--------------
* **[Library](https://github.com/sparkfun/SparkFun_Ublox_Arduino_Library)** - Arduino Library the SparkFun GPS NEO-M9N.
* **[Hookup Guide](https://learn.sparkfun.com/tutorials/sparkfun-gps-neo-m9n-hookup-guide)** - Basic hookup guide for the SparkFun GPS NEO-M9N

License Information
-------------------

This product is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact technical support on our [SparkFun forums](https://forum.sparkfun.com/viewforum.php?f=152).

Distributed as-is; no warranty is given.

- Your friends at SparkFun.

_<COLLABORATION CREDIT>_
