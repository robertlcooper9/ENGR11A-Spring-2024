---
title: "[Design Project 1] First 3D Print and Stress Test"
summary: This is the very first 3D print I made. It is a name tag. The stress tester I am trying to print has a mix of fine details such as small holes, overhangs, and cylindrical protrusions, which test the printer's precision and its ability to handle overhangs without support.
tags:
  - DP
date: 2024-01-23
external_link: https://marcopo1o.github.io/engineer/project/first/
---

# 1. Analysis of the First 3D Printed Object

## Process Overview:

The 3D printing process began by accessing the 3MF file provided by the instructor on the Brandeis University's [resource repository](http://brandeis.box.com/v/prusaminifiles). The file was initially designed for the Prusa Mini printer and was preconfigured with specific design parameters suited for the class project.

#### Design Customization:

Upon downloading, the 3MF file was edited to personalize the design — the name was replaced with my own. This customization involved not only a change in the text but also an adjustment in the font size and style to fit the print bed while maintaining legibility.

## Print Evaluation:

![First Print Image Placeholder](featured.jpg)

The resulting print, as displayed above, reveals a significant detail about the printer's capabilities. It is apparent that the font choice had segments that were too fine for the printer to accurately reproduce, leading to disconnection in the text. This highlights the limitations of the printer in handling extremely thin features that demand precision beyond its current setting or capability.

### Color Layering Issue:

![Second Print Image Placeholder](nametag2.jpg)


The design intended for a dual-color output, with a filament change to mark the text distinctly from the base layer. However, as shown in the second image, the print is monochromatic. This was due to an oversight during the slicing phase, where the file was re-sliced without setting the pause for a filament change. 

![Prusa Slider](slicer.png)

This misstep underscores the importance of attentive file preparation in multi-color 3D printing.

*Conclusion:*

The exercise has been enlightening in understanding the constraints of 3D printing technology, particularly in terms of fine detail work and multi-material prints. It emphasizes the need for careful pre-print configuration and the printer's precision limits.

$~~$

$~$

$~$

$~$

$~$

# 2. Analysis of 3D Print Stress Test

The stress tester I am trying to print has a mix of fine details such as small holes, overhangs, and cylindrical protrusions, which test the printer's precision and its ability to handle overhangs without support. I can't find the exact link I used. But I found a similar one [here](https://www.thingiverse.com/thing:2656594).

![Image of the 3D print showing overhangs](stresstest4.jpg)

From the product, it is evident that the printer is capable of creating fine details to a certain degree. The small holes on the flat surface are well-formed, and the squares and rectangles are accurately produced with straight edges. This indicates a good level of precision in the XY plane. However, there are noticeable strings of plastic and minor imperfections on the parts of the object with overhangs, suggesting that the printer may struggle with cooling or extrusion control. This is a common challenge in 3D printing, where overhangs can lead to drooping if the material does not solidify quickly enough.

![Image of the 3D print showing cylindrical protrusions](stresstest2.jpg)

The cylindrical pillars show the printer's capability to create round shapes and vertical structures. The roundness of the pillars appears to be fairly consistent, although there is some evidence of oozing or stringing between the pillars. This could be due to the retraction settings on the printer not being fully optimized.

![Image of the 3D print showing fine details](stresstest1.jpg)

Overall, the printer demonstrates a commendable ability to handle moderately complex structures and details. To push the limits of what is possible to design and print, one could experiment with different materials, print speeds, temperatures, and retraction settings. Each of these variables can affect the print quality, especially for challenging geometries.

### File Formats and Their Impact

In terms of file formats, the 3MF file format would be advantageous for complex designs because it can encode color, texture, and other properties that are not supported by the STL format. The STL format, while widely supported and easy to use, represents only the surface geometry of the model without any additional attributes.

### Improvement Suggestions

Stringing in 3D prints often indicates a need for adjustments in temperature and retraction settings: lowering the nozzle temperature can reduce the oozing of plastic that leads to strings, and optimizing retraction settings can minimize the amount of filament pulled back during movements between print areas. Additionally, decreasing the print speed can allow better precision and give the material more time to cool, further mitigating the stringing effect.