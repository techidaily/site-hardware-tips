---
title: Navigating the World of PC Parts with Tom's Hardware Experts
date: 2024-08-15T06:17:56.582Z
updated: 2024-08-16T06:17:56.582Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/StJQAUjdfbrguLmZvf2qnJ-320-80.jpg
---

## Legacy Over: How LLVM Compiler's Departure Signals the End of AMD's 3DNow

AMD’s near-ancient 3DNow! instructions have faded even further into obscurity.[Open-source compiler LLVM](https://github.com/llvm/llvm-project/commit/f0eb5587ceeb641445b64cb264c822b4751de04a) is finally removing support for the set of instructions that hasn’t been supported by AMD’s CPUs since 2011.

 The 3DNow! instruction set was introduced in 1998 as a competitor to Intel’s MMX. It added Single Instruction, Multiple Data (SIMD) instructions to AMD’s base x86 instruction set, which helped the CPUs do vector processing of floating-point operations using vector registers.

[AMD replaced 3DNow!](https://www.tomshardware.com/news/3dnow-simd-extensions-phenom-sse,11128.html) with the newer SSE equivalents in 2011 and stopped including that feature flag bit beginning with the K10 Bulldozer CPUs. It did take some time for compilers to start dropping support for the instruction set, though, since the CPUs remained in use for quite some time.

 In 2021,[Linux retired the instruction set](https://www.tomshardware.com/news/linux-says-goodbye-to-amd-3d-now) from its kernel, but LLVM maintained support long after everyone else dropped it. The developers behind the LLVM compiler also work to remove MMX types and instructions from the tool.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

 A commit for LLVM 19, expected to be released in September or October, confirmed the impending removal.

 _“This set of instructions was only supported by AMD chips starting in the K6-2 (introduced 1998), and before the “Bulldozer” family (2011). They were never much used, as they were effectively superseded by the more-widely-implemented SSE (first implemented on the AMD side in Athlon XP in 2001)._

 _This is being done as a predecessor towards general removal of MMX register usage. Since there is almost no usage of the 3DNow! intrinsics, and no modern hardware even implements them, simple removal seems like the best option.”_

## Stay On the Cutting Edge: Get the Tom's Hardware Newsletter

 Get Tom's Hardware's best news and in-depth reviews, straight to your inbox.

 Contact me with news and offers from other Future brands  Receive email from us on behalf of our trusted partners or sponsors

 By submitting your information you agree to the[Terms & Conditions](https://futureplc.com/terms-conditions/) and[Privacy Policy](https://futureplc.com/privacy-policy/) and are aged 16 or over.

 The AMD 3DNow! instructions were popular in the late 90s and early 2000s for improving gaming, video playback, and Adobe Photoshop workflows. Then, Intel released the SSE instructions, which became more dominant overall. When Intel released SSE2, AMD adopted it and dropped its older SIMD instruction set.

 Developers who need to write for old AMD processors can still use 3DNow! instructions in Assembly, including inline Assembly code with LLVM. Other than that, anything related to 3DNow! should be considered deprecated and no longer used.


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
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-thumbnail-crafting-101-the-fundamentals-covered/"><u>[New] 2024 Approved  Thumbnail Crafting 101  The Fundamentals Covered</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/rafting-a-cash-flow-career-with-content-creation-like-ajey-nagar/"><u>[New] Crafting a Cash-Flow Career with Content Creation Like Ajey Nagar</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-fuse-voice-recordings-with-ppt-content-for-2024/"><u>[New] Fuse Voice Recordings with PPT Content for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-tech-tools-for-streaming-a-detailed-overview-on-tv-recording/"><u>[New] In 2024, Tech Tools for Streaming  A Detailed Overview on TV Recording</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/benchmarking-the-future-in-depth-analysis-on-top-gaming-laptops-in-202/"><u>Benchmarking The Future: In-Depth Analysis on Top Gaming Laptops in 202</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/comprehensive-hardware-insights-from-toms-experts/"><u>Comprehensive Hardware Insights From Tom's Experts</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/delving-into-gadgets-with-tom-a-comprehensive-guide-on-modern-computing-equipment/"><u>Delving Into Gadgets with Tom - A Comprehensive Guide on Modern Computing Equipment</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discovering-cutting-edge-gear-a-closer-look-by-toms-hardware-experts/"><u>Discovering Cutting-Edge Gear: A Closer Look by Tom’s Hardware Experts</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/dive-into-toms-hardware-insights-and-equipment-analysis/"><u>Dive Into Tom's Hardware Insights and Equipment Analysis</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/dominating-desktops-top-performance-analysis-of-the-id-cooling-frozn-series-a720-and-a620-air-cooling-unleashed/"><u>Dominating Desktops: Top Performance Analysis of the ID-Cooling FROZN Series (A720 & A620) - Air Cooling Unleashed</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723125193005-expert-hardware-analysis-by-tom-dive-into-gear-details/"><u>Expert Hardware Analysis by Tom – Dive Into Gear Details</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/find-your-perfect-companion-elite-portable-wireless-mice-of-2024-for-optimal-performance/"><u>Find Your Perfect Companion: Elite Portable Wireless Mice of 2024 for Optimal Performance</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/high-performance-vs-low-cost-gaming-ram-of-2024-options-and-reviews/"><u>High Performance Vs. Low Cost Gaming RAM of 2024: Options and Reviews</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-fix-repeated-crashing-in-pathfinder-wrath-of-the-righte-experts-reveal-solutions/"><u>How to Fix Repeated Crashing in Pathfinder: Wrath of the Righte# #Experts Reveal Solutions</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-from-realme-c33-2023-by-drfone-android/"><u>In 2024, How to Bypass FRP from Realme C33 2023?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-show-wi-fi-password-on-samsung-galaxy-f14-5g-by-drfone-android/"><u>In 2024, How to Show Wi-Fi Password on Samsung Galaxy F14 5G</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-xiaomi-redmi-note-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On Xiaomi Redmi Note 12 5G | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-passfab-apple-iphone-11-pro-max-backup-unlocker-top-4-alternatives-drfone-by-drfone-ios/"><u>In 2024, PassFab Apple iPhone 11 Pro Max Backup Unlocker Top 4 Alternatives | Dr.fone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/inside-toms-tech-lab-unveiling-top-notch-computing-equipment/"><u>Inside Tom's Tech Lab: Unveiling Top-Notch Computing Equipment</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/master-the-art-of-merging-multiple-filaments-into-a-single-cylinder-quickly-and-easily/"><u>Master the Art of Merging Multiple Filaments Into a Single Cylinder Quickly and Easily</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/master-your-pcs-temperature-with-the-latest-id-cooling-review-a720-and-a620-series-unveiled/"><u>Master Your PC's Temperature with the Latest ID-Cooling Review: A720 and A620 Series Unveiled</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-the-market-top-choices-in-toms-hardware-evaluation/"><u>Mastering the Market: Top Choices in Tom's Hardware Evaluation</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-the-latest-in-computing-a-guide-by-toms-hardware/"><u>Navigating the Latest in Computing: A Guide by Tom's Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/say-goodbye-to-three-fans-with-cooler-masters-innovative-2-fan-graphics-solution/"><u>Say Goodbye to Three Fans with Cooler Master’s Innovative 2-Fan Graphics Solution</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/secure-data-purge-on-macos-made-easy-discover-the-power-of-stellar-5-file-eraser-standard-with-set-it-and-forget-it-scheduling/"><u>Secure Data Purge on macOS Made Easy: Discover the Power of Stellar 5 File Eraser Standard with Set-It-And-Forget-It Scheduling</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/stay-ahead-in-technology-with-toms-hardware-analysis/"><u>Stay Ahead in Technology with Tom's Hardware Analysis</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-selection-of-premium-3d-printing-filaments/"><u>The Ultimate Selection of Premium 3D Printing Filaments</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-electronic-oasis-expert-insights-on-pc-components-and-gear/"><u>Tom's Electronic Oasis: Expert Insights on PC Components and Gear</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-hub-a-detailed-look-at-comprehensive-computer-insights/"><u>Tom's Tech Hub: A Detailed Look at Comprehensive Computer Insights</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ultimate-tech-insight-with-toms-computer-review/"><u>Ultimate Tech Insight with Tom's Computer Review</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unlocking-performance-the-complete-guide-from-toms-hardware/"><u>Unlocking Performance: The Complete Guide From Tom's Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-lamptrons-misuse-of-fake-aida64-license-keys-in-their-display-units/"><u>Unveiling Lamptron's Misuse of Fake AIDA64 License Keys in Their Display Units</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->