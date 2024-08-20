---
title: Revolutionize Your Rig with Lamptron's Newest CPU Cooler - A Mega Screen Like the iPhone 15 for Ultra HD Secondary Monitor Functionality
date: 2024-08-19T03:06:24.404Z
updated: 2024-08-20T03:06:24.404Z
tags:
  - cooling
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/tTxVTejGJjFYkhpA5nZk7o-320-80.jpg
---

## Custom Python Script for a Quieter, Streamlined Experience with the NZXT Kraken AIO - Beat Fan Noise & Bulky Apps

Software designer Cal Bryant created a PC cooling app for his liquid-cooled Ryzen 9 5950X PC from scratch[using Python](https://calbryant.uk/blog/better-pc-cooling-with-python/#) . With his app, he was able to fine-tune his Kraken X53's pump and fan speed and run both a lot more efficiently, making the cooler run significantly quieter compared to running the fan controls through the motherboard[BIOS/UEFI](https://www.tomshardware.com/reviews/bios-keys-to-access-your-firmware,5732.html) .

 The origins of Bryant's home-brewed Python cooling app started when he upgraded his personal system from a[Ryzen 7 3700X](https://www.tomshardware.com/reviews/ryzen-9-3900x-7-3700x-review,6214.html) to the much more potent[Ryzen 9 5950X](https://www.tomshardware.com/reviews/amd-ryzen-9-5950x-5900x-zen-3-review) . According to Bryant, the extra cores nearly doubled the heat output of his system, forcing his NZXT Kraken X53 240mm[AIO liquid cooler](https://www.tomshardware.com/best-picks/best-aio-coolers) to work much harder. Consequently, the CPU swap also made his cooler much louder to deal with the extra heat output. On top of this, the fans were also spinning up and down erratically, due to Zen 3's notoriously spiky thermal output.

 Bryant found that the Kraken's cooler is not optimized out of the box for Ryzen CPUs, causing the fans to spin up and down erratically. The Kraken's pump speed is based on liquid temperature, while the fans are based on the[CPU temperature](https://www.tomshardware.com/how-to/how-to-check-cpu-temp-temperature) , something Bryant found unattractive. (We've also complained about this[our own cooler reviews](https://www.tomshardware.com/pc-components/cooling/reviews) .)

 To fix this problem, Bryant decided to build his own cooling app that could eliminate the problem and give him more granular control over his pump and fan speeds. Additionally, he doesn't like how bloated traditional fan software normally is, giving him even more incentive to build his own app.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
![Cal Bryant's fan curve from his Python app](https://cdn.mos.cms.futurecdn.net/HLapN7zrv8kWaLCxAFnc93-320-80.png)

 (Image credit: Cal Bryant)

 In the end, he was able to create an application that can read the CPU, case, and liquid temperatures of the system, and adjust the CPU fan and pump speeds accordingly. The app was written in[Python](https://www.tomshardware.com/how-to/use-for-loops-in-python) and Liquidctl, a programmatic control system that can allow Python scripts to control liquid coolers such as the X53\. For temperature control, the app reads temperature data from Linux's built-in hardware sensor capabilities, known as lm-sensors. Bryant wrote his Python app in such a way that it can be installed as a system service that starts when the OS boots up and hides in the background. For the nitty-gritty details on how the app was written step-by-step, check out Bryant's[full article](https://calbryant.uk/blog/better-pc-cooling-with-python/) .

 The app was tuned to run the X53's pump in conjunction with the CPU's temperature output and run the radiator fans in conjunction with the coolant temperature. This is very different from the X53's default configuration where the pump RPM is driven by the coolant temperature.

 With this method of RPM control, he was able to significantly reduce the spiky nature of his cooler's default fan profile and make the cooler more performant only when needed. Having the pump speed up based on the CPU temperature allows the cooler to extract heat more quickly from the CPU. Coolant takes a long time to warm up under a heavy load compared to[air coolers](https://www.tomshardware.com/reviews/best-cpu-coolers,4181.html) . Having the fans connected to the coolant temperature, in turn, allows the cooler to only run the fans at a high RPM when the coolant is warm. In an AIO, the fans aren't cooling the[CPU](https://www.tomshardware.com/reviews/best-cpus,3986.html) , they are cooling down the liquid that is extracting heat from the CPU.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-sunrise-to-starry-nights-top-animated-youtubers-for-daily-joy/"><u>[New] 2024 Approved  From Sunrise to Starry Nights - Top Animated YouTubers for Daily Joy</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-incorporating-time-features-into-youtube-video-formats/"><u>[New] In 2024, Incorporating Time Features Into YouTube Video Formats</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-innovative-ways-to-document-your-virtual-sessions-mac-and-pc-edition/"><u>[New] Innovative Ways to Document Your Virtual Sessions - Mac & PC Edition</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-erase-wisely-strategies-using-photoshops-eraser/"><u>[Updated] 2024 Approved  Erase Wisely  Strategies Using Photoshop's Eraser</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-interpreting-user-inactivity-could-it-be-a-blocked-status/"><u>[Updated] 2024 Approved  Interpreting User Inactivity  Could It Be a Blocked Status?</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-chroma-lens-reimagined-embracing-the-power-of-4k/"><u>[Updated] Chroma Lens Reimagined  Embracing the Power of 4K</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-optimizing-nintendo-switch-controller-for-steam-games/"><u>[Updated] In 2024, Optimizing Nintendo Switch Controller for Steam Games</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-learn-to-leverage-telegram-a-comprehensive-online-tutorial/"><u>[Updated] Learn to Leverage Telegram  A Comprehensive Online Tutorial</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-key-scenes-in-video-production/"><u>[Updated] Mastering Key Scenes in Video Production</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-best-of-editing-filmoras-captivating-features/"><u>[Updated] The Best of Editing  Filmora's Captivating Features</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-privacy-prowess-how-to-disconnect-on-insta/"><u>2024 Approved  Privacy Prowess  How to Disconnect on Insta</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/arctics-liquid-freezer-iii-potential-impact-on-intel-cpus-and-warranty-concerns-need-specialized-contact-frame/"><u>Arctic's 'Liquid Freezer III': Potential Impact on Intel CPUs and Warranty Concerns – Need Specialized Contact Frame?</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/best-selling-resin-3d-printing-devices-2024-edition/"><u>Best Selling Resin 3D Printing Devices - 2024 Edition</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/best-value-3d-printers-on-the-market-a-comprehensive-look-at-fdm-resin-and-budget-models/"><u>Best Value 3D Printers on the Market : A Comprehensive Look at FDM, Resin and Budget Models</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/beyond-bits-and-bytes-innovative-tech-insights-from-toms-realm/"><u>Beyond Bits & Bytes - Innovative Tech Insights From Tom's Realm</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discover-the-best-gaming-and-professional-monitors-available/"><u>Discover the Best Gaming & Professional Monitors Available</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discover-top-notch-electronics-with-toms-tech-treasures/"><u>Discover Top-Notch Electronics with Tom's Tech Treasures</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/diy-enthusiast-crafts-liquid-nitrogen-using-common-fridge-parts/"><u>DIY Enthusiast Crafts Liquid Nitrogen Using Common Fridge Parts</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/elevating-your-instagram-experience-through-smart-archiving-for-2024/"><u>Elevating Your Instagram Experience Through Smart Archiving for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/elite-gaming-monitors-comparison-optimizing-your-play-on-ps5-xbox-series-x-and-s/"><u>Elite Gaming Monitors Comparison: Optimizing Your Play on PS5, Xbox Series X, & S</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exclusive-look-inside-the-ultimate-bambu-lab-mattress-for-double-sized-dreaming/"><u>Exclusive Look Inside the Ultimate Bambu Lab Mattress for Double-Sized Dreaming</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/experience-cooler-performance-with-grizzlys-latest-heatspreader-15c-drop-in-cpu-temps-achieved/"><u>Experience Cooler Performance with Grizzly's Latest Heatspreader: 15°C Drop in CPU Temps Achieved!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/experience-revolutionary-scanning-with-3dmakerpros-mole-3d-scanner-a-comprehensive-examination/"><u>Experience Revolutionary Scanning with 3DMakerPro's Mole 3D Scanner - A Comprehensive Examination</u></a></li>
<li><a href="https://some-techniques.techidaily.com/explore-10-websites-for-unlicensed-gaming-tunes-for-2024/"><u>Explore 10 Websites for Unlicensed Gaming Tunes for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-technology-with-toms-hardware-hub-your-source-for-cutting-edge-insights/"><u>Exploring Technology with Tom's Hardware Hub – Your Source for Cutting-Edge Insights</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-toms-tech-insights-in-depth-reviews-and-gadget-analysis/"><u>Exploring Tom's Tech Insights: In-Depth Reviews and Gadget Analysis</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/filmora-promo-codes-2024-your-ultimate-guide-to-savings/"><u>Filmora Promo Codes 2024 Your Ultimate Guide to Savings</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/from-idea-to-indulgence-exploring-the-world-of-diy-chocolate-designs-with-the-cocoa-press-printer/"><u>From Idea to Indulgence: Exploring the World of DIY Chocolate Designs with the Cocoa Press Printer</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/gadget-guide-toms-detailed-evaluations/"><u>Gadget Guide - Tom's Detailed Evaluations</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/go-underwater-without-compromise-discover-the-unveiling-of-frores-waterproof-fanless-sport-cooling-device-with-advanced-active-technology/"><u>Go Underwater Without Compromise: Discover the Unveiling of Frore’s Waterproof, Fanless Sport Cooling Device with Advanced Active Technology</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-frp-on-xiaomi-13-ultra-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass FRP on Xiaomi 13 Ultra</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-find-ispoofer-pro-activation-key-on-apple-iphone-13-mini-drfone-by-drfone-virtual-ios/"><u>How to Find iSpoofer Pro Activation Key On Apple iPhone 13 mini? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/how-to-use-zoom-for-skype-easy-solutions/"><u>How to Use Zoom for Skype [Easy Solutions]</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-transform-your-gopro-footage-mac-video-editing-essentials/"><u>In 2024, Transform Your GoPro Footage Mac Video Editing Essentials</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/innovative-and-functional-raspberry-pi-cases-of-2hren2024/"><u>Innovative and Functional Raspberry Pi Cases of 2Hren2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/innovative-heat-dissipation-pink-aroma-and-berry-fragrance-elevate-extreme-mugurisus-4g-strawberry-edition-beyond-thermal-grizzly/"><u>Innovative Heat Dissipation: Pink Aroma and Berry Fragrance Elevate Extreme Mugurisu's 4G Strawberry Edition Beyond Thermal Grizzly</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/inside-look-at-new-electronics-tips-reviews-and-tech-news-from-tom/"><u>Inside Look at New Electronics: Tips, Reviews & Tech News From Tom</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/inside-the-world-of-tech-expert-insights-at-toms-hardware/"><u>Inside the World of Tech: Expert Insights at Tom's Hardware</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/instagram-photo-and-video-size-adjustment-guide-for-2024/"><u>Instagram Photo and Video Size Adjustment Guide for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/introducing-the-miniature-marvel-of-additive-manufacturing-a-coin-sized-3d-printer-using-cutting-edge-silicon-technology-no-moving-parts/"><u>Introducing the Miniature Marvel of Additive Manufacturing: A Coin-Sized 3D Printer Using Cutting-Edge Silicon Technology, No Moving Parts!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-computer-gadgets-with-advice-from-toms-experts/"><u>Mastering Computer Gadgets with Advice From Tom's Experts</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-gadgets-with-toms-hardware-expertise/"><u>Mastering Gadgets with Tom's Hardware Expertise</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-nvme-thermal-management-why-teamgroups-t-force-dark-airflow-i-is-a-must-have-cooler/"><u>Mastering NVMe Thermal Management: Why TeamGroup's T-Force Dark AirFlow I Is a Must-Have Cooler</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/noctuas-newest-lineup-meet-the-home-series-spotlight-on-the-exceptional-100-nv-fs1-desk-cooler/"><u>Noctua's Newest Lineup: Meet the Home Series - Spotlight on the Exceptional $100 NV-FS1 Desk Cooler</u></a></li>
<li><a href="https://extra-resources.techidaily.com/optimal-drone-cameras-film-and-snapshot-heroes-10/"><u>Optimal Drone Cameras  Film & Snapshot Heroes #10</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/quick-fix-tweeter-conversion-for-social-sharing-for-2024/"><u>Quick-Fix Tweeter Conversion for Social Sharing for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-art-of-accompanying-visual-content-with-music-for-2024/"><u>The Art of Accompanying Visual Content with Music for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unseen-linguist-how-gpt-deciphers-human-communication/"><u>Unseen Linguist: How GPT Deciphers Human Communication</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-secrets-of-hardware-with-tom-the-expert-insight/"><u>Unveiling the Secrets of Hardware with Tom - The Expert Insight</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/what-does-jailbreaking-apple-iphone-11-pro-i-do-get-answers-here-by-drfone-ios/"><u>What Does Jailbreaking Apple iPhone 11 Pro i Do? Get Answers here</u></a></li>
</ul></div>
