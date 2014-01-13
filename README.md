GPIBUSB Adapter PCB
===================

This repository contains the KiCAD PCB project files for the GPIBUSB Adapter project.

The associated firmware project can be found on GitHub at www.github.com/Galvant/gpibusb-firmware

Pre-assembled boards can be found at www.galvant.ca

About
-----

Many pieces of test & measurement equipment feature a connectivity port labelled "GPIB" which stands
for General Purpose Interface Bus. On some equipment this can also be labelled as "HPIB" after the 
company that originally invented it.

Commercial USB to GPIB adapters contain a lot of features and functionality, but are also very 
expensive ($500+ new). This is well out of price range for most hobbyists, as well as plenty of engineers
and scientists. A lot of people don't need all of the advanced GPIB communication functionality; some
are just looking to download multimeter readings or oscilloscope waveforms to their PC. This firmware
project aims to implement as much GPIB communication functionality as possible, while still remaining
accessable.

Another limitation of your typical USB to GPIB adapter is the development environment restriction
due to the required drivers. For example, these vendors only provide Linux drivers for Red 
Hat-based distributions, but these drivers do not include MATLAB bindings! Instead of having to deal
with all sorts of GPIB and VISA driver stuff, this GPIBUSB adapter presents itself to the attached PC
as a serial port, allowing a wide variety of operating systems and development environments to utilize
it. So although this means that this adapter is NOT a drop in replacement for convential ones, this
flexability is desired by many.

Related Repos
-------------

See the following repos for more information

Firmware: https://www.github.com/Galvant/gpibusb-firmware
Docs: https://www.github.com/Galvant/gpibusb-documentation
Bootloader: https://www.github.com/Galvant/gpibusb-bootloader

Firmware Compatibility
----------------------

Here hardware revisions (left) are listed with their compatible software versions (right). The hardware
revision is marked on the silkscreen on the adapter PCB.

revB/rev2: v1 - v3

rev3 family (ie 3.1, 3.2): v4

License
-------

This work is released under the Creative Commons Attribution-Sharealike 3.0 license.
See http://creativecommons.org/licenses/by-sa/3.0/ or the included license/LICENSE.TXT file for more information.
