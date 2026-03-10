# Problem Definition

## Overview

Data centers contain racks filled with hardware modules such as GPU nodes,
CPU servers, networking equipment, and cooling units.

The arrangement of hardware within a rack can significantly impact:

* compute performance
* power consumption
* cooling efficiency
* network performance

Manually designing optimal rack layouts is difficult due to the number of
possible configurations and the infrastructure constraints involved.

This project explores the use of **constraint programming and optimization
algorithms** to automatically generate efficient rack layouts.

---

## Rack Model

A rack is represented as a 2D grid of slots.

Example rack layout:

[ GPU ][ GPU ][ SWITCH ]
[ CPU ][ GPU ][ CPU ]
[ CPU ][ COOL ][ SWITCH ]

Each slot can contain one hardware module.

---

## Hardware Modules

Example modules:

GPU Node
CPU Server
Network Switch
Cooling Unit
Storage Node

Each module contributes different properties such as compute capacity,
power consumption, and heat generation.

---

## Objective

The goal is to generate rack layouts that maximize system performance while
satisfying operational constraints.

This will be approached using both **constraint programming** and
**AI optimization techniques**.
