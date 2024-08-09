---
title: Top Techniques for Avoiding Voids & Deficiencies in Your 3D Printing Projects
date: 2024-08-07 22:17:13
updated: 2024-08-08 11:44:34
tags:
  - printer
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/xD3YkfhmCz6nSQvsp8WTeC-320-80.png
---

## Achieving Perfectly Sealed 3D Prints: How to Avoid Common Hole and Gap Issues

One of the issues 3D printer hobbyists face is holes and gaps in 3D prints. These issues can occur in any 3D print (even on the[best 3D Printers](https://www.tomshardware.com/best-picks/best-3d-printers) ) and they compromise the print's structural integrity and overall strength and usually appear as small cracks on the print’s surface. Sometimes, they appear as more profound weaknesses that distort the intended geometry accuracy, which can lead to mechanical failure, especially for the functional prints or prototypes, more so in areas where precision and reliability are crucial.

 As with other 3D printing problems, you need to understand the root cause to know how to address it. Different types of holes and gaps can appear on the print based on the location, size, and structure, and we will look at the main ones and how to solve them.

## 1\. Holes and Gaps on the Top Section of the Print

![How to Prevent Holes and Gaps in 3D Prints](https://cdn.mos.cms.futurecdn.net/hizhp3jQoN2EAWHJsY3NPA-320-80.png)

 (Image credit: Eliteprint3d)

 Holes and gaps on the top section of your 3D print can quickly be noticed and are usually characterized by hollow or sunken areas on the top surfaces. They typically occur during the cooling phase of the 3D printing process, and the deposited layers retract or shrink, leaving voids behind on the top surfaces. They can also occur when there is no sufficient top-layer infill. You can fix these by increasing the top layer thickness so that more material is deposited to create a more solid surface.

![How to Prevent Holes and Gaps in 3D Prints](https://cdn.mos.cms.futurecdn.net/KehSpotVtUyHXKE6wK8jY8-320-80.png)

 (Image credit: Tom's Hardware)

 As you increase it, you also need to check the[infill patterns](https://www.tomshardware.com/how-to/choose-infill-pattern-for-3d-prints) and ensure that you use one that is not susceptible to pillowing, like gyroid and honeycomb. Adjusting cooling to ensure the layers have enough time to cool is vital. You can adjust the fan speed in the[3D printer slicer](https://www.tomshardware.com/features/6-best-3d-printer-slicers-and-how-to-use-them) and ensure it works as required.

![How to Prevent Holes and Gaps in 3D Prints](https://cdn.mos.cms.futurecdn.net/as8GnfwzxKhA3oP7BwBA8A-320-80.png)

 (Image credit: Tom's Hardware)

 When the uppermost layers of the print do not have sufficient support or material to form a solid surface, the deposited filament may retract or shrink, leaving behind voids that manifest as holes or depressions.

## 2\. Tiny Holes in the Walls of the 3D Print

![How to Prevent Holes and Gaps in 3D Prints](https://cdn.mos.cms.futurecdn.net/ohZWqZjArgJmwVqf8fhtu9-320-80.png)

 (Image credit: Tom's Hardware)

 Tiny holes or gaps on the walls can be caused by[under-extrusion issues](https://www.tomshardware.com/how-to/fix-under-extrusion-issues-in-3d-prints) due to the printer not extruding enough filament, especially when it passes through complex geometries. It can also be caused by inconsistent layer adhesion, maybe because of a clogged nozzle, inconsistent diameter, or improper printer calibration. To address this issue, you must check your 3D printer and ensure that the nozzle is not clogged by regularly cleaning it. You must also check the extruder and ensure it is well-calibrated and other components like the gear system are working as expected. Additionally, adjusting the flow rate compensation, temperature, and speed can address under-extrusion issues, and you can find those settings in your slicer.

 If the gaps appear because of the printer struggling to print thin walls, you need to activate the**Print Thin Walls** setting in Cura Slicer (if it’s the one you are using) or**Detect Thin Walls** if you are[using PrusaSlicer](https://www.tomshardware.com/how-to/use-prusaslicer) . The printer can struggle to deposit filament on the specific areas intended in the print if the horizontal walls of the design are thinner than the diameter of the nozzle. When you activate that feature, the slicer optimizes the extrusion flow for thin walls to ensure more accurate filament deposition.

## Stay On the Cutting Edge: Get the Tom's Hardware Newsletter

 Get Tom's Hardware's best news and in-depth reviews, straight to your inbox.

 Contact me with news and offers from other Future brands  Receive email from us on behalf of our trusted partners or sponsors

 By submitting your information you agree to the[Terms & Conditions](https://futureplc.com/terms-conditions/) and[Privacy Policy](https://futureplc.com/privacy-policy/) and are aged 16 or over.

 In Cura, you can find it in the**Walls** section. You can select the box for**Print Thin Walls** .

![How to Prevent Holes and Gaps in 3D Prints](https://cdn.mos.cms.futurecdn.net/taDeWfHqvLvgkKsyhC4tD8-320-80.png)

 (Image credit: Tom's Hardware)

## 3\. Large Gaps that Result in Layer Separation

 When the layers fail to adhere correctly to each other, they can start separating, resulting in visible gaps and cracks and the print becomes weak and you can pull the layers apart. One leading cause of this issue is inadequate layer adhesion due to insufficient nozzle temperature or improper bed adhesion.

 To solve this issue, you need to optimize the temperature settings to ensure they are consistent and you need to experiment with different ranges depending on the filament and printer you are using until you achieve the optimal value. You can also 3D print a[temperature tower](https://www.thingiverse.com/thing:2729076) and use it to experiment with different temperatures until you find the appropriate value.

 You also have to ensure that the bed temperature is set correctly for the specific filament you use to provide a stable foundation for the first layers which helps overall adhesion. Layers cooling at different rates can also cause layer separation especially at the edges. So you need to adjust the cooling settings of the fan so that there is proper cooling of the layers.

 Adjusting the flow rate is essential as it helps to ensure that the quantity and thickness of the filament extruded from the nozzle are consistent. When the flow rate is set too low, it results in under-extrusion as insufficient filament will be extruded, leading to noticeable gaps.

 You can 3D print a[flow calibration cube](https://www.thingiverse.com/thing:4838076) and use it to find the optimal value. You must also lower the layer height (the distance between each layer deposited). The default value is usually 0.2mm. Slowing down the 3D printing speed can also help fix the issue, as it allows for better deposition and improved bonding between the layers. In addition to adjusting those settings, you also need to ensure that the filament you are using is dry as moisture in the filament can cause pressure build-up in the nozzle. When extruded, it might not come out as intended, and this brings problems. You need also to ensure that it has a consistent diameter all through.

## 4\. Gaps in the First Few Layers of the 3D Print

 Gaps in the initial layers of your print can be as a result of an improperly leveled print bed. If the distance between the nozzle and the bed is uneven, it can contribute to the gaps. If it is too close to the bed, for example, it may compress the filament affecting the smooth flow and leading to gaps as the material struggles to extrude.

 Alternatively, the filament might not adhere adequately to the surface if the nozzle is too far from the bed. These variations in the nozzle and bed distance can disrupt the uniformity of the initial layers. To address this, you need to properly level your 3D printer bed and ensure the Z offset is set correctly.

 You can[manually level your 3D printer bed](https://www.tomshardware.com/how-to/level-3d-printer-bed) or use the automatic bed leveling feature found in most of the best[3D printers](https://www.tomshardware.com/best-picks/best-3d-printers) . You can[correctly set the Z offset of your 3D printer](https://www.tomshardware.com/how-to/correctly-set-3d-printer-z-offset) manually by adjusting the nozzle height as you place a piece of paper on the bed. You can find the Z offset setting on the menu of your 3D printer.

![How to Prevent Holes and Gaps in 3D Prints](https://cdn.mos.cms.futurecdn.net/TtXhijJg3aMuMsYBQqUwB9-320-80.png)

 (Image credit: Tom's Hardware)

## 5\. Holes and Gaps in the Corners of the Print

![How to Prevent Holes and Gaps in 3D Prints](https://cdn.mos.cms.futurecdn.net/yNYqczmqhVnKMJbe2eFSLF-320-80.png)

 (Image credit: Tom's Hardware)

 3D printers usually face challenges when printing corners, especially those that are sharp because the extruder needs to change direction and accelerate within a short time when it comes across those areas. There can be a build up of pressure on the extruder as the printer navigates through the corners which can lead to variations in extrusion, more so when printing at high speeds. To fix this, you need to start by adjusting the acceleration and jerk settings to ensure that the extruder can smoothly transition between different directions without introducing excessive vibrations.

![How to Prevent Holes and Gaps in 3D Prints](https://cdn.mos.cms.futurecdn.net/vXV42Vo2jQBbjNLJ56uaP8-320-80.png)

 (Image credit: Tom's Hardware)

 In addition to jerk and acceleration settings, you also need to slow down the printing speed for the printer to manage the abrupt changes in the direction better when it approaches the sharp corners. Fine-tuning the retraction settings can also minimize the issues like blobs and[stringing in 3D prints](https://www.tomshardware.com/3d-printing/how-to-fix-stringing-in-3d-prints) that can result in gaps in the corners in severe cases.

 The above strategies can help address issues related to holes and gaps in your 3D prints. If you have a print that has suffered from these problems, you can salvage it through post-processing activities. One approach is to apply filler material like[Bondo](https://target.georiot.com/Proxy.ashx?tsid=45723&GR%5FURL=https%3A%2F%2Famazon.com%2Fs%3Fk%3Dbondo%26crid%3D18ZZ4URMWWITX%26sprefix%3Db%252Caps%252C1739%26ref%3Dnb%5Fsb%5Fnoss%5F2%26tag%3Dhawk-future-20%26ascsubtag%3Dtomshardware-us-3135570975057401036-20) or[Milliput](https://target.georiot.com/Proxy.ashx?tsid=45723&GR%5FURL=https%3A%2F%2Famazon.com%2Fdp%2FB002CNEWAM%3Fth%3D1%26tag%3Dhawk-future-20%26ascsubtag%3Dtomshardware-us-7059939473745178478-20) to the areas with gaps or holes to refine the appearance and structural integrity. Other strategies like applying acetone vapor smoothing and painting can also help achieve a smoother surface, even though it might not work on all prints.

## Related 3D PrintingTutorials

**More:** [5 Ways Fix Z Banding in 3D Printing](https://www.tomshardware.com/how-to/fix-z-banding-in-3d-printing)

**More:** [How to Use FreeCAD for 3D Printing](https://www.tomshardware.com/how-to/use-freecad-3d-printing)

**More:** [How to Convert OBJ Files to STL Files for 3D Printing](https://www.tomshardware.com/how-to/convert-obj-files-to-stl)

**More:** [How to Use PrusaSlicer: A Beginners Guide](https://www.tomshardware.com/how-to/use-prusaslicer)


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>
