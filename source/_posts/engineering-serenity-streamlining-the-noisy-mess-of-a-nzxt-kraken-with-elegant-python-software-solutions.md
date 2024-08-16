---
title: "Engineering Serenity: Streamlining the Noisy Mess of a NZXT Kraken with Elegant Python Software Solutions"
date: 2024-08-15T06:23:17.668Z
updated: 2024-08-16T06:23:17.668Z
tags:
  - cooling
categories:
  - hardware
thumbnail: https://thmb.techidaily.com/d506d541a004c51c2cd3026bd49f4e9e82c157f9f39dde8952261d2b96a29117.jpg
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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-google-chats-mastery-key-elements-4-ways/"><u>[New] 2024 Approved  Google Chats Mastery  Key Elements, #4 Ways</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-ultimate-download-hub-for-social-media-videos-fb/"><u>[New] 2024 Approved  Ultimate Download Hub for Social Media Videos (FB)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-collabcanvas-mosaic-magic-on-instagram-devices/"><u>[New] In 2024, CollabCanvas  Mosaic Magic on Instagram Devices</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-techniques-to-extract-sound-from-vimeo-videos-for-2024/"><u>[New] Techniques to Extract Sound From Vimeo Videos for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-a-comprehensive-guide-to-crop-your-video-for-instagram/"><u>[Updated] A Comprehensive Guide to Crop Your Video for Instagram</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-seamless-skype-call-recordings-a-cross-platform-approach-for-2024/"><u>[Updated] Seamless Skype Call Recordings  A Cross-Platform Approach for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-audio-quality-boost-for-skype-calls/"><u>2024 Approved  Audio Quality Boost for Skype Calls</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/affordable-high-definition-monitors-top-pickup-list-of-4k-screens/"><u>Affordable High Definition Monitors: Top Pickup List of 4K Screens</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/benchmark-analysis-the-fastest-3d-printer-models-for-rapid-prototyping/"><u>Benchmark Analysis: The Fastest 3D Printer Models for Rapid Prototyping</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/celebrity-actress-felicia-day-ventures-into-3d-printing-shares-her-models-with-fans-for-free/"><u>Celebrity Actress Felicia Day Ventures Into 3D Printing, Shares Her Models with Fans for Free</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/comprehensive-hardware-evaluations-from-toms-technology-blog/"><u>Comprehensive Hardware Evaluations From Tom's Technology Blog</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discover-noctuas-game-changer-the-prototype-for-pumpless-eco-friendly-aio-liquid-cooling-system/"><u>Discover Noctua's Game-Changer: The Prototype for Pumpless, Eco-Friendly AIO Liquid Cooling System</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discover-the-best-value-cpu-picks-for-2abies-as-tested-and-evaluated-by-toms-hardware/"><u>Discover the Best Value CPU Picks for 2Abies, as Tested and Evaluated by Tom's Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discover-the-latest-in-tech-with-toms-hardware-reviews/"><u>Discover the Latest in Tech with Tom's Hardware Reviews</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discover-the-leading-gaming-chair-models-of-2-for-optimal-play-comfort/"><u>Discover the Leading Gaming Chair Models of 2# for Optimal Play Comfort</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discovering-the-secrets-behind-the-popular-creality-ender-3-v3-ke-a-detailed-seo-guide-for-savvy-shoppers/"><u>Discovering the Secrets Behind the Popular Creality Ender 3 V3 Ke - A Detailed SEO Guide for Savvy Shoppers</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/dont-miss-out-on-top-tier-performance-save-75-with-the-editors-choice-elegoo-neptune-4-pro/"><u>Don't Miss Out on Top-Tier Performance - Save $75 with the Editor's Choice, Elegoo Neptune 4 Pro!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ekwb-owns-up-company-apologizes-for-late-remittances-vows-improved-practices/"><u>EKWB Owns Up: Company Apologizes for Late Remittances, Vows Improved Practices</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/elevate-playstation-5-experience-with-leading-ssd-upgrades-and-speed-enhancements/"><u>Elevate PlayStation 5 Experience with Leading SSD Upgrades and Speed Enhancements</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-analysis-of-the-scythe-mugen-6-and-mugen-6-black-edition-cutting-edge-quiet-cooling-at-a-competitive-price-range/"><u>Expert Analysis of the Scythe Mugen 6 and Mugen 6 Black Edition: Cutting-Edge Quiet Cooling at a Competitive Price Range</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-review-how-does-the-levelplay-combat-air-ca4-keep-your-cpu-cool-and-quiet/"><u>Expert Review: How Does the Levelplay Combat Air CA4 Keep Your CPU Cool and Quiet?</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-advanced-computing-gear-with-tom-insights-and-analysis/"><u>Exploring Advanced Computing Gear with Tom - Insights & Analysis</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-technology-with-tom-your-go-to-guide/"><u>Exploring Technology with Tom - Your Go-To Guide</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-the-latest-gadgets-with-tom-comprehensive-hardware-guides/"><u>Exploring the Latest Gadgets with Tom - Comprehensive Hardware Guides</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-the-latest-gadgets-with-toms-hardware-guides/"><u>Exploring the Latest Gadgets with Tom's Hardware Guides</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-honor-x8b-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Solutions to Find Your Honor X8b Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-any-oppo-k11-5g-phone-password-using-emergency-call-by-drfone-android/"><u>In 2024, How To Unlock Any Oppo K11 5G Phone Password Using Emergency Call</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-innovative-visual-alteration-solutions-pixelpioneers-edge/"><u>In 2024, Innovative Visual Alteration Solutions  PixelPioneer's Edge</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-learn-to-edit-the-ultimate-guide-for-igtv-titles/"><u>In 2024, Learn to Edit  The Ultimate Guide for IGTV Titles</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/in-depth-review-why-the-arctic-liquid-freezer-iii-aio-doesnt-meet-expectations/"><u>In-Depth Review: Why the Arctic Liquid Freezer III AIO Doesn't Meet Expectations</u></a></li>
<li><a href="https://extra-hints.techidaily.com/sci-fis-virtual-cosmos-the-most-innovative-movies-of-the-metaverse-era/"><u>Sci-Fi's Virtual Cosmos  The Most Innovative Movies of the Metaverse Era</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->