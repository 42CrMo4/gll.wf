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

Many designs rela on 2.54mm pinheaders or 

## How does it work?

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