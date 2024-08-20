---
title: "The Ultimate Breakdown of the Corsair Air A115 Cooler: Striking Balance Between Strength, Quiet Operation & Expense"
date: 2024-08-19T02:57:04.214Z
updated: 2024-08-20T02:57:04.214Z
tags:
  - cooling
categories:
  - hardware
thumbnail: https://thmb.techidaily.com/1a08c8dedd48664d90b507bda304483e40c9a1d2dac0696255a8394fc453f16e.jpg
---

## Custom Python Script for a Quieter, Streamlined Experience with the NZXT Kraken AIO - Beat Fan Noise & Bulky Apps

Software designer Cal Bryant created a PC cooling app for his liquid-cooled Ryzen 9 5950X PC from scratch[using Python](https://calbryant.uk/blog/better-pc-cooling-with-python/#) . With his app, he was able to fine-tune his Kraken X53's pump and fan speed and run both a lot more efficiently, making the cooler run significantly quieter compared to running the fan controls through the motherboard[BIOS/UEFI](https://www.tomshardware.com/reviews/bios-keys-to-access-your-firmware,5732.html) .

 The origins of Bryant's home-brewed Python cooling app started when he upgraded his personal system from a[Ryzen 7 3700X](https://www.tomshardware.com/reviews/ryzen-9-3900x-7-3700x-review,6214.html) to the much more potent[Ryzen 9 5950X](https://www.tomshardware.com/reviews/amd-ryzen-9-5950x-5900x-zen-3-review) . According to Bryant, the extra cores nearly doubled the heat output of his system, forcing his NZXT Kraken X53 240mm[AIO liquid cooler](https://www.tomshardware.com/best-picks/best-aio-coolers) to work much harder. Consequently, the CPU swap also made his cooler much louder to deal with the extra heat output. On top of this, the fans were also spinning up and down erratically, due to Zen 3's notoriously spiky thermal output.

 Bryant found that the Kraken's cooler is not optimized out of the box for Ryzen CPUs, causing the fans to spin up and down erratically. The Kraken's pump speed is based on liquid temperature, while the fans are based on the[CPU temperature](https://www.tomshardware.com/how-to/how-to-check-cpu-temp-temperature) , something Bryant found unattractive. (We've also complained about this[our own cooler reviews](https://www.tomshardware.com/pc-components/cooling/reviews) .)

 To fix this problem, Bryant decided to build his own cooling app that could eliminate the problem and give him more granular control over his pump and fan speeds. Additionally, he doesn't like how bloated traditional fan software normally is, giving him even more incentive to build his own app.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Cal Bryant's fan curve from his Python app](https://cdn.mos.cms.futurecdn.net/HLapN7zrv8kWaLCxAFnc93-320-80.png)

 (Image credit: Cal Bryant)

 In the end, he was able to create an application that can read the CPU, case, and liquid temperatures of the system, and adjust the CPU fan and pump speeds accordingly. The app was written in[Python](https://www.tomshardware.com/how-to/use-for-loops-in-python) and Liquidctl, a programmatic control system that can allow Python scripts to control liquid coolers such as the X53\. For temperature control, the app reads temperature data from Linux's built-in hardware sensor capabilities, known as lm-sensors. Bryant wrote his Python app in such a way that it can be installed as a system service that starts when the OS boots up and hides in the background. For the nitty-gritty details on how the app was written step-by-step, check out Bryant's[full article](https://calbryant.uk/blog/better-pc-cooling-with-python/) .

 The app was tuned to run the X53's pump in conjunction with the CPU's temperature output and run the radiator fans in conjunction with the coolant temperature. This is very different from the X53's default configuration where the pump RPM is driven by the coolant temperature.

 With this method of RPM control, he was able to significantly reduce the spiky nature of his cooler's default fan profile and make the cooler more performant only when needed. Having the pump speed up based on the CPU temperature allows the cooler to extract heat more quickly from the CPU. Coolant takes a long time to warm up under a heavy load compared to[air coolers](https://www.tomshardware.com/reviews/best-cpu-coolers,4181.html) . Having the fans connected to the coolant temperature, in turn, allows the cooler to only run the fans at a high RPM when the coolant is warm. In an AIO, the fans aren't cooling the[CPU](https://www.tomshardware.com/reviews/best-cpus,3986.html) , they are cooling down the liquid that is extracting heat from the CPU.

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Stay On the Cutting Edge: Get the Tom's Hardware Newsletter

 Get Tom's Hardware's best news and in-depth reviews, straight to your inbox.

 Contact me with news and offers from other Future brands  Receive email from us on behalf of our trusted partners or sponsors

 By submitting your information you agree to the[Terms & Conditions](https://futureplc.com/terms-conditions/) and[Privacy Policy](https://futureplc.com/privacy-policy/) and are aged 16 or over.

 The app can be downloaded for free from a link in Cal Bryant's article. However, the it's specifically fine-tuned to his system, meaning that users would need to edit the code he created to make the cooling app work on their systems.


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
<li><a href="https://snapchat-videos.techidaily.com/new-enhance-engagement-with-these-15-snap-insights/"><u>[New] Enhance Engagement with These 15 Snap Insights</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-mastering-iphones-voice-memo-functionality/"><u>[New] In 2024, Mastering iPhone's Voice Memo Functionality</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-quick-guide-personalized-youtube-shorts-images-without-hassle/"><u>[New] Quick Guide  Personalized YouTube Shorts Images Without Hassle</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/iral-video-venues-clash-youtube-shorts-vs-tiktoks-rapid-rise-for-2024/"><u>[New] Viral Video Venues Clash  YouTube Shorts Vs. TikTok's Rapid Rise for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-top-10-gratis-video-call-tools-for-virtual-gatherings/"><u>[Updated] 2024 Approved  Top 10 Gratis Video Call Tools for Virtual Gatherings</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-a-roadmap-for-optimizing-and-tracking-your-fb-in-stream-ad-performance-for-2024/"><u>[Updated] A Roadmap for Optimizing and Tracking Your FB In-Stream Ad Performance for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-image-all-screen-website-view/"><u>[Updated] In 2024, Image All-Screen Website View</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-groundbreision-of-top-8-free-video-call-software-for-companies/"><u>2024 Approved  Groundbreision of Top 8 Free Video Call Software for Companies</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-in-depth-review-of-audfreeplus-software/"><u>2024 Approved  In-Depth Review of AudFreePlus Software</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/2024s-elite-selection-of-ergonomic-chairs-for-serious-gamers/"><u>2024'S Elite Selection of Ergonomic Chairs for Serious Gamers</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/advanced-computer-components-decoded-by-toms-hardware-experts/"><u>Advanced Computer Components Decoded by Tom's Hardware Experts</u></a></li>
<li><a href="https://extra-information.techidaily.com/best-practices-in-selecting-premium-hdr-cameras-for-2024/"><u>Best Practices in Selecting Premium HDR Cameras for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/bold-disclosure-of-vulnerability-as-hackers-break-into-anycubics-3d-printer-network/"><u>Bold Disclosure of Vulnerability as Hackers Break Into Anycubic's 3D Printer Network</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/budget-friendly-uphere-c5c-and-d6sec-air-cooler-evaluation-great-value-under-20/"><u>Budget-Friendly UpHere C5C & D6Sec Air Cooler Evaluation - Great Value Under $20</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/decoding-computer-specs-in-depth-reviews-from-toms-gear-guides/"><u>Decoding Computer Specs: In-Depth Reviews From Tom's Gear Guides</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discover-in-depth-reviews-at-toms-hardware-your-gadget-hub/"><u>Discover In-Depth Reviews at Tom's Hardware - Your Gadget Hub</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/elegoo-neptune-4-pro-the-ultimate-combo-of-speed-precision-and-economy-in-3d-printing-reviews/"><u>Elegoo Neptune 4 Pro: The Ultimate Combo of Speed, Precision & Economy in 3D Printing Reviews</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/enhanced-user-experience-through-cookiebot-integration/"><u>Enhanced User Experience Through Cookiebot Integration</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-review-id-cooling-frozn-a620-pro-se-unparalleled-value/"><u>Expert Review: ID-Cooling Frozn A620 PRO SE - Unparalleled Value</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-computer-components-with-tom-a-hardware-specialist/"><u>Exploring Computer Components with Tom - A Hardware Specialist</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-computer-components-with-tom-your-hardware-hub/"><u>Exploring Computer Components with Tom - Your Hardware Hub</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-computing-systems-with-toms-technology-reviews/"><u>Exploring Computing Systems with Tom's Technology Reviews</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-the-co-pilot-extension-for-chatgpt-impactful-functionalities/"><u>Exploring the Co-Pilot Extension for ChatGPT: Impactful Functionalities</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/freezing-into-action-with-frore-trio-of-trial-airjet-pak-cools-ideal-for-edge-ai-max-25-watts/"><u>Freezing Into Action with Frore - Trio of Trial AirJet PAK Cools Ideal for Edge AI, Max 25 Watts</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723125187744-how-the-largest-advance-in-additive-manufacturing-shrinks-to-coin-size-revolutionizing-tech-with-no-movable-parts/"><u>How the Largest Advance in Additive Manufacturing Shrinks to Coin Size, Revolutionizing Tech With No Movable Parts!</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-oppo-find-x6-pro-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Oppo Find X6 Pro phone? | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-7-energizing-youtube-exercise-challenges-for-viewers-participation/"><u>In 2024, 7 Energizing YouTube Exercise Challenges for Viewers' Participation</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-unleash-potential-in-media-production-via-xp/"><u>In 2024, Unleash Potential in Media Production via XP</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/in-depth-analysis-of-modern-hardware-by-toms-hardware-experts/"><u>In-Depth Analysis of Modern Hardware by Tom's Hardware Experts</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/in-depth-electronics-analysis-and-reviews-by-toms-digital-workshop/"><u>In-Depth Electronics Analysis and Reviews by Tom's Digital Workshop</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/in-depth-review-the-impact-of-using-the-cooler-master-ion-360-liquid-cpu-cooling-system/"><u>In-Depth Review: The Impact of Using the Cooler Master ION 360 Liquid CPU Cooling System</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/in-depth-reviews-and-tips-by-toms-gadget-experts/"><u>In-Depth Reviews and Tips by Tom's Gadget Experts</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/innovative-insights-on-computers-and-components-by-toms-hardware-experts/"><u>Innovative Insights on Computers and Components by Tom’s Hardware Experts</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/masterful-hacks-for-hardware-enthusiasts-dive-into-toms-comprehensive-guide/"><u>Masterful Hacks for Hardware Enthusiasts - Dive Into Tom's Comprehensive Guide</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-modern-computing-a-deep-dive-into-toms-hardware-insights/"><u>Mastering Modern Computing: A Deep Dive Into Tom's Hardware Insights</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-tech-essentials-insightful-reviews-from-toms-hardware-authority/"><u>Mastering Tech Essentials: Insightful Reviews From Tom's Hardware Authority</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-new-technologies-in-depth-tutorials-and-product-comparisons-by-toms-hardware/"><u>Navigating New Technologies: In-Depth Tutorials and Product Comparisons by Tom's Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/next-gen-refrigeration-innovation-aseteks-advanced-ai-cold-plate-for-ecam-systems-born-from-cutting-edge-3d-metal-printing-and-synergistic-development-with-16/"><u>Next-Gen Refrigeration Innovation: Asetek's Advanced AI Cold Plate for ECAM Systems, Born From Cutting-Edge 3D Metal Printing and Synergistic Development with Fabric8 Labs</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/noctua-unveils-top-of-the-line-flagship-cooler-premium-next-gen-performance-with-the-newly-released-nh-d15-g2-at-just-1eby/"><u>Noctua Unveils Top-of-the-Line Flagship Cooler - Premium Next-Gen Performance with the Newly Released NH-D15 G2 at Just $1Eby</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedying-network-unavailable-error-on-windows-devices/"><u>Remedying 'Network Unavailable' Error on Windows Devices</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/revitalize-your-gaming-with-the-99-chromax-black-noctua-cooler-the-highest-quality-in-air-ventilation-technology/"><u>Revitalize Your Gaming with the £99 Chromax Black Noctua Cooler: The Highest Quality in Air Ventilation Technology</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-resource-for-computing-gear-toms-authoritative-opinions/"><u>The Ultimate Resource for Computing Gear - Tom's Authoritative Opinions</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-updated-method-to-bypass-tecno-spark-20-proplus-frp-by-drfone-android/"><u>The Updated Method to Bypass Tecno Spark 20 Pro+ FRP</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-review-in-depth-analysis-and-hardware-insights/"><u>Tom's Tech Review: In-Depth Analysis & Hardware Insights</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-specs-ultimate-computer-components-guide/"><u>Tom's Tech Specs: Ultimate Computer Components Guide</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-rated-graphics-cards-of-2024-ultimate-guide-to-value-packed-gaming-gpus/"><u>Top Rated Graphics Cards of 2024: Ultimate Guide to Value-Packed Gaming GPUs</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-tech-secrets-revealed-by-tom-for-savvy-hardware-shoppers/"><u>Top Tech Secrets Revealed by Tom for Savvy Hardware Shoppers</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unleash-next-level-chill-the-iconic-return-of-the-noctua-nh-d12l-in-stunning-black-just-99/"><u>Unleash Next-Level Chill: The Iconic Return of the Noctua NH-D12L in Stunning Black - Just $99</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unmatched-printing-velocity-unleashed-speed-benchy-model-materializes-faster-than-ever-with-a-modified-3d-printer/"><u>Unmatched Printing Velocity Unleashed – 'Speed Benchy' Model Materializes Faster than Ever with a Modified 3D Printer</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-best-value-in-rapid-printing-elegoos-neptune-ebeam-reviewed-for-quality-and-price/"><u>Unveiling the Best Value in Rapid Printing: Elegoo's Neptune Ebeam Reviewed for Quality and Price</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/upgrade-to-the-future-of-pc-components-introducing-deepcools-advanced-coolers-psus-and-fans-with-customizable-pixel-silicone-decorations/"><u>Upgrade to the Future of PC Components - Introducing DeepCool's Advanced Coolers, PSUs & Fans with Customizable Pixel Silicone Decorations</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/visual-vistas-essential-effects-for-striking-snaps-for-2024/"><u>Visual Vistas  Essential Effects for Striking Snaps for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/warframe-no-longer-receiving-updates-diagnosing-and-fixing-the-error/"><u>Warframe No Longer Receiving Updates: Diagnosing and Fixing the Error</u></a></li>
</ul></div>
