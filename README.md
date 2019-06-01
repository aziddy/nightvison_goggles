# nightvison_goggles

Nightvision can be really easy. One way is to use infrared light, a camera and screen

This can also be used for some people who are legally blind and can't see in dark areas

<br>
<br>


## Rev 2
<p align="center" style="vertical-align: top; position: relative" >
  
<img align="top" style="vertical-align:top" src="https://github.com/aziddy/nightvison_goggles/blob/master/media/5.jpg?raw=true" width="400"/>  
  
<img align="top" style="vertical-align:top" src="https://github.com/aziddy/nightvison_goggles/blob/master/media/Untitled-2.png?raw=true" width="400"/>

<img align="top" style="vertical-align:top;" src="https://github.com/aziddy/nightvison_goggles/blob/master/media/boop.png?raw=true" width="400"/>

<img align="top" style="vertical-align:top" src="https://github.com/aziddy/nightvison_goggles/blob/master/media/3g.gif" width="400"/>

<img align="top" style="vertical-align:top" src="https://github.com/aziddy/nightvison_goggles/blob/master/media/2g.gif?raw=true" width="400"/>

</p>

<br>
<br>


## Rev 1
<p align="center" style="vertical-align: top; position: relative" >
<img align="top" style="vertical-align:top" src="https://github.com/aziddy/nightvison_goggles/blob/master/media/IMG_20160605_202914.jpg?raw=true" width="700"/>
  
  <img align="top" style="vertical-align:top" src="https://github.com/aziddy/nightvison_goggles/blob/master/media/13423923_10154289054524036_8627727971720125782_n.jpg?raw=true" width="700"/>
  
</p>


<br>
<br>

## How the Night Vision works




So there obviously forms of light we can see. Like light bulbs, screens etc ...

<p align="center" style="vertical-align: top; position: relative" >
<img align="top" style="vertical-align:top" src="https://github.com/aziddy/nightvison_goggles/blob/master/media/1_isee.png?raw=true" width="500"/>
 </p> 
 
 And there are also forms of light we can't directly see. Like Infrared

<p align="center" style="vertical-align: top; position: relative" >
  <img align="top" style="vertical-align:top" src="https://github.com/aziddy/nightvison_goggles/blob/master/media/2_idontsee.png?raw=true" width="500"/>
</p>

<br>
<br>
So we if get a camera that can see Infrared, then connect it to a normal screen. Then we can see what camera can see, therefore we can see the Infrared now
<br>
<br>
<p align="center" style="vertical-align: top; position: relative" >
  <img align="top" style="vertical-align:top" src="https://github.com/aziddy/nightvison_goggles/blob/master/media/3_isee.png?raw=true" width="600"/>
</p>

<br>
<br>


## Component List
* ~~TFT Rearview Screen~~ (Rev 1)
* ~~Mobile VR Headset with its lenses taken out~~ (Rev 1)
* IR Flash Light
* Phone Battery Bank with atleast 2 amp output
* A Hat
* 3D printed Monocular Display Mount Monocular Display https://www.thingiverse.com/thing:1745757
* Hot Glue
* Electrical Tape
* NTSC/PAL (Television) TFT Display - 2.0" https://www.adafruit.com/product/911
* Boost Convertor that can tolerate atleast 1A and can bring 5v to the voltage for the screen 
* Camera with composite (yellow) ouput
* LM350 Linear Voltage Regulator
* Resistors 220, 210, 100 and 10 Ohm

<br>

<p align="center" style="vertical-align: top; position: relative" >
  
<img align="top" style="vertical-align:top" src="https://github.com/aziddy/nightvison_goggles/blob/master/media/cad.PNG?raw=true" width="200"/>
  
  <img align="top" style="vertical-align:top" src="https://github.com/aziddy/nightvison_goggles/blob/master/media/ir_flashlight.PNG?raw=true" width="400"/>
  
  <img align="top" style="vertical-align:top" src="https://github.com/aziddy/nightvison_goggles/blob/master/media/2inch_tft.PNG?raw=true" width="200"/>
  
  <img align="top" style="vertical-align:top" src="https://github.com/aziddy/nightvison_goggles/blob/master/media/boost%20reg.jpg?raw=true" width="200"/>
  
  
</p>

<br>
<br>


## Assembly



### Removing IR Filter on the camera

Alot of cameras have IR filters to stop bright light from hitting the image sensor. We need to get rid of that so the camera can see the smallest amount light, including non visable light.

It was adhesively bounded to edge of the camera sensors enclosure. So I used a blow dryer and knife to take it off

<p align="center" style="vertical-align: top; position: relative" >
<img align="top" style="vertical-align:top" src="https://github.com/aziddy/nightvison_goggles/blob/master/media/camera_ir_filter_illustrated.png?raw=true" width="400"/>
</p>

<br>
<br>

## Rev 2 Wiring

The convertor is boosting 5v from the battery bank, up to 12v

Both the camera and the screen can operate at 12v. The boosted voltage can be changed though, depending on the voltage ranges on both

<p align="center" style="vertical-align: top; position: relative" >
<img align="top" style="vertical-align:top" src="https://github.com/aziddy/nightvison_goggles/blob/master/media/wiring.PNG?raw=true" width="700"/>
  <br>
  <br>
  <br>
  <br>
  <br>
  The LM350 outputs ~1.5v with the given resistor config below and ~0.4-0.5A draw from the IR Light. The LM350 seems to get real hot though, so I would recommend a small buck converter if you have one on hand
  <br>
  <br>
    <img align="top" style="vertical-align:top" src="https://github.com/aziddy/nightvison_goggles/blob/master/media/wiring_proto.PNG?raw=true" width="400"/>
    <br>
  <br>
  <br>
  <img align="top" style="vertical-align:top" src="https://github.com/aziddy/nightvison_goggles/blob/master/media/1.jpg?raw=true" width="300"/>
  
  <img align="top" style="vertical-align:top" src="https://github.com/aziddy/nightvison_goggles/blob/master/media/IMG_20190504_210337.jpg?raw=true" width="300"/>
  
  <img align="top" style="vertical-align:top" src="https://github.com/aziddy/nightvison_goggles/blob/master/media/IMG_20190504_201211.jpg?raw=true" width="300"/>
  
  <img align="top" style="vertical-align:top" src="https://github.com/aziddy/nightvison_goggles/blob/master/media/MVIMG_20190504_210348.jpg?raw=true" width="300"/>
  
</p>




<br>
<br>




