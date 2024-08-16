---
title: The Ultimate Guide to Hardware by Tom - Informed Choices Await!
date: 2024-08-15T06:12:36.223Z
updated: 2024-08-16T06:12:36.223Z
tags:
  - cooling
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/9DwbhNCSEmuv6msMmxack4-320-80.jpg
---

## Custom Python Script for a Quieter, Streamlined Experience with the NZXT Kraken AIO - Beat Fan Noise & Bulky Apps

Software designer Cal Bryant created a PC cooling app for his liquid-cooled Ryzen 9 5950X PC from scratch[using Python](https://calbryant.uk/blog/better-pc-cooling-with-python/#) . With his app, he was able to fine-tune his Kraken X53's pump and fan speed and run both a lot more efficiently, making the cooler run significantly quieter compared to running the fan controls through the motherboard[BIOS/UEFI](https://www.tomshardware.com/reviews/bios-keys-to-access-your-firmware,5732.html) .

 The origins of Bryant's home-brewed Python cooling app started when he upgraded his personal system from a[Ryzen 7 3700X](https://www.tomshardware.com/reviews/ryzen-9-3900x-7-3700x-review,6214.html) to the much more potent[Ryzen 9 5950X](https://www.tomshardware.com/reviews/amd-ryzen-9-5950x-5900x-zen-3-review) . According to Bryant, the extra cores nearly doubled the heat output of his system, forcing his NZXT Kraken X53 240mm[AIO liquid cooler](https://www.tomshardware.com/best-picks/best-aio-coolers) to work much harder. Consequently, the CPU swap also made his cooler much louder to deal with the extra heat output. On top of this, the fans were also spinning up and down erratically, due to Zen 3's notoriously spiky thermal output.

 Bryant found that the Kraken's cooler is not optimized out of the box for Ryzen CPUs, causing the fans to spin up and down erratically. The Kraken's pump speed is based on liquid temperature, while the fans are based on the[CPU temperature](https://www.tomshardware.com/how-to/how-to-check-cpu-temp-temperature) , something Bryant found unattractive. (We've also complained about this[our own cooler reviews](https://www.tomshardware.com/pc-components/cooling/reviews) .)

 To fix this problem, Bryant decided to build his own cooling app that could eliminate the problem and give him more granular control over his pump and fan speeds. Additionally, he doesn't like how bloated traditional fan software normally is, giving him even more incentive to build his own app.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
![Cal Bryant's fan curve from his Python app](https://cdn.mos.cms.futurecdn.net/HLapN7zrv8kWaLCxAFnc93-320-80.png)

 (Image credit: Cal Bryant)

 In the end, he was able to create an application that can read the CPU, case, and liquid temperatures of the system, and adjust the CPU fan and pump speeds accordingly. The app was written in[Python](https://www.tomshardware.com/how-to/use-for-loops-in-python) and Liquidctl, a programmatic control system that can allow Python scripts to control liquid coolers such as the X53\. For temperature control, the app reads temperature data from Linux's built-in hardware sensor capabilities, known as lm-sensors. Bryant wrote his Python app in such a way that it can be installed as a system service that starts when the OS boots up and hides in the background. For the nitty-gritty details on how the app was written step-by-step, check out Bryant's[full article](https://calbryant.uk/blog/better-pc-cooling-with-python/) .

 The app was tuned to run the X53's pump in conjunction with the CPU's temperature output and run the radiator fans in conjunction with the coolant temperature. This is very different from the X53's default configuration where the pump RPM is driven by the coolant temperature.

 With this method of RPM control, he was able to significantly reduce the spiky nature of his cooler's default fan profile and make the cooler more performant only when needed. Having the pump speed up based on the CPU temperature allows the cooler to extract heat more quickly from the CPU. Coolant takes a long time to warm up under a heavy load compared to[air coolers](https://www.tomshardware.com/reviews/best-cpu-coolers,4181.html) . Having the fans connected to the coolant temperature, in turn, allows the cooler to only run the fans at a high RPM when the coolant is warm. In an AIO, the fans aren't cooling the[CPU](https://www.tomshardware.com/reviews/best-cpus,3986.html) , they are cooling down the liquid that is extracting heat from the CPU.

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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-accelerate-audience-engagement-with-high-impact-hash-tags/"><u>[New] 2024 Approved  Accelerate Audience Engagement with High-Impact Hash Tags</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-adding-subtitles-a-step-by-step-youtube-video-approach-for-2024/"><u>[New] Adding Subtitles  A Step-by-Step YouTube Video Approach for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-elevate-to-success-top-hashtags-for-6-figure-views-on-youtube/"><u>[New] Elevate to Success  Top Hashtags for 6-Figure Views on YouTube</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-enhance-ipad-recording-simpler-approaches-revealed/"><u>[New] Enhance iPad Recording  Simpler Approaches Revealed</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-finding-the-right-wordmark-for-your-personalized-tiktok-stream-for-2024/"><u>[New] Finding the Right Wordmark for Your Personalized TikTok Stream for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-dial-back-your-playlist-quick-steps-to-reverse-order/"><u>[New] In 2024, Dial Back Your Playlist  Quick Steps to Reverse Order</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-streaming-mastery-zoom-plus-fb-live-tactics/"><u>[New] Streaming Mastery  ZOOM + FB Live Tactics</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-elite-environmentally-friendly-cinematography-tech-for-2024/"><u>[Updated] Elite Environmentally Friendly Cinematography Tech for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-cross-posting-strategies-sharing-tiktok-on-your-facebook-feed/"><u>[Updated] In 2024, Cross-Posting Strategies  Sharing TikTok on Your Facebook Feed</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-expert-tips-extracting-audio-from-youtube-video-playback/"><u>[Updated] In 2024, Expert Tips  Extracting Audio From YouTube Video Playback</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-professional-pathway-setting-up-wm6/"><u>[Updated] In 2024, Professional Pathway  Setting Up WM6</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-the-ultimate-guide-upgrade-your-fb-videos-with-hd-mp4-format-forfree/"><u>[Updated] The Ultimate Guide  Upgrade Your FB Videos with HD MP4 Format – Forfree</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-pick-the-perfect-video-youtube-vs-tiktok/"><u>2024 Approved  Pick the Perfect Video  YouTube Vs. TikTok</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-voice-logger-essentials-the-best-speech-apps-for-mac-devices/"><u>2024 Approved  Voice Logger Essentials  The Best Speech Apps for Mac Devices</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/advanced-data-protection-made-simple-storing-sensitive-information-in-common-plastic-with-3d-printed-holographic-tech/"><u>Advanced Data Protection Made Simple - Storing Sensitive Information in Common Plastic with 3D Printed Holographic Tech</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/arctic-liquid-freezer-iii-cooling-units-and-their-effect-on-cpu-warranties-is-a-tailored-contact-frame-necessary-for-intel/"><u>Arctic 'Liquid Freezer III' Cooling Units and Their Effect on CPU Warranties – Is a Tailored Contact Frame Necessary for Intel?</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/best-low-cost-mechanical-keyboard-options/"><u>Best Low-Cost Mechanical Keyboard Options</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/budget-friendly-3d-creation-strategies-for-calculating-and-reducing-your-printers-price-tag/"><u>Budget-Friendly 3D Creation: Strategies for Calculating and Reducing Your Printer's Price Tag</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/complete-setup-of-wacom-graphics-tablets-for-pcs-running-windows-1087-download-drivers-and-enhance-digital-creativity/"><u>Complete Setup of Wacom Graphics Tablets for PCs Running Windows 10/8/7, Download Drivers & Enhance Digital Creativity</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discover-the-latest-in-tech-at-your-site-name-your-one-stop-resource-like-toms-hardware/"><u>Discover the Latest in Tech at [Your Site Name]: Your One-Stop Resource Like Tom's Hardware!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/dive-into-hardware-with-tom-top-reviews-and-guides/"><u>Dive Into Hardware with Tom: Top Reviews & Guides</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ek-unveils-advanced-custom-water-block-technology-to-keep-your-delidded-amd-ryzen-am5-at-peak-temperatures/"><u>EK Unveils Advanced Custom Water Block Technology to Keep Your Delidded AMD Ryzen AM5 at Peak Temperatures</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/elevating-your-rest-the-thoroughly-tested-guide-to-the-bamboo-lab-a1-slide-bed-for-an-immaculate-king-size-experience/"><u>Elevating Your Rest: The Thoroughly Tested Guide to the Bamboo Lab A1 Slide Bed for an Immaculate King-Size Experience</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/enhance-overclocking-potential-with-cooler-masters-innovative-colored-ai-nano-diamond-technology-in-cryofuze-5-paste/"><u>Enhance Overclocking Potential with Cooler Master's Innovative Colored AI Nano-Diamond Technology in CryoFuze 5 Paste</u></a></li>
<li><a href="https://win-solutions.techidaily.com/error-leaf-resolved-optimize-your-apex-legends-experience-with-2022-fixes/"><u>Error Leaf Resolved: Optimize Your Apex Legends Experience with 2022 Fixes</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-advice-on-computing-equipment-from-toms-hardware-hub/"><u>Expert Advice on Computing Equipment From Tom's Hardware Hub</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-hardware-analysis-by-toms-technology-hub/"><u>Expert Hardware Analysis by Tom's Technology Hub</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-digital-tools-with-tom-your-guide-to-top-tier-electronics/"><u>Exploring Digital Tools with Tom - Your Guide to Top-Tier Electronics</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-value-for-money-cpus-in-depth-tutorial-and-ranking-hardware-central/"><u>Exploring Value for Money CPUs : In-Depth Tutorial and Ranking - Hardware Central</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/gamers-computer-ravaged-by-fire-ants-feasting-on-thermal-pad-see-the-unexpected-infestation/"><u>Gamer's Computer Ravaged by Fire Ants Feasting on Thermal Pad - See the Unexpected Infestation</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/gaming-gpu-reviews-2024-most-cost-effective-graphics-cards-ranked-for-optimal-playing-experience/"><u>Gaming GPU Reviews 2024 - Most Cost-Effective Graphics Cards Ranked for Optimal Playing Experience</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/get-quality-refreshment-the-top-value-pick-thermalright-phantom-spirit-120-se-for-just-35/"><u>Get Quality Refreshment: The Top Value Pick - Thermalright Phantom Spirit 120 SE for Just $35</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723125191106-get-your-hands-on-the-highest-ranked-eleegoo-neptune-4-pro-3d-printer-for-a-steal-at-240-from-newegg/"><u>Get Your Hands on the Highest-Ranked Eleegoo Neptune 4 Pro 3D Printer for a Steal at $240 From Newegg</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/how-to-change-voice-on-snapchat-with-2-easy-methods-for-2024/"><u>How to Change Voice on Snapchat with 2 Easy Methods for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-delete-icloud-account-on-apple-iphone-xr-without-password-by-drfone-ios/"><u>How to Delete iCloud Account On Apple iPhone XR without Password?</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-realme-c67-4g-drfone-by-drfone-virtual-android/"><u>How to get the dragon scale and evolution-enabled pokemon On Realme C67 4G? | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/immediate-screenshot-on-a-mac/"><u>Immediate Screenshot on a MAC</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-change-location-on-yik-yak-for-your-poco-x6-pro-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>In 2024, Change Location on Yik Yak For your Poco X6 Pro to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-everything-you-need-to-know-about-unlocked-apple-iphone-14-pro-max-drfone-by-drfone-ios/"><u>In 2024, Everything You Need To Know About Unlocked Apple iPhone 14 Pro Max | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/inside-the-mindset-of-a-photographer-polarrs-editing-techniques-for-2024/"><u>Inside the Mindset of a Photographer  Polarr’s Editing Techniques for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723175708186-inside-the-world-of-high-performance-testing-results-for-top-m2-ssd-heatsinks-featuring-id-cooling-zero-series-reviewed/"><u>Inside the World of High-Performance: Testing Results for Top M.2 SSD Heatsinks, Featuring ID-Cooling Zero Series Reviewed!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723125171105-master-the-art-of-3d-printing-with-the-powerful-anycubic-kobra-max-expert-review-inside/"><u>Master the Art of 3D Printing with the Powerful Anycubic Kobra Max - Expert Review Inside!</u></a></li>
<li><a href="https://extra-information.techidaily.com/pro-hdr-image-creation-with-photoshop-secrets/"><u>Pro HDR Image Creation with Photoshop Secrets</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-toms-hardware-reviews-and-in-depth-guides/"><u>Top Tom's Hardware Reviews and In-Depth Guides</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ultimate-list-leading-resin-3d-printers/"><u>Ultimate List: Leading Resin 3D Printers</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723175648404-unbeatable-deal-on-the-top-value-choice-thermalright-phantom-spirit-120-se-for-just-35/"><u>Unbeatable Deal on The Top Value Choice: Thermalright Phantom Spirit 120 SE for Just $35</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unlocking-pc-potential-lessons-from-toms-hardware-reviews/"><u>Unlocking PC Potential: Lessons From Tom's Hardware Reviews</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-pc-innovations-at-toms-electronic-showcase/"><u>Unveiling PC Innovations at Tom's Electronic Showcase</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-creality-ender-v3-a-budget-friendly-open-source-additive-manufacturing-marvel/"><u>Unveiling the Creality Ender 지오 V3: A Budget-Friendly Open Source Additive Manufacturing Marvel</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-latest-in-tech-insights-from-toms-hardware/"><u>Unveiling the Latest in Tech - Insights From Tom's Hardware</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/youtube-music-reactions-years-top-ten-showcase-for-2024/"><u>YouTube Music Reactions  Year's Top Ten Showcase for 2024</u></a></li>
</ul></div>
