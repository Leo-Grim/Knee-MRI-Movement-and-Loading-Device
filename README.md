# Knee-MRI-Movement-and-Loading-Device

A compact, passive, MRI-compatible knee motion and loading device designed for use inside standard closed-bore 3 T MRI scanners.
This project was developed as an Imperial College London Bioengineering group project to enable controlled knee flexion and compressive loading during MRI. The aim is to support imaging of load-dependent knee behaviour, such as cartilage deformation, altered joint contact mechanics, and meniscal extrusion, which may not be visible during conventional unloaded supine MRI.

## Project Overview
Conventional knee MRI is usually performed with the patient lying supine, with the knee unloaded and close to full extension. While this gives high-quality anatomical images, it does not represent the mechanical conditions experienced by the knee during movement or weight-bearing.

This device addresses that limitation by providing:

- Controlled knee flexion using a passive notch-lock mechanism
- Compressive loading through a resistance-band footplate system
- MRI-compatible construction using non-ferromagnetic materials
- Operation inside a standard closed-bore 3 T scanner
- Patient-controlled adjustment using guiding ropes

The prototype is intended as a research platform for future loaded and flexed knee MRI studies.

## Key Features

- Passive mechanical actuation
- No motors, electronics, pneumatics, or ferromagnetic components
- Compatible with closed-bore 3 T MRI environments
- Constructed from PLA and HDPE
- Adjustable knee flexion through discrete notch positions
- Resistance-band-based axial loading
- Low-cost fabrication using FDM 3D printing and CNC machining
- Modular design for future refinement and replication

## Device Concept

The device consists of two main subsystems:

### 1. Movement System

The movement system controls knee flexion. It uses a hinged leg plate and a notch-lock base plate to hold the leg at predefined angles. The user can adjust the knee angle by pulling guide ropes while lying inside the scanner.

### 2. Loading System

The loading system applies compressive force through the foot. A footplate moves along rails against resistance bands, generating a displacement-dependent load. Loading is applied by pushing the footplate to its end position before imaging.

## Materials

The prototype was manufactured from MRI-compatible polymer materials:

- **PLA**: used for 3D-printed components, including hinge parts, rails, notches, backplate, and footplate components
- **HDPE**: used for CNC-machined plate sections due to its flexibility, impact resistance, and machinability

No ferromagnetic, electronic, or closed conductive components are used in the current prototype.

## Fabrication

The prototype was fabricated using:

- Fused deposition modelling 3D printing
- CNC machining of HDPE sheets
- Resistance bands for passive loading
- Polymer-based fasteners and mechanical components where possible

/FEA
/testing-data
/docs
