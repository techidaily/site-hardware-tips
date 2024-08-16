---
title: Advanced Gadget Analysis by Tom's Hardware Specialists
date: 2024-08-15T06:31:03.427Z
updated: 2024-08-16T06:31:03.427Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/hCkLJctSSicufPLB47JpXf-320-80.jpg
---

## Discovering Top Tech at Tom's Hardware - Your Ultimate Guide

Intel has[announced that it has found the root](https://community.intel.com/t5/Processors/July-2024-Update-on-Instability-Reports-on-Intel-Core-13th-and/m-p/1617113#M74792) [cause](https://community.intel.com/t5/Processors/July-2024-Update-on-Instability-Reports-on-Intel-Core-13th-and/m-p/1617113#M74792) of the crashing issues plaguing its CPUs. The company will issue a microcode update to address the issues by mid-August, ostensibly ending the long-running saga that began when the first sporadic reports of CPU crashing errors surfaced in December 2022 and grew to a crescendo by the end of 2023\. Intel's response comes after complaints about the issue, which causes PCs to inexplicably crash/BSOD during gaming and other workloads,[reached a fever pitch](https://www.tomshardware.com/pc-components/cpus/game-publisher-claims-100-crash-rate-with-intel-cpus-alderon-games-says-company-sells-defective-13th-and-14th-gen-chips) in recent weeks. However, the microcode update will not repair impacted processors. Intel also confirmed a rumored issue with via oxidation in its 7nm node, but said those issues were corrected in 2023 and didn't contribute to the failures.

 Intel's advisory says an erroneous CPU microcode is the root cause of the incessant instability issues. The microcode caused the CPU to request elevated voltage levels, resulting in the processor operating outside its safe boundaries. Intel is now validating a microcode patch to correct the issues, with its release slated for mid-August. This patch will be distributed through BIOS updates from motherboard OEMs and via Windows updates, so the timing for end-user availability could vary.

 The bug causes irreversible degradation of the impacted processors. We're told that the microcode patch will_not_ repair processors already experiencing crashes, but it is expected to prevent issues on processors that aren't currently impacted by the issue. For now, it is unclear if CPUs exposed to excessive voltage have suffered from invisible degradation or damage that hasn't resulted in crashes yet but could lead to errors or crashes in the future.

 Intel advises all customers having issues to seek help from its customer support. Because the microcode update will not repair impacted processors, the company will continue to replace them. Intel has pledged to grant RMAs to all impacted customers.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

 The company had previously advised its customers to stick with the basic power guidelines for its processors, rather than running them at fully unlocked settings, as it worked through the issues. Those instructions, [which you can see here](https://www.tomshardware.com/pc-components/cpus/intel-issues-official-statement-on-core-k-series-crashes-stick-to-intels-official-power-profiles) , remain in effect for now, and Intel hasn't issued any new workarounds for impacted customers. It is unclear if Intel will lift the existing restrictions after it issues the patch.

 Intel had previously[fixed an eTVB bug](https://www.tomshardware.com/pc-components/cpus/intel-denies-reports-that-it-identified-a-root-cause-for-core-i9-crashing-issues-investigation-continues) that contributed to the problems, but now says microcode is the root cause. We're told that the microcode patch currently doesn't exhibit any adverse performance impact (i.e., the chip running slower), but testing is ongoing. We can expect Intel to share more information about performance in the future.

 Intel isn't sharing many deep-dive details about the bug yet but says it will continue its validation process to ensure the microcode fully addresses the issues. The company will release more details about the bug itself in the future.

## Stay On the Cutting Edge: Get the Tom's Hardware Newsletter

 Get Tom's Hardware's best news and in-depth reviews, straight to your inbox.

 Contact me with news and offers from other Future brands  Receive email from us on behalf of our trusted partners or sponsors

 By submitting your information you agree to the[Terms & Conditions](https://futureplc.com/terms-conditions/) and[Privacy Policy](https://futureplc.com/privacy-policy/) and are aged 16 or over.

 Today, the company also posted to Reddit that it had encountered rumored issues via oxidation in its Intel 7 process node in 2023\. Intel says that the issue was resolved and isn't the source of the Raptor Lake crashes.

 Intel has not issued a recall of its processors; sources close to the matter tell us that isn't expected. We have both of Intel's statements below.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
## Intel statement on 13th- and 14th-Gen instability

 _"Based on extensive analysis of Intel Core 13th/14th Gen desktop processors returned to us due to instability issues, we have determined that elevated operating voltage is causing instability issues in some 13th/14th Gen desktop processors. Our analysis of returned processors confirms that the elevated operating voltage is stemming from a microcode algorithm resulting in incorrect voltage requests to the processor."_

 _"Intel is delivering a microcode patch which addresses the root cause of exposure to elevated voltages. We are continuing validation to ensure that scenarios of instability reported to Intel regarding its Core 13th/14th Gen desktop processors are addressed. Intel is currently targeting mid-August for patch release to partners following full validation."_

 _"Intel is committed to making this right with our customers, and we continue asking any customers currently experiencing instability issues on their Intel Core 13th/14th Gen desktop processors reach out to Intel Customer Support for further assistance."_

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Intel statement on via oxidation

**Short answer:** We can confirm there was a via Oxidation manufacturing issue (addressed back in 2023) but it is not related to the instability issue.

**Long answer:**   _We can confirm that the via Oxidation manufacturing issue affected some early Intel Core 13th Gen desktop processors. However, the issue was root caused and addressed with manufacturing improvements and screens in 2023\. We have also looked at it from the instability reports on Intel Core 13th Gen desktop processors and the analysis to-date has determined that only a small number of instability reports can be connected to the manufacturing issue._

 _For the Instability issue, we are delivering a microcode patch which addresses exposure to elevated voltages which is a key element of the Instability issue. We are currently validating the microcode patch to ensure the instability issues for 13th/14th Gen are addressed. -_ Intel representative[via Reddit](https://www.reddit.com/r/intel/comments/1e9mf04/comment/lefz09c/) .


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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-classic-fanfare-fix/"><u>[New] 2024 Approved  Classic Fanfare Fix</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-adhering-to-correct-aspect-ratio-in-twitter-videos-for-2024/"><u>[New] Adhering to Correct Aspect Ratio in Twitter Videos for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-chromebook-audio-revamp-guide-selecting-the-leading-speech-converters-online/"><u>[New] Chromebook Audio Revamp Guide  Selecting the Leading Speech Converters Online</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-crafting-a-professional-rss-feed-for-your-podcast/"><u>[New] Crafting a Professional RSS Feed for Your Podcast</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-disable-unsolicited-youtube-video-listings/"><u>[New] Disable Unsolicited YouTube Video Listings</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-is-vidma-the-ultimate-screen-recording-tool-for-2024/"><u>[New] Is Vidma the Ultimate Screen Recording Tool for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-streamlining-your-edit-with-jump-cut-tips/"><u>[New] Streamlining Your Edit with Jump Cut Tips</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-a-critique-of-dogmatism/"><u>[Updated] In 2024, A Critique of Dogmatism</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-secrets-to-surpassing-the-top-in-youtube-fame/"><u>[Updated] Secrets to Surpassing the Top in YouTube Fame</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unlocking-fcp-a-guide-to-obtaining-copy-without-cost/"><u>[Updated] Unlocking FCP  A Guide to Obtaining Copy Without Cost</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unpacking-the-features-and-shortcomings-of-samsung-image-editor/"><u>[Updated] Unpacking the Features and Shortcomings of Samsung Image Editor</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/60-worth-of-excellence-unveiling-the-potential-of-id-coolings-fx360-pro-our-in-depth-review/"><u>$60 Worth of Excellence? Unveiling the Potential of ID-Cooling's FX360 Pro - Our In-Depth Review</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-how-zooming-up-with-fb-live-transforms-broadcasts/"><u>2024 Approved  How Zooming Up with FB Live Transforms Broadcasts</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-pinnacle-resources-for-3d-type-art/"><u>2024 Approved  Pinnacle Resources for 3D Type Art</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/5-must-have-rp2amodelos-rp2040-development-kits-of-the-year-2024/"><u>5 Must-Have RP2amodelos (RP2040) Development Kits of the Year 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/assessing-the-valkyrie-vind-sl125-aesthetic-appeal-vs-lackluster-performance-metrics/"><u>Assessing the Valkyrie Vind SL125 - Aesthetic Appeal Vs. Lackluster Performance Metrics</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/bring-your-ideas-to-life-discover-the-magic-of-phrozens-multi-hued-3d-printer/"><u>Bring Your Ideas to Life - Discover the Magic of Phrozen’s Multi-Hued 3D Printer</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/comprehensive-guide-by-toms-gadget-hub-expert-hardware-reviews/"><u>Comprehensive Guide by Tom's Gadget Hub: Expert Hardware Reviews</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/conquer-online-battles-choosing-high-speed-champions-amongst-gaming-routers/"><u>Conquer Online Battles: Choosing High-Speed Champions Amongst Gaming Routers</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/delving-into-digital-the-wonders-of-toms-technology-insights/"><u>Delving Into Digital: The Wonders of Tom's Technology Insights</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discover-the-high-tech-lifestyle-at-2-4-million-texas-abode-featuring-a-vast-5786-sq-ft-data-center-with-full-immersion-liquid-cooling-system/"><u>Discover the High Tech Lifestyle at $2. 4 Million - Texas Abode Featuring a Vast 5,786 Sq Ft Data Center with Full Immersion Liquid Cooling System</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/elevate-your-print-quality-and-save-more-with-a-substantial-80-discount-on-the-elegoo-neptune-plus-printer/"><u>Elevate Your Print Quality & Save More with a Substantial $80 Discount on the Elegoo Neptune Plus Printer</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/experience-faster-pc-builds-with-corsairs-redesigned-screw-installing-in-just-a-single-turn/"><u>Experience Faster PC Builds with Corsair’s Redesigned Screw, Installing in Just a Single Turn</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-the-missing-driver-for-your-gpu/"><u>Fixing the Missing Driver for Your GPU</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changefake-your-oneplus-nord-n30-se-location-on-viber-drfone-by-drfone-virtual-android/"><u>How to Change/Fake Your OnePlus Nord N30 SE Location on Viber | Dr.fone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ideal-laptops-for-college-use-thoroughly-tested-picks-for-research-composing-gaming-etc/"><u>Ideal Laptops for College Use: Thoroughly Tested Picks for Research, Composing, Gaming, Etc.</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-planning-to-use-a-pokemon-go-joystick-on-samsung-galaxy-f14-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Planning to Use a Pokemon Go Joystick on Samsung Galaxy F14 5G? | Dr.fone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/in-depth-analysis-of-your-favorite-tech-by-toms-hardware-team/"><u>In-Depth Analysis of Your Favorite Tech by Tom's Hardware Team</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/innovative-chill-the-ultimate-id-cooling-frozn-a720-and-a620-air-cooler-reviews/"><u>Innovative Chill: The Ultimate ID-Cooling FROZN A720 & A620 Air Cooler Reviews</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/introducing-freezes-new-underwater-cooling-gadget-the-fanless-solid-state-waterproof-airjet-mini-sport-with-advanced-active-cooling-technology/"><u>Introducing Freeze's New Underwater Cooling Gadget: The Fanless, Solid-State Waterproof AirJet Mini Sport with Advanced Active Cooling Technology</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/leading-wireless-keyboard-innovations-unveiled-in-ndark-mode-enhance-productivity-and-style-with-a-theme-that-fits-every-mood-)(meta-nametwittercard-content3/"><u>Leading Wireless Keyboard Innovations Unveiled in nDark Mode: Enhance Productivity and Style with a Theme That Fits Every Mood /><Meta Name=twitter:card Content=summary_large_image></u></a></li>
<li><a href="https://hardware-tips.techidaily.com/master-your-gadgets-insightful-hardware-tips-from-toms-experience/"><u>Master Your Gadgets: Insightful Hardware Tips From Tom’s Experience</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-electronics-top-picks-and-reviews-by-toms-computing-experts/"><u>Mastering Electronics: Top Picks and Reviews by Tom's Computing Experts</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/most-affordable-3d-printer-offers-available-this-year/"><u>Most Affordable 3D Printer Offers Available This Year</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-gadgets-with-precision-the-toms-hardware-experts-speak-out/"><u>Navigating Gadgets with Precision: The Tom's Hardware Experts Speak Out</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/navigating-the-dynamic-world-of-drone-racing-and-top-5-high-speed-drones/"><u>Navigating the Dynamic World of Drone Racing & Top 5 High-Speed Drones</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-the-latest-gadgets-with-tom-a-comprehensive-guide/"><u>Navigating the Latest Gadgets with Tom - A Comprehensive Guide</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-the-tech-landscape-discoveries-at-toms-hardware/"><u>Navigating the Tech Landscape: Discoveries at Tom's Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-the-world-of-computing-with-tom-expert-insights/"><u>Navigating the World of Computing with Tom - Expert Insights</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-through-gadgets-and-components-with-expertise-from-toms-workshop/"><u>Navigating Through Gadgets and Components with Expertise From Tom's Workshop</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-through-silicon-and-circuits-a-dive-into-toms-hardware-collection/"><u>Navigating Through Silicon and Circuits - A Dive Into Tom's Hardware Collection</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/premium-cameras-for-next-level-music-video-production/"><u>Premium Cameras for Next-Level Music Video Production</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/smooth-printing-techniques-to-stop-your-3d-filament-from-tangling/"><u>Smooth Printing: Techniques to Stop Your 3D Filament From Tangling</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-selection-of-best-2024-motherboards-for-gamers-based-on-sockets-and-chipsets/"><u>The Ultimate Selection of Best 2024 Motherboards for Gamers Based on Sockets & Chipsets</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-insights-expert-reviews-and-advice/"><u>Tom's Tech Insights: Expert Reviews & Advice</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-insights-in-depth-computer-hardware-analysis/"><u>Tom's Tech Insights: In-Depth Computer Hardware Analysis</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/triumph-of-david-how-the-desktop-sls-kickstarter-campaign-culminated-in-a-surprise-buyout/"><u>Triumph of David: How the Desktop SLS Kickstarter Campaign Culminated in a Surprise Buyout</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/troubleshooting-your-3d-prints-a-step-by-step-solution-to-combat-pillowing-issues/"><u>Troubleshooting Your 3D Prints: A Step-by-Step Solution to Combat Pillowing Issues</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unraveling-tech-mysteries-at-toms-hardware-haven-reviews-tips-and-more/"><u>Unraveling Tech Mysteries at Tom's Hardware Haven: Reviews, Tips & More</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-efficiency-of-akasa-geckos-ssd-heatsink-with-blower-cooling-system-a-comprehensive-review/"><u>Unveiling the Efficiency of Akasa Gecko’s SSD Heatsink with Blower Cooling System – A Comprehensive Review</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-mysteries-of-toms-electronic-marvels-and-components/"><u>Unveiling the Mysteries of Tom's Electronic Marvels and Components</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/value-vs-power-in-cooling-tech-a-thorough-review-of-the-frozn-series-by-id-cooling/"><u>Value Vs. Power in Cooling Tech: A Thorough Review of the FROZN Series by ID-Cooling</u></a></li>
</ul></div>
