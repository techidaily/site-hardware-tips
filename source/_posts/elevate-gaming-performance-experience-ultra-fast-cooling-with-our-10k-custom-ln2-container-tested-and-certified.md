---
title: "Elevate Gaming Performance: Experience Ultra-Fast Cooling with Our $10K Custom LN2 Container - Tested and Certified"
date: 2024-08-23T12:55:16.823Z
updated: 2024-08-24T12:55:16.823Z
tags:
  - cooling
categories:
  - hardware
thumbnail: https://thmb.techidaily.com/dfc76f0ba5d27ec9fc744372720f89b9cd207751d15fc2d7499285fee5808af2.jpg
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
<li><a href="https://youtube-help.techidaily.com/new-pixel-powerhouse-the-ultimate-game-collection/"><u>[New] Pixel Powerhouse  The Ultimate Game Collection</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-editscreen-pro-windows-8/"><u>[Updated] 2024 Approved  EditScreen Pro Windows 8</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-integrating-social-video-platforms-with-hdtv/"><u>[Updated] Integrating Social Video Platforms with HDTV</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-the-grandmasters-choice-best-martial-arts-games-list/"><u>[Updated] The Grandmasters' Choice  Best Martial Arts Games List</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/4799-razer-blade-18-upgrades-gaming-laptops-packed-with-i9-14900hx-cpu-and-cutting-edge-rtx-4090-gpu/"><u>$4,799 Razer Blade 18 Upgrades Gaming Laptops: Packed with I9-14900HX CPU and Cutting-Edge RTX 4090 GPU</u></a></li>
<li><a href="https://extra-hints.techidaily.com/10-secret-tips-to-better-use-canva-photo-editor/"><u>10 Secret Tips to Better Use Canva Photo Editor</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-enhancing-presentations-with-vo-techniques-in-ppt/"><u>2024 Approved  Enhancing Presentations with VO Techniques in PPT</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-streamline-your-conversations-with-twitter-video-uploads-on-whatsapp/"><u>2024 Approved  Streamline Your Conversations with Twitter Video Uploads on WhatsApp</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/comprehensive-asus-tuf-gaming-a14-laptop-analysis-the-silent-powerhouse/"><u>Comprehensive Asus TUF Gaming A14 Laptop Analysis - The Silent Powerhouse</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/dells-newest-xps-13-plus-revolutionizing-battery-efficiency-with-qualcomm-snapdragon-x-chips/"><u>Dell's Newest XPS 13 Plus: Revolutionizing Battery Efficiency with Qualcomm Snapdragon X Chips</u></a></li>
<li><a href="https://driver-install.techidaily.com/elite-sound-driver-amd-and-windows/"><u>Elite Sound Driver: AMD & Windows</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/experience-unmatched-endurance-with-lenovos-new-thinkpad-t1-4s-exclusive-specs-include-up-to-29-hour-battery-life-x-elite-cpu-and-expansive-storage/"><u>Experience Unmatched Endurance with Lenovo's New ThinkPad T1 4S: Exclusive Specs Include Up to 29-Hour Battery Life, X Elite CPU and Expansive Storage</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-the-latest-gadgets-with-toms-hardware-insights/"><u>Exploring the Latest Gadgets with Tom's Hardware Insights</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-toms-gadgets-and-hardware-the-ultimate-resource/"><u>Exploring Tom's Gadgets & Hardware: The Ultimate Resource</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/framework-condemns-excessive-use-of-ai-by-other-computer-makers-in-latest-marketing-flap/"><u>Framework Condemns Excessive Use of 'AI' By Other Computer Makers in Latest Marketing Flap</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/get-your-hands-on-the-affordable-msi-bravo-with-rtx-4060-graphics-sub-1000-deals/"><u>Get Your Hands on the Affordable MSI Bravo with RTX 4060 Graphics: Sub-$1,000 Deals</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/hydrogen-peroxide-h2o2-it-releases-oxygen-when-applied-to-a-wound-creating-a-foam-that-helps-remove-debris-and-bacteria-however-it-can-also-damage-healthy-c8/"><u>Hydrogen Peroxide (H2O2) - It Releases Oxygen when Applied to a Wound, Creating a Foam that Helps Remove Debris and Bacteria. However, It Can Also Damage Healthy Cells Surrounding the Wound, so Its Use Is Somewhat Controversial Among Medical Professionals</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-bypassing-google-account-with-vnrom-bypass-for-motorola-moto-g34-5g-by-drfone-android/"><u>In 2024, Bypassing Google Account With vnROM Bypass For Motorola Moto G34 5G</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changefake-your-lava-yuva-2-location-on-viber-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Fake Your Lava Yuva 2 Location on Viber | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-the-speed-spectacle-hero-4-versus-ghost-s-drifting-edition/"><u>In 2024, The Speed Spectacle  Hero 4 Versus Ghost-S Drifting Edition</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-depth-analysis-applying-luts-to-elevate-your-cinematography-for-2024/"><u>In-Depth Analysis  Applying LUTs to Elevate Your Cinematography for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/in-depth-analysis-of-the-latest-dell-xps-16-9640-and-xps-14-9/"><u>In-Depth Analysis of the Latest Dell XPS 16 (9640) & XPS 14 (9</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/in-depth-analysis-of-the-lenovo-legion-pro-5i-generation-9-striking-a-balance-between-gaming-prowess-and-affordability/"><u>In-Depth Analysis of the Lenovo Legion Pro 5I (Generation 9) - Striking a Balance Between Gaming Prowess and Affordability</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-media-giants-navigating-through-facebook-twitter-instagram-and-youtube/"><u>Social Media Giants: Navigating Through Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/tech-insight-saving-meetings-on-devices/"><u>Tech Insight  Saving Meetings on Devices</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-hub-unveiling-the-latest-in-computer-hardware/"><u>Tom's Tech Hub: Unveiling the Latest in Computer Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-insights-your-guide-to-the-latest-in-computer-hardware/"><u>Tom's Tech Insights: Your Guide to the Latest in Computer Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-value-packed-gaming-laptops-available-for-less-than-1500/"><u>Top Value-Packed Gaming Laptops Available For Less Than $1,500</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-ranking-gaming-laptop-reviews-of-2024-comprehensive-tests-and-performance-analytics/"><u>Top-Ranking Gaming Laptop Reviews of 2024 - Comprehensive Tests & Performance Analytics</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723862723791-unbeatable-deal-alert-grab-the-power-of-rtx-4080-in-lenovo-legion-gaming-laptops-for-750-less-plus-a-240hz-display/"><u>Unbeatable Deal Alert! Grab the Power of RTX 4080 in Lenovo Legion Gaming Laptops for $750 Less – Plus a 240Hz Display</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/uncover-trends-in-tech-an-in-depth-look-with-toms-hardware/"><u>Uncover Trends in Tech: An In-Depth Look with Tom's Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723862688448-unleash-the-beast-seize-the-powerful-16-inch-dell-g16-for-gaming-at-an-amazing-949-price-point/"><u>Unleash the Beast: Seize the Powerful 16-Inch Dell G16 for Gaming at an Amazing $949 Price Point</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unleash-your-computer-potential-through-toms-hardware-wisdom/"><u>Unleash Your Computer Potential Through Tom's Hardware Wisdom</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unlocking-the-secret-of-fully-formatted-paper-trails/"><u>Unlocking the Secret of Fully Formatted Paper Trails</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-hardware-secrets-with-tomcuoinsider-tips/"><u>Unveiling Hardware Secrets with Tom'cuoinsider Tips</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-hardware-secrets-with-toms-analytical-guidance/"><u>Unveiling Hardware Secrets with Tom’s Analytical Guidance</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-latest-in-pc-hardware-with-toms-insights/"><u>Unveiling the Latest in PC Hardware with Tom's Insights</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-strongest-gaming-laptop-contenders-for-e-2024-in-depth-analysis-and-benchmarking/"><u>Unveiling the Strongest Gaming Laptop Contenders for E 2024: In-Depth Analysis and Benchmarking</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-top-tech-in-depth-reviews-by-toms-hardware/"><u>Unveiling Top Tech: In-Depth Reviews by Tom's Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/worlds-pioneer-risc-v-laptop-receives-impressive-overhaul-now-boasts-increased-core-count-turbocharged-clock-speed-at-2-ghz-and-advanced-ai-capabilities/"><u>World's Pioneer RISC-V Laptop Receives Impressive Overhaul - Now Boasts Increased Core Count, Turbocharged Clock Speed at 2 GHz, and Advanced AI Capabilities!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->