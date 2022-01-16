# Build Report for a Sol'ex Spectroheliograph
by Jens Scheidtmann

## Introduction
Christian Buit created a Do-It-Yourself 3D-print spectroheliograph, see its presentation and build instructions here:
http://www.astrosurf.com/solex/sol-ex-presentation-en.html. 

This build-log reports on my attempt at building it in the form of a diary. I hope this will be useful for others, so that my 
experience will help others. 

### License

This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License. See file LICENSE for details.

## Building the Sol'ex

### 2022-01-12
The Shelyak kit arrived: Got the lenses, the diffraction grating, the slit and additional items for building a Star'ex. 
It's the [kit from Shelyak](https://www.shelyak.com/produit/es0027-solex-and-starex-optical-kit/?lang=en).

M3 and M4 Screws are on the way. I ordered sets of M3 and M4 screws from 4 mm length up to 40 mm length and some 
additional larger washers. Mold insert nuts are M3 and M4 from Ruthex. Unfortunately I couldn't find a bill of material 
on the original site.   

Hopefully one roll of PETG
[black filament from dasfilament](https://www.dasfilament.de/filament-spulen/petg-1-75-mm/158/petg-filament-1-75-mm-schwarz?c=21) 
is enough.

### 2022-01-13
Read the DADOS Tutorials by [Bernd Koch](http://astrofoto.de/german/profil/fprofil.htm) available [here](https://www.baader-planetarium.com/de/blog/neue-tutorials-fuer-den-dados-spaltspektrografen/) on Baader's site (in German, english version available [here](https://www.unitronitalia.com/schede/Baader-Dados-tutorial.pdf - very slow download). Ordered a MegaMan lamp for callibration purposes.

### 2022-01-14
Ordered two [helical ZWO focusers](https://www.astroshop.eu/focusers/zwo-helical-focuser-1-25-/p,63166) and a T2-1.25" adapter.

### 2022-01-16
Conducted first prints with the PETG filament on a Flashforge Finder. The PETG is much more prone to warping, i.e. a raft and 
glue is mandatory. Hopefully I can print the large spectrometre body parts with-out too much warping.

These are the settings I used in FlashPrint 5.2.1: 
 - Extruder Temp: 230°C
 - Shells: 3
 - Infill: 60%
 - Infull-Type: Hexagons
 - Activate Raft: Yes  (used the other default settings) 

Today's printed parts (named as given in [this picture](http://www.astrosurf.com/solex/images/image-collee-701-1.webp)):
 - Interface tel. #1 (My T2-1.25" adapter fits snuggly, even on the first warped print)
 - Support fente #2
 - Bague collimateur #5
 - Support réseau #9
 - Patte réseau #10
 - Bague objective #11
 - Bague épaisseur #13
 - Raidisseur #14

Here's a picture of the parts:
![Picture of printed parts from #1 to #14 as given in list above](pics/2022-01-16.jpg)

We will see, if I need to reprint the rings (#5 and #11) as they have a little bit of warping.

The STL-files are [available on github](https://github.com/Vdesnoux/Sol-ex) and there are some extensions available in subdirs:
 - motorisation_fichiers, move the diffraction grating with a motor
 - cache_parasite, avoid scattered light in the sprectrometre body
 - vernier_reseau, a dial for more visually selecting the color that is centered in the cam. Couldn't find the print-out for that, yet.

There is also a mailing list (french mostly): https://groups.io/g/Solex-project, on which new developments/extensions are reported.

### 2022-01-17
Printing the upper body part.
