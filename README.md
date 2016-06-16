# Autofab-concepts
Conceptual development and modeling of an automatic fabricator based on contemporary technology

*Current Status: Very Early Development*

## Chemical Processing (ChPU)
Uses modular microfluidic components to process chemicals from simple inputs.

## Materials Processing (MPU)
Uses a combination of micro-extrusion, electrojetting, and electroplating to fabricate components with material from the chemical processing system.

## Convergent Assembly (CAU)
Uses diamagnetically actuated microdrones to assemble the fabricated components, along with pre-fabricated off-the-shelf components if necessary, into more complex finished products.

*Necessary for Next Stage: (Early Development)*

ChPU:
- Distillation, chromatographic column separator modules
- ~~Repeating unit configuration (l1 cache -> sep./cat./merge/mix/xchange/l1,l2 cache)~~

MPU:
- ~~Electroplater model~~
- Electrojet emitters enlarged to accomodate wiring (6/15/16 WIP)
- Material distribution in line with ChPU standards

CAU:
- CAU II interior
- Align electronics with known constraints

Assembly:
- At least one complete assembly of each kind and scale up to CAU II
