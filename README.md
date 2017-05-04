# Getting to Blinky with Kicad.

Learning the pipeline of creating a PCB (printed circuit board) from scratch. From ground zero design using [Kicad](http://kicad-pcb.org/), to ordering the PCB via [OSHPark]https://oshpark.com, and finally using SMD soldering to put it together. This project is building [flashing LED circuit](http://www.555-timer-circuits.com/flashing-led.html) using a [7555](http://www.nxp.com/documents/data_sheet/ICM7555.pdf) CMOS timer.

# Backstory to this repo.

This started because I tried to build an open source hardware device called the [CANtact](http://linklayer.github.io/cantact/). I wanted to make my own CAN sniffer so that I could look into decoding CAN messages. The CANtact hooks into your car via an OBD2 wire and connects to a computer via USB... Long story short I bit off more than I could chew; I never soldered before and this required SMD soldering.

The CANtact creator used [Kicad](http://kicad-pcb.org/) to design the PCB. To get going, I first figured out how to solder. S/O to [Noisebridge](https://noisebridge.net/wiki/Noisebridge) for circuit hack Mondays. J is a fantastic teacher, he had me operational in a few hours. Next was SMD soldering. I found Nick, a regular at Noisebridge, that happen to have been working on a different SMD project was willing to let me observe him work. I am very thankful to Nick for his kindness and patience. I must of asked him a million questions :D

The last component is Kicad; I needed to be somewhat operational with this tool to be able to understand what the CANtact is doing and how it was designed. Youtube to the rescue! [Contextual Electronics](https://contextualelectronics.com/) has a fantastic Kicad tutorial titled [KiCad tutorial 2016 - Contextual Electronics](https://www.youtube.com/playlist?list=PL5iUxv3Op2fOpVASHvcpM2O4UO0yMfKJi) on YouTube.

I am far from being a pro, but I can at least navigate my way around electronics now. I found my footing and the CANtact creation is well underway. Learning the entire pipeline was a very rewarding process. I enjoyed it and met wonderful people along the way to set me on the right path.
