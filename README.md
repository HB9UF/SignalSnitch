# HB9UF SignalSnitch

## Introduction

At the [Fantasy Basel](https://fantasybasel.ch) 2025, we were thrilled to participate with a booth, sharing the space with [AMSAT-HB](//www.amsat-hb.org/) in the section of the [Swiss Space Museum](https://swissspacemuseum.ch/). As part of our contribution to this unique blend of science, pop culture, and hands-on experiences, we introduced the SignalSnitch -- a simple, educational RF detector kit designed by Andreas HB9HDF.

The SignalSnitch kit was created specifically for this event to spark interest in amateur radio through a hands-on activity that anyone could enjoy. The kit uses through-hole technology (THT) components to keep assembly straightforward and beginner-friendly, making it ideal for both newcomers and seasoned enthusiasts. Once put together, it lights up an LED when it detects the presence of a nearby RF signal, offering a tangible and satisfying introduction to radio frequency detection.

The concept behind SignalSnitch is not entirely new -- it builds upon a [similar kit with SMD parts](https://github.com/HB9UF/aufdermauer/) conceived by Hansjörg HB9DWS and implemented by Matt HB9FRV for the 2019 HAMFEST in Zug.

The response was overwhelmingly positive! We had a fantastic time meeting fellow hobbyists, curious newcomers, and future radio amateurs. We were out of kits long before the fare ended. A heartfelt thank you to everyone who helped make this project possible and to all who stopped by to build their own SignalSnitch. Your enthusiasm made this experience truly memorable.

## Schematic and Theory of Operation
![Schematic](/contrib/schematic.png)

This simple circuit works as follows: The PCB antenna picks up electromagnetic fields, in consequence, AC voltage develops across the antenna terminals. Diodes `D1` and `D2` rectify this AC voltage to a DC voltage across capacitor `C1`. This DC voltage activates JFET `Q1` which in turn enables `Q2`. Light is emitted by LED `D3` due to the resulting collector current. Bias can be adjusted with `Pot1`.

## PCB
The PCB features the schematic on the front side and a QR code for [assembly instructions](https://hb9uf.ch/snitch). Components are clearly labeled and assembly is straight forward. See below for images of the board as well as a video of the kit in operation.
