---
title: Custom Python Script for a Quieter, Streamlined Experience with the NZXT Kraken AIO - Beat Fan Noise & Bulky Apps
date: 2024-08-19T03:16:08.886Z
updated: 2024-08-20T03:16:08.886Z
tags:
  - cooling
categories:
  - hardware
thumbnail: https://thmb.techidaily.com/3c089195526935c85a4cb3e6dde5d5ebf9d1e09e8343d1ce6aea5ca384c30ca3.jpg
---

## Custom Python Script for a Quieter, Streamlined Experience with the NZXT Kraken AIO - Beat Fan Noise & Bulky Apps

Software designer Cal Bryant created a PC cooling app for his liquid-cooled Ryzen 9 5950X PC from scratch[using Python](https://calbryant.uk/blog/better-pc-cooling-with-python/#) . With his app, he was able to fine-tune his Kraken X53's pump and fan speed and run both a lot more efficiently, making the cooler run significantly quieter compared to running the fan controls through the motherboard[BIOS/UEFI](https://www.tomshardware.com/reviews/bios-keys-to-access-your-firmware,5732.html) .

 The origins of Bryant's home-brewed Python cooling app started when he upgraded his personal system from a[Ryzen 7 3700X](https://www.tomshardware.com/reviews/ryzen-9-3900x-7-3700x-review,6214.html) to the much more potent[Ryzen 9 5950X](https://www.tomshardware.com/reviews/amd-ryzen-9-5950x-5900x-zen-3-review) . According to Bryant, the extra cores nearly doubled the heat output of his system, forcing his NZXT Kraken X53 240mm[AIO liquid cooler](https://www.tomshardware.com/best-picks/best-aio-coolers) to work much harder. Consequently, the CPU swap also made his cooler much louder to deal with the extra heat output. On top of this, the fans were also spinning up and down erratically, due to Zen 3's notoriously spiky thermal output.

 Bryant found that the Kraken's cooler is not optimized out of the box for Ryzen CPUs, causing the fans to spin up and down erratically. The Kraken's pump speed is based on liquid temperature, while the fans are based on the[CPU temperature](https://www.tomshardware.com/how-to/how-to-check-cpu-temp-temperature) , something Bryant found unattractive. (We've also complained about this[our own cooler reviews](https://www.tomshardware.com/pc-components/cooling/reviews) .)

 To fix this problem, Bryant decided to build his own cooling app that could eliminate the problem and give him more granular control over his pump and fan speeds. Additionally, he doesn't like how bloated traditional fan software normally is, giving him even more incentive to build his own app.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Cal Bryant's fan curve from his Python app](https://cdn.mos.cms.futurecdn.net/HLapN7zrv8kWaLCxAFnc93-320-80.png)

 (Image credit: Cal Bryant)

 In the end, he was able to create an application that can read the CPU, case, and liquid temperatures of the system, and adjust the CPU fan and pump speeds accordingly. The app was written in[Python](https://www.tomshardware.com/how-to/use-for-loops-in-python) and Liquidctl, a programmatic control system that can allow Python scripts to control liquid coolers such as the X53\. For temperature control, the app reads temperature data from Linux's built-in hardware sensor capabilities, known as lm-sensors. Bryant wrote his Python app in such a way that it can be installed as a system service that starts when the OS boots up and hides in the background. For the nitty-gritty details on how the app was written step-by-step, check out Bryant's[full article](https://calbryant.uk/blog/better-pc-cooling-with-python/) .

 The app was tuned to run the X53's pump in conjunction with the CPU's temperature output and run the radiator fans in conjunction with the coolant temperature. This is very different from the X53's default configuration where the pump RPM is driven by the coolant temperature.

 With this method of RPM control, he was able to significantly reduce the spiky nature of his cooler's default fan profile and make the cooler more performant only when needed. Having the pump speed up based on the CPU temperature allows the cooler to extract heat more quickly from the CPU. Coolant takes a long time to warm up under a heavy load compared to[air coolers](https://www.tomshardware.com/reviews/best-cpu-coolers,4181.html) . Having the fans connected to the coolant temperature, in turn, allows the cooler to only run the fans at a high RPM when the coolant is warm. In an AIO, the fans aren't cooling the[CPU](https://www.tomshardware.com/reviews/best-cpus,3986.html) , they are cooling down the liquid that is extracting heat from the CPU.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-uninterrupted-playback-capture/"><u>[New] 2024 Approved  Uninterrupted Playback Capture</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-address-chromes-problematic-facebook-vids/"><u>[New] Address Chrome's Problematic Facebook Vids</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-becoming-a-trendsetter-viral-tactics-for-fb-for-2024/"><u>[New] Becoming a Trendsetter  Viral Tactics for FB for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-in-picture-smoothing-techniques-for-better-photo-clarity/"><u>[Updated] In-Picture Smoothing Techniques for Better Photo Clarity</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-infusing-life-into-jujutsu-kaisen-with-tiktok-videos/"><u>[Updated] Infusing Life Into Jujutsu Kaisen with TikTok Videos</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-pioneering-6-networks-supporting-business-development-for-2024/"><u>[Updated] Pioneering 6 Networks Supporting Business Development for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-step-by-step-record-and-save-facebook-chats-effectively-for-2024/"><u>[Updated] Step-By-Step  Record and Save Facebook Chats Effectively for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/archive-awesome-perfecting-twitter-video-backups/"><u>Archive Awesome  Perfecting Twitter Video Backups</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/authoritative-top-picks-the-finest-mini-itx-enclosures-to-maximize-your-compact-pcs-potential/"><u>Authoritative Top Picks: The Finest Mini ITX Enclosures to Maximize Your Compact PC's Potential</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723125173289-beat-the-clock-and-save-big-get-your-thrifty-beginner-4k-resin-3d-printer-at-a-whopping-44-off-for-black-friday/"><u>Beat the Clock and Save Big - Get Your 'Thrifty Beginner 4K Resin' 3D Printer at a Whopping 44%% Off for Black Friday</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/bringing-high-tech-additive-fabrication-home-micronics-newly-released-desktop-form-factor-sls-printer-at-a-budget-of-2999/"><u>Bringing High-Tech Additive Fabrication Home: Micronics' Newly Released Desktop Form Factor SLS Printer at a Budget of $2,999</u></a></li>
<li><a href="https://buynow-help.techidaily.com/brookstone-photoshare-smart-frame-review/"><u>Brookstone Photoshare Smart Frame Review</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/cutting-edge-single-pass-3d-printing-unveils-operational-robotic-hand-advancing-the-dream-of-at-home-limb-fabrication/"><u>Cutting-Edge Single-Pass 3D Printing Unveils Operational Robotic Hand: Advancing the Dream of At-Home Limb Fabrication</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723175676802-discover-the-best-coolers-for-your-nvme-drives-in-depth-analysis-of-30-models-with-spotlight-on-id-cooling-m15-and-m05/"><u>Discover The Best Coolers for Your NVMe Drives: In-Depth Analysis Of 30 Models With Spotlight On ID-Cooling M15 & M05!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discover-the-best-deal-on-eleegoo-neptune-4-pro-3d-printer-unbeatable-price-of-240-at-newegg/"><u>Discover the Best Deal on Eleegoo Neptune 4 Pro 3D Printer: Unbeatable Price of $240 at Newegg!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/elevate-your-multi-core-setup-silverstones-xe360-dual-all-in-one-liquid-cooler-for-two-cpus-simultaneously/"><u>Elevate Your Multi-Core Setup: SilverStone's XE360-Dual All-in-One Liquid Cooler for Two CPUs Simultaneously</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-advice-on-pc-gear-with-toms-hardware-resource-hub/"><u>Expert Advice on PC Gear with Tom's Hardware Resource Hub</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-insights-on-gadgets-and-hardware-with-toms-analysis/"><u>Expert Insights on Gadgets and Hardware with Tom's Analysis</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-the-world-of-technology-with-toms-hardware-insights/"><u>Exploring the World of Technology with Tom's Hardware Insights</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-toms-gadget-world-in-depth-reviews-and-news/"><u>Exploring Tom's Gadget World: In-Depth Reviews and News</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-i-play-mkv-movies-on-huawei-nova-y71-by-aiseesoft-video-converter-play-mkv-on-android/"><u>How do I play MKV movies on Huawei Nova Y71?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-a-locked-realme-narzo-60x-5g-phone-by-drfone-android/"><u>How to Reset a Locked Realme Narzo 60x 5G Phone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-text-messages-from-lava-storm-5g-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Text Messages from Lava Storm 5G to New Phone | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-honor-x50i-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Honor X50i PC | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-vivo-y78plus-t1-editionmirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Vivo Y78+ (T1) EditionMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-how-to-estimate-income-from-youtube-video-snippets/"><u>In 2024, How to Estimate Income From YouTube Video Snippets</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-xiaomi-redmi-note-13-5g-phone-without-password-by-drfone-android/"><u>In 2024, How To Unlock Xiaomi Redmi Note 13 5G Phone Without Password?</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-perfecting-live-streams-selecting-top-5-recording-systems/"><u>In 2024, Perfecting Live Streams  Selecting Top 5 Recording Systems</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/introducing-the-innovative-caulk-gun-applicator-for-pink-thermal-gel-revolutionizing-heat-transfer-and-component-gaps/"><u>Introducing the Innovative Caulk-Gun Applicator for Pink Thermal Gel: Revolutionizing Heat Transfer & Component Gaps</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/major-customer-retractions-compel-asetek-to-discontinue-revenue-estimation-plans/"><u>Major Customer Retractions Compel Asetek To Discontinue Revenue Estimation Plans</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-the-world-of-tech-innovations-with-toms-hardware-insights/"><u>Navigating the World of Tech Innovations with Tom's Hardware Insights</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/new-study-finds-many-pc-watercoolers-fell-short-on-using-the-high-quality-materials-they-advertise-especially-copper/"><u>New Study Finds Many PC Watercoolers Fell Short on Using the High-Quality Materials They Advertise, Especially Copper</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/revolutionary-ultra-strong-microscopic-3d-metal-a-marvel-smaller-than-a-virus/"><u>Revolutionary Ultra-Strong, Microscopic 3D Metal: A Marvel Smaller than a Virus</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/surprising-discovery-repurposing-plastic-cutlery-for-efficient-and-effective-3d-printing-uses/"><u>Surprising Discovery: Repurposing Plastic Cutlery for Efficient and Effective 3D Printing Uses</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-guide-to-portable-screens-enhancing-your-gameplay-and-work-efficiency/"><u>The Ultimate Guide to Portable Screens : Enhancing Your Gameplay and Work Efficiency</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-review-the-ultimate-guide-to-hardware/"><u>Tom's Tech Review: The Ultimate Guide to Hardware</u></a></li>
</ul></div>
