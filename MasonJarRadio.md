<!DOCTYPE html>
<h1>Batteryless FM Radio in a Mason Jar</h1>
<p><a href="README.md"> ⬆️</a> | <a href="MasonJarRadio.md#Introduction">Introduction</a> | <a href="MasonJarRadio.md#partslist">Parts Required</a> | <a href="MasonJarRadio.md#assembly">Assembly</a></p>
<h1 id="introduction">Introduction</h1>                                                                         
<p><a href="https://thepublicrad.io">The Public Rad.io</a> is a single station FM Tuner in a Mason jar <a href="https://github.com/The-Public-Radio">open source project</a> by Zach Dunham and Spencer Wright <a href="https://www.kickstarter.com/projects/centerlinelabs/kickstarter-gold-the-public-radio-the-single-stati?ref=44759g">crowdfunded on Kickstarter</a> into being.
Their blog discusses how they used the mason jar just because they had one handy and needed to test the speaker radios, but the general benefit is that it in choosing an established standard for packaging goods, <a href="https://en.wikipedia.org/wiki/Mason_jar">since 1858</a>, it is easy to change the container for the radio.  Note that it isn't actually a single station radio, it is possible for a user to change the station by unscrewing the jar and hitting the seek button. Few listeners are actually station-hoppers, though: most prefer to return to their favourite station and programming.</p>
<center><img src="IMG_2457.png"></center>
<img src="Hardware_Hacks_for_Batteryless_Energy_Harvesting_Computing_Page_10.jpg" width="1024">
<h1 id="partslist">Parts Required</h1> 
<h1 id="assembly">Assembly</h1> 
We begin by removing the AA battery clips and soldering in a postive red wire and a negative black wire.   Although this radio uses a small amount of current, using large wires with low power sources has been shown to have a benefit and it supports the longevity of the device.
<img src="IMG_2458.png"></center><br/>
<p>The solar cell we will use is this one, it is rated for 3.5V but in full sun it will produce 4.2V.  When solar cells are used to charge supercapacitors, they always charge to the open circuit voltage, not the rated voltage, due to the lack of resistance which capacitors offer compared with batteries.</p>
<img src="IMG_2463.png"></center><br/>
<p>The purple cylinders are hybrid supercapacitors made by cds of Taiwan.  Eaton electronics will have <a href="http://www.farnell.com/datasheets/4422020.pdf">1400F capacitors out by 2025</a>.
  Each one stores about 12,000 J as it charges to 4V then discharges to 2.2V.<br/>
Joules = C V ^2 (Charged) - C V ^2 (Discharged) -<br/>
1100F x 4V^2 - 1100F x 2.2V^2<br/>
17600 - 5364 J<br/>
12236 J<br/>
Hybrid supercapacitors ship fully charged, usually with the long foot (positive voltage) in a plastic tube.  As they can discharge MUCH faster than batteries when they short circuit, it is important in handling them to take special care as a significant heating occurs across the leads for anything conductive which causes a short circuit.  A short circuited hybrid supercapacitor will spontaneous melt a line of solder, or make a wire glow red and melt the insulation for example.  So proper handling!
</p>
<img src="IMG_2459.png"></center><br/>
<img src="IMG_2460.png"></center><br/>
<img src="IMG_2461.png"></center><br/>
<img src="IMG_2462.png"></center><br/>
</html>
