---
title: Steps to Rectify Problems Caused by Grinding of 3D Printing Material
date: 2024-08-23T12:58:38.506Z
updated: 2024-08-24T12:58:38.506Z
tags:
  - printer
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/ZdLwaxxEFSdAxaF3eBWR6Q-320-80.png
---

## Master the Art of Flawless 3D Printing: No More Blisters or Pimples

Blobs are excessive deposits of melted filament that appear as small and irregular protrusions on the print's surface. It occurs mainly when the extruder deposits more material than necessary at specific points due to factors like inconsistent extrusion, incorrect retraction settings, and or insufficient cooling. Zits, on the other hand, are tiny imperfections that look like scars on the surface of a 3D print, and they can also come as a result of inconsistent extrusion, changes in 3D print speed, and variations in cooling, even if you’re using one of the[best 3D printers](https://www.tomshardware.com/best-picks/best-3d-printers) . Zits are generally smaller than blobs, but they still compromise the overall look of the print and affect the print's surface finish. You can fix these issues by implementing the following strategies.

## 1\. Ensure There is Proper Cooling of the Layers

 If the layers are overheated due to poor cooling, the excess melted filament will form the blobs on the printed object. You need to optimize the cooling settings to be consistent on all the sections of your 3D print.

 It’s also advisable to increase the fan's speed to prevent overheating of the layers before the next ones are deposited, which leads to excess melted filament, which later forms blobs on the object.

## 2\. Optimize Retraction Settings

 Retraction plays an essential role in pulling the filament back slightly when the nozzle is not moving between different locations. This helps prevent oozing which can result in blobs and other issues like[stringing in 3D prints](https://www.tomshardware.com/3d-printing/how-to-fix-stringing-in-3d-prints) .

 When adjusting the retraction, you need to consider the retraction speed which determines how quickly the filament is retracted back and the retraction distance, which determines the amount of filament pulled back to the nozzle. When the retraction settings are inadequate, small bumps can occur because of the pressure variations on the extruder when the nozzle is not extruding, especially when moving on the empty spaces, leaving behind filament due to oozing. So you need to experiment and get the perfect retraction distance and speed to prevent unwanted material residuals from being deposited on the surface of the print.

 The standard retraction distance is usually around 2 to 7 mm, and the speed ranges from 30 to 60 mm/s. You can find these settings on your 3D printer slicer. For example, in Cura, you have to ensure that you check the**Enable** **Retraction** box.

![How to Avoid Blobs and Zits in 3D Prints](https://cdn.mos.cms.futurecdn.net/nainugXq6FRCAXonoEkKyA-320-80.png)

 (Image credit: Tom's Hardware)

 As you make the adjustments, you can also 3D print a[retraction test model](https://www.thingiverse.com/thing:909901) and use it to adjust the settings until you achieve the sweet spot.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
## Stay On the Cutting Edge: Get the Tom's Hardware Newsletter

 Get Tom's Hardware's best news and in-depth reviews, straight to your inbox.

 Contact me with news and offers from other Future brands  Receive email from us on behalf of our trusted partners or sponsors

 By submitting your information you agree to the[Terms & Conditions](https://futureplc.com/terms-conditions/) and[Privacy Policy](https://futureplc.com/privacy-policy/) and are aged 16 or over.

![How to Avoid Blobs and Zits in 3D Prints](https://cdn.mos.cms.futurecdn.net/bf3r7C9s6nZACJhsioefLA-320-80.png)

 (Image credit: Tom's Hardware)

 You can begin with a lower retraction distance, like 2mm, print the model, and then check how it appears. It might have strings and other imperfections, and you can continue increasing by 0.5mm until you see improvement. You can then shift to retraction speed and start with a lower value, like 30 mm/s, and increase it gradually as you observe how the prints appear until you find the optimal value.

## 3\. Use Coasting

 When you activate coasting settings, it stops the extruding filament slightly before the end of the path when the nozzle is about to travel over an area without printing. This is helpful as it minimizes the pressure build-up in the nozzle, which causes the filament to ooze out and turn into blobs or zits. You can find the coasting setting in the**Experimental** section, and check the**Enable coasting** box to activate it.

![How to Avoid Blobs and Zits in 3D Prints](https://cdn.mos.cms.futurecdn.net/WcERQDGybguB9i8aCqZ5jA-320-80.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 (Image credit: Tom's Hardware)

 When you enable it, other settings appear, like**Coasting Volume** ,**Minimum Volume Before Coasting** , and**Coasting Speed** .

![How to Avoid Blobs and Zits in 3D Prints](https://cdn.mos.cms.futurecdn.net/dddhLGSrhmwrGxEcJzAHYA-320-80.png)

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
 (Image credit: Tom's Hardware)

 Coasting volume is the amount or size of the material that is not extruded at the end of each layer. You need to find the appropriate value because if it’s too high, the printer might not extrude enough filament, resulting in under-extrusion.

 If it’s too low, there will be a build-up of pressure on the nozzle, so you need to tweak it until you get the correct value. The default value is around 0.064mm³. To get the correct value, multiply the nozzle width, layer height, and length at a certain height. For example, if the nozzle width is 0.4mm, layer height is 0.2mm, and an extrusion path is around 0.8, when you multiply them, you will get 0.064\. You can increase in small increments until you find the appropriate value.

**Minimum** **Volume Before Coasting** refers to the minimum material size that should be there for the slicer to apply coasting. The default value is around 0.8mm³, which works great for most prints.**Coasting speed** on the other hand is the speed at which the nozzle moves when it is coasting. It’s usually relative to the printing speed, and using a slightly lower value than 100%, like 90% is advisable.

 As you enable coasting to eliminate blobs and zits, you need to remember that its effectiveness depends on the geometry of your 3D model, 3D printing speed, and the type of filament you are using. So you need to tweak the settings until you achieve the best results.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Adjust 3D printing Speed and Temperature

 Adjusting how fast your 3D printer prints as well as the temperature you are using can also help fix the issue as these settings influence the extrusion rate and the cooling time for the layers. A higher 3D printing speed than necessary can result in increased pressure in the nozzle, which can cause the excess filament to ooze out, causing issues on the print as the nozzle moves.

 The standard speed is usually between 50-60 mm/s, and anything above this can result in problems. If the temperature is too high, the filament can become too fluid and start oozing out. Alternatively, if it is too low, there can be incomplete melting which results in uneven extrusion which causes irregularities and inconsistencies in the printed layers. You must adjust the temperature until you find the perfect settings for your filament and printer.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## 5\. Disable Power Recovery Feature

 If none of the above options don’t work, you should consider turning off the power recovery option if it’s turned on. Even though this feature helps save your 3D print instead of starting to print from scratch in case of power interruption, it can introduce blobs. This is because when the feature is activated, the 3D printers utilize the SD card to write “check-points” or the print job state to the card, which will help in resuming the print and this might start competing with the standard printing operation, resulting in blobs.

 Turning this feature on is not easy as not all the[best 3D printers](https://www.tomshardware.com/best-picks/best-3d-printers) have that option on the menu, and you need to use the SD card. Luckily, a YouTuber, Geek Detour, created[G-code files for enabling and disabling power recovery](https://geekdetour.com/3d-printing/blobs-in-your-3d-prints-power-loss-recovery-can-be-the-problem/) and you can download and save them to your SD card and use them. You can also choose to buy a UPS battery to address power challenges if you don’t want the challenge of your print being affected due to power loss.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-the-essential-guide-to-motion-blur-in-adobe-photoshop/"><u>[New] In 2024, The Essential Guide to Motion Blur in Adobe Photoshop</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-leading-audio-designers-for-iphone-ringtones/"><u>[New] Leading Audio Designers for iPhone Ringtones</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-navigating-the-professional-lands-cooked-by-audacity/"><u>[New] Navigating the Professional Lands Cooked by Audacity</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-step-by-step-enabling-screen-capture-on-macos/"><u>[New] Step-by-Step  Enabling Screen Capture on MacOS</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-mastering-background-replacement-on-instagrams-platform/"><u>[Updated] 2024 Approved  Mastering Background Replacement on Instagram's Platform</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-chromebook-pitch-and-timbre-control-guide-the-leading-online-speech-modifiers/"><u>[Updated] Chromebook Pitch and Timbre Control Guide  The Leading Online Speech Modifiers</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-a-practical-guide-to-saving-screens-on-dell-computers/"><u>[Updated] In 2024, A Practical Guide to Saving Screens on Dell Computers</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-sony-bdp-s6500-review/"><u>2024 Approved  Sony BDP-S6500 Review</u></a></li>
<li><a href="https://howto.techidaily.com/8-ultimate-fixes-for-google-play-your-zte-axon-40-lite-isnt-compatible-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Ultimate Fixes for Google Play Your ZTE Axon 40 Lite Isnt Compatible | Dr.fone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/tics-unlocked-your-step-by-step-youtube-guide/"><u>Analytics Unlocked  Your Step-by-Step YouTube Guide</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723862735104-buying-a-new-laptop-choose-from-the-latest-snapdragon-elite-x-series-with-integrated-microsoft-copilot-now-available/"><u>Buying a New Laptop? Choose From the Latest Snapdragon Elite X Series with Integrated Microsoft Copilot Now Available!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/computex-2024-unveiled-asus-rog-ally-and-qualcomm-powered-laptops-featured-absence-of-latest-gpus-noted/"><u>Computex 2024 Unveiled: Asus ROG Ally & Qualcomm-Powered Laptops Featured, Absence of Latest GPUs Noted</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discover-the-best-high-end-notebooks-and-top-tier-laptops-for-tech-savvy-users-in-202/"><u>Discover the Best High-End Notebooks and Top-Tier Laptops for Tech Savvy Users in 202</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/dive-deep-into-the-world-of-high-performance-laptops-with-our-review-of-the-asus-zenbook-s1-6-where-we-thoroughly-examine-and-test-its-capabilities-when-pow29/"><u>Dive Deep Into the World of High-Performance Laptops with Our Review of the Asus Zenbook S1 6, Where We Thoroughly Examine and Test Its Capabilities when Powered by the Advanced AMD Ryzen AI 9 HX 370 CPU</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/embracing-the-future-of-computing-new-frameworks-laptop-board-compatible-with-risc-v-architecture-teamed-up-with-deepcomputing-for-revolutionary-starfive-so7/"><u>Embracing the Future of Computing: New Framework's Laptop Board Compatible with RISC-V Architecture, Teamed Up with DeepComputing for Revolutionary StarFive SoC</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/experience-supreme-gaming-performance-msi-katana-156-inch-laptop-powered-by-nvidia-geforce-rtx-4070-for-just-1199/"><u>Experience Supreme Gaming Performance: MSI Katana 15.ˈ6 Inch Laptop - Powered by NVIDIA GeForce RTX 4070 for Just $1,199</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-analysis-of-hardware-by-tom-your-go-to-resource/"><u>Expert Analysis of Hardware by Tom - Your Go-To Resource</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-analysis-on-cutting-edge-tech-hardware-by-tom/"><u>Expert Analysis on Cutting-Edge Tech Hardware by Tom</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-advanced-computing-with-toms-hardware-expertise/"><u>Exploring Advanced Computing with Tom's Hardware Expertise</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-hardware-with-tom-your-essential-guide-to-pc-gear/"><u>Exploring Hardware with Tom: Your Essential Guide to PC Gear</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-tech-with-tom-comprehensive-hardware-insights/"><u>Exploring Tech with Tom: Comprehensive Hardware Insights</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-technology-with-toms-hardware-reviews/"><u>Exploring Technology with Tom’s Hardware Reviews</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/high-end-spec-showdown-unveiling-the-true-potential-of-the-asus-rog-zephyrus-g16-for-gamers/"><u>High-End Spec Showdown: Unveiling the True Potential of the Asus ROG Zephyrus G16 for Gamers</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-use-special-features-virtual-location-on-tecno-camon-20-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Tecno Camon 20? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-expertly-enhance-videos-with-top-10plus-mobile-and-desktop-editors/"><u>In 2024, Expertly Enhance Videos with Top 10+ Mobile & Desktop Editors</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/inside-computex-2024s-early-leaks-asus-rog-ally-and-snapdragon-x-laptops-announced-no-mention-of-upcoming-gpu-innovations/"><u>Inside Computex 2024'S Early Leaks: Asus ROG Ally & Snapdragon X Laptops Announced, No Mention of Upcoming GPU Innovations</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/inside-out-on-equipment-discover-toms-hardware-wisdom/"><u>Inside Out on Equipment: Discover Tom's Hardware Wisdom</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-technology-choices-through-toms-hardware-wisdom/"><u>Mastering Technology Choices Through Tom's Hardware Wisdom</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-technology-trends-at-toms-hardware-haven/"><u>Mastering Technology Trends at Tom's Hardware Haven</u></a></li>
<li><a href="https://facebook.techidaily.com/maximizing-daily-rest-with-facebooks-alert-system/"><u>Maximizing Daily Rest with Facebook's Alert System</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-the-benefits-of-using-video-for-social-media-marketing/"><u>New 2024 Approved The Benefits Of Using Video For Social Media Marketing</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/izing-channel-branding-to-skyrocket-subscriber-numbers-for-2024/"><u>Optimizing Channel Branding to Skyrocket Subscriber Numbers for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/transform-your-gaming-with-acers-incredible-offer-nitro-16-laptop-packing-rtx-4070-and-amd-cpu-for-a-steal-at-1129/"><u>Transform Your Gaming with Acer’s Incredible Offer: Nitro 16 Laptop Packing RTX 4070 & AMD CPU for a Steal at $1,129</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ultimate-guide-to-budget-friendly-premium-gaming-laptops-under-1500/"><u>Ultimate Guide to Budget-Friendly Premium Gaming Laptops Under 1500$</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unbeatable-deal-alert-asus-rog-zephyrus-g14-laptop-featuring-rtx-graphics-now-just-1099-at-best-buy/"><u>Unbeatable Deal Alert: Asus ROG Zephyrus G14 Laptop Featuring RTX Graphics Now Just $1099 at Best Buy</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unleash-unmatched-speed-and-lower-energy-consumption-with-lenovos-game-changing-thinkpad-p1-gen-e-the-first-to-incorporate-advanced-lpcmam2-ram-technology.m20/"><u>Unleash Unmatched Speed and Lower Energy Consumption with Lenovo's Game-Changing ThinkPad P1 Gen E – The First to Incorporate Advanced Lpcmam2 RAM Technology</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unlock-the-secrets-of-advanced-gadgets-at-toms-computer-review/"><u>Unlock the Secrets of Advanced Gadgets at Tom’s Computer Review</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-top-tier-electronics-insider-reviews-by-toms-hardware-professionals/"><u>Unveiling Top-Tier Electronics: Insider Reviews by Tom's Hardware Professionals</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/upcoming-reveal-next-generation-dell-xps-and-snapdragon-x-inspiron-series-a-glimpse-through-image-leaks/"><u>Upcoming Reveal: Next-Generation Dell XPS & Snapdragon X Inspiron Series - A Glimpse Through Image Leaks</u></a></li>
</ul></div>
