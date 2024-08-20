---
title: Unveiling the Latest with Tom's PC & Hardware Expertise
date: 2024-08-19T03:22:45.897Z
updated: 2024-08-20T03:22:45.897Z
tags:
  - cooling
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/UDbziUwtN3KVN4zhuUpjTe-320-80.jpg
---

## Custom Python Script for a Quieter, Streamlined Experience with the NZXT Kraken AIO - Beat Fan Noise & Bulky Apps

Software designer Cal Bryant created a PC cooling app for his liquid-cooled Ryzen 9 5950X PC from scratch[using Python](https://calbryant.uk/blog/better-pc-cooling-with-python/#) . With his app, he was able to fine-tune his Kraken X53's pump and fan speed and run both a lot more efficiently, making the cooler run significantly quieter compared to running the fan controls through the motherboard[BIOS/UEFI](https://www.tomshardware.com/reviews/bios-keys-to-access-your-firmware,5732.html) .

 The origins of Bryant's home-brewed Python cooling app started when he upgraded his personal system from a[Ryzen 7 3700X](https://www.tomshardware.com/reviews/ryzen-9-3900x-7-3700x-review,6214.html) to the much more potent[Ryzen 9 5950X](https://www.tomshardware.com/reviews/amd-ryzen-9-5950x-5900x-zen-3-review) . According to Bryant, the extra cores nearly doubled the heat output of his system, forcing his NZXT Kraken X53 240mm[AIO liquid cooler](https://www.tomshardware.com/best-picks/best-aio-coolers) to work much harder. Consequently, the CPU swap also made his cooler much louder to deal with the extra heat output. On top of this, the fans were also spinning up and down erratically, due to Zen 3's notoriously spiky thermal output.

 Bryant found that the Kraken's cooler is not optimized out of the box for Ryzen CPUs, causing the fans to spin up and down erratically. The Kraken's pump speed is based on liquid temperature, while the fans are based on the[CPU temperature](https://www.tomshardware.com/how-to/how-to-check-cpu-temp-temperature) , something Bryant found unattractive. (We've also complained about this[our own cooler reviews](https://www.tomshardware.com/pc-components/cooling/reviews) .)

 To fix this problem, Bryant decided to build his own cooling app that could eliminate the problem and give him more granular control over his pump and fan speeds. Additionally, he doesn't like how bloated traditional fan software normally is, giving him even more incentive to build his own app.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![Cal Bryant's fan curve from his Python app](https://cdn.mos.cms.futurecdn.net/HLapN7zrv8kWaLCxAFnc93-320-80.png)

 (Image credit: Cal Bryant)

 In the end, he was able to create an application that can read the CPU, case, and liquid temperatures of the system, and adjust the CPU fan and pump speeds accordingly. The app was written in[Python](https://www.tomshardware.com/how-to/use-for-loops-in-python) and Liquidctl, a programmatic control system that can allow Python scripts to control liquid coolers such as the X53\. For temperature control, the app reads temperature data from Linux's built-in hardware sensor capabilities, known as lm-sensors. Bryant wrote his Python app in such a way that it can be installed as a system service that starts when the OS boots up and hides in the background. For the nitty-gritty details on how the app was written step-by-step, check out Bryant's[full article](https://calbryant.uk/blog/better-pc-cooling-with-python/) .

 The app was tuned to run the X53's pump in conjunction with the CPU's temperature output and run the radiator fans in conjunction with the coolant temperature. This is very different from the X53's default configuration where the pump RPM is driven by the coolant temperature.

 With this method of RPM control, he was able to significantly reduce the spiky nature of his cooler's default fan profile and make the cooler more performant only when needed. Having the pump speed up based on the CPU temperature allows the cooler to extract heat more quickly from the CPU. Coolant takes a long time to warm up under a heavy load compared to[air coolers](https://www.tomshardware.com/reviews/best-cpu-coolers,4181.html) . Having the fans connected to the coolant temperature, in turn, allows the cooler to only run the fans at a high RPM when the coolant is warm. In an AIO, the fans aren't cooling the[CPU](https://www.tomshardware.com/reviews/best-cpus,3986.html) , they are cooling down the liquid that is extracting heat from the CPU.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-helps.techidaily.com/new-android-and-lightroom-review-a-full-examination-for-2024/"><u>[New] Android & Lightroom Review  A Full Examination for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-chromebooks-premium-free-video-capture-extensions-for-2024/"><u>[New] Chromebook's Premium Free Video Capture Extensions for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-best-hidden-downloaders-1-8-unveiled/"><u>[New] In 2024, Best Hidden Downloaders - #1-8 Unveiled</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-the-ultimate-guide-to-audio-integration-on-reels/"><u>[New] The Ultimate Guide to Audio Integration on Reels</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-audiorecorder-inspection/"><u>[Updated] Audiorecorder Inspection</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-hilarious-highlights-reddit-and-twitters-best-bits-for-2024/"><u>[Updated] Hilarious Highlights  Reddit and Twitter's Best Bits for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-how-to-engage-fans-through-real-time-streams-mobile-edition/"><u>[Updated] In 2024, How to Engage Fans Through Real-Time Streams  Mobile Edition</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-premier-text-motion-manuals/"><u>[Updated] Premier Text Motion Manuals</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-seamless-manipulation-of-iphone-magnification/"><u>[Updated] Seamless Manipulation of iPhone Magnification</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/addressing-freeze-during-facebook-live-events-for-2024/"><u>Addressing Freeze During Facebook Live Events for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/advanced-gadget-guidance-by-toms-electronics-mastery/"><u>Advanced Gadget Guidance by Tom's Electronics Mastery</u></a></li>
<li><a href="https://article-files.techidaily.com/becoming-a-leader-in-the-world-of-design-work-for-2024/"><u>Becoming a Leader in the World of Design Work for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/decoding-electronics-with-tom-the-ultimate-hardware-hub/"><u>Decoding Electronics with Tom: The Ultimate Hardware Hub</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discover-advanced-tech-insights-at-toms-hardware-expert-reviews-and-comparisons/"><u>Discover Advanced Tech Insights at Tom's Hardware: Expert Reviews and Comparisons</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discovering-superior-case-options-for-your-raspberry-pi-top-picks/"><u>Discovering Superior Case Options for Your Raspberry Pi - Top Picks</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ekwb-officially-apologizes-for-late-payouts-commits-to-improved-practices/"><u>EKWB Officially Apologizes for Late Payouts: Commits to Improved Practices</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/elite-picks-for-ultraportable-computers-a-comprehensive-review/"><u>Elite Picks for Ultraportable Computers : A Comprehensive Review</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/elite-selection-of-high-speed-microsd-cards-for-seamless-raspberry-pi-use-in-2eplust-year/"><u>Elite Selection of High-Speed MicroSD Cards for Seamless Raspberry Pi Use in 2E+t Year</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723125175149-exclusive-deal-on-high-quality-black-tpu-filament-save-big-at-just-16-per-kilo/"><u>Exclusive Deal on High-Quality Black TPU Filament – Save Big at Just $16 Per Kilo</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-advice-how-to-transform-sketches-into-beautiful-lithophanes-using-a-3d-printer/"><u>Expert Advice: How to Transform Sketches Into Beautiful Lithophanes Using a 3D Printer</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-analysis-by-tom-on-cutting-edge-devices/"><u>Expert Analysis by Tom on Cutting-Edge Devices</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-hardware-horizons-innovative-findings-from-the-toms-technology-review-platform/"><u>Expert Hardware Horizons: Innovative Findings From The Tom's Technology Review Platform</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/expert-video-editing-on-mac-the-power-of-adobe-premiere-pro/"><u>Expert Video Editing on Mac The Power of Adobe Premiere Pro</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/explore-comprehensive-hardware-guides-with-toms-hardware/"><u>Explore Comprehensive Hardware Guides with Tom's Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-advanced-gadgets-with-toms-hardware-insights/"><u>Exploring Advanced Gadgets with Tom's Hardware Insights</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-the-latest-in-technology-with-toms-hardware-guides/"><u>Exploring the Latest in Technology with Tom's Hardware Guides</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/fire-ant-infestation-found-inside-gaming-pc-a-look-at-creepy-video-evidence/"><u>Fire Ant Infestation Found Inside Gaming PC: A Look at Creepy Video Evidence</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/future-proof-your-gameplay-the-top-rated-wireless-gaming-headsets-for-enhanced-audio-and-convenience/"><u>Future-Proof Your Gameplay: The Top Rated Wireless Gaming Headsets for Enhanced Audio & Convenience</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/get-ready-for-the-k1c-creality-shares-exciting-launch-date-price-tag-and-full-technical-specifications/"><u>Get Ready for the K1C: Creality Shares Exciting Launch Date, Price Tag & Full Technical Specifications!</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-bypass-iphone-15-pro-passcode-easily-video-inside-drfone-by-drfone-ios/"><u>How to Bypass iPhone 15 Pro Passcode Easily Video Inside | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/how-to-restart-and-reset-bluetooth-driver-on-windows-1111/"><u>How to Restart and Reset Bluetooth Driver on Windows 11/11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-vivo-y100-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Vivo Y100 Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-3utools-virtual-location-not-working-on-oneplus-ace-3-fix-now-drfone-by-drfone-virtual-android/"><u>In 2024, 3uTools Virtual Location Not Working On OnePlus Ace 3? Fix Now | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-best-8-streamers-pick-high-end-cameras-reviewed/"><u>In 2024, Best 8 Streamer's Pick  High-End Cameras Reviewed</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-show-wi-fi-password-on-oppo-a78-5g-by-drfone-android/"><u>In 2024, How to Show Wi-Fi Password on Oppo A78 5G</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/inside-toms-electronics-emporium-your-source-for-gear-reviews-and-news/"><u>Inside Tom's Electronics Emporium: Your Source for Gear Reviews and News</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/keep-your-temperature-right-with-arctics-superior-liquid-freezer-ii-aio-cooler-for-a-steal-at-just-74/"><u>Keep Your Temperature Right with Arctic's Superior Liquid Freezer II AIO Cooler for a Steal at Just $74!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/latest-geforce-rtx-770-driver-downloads-compatible-with-windows-pcs/"><u>Latest GeForce RTX 770 Driver Downloads Compatible with Windows PCs</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723175681761-maximize-speed-with-corsairs-innovative-single-twist-pc-fan-screw-build-your-rig-in-record-time/"><u>Maximize Speed with Corsair's Innovative Single-Twist PC Fan Screw - Build Your Rig in Record Time!</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-music-from-tecno-spark-go-2024-by-fonelab-android-recover-music/"><u>Possible solutions to restore deleted music from Tecno Spark Go (2024)</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-guide-to-computer-components-by-toms-hardware/"><u>The Ultimate Guide to Computer Components - By Tom's Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-guide-to-selecting-quality-hardware-wisdom-from-toms-tech-library/"><u>The Ultimate Guide to Selecting Quality Hardware – Wisdom From Tom's Tech Library</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-hub-expert-reviews-and-insights/"><u>Tom's Tech Hub: Expert Reviews & Insights</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-insights-unveiling-the-latest-in-computer-hardware/"><u>Tom's Tech Insights: Unveiling the Latest in Computer Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-review-expert-insights-and-comprehensive-gadget-testing/"><u>Tom's Tech Review: Expert Insights and Comprehensive Gadget Testing</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-review-expert-insights-into-hardware/"><u>Tom's Tech Review: Expert Insights Into Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-review-in-depth-gadget-analysis/"><u>Tom's Tech Review: In-Depth Gadget Analysis</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-comprehensive-computer-hardware-insights/"><u>Tom's Tech: Comprehensive Computer Hardware Insights</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/top-10-globally-acclaimed-video-sensations-on-youtube-for-2024/"><u>Top 10 Globally Acclaimed Video Sensations on YouTube for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-2024-raspberry-pi-pico-extensions-and-enhancements/"><u>Top 2024 Raspberry Pi Pico Extensions & Enhancements</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-picks-for-best-and-fastest-gan-powered-usb-c-laptop-chargers/"><u>Top Picks for Best and Fastest GaN Powered USB-C Laptop Chargers</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/trustworthy-hardware-analysis-and-comparisons-toms-hardware-insights/"><u>Trustworthy Hardware Analysis and Comparisons - Tom's Hardware Insights</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ultimate-guide-to-choosing-a-game-masters-monitor-budget-friendly-curved-and-g-sync-technology/"><u>Ultimate Guide to Choosing a Game Master's Monitor : Budget-Friendly, Curved, and G-Sync Technology</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ultimate-selection-best-raspberry-pi-protectors/"><u>Ultimate Selection: Best Raspberry Pi Protectors</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ultimate-selection-the-best-laser-etching-devices/"><u>Ultimate Selection: The Best Laser Etching Devices</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-a-breakthrough-in-3d-printing-the-worlds-first-chip-based-device-that-fits-in-your-pocket-with-zero-motion-components/"><u>Unveiling a Breakthrough in 3D Printing: The World’s First Chip-Based Device That Fits in Your Pocket with Zero Motion Components</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-computer-secrets-at-toms-hardware-fortress/"><u>Unveiling Computer Secrets at Tom's Hardware Fortress</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-gadgets-with-toms-computer-and-electronics/"><u>Unveiling Gadgets with Tom's Computer & Electronics</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-superior-strength-miniature-3d-printed-metal-surpasses-size-of-viruses/"><u>Unveiling Superior Strength: Miniature 3D-Printed Metal Surpasses Size of Viruses</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-latest-in-tech-toms-hardware-deep-dive/"><u>Unveiling the Latest in Tech – Tom's Hardware Deep-Dive</u></a></li>
</ul></div>
