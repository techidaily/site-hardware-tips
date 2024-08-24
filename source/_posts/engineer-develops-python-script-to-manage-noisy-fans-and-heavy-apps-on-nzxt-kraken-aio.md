---
title: Engineer Develops Python Script to Manage Noisy Fans & Heavy Apps on NZXT Kraken AIO
date: 2024-08-23T13:01:12.011Z
updated: 2024-08-24T13:01:12.011Z
tags:
  - cooling
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/uNadajpX9UjUcAQXfR5gUk-320-80.jpg
---

## Custom Python Script for a Quieter, Streamlined Experience with the NZXT Kraken AIO - Beat Fan Noise & Bulky Apps

Software designer Cal Bryant created a PC cooling app for his liquid-cooled Ryzen 9 5950X PC from scratch[using Python](https://calbryant.uk/blog/better-pc-cooling-with-python/#) . With his app, he was able to fine-tune his Kraken X53's pump and fan speed and run both a lot more efficiently, making the cooler run significantly quieter compared to running the fan controls through the motherboard[BIOS/UEFI](https://www.tomshardware.com/reviews/bios-keys-to-access-your-firmware,5732.html) .

 The origins of Bryant's home-brewed Python cooling app started when he upgraded his personal system from a[Ryzen 7 3700X](https://www.tomshardware.com/reviews/ryzen-9-3900x-7-3700x-review,6214.html) to the much more potent[Ryzen 9 5950X](https://www.tomshardware.com/reviews/amd-ryzen-9-5950x-5900x-zen-3-review) . According to Bryant, the extra cores nearly doubled the heat output of his system, forcing his NZXT Kraken X53 240mm[AIO liquid cooler](https://www.tomshardware.com/best-picks/best-aio-coolers) to work much harder. Consequently, the CPU swap also made his cooler much louder to deal with the extra heat output. On top of this, the fans were also spinning up and down erratically, due to Zen 3's notoriously spiky thermal output.

 Bryant found that the Kraken's cooler is not optimized out of the box for Ryzen CPUs, causing the fans to spin up and down erratically. The Kraken's pump speed is based on liquid temperature, while the fans are based on the[CPU temperature](https://www.tomshardware.com/how-to/how-to-check-cpu-temp-temperature) , something Bryant found unattractive. (We've also complained about this[our own cooler reviews](https://www.tomshardware.com/pc-components/cooling/reviews) .)

 To fix this problem, Bryant decided to build his own cooling app that could eliminate the problem and give him more granular control over his pump and fan speeds. Additionally, he doesn't like how bloated traditional fan software normally is, giving him even more incentive to build his own app.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

![Cal Bryant's fan curve from his Python app](https://cdn.mos.cms.futurecdn.net/HLapN7zrv8kWaLCxAFnc93-320-80.png)

 (Image credit: Cal Bryant)

 In the end, he was able to create an application that can read the CPU, case, and liquid temperatures of the system, and adjust the CPU fan and pump speeds accordingly. The app was written in[Python](https://www.tomshardware.com/how-to/use-for-loops-in-python) and Liquidctl, a programmatic control system that can allow Python scripts to control liquid coolers such as the X53\. For temperature control, the app reads temperature data from Linux's built-in hardware sensor capabilities, known as lm-sensors. Bryant wrote his Python app in such a way that it can be installed as a system service that starts when the OS boots up and hides in the background. For the nitty-gritty details on how the app was written step-by-step, check out Bryant's[full article](https://calbryant.uk/blog/better-pc-cooling-with-python/) .

 The app was tuned to run the X53's pump in conjunction with the CPU's temperature output and run the radiator fans in conjunction with the coolant temperature. This is very different from the X53's default configuration where the pump RPM is driven by the coolant temperature.

 With this method of RPM control, he was able to significantly reduce the spiky nature of his cooler's default fan profile and make the cooler more performant only when needed. Having the pump speed up based on the CPU temperature allows the cooler to extract heat more quickly from the CPU. Coolant takes a long time to warm up under a heavy load compared to[air coolers](https://www.tomshardware.com/reviews/best-cpu-coolers,4181.html) . Having the fans connected to the coolant temperature, in turn, allows the cooler to only run the fans at a high RPM when the coolant is warm. In an AIO, the fans aren't cooling the[CPU](https://www.tomshardware.com/reviews/best-cpus,3986.html) , they are cooling down the liquid that is extracting heat from the CPU.

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
<li><a href="https://facebook-video-footage.techidaily.com/updated-bridging-the-gap-youtube-editing-mastered-in-imovie-workflows-for-2024/"><u>[Updated] Bridging the Gap  YouTube Editing Mastered in iMovie Workflows for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-capture-and-save-top-15-insta-downloader-apps/"><u>[Updated] In 2024, Capture and Save  Top 15 Insta Downloader Apps</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-the-role-of-cdn-in-reducing-web-page-load-times-for-2024/"><u>[Updated] The Role of CDN in Reducing Web Page Load Times for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-fading-frequencies-the-gentle-way-with-garageband/"><u>2024 Approved  Fading Frequencies  The Gentle Way with Garageband</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-vdreams-comparing-paid-and-free-lightroom-counterparts/"><u>2024 Approved  VDreams  Comparing Paid & Free Lightroom Counterparts</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/advanced-hardware-guides-by-toms-computing-corner/"><u>Advanced Hardware Guides by Tom's Computing Corner</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/advanced-tutorials-and-reviews-by-toms-hardware-experts/"><u>Advanced Tutorials & Reviews by Tom’s Hardware Experts</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/architectural-weaknesses-exposed-how-ghostwrite-takes-advantage-of-risc-v-for-root-entry/"><u>Architectural Weaknesses Exposed: How GhostWrite Takes Advantage of RISC-V for Root Entry</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/budget-friendly-top-picks-thermalright-frozen-notte-vs-aqua-elite-360-white-v3-comprehensive-aio-reviews/"><u>Budget-Friendly Top Picks: Thermalright Frozen Notte Vs. Aqua Elite 360 White V3 - Comprehensive AIO Reviews</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/captivating-content-creation-the-best-10-igtv-strategies-for-brands-for-2024/"><u>Captivating Content Creation  The Best 10 IGTV Strategies for Brands for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/dive-into-computing-with-toms-hardware-expertise/"><u>Dive Into Computing with Tom's Hardware Expertise</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-the-latest-in-computing-with-toms-equipment-reviews/"><u>Exploring the Latest in Computing with Tom's Equipment Reviews</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/extended-warranty-insights-intel-unveils-coverage-for-core-i5-i7-and-i9-processors-in-13th-and-14th-generation-chipsets/"><u>Extended Warranty Insights: Intel Unveils Coverage for Core I5, I7, and I9 Processors in 13Th & 14Th Generation Chipsets</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-print-server-not-responding-issue/"><u>Fixing Print Server Not Responding Issue</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/gamers-essential-guide-to-the-premier-power-supplies-of-202e4/"><u>Gamers' Essential Guide to the Premier Power Supplies of 202E4</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/how-der8auer-admitted-his-mistake-with-inefficient-grizzly-heatsink-units/"><u>How Der8auer Admitted His Mistake with Inefficient Grizzly Heatsink Units</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-netflix-location-to-get-more-country-version-on-apple-iphone-13-pro-max-drfone-by-drfone-virtual-ios/"><u>How to Change Netflix Location to Get More Country Version On Apple iPhone 13 Pro Max | Dr.fone</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-master-the-art-of-trailer-creation-for-enhanced-income/"><u>In 2024, Master the Art of Trailer Creation for Enhanced Income</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-top-video-conference-solutions-security-first-for-businesses/"><u>In 2024, Top Video Conference Solutions  Security First for Businesses</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/innovative-raspberry-pi-pico-accessories-coming-in-25-trending-add-ons-for-raspberry-pi-pico-whats-new/"><u>Innovative Raspberry Pi Pico Accessories Coming in 2#5 Trending Add-Ons for Raspberry Pi Pico - What's New</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/inside-toms-gadget-rundown-your-source-for-computer-components/"><u>Inside Tom's Gadget Rundown: Your Source for Computer Components</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723125180939-join-felicia-days-newest-adventure-in-the-thangs-3d-community-unique-downloadable-model-collection-available-now/"><u>Join Felicia Day's Newest Adventure in the Thangs 3D Community: Unique, Downloadable Model Collection Available Now!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-technology-at-toms-hardware-haven-online/"><u>Mastering Technology at Tom's Hardware Haven Online</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-the-tech-scene-toms-precision-hardware-critiques-and-advice/"><u>Mastering the Tech Scene: Tom's Precision Hardware Critiques and Advice</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mo-ra-iv-600-mega-pc-liquid-cooling-radiator-9x200mm-fans-heavyweight-design-for-superior-performance-over-35lbs-under-600/"><u>MO-RA IV 600 - Mega PC Liquid Cooling Radiator: 9X200mm Fans, Heavyweight Design for Superior Performance (Over 35Lbs) Under $600</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-new-electronics-with-toms-comprehensive-hardware-analysis/"><u>Navigating New Electronics with Tom's Comprehensive Hardware Analysis</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-review-hub-for-electronics-by-toms-hardware-team/"><u>The Ultimate Review Hub for Electronics by Tom's Hardware Team</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-computing-world-the-ultimate-hardware-hub/"><u>Tom's Computing World: The Ultimate Hardware Hub</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ultimate-guide-to-buying-powerful-gaming-laptops-below-1500/"><u>Ultimate Guide to Buying Powerful Gaming Laptops Below $1,500</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-latest-in-computers-and-peripherals-with-toms-analysis/"><u>Unveiling the Latest in Computers & Peripherals with Tom's Analysis</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-potential-of-crealitys-k1-carbon-the-next-big-thing-in-carbon-fiber-printing/"><u>Unveiling the Potential of Creality's K1-Carbon: The Next Big Thing in Carbon Fiber Printing?</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-top-performers-a-deep-dive-into-toms-hardware-selection/"><u>Unveiling Top Performers - A Deep Dive Into Tom's Hardware Selection</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->