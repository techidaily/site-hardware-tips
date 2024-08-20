---
title: Expert Tips for Flawless Printouts and Zero Weaknesses in 3D Fabrication
date: 2024-08-19T03:17:32.367Z
updated: 2024-08-20T03:17:32.367Z
tags:
  - printer
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/xD3YkfhmCz6nSQvsp8WTeC-320-80.png
---

## Elevate Your 3D Prints - Say Goodbye to Blobs and Zits Forever

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

## Stay On the Cutting Edge: Get the Tom's Hardware Newsletter

 Get Tom's Hardware's best news and in-depth reviews, straight to your inbox.

 Contact me with news and offers from other Future brands  Receive email from us on behalf of our trusted partners or sponsors

 By submitting your information you agree to the[Terms & Conditions](https://futureplc.com/terms-conditions/) and[Privacy Policy](https://futureplc.com/privacy-policy/) and are aged 16 or over.

![How to Avoid Blobs and Zits in 3D Prints](https://cdn.mos.cms.futurecdn.net/bf3r7C9s6nZACJhsioefLA-320-80.png)

 (Image credit: Tom's Hardware)

 You can begin with a lower retraction distance, like 2mm, print the model, and then check how it appears. It might have strings and other imperfections, and you can continue increasing by 0.5mm until you see improvement. You can then shift to retraction speed and start with a lower value, like 30 mm/s, and increase it gradually as you observe how the prints appear until you find the optimal value.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## 3\. Use Coasting

 When you activate coasting settings, it stops the extruding filament slightly before the end of the path when the nozzle is about to travel over an area without printing. This is helpful as it minimizes the pressure build-up in the nozzle, which causes the filament to ooze out and turn into blobs or zits. You can find the coasting setting in the**Experimental** section, and check the**Enable coasting** box to activate it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
![How to Avoid Blobs and Zits in 3D Prints](https://cdn.mos.cms.futurecdn.net/WcERQDGybguB9i8aCqZ5jA-320-80.png)

 (Image credit: Tom's Hardware)

 When you enable it, other settings appear, like**Coasting Volume** ,**Minimum Volume Before Coasting** , and**Coasting Speed** .

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![How to Avoid Blobs and Zits in 3D Prints](https://cdn.mos.cms.futurecdn.net/dddhLGSrhmwrGxEcJzAHYA-320-80.png)

 (Image credit: Tom's Hardware)

 Coasting volume is the amount or size of the material that is not extruded at the end of each layer. You need to find the appropriate value because if it’s too high, the printer might not extrude enough filament, resulting in under-extrusion.

 If it’s too low, there will be a build-up of pressure on the nozzle, so you need to tweak it until you get the correct value. The default value is around 0.064mm³. To get the correct value, multiply the nozzle width, layer height, and length at a certain height. For example, if the nozzle width is 0.4mm, layer height is 0.2mm, and an extrusion path is around 0.8, when you multiply them, you will get 0.064\. You can increase in small increments until you find the appropriate value.

**Minimum** **Volume Before Coasting** refers to the minimum material size that should be there for the slicer to apply coasting. The default value is around 0.8mm³, which works great for most prints.**Coasting speed** on the other hand is the speed at which the nozzle moves when it is coasting. It’s usually relative to the printing speed, and using a slightly lower value than 100%, like 90% is advisable.

 As you enable coasting to eliminate blobs and zits, you need to remember that its effectiveness depends on the geometry of your 3D model, 3D printing speed, and the type of filament you are using. So you need to tweak the settings until you achieve the best results.

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Adjust 3D printing Speed and Temperature

 Adjusting how fast your 3D printer prints as well as the temperature you are using can also help fix the issue as these settings influence the extrusion rate and the cooling time for the layers. A higher 3D printing speed than necessary can result in increased pressure in the nozzle, which can cause the excess filament to ooze out, causing issues on the print as the nozzle moves.

 The standard speed is usually between 50-60 mm/s, and anything above this can result in problems. If the temperature is too high, the filament can become too fluid and start oozing out. Alternatively, if it is too low, there can be incomplete melting which results in uneven extrusion which causes irregularities and inconsistencies in the printed layers. You must adjust the temperature until you find the perfect settings for your filament and printer.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
## 5\. Disable Power Recovery Feature

 If none of the above options don’t work, you should consider turning off the power recovery option if it’s turned on. Even though this feature helps save your 3D print instead of starting to print from scratch in case of power interruption, it can introduce blobs. This is because when the feature is activated, the 3D printers utilize the SD card to write “check-points” or the print job state to the card, which will help in resuming the print and this might start competing with the standard printing operation, resulting in blobs.

 Turning this feature on is not easy as not all the[best 3D printers](https://www.tomshardware.com/best-picks/best-3d-printers) have that option on the menu, and you need to use the SD card. Luckily, a YouTuber, Geek Detour, created[G-code files for enabling and disabling power recovery](https://geekdetour.com/3d-printing/blobs-in-your-3d-prints-power-loss-recovery-can-be-the-problem/) and you can download and save them to your SD card and use them. You can also choose to buy a UPS battery to address power challenges if you don’t want the challenge of your print being affected due to power loss.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
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
<li><a href="https://instagram-video-files.techidaily.com/new-a-guide-to-the-finest-apps-for-instagram-reel-creation/"><u>[New] A Guide to the Finest Apps for Instagram Reel Creation</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-mastering-the-art-of-combining-igtv-with-insta-stories/"><u>[New] In 2024, Mastering the Art of Combining IGTV with Insta Stories</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-secrets-to-dynamic-and-effective-igtv-covers/"><u>[New] In 2024, Secrets to Dynamic & Effective IGTV Covers</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-social-media-mirrors-the-science-of-true-ig-selfies/"><u>[New] Social Media Mirrors  The Science of True IG Selfies</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-breakdown-of-how-youtube-ad-revenue-works-cpm/"><u>[Updated] 2024 Approved  Breakdown of How YouTube Ad Revenue Works (CPM)</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-enhance-video-production-7-best-free-sounds-for-editors/"><u>[Updated] 2024 Approved  Enhance Video Production - 7 Best Free Sounds for Editors</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-journey-through-your-watch-history-find-latest-views-on-fb/"><u>[Updated] 2024 Approved  Journey Through Your Watch History  Find Latest Views on FB</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-aurora-hdr-reviews-is-aurora-hdr-a-good-choice/"><u>[Updated] Aurora HDR Reviews  Is Aurora HDR a Good Choice ?</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-evaluating-earnings-from-one-million-youtube-watches-for-2024/"><u>[Updated] Evaluating Earnings From One Million YouTube Watches for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-free-meme-makers-the-ultimate-resource-guide/"><u>[Updated] Free Meme Makers – The Ultimate Resource Guide</u></a></li>
<li><a href="https://location-fake.techidaily.com/11-best-location-changers-for-oneplus-12r-drfone-by-drfone-virtual-android/"><u>11 Best Location Changers for OnePlus 12R | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-motorola-razr-40-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from Motorola Razr 40 to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-infinix-hot-30-5g-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On Infinix Hot 30 5G | Dr.fone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723125146721-avoid-these-6-common-pitfalls-in-using-cura-expert-fixes-revealed/"><u>Avoid These 6 Common Pitfalls in Using Cura: Expert Fixes Revealed</u></a></li>
<li><a href="https://fox-info.techidaily.com/bargain-ballbusters-learn-free-football-broadcast-techniques/"><u>Bargain Ballbusters  Learn Free Football Broadcast Techniques</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/crafting-true-to-life-wood-objects-using-a-novel-3d-printing-approach-and-sawdust-ink-material/"><u>Crafting True-to-Life Wood Objects Using a Novel 3D Printing Approach and Sawdust Ink Material</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723175706142-deepcools-latest-innovations-next-gen-coolers-psus-and-more-now-featuring-customizable-pixel-silicone-design-accents/"><u>DeepCool's Latest Innovations: Next-Gen Coolers, PSUs & More - Now Featuring Customizable Pixel Silicone Design Accents!</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/easy-guide-to-xiaomi-redmi-13c-5g-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Xiaomi Redmi 13C 5G FRP Bypass With Best Methods</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723125257451-elevate-your-raspberry-pi-projects-with-the-premier-selection-of-2024s-top-hat-devices/"><u>Elevate Your Raspberry Pi Projects with the Premier Selection of 2024'S Top HAT Devices!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723125150766-get-ready-for-the-k1c-creality-shares-exciting-launch-date-price-tag-and-full-technical-specifications/"><u>Get Ready for the K1C: Creality Shares Exciting Launch Date, Price Tag & Full Technical Specifications</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changefake-your-vivo-y56-5g-location-on-viber-drfone-by-drfone-virtual-android/"><u>How to Change/Fake Your Vivo Y56 5G Location on Viber | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-icloud-lock-on-your-apple-iphone-14-and-ipad-by-drfone-ios/"><u>How to fix iCloud lock on your Apple iPhone 14 and iPad</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-phone-number-from-your-apple-id-on-your-apple-iphone-12-pro-max-by-drfone-ios/"><u>How To Remove Phone Number From Your Apple ID on Your Apple iPhone 12 Pro Max?</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfer-from-apple-iphone-xr-to-samsung-galaxy-s20-drfone-by-drfone-transfer-from-ios/"><u>How to Transfer from Apple iPhone XR to Samsung Galaxy S20? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-htc-u23-pro-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Transfer Music from HTC U23 Pro to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-best-android-videography-6-must-try-music-videos-apps/"><u>In 2024, Best Android Videography  6 Must-Try Music Videos Apps</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-premier-annual-update-best-free-livestream-software-and-apps-review/"><u>In 2024, Premier Annual Update  Best Free Livestream Software & Apps Review</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-reasons-why-pokemon-gps-does-not-work-on-samsung-galaxy-a23-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Reasons why Pokémon GPS does not Work On Samsung Galaxy A23 5G? | Dr.fone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/in-depth-gadget-exploration-with-toms-hardware-guidance/"><u>In-Depth Gadget Exploration with Tom's Hardware Guidance</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/innovative-tips-on-designing-and-3d-printing-secure-qr-codes-at-home/"><u>Innovative Tips on Designing and 3D Printing Secure QR Codes at Home</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/inside-the-world-of-toms-tech-gadgets-and-innovations/"><u>Inside the World of Tom's Tech Gadgets and Innovations</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/master-your-pc-upgrades-with-insight-from-toms-technology-zone/"><u>Master Your PC Upgrades with Insight From Tom's Technology Zone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/master-your-tech-top-pickings-from-toms-circuitry-chronicles/"><u>Master Your Tech: Top Pickings From Tom's Circuitry Chronicles</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-the-latest-in-computer-hardware-with-toms-reviews/"><u>Mastering the Latest in Computer Hardware with Tom's Reviews</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-high-tech-purchases-trustworthy-advice-from-toms-hardware-experts/"><u>Navigating High-Tech Purchases: Trustworthy Advice From Tom's Hardware Experts</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-modern-gadgets-with-guidance-from-toms-hardware/"><u>Navigating Modern Gadgets with Guidance From Tom's Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-the-world-of-electronics-with-toms-hardware/"><u>Navigating the World of Electronics with Tom's Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-the-world-of-gadgets-tips-from-toms-hardware-experts/"><u>Navigating the World of Gadgets – Tips From Tom's Hardware Experts</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/pioneering-pc-advice-by-tom-the-ultimate-guide-to-hardware/"><u>Pioneering PC Advice by Tom - The Ultimate Guide to Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/revolutionary-ek-custom-heat-sinks-optimal-cooling-for-delidded-amd-ryzen-am5-processors/"><u>Revolutionary EK Custom Heat Sinks: Optimal Cooling for Delidded AMD Ryzen AM5 Processors</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/streamline-gpu-cooling-with-cooler-masters-compact-2-fan-replacement-over-traditional-triple-fans/"><u>Streamline GPU Cooling with Cooler Master's Compact 2-Fan Replacement Over Traditional Triple Fans</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/tackling-thick-footprint-troubles-a-how-to-on-3d-print-perfection/"><u>Tackling Thick Footprint Troubles: A How-To on 3D Print Perfection</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/teamgroup-unveils-the-future-of-pc-maintenance-with-magnetic-features-on-their-iconic-t-force-siren-aio-cpu-coolers/"><u>TeamGroup Unveils the Future of PC Maintenance with Magnetic Features on Their Iconic T-Force Siren AIO CPU Coolers</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-comprehensive-guide-to-electronics-toms-insights/"><u>The Comprehensive Guide to Electronics - Tom's Insights</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-list-of-5-benefits-that-make-buying-a-veil-printer-irresistible-this-black-friday/"><u>The Ultimate List of 5 Benefits That Make Buying a Veil Printer Irresistible This Black Friday</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-precision-tools-for-computers-and-hardware-enthusiasts/"><u>Tom's Precision Tools for Computers and Hardware Enthusiasts</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-rated-sweeping-game-displays-of-2024/"><u>Top Rated Sweeping Game Displays of 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-missing-coredll-errors-on-your-computer-a-step-by-step-tutorial/"><u>Troubleshooting Missing Core.dll Errors on Your Computer - A Step-by-Step Tutorial</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/under-65-cooling-mastery-comparative-review-of-thermalrights-frozen-notte-and-the-aqua-elite-e360-v3/"><u>Under $65 Cooling Mastery: Comparative Review of Thermalright's Frozen Notte and the Aqua Elite E360 V3</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/understanding-and-applying-youtube-markup-for-2024/"><u>Understanding & Applying YouTube Markup for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-latest-gadgets-and-pcs-the-toms-analysis/"><u>Unveiling the Latest Gadgets and PCs: The Tom's Analysis</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-latest-in-computing-toms-hardware-guide/"><u>Unveiling the Latest in Computing: Tom's Hardware Guide</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-latest-tech-in-depth-hardware-reviews-from-toms-hardware/"><u>Unveiling the Latest Tech: In-Depth Hardware Reviews From Tom's Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-toms-guide-expert-insights-into-modern-electronics/"><u>Unveiling Tom's Guide: Expert Insights Into Modern Electronics</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/vogue-videos-compiling-free-youtube-channel-frames-for-2024/"><u>Vogue Videos  Compiling FREE YouTube Channel Frames for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/your-journey-to-becoming-a-pro-at-gifs/"><u>Your Journey to Becoming a Pro at GIFs</u></a></li>
</ul></div>
