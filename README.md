# Autofab-concepts
Conceptual development and modeling of an automatic fabricator based on contemporary technology

*Current Status: Very Early Development (v0.1)*

## Chemical Processing (ChPU)
Uses modular microfluidic components to process chemicals from simple inputs.

## Materials Processing (MPU)
Uses a combination of micro-extrusion, electrojetting, and electroplating to fabricate components with material from the chemical processing system.

## Convergent Assembly (CAU)
Uses diamagnetically actuated microdrones to assemble the fabricated components, along with pre-fabricated off-the-shelf components if necessary, into more complex finished products. Provides structure to the whole system and a clean, controlled environment.

## Power and Control
Provides appropriate power and signal channels for all manufacturing systems: ChPU, MPU, CAU. Provides an interface for loading digital manufacturing files.

*Necessary for Next Stage: (Early Development, v0.2)*

ChPU:
- ~~Distillation, chromatographic column separator modules~~
- ~~Repeating unit configuration (l1 cache -> sep./cat./merge/mix/xchange/l1,l2 cache)~~

MPU:
- ~~Electroplater model~~
- ~~Electrojet emitters enlarged to accomodate wiring~~
- ~~Material distribution in line with ChPU standards~~

CAU:
- ~~CAU I~~/II interior (7/21 WIP)
- ~~Align electronics with known constraints (8/7/16 WIP)~~

Assembly:
- ~~At least one complete assembly of each kind and scale up to CAU II~~

*Necessary for Mid-Development (v0.3)*

ChPU:
- Reservoir Modules (I,II,III,IV)
- Intake and output interfaces
- Interconnects for ChPU-I
- Ensure electronics meet power/control requirements, known physical constraints (physical dimensions, number of actuation electrodes, etc.)
- Wiring for all ChPU components
- Basic feasible chromatograph spectroscope, mass spectrometer designs

MPU:
- Feasible and viable electroplater design
- Wiring for all MPU components
- Ensure electronics meet p/c req.s, known phys constraints
- Microfluidic interconnects 

CAU:
- Design feasible diagmagnetic drones, substrate (I,II)
- Align substrate power control systems with known constraints
- Complete all basic necessary substrate paths

Assembly:
- Sufficient mechanical support for anticipated system density and conformation
