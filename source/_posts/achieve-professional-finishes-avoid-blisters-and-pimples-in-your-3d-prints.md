---
title: "Achieve Professional Finishes: Avoid Blisters & Pimples in Your 3D Prints"
date: 2024-08-23T12:59:40.054Z
updated: 2024-08-24T12:59:40.054Z
tags:
  - printer
categories:
  - hardware
thumbnail: https://thmb.techidaily.com/97a064f556a7bb067611e98f7f33b087d4344415697ae32a33a8f3d286a74da8.png
---

## Avoid These 6 Common Pitfalls in Using Cura: Expert Fixes Revealed

Just like any other application, Cura can experience occasional failures and common errors when one is preparing designs for 3D printing. The errors range in different forms, from issues related to the 3D model you’re using, like manifold errors, to Cura just not slicing files. These errors can occur even when you are using one of the[best 3D printers](https://www.tomshardware.com/best-picks/best-3d-printers) and configured the profiles appropriately. Below, we discuss the main issues you can encounter with Cura and how to solve them.

## 1\. Cura Unable to Slice 3D Models

 Cura not being able to slice can result from various factors, including problems with the file itself and issues with the software. To fix this, you need to check the model itself and ensure that it’s not too big for your build plate, and if it is, you have to reduce the size. For example, in the image below, the file is too big than the build plate and it generated the error “**Unable to slice** .

![Common Cura Errors](https://cdn.mos.cms.futurecdn.net/67p8riRUhVNYEhTtefDyAm-320-80.png)

 (Image credit: Tom's Hardware)

 After scaling it down, it was able to slice appropriately. You can reduce the size of your file using the scale tool or you can[split the 3D model](https://www.tomshardware.com/3d-printing/how-to-split-an-object-for-3d-printing) into various separate files and arrange them on the build plate.

 If the file fits the build plate well and Cura doesn’t slice, you can restart or update it to the latest version to see if it does. It’s also important to check your computer and ensure that it meets the system requirements for running Cura because if it doesn’t, it will struggle to slice files, especially complex ones, which require more memory and power.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

 If the model has issues that require repairing, Cura will give errors, which we will discuss more below.

## 2\. Model Has Missing or Extraneous Surfaces

 Missing surfaces errors usually occur due to incomplete geometry or some sections of the design missing during the 3D modeling process. Extraneous surfaces can occur because of overlapping geometries, duplicate faces, or other inconsistencies within the surface of the model.

 To address this issue, you should inspect the model using 3D modeling software to identify and fix the issues before slicing. As you fix the issues with the model, you should also consider the orientation of the model when you import to the slicer to help avoid other issues that can occur.

## Stay On the Cutting Edge: Get the Tom's Hardware Newsletter

 Get Tom's Hardware's best news and in-depth reviews, straight to your inbox.

 Contact me with news and offers from other Future brands  Receive email from us on behalf of our trusted partners or sponsors

 By submitting your information you agree to the[Terms & Conditions](https://futureplc.com/terms-conditions/) and[Privacy Policy](https://futureplc.com/privacy-policy/) and are aged 16 or over.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. 3D Model Not Manifold

 When you face such an error, it means that the model has geometric problems that prevent it from being sliced. These problems can include holes and gaps in the meshes, open edges, and even intersecting faces. The slicer cannot properly slice the file if there are these issues, as it relies on solid, closed geometry to generate toolpaths accurately. If you decide to continue slicing the file even with these issues, the final print will have gaps and missing sections, or it can even fail to print.

 You can use various tools to fix this issue, such as Meshmixer. To use it, you will first import your file, then go to**Analysis >** **Inspector** to identify the non manifold parts.

![Common Cura Errors](https://cdn.mos.cms.futurecdn.net/7FAuidQeJZHXhXW9Je6ZNm-320-80.png)

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 (Image credit: Tom's Hardware)

 If there is an issue with the file, it will display in the new window that launches, and you can click on**Auto Repair All** to fix it. Another essential tool that you can use to repair your file is the Blender. Once you import your file, you need to activate the 3D printing add-on. To do this, go to**Edit > Preferences > Add-ons** then search for 3D-Print Toolbox and then select the checkbox.

![Common Cura Errors](https://cdn.mos.cms.futurecdn.net/zdGDPHXTV7uFcB3oBQkvcm-320-80.png)

 (Image credit: Tom's Hardware)

**Click on the 3D-print option** near the options section and then select**Check All** to start analyzing the model.

![Common Cura Errors](https://cdn.mos.cms.futurecdn.net/d5fShifF7iXtHmjQySvefj-320-80.png)

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
 (Image credit: Tom's Hardware)

 After analyzing, you will see if there is any issue with your 3D model. In my case, I see one non-manifold edge and other problems, as shown in the results section below.

![Common Cura Errors](https://cdn.mos.cms.futurecdn.net/MPWRuoMMcXfyXdwzzAer4k-320-80.png)

 (Image credit: Tom's Hardware)

 To fix the issues, we shall go to the**Clean Up** section and click**Make Manifold** .

![Common Cura Errors](https://cdn.mos.cms.futurecdn.net/nF2ZDmvNGt5JwnuzsVaUfk-320-80.png)

 (Image credit: Tom's Hardware)

 The software will fill all the gaps, non-manifold edges, and inverted normals. Depending on the complexity of the model, it will take a while to finish. Once it is done and you check again, you will realize the issues have disappeared. You can then export the model and reload it to Cura to slice. Fixing this problem will also, in most cases, fix the other error of the 3D model not being watertight.

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
## 4\. Configuration Errors in Cura

 Configuration errors can result from factors like incorrect settings or issues with profiles. But the leading cause is material options. That is, when Cura fails to locate the material previously designated as the default for your specific 3D printer during the last session. This will make the software interpret this as a sign of configuration corruption.

 In most cases, this error is not serious, and you can ignore it and slice your file and 3D print successfully. However, it can be annoying when it pops up whenever you try to slice your file, hence the need to fix it.

 To solve this problem, you can reset Cura to factory settings. But if you have settings you don’t want to lose, you can use a Cura plugin like[Startup Optimiser](https://marketplace.ultimaker.com/app/cura/plugins/fieldofview/StartOptimiser) , which you can download from the Ultimaker marketplace.

![Common Cura Errors](https://cdn.mos.cms.futurecdn.net/B5BwpY7VvYWFbPCabgjdmk-320-80.png)

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 (Image credit: Tom's Hardware)

 After installation, restart Cura, and in the error message box, choose**Disable Affected Profiles** and then restart Cura again, and the message will disappear. This plugin can also help you reduce the amount of time that Cura loads when you choose**Disable loading unused configuration files** .

(Image credit: Tom's Hardware)

![Common Cura Errors](https://cdn.mos.cms.futurecdn.net/VYv5JwaZ9ztJUwsF8DCw5j-320-80.png)

 (Image credit: Tom's Hardware)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Cura Not Generating Supports

 If the support generation settings are correctly configured and Cura is still failing to generate them or only generating a few, you need to adjust certain settings to fix the issue. But before that, you need to ensure that you update the software to the latest version.

 One setting to adjust when Cura is not generating supports is changing the support placement setting to**Everywhere** instead of the default**Touching Build Plate.**

![Common Cura Errors](https://cdn.mos.cms.futurecdn.net/pVYrwxpqZqAjwKk4cBSoJk-320-80.png)

 (Image credit: Tom's Hardware)

 Doing this, in most cases, will solve the issue. If the supports appear even in the areas that you don’t want, you can use support blockers to block them in those areas. In addition, to support placement, you must check the**Minimum Support Area** and**Minimum Support Interface Area** settings. These settings determine the minimum surface area required for the supports to be generated and the minimum area for support interfaces. If the values are too high, the software may not generate supports for smaller overhangs. So you lower them a little to allow Cura to generate supports for smaller overhangs.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
## 6\. Cura Settings Error

 This error occurs when one inputs values for certain settings that exceed the software’s supported ranges. Just like many other[3D printer slicers](https://www.tomshardware.com/features/6-best-3d-printer-slicers-and-how-to-use-them) , Cura has predefined limits for settings parameters, and when one attempts to exceed those ranges, Cura will generate a message indicating the specific setting causing the problem. Such error messages allow you to adjust the settings to ensure they fall within the supported ranges and this helps prevent errors or print failure.

 To avoid such errors from occurring you should adhere to the limits of the software when adjusting the settings to avoid exceeding. Also, you should keep in mind that there are certain settings in Cura that are related, hence an increase or reduction in one affects the other and you should take note of that when adjusting your settings.

## More 3D Printer Tutorials

* [**How to Use PrusaSlicer: A Beginners Guide**](https://www.tomshardware.com/how-to/use-prusaslicer)
* [**5 Ways Fix Z Banding in 3D Printing**](https://www.tomshardware.com/how-to/fix-z-banding-in-3d-printing)
* [**How to Use FreeCAD for 3D Printing**](https://www.tomshardware.com/how-to/use-freecad-3d-printing)
* [**How to Convert OBJ Files to STL Files for 3D Printing**](https://www.tomshardware.com/how-to/convert-obj-files-to-stl)
* [**How to Clean and Cure Resin Prints**](https://www.tomshardware.com/how-to/clean-and-cure-resin-3d-prints)


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


