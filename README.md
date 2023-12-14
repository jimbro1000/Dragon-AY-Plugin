# AY(ish) Plugin For Dragon32 Rev 3 #

This repository contains the design for an emulated AY8910/2/3 
plugin board to fit the Dragon32 Rev3 boards.

The design is based on the avr-ay designs using an Atmega MCU

The design does not support the PIO capabilities of the
original AY8910/2, providing only the sound generation

The footprint is a significant departure using a largish
plcc style footprint but thanks to a lack of support in
KiCad this has come out larger than intended