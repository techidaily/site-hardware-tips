---
title: Engineer Develops Python Script to Manage Noisy Fans & Heavy Apps on NZXT Kraken AIO
date: 2024-12-30T23:11:09.881Z
updated: 2025-01-05T22:44:44.210Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4DJKH1uY7P0?si=tCG66XVlbwSKoATj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-mastering-video-success-on-facebook-platforms/"><u>[New] In 2024, Mastering Video Success on Facebook Platforms</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-deciphering-youtubes-subscriber-code/"><u>[Updated] 2024 Approved Deciphering YouTube's Subscriber Code</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-total-disconnect-from-youtube-shorts-made-simple/"><u>[Updated] 2024 Approved Total Disconnect From YouTube Shorts Made Simple</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-crafting-an-engaging-review-vlog-for-everyday-items/"><u>[Updated] Crafting an Engaging Review Vlog for Everyday Items</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1-can-you-safely-charge-your-iphone-while-driving-top-picks-and-reviews-for-the-best-car-chargers-based-on-rigorous-testing-zdnet/"><u>1. Can You Safely Charge Your iPhone While Driving? Top Picks & Reviews for the Best Car Chargers Based on Rigorous Testing - ZDNet</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1-starlink-internet-access-the-future-of-connectivity-in-moving-cars-and-buses-how-it-works/"><u>1. Starlink Internet Access: The Future of Connectivity in Moving Cars and Buses - How It Works</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1-unlock-jet-setting-perks-save-25-on-flights-with-your-amazon-prime-student-card-insider-tips/"><u>1. Unlock Jet-Setting Perks: Save $25 on Flights with Your Amazon Prime Student Card - Insider Tips</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-access-no-cost-vod-media-player-on-windowsmacos/"><u>2024 Approved Access No-Cost VOD Media Player on Windows/MacOS</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/affordable-96-automotive-safety-upgrade-install-dual-camera-system-for-any-vehicle-zdnet/"><u>Affordable $96 Automotive Safety Upgrade: Install Dual-Camera System for Any Vehicle - ZDNet</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ai-enhances-top-navigation-tool-with-accurate-flight-delay-forecasts-discover-how-flight-tracker-revolutionizes-airline-experience/"><u>AI Enhances Top Navigation Tool with Accurate Flight Delay Forecasts: Discover How [Flight Tracker] Revolutionizes Airline Experience</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-oppo-find-n3-flip-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My Oppo Find N3 Flip Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-is-a-sim-network-unlock-pin-get-your-infinix-zero-5g-2023-turbo-phone-network-ready-by-drfone-android/"><u>In 2024, What Is a SIM Network Unlock PIN? Get Your Infinix Zero 5G 2023 Turbo Phone Network-Ready</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-tutorial-installing-latest-graphics-drivers-for-windows-systems/"><u>Step-by-Step Tutorial: Installing Latest Graphics Drivers for Windows Systems</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/when-corporate-image-clashes-with-staff-sentiment-the-backlash-against-united-airlines-sexy-branding/"><u>When Corporate Image Clashes with Staff Sentiment: The Backlash Against United Airlines' Sexy Branding</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/zendure-superbase-v-the-ultimate-all-in-one-charger-for-homes-and-evs-review/"><u>Zendure SuperBase V: The Ultimate All-in-One Charger for Homes and EVs - Review</u></a></li>
</ul></div>

