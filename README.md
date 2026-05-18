# **OS1:** An Open-Source, Automated, High-Resolution DLP Printer for Microfluidic Device Fabrication

Open Source 1 (OS1), an open-source, high-resolution, DLP-based vat photopolymerization platform for fabricating microfluidic devices. Microfluidic function is defined by interconnected negative features, i.e., void regions that form channels, chambers, valves, and other fluidic elements within the printed structure. Accurately producing these features requires high optical resolution, uniform exposure, precise build-surface alignment, and reliable focus control. OS1 addresses these requirements in an automated platform derived from more than 10 years of custom DLP printer development for microfluidics. The printer enables rapid fabrication of microfluidic devices with complex three-dimensional negative-feature geometries that are difficult to achieve using traditional cleanroom-based methods. To reduce dependence on specialized hardware expertise and custom calibration tools, OS1 includes automatic build-surface planarization, automated focus calibration, active focus correction across the build area using a confocal displacement sensor, light-engine power correction using a fiber-optic photodiode sensor, and grayscale image correction for improved irradiance uniformity. These capabilities support repeatable, high-quality fabrication while making advanced microfluidic 3D printing more accessible to other research groups.

This repository is the home to the digital design files for the OS1's hardware, the standalone instruction manual, and the bill of materials.

## CAD

In the CAD folder, step files for the entire printer assmebly and each custom component are included. For parts that are FDM printed, a .3mf file is included. For aluminum parts and polycarbonate parts that are to be cut on a CNC waterjet, a .dxf "Tetris" layout file is included. There are also folders containing the design and manufacturing files for 2 custom printed circuit boards.

## Bill of Materials

The Bill of Materials is contained in a Microsoft Excel spreadsheet (.xlsx). It is oraganized into subassembly groups to match the instruction manual.

## Supplemental

The Visitech LRS WQ light engine utilized in this platform has been discontinued and replaced with an LRS WQ Plus light engine. This new version is not compatible with the current OS1 software and has not been validated with our platform; however, the full STEP assembly for the updated version and an alternate instruction manual are available in the supplemental information. Note on printer software: the LRS WQ Plus is a major revision of the LRS platform and uses a new communication protocol from the previous version. To implement the new LRS WQ Plus, a new hardware driver will need to be written which does not rely on HDMI data transfer from the Raspberry Pi.

Included in the supplemental materials is also a set of videos detailing specific parts of printer construction, operation, and maintenance.