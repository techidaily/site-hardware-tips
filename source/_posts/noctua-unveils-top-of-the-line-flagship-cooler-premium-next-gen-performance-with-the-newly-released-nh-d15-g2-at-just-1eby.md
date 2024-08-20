---
title: Noctua Unveils Top-of-the-Line Flagship Cooler - Premium Next-Gen Performance with the Newly Released NH-D15 G2 at Just $1Eby
date: 2024-08-19T03:08:19.397Z
updated: 2024-08-20T03:08:19.397Z
tags:
  - cooling
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/iD8sv93T3UL69ADecUGpwW-320-80.jpg
---

## Custom Python Script for a Quieter, Streamlined Experience with the NZXT Kraken AIO - Beat Fan Noise & Bulky Apps

Software designer Cal Bryant created a PC cooling app for his liquid-cooled Ryzen 9 5950X PC from scratch[using Python](https://calbryant.uk/blog/better-pc-cooling-with-python/#) . With his app, he was able to fine-tune his Kraken X53's pump and fan speed and run both a lot more efficiently, making the cooler run significantly quieter compared to running the fan controls through the motherboard[BIOS/UEFI](https://www.tomshardware.com/reviews/bios-keys-to-access-your-firmware,5732.html) .

 The origins of Bryant's home-brewed Python cooling app started when he upgraded his personal system from a[Ryzen 7 3700X](https://www.tomshardware.com/reviews/ryzen-9-3900x-7-3700x-review,6214.html) to the much more potent[Ryzen 9 5950X](https://www.tomshardware.com/reviews/amd-ryzen-9-5950x-5900x-zen-3-review) . According to Bryant, the extra cores nearly doubled the heat output of his system, forcing his NZXT Kraken X53 240mm[AIO liquid cooler](https://www.tomshardware.com/best-picks/best-aio-coolers) to work much harder. Consequently, the CPU swap also made his cooler much louder to deal with the extra heat output. On top of this, the fans were also spinning up and down erratically, due to Zen 3's notoriously spiky thermal output.

 Bryant found that the Kraken's cooler is not optimized out of the box for Ryzen CPUs, causing the fans to spin up and down erratically. The Kraken's pump speed is based on liquid temperature, while the fans are based on the[CPU temperature](https://www.tomshardware.com/how-to/how-to-check-cpu-temp-temperature) , something Bryant found unattractive. (We've also complained about this[our own cooler reviews](https://www.tomshardware.com/pc-components/cooling/reviews) .)

 To fix this problem, Bryant decided to build his own cooling app that could eliminate the problem and give him more granular control over his pump and fan speeds. Additionally, he doesn't like how bloated traditional fan software normally is, giving him even more incentive to build his own app.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
![Cal Bryant's fan curve from his Python app](https://cdn.mos.cms.futurecdn.net/HLapN7zrv8kWaLCxAFnc93-320-80.png)

 (Image credit: Cal Bryant)

 In the end, he was able to create an application that can read the CPU, case, and liquid temperatures of the system, and adjust the CPU fan and pump speeds accordingly. The app was written in[Python](https://www.tomshardware.com/how-to/use-for-loops-in-python) and Liquidctl, a programmatic control system that can allow Python scripts to control liquid coolers such as the X53\. For temperature control, the app reads temperature data from Linux's built-in hardware sensor capabilities, known as lm-sensors. Bryant wrote his Python app in such a way that it can be installed as a system service that starts when the OS boots up and hides in the background. For the nitty-gritty details on how the app was written step-by-step, check out Bryant's[full article](https://calbryant.uk/blog/better-pc-cooling-with-python/) .

 The app was tuned to run the X53's pump in conjunction with the CPU's temperature output and run the radiator fans in conjunction with the coolant temperature. This is very different from the X53's default configuration where the pump RPM is driven by the coolant temperature.

 With this method of RPM control, he was able to significantly reduce the spiky nature of his cooler's default fan profile and make the cooler more performant only when needed. Having the pump speed up based on the CPU temperature allows the cooler to extract heat more quickly from the CPU. Coolant takes a long time to warm up under a heavy load compared to[air coolers](https://www.tomshardware.com/reviews/best-cpu-coolers,4181.html) . Having the fans connected to the coolant temperature, in turn, allows the cooler to only run the fans at a high RPM when the coolant is warm. In an AIO, the fans aren't cooling the[CPU](https://www.tomshardware.com/reviews/best-cpus,3986.html) , they are cooling down the liquid that is extracting heat from the CPU.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-direct.techidaily.com/new-in-2024-gopro-max-vs-hero-11-a-video-quality-showdown/"><u>[New] In 2024, GoPro Max vs Hero 11  A Video Quality Showdown</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-youtubes-best-gamers-audio-selection-guide/"><u>[New] YouTube's Best Gamers' Audio Selection Guide</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/24m-texas-property-showcases-unique-infrastructure-expansive-5786-sq-ft-data-facility-with-superior-liquid-immersion-technology-bedrooms-excluded/"><u>$2.4M Texas Property Showcases Unique Infrastructure: Expansive 5,786 Sq Ft Data Facility with Superior Liquid Immersion Technology - Bedrooms Excluded</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-future-fortunes-for-virtual-game-masters/"><u>2024 Approved  Future Fortunes for Virtual Game Masters</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/advanced-tech-insights-a-deep-dive-by-tomcuits/"><u>Advanced Tech Insights: A Deep-Dive by Tom'cuits</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/asetek-stops-issuing-sales-forecasts-due-to-major-client-order-cancellations/"><u>Asetek Stops Issuing Sales Forecasts Due to Major Client Order Cancellations</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/breakthrough-in-electronics-producing-3d-chip-circuits-using-state-of-the-art-3d-printing-techniques/"><u>Breakthrough in Electronics: Producing 3D Chip Circuits Using State-of-the-Art 3D Printing Techniques</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discover-the-advantages-of-using-ultralight-gan-technology-in-premium-usb-c-laptop-chargers/"><u>Discover the Advantages of Using Ultralight GaN Technology in Premium USB-C Laptop Chargers</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discover-the-finest-ultramodern-notebooks-and-high-end-laptops-of-2024/"><u>Discover the Finest Ultramodern Notebooks & High-End Laptops of 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/essential-tips-to-ensure-solid-hole-free-3d-prints-every-time/"><u>Essential Tips to Ensure Solid, Hole-Free 3D Prints Every Time</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/experience-classic-games-anywhere-with-these-top-5-game-boy-advance-console-emulators/"><u>Experience Classic Games Anywhere with These Top 5 Game Boy Advance Console Emulators</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-insights-on-the-cooler-master-ion-360-all-in-one-aio-is-it-a-leap-forward-in-pc-cooling/"><u>Expert Insights on the Cooler Master ION 360 All-in-One AIO - Is It a Leap Forward in PC Cooling?</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-hardware-with-tom-the-ultimate-guide/"><u>Exploring Hardware with Tom: The Ultimate Guide</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723175710378-get-cold-pay-less-secure-arctics-high-efficiency-liquid-freezer-ii-aioldii-for-only-74-bucks/"><u>Get Cold, Pay Less: Secure Arctic's High-Efficiency Liquid Freezer II (AIOLDII) for Only 74 Bucks!</u></a></li>
<li><a href="https://program-issues.techidaily.com/how-to-fix-age-of-empires-iv-installation-problems-on-the-microsoft-store/"><u>How to Fix Age of Empires IV Installation Problems on the Microsoft Store</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-apple-iphone-12-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, How to get the dragon scale and evolution-enabled pokemon On Apple iPhone 12 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-keep-your-viewers-hooked-6-compelling-video-types/"><u>In 2024, Keep Your Viewers Hooked  6 Compelling Video Types</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-skyward-haven-of-the-pennywise-clouds/"><u>In 2024, Skyward Haven of the Pennywise Clouds</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/introducing-crealitys-latest-milestone-a-colorful-addition-to-its-10year-legacy-in-3d-printing/"><u>Introducing Creality’s Latest Milestone: A Colorful Addition to Its 10Year Legacy in 3D Printing</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/masterclass-on-hardware-solutions-by-toms-technological-wisdom/"><u>Masterclass on Hardware Solutions by Tom's Technological Wisdom</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/masterful-video-chats-best-webcams-for-zoom-6-for-2024/"><u>Masterful Video Chats  Best Webcams for Zoom #6 for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-the-tech-landscape-insider-tips-from-toms-comprehensive-hardware-reviews/"><u>Mastering the Tech Landscape: Insider Tips From Tom's Comprehensive Hardware Reviews</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-your-tech-game-plan-with-insights-from-toms-hardware-hub/"><u>Mastering Your Tech Game Plan with Insights From Tom's Hardware Hub</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-the-realm-of-gadgets-at-toms-hardware/"><u>Navigating the Realm of Gadgets at Tom's Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-the-tech-world-insights-from-toms-comprehensive-hardware-analysis/"><u>Navigating the Tech World: Insights From Tom’s Comprehensive Hardware Analysis</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-the-world-of-electronics-with-toms-hardware-expertise/"><u>Navigating the World of Electronics with Tom's Hardware Expertise</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/pwm-versus-dc-fans-which-is-better-suited-for-effective-pc-temperature-regulation/"><u>PWM versus DC Fans: Which Is Better Suited for Effective PC Temperature Regulation?</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/review-cost-effective-performance-of-upheres-c5c-and-d6sec-air-conditioners-below-20/"><u>Review: Cost-Effective Performance of UpHere's C5C and D6Sec Air Conditioners Below 20$</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723125181503-save-big-with-the-newly-discounted-phrozen-sonic-mini-8k-ss-resin-3d-printing-machine-just-325/"><u>Save Big with the Newly Discounted Phrozen Sonic Mini 8K sS Resin 3D Printing Machine - Just $325</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/selecting-superior-speed-best-ssds-for-an-unmatched-gaming-journey-on-the-steam-deck/"><u>Selecting Superior Speed: Best SSDs for an Unmatched Gaming Journey on the Steam Deck</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-next-gen-apple-phones-insight-into-the-forthcoming-foldable-models-specs-and-market-entry-strategy/"><u>The Next-Gen Apple Phones: Insight Into the Forthcoming Foldable Model's Specs and Market Entry Strategy</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-guide-mastering-the-art-of-3d-printed-lithophanes/"><u>The Ultimate Guide: Mastering the Art of 3D Printed Lithophanes</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-rated-cpu-cooling-solutions-of-2024-comparing-aio-vs-air-models/"><u>Top-Rated CPU Cooling Solutions of 2024 - Comparing AIO Vs. Air Models</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-rated-wireless-mice-of-2024-enhance-efficiency-with-ultimate-portability/"><u>Top-Rated Wireless Mice of 2024: Enhance Efficiency with Ultimate Portability</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unveiling-the-best-21-hdmi-screens-side-by-side-review-for-2024/"><u>Unveiling the Best 2.1 HDMI Screens  Side-By-Side Review for 2024</u></a></li>
</ul></div>
