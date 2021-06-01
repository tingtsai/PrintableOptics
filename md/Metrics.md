---
layout: page
title: Process
---
The process of microlens fabrication can be broken down into three process - File generation, 3-D printing, and Lens Optimization. Each step has its critical factors and we design corresponding metrics and characterization strategy to evaluate those factors.

![Metrics](/assets/img/Metrics.jpg) 

At file generation stage, the STL files could be generated from any 3-D CAD software(AutoCAD, Solidworks, TinkerCAD, Blender, etc.). We use Zemax OpticStudio for STL file generation because its powerfulness and convenience to do ray tracing and image simulation. We further use Describe to convert STL file to writing sequences. In Describe, we can define parameters including hatching distance and slicing distance for the wrting and these parameter would highly affects the writing accuracy and performance. In micro-optics printing, the suface profile and smoothness matter the most for the optical performance. We could use Keyence Laser confocal microscope to evaluate the surface profile and use SEM and AFM to evaluate the surface roughness. 


At 3-D printing stage, we harness Nanoscribe GT system to perform the printing. The critical factors include laser power and scan speed. Pretreatment and post-processing of the substrate also highly affect the final writing performance. The printing results can be evaluate in terms of repeatability and mechanical stability and we use Keyence 3-D microscope and SEM (0 and 90 degree) characterization for this purpose. 


Once the microlens fabrication protocol has been established, we could enter the last stage - lens optimization. For this purpose, the experiments could be done by either Zemax simulation or real optical experiment. We evaluate the image quality and point spread function (PSF) to figure out the curvature combination to produce the best microlens! 
