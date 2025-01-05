---
title: GLL1 - UPDI Programming Interface
layout: default
redirect_from:
  - /1/
---

# GLL1 - UPDI programming interface connector

This document describes the UPDI programming interface connector specification with the name GLL1. 

## What is it for?

It aims to be a cost effective hands free UPDI connector interface for programming ATtiny Microchip MCUs. 

## Why does it exist?

Many designs rela on 2.54mm pinheaders or bulky connectors. 
They are either not very reliable or pleasant to work with or are big and "expensive" to use for each board. 
For this reasons the [WR-WST REDFIT IDC SKEDD](https://www.we-online.com/en/components/products/REDFIT_IDC_SKEDD) connetor is used. 

## How does it work?

### pinout

![](../assets/images/gll1-pinout.svg)

### connector

### footprint

# Cabling colours (optional)

The cabling to the connetor is not too important, as the connector makes only in the correct positions contact, but for good practice it makes it more abvois for the user.

VCC - red
GND - black
UPDI - blue
TX - green (optional)

### pros
- hands free as the connector is self clamping
- cheap on the target side (no additional component)
- Reverse polarity protected
- no crimping tool needed (atleast not in low quantities)

### cons
- big footprint compared to TagConnect or 3x1 pinheader
- Troughthole for all pins 
- connector only rated for 50 cycles (aspite questionable for this perpose)

# alternative connector ideas

A non comprehensible list of connectors for this purpose:
- ATMEL ICE - UPDI 6 pin header
- [AVR UPDI headers](https://microchip.my.site.com/s/article/ATMEL-ICE---UPDI-6-pin-header-internal-connections-during-programing) - MCUdude
- [1.27mm self-clamping zigzag](https://avdweb.nl/arduino/attiny3217/ftdi-updi-connector) - avdweb
- 3 pin 2.54mm header (VCC-UPDI-GND) or any combination
