---
title: Exploring the Latest in Hardware with Tom's Gadget Analysis
date: 2024-08-19T03:10:28.191Z
updated: 2024-08-20T03:10:28.191Z
tags:
  - printer
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/J9jY2r2xZUN3yMQfvHKuE7-320-80.jpg
---

## Expert Hardware Analysis by Tom – Dive Into Gear Details

Create and 3D print QR codes easily. You can convert it into a 3D model and 3D print it. You can create physical objects embedded with the QR code, like keychains, business card holders, Wi-Fi passwords, and even embed them on photo frames, which when scanned, redirect to a personal video. The ideas are endless.

 3D-printed QR codes can withstand environmental factors that might damage traditional printed codes, which makes them helpful even for outdoor use. All you need is a reliable FDM 3D printer. Check out our[best 3D printers](https://www.tomshardware.com/best-picks/best-3d-printers) for recommendations if you don't already own one. We will take you through the process of generating the QR code, embedding it into a 3D model, and preparing it for 3D printing. You will also show you how to convert a QR code in 2D image into a 3D model.

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
### Generating the QR Code

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Generating the QR Code

 You can use various tools to generate the QR codes; we will use the[qrcode2stl](https://printer.tools/qrcode2stl/) in this article. After clicking the link, you can follow the steps below:

 1.**Select the QR code options** : text/URL, Wifi, E-mail, Contact, or SMS. For our case, we shall choose Text/URL and then**enter the website URL** .

 LATEST VIDEOS FROM tomshardware Tom's Hardware

![3D Print QR codes](https://cdn.mos.cms.futurecdn.net/pzBPMURGEscHThkFEEGZKn-320-80.png)

 (Image credit: Tom's Hardware)

 2.**Choose error correction** . When the value is higher, the QR code will be denser. In our case, we shall retain the medium value of 15%.

 3.**Specify 3D model settings** , that is, base options like the shape, width, corner radius, and border settings. You can also add custom text and attach a hole to the side of the tag, which you can attach to your keychain by selecting the**Keychain** box. Specify the QR Code settings like the depth, margin, block size, and Icon.

 4\. After applying the settings,**click** **Generate 3D Model,** and it will display in the right section, as shown below.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Stay On the Cutting Edge: Get the Tom's Hardware Newsletter

 Get Tom's Hardware's best news and in-depth reviews, straight to your inbox.

 Contact me with news and offers from other Future brands  Receive email from us on behalf of our trusted partners or sponsors

 By submitting your information you agree to the[Terms & Conditions](https://futureplc.com/terms-conditions/) and[Privacy Policy](https://futureplc.com/privacy-policy/) and are aged 16 or over.

![3D Print QR codes](https://cdn.mos.cms.futurecdn.net/GQXvo8YhLiEferVjx44gmi-320-80.png)

 (Image credit: Tom's Hardware)

 The QR code below was generated after adding a custom text, icon and selecting the**Keychain** box.

![3D Print QR codes](https://cdn.mos.cms.futurecdn.net/khwqMMpGmzs5M6nAkDZ9zj-320-80.png)

 (Image credit: Tom's Hardware)

 6.**Download the STL file** by clicking**Save as STL** .

 7.**Import the STL file** to a[3D printer slicer](https://www.tomshardware.com/features/6-best-3d-printer-slicers-and-how-to-use-them) of your choice.

 If you are using a single-extruder 3D printer and you don’t want the process of painting the file after 3D printing, you will need to change the filament during the 3D printing process. To do this:

 1.**Locate the layer** when the color changes as you preview the slicing. In my case, it will be at layer 9.

![3D Print QR codes](https://cdn.mos.cms.futurecdn.net/tsJQZmm39QiQPGfsVLCW7i-320-80.png)

 (Image credit: Tom's Hardware)

 2.**Install the Modify G-Code extension** in Cura. You can find it on Extensions > Post Processing.

 3\. After installing, go to**Extensions > Post Processing** \>**Modify G-Code** and then proceed by clicking**Add a script** .

![3D Print QR codes](https://cdn.mos.cms.futurecdn.net/WQQs2srSXt5ysMNTsJ7u5k-320-80.png)

 (Image credit: Tom's Hardware)

 4.**Select Filament Change** , and in the**Layer** section, set the**Layer** value from step 1\. Mine was 15.

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![3D Print QR codes](https://cdn.mos.cms.futurecdn.net/8orVU3p927KeesoLinZFxi-320-80.png)

 (Image credit: Tom's Hardware)

 5.**Re-slice the design** and send the G-code to your 3D printer.

 The 3D printer will pause when it reaches the layer that you have specified and it will move to the origin of the print bed so that you can swap the filament. In case you don’t have white and black filaments and you have a single extruder 3D printer, you can 3D print as it is.

![3D Print QR codes](https://cdn.mos.cms.futurecdn.net/4xcS97zTMB8PBdc5dabbs3-320-80.png)

 (Image credit: Tom's Hardware)

 The next step will be to paint the QR code part to distinguish it from the rest of the sections so the camera can pick up the code. You can use a small brush or a black marker pen and must ensure that you do it precisely to avoid distorting the QR code.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
![3D Print QR codes](https://cdn.mos.cms.futurecdn.net/Ar6Lh5iKZtLVqcNy5c2cxA-320-80.png)

 (Image credit: Tom's Hardware)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
### Multi-Color 3D Printing QR Codes

## Multi-Color 3D Printing QR Codes

 If you own a dual-extruder 3D printer, you can customize the colors in your QR code in the slicer before sending it for 3D printing. Follow the steps below to prepare the file for multi-color 3D printing[using Orca slicer](https://www.tomshardware.com/3d-printing/how-to-use-orca-slicer) .

 1.**Import the file to Orca slicer** by holding and dragging it to the workspace or**click** **Create new project** , then go to where you have stored your file and import it.

 2.**Change the color** of the STL file to white.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
![3D Print QR codes](https://cdn.mos.cms.futurecdn.net/m4MEJHFS56AzRS7daHbRDk-320-80.png)

 (Image credit: Tom's Hardware)

 2.**Click on the file** , then go to**Color Painting** .

![3D Print QR codes](https://cdn.mos.cms.futurecdn.net/7uAmWAo35AkGqy3NPuToqk-320-80.png)

 (Image credit: Tom's Hardware)

 3.**Select the height range** option and**put the depth value** you specified earlier when creating the QR code. For my case, I used the website's default value, which was 1\. Apply on it then change the color of the second filament to black and you will see a design similar to the one shown below

![3D Print QR codes](https://cdn.mos.cms.futurecdn.net/avQmDx4B66DFdFkYmo2Vbm-320-80.png)

 (Image credit: Tom's Hardware)

 4.**Slice and send it** to your 3D printer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Converting 2D QR Code to 3D

## Converting 2D QR Code to 3D

 If you have a 2D QR code that you would like to turn into a 3D model, you can follow the steps below.

 1\. Let’s**generate a 2D QR code** to use as a sample using[QR Code Generator](https://www.the-qrcode-generator.com/) .

![3D Print QR codes](https://cdn.mos.cms.futurecdn.net/oaCVbuYxMEMuW3Chrwtaei-320-80.png)

 (Image credit: Tom's Hardware)

 When you click Download, you will see an option to download it either in PNG or SVG. We are going to choose SVG.

 2.**Import the SVG file to TinkerCAD** . You can also specify the dimensions then**click Import** .

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![3D Print QR codes](https://cdn.mos.cms.futurecdn.net/UKm5mC5ZTXUzCtE7Wdg2in-320-80.png)

 (Image credit: Tom's Hardware)

TinkerCAD will automatically convert the SVG file into a 3D model.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![3D Print QR codes](https://cdn.mos.cms.futurecdn.net/pP45uzzcJyxsusznxMoXjk-320-80.png)

 (Image credit: Tom's Hardware)

 Add the base frame using a cube and then download and import it to your 3D slicer. Besides TinkerCAD, there are many other tools that you can use to convert 2D images to 3D models, such as Blender, Alpha3d, Embossify, and many others.

### Creating a QR Code in a 3D Modeling Software

## Creating a QR Code in a 3D Modeling Software

 The software we will use is TinkerCAD as it has the QR code option. Follow the steps:

 1. **Launch TinkerCAD** and**click** **Create** then**3D design** to create a new project.

 2.**Locate the QR code generator** in the**Shape Generators** section, then place it in the workspace by dragging and dropping it.

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
![3D Print QR codes](https://cdn.mos.cms.futurecdn.net/VAPfJUVZLoEKBCZeCMynKm-320-80.png)

 (Image credit: Tom's Hardware)

 3.**Add the link** in the**Text** section, and you will see the shape changing.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
![3D Print QR codes](https://cdn.mos.cms.futurecdn.net/EEhTyZVBqZeomGuhBZk9tj-320-80.png)

 (Image credit: Tom's Hardware)

 4.**Add a shape below the QR code** to act as the base. You can do this by going to the basic shapes section, then selecting the box option and dragging it to the workspace. You can then resize it so the QR code is well visible.

![3D Print QR codes](https://cdn.mos.cms.futurecdn.net/DjV5CrEgw5oHYE2JKxYCVj-320-80.png)

 (Image credit: Tom's Hardware)

Use the align tool to center them correctly.

 5.**Customize it** further by adding the text using the text shape and then resize it.

![3D Print QR codes](https://cdn.mos.cms.futurecdn.net/4TRtXNAERPZnk4v6JmMvCn-320-80.png)

 (Image credit: Tom's Hardware)

 6\. You can**add a logo to the design** by going to**Import** section and then go to where you have stored it. Ensure that the logo is in SVG format.

<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![3D Print QR codes](https://cdn.mos.cms.futurecdn.net/h9D8NLWXHXtrwBDYzPSNVn-320-80.png)

 (Image credit: Tom's Hardware)

 7.**Export the file in STL format** and**slice it** . For multi-color 3D printing, you can follow the steps we highlighted above. If you don’t have a dual-extruder 3D printer, you will paint it after 3D printing, most preferably with a white filament. I imported mine to Cura, scaled it before 3D printing, and after painting, I got the design below.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![3D Print QR codes](https://cdn.mos.cms.futurecdn.net/ac3tji2P9xEhMN86TuR7W8-320-80.png)

 (Image credit: Tom's Hardware)

### Customizing QR Codes

## Customizing QR Codes

 You can find QR codes online to customize and add the necessary details before 3D printing. An example is the[Makerworld QR code generator](https://makerworld.com/en/models/476280#profileId-387583) , which is meant to be 3D printed in Bambu 3D printers, but you can also download and 3D print. To use this option:

 1\. Once you visit Makerworld website using the link above, it will launch the QR code generator, and you will need to**sign up to the platform** to start customizing.

 2\. After signing up,**Click the** **Customize** button on the bottom-right section.

![3D Print QR codes](https://cdn.mos.cms.futurecdn.net/JKmnGvfsmz3S4VBfazKbYi-320-80.png)

 (Image credit: Tom's Hardware)

 2\. In the new window that launches,**choose the** **QR code type** you want to create. That is, whether Text, Wi-Fi, phone call, or vCard.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
![3D Print QR codes](https://cdn.mos.cms.futurecdn.net/NMs7mhj65SBzCiTWTo9xim-320-80.png)

 (Image credit: Tom's Hardware)

 3.**Click Generate** to modify the QR code.

 4\. You can also**adjust the dimensions** and appearance of the QR code, add other options like a keyring hole or a label, and then**click** **Generate** .

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
![3D Print QR codes](https://cdn.mos.cms.futurecdn.net/4xcS97zTMB8PBdc5dabbs3-320-80.png)

 (Image credit: Tom's Hardware)

 5.**Download the file** by**clicking** **Download** , then import it to your slicing program, and follow the steps we discussed above for dual-extruder 3D printers and swapping filament for the 3D printers that don’t support multi-color 3D printing.

 After 3D printing your QR code, it’s also important to 3D print a stand if it will be placed on a flat surface like a table.

![3D Print QR codes](https://cdn.mos.cms.futurecdn.net/hKShdgwdFsmchSy8PeuaA6-320-80.png)

 (Image credit: Tom's Hardware)

 The[Ultimate QR Code Stand](https://makerworld.com/en/models/481160#profileId-392872) in Makerworld is a great option.

**MORE:** [**Best 3D Printers**](https://www.tomshardware.com/best-picks/best-3d-printers)

**MORE:** [**Best Budget 3D Printers**](https://www.tomshardware.com/best-picks/best-budget-3d-printers)

**MORE:** [**Best Resin 3D Printers**](https://www.tomshardware.com/best-picks/best-resin-3d-printers)


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


