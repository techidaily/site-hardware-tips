---
title: Master the Art of Keeping a Clean Nozzle on Your 3D Printing Device
date: 2025-01-08T18:59:02.299Z
updated: 2025-01-12T21:47:54.130Z
tags:
  - printer
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/5txdWHFbi8WFhpfyaNzHDK-320-80.png
---

## Master the Art of Flawless 3D Printing: No More Blisters or Pimples

Blobs are excessive deposits of melted filament that appear as small and irregular protrusions on the print's surface. It occurs mainly when the extruder deposits more material than necessary at specific points due to factors like inconsistent extrusion, incorrect retraction settings, and or insufficient cooling. Zits, on the other hand, are tiny imperfections that look like scars on the surface of a 3D print, and they can also come as a result of inconsistent extrusion, changes in 3D print speed, and variations in cooling, even if you’re using one of the[best 3D printers](https://www.tomshardware.com/best-picks/best-3d-printers) . Zits are generally smaller than blobs, but they still compromise the overall look of the print and affect the print's surface finish. You can fix these issues by implementing the following strategies.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=lhdUUVYMVQjzHXBh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Ensure There is Proper Cooling of the Layers

 If the layers are overheated due to poor cooling, the excess melted filament will form the blobs on the printed object. You need to optimize the cooling settings to be consistent on all the sections of your 3D print.

 It’s also advisable to increase the fan's speed to prevent overheating of the layers before the next ones are deposited, which leads to excess melted filament, which later forms blobs on the object.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Optimize Retraction Settings

 Retraction plays an essential role in pulling the filament back slightly when the nozzle is not moving between different locations. This helps prevent oozing which can result in blobs and other issues like[stringing in 3D prints](https://www.tomshardware.com/3d-printing/how-to-fix-stringing-in-3d-prints) .

 When adjusting the retraction, you need to consider the retraction speed which determines how quickly the filament is retracted back and the retraction distance, which determines the amount of filament pulled back to the nozzle. When the retraction settings are inadequate, small bumps can occur because of the pressure variations on the extruder when the nozzle is not extruding, especially when moving on the empty spaces, leaving behind filament due to oozing. So you need to experiment and get the perfect retraction distance and speed to prevent unwanted material residuals from being deposited on the surface of the print.

 The standard retraction distance is usually around 2 to 7 mm, and the speed ranges from 30 to 60 mm/s. You can find these settings on your 3D printer slicer. For example, in Cura, you have to ensure that you check the**Enable** **Retraction** box.

![How to Avoid Blobs and Zits in 3D Prints](https://cdn.mos.cms.futurecdn.net/nainugXq6FRCAXonoEkKyA-320-80.png)

 (Image credit: Tom's Hardware)

 As you make the adjustments, you can also 3D print a[retraction test model](https://www.thingiverse.com/thing:909901) and use it to adjust the settings until you achieve the sweet spot.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 (Image credit: Tom's Hardware)

 When you enable it, other settings appear, like**Coasting Volume** ,**Minimum Volume Before Coasting** , and**Coasting Speed** .

![How to Avoid Blobs and Zits in 3D Prints](https://cdn.mos.cms.futurecdn.net/dddhLGSrhmwrGxEcJzAHYA-320-80.png)

 (Image credit: Tom's Hardware)

 Coasting volume is the amount or size of the material that is not extruded at the end of each layer. You need to find the appropriate value because if it’s too high, the printer might not extrude enough filament, resulting in under-extrusion.

 If it’s too low, there will be a build-up of pressure on the nozzle, so you need to tweak it until you get the correct value. The default value is around 0.064mm³. To get the correct value, multiply the nozzle width, layer height, and length at a certain height. For example, if the nozzle width is 0.4mm, layer height is 0.2mm, and an extrusion path is around 0.8, when you multiply them, you will get 0.064\. You can increase in small increments until you find the appropriate value.

**Minimum** **Volume Before Coasting** refers to the minimum material size that should be there for the slicer to apply coasting. The default value is around 0.8mm³, which works great for most prints.**Coasting speed** on the other hand is the speed at which the nozzle moves when it is coasting. It’s usually relative to the printing speed, and using a slightly lower value than 100%, like 90% is advisable.

 As you enable coasting to eliminate blobs and zits, you need to remember that its effectiveness depends on the geometry of your 3D model, 3D printing speed, and the type of filament you are using. So you need to tweak the settings until you achieve the best results.

## 4\. Adjust 3D printing Speed and Temperature

 Adjusting how fast your 3D printer prints as well as the temperature you are using can also help fix the issue as these settings influence the extrusion rate and the cooling time for the layers. A higher 3D printing speed than necessary can result in increased pressure in the nozzle, which can cause the excess filament to ooze out, causing issues on the print as the nozzle moves.

 The standard speed is usually between 50-60 mm/s, and anything above this can result in problems. If the temperature is too high, the filament can become too fluid and start oozing out. Alternatively, if it is too low, there can be incomplete melting which results in uneven extrusion which causes irregularities and inconsistencies in the printed layers. You must adjust the temperature until you find the perfect settings for your filament and printer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Disable Power Recovery Feature

 If none of the above options don’t work, you should consider turning off the power recovery option if it’s turned on. Even though this feature helps save your 3D print instead of starting to print from scratch in case of power interruption, it can introduce blobs. This is because when the feature is activated, the 3D printers utilize the SD card to write “check-points” or the print job state to the card, which will help in resuming the print and this might start competing with the standard printing operation, resulting in blobs.

 Turning this feature on is not easy as not all the[best 3D printers](https://www.tomshardware.com/best-picks/best-3d-printers) have that option on the menu, and you need to use the SD card. Luckily, a YouTuber, Geek Detour, created[G-code files for enabling and disabling power recovery](https://geekdetour.com/3d-printing/blobs-in-your-3d-prints-power-loss-recovery-can-be-the-problem/) and you can download and save them to your SD card and use them. You can also choose to buy a UPS battery to address power challenges if you don’t want the challenge of your print being affected due to power loss.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iOVkXoUxLf4?si=QfC18T2cb5OkiaXo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-the-role-of-creative-commons-in-youtube-content-sharing/"><u>[Updated] In 2024, The Role of Creative Commons in YouTube Content Sharing</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-the-cheapest-cloud-storage-service-for-mass-file-for-2024/"><u>[Updated] The Cheapest Cloud Storage Service for Mass File for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-decoding-the-mechanics-of-obtaining-facebooks-badge-of-trust/"><u>2024 Approved Decoding the Mechanics of Obtaining Facebook's Badge of Trust</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/acer-nitro-5-gaming-laptop-sale-secure-savings-of-up-to-250-now-zdnet/"><u>Acer Nitro 5 Gaming Laptop Sale - Secure Savings of Up To $250 Now! | ZDNet</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/alternative-video-editors-for-laptops/"><u>Alternative Video Editors for Laptops</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/customized-advertising-solutions-enhanced-with-the-power-of-cookiebot-technology/"><u>Customized Advertising Solutions: Enhanced with the Power of Cookiebot Technology</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/cyber-monday-alert-snag-an-hp-pavilion-laptop-for-half-the-price-only-450-this-year-zdnet/"><u>Cyber Monday Alert: Snag an HP Pavilion Laptop for Half the Price - Only $450 This Year! | ZDNet</u></a></li>
<li><a href="https://vp-tips.techidaily.com/does-adobe-premiere-pro-support-importing-and-exporting-videos-in-the-av1-format/"><u>Does Adobe Premiere Pro Support Importing and Exporting Videos in the AV1 Format?</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/experience-samsungs-game-changing-copilotplus-laptop-the-most-innovative-windows-deal-on-the-market-zdnet-insights/"><u>Experience Samsung's Game-Changing Copilot+ Laptop: The Most Innovative Windows Deal on the Market | ZDNET Insights</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/experiencing-lenovos-revolutionary-self-rotating-notebook-unveiled-at-ifa-2024-a-game-changer-for-mobile-workstations-techradar/"><u>Experiencing Lenovo's Revolutionary Self-Rotating Notebook Unveiled at IFA 2024: A Game-Changer for Mobile Workstations? | TechRadar</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mega-savings-at-hps-cyber-event-discounts-of-up-to-71-on-desktops-and-laptops-explore-the-deals-now/"><u>Mega Savings at HP's Cyber Event: Discounts of up to 71% on Desktops and Laptops - Explore the Deals Now!</u></a></li>
<li><a href="https://win-tutorials.techidaily.com/p2v3/"><u>P2V（物理→仮想）移行を成功させるためのトップ3ツール</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-directx-d3d-creation-issues-a-step-by-step-tutorial/"><u>Solving DirectX D3D Creation Issues: A Step-by-Step Tutorial</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-pc-and-console-bargains-during-octobers-prime-gaming-sales-featured-on-zdnet/"><u>Top PC and Console Bargains During October's Prime Gaming Sales - Featured on ZDNet</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-rated-work-travel-tablet-a-non-microsoft-non-lenovo-recommendation-from-a-seasoned-reviewer/"><u>Top-Rated Work Travel Tablet: A Non-Microsoft, Non-Lenovo Recommendation From a Seasoned Reviewer</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ultimate-beginners-choice-of-linux-distributions-thoroughly-evaluated-and-ranked-with-expert-reviews/"><u>Ultimate Beginner's Choice of Linux Distributions: Thoroughly Evaluated & Ranked with Expert Reviews</u></a></li>
<li><a href="https://some-tips.techidaily.com/unlock-early-bird-perks-preordering-iphone-15-apple-watch-series-ultra-2-with-amazing-discounts-tech-insights/"><u>Unlock Early Bird Perks: Preordering iPhone 15, Apple Watch Series Ultra 2 with Amazing Discounts | Tech Insights</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/why-professionals-need-the-budget-friendly-apple-m3-macbook-pro-the-ultimate-workhorse-explained-insights/"><u>Why Professionals Need the Budget-Friendly Apple M3 MacBook Pro: The Ultimate Workhorse Explained - Insights</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/your-ultimate-companion-for-mastering-mov-recordings-on-windows-10-for-2024/"><u>Your Ultimate Companion for Mastering MOV Recordings on Windows 10 for 2024</u></a></li>
</ul></div>

