# AC-to-DC Regulated Power Supply

## Project Overview

This project focuses on designing and developing a regulated DC power supply that converts 230V AC mains into a stable 5V DC output using a step-down transformer, a full-wave bridge rectifier, a filter capacitor, and a 7805 linear voltage regulator.

**Project Status:** In Progress

## Design Specifications

| Parameter         | Specification                           |
| ----------------- | --------------------------------------- |
| Input             | 230V AC, 50Hz                           |
| Transformer       | 230V AC to 9V AC                        |
| Rectifier         | Full-wave bridge rectifier              |
| Diodes            | 4 × 1N4007                              |
| Filter Capacitor  | 10,000 µF (design value to be verified) |
| Voltage Regulator | 7805                                    |
| Target Output     | 5V DC, 1A                               |

## Block Diagram

230V AC → Step-Down Transformer → Bridge Rectifier → Filter Capacitor → 7805 Regulator → 5V DC Output

## Circuit Design

The circuit consists of the following stages:

1. **Step-Down Transformer:** Reduces the AC voltage and provides isolation from the mains.
2. **Bridge Rectifier:** Converts AC into full-wave pulsating DC using four 1N4007 diodes.
3. **Filter Capacitor:** Smooths the rectified DC voltage by reducing ripple.
4. **7805 Regulator:** Regulates the filtered DC input to a nominal 5V output.

## Calculations

The design calculations cover:

* Transformer secondary peak voltage
* Bridge rectifier voltage drop
* Filter capacitor sizing and ripple voltage
* Regulator input voltage requirements
* Regulator power dissipation

## Bill of Materials

Refer to `calculations/bom.csv` for the component list.

## Testing and Results

Testing results will be added after the circuit is assembled and validated.

## Learning Outcomes

* AC-to-DC conversion
* Full-wave bridge rectification
* Capacitor filtering and ripple voltage
* Linear voltage regulation
* Component selection and power dissipation

## Safety

This project involves hazardous mains voltage. The mains section must be properly isolated, fused, enclosed, and handled with appropriate electrical safety precautions.
