---
title: Discover Top-Tier Hardware with Tom's PC and Device Analysis
date: 2024-08-15T06:22:00.664Z
updated: 2024-08-16T06:22:00.664Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/229FoESMtHATGsTaPQxpLj-320-80.jpg
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
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-top-12-best-animal-simulator-games-for-android/"><u>[New] In 2024, Top 12 Best Animal Simulator Games for Android</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-dusks-descent-pre-pro-screen-transitions/"><u>[Updated] 2024 Approved  Dusk's Descent  Pre-Pro Screen Transitions</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-top-10-extensions-for-maxed-out-terria/"><u>[Updated] 2024 Approved  Top 10 Extensions for Maxed-Out Terria</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-essential-gear-for-capturing-skisnowboarding-moments/"><u>[Updated] In 2024, Essential Gear for Capturing Ski/Snowboarding Moments</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-journey-through-japan-best-video-games-akin-to-ghost-of-tsushima/"><u>[Updated] Journey Through Japan  Best Video Games Akin to Ghost of Tsushima</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-tech-savvy-guide-from-digital-to-physical-dvds-on-mac/"><u>[Updated] Tech Savvy Guide  From Digital to Physical - DVDs on Mac</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-best-practices-in-photo-captioning-tools/"><u>2024 Approved  Best Practices in Photo Captioning Tools</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/advanced-insights-from-toms-hardware-for-gamers-and-professionals/"><u>Advanced Insights From Tom's Hardware for Gamers and Professionals</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/best-vr-headset-picks-for-an-immersive-gaming-experience-on-your-computer/"><u>Best VR Headset Picks for an Immersive Gaming Experience on Your Computer</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/beyond-the-headlines-cooler-master-addresses-the-ai-thermal-paste-miscommunication-in-cryofuze-5-specs/"><u>Beyond the Headlines: Cooler Master Addresses the 'AI Thermal Paste' Miscommunication in CryoFuze 5 Specs</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/decoding-digital-advancements-through-toms-perspective/"><u>Decoding Digital Advancements Through Tom's Perspective</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discover-the-highest-rated-webcams-on-the-market-today/"><u>Discover the Highest Rated Webcams on the Market Today</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/economical-precision-the-elegoo-neptune-4-pro-laser-priced-at-284/"><u>Economical Precision: The Elegoo Neptune 4 Pro Laser Priced at $284</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723175713630-experience-top-tier-cpu-cooling-with-this-ai-crafted-3d-printed-liquid-n2-container-achieve-up-to-triple-the-speed/"><u>Experience Top-Tier CPU Cooling with This AI-Crafted, 3D-Printed Liquid N2 Container – Achieve Up to Triple the Speed</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/explore-the-worlds-biggest-event-for-3d-enthusiasts-rapid-plus-tct-2024-highlights-and-innovations/"><u>Explore the World's Biggest Event for 3D Enthusiasts: Rapid + TCT 2024 Highlights and Innovations</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/flsun-s1-test-results-unveiling-the-quirks-of-its-innovative-delta-and-hyper-fast-performance/"><u>FLSun S1 Test Results: Unveiling the Quirks of Its Innovative Delta and Hyper-Fast Performance</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/from-frustration-to-freedom-how-one-engineer-used-python-to-master-his-overpowered-nzxt-kraken-cooling-unit/"><u>From Frustration to Freedom: How One Engineer Used Python to Master His Overpowered NZXT Kraken Cooling Unit</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/get-the-best-value-cooling-tech-at-an-unbelievable-price-only-35-discover-the-thermalright-phantom-spirit-120-se/"><u>Get the Best-Value Cooling Tech at an Unbelievable Price - Only $35! Discover the Thermalright Phantom Spirit 120 SE</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/harness-online-tools-for-free-fb-video-conversion-to-1080p720p-mp4/"><u>Harness Online Tools for Free FB Video Conversion to 1080P/720p MP4</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-music-files-from-sony-by-fonelab-android-recover-music/"><u>How To  Restore Missing Music Files from Sony</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-google-frp-on-honor-magic-6-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass Google FRP on Honor Magic 6</u></a></li>
<li><a href="https://some-techniques.techidaily.com/how-to-overcome-sony-a6400-video-viewing-failure-for-2024/"><u>How to Overcome Sony A6400 Video Viewing Failure for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/innovative-computing-insights-from-toms-hardware-reviews/"><u>Innovative Computing Insights From Tom's Hardware Reviews</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/inside-toms-tech-emporium-a-comprehensive-guide-to-computer-hardware/"><u>Inside Tom's Tech Emporium: A Comprehensive Guide to Computer Hardware</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/mastering-mac-from-live-classroom-to-recorded-session-for-2024/"><u>Mastering Mac  From Live Classroom to Recorded Session for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-technology-trends-with-toms-hardware-reviews/"><u>Mastering Technology Trends with Tom's Hardware Reviews</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/maximize-your-game-the-finest-and-best-priced-graphics-cards-for-gamers/"><u>Maximize Your Game: The Finest and Best-Priced Graphics Cards for Gamers</u></a></li>
<li><a href="https://driver-error.techidaily.com/missing-external-drive-in-windows-10-the-seagate-dilemma/"><u>Missing External Drive in Windows 10: The Seagate Dilemma</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-the-world-of-modern-computer-systems-at-toms-hardware-emporium/"><u>Navigating the World of Modern Computer Systems at Tom’s Hardware Emporium</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-through-cutting-edge-devices-at-toms-electronic-hub/"><u>Navigating Through Cutting-Edge Devices at Tom's Electronic Hub</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/prusa-unveils-innovative-manufacturing-in-delaware-for-3d-printing-solutions/"><u>Prusa Unveils Innovative Manufacturing in Delaware for 3D Printing Solutions</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/stay-chill-with-powerful-airflow-meet-the-new-standard-of-thermaltakes-flippable-br)/"><u>Stay Chill with Powerful Airflow: Meet the New Standard of Thermaltake's Flippable ^Br></u></a></li>
<li><a href="https://hardware-tips.techidaily.com/study-reveals-only-half-of-promoted-high-quality-pc-cooling-systems-are-made-with-real-copper/"><u>Study Reveals Only Half of Promoted High-Quality PC Cooling Systems Are Made With Real Copper</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-informed-buyers-resource-for-cutting-edge-computer-equipment-choose-wisely-at-toms-tech-selection/"><u>The Informed Buyer's Resource for Cutting-Edge Computer Equipment – Choose Wisely at Tom's Tech Selection</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-guide-to-perfect-blemish-free-3d-printing-results/"><u>The Ultimate Guide to Perfect, Blemish-Free 3D Printing Results</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-selection-elite-raspberry-pi-hardware-for-the-year-2024/"><u>The Ultimate Selection: Elite Raspberry Pi Hardware for the Year 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-ultimate-vsco-editors-handbook/"><u>The Ultimate VSCO Editor's Handbook</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-insights-comprehensive-computer-hardware-reviews/"><u>Tom's Tech Insights: Comprehensive Computer Hardware Reviews</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-reviews-expert-insights-on-latest-gadgets/"><u>Tom's Tech Reviews: Expert Insights on Latest Gadgets</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723125120931-unbeatable-deal-save-75-on-the-lightning-fast-elegoo-neptune-4-pro-editors-pick/"><u>Unbeatable Deal: Save $75 on the Lightning-Fast Elegoo Neptune 4 Pro - Editors Pick</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-high-tech-secrets-at-toms-hardware-haven/"><u>Unveiling High-Tech Secrets at Tom's Hardware Haven</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-latest-gadgets-with-toms-hardware-experts/"><u>Unveiling the Latest Gadgets with Tom's Hardware Experts</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-mighty-and-serene-performance-of-the-thicc-q60-240mm-hytech-air-intercooler-comprehensive-review/"><u>Unveiling the Mighty and Serene Performance of the Thicc Q60 240Mm Hytech Air Intercooler - Comprehensive Review</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/us-crackdown-on-tech-trade-punishing-deepcool-for-providing-power-and-cooling-equipment-to-wartime-russia/"><u>US Crackdown on Tech Trade: Punishing DeepCool for Providing Power & Cooling Equipment to Wartime Russia</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->