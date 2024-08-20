---
title: "Unraveling Tech Secrets: Expert Advice From Tom's Workshop"
date: 2024-08-19T03:23:29.706Z
updated: 2024-08-20T03:23:29.706Z
tags:
  - cooling
categories:
  - hardware
thumbnail: https://thmb.techidaily.com/e05f2d33f2fefb8dc7c06028c76750542668dde0166f66e5a57d5c818d2809aa.jpg
---

## Custom Python Script for a Quieter, Streamlined Experience with the NZXT Kraken AIO - Beat Fan Noise & Bulky Apps

Software designer Cal Bryant created a PC cooling app for his liquid-cooled Ryzen 9 5950X PC from scratch[using Python](https://calbryant.uk/blog/better-pc-cooling-with-python/#) . With his app, he was able to fine-tune his Kraken X53's pump and fan speed and run both a lot more efficiently, making the cooler run significantly quieter compared to running the fan controls through the motherboard[BIOS/UEFI](https://www.tomshardware.com/reviews/bios-keys-to-access-your-firmware,5732.html) .

 The origins of Bryant's home-brewed Python cooling app started when he upgraded his personal system from a[Ryzen 7 3700X](https://www.tomshardware.com/reviews/ryzen-9-3900x-7-3700x-review,6214.html) to the much more potent[Ryzen 9 5950X](https://www.tomshardware.com/reviews/amd-ryzen-9-5950x-5900x-zen-3-review) . According to Bryant, the extra cores nearly doubled the heat output of his system, forcing his NZXT Kraken X53 240mm[AIO liquid cooler](https://www.tomshardware.com/best-picks/best-aio-coolers) to work much harder. Consequently, the CPU swap also made his cooler much louder to deal with the extra heat output. On top of this, the fans were also spinning up and down erratically, due to Zen 3's notoriously spiky thermal output.

 Bryant found that the Kraken's cooler is not optimized out of the box for Ryzen CPUs, causing the fans to spin up and down erratically. The Kraken's pump speed is based on liquid temperature, while the fans are based on the[CPU temperature](https://www.tomshardware.com/how-to/how-to-check-cpu-temp-temperature) , something Bryant found unattractive. (We've also complained about this[our own cooler reviews](https://www.tomshardware.com/pc-components/cooling/reviews) .)

 To fix this problem, Bryant decided to build his own cooling app that could eliminate the problem and give him more granular control over his pump and fan speeds. Additionally, he doesn't like how bloated traditional fan software normally is, giving him even more incentive to build his own app.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![Cal Bryant's fan curve from his Python app](https://cdn.mos.cms.futurecdn.net/HLapN7zrv8kWaLCxAFnc93-320-80.png)

 (Image credit: Cal Bryant)

 In the end, he was able to create an application that can read the CPU, case, and liquid temperatures of the system, and adjust the CPU fan and pump speeds accordingly. The app was written in[Python](https://www.tomshardware.com/how-to/use-for-loops-in-python) and Liquidctl, a programmatic control system that can allow Python scripts to control liquid coolers such as the X53\. For temperature control, the app reads temperature data from Linux's built-in hardware sensor capabilities, known as lm-sensors. Bryant wrote his Python app in such a way that it can be installed as a system service that starts when the OS boots up and hides in the background. For the nitty-gritty details on how the app was written step-by-step, check out Bryant's[full article](https://calbryant.uk/blog/better-pc-cooling-with-python/) .

 The app was tuned to run the X53's pump in conjunction with the CPU's temperature output and run the radiator fans in conjunction with the coolant temperature. This is very different from the X53's default configuration where the pump RPM is driven by the coolant temperature.

 With this method of RPM control, he was able to significantly reduce the spiky nature of his cooler's default fan profile and make the cooler more performant only when needed. Having the pump speed up based on the CPU temperature allows the cooler to extract heat more quickly from the CPU. Coolant takes a long time to warm up under a heavy load compared to[air coolers](https://www.tomshardware.com/reviews/best-cpu-coolers,4181.html) . Having the fans connected to the coolant temperature, in turn, allows the cooler to only run the fans at a high RPM when the coolant is warm. In an AIO, the fans aren't cooling the[CPU](https://www.tomshardware.com/reviews/best-cpus,3986.html) , they are cooling down the liquid that is extracting heat from the CPU.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-discover-the-magic-of-jujutsu-kaisen-with-tiktok-videos/"><u>[New] 2024 Approved  Discover the Magic of Jujutsu Kaisen with TikTok Videos</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-first-time-streamers-unite-learn-obs-and-broadcast-to-youtube/"><u>[New] 2024 Approved  First-Time Streamers Unite  Learn OBS & Broadcast to Youtube</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-obs-studio-vs-bandicam-which-is-better/"><u>[New] 2024 Approved  OBS Studio vs Bandicam  Which Is Better</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-worldwide-top-earners-in-the-streaming-sphere/"><u>[New] 2024 Approved  Worldwide Top Earners in the Streaming Sphere</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-top-5-best-facebook-video-downloader-for-ios/"><u>[New] In 2024, Top 5 Best Facebook Video Downloader for iOS</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-full-picture-mastering-picsart-with-the-2024-guide/"><u>[New] The Full Picture  Mastering PicsArt with the 2024 Guide</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-cinematic-chronology-best-video-cameras-for-detailed-speed-recording/"><u>[Updated] Cinematic Chronology  Best Video Cameras for Detailed Speed Recording</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exploring-the-best-iphone-selfie-tools-ranked-8/"><u>[Updated] Exploring the Best iPhone Selfie Tools, Ranked #8</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-screen-capturing-made-easy-best-apps-for-windows-10/"><u>[Updated] In 2024, Screen Capturing Made Easy  Best Apps for Windows 10</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-strategies-for-improved-zoom-visuals-via-filters/"><u>[Updated] In 2024, Strategies for Improved Zoom Visuals via Filters</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-syncsavvy-experts-opinion/"><u>[Updated] In 2024, SyncSavvy Experts Opinion</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-risky-business-buying-non-real-youtube-supporters-for-2024/"><u>[Updated] Risky Business  Buying Non-Real YouTube Supporters for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-unparalleled-selection-of-budget-stock-media-sites/"><u>[Updated] Unparalleled Selection of Budget Stock Media Sites</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-in-depth-breakdown-stream-yourself-successfully-via-zoom-and-youtube/"><u>2024 Approved  In-Depth Breakdown  Stream Yourself Successfully via Zoom and YouTube</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-the-minecraft-enthusiasts-blueprint-6-essential-recordings-strategies/"><u>2024 Approved  The Minecraft Enthusiast's Blueprint  6 Essential Recordings Strategies</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/2024s-ultimate-guide-to-the-best-cpu-thermal-pastes-evaluating-and-ranking-top-90-picks/"><u>2024'S Ultimate Guide to the Best CPU Thermal Pastes: Evaluating and Ranking Top 90 Picks</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/accidental-tiktok-giveaway-unauthorized-returns-for-safe-and-new-bambu-lab-a1-3d-printers/"><u>Accidental TikTok Giveaway: Unauthorized Returns for Safe and New Bambu Lab A1 3D Printers</u></a></li>
<li><a href="https://extra-hints.techidaily.com/comprehensive-guide-to-sound-in-powerpoint-presentations-for-2024/"><u>Comprehensive Guide to Sound in PowerPoint Presentations for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/discover-the-ultimate-7-free-ai-apps-and-chatgpt-replacements-for-instant-travel-arrangement/"><u>Discover the Ultimate 7 Free AI Apps and ChatGPT Replacements for Instant Travel Arrangement</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/dive-into-the-world-of-gadgets-premium-guides-and-in-depth-analysis-by-toms-hardware-your-trusted-tech-authority/"><u>Dive Into the World of Gadgets - Premium Guides & In-Depth Analysis by Tom's Hardware | Your Trusted Tech Authority!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/elite-picks-the-fastest-external-solid-state-drives-for-this-year/"><u>Elite Picks: The Fastest External Solid State Drives for This Year</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723175662321-expert-advice-for-upgrading-your-rig-check-out-toms-hardware/"><u>Expert Advice for Upgrading Your Rig? Check Out Tom's Hardware!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-advice-from-toms-digital-world-for-your-pc-and-more/"><u>Expert Advice From Tom's Digital World for Your PC and More</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-technology-in-depth-analysis-from-toms-world-of-hardware/"><u>Exploring Technology: In-Depth Analysis From Tom's World of Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-the-latest-in-computing-with-toms-expertise/"><u>Exploring the Latest in Computing with Tom's Expertise</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/find-your-perfect-match-best-thermal-pastes-for-modern-cpus-our-in-depth-testing-of-90-products/"><u>Find Your Perfect Match: Best Thermal Pastes for Modern CPUs - Our In-Depth Testing of 90 Products</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-vivo-t2-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/full-guide-to-catch-100-iv-pokemon-using-a-map-on-vivo-v30-pro-drfone-by-drfone-virtual-android/"><u>Full Guide to Catch 100 IV Pokémon Using a Map On Vivo V30 Pro | Dr.fone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/future-proof-cooling-technology-top-aio-units-for-tech-enthusiasts/"><u>Future-Proof Cooling Technology: Top AIO Units for Tech Enthusiasts</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-nubia-red-magic-8s-pro-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Nubia Red Magic 8S Pro | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-oppo-a18-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Oppo A18 to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-capturing-content-in-the-digital-age-top-strategies/"><u>In 2024, Capturing Content in the Digital Age  Top Strategies</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-enhancing-authenticity-and-connection-via-fb-profile-covers/"><u>In 2024, Enhancing Authenticity and Connection via FB Profile Covers</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-lava-yuva-3-drfone-by-drfone-virtual-android/"><u>In 2024, How to Check Distance and Radius on Google Maps For your Lava Yuva 3 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-migrate-android-data-from-tecno-phantom-v-fold-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Migrate Android Data From Tecno Phantom V Fold to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-in-depth-look-at-facetune-complete-app-revision/"><u>In 2024, In-Depth Look at Facetune  Complete App Revision</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-insightful-comparisons-top-android-applications-for-youtube-download/"><u>In 2024, Insightful Comparisons  Top Android Applications for YouTube Download</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unleash-creativity-with-these-10-ae-text-setups/"><u>In 2024, Unleash Creativity with These 10 AE Text Setups</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-samsung-galaxy-s24-drfone-by-drfone-virtual-android/"><u>In 2024, Where Is the Best Place to Catch Dratini On Samsung Galaxy S24 | Dr.fone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/introducing-the-revolutionary-noctua-nh-d15-g2-the-latest-and-greatest-in-high-performance-cpu-cooling-for-150/"><u>Introducing the Revolutionary Noctua NH-D15 G2: The Latest and Greatest in High-Performance CPU Cooling for $150</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/master-your-build-professional-tips-from-toms-hardware-reviews/"><u>Master Your Build: Professional Tips From Tom's Hardware Reviews</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/master-your-build-top-tips-and-reviews-by-toms-hardware-experts/"><u>Master Your Build: Top Tips and Reviews by Tom's Hardware Experts</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-gadgets-and-pc-components-with-toms-expert-analysis/"><u>Mastering Gadgets and PC Components with Tom's Expert Analysis</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-modern-technology-insider-secrets-from-toms-hardware-review/"><u>Mastering Modern Technology: Insider Secrets From Tom's Hardware Review</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigate-through-cutting-edge-hardware-with-toms-comprehensive-gear-reviews/"><u>Navigate Through Cutting-Edge Hardware with Tom's Comprehensive Gear Reviews</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-tech-choices-expert-advice-and-reviews-by-toms-hardware/"><u>Navigating Tech Choices: Expert Advice and Reviews by Tom's Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-the-latest-in-technology-with-toms-hardware-expertise/"><u>Navigating the Latest in Technology with Tom's Hardware Expertise</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/noctua-unveils-its-home-collection-the-100-desk-fan-that-takes-center-stage/"><u>Noctua Unveils Its Home Collection: The $100 Desk Fan that Takes Center Stage</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/precision-reviewed-the-inside-scoop-on-hardware-from-toms-desk/"><u>Precision Reviewed - The Inside Scoop on Hardware From Tom's Desk</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-definitive-review-of-lian-lis-galahad-ii-an-all-in-one-solution-for-extreme-overclocking-rig-optimization/"><u>The Definitive Review of Lian Li's Galahad II: An All-in-One Solution for Extreme Overclocking Rig Optimization</u></a></li>
<li><a href="https://unlock-android.techidaily.com/the-ultimate-guide-to-xiaomi-civi-3-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>The Ultimate Guide to Xiaomi Civi 3 Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-upgrade-corsair-icue-link-h1-h150i-rgb-performance-excellence-with-limitless-creativity/"><u>The Ultimate Upgrade: Corsair iCUE Link H1 🖤H150i RGB - Performance Excellence with Limitless Creativity</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-hub-expert-reviews-on-hardware/"><u>Tom's Tech Hub: Expert Reviews on Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-hub-your-guide-to-cutting-edge-gadgets-and-components/"><u>Tom's Tech Hub: Your Guide to Cutting-Edge Gadgets and Components</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-hub-your-ultimate-guide-to-computer-hardware/"><u>Tom's Tech Hub: Your Ultimate Guide to Computer Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-insights-comprehensive-computer-reviews/"><u>Tom's Tech Insights: Comprehensive Computer Reviews</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-review-insightful-analysis-on-latest-computer-components/"><u>Tom's Tech Review: Insightful Analysis on Latest Computer Components</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-steps-for-the-not-found-x3daudiodll-error/"><u>Troubleshooting Steps for the 'Not Found' X3DAudio.dll Error</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ultimate-guide-picking-the-perfect-soldering-tools/"><u>Ultimate Guide: Picking the Perfect Soldering Tools</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ultimate-selection-of-gaming-headsets-and-mic-combos-for-online-play/"><u>Ultimate Selection of Gaming Headsets and Mic Combos for Online Play</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unlock-the-potential-revolutionary-3d-printed-holographics-for-high-capacity-encoding-of-keys-and-addresses-up-to-57n-bits/"><u>Unlock the Potential: Revolutionary 3D-Printed Holographics for High Capacity Encoding of Keys and Addresses (Up to 57N Bits)</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-new-gadgets-and-systems-on-toms-tech-hub/"><u>Unveiling New Gadgets and Systems on Tom's Tech Hub</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-newest-innovations-a-tour-of-toms-hardware-review-site/"><u>Unveiling the Newest Innovations: A Tour of Tom's Hardware Review Site</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-top-hardware-secrets-the-toms-hardware-way/"><u>Unveiling Top Hardware Secrets - The Tom's Hardware Way</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-the-ultimate-guide-to-online-vertical-video-editors/"><u>Updated The Ultimate Guide to Online Vertical Video Editors</u></a></li>
</ul></div>
