<!DOCTYPE html>
<html>
<body>
<h1>Hardware Hacks for Batteryless Energy Harvesting Electronics and Computing</h1>
<a href="https://github.com/RIPE-Atlas-Community/Green-Tech/"><p align="center"><a href="https://github.com/RIPE-Atlas-Community/Green-Tech/blob/main/README.md"><img src="hackathon.png" width="200" height="200"></a></p></a>
<p><a href="README.md#introduction">Introduction</a> | <a href="README.md#speculativeprototypes">Speculative Prototyping Projects</a> | <a href="README.md#faqs">Frequently Asked Questions</a> | <a href="README.md#links">Links and References</a></p>
  <h2 id="introduction">Introduction</h2>
<p>Green technology is about reducing the use of materials, energy, and waste systems and their associated carbon footprints.  This hackathon collection documents specific hardware hacks around the use of energy harvesting, batteryless electricity storage, and upcycling prior materials, in the creation of novel sustainable consumer electronics such as media players and computing devices.</p>
<p><b>Energy harvesting</b> is a strategy where natural sources of ambient energy are converted to stored fuel in various ways.  The ability to make fuel, to absorb ambient energy from the surroundings and render it into useful electricity, makes electricity systems (writ large, like grids) and at consumer scale: devices uniquely non-consuming and sustainable.   Wind turbines and solar collectors are a common means of energy harvesting, but a variety of arcane systems exist as well.  Even trees manifest enough electricity to power small internet of things devices <a href="https://doi.org/10.1109/TNANO.2009.2032293">(Himes, et. al., 2010).</a></p>
<p><b>Batterylessness</b> is possible in the sense that electricity can be stored physically as well as chemically.  In 1746, Leiden University professor <a href="https://top450.universiteitleiden.nl/en/items/de-uitvinding-van-de-condensator">Pieter van Musschenbroek invented the capacitor</a>, which stores electricity as static charge on non-conducting glass layers, like rubbing a balloon on one's head.  Initially, the capacitors stored small amounts of high voltages, making them somewhat dangerous.  However in 1954, the same year solar panels were invented, low voltage storage capacitors, or supercapacitors were invented by <a href="https://patentimages.storage.googleapis.com/a2/f8/a9/b7d5c04a415c8b/US2800616.pdf">Becker and Ferry</a> which were more properly able to store electricity, although at the time, they had not as much energy density as batteries.  One of the things noted in the invention patent was that depleting the capacitor completely and in various ways seemed to have no effect at all on the supercapacitor's future ability to store charge.  So, unlike batteries, capacitors last for millions of recharges, and decades of use!  Given that the world goes through 15 billion batteries each year, wouldn't it be great if there were more devices that work like a solar calculator, that doesn't repeatedly consume batteries and are common to find still working after half a century!  There's also the phenomenon of battery leakage and obsolescence in devices -- where people discard devices when they don't store power properly, the batteries can't be easily replaced or have leaked and damaged the electronics.  With the advent of ultracapacitors in 2010 (used in wind turbines to adjust the pitch) and hybrid supercapacitors in 2020, the energy density of these physical storage devices is now comparable to batteries, which makes real change possible.</p>
<p><b>Upcycling</b> recognizes that not only are there vast quantities of batteries being wasted, but that electronics devices themselves are discarded <a href="https://labs.ripe.net/author/mirjam/what-do-we-do-with-e-waste/">at an unprecedented rate</a>, significantly outpacing proper disposal and recycling programs worldwide.  Would it be possible to make use of the generic parts in new creations?   Musical instruments being absolutely standardized and objects of care appreciate with time, resulting in fewer being discarded.  Degrowth or the slowing down of consumption is mainly about treating the things we own differently with respect to maintenance.  But they also need to be manufactured differently -- to last longer, have upgrades, parts replacement and repair.</p>
<h1 id="speculativeprototypes">Speculative Prototyping Projects</h1>
  <p><a href="https://dunneandraby.co.uk">Dunne and Raby</a> originated the expression critical or speculative prototyping in their design work around 2005, in Hertzian Tales.  The essential idea is to discuss examine and critique social issues by redesigning objects we use (particularly electronics objects) in alternative ways.  With that in mind, here are a number of projects which use the approach outlined in the Introduction.</p>
  <ul>
    <li><a href="https://github.com/bksutherland/GreenTechHackathon/blob/main/MasonJarRadio.md">Batteryless FM Radio in a Mason Jar</a></li>
    <li><a href="https://github.com/bksutherland/GreenTechHackathon/blob/main/batterylessbiketaillight.md">Batteryless Bicycle Tail Light</a></li>
    <li><a href="https://github.com/bksutherland/GreenTechHackathon/blob/main/batterylessbikeheadlight.md">Batteryless Bicycle Headlight</a></li>
    <li><a href="https://github.com/bksutherland/GreenTechHackathon/blob/main/portablesolaroffice.md">Portable Solar-Powered Office</</a></li>
    <li><a href="https://github.com/bksutherland/GreenTechHackathon/blob/main/bluetoothewastestereo.md">Bluetooth Stereo from eWaste</a></li>
  </ul>
<h1 id="faqs">Frequently Asked Questions</h1>
  <p><em>What is the problem we are trying to solve?</em></p>
  <p>As per the introduction - two problems specific to technology-use: significant battery waste and it's associated <a href="https://www.irena.org/Energy-Transition/Technology/Critical-materials">critical materials or mineral problem</a>, and making consumer electronics devices last longer, be repairable and upcyclable, <a href="https://labs.ripe.net/author/mirjam/what-do-we-do-with-e-waste/">the e-Waste problem</a>.</p>
  <p><em>How do hybrid supercapacitors, also called lithium ion capacitors compare to batteries?</em></p>
  <p>Typically energy storage solutions are compared along two dimensions, energy density (ability to store energy in a given volume) and power density (ability to supply the energy at a significant rate from a given volume).   This is often represented visually using a <a href="https://en.wikipedia.org/wiki/Ragone_plot#/media/File:Lithium_Ion_Capacitor_Chart.png">Ragone plot</a> and you may observe that lithium ion capacitors have a similar energy density to low end batteries, but a higher power density.   Not captured on the plot are that they recharge much more, 500 000x and last much longer, decades!  They also are less affected by low temperatures, which can be useful in countries like Canada.  They are however, harder to use, because the voltage decreases as the capacitors discharge and most electronics are designed around a specific voltage, they don't tolerate voltage variation very well without a regulator.
  <p><em>Why haven't heard of this before? Why is this possible now?</em></p>
  <p>Some products like solar calculators and solar wristwatches (such as the <a href="https://www.citizenwatch.com/ca/en/technology-eco-drive.html">Citizen Eco-Drive</a>, or Swatch solar) you may have heard of but were perhaps unaware they used capacitors instead of batteries.  The other reason is simply that there are a lot of new advances in energy storage -- only recently did hybrid supercapacitors come out in the market (2020), and even more recently, sizes in the 1100F range (2022) comparable in energy density to some batteries.
  <p><em>Where are hybrid supercapacitors made?</em></p>
  <p>Two of the largest mass production vendors are <a href="https://www.eaton.com/ie/en-gb/company/careers/life-at-eaton/dublin.html">Eaton Electronics</a>; <a href="https://en.cda-cap.com/">cds</a> in Taiwan;   The best price I've seen is $10 (Cdn) for a 1100F cds, delivered.</p>
  <p><em>What are hybrid supercapacitors made of?</em></p>
  <p>While it's true that critical minerals like lithium are used in hybrid supercapacitors, they recharge and last much longer than rechargeable batteries.  More long lasting products would result in a reduction of the need for critical minerals and generate less carbon from mining, manufacturing and eWaste.</pre></p>
  <p><em>Where do I go for more information?</em></p>
  <p>In the sense this is about the use and evolution of energy storage components, and they are new in the market, I would watch parts vendors for new products in this space such as <a href="https://www.farnell.com/datasheets/4422020.pdf">1400F hybrid supercapacitors from Eaton</a>, as well as unusual new smart devices products, <a href="https://www.epishine.com/news/epishine-secures-extensive-agreement-for-solar-powered-smoke-detectors">solar powered smoke alarms</a>.  This approach (energy harvesting + batteryless) has yet to be successful in altering existing consumer electronics habits, the devices people commonly choose.  It may be there is more competition around pricing where the advantage of a longer lasting product would be harder to sell.  Ask yourself, however why photovoltaic cells were invented 75 years ago, yet almost no consumer products use them aside from very briefly manufactured LG510, Samsung Blue Earth, <a href="https://news.samsung.com/global/samsung-electronics-launches-eco-friendly-solar-powered-rechargeable-netbook-nc-215s">Samsung NC215S laptop</a> etc.</p>
<h1 id="links">Links and References</h1>
<p>Low-Carbon-Wayfinding Conversations (Director). (2024, August 8). Low Carbon Consumer Electronics — With Brian Sutherland (17 July 2024) [Video recording]. <a href="https://youtu.be/Zicvndw5lNI?si=3cR8pBB4yYd79-CS">https://www.youtube.com/watch?v=Zicvndw5lNI
  <p>Gao, D., Luo, Z., Liu, C., & Fan, S. (2023). A survey of hybrid energy devices based on supercapacitors. Green Energy & Environment, 8(4), 972–988. <a href="https://doi.org/10.1016/j.gee.2022.02.002">https://doi.org/10.1016/j.gee.2022.02.002</a> - on the use of batteries and supercapacitors together in hybrid systems</br>
  <p>Angulo, F., Navarro, L., Quintero M., C. G., & Pardo, M. (2021). A Simple WiFi Harvester with a Switching-Based Power Management Scheme to Collect Energy from Ordinary Routers. Electronics, 10(10), Article 10. <a href="https://doi.org/10.3390/electronics10101191">https://doi.org/10.3390/electronics10101191</a> - electromagnetic energy (wifi) harvester, like Tesla envisaged.
</a><br/>
</p>
</body>
</html>
