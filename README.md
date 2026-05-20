Image Build Test
======

My test to create custom RPi images

Repo derived from [guysoft/OctoPi](https://github.com/guysoft/OctoPi) and uses [guysoft/CustomPiOS](https://github.com/guysoft/CustomPiOS)


# Known quirks
* Sometimes the Lab-Box splash screen does not appear at first boot, but on the first shutdown and thereafter on every boot. Nothing to worry about, maybe only confusing when flashing new SD cards


# Roadmap
* Make Pull Request in CustomPiOS repo to get the project on the list there in the readme https://github.com/guysoft/CustomPiOS
* Plymouth adding progress bar at boot
  * Can be done like here with the script https://github.com/1deterministic/Plymouth-Progress-Bar and docu here: https://www.freedesktop.org/wiki/Software/Plymouth/Scripts
* Move generation of self-signed certificate for nginx into some kind of "first startup" command, so not every image has the same cert & key
