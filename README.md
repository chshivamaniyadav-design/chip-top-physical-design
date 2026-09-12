# CHIP_TOP — GPRS Broadcast Network

## Project Overview

CHIP_TOP is a top-level VLSI physical design implementation
using Cadence Innovus for a 45nm technology node.

The design integrates 16 macros and approximately 20K instances
through the physical design flow from floorplanning to routing
and physical verification.

## Project Specifications

| Parameter | Value |
|---|---|
| Technology | 45nm |
| EDA Tool | Cadence Innovus |
| Design | GPRS Broadcast Network |
| Macros | 16 |
| Instances | ~20K |
| Metal Layers | 9 |
| Target Frequency | 250 MHz |
| Power Domains | 1 |

## Physical Design Flow

Design Import → Floorplanning → Power Planning → Placement
→ Clock Tree Synthesis → Routing → Timing Analysis → DRC

## Key Work

- Top-level floorplanning and macro integration
- IO ring placement
- Power distribution planning
- Placement and CTS analysis
- Top-level routing
- Timing analysis
- DRC verification

## TCL Scripts

TCL scripts used for the physical design implementation are
included in this repository.

## Tools

- Cadence Innovus
- TCL
- Linux
