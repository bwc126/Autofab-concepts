# Autofab-concepts
Conceptual development and modeling of an automatic fabricator based on contemporary technology.

Key Goals:

-Capable of transforming simple chemical inputs into complex organic and inorganic chemicals, additively-manufactured products, and assemblies incorporating SMD's and other mass produced components.

-Total self-replication except SMD's (for now).

*Current Status: Early Development (v0.2)*

## Chemical Processing (ChPU)
Uses modular microfluidic components to process chemicals from simple inputs.

## Materials Processing (MPU)
Uses a combination of micro-extrusion, electrojetting, and electroplating to fabricate components with material from the chemical processing system.

## Convergent Assembly (CAU)
Uses diamagnetically actuated microdrones to assemble the fabricated components, along with pre-fabricated off-the-shelf components if necessary, into more complex finished products. Provides structure to the whole system and a clean, controlled environment.

## Power and Control
Provides appropriate power and signal channels for all manufacturing systems: ChPU, MPU, CAU. Provides an interface for loading digital manufacturing files.

*Necessary for Next Stage: (Early-Mid-Development, v0.3)*

ChPU:
- Reservoir Modules (I,II,III)
- Intake and output interfaces (I)
- Interconnects for ChPU-I
- Ensure electronics meet power/control requirements, known physical constraints (physical dimensions, number of actuation electrodes, etc.)
- Wiring for all ChPU components
- Basic feasible chromatograph spectroscope, mass spectrometer designs

MPU:
- Feasible and viable electroplater design
- Wiring for all MPU components
- Ensure electronics meet p/c req.s, known phys constraints
- Microfluidic interconnects
- Complete dia-mag substrate paths

CAU:
- Design feasible diagmagnetic drones, substrate (I,II)
- Align substrate power control systems with known constraints
- Complete all basic necessary substrate paths

Assembly:
- Sufficient mechanical support for anticipated system density and conformation

*Necessary for Mid-Development (v0.4)*

ChPU:
- Intake and output interfaces (II,III)
- Interscale i/o adapter
- Microfluidic interlocks
- Mechanical interlocks
- Electrical interlocks

MPU:
- Multiphasic microfluidic processing module
- Microfluidic interlocks
- Mechanical interlocks
- Electrical interlocks

CAU:
- Drone tools/attachments
- Mechanical interlocks
- Electrical interlocks

Assembly:
- External enclosure
- External dia-mag substrates

Power and Control:
- Power, control lines and SMD for all ChPU/MPU/CAU
- User interface (hardware)
- Intermediate control systems

*Necessary for Late-Mid-Development (v0.5)*
