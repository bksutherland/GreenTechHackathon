<!DOCTYPE html>
<h1>Batteryless Bicycle Headlight</h1>
<p><a href="README.md"> ⬆️</a> | <a href="batterylessbikeheadlight.md#Introduction">Introduction</a> | <a href="batterylessbikeheadlight.md#partslist">Parts Required</a> | <a href="batterylessbikeheadlight.md#assembly">Assembly</a></p>
<h1 id="introduction">Introduction</h1>                                                                         
<p> A widespread adoption of bicycles and electric vehicles is essential for reducing carbon generation in the transportation sector.  Dutch design culture, along with many others is significantly concerned with integrating bicycle-use into daily life.  One problem with the use of bicycles year-round or at any time of day, is being seen in the dark -- particularly during the winter in northern climates and in countries with less established infrastructure around bicycle use.  Bicycles would benefit from a cheap DIY sustainable lighting solution for safer travelling. The batteryless, hybrid supercapacitor approach can really score here -- 500,000x recharges. The bicycle headlight circuit on this page is similar to the <a href="https://github.com/bksutherland/GreenTechHackathon/blob/main/batterylessbiketaillight.md">bicycle taillight project</a> except the design is for a more directional beam, it requires a brighter LED and a larger batteryless power supply.  For the enclosure, it is useful to find an old length of plastic waterproof tube, either gas or water.   The recipe makes use of the larger, 1100F hybrid supercapacitor, a Seiko 1/3/5W warm white LED, a TP4056 lithium ion recharging circuit, a resistor and a schottky 1N4004 diode. Supercapacitor voltages are minimally affected by cold temperatures down to -25 °C.   
<p align="center"><img src="bikeheadlight_00.png" width="640"></p>


<h1 id="partslist">Parts Required</h1> 
<p>To build this project you will need:
<ul>
  <li>1100F 4V cds Hybrid Supercapacitor (or similar capacity from a different manufacturer)</li>
  <li>1 Seiko 1/3/5 Watt warm white LEDs</li><br/><img src="bikeheadlight_03.png" width="640"></li>
  <li>LED reflector and plastic insert (optional, can be bought in bulk)</li>
  <li>TP4056 lithium ion battery charger (can be harvested from an old battery bank or power brick or purchased new for < $1)</li>
  <li>Schottky diode - IN4004 or equivalent</li>
  <li>High wattage resistor (more than 1/4 W), 10-20 ohms, to adjust the run time/brightness. This could be a negative temperature coefficient thermistor, whose resistance approaches zero as it heats up, sourced from eWaste electronics or bought new.</li>
  <li>Switch, preferably high wattage.  A small, low wattage switch is good for testing, but it might not last long, the leads tend to spot weld themselves if there isn't any regulation (resistor) reducing the surge current.</li>
</ul>
</p>
<h1 id="assembly">Assembly</h1> 
<p>The assembly involves attaching a diode to the B+ pin of the TP4046, and the other end to the positive lead of the hybrid supercapacitor.  The negative lead attaches to B-.  This completes the charging system for the capacitor storage, and you could test it at this point.  When the TP4056 reaches 4.2V, less 0.4V for the diode drop (3.8V), it will cease charging the hybrid supercapacitor, the blue ID will light showing charging is finished.   Now you will want to attach a positive and negative wire to these other wires, in front of the diode. The positive wire goes into the switch, then switch to a resistor, then to the positive foot of the Seiko LED.  The negative wire attaches to the negative foot of the Seiko LED.  While high wattage LED designs vary, the negative foot is sometimes notched or there is a + sign on the positive foot if you look carefully.  You can also establish which are the positive and negative feet of the LED just by testing it out with a battery or power supply.  </p>
    <p align="center"><img src="bikeheadlight_01.png" width="800"></p>
     <p align="center"><img src="bikeheadlight_02.png" width="800"></p>
    <p>Unlike the others, this project <em>is a little more risky, treat it as an experiment project</em>.   This hybrid supercapacitor although being less than 5 volts, can source enough current if short circuited -- to melt insulation, make smoke, and potentially cause a fire, and this bike headlight use-application involves a lot of movement and vibration.  Don't leave this unattended during charging, and make sure it is sufficiently insulated with tape and epoxy to work safely before strapping it onto a bike, riding with it in the rain, carrying it in a pocket, dropping it in a bag with keys, etc. </p>
</html>
