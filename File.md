---
layout: page
title: File generation
---

In order to print microlens with better image quality, we aim to print doublet lens as our final target. However, doublet lens has an overhanging structure and this could pontential leads to the writing failure. 

For the image below, we show a set of lens we designed for relay system. Our structures are challenging due high-aspect ratio and overhanging structures. Describe software has the ability to correct writing order for different writing blocks to avoid flying writing. However, when overhanging structure exists within the same block, we need further trick to maintain structural integrity. 

![](/assets/img/STL.png)




For some lens design, we have some lens facing to the bottom and this will lead to float writing for the structure and create off-center issue. (As the image below)

![](/assets/img/float.png)




In order to deal with this, we have to use a small trick for Describe. We generated two separate gwl code from two STL files for supported rod and lens and insert a z movement in between. We also set the writing direction differently for two gwl to avoid flying structures during writing.  



![](/assets/img/combine.png)



Here we exemplify how we programmed GWL codes in Describe to avoid float writing.


![](/assets/img/gwl.png)



And this issue could be solved after we applied this trick.

![](/assets/img/solve.png)
