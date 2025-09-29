# LedBox V2 | StanleyProjects.com
[![](https://stanleyprojects.com/projects/ledbox-v2/ledbox_renders.png)](https://stanleyprojects.com/projects/ledbox-v2)
[![](https://stanleyprojects.com/projects/ledbox-v2/collage.png)](https://stanleyprojects.com/projects/ledbox-v2)

# Introduction
LedBox V2 / V2.1 is a fully contained, sound reactive, ESP32 based module for controlling 5-12V addressable LED strips (WS281x, SK6812, etc.), supporting both 3-(VDD,DAT,GND) and 4-(VDD,DAT,CLK,GND) wire configuration.

The module (V2 & V2.1) has a dedicated step-down converter, which allows to seamlessly use both 5V and 12V strips (input voltage has to match strip's voltage). It also contains a digital MEMS microphone, side button, 32kHz IR receiver, 10A safety resettable fuse, 1000µF buffer capacitor, 3.3V/5V level converter for both Data and Clock lines, together with an impedance matching resistor. These features ensure maximum functionality, safety, and led strip compatibility, all in a small 3D printable enclosure.

LedBox V2.1 has these additional features:

-   MOSFET that automatically disconnects the LED strip power when in standby
-   Potentiometer for precise impedance matching
-   3 unallocated GPIO pins for possible expansion

Purchased module comes with the latest version of sound-reactive firmware.

# Specification
![](https://stanleyprojects.com/projects/ledbox-v2/table1.png)
![](https://stanleyprojects.com/projects/ledbox-v2/thumbs/LedBox_V2.x_description.png)
![](https://stanleyprojects.com/projects/ledbox-v2/table2.png)

## Firmware versions
The original precompiled SR WLED firmware has a disabled IR control. Therefore, it is recommended to use builds from this repo, which are compiled with correct pin/microphone settings and IR control support, to work with the module straight out of the box.

The firmware is compatible with both, V2 and V2.1.

|Version|Firmware|
|-|-|
|0.13.3|[LedBoxV2_SR_WLED_0.13.3.bin](https://github.com/stanleyondrus/LedBoxV2/releases/download/v0.13.3/LedBoxV2_SR_WLED_0.13.3.bin)|
|0.13.2|[LedBoxV2_SR_WLED_0.13.2.bin](https://github.com/stanleyondrus/LedBoxV2/releases/download/v0.13.2/LedBoxV2_SR_WLED_0.13.2.bin)|
|0.12.0|[LedBoxV2_SR_WLED_0.12.0.bin](https://github.com/stanleyondrus/LedBoxV2/releases/download/v0.12.0/LedBoxV2_SR_WLED_0.12.0.bin)|

# Documentation
#### The full documentation can be found at https://stanleyprojects.com/projects/ledbox-v2/
#### To stay in touch, get updates, or ask for help, visit https://fb.me/stanleyprojectscom

## Explanation video
[![](https://img.youtube.com/vi/DlzgvoAP7WI/mqdefault.jpg)](https://www.youtube.com/watch?v=DlzgvoAP7WI)
