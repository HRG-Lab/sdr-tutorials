# About sdr-tutorials

This repository contains tutorials and getting-started instructions for using a Software-Defined Radio (SDR). The purpose is to have a centralized location where new users can get their setup together and interface with an SDR to study digital communications. This will be updated as new versions and releases come out, as well as new architectures are implemented.

You should clone this repository to download a copy of all of the example flowgraphs and a local copy of the out-of-tree (OOT) modules from HRG.

## GNURadio Installation Instructions

First, we will need to get an instance of Ubuntu or Raspbian Linux working. This section will detail several setups depending on if you have native Ubuntu, native Windows, or an embedded device such as a Raspberry Pi.

### Pybombs Overview

### Native Ubuntu LTS (20.04)

This is the easiest way to get GNURadio up and running.

### Ubuntu LTS (20.04) over Windows Subsystem for Linux (WSL) 2

This is a nice way to use a virtualized Linux kernel setup on Windows without needing to do a full OS install. Pierce edit.

### Raspberry Pi OS

## Reference Matrial 

There are many great learning resources out there for SDR from reading material (papers, textbooks, etc) to video lectures. Below are some great starting points; as you work with SDRs, if you come across something new and great, please add it below.

### Reading Material

* [PySDR: A Guide to SDR and DSP using Python](http://pysdr.org/index.html) - This is probably the best starting point for a new user. It contains indepth overview of DSP theory, digital communications, Python, and examples using the PlutoSDR. The references section includes more textbooks.
* [Software-Defined Radio for Engineers](https://www.analog.com/en/education/education-library/software-defined-radio-for-engineers.html) - This is written by the Analog Devices team and is very good for understanding theory. It uses MATLAB and the ADALM-PlutoSDR, but the DSP theory is easily implementable in Python.

### SDR Videos to Watch

GNURadio Conference publicly posts their conference talks on their [GR Youtube channel](https://www.youtube.com/channel/UCceoapZVEDCQ4s8y16M7Fng). All of the talks are fantastic; for a beginniner, I would recommend watching the following high-level talks below. We will be using mostly Analog Devices infrastructure in this lab, so the overview videos on the IIO library that ADI built.

* [Why Doesn't My Signal Look Like the Textbook? - Matt Ettus](https://www.youtube.com/watch?v=PNMOwhEHE6w)
* [Misunderstandings and Mistruths in SDR - Robin Getz](https://www.youtube.com/watch?v=lCPXqCxtjW4)
* [ADI Transceivers Deep Dive - Travis Collins](https://www.youtube.com/watch?v=VFqg6eN2ACE)
* [gr-iio: Nuances, Adv Features, New Stuff - Travis Collins](https://www.youtube.com/watch?v=tX8Tg9TBkPw)
* [Mega Hertz, Mega Samples, Mega bits, Mega Confusing - Robin Getz](https://www.youtube.com/watch?v=PNMOwhEHE6w)

### Random Websites (Wikis, tutorials, github)

* [ADI University Program Virtual Classroom](https://ez.analog.com/adieducation/university-program) - If you're using ADI Active Learning Modules like the PlutoSDR, this is a support forum where you can ask any questions. They're very helpful and welcoming.
* [ADI Wiki](https://wiki.analog.com/)
* [GNURadio Wiki](https://wiki.gnuradio.org)
* [LinkedIn Learning](https://www.linkedin.com/learning/) - Great source for learning stuff. I recommend [Learning Linux Command Line](https://www.linkedin.com/learning/learning-linux-command-line-2/learning-linux-command-line?u=76811570).

## Guided Tutorials for HRG-Lab

Now that GNURadio is installed, we can use GNURadio to set up some basic examples. Descriptions of each tutorial are below, and the instructions are inside each specific sub-directory of this repository.

### (Beginner) FM Transmitter Simulation

### (Beginner) Interfacing with Hardware (PlutoSDR)

### (Intermediate) Installing an OOT Module

### (Advanced) Adding a Block with `gr_modtool`, the Swiss-Army Knife of GNURadio
