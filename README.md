# ERCF-Buffer-Box

<p align="center">
  <img src="/Assets/Filament_Box.png" alt='Buffer-Box' width='70%'>
</p>

12 Spool Buffer Filament Box for the ERCF v2 (Updated March 2026)

## BOM

12 x [M4 Roll-in T-nuts](https://www.amazon.com/dp/B07VHNZ9XG)<br>
12 x [M4 x 10mm Flat Head](https://a.co/d/0fNCq3q4)<br>
~130 x [M5 Roll-in T-nuts](https://www.amazon.com/dp/B07VHNGBWJ)<br>
126 x [M5 x 10mm Flat Head](https://a.co/d/01dUSnKL)<br>
4 x [PC4-M10 Male Straight Pneumatic PTFE Tube Push-In Quick Fitting Connector](https://a.co/d/0e4PLHHR)<br>
2 x [10 Inch 100N/22.5lb Gas Struts](https://www.amazon.com/dp/B09BYY65W1)<br>
20ft x [Weather Stripping, D-shaped Rubber Seal Strip](https://www.amazon.com/dp/B0CCRXHYT7)<br>
~32 x [2020 Series L-Shape Interior Inside Corner Connector](https://www.amazon.com/dp/B08D6T9CGN)<br>
~12 x [2028 Corner Bracket](https://www.amazon.com/dp/B0BFRB35Z8)<br>
~15,000mm x [2020 V-slot Aluminum Extrusion](https://www.amazon.com/dp/B0BM8H5XZ9)<br>
~24 x [608-2RS Skateboard Bearing](https://www.amazon.com/gp/product/B073ST742Z)<br>
1 x [Under Cabinet Light, 12 Inch Plug-in LED Closet Light, 2pk](https://www.amazon.com/gp/product/B08VDH1GJV)<br>
LOTS x [PTFE Tube 3mm ID, 4mm OD](https://www.aliexpress.us/item/2251832878144608.html)<br>


## 2026 Updates

* No more [Stern-Wheeler](https://www.printables.com/model/472316-stern-wheeler). I had too much trouble getting these to work right. I kept getting false jams or actual jams because there was too much friction. I’m now using the [Integrated Auto-Rewind Spool Holder](https://www.thingiverse.com/thing:3781815) and made a custom profile that works very well. Models are included, but due to the size of the ones I included, they may not work for you. You may need to “play” with the Integrated Auto-Rewind Spool Holder’s diameter for your needs. The new spool holders also use less hardware. I've included my SCAD settings if you want to start there — see `/STL/Spool Holder 2026 Edition/IntegratedRewinderv5_6_1 Settings.txt`.

* Also, for the Integrated Auto-Rewind Spool Holder — I don't know if this is required, but I think a couple spring sections were sticking together at some points, preventing the spools from rewinding. So I added `Large Divider.stl` and `Small Divider.stl`. These are 0.2mm spacers that go between each spring section. I printed these in PLA since PLA and PETG do not stick together. I haven't had that problem since.  
  NOTE: Printing a 1-layer pla object and peeling it off is kind of fun, I printed a ton of them and tossed any “bad” ones. Use a [Plastic razor blade](https://a.co/d/0enmqdN7) for better luck.

* The `Guide.stl` and `Axle.stl` get glued together so it is easier to align the rewinder when putting them in. the Axle also snaps into the `Spool Mount.stl` on both sides so you know if they are in and secure. Just make sure your printer is fairly dialed in when printing these parts. 



## 2025 Updates

### Heater Controller Mount:
2 x M5 x 10mm Flat Head  
2 x M5 Roll-in T-nuts  
Misc screws for mounting  

### Heater and Fan (Rear of Cabinet):
2 x M5 x 10mm Flat Head  
2 x M5 Roll-in T-nuts  
Misc screws for mounting  

### Filament Box Temp Sensor:
2 x M5 x 10mm Flat Head  
2 x M5 Roll-in T-nuts  

### PTFE Quick Connect:
24 x [Bowden Collets](https://a.co/d/7jrjyus)<br>
26 x [6x3 mm Neodymium Magnets](https://a.co/d/eJB51Ad)<br>
Misc screws for mounting<br>

### Heater
1 x [Digital LED Temperature Controller Module](https://a.co/d/0iozePl6)<br>
1 x [Air Heater, PTC Ceramic Heating DC12V 50W](https://a.co/d/0bwOyqDZ)<br>
1 x [DC 12V 60W Power Supply](https://a.co/d/0igF9PvV)<br>




## 3D Models

[Integrated Auto-Rewind Spool Holder](https://www.thingiverse.com/thing:3781815)<br>
[2020 Print-In-Place Vertical Hinge](https://www.printables.com/model/794070-2020-print-in-place-vertical-hinge)<br>
[Voron 2.4 Exhaust Cover](https://www.printables.com/model/633527-voron-24-exhaust-cover)<br>

## Notes

* Spool holder parts do not need any hardware except two 608-2RS skateboard bearings. I cleaned all the grease from my bearings so they spin freely.
* Print the spool holder parts in PETG. It gives them more grip on the spool, and the internal springs are more flexible.
* When glueing the Guide and Axle, the Axel should be flat on the ground and the Guide sticking stright up. The parts are not a friction fit, use PETG Gloop or Super Glue
* I moved the ERCF outside of the box — it was a pain to clean or deal with issues when it was inside the box.
* Created a PTFE Quick Connect so I can more easily pull the ERCF away from the filament box.
* For the PTFE Quick Connect: print the female piece and the cap, then glue them together (super glue works great). See image below.
* I added some TPU feet under the box so when I pull it off the wall, I can set it down without damaging anything on the bottom.

## Wiring

I will not provide wiring instructions, because if you have built a Voron you can probably figure this out on your own — plus your setup is going to be very different than mine.

## Misc

I included some misc parts that I created for my setup that you are welcome to use.<br><br>

If you use the [Voron 2.4 Canopy](https://www.printables.com/model/568090-voron-24-canopy) and have a [BTT PITFT50](https://a.co/d/5EXvKxF):  
See: `/Misc/Corner.stl` and `/Misc/PITFT50 Mount.stl`<br><br>

To make wiring easier, I used a [14-pin Micro-Fit 3.0mm connector](https://www.aliexpress.us/item/2251832548943535.html)<br>
See: `/Misc/Back Plate.stl` and `/Misc/Port.stl`  
(P.S. I have a Voron 2.4 350, so the Back Plate may not fit yours.)

## Spool Holder Parts

<p align="center">
  <img src="/Assets/Spool Rewinder Parts.jpg" alt='Spool Rewinder parts' width='50%'><br />
  <img src="/Assets/Guide and Axle 1.jpg" alt='Guide and Axle 1' width='25%'>
  <img src="/Assets/Guide and Axle 2.jpg" alt='Guide and Axle 2' width='25%'>
</p>

## Misc Photos

<p align="center">
  <img src="/Assets/Door Closed.png" alt='Door Closed' width='25%'>
  <img src="/Assets/Heater and Light Power Wires.png" alt='Heater and Light Power Wires' width='25%'>
  <img src="/Assets/Heater.png" alt='Heater' width='25%'><br/>
  <img src="/Assets/PITFT50 Mount.png" alt='PITFT50 Mount' width='25%'>
  <img src="/Assets/Quick Disconnect and Wire.png" alt='Quick Disconnect and Wire' width='25%'>
  <img src="/Assets/Ribbon Cable.png" alt='Ribbon Cable' width='25%'><br/>
  <img src="/Assets/Strut Mount.png" alt='Strut Mount' width='25%'>
  <img src="/Assets/Strut Mount 2.png" alt='Strut Mount 2' width='25%'>
</p>