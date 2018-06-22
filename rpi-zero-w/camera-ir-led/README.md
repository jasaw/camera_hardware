# IR-LED board

IR-LED board for night vision.

Current issues:
* IR light is not bright enough to illuminate large area
  * As a workaround, use [external IR LEDs](https://www.aliexpress.com/item/Free-shipping-48LEDs-Illuminator-IR-Infrared-dome-CCTV-camera-hd-Night-enhancement-Fill-light-Vision-40M/32811672765.html).


### Design files

* [Gerbers](camera-ir-led-rev-1a.zip)
* [PCB top](camera-ir-led-rev-1a-top-parts.pdf)
* [PCB bottom](camera-ir-led-rev-1a-bottom-parts.pdf)


### Bill of Materials

* [BoM](camera-ir-led-rev-1a.xlsx)
* 5mm IR LEDs 940nm Wave Length
  * Forward Voltage: 1.5~1.6V
  * Forward Current: 60mA Continuous, 120mA peak 10% pulse width
  * View Angle: 15-30 degree
  * [ebay](https://www.ebay.com.au/itm/100pcs-5mm-LED-Lights-Infrared-Emitters-IR-Emitting-Diodes-940nm-Wave-Length/201201649166)
* 5mm IR LEDs 850nm Wave Length
  * Forward Voltage: 1.45~1.65V
  * Forward Current: 20mA Continuous, 100mA max pulse
  * View Angle: 30 degree
  * [AliExpress](https://www.aliexpress.com/item/100Pcs-5mm-IR-Led-850nm-Lamp-Transmitting-Tube-Emitting-Diode-Infrared-LED-Diode-ir-850nm-High/32373548361.html)
* GL5528 LDR Photo Resistors
  * [ebay](http://www.ebay.com.au/itm/20PCS-Photoresistor-GL5528-LDR-Photo-Resistors-Light-Dependent-WS/222122787897)
* JST PH 2.00mm pitch 4-pin connector and cable
  * [AliExpress](https://www.aliexpress.com/item/20-Sets-PH-2-0mm-JST-2-3-4-5-6-7-8-9-10-12P/32782287584.html)
  * [AliExpress](https://www.aliexpress.com/item/20-SETS-Mini-Micro-JST-2-0-PH-4-Pin-Connector-plug-with-Wires-Cables-300MM/32611300648.html)
  * [AliExpress](https://www.aliexpress.com/item/10sets-1-0mm-1-25mm-1-5mm-2-0-2-54mm-2-3-4-5-6/32733307616.html)
* Optical IR Cut Light Filter 8mm (for LDR light sensor)
  * [ebay](https://www.ebay.com.au/itm/10pcs-Optical-UV-IR-Cut-Light-Filter-Blocking-For-Camera-Astronomy-Lens-8mm-Slim/282653207704)
* Some heatshrink to hold the IR Cut Light Filter
