---
title: Assessing the Valkyrie Vind SL125 - Aesthetic Appeal Vs. Lackluster Performance Metrics
date: 2024-08-19T03:44:56.010Z
updated: 2024-08-20T03:44:56.010Z
tags:
  - cooling
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/yF4vYsbVZXABgoDgrLaGaY-320-80.jpg
---

## Custom Python Script for a Quieter, Streamlined Experience with the NZXT Kraken AIO - Beat Fan Noise & Bulky Apps

Software designer Cal Bryant created a PC cooling app for his liquid-cooled Ryzen 9 5950X PC from scratch[using Python](https://calbryant.uk/blog/better-pc-cooling-with-python/#) . With his app, he was able to fine-tune his Kraken X53's pump and fan speed and run both a lot more efficiently, making the cooler run significantly quieter compared to running the fan controls through the motherboard[BIOS/UEFI](https://www.tomshardware.com/reviews/bios-keys-to-access-your-firmware,5732.html) .

 The origins of Bryant's home-brewed Python cooling app started when he upgraded his personal system from a[Ryzen 7 3700X](https://www.tomshardware.com/reviews/ryzen-9-3900x-7-3700x-review,6214.html) to the much more potent[Ryzen 9 5950X](https://www.tomshardware.com/reviews/amd-ryzen-9-5950x-5900x-zen-3-review) . According to Bryant, the extra cores nearly doubled the heat output of his system, forcing his NZXT Kraken X53 240mm[AIO liquid cooler](https://www.tomshardware.com/best-picks/best-aio-coolers) to work much harder. Consequently, the CPU swap also made his cooler much louder to deal with the extra heat output. On top of this, the fans were also spinning up and down erratically, due to Zen 3's notoriously spiky thermal output.

 Bryant found that the Kraken's cooler is not optimized out of the box for Ryzen CPUs, causing the fans to spin up and down erratically. The Kraken's pump speed is based on liquid temperature, while the fans are based on the[CPU temperature](https://www.tomshardware.com/how-to/how-to-check-cpu-temp-temperature) , something Bryant found unattractive. (We've also complained about this[our own cooler reviews](https://www.tomshardware.com/pc-components/cooling/reviews) .)

 To fix this problem, Bryant decided to build his own cooling app that could eliminate the problem and give him more granular control over his pump and fan speeds. Additionally, he doesn't like how bloated traditional fan software normally is, giving him even more incentive to build his own app.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
![Cal Bryant's fan curve from his Python app](https://cdn.mos.cms.futurecdn.net/HLapN7zrv8kWaLCxAFnc93-320-80.png)

 (Image credit: Cal Bryant)

 In the end, he was able to create an application that can read the CPU, case, and liquid temperatures of the system, and adjust the CPU fan and pump speeds accordingly. The app was written in[Python](https://www.tomshardware.com/how-to/use-for-loops-in-python) and Liquidctl, a programmatic control system that can allow Python scripts to control liquid coolers such as the X53\. For temperature control, the app reads temperature data from Linux's built-in hardware sensor capabilities, known as lm-sensors. Bryant wrote his Python app in such a way that it can be installed as a system service that starts when the OS boots up and hides in the background. For the nitty-gritty details on how the app was written step-by-step, check out Bryant's[full article](https://calbryant.uk/blog/better-pc-cooling-with-python/) .

 The app was tuned to run the X53's pump in conjunction with the CPU's temperature output and run the radiator fans in conjunction with the coolant temperature. This is very different from the X53's default configuration where the pump RPM is driven by the coolant temperature.

 With this method of RPM control, he was able to significantly reduce the spiky nature of his cooler's default fan profile and make the cooler more performant only when needed. Having the pump speed up based on the CPU temperature allows the cooler to extract heat more quickly from the CPU. Coolant takes a long time to warm up under a heavy load compared to[air coolers](https://www.tomshardware.com/reviews/best-cpu-coolers,4181.html) . Having the fans connected to the coolant temperature, in turn, allows the cooler to only run the fans at a high RPM when the coolant is warm. In an AIO, the fans aren't cooling the[CPU](https://www.tomshardware.com/reviews/best-cpus,3986.html) , they are cooling down the liquid that is extracting heat from the CPU.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-transforming-snaps-into-animated-characters-in-snapchat/"><u>[New] 2024 Approved  Transforming Snaps Into Animated Characters in Snapchat</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-open-broadcasters-versus-shadowreplay/"><u>[Updated] 2024 Approved  Open Broadcasters Versus ShadowReplay</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-abletons-pathway-to-harmonious-declines-for-2024/"><u>[Updated] Ableton's Pathway to Harmonious Declines for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-beginners-bonanza-affordable-profitable-channel-options/"><u>[Updated] Beginner's Bonanza  Affordable, Profitable Channel Options</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-immediate-ios-screen-playback-guide-for-2024/"><u>[Updated] Immediate iOS Screen Playback Guide for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-exposure-boost-for-your-social-media-visuals/"><u>[Updated] In 2024, Exposure Boost for Your Social Media Visuals</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-perfect-audio-connection-must-have-tips-for-podcasters-for-2024/"><u>[Updated] Perfect Audio Connection  Must-Have Tips for Podcasters for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-reclaiming-deleted-youtube-treasures-a-2-step-guide/"><u>[Updated] Reclaiming Deleted YouTube Treasures  A 2-Step Guide</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-techniques-for-smoothing-meetings-backgrounds-in-teams/"><u>[Updated] Techniques for Smoothing Meetings' Backgrounds in Teams</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-bridging-gaps-online-effective-techniques-for-screenshare-on-fb/"><u>2024 Approved  Bridging Gaps Online  Effective Techniques for Screenshare on FB</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/2024s-most-innovative-and-efficient-bendy-gaming-displays/"><u>2024'S Most Innovative and Efficient Bendy Gaming Displays</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/apex-screen-capture-tools-the-elite-line-up-for-2024/"><u>Apex Screen Capture Tools  The Elite Line-Up for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/beat-the-heat-without-breaking-the-bank-secure-your-pcs-temperature-below-45-using-deepcools-as500-plus-at-amazon/"><u>Beat the Heat without Breaking the Bank: Secure Your PC's Temperature Below $45 Using DeepCool's AS500 Plus at Amazon</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-t-view-mkv-movies-content-on-defy-2-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Can’t view MKV movies content on Defy 2</u></a></li>
<li><a href="https://tech-haven.techidaily.com/creating-your-personalized-ai-chatbot-tailoring-a-custom-gpt-model-to-your-data/"><u>Creating Your Personalized AI Chatbot: Tailoring a Custom GPT Model to Your Data</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/cutting-edge-thermal-solutions-surpass-300w-efficaciously-with-cooler-masters-newest-aio-and-air-cooling-tech/"><u>Cutting-Edge Thermal Solutions: Surpass 300[W Efficaciously With Cooler Master's Newest AIO and Air Cooling Tech</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discover-the-ultimate-selection-of-high-end-cost-effective-3d-printers/"><u>Discover the Ultimate Selection of High-End, Cost-Effective 3D Printers</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723175706517-dive-into-a-cool-experience-discover-the-revolutionary-sporty-active-chillers-by-frore-the-innovative-underwater-friendly-fanless-airjet-mini/"><u>Dive Into a Cool Experience - Discover the Revolutionary Sporty Active Chillers by Frore: The Innovative Underwater Friendly, Fanless AirJet Mini!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/effective-techniques-to-prevent-surface-defects-on-your-3d-printed-objects/"><u>Effective Techniques to Prevent Surface Defects on Your 3D Printed Objects</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/enhance-your-pcs-cooling-system-with-the-mighty-moora-iv-600-nine-200mm-fans-and-a-bulky-35lbs-radiator-for-under-600/"><u>Enhance Your PC's Cooling System with the Mighty MOORA IV 600: Nine 200Mm Fans and a Bulky 35Lbs Radiator for Under $600</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ensuring-solidity-in-3d-printing-stop-layers-from-peeling-apart/"><u>Ensuring Solidity in 3D Printing: Stop Layers From Peeling Apart</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/experience-top-quality-with-our-favorite-the-eleegoo-neptune-4-pro-now-available-for-only-240-on-newegg/"><u>Experience Top Quality with Our Favorite - The Eleegoo Neptune 4 Pro, Now Available for Only $240 on Newegg!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-insights-on-electronics-with-toms-hardware-experts/"><u>Expert Insights on Electronics with Tom's Hardware Experts</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723125123693-expert-reviews-and-gear-guides-by-your-brand-the-next-level-after-toms-hardware/"><u>Expert Reviews and Gear Guides by [Your Brand] – The Next Level After Tom's Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723125239890-explore-cutting-edge-tech-with-toms-hardware-review-hub/"><u>Explore Cutting-Edge Tech with Tom's Hardware Review Hub!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-computer-hardware-with-tom-in-depth-guides-and-reviews/"><u>Exploring Computer Hardware with Tom - In-Depth Guides & Reviews</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-the-fast-world-of-sovol-sv08-the-new-voron-homage-racer/"><u>Exploring the Fast World of Sovol SV08: The New Voron Homage Racer</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/how-to-stop-separation-between-layers-during-the-3d-printing-process/"><u>How to Stop Separation Between Layers During the 3D Printing Process</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ideal-screen-selection-find-the-perfect-display-for-your-next-gen-console-experience-ps5-xbox-series-xs/"><u>Ideal Screen Selection: Find the Perfect Display for Your Next-Gen Console Experience (PS5, Xbox Series X/S)</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-itel-p55-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On Itel P55? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-vivo-y17s-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Vivo Y17s to Outlook | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-infinix-smart-8-plus-phone-with-broken-screen-by-drfone-android/"><u>In 2024, How to Unlock Infinix Smart 8 Plus Phone with Broken Screen</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-top-10-airplay-apps-in-vivo-t2-5g-for-streaming-drfone-by-drfone-android/"><u>In 2024, Top 10 AirPlay Apps in Vivo T2 5G for Streaming | Dr.fone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/inside-look-at-top-tier-computer-systems-by-toms-team/"><u>Inside Look at Top-Tier Computer Systems by Tom’s Team</u></a></li>
<li><a href="https://extra-tips.techidaily.com/master-the-art-of-editing-story-remix-and-windows-photos-synergy/"><u>Master the Art of Editing  Story Remix & Windows Photos Synergy</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-pc-building-tips-from-toms-hardware-experts/"><u>Mastering PC Building Tips From Tom's Hardware Experts</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-secure-passwords-the-best-software-for-free-and-subscription-based-management-systems/"><u>Mastering Secure Passwords: The Best Software for Free & Subscription-Based Management Systems</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723125125687-modded-marvels-astonishingly-swift-completion-of-speed-benchy-by-an-enhanced-3d-printer-in-merely-2-minutes/"><u>Modded Marvels: Astonishingly Swift Completion of ‘Speed Benchy’ by an Enhanced 3D Printer in Merely 2 Minutes!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-3d-print-designs-a-guide-to-the-industrys-top-5-standards/"><u>Navigating 3D Print Designs: A Guide to the Industry's Top 5 Standards</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-tech-choices-insider-tips-from-toms-hardware-guru/"><u>Navigating Tech Choices: Insider Tips From Tom's Hardware Guru</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-the-world-of-gadgets-informed-perspectives-from-toms-hardware-journey/"><u>Navigating the World of Gadgets: Informed Perspectives From Tom's Hardware Journey</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/noctua-unveils-ultra-compact-nh-l12sx77-enhanced-ram-clearance-and-efficient-vrm-cooling-in-sff-rigs/"><u>Noctua Unveils Ultra-Compact NH-L12Sx77: Enhanced Ram Clearance & Efficient VRM Cooling in SFF Rigs</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/pioneering-gadget-analysis-by-toms-hardware-experts/"><u>Pioneering Gadget Analysis by Tom's Hardware Experts</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723175642094-revolutionize-your-pc-cooling-foolproof-thermal-interface-material-tim-applier-by-x-apply-coming-shortly/"><u>Revolutionize Your PC Cooling: 'Foolproof' Thermal Interface Material (TIM) Applier by X-Apply - Coming Shortly</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-unlock-software-for-vivo-t2x-5g-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>The Best Android Unlock Software For Vivo T2x 5G Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-guide-to-the-features-and-performance-of-crealitys-k1-c-carbon-edition/"><u>The Ultimate Guide to the Features and Performance of Creality's K1 C Carbon Edition</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-computer-chronicles-a-journey-through-hardware-excellence/"><u>Tom's Computer Chronicles: A Journey Through Hardware Excellence</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-hardware-comprehensive-tech-reviews-and-guides-unveiling-cutting-edge-gadgets/"><u>Tom's Hardware - Comprehensive Tech Reviews & Guides | Unveiling Cutting Edge Gadgets!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-hub-expert-reviews-and-guides/"><u>Tom's Tech Hub - Expert Reviews & Guides</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-hub-comprehensive-reviews-and-buying-guides/"><u>Tom's Tech Hub: Comprehensive Reviews & Buying Guides</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-6-cura-mistakes-and-their-easy-solutions/"><u>Top 6 Cura Mistakes & Their Easy Solutions</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-notch-thermal-performance-under-65-in-depth-review-of-thermalright-frozen-notte-and-aquaelite-360-white-v3/"><u>Top-Notch Thermal Performance Under $65: In-Depth Review of Thermalright Frozen Notte and AquaElite 360 White V3</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-tips-fixing-no-sound-issues-in-windows-7/"><u>Troubleshooting Tips: Fixing No-Sound Issues in Windows 7</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ultimate-guide-to-ps5s-fastest-ssds-selecting-the-speediest-nvme-memory-upgrades/"><u>Ultimate Guide to PS5's Fastest SSDs: Selecting the Speediest NVMe Memory Upgrades</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unleash-your-imagination-the-massive-potential-of-the-elegoo-kids-size-3d-printer/"><u>Unleash Your Imagination: The Massive Potential of the Elegoo Kids-Size 3D Printer</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unraveling-the-world-of-technology-with-toms-gear-guides/"><u>Unraveling the World of Technology with Tom's Gear Guides</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/why-the-id-cooling-fx360-pro-is-your-best-bet-for-adequate-cooling-under-60/"><u>Why the ID-Cooling FX360 Pro Is Your Best Bet for Adequate Cooling Under $60</u></a></li>
</ul></div>
