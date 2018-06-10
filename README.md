# AppleSensors 
A singleton which on Apple computers can:

<ul>
<li> get and set display and keyboard brightness
<li> read left and right ambient light sensors (laptops only)
<li> read accelerometer sensor (laptops only)
</ul>

Example use:
```
sensors = AppleSensors clone
value := sensors getRightLightSensor

```

# Installation

```
eerie install https://github.com/IoLanguage/AppleSensors.git
```
