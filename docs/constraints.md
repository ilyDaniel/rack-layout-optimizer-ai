# Rack Layout Constraints

The optimizer must respect several infrastructure constraints.

## Physical Constraints

* Each rack slot can contain only one hardware module.
* Modules must fit within the rack grid.

## Power Constraints

Total power consumption of all modules must not exceed the rack power limit.

Example:

Rack Power Limit: 12 kW

## Thermal Constraints

Hardware modules produce heat.

Cooling units reduce heat for nearby modules.

The layout must keep total heat generation within cooling capacity.

## Inventory Constraints

Only a limited number of modules are available.

Example inventory:

* 4 GPU nodes
* 6 CPU servers
* 2 network switches
* 2 cooling units

## Adjacency Rules

Some modules benefit from proximity.

Examples:

GPU nodes next to switches improve bandwidth.
Cooling units reduce heat for nearby modules.

These relationships create strategic placement decisions.
