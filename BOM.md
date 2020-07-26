Below are links to the items that I used. Most of these are Amazon Affiliate links.

Arduino:
I prefer the Arduino Uno with a socketed DIP since it's easily repairable, but the SMD version is a little less expensive. The bare shield is a convenient for mounting all.

Arduino Uno R3 https://amzn.to/2Ekh8hU (with replaceable processor) or https://amzn.to/3jF4XfJ (SMD version)
Arduino Uno R3 Bare Shield https://amzn.to/3hA0Lfq
Straight Headers https://amzn.to/2ZXLKOt



Power conversion:
The Murata DC-DC converters will produce a sufficient 5V to power the electronics from a single 12V or 24V source that also powers the fan. To save space, the converter should be mounted flush with the shield, which may require a right-angle header, depending on the Murata model available.

Right-angle Headers https://amzn.to/39v0EPC
Murata DC-DC Converter OKI-78SR-5/1.5-W36-C https://amzn.to/30IcyS2

or 

Murata DC-DC Converter OKI-78SR-5/1.5-W36H-C https://www.digikey.com/product-detail/en/murata-power-solutions-inc/OKI-78SR-5-1-5-W36H-C/811-2692-ND/3438675



Display:
The GPIO board is not required, but will useful if you wish to use the Nextion display for other projects. The display can generate a PWM signal, which might control the fan. But, reading the fan tach or the temperature sensors may not be possible with the display.

Nextion Enhanced NX4832K035 https://amzn.to/2BzLn3o
Nextion GPIO Breakout https://amzn.to/300HcXz



Temperature sensor
The DS18B20 and OTI-301 were used. The OTI-301 has a response curve in its manual, but the MLX90614ESF has a richer datasheet. The OTI-301 is also harder to find than the MLX90614ESF.

DS18B20-based Contact Temperature Sensor https://amzn.to/32WuU4u
OTI-301-based Non-contact Temperature Sensor https://amzn.to/32WzyzE
MLX90614ESF-based Non-contact Temperature Sensor https://amzn.to/2CQswS5



Fan
Noctua NF-F12 industrialPPC-24V-3000 Q100 IP67 PWM https://amzn.to/3g4mzQ6