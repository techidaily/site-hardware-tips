---
title: "Elevate Gaming Performance: Experience Ultra-Fast Cooling with Our $10K Custom LN2 Container - Tested and Certified"
date: 2025-01-07T00:29:57.603Z
updated: 2025-01-12T22:10:07.416Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-docs.techidaily.com/ed-discover-the-top-8-services-to-amplify-video-content/"><u>[Updated] Discover the Top 8 Services to Amplify Video Content</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-elite-media-reader-unmatched-for-all-devices-type/"><u>[Updated] In 2024, Elite Media Reader - Unmatched for All Devices Type</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-top-kid-approved-drone-choices-summarized/"><u>[Updated] In 2024, Top Kid-Approved Drone Choices Summarized</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/beyond-macbooks-shadow-a-surprising-tech-marvel-emerges-as-one-of-the-top-performers-tested-by-zdnet/"><u>Beyond MacBook's Shadow: A Surprising Tech Marvel Emerges as One of the Top Performers Tested by ZDNet</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/budget-friendly-hp-touchscreen-notebook-with-keyboard-and-mouse-combo-plus-free-microsoft-office-suite-only-400-on-zdnet/"><u>Budget-Friendly HP Touchscreen Notebook with Keyboard & Mouse Combo + Free Microsoft Office Suite - Only $400 on ZDNet</u></a></li>
<li><a href="https://games-able.techidaily.com/fast-track-pinpointing-your-virtual-gaming-number/"><u>Fast Track: Pinpointing Your Virtual Gaming Number</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/hp-shakes-up-laptop-industry-with-innovative-approach-that-even-apple-cant-match-expert-analysis-by-zdnet/"><u>HP Shakes Up Laptop Industry with Innovative Approach that Even Apple Can't Match | Expert Analysis by ZDNET</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-a-childs-fortune-the-wealthy-world-of-youtubes-youngest-star/"><u>In 2024, A Child’s Fortune The Wealthy World of YouTube’s Youngest Star</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ultimate-list-of-prompts-overcoming-tech-disruptions-with-chatgpt/"><u>Ultimate List of Prompts: Overcoming Tech Disruptions with ChatGPT</u></a></li>
<li><a href="https://fox-sure.techidaily.com/ultra-hd-1920x12-similar-problem/"><u>Ultra HD 1920X12 # Similar Problem:</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-simplified-non-windows-living-a-look-at-the-budget-friendly-hp-chromebook-with-a-136-discounted-price-on-zdnet/"><u>Unveiling Simplified Non-Windows Living: A Look at the Budget-Friendly HP Chromebook with a 136% Discounted Price on ZDNet</u></a></li>
</ul></div>

