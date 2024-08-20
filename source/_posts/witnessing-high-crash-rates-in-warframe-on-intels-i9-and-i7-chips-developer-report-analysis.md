---
title: "Witnessing High Crash Rates in Warframe on Intel's I9 and I7 Chips: Developer Report Analysis"
date: 2024-08-19T03:56:06.731Z
updated: 2024-08-20T03:56:06.731Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://thmb.techidaily.com/400ab6b2d84e9fcc703013e683c9e38470acb071407495f0911dc7de431c6c41.jpg
---

## Exploring Innovation in Computers and Gaming - Dive Into Tom's Hardware Insights

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

## Intel statement on 13th- and 14th-Gen instability

 _"Based on extensive analysis of Intel Core 13th/14th Gen desktop processors returned to us due to instability issues, we have determined that elevated operating voltage is causing instability issues in some 13th/14th Gen desktop processors. Our analysis of returned processors confirms that the elevated operating voltage is stemming from a microcode algorithm resulting in incorrect voltage requests to the processor."_

 _"Intel is delivering a microcode patch which addresses the root cause of exposure to elevated voltages. We are continuing validation to ensure that scenarios of instability reported to Intel regarding its Core 13th/14th Gen desktop processors are addressed. Intel is currently targeting mid-August for patch release to partners following full validation."_

 _"Intel is committed to making this right with our customers, and we continue asking any customers currently experiencing instability issues on their Intel Core 13th/14th Gen desktop processors reach out to Intel Customer Support for further assistance."_

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
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
<li><a href="https://extra-hints.techidaily.com/updated-big-sur-basics-system-and-hardware-checklist/"><u>[Updated] Big Sur Basics  System & Hardware Checklist</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-finding-the-perfect-screen-recorder-for-games/"><u>[Updated] In 2024, Finding the Perfect Screen Recorder for Games</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-master-content-creation-video-and-photo-synergy/"><u>[Updated] Master Content Creation  Video & Photo Synergy</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-spectrum-mastery-in-depth-color-techniques/"><u>2024 Approved  Spectrum Mastery  In-Depth Color Techniques</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/addressing-the-rattling-sound-issues-noctuas-nh-d15-g2-cpu-heatsink-investigation/"><u>Addressing the Rattling Sound Issues: Noctua's NH-D15 G2 CPU Heatsink Investigation</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/advanced-tips-for-choosing-cutting-edge-technology-from-tom/"><u>Advanced Tips for Choosing Cutting-Edge Technology From Tom</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723175648192-affordable-pc-temperature-control-with-deepcools-as500-plus-at-just-under-45-on-amazon/"><u>Affordable PC Temperature Control with DeepCool's AS500 Plus at Just Under $45 on Amazon!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/arctic-freezer-36xl-reviews-elevating-entry-level-chill-with-innovative-technology/"><u>Arctic Freezer 36XL Reviews: Elevating Entry-Level Chill with Innovative Technology</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/aspiring-youtubers-guide-to-affiliate-allies-for-2024/"><u>Aspiring YouTubers' Guide to Affiliate Allies for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/best-budget-gaming-pcs-for-less-than-a-grand/"><u>Best Budget Gaming PCs for Less Than a Grand</u></a></li>
<li><a href="https://tech-revival.techidaily.com/combatting-fraudgpt-essential-self-defense-tips/"><u>Combatting FraudGPT: Essential Self-Defense Tips</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/diy-animated-wireless-charger-in-the-shape-of-a-3d-printer-save-over-50-with-bambu-labs/"><u>DIY Animated Wireless Charger in the Shape of a 3D Printer: Save Over $50 with Bambu Labs</u></a></li>
<li><a href="https://facebook.techidaily.com/double-tap-deception-verifying-profiles-authenticity/"><u>Double-Tap Deception: Verifying Profiles' Authenticity</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/evaluating-the-creality-cr10s-impressive-specs-marred-by-dimensional-issues/"><u>Evaluating the Creality CR10s - Impressive Specs Marred by Dimensional Issues</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-roundup-performance-analysis-of-120mm-all-in-one-coolers-by-be-quiet-corsair-cooler-master-and-enermax/"><u>Expert Roundup: Performance Analysis of 120Mm All-in-One Coolers by Be Quiet, Corsair, Cooler Master & Enermax</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-pioneer-dj-ddj-sx2-control-app-swift-and-simple-download/"><u>Get the Pioneer DJ DDJ-SX2 Control App - Swift and Simple Download</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-lock-your-vivo-y100-5g-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Vivo Y100 5G Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-strategic-use-of-hashtags-in-gaming-vlog-production/"><u>In 2024, Strategic Use of Hashtags in Gaming Vlog Production</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/inside-the-world-of-technology-with-toms-hardware-guide/"><u>Inside the World of Technology with Tom's Hardware Guide</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-gadgets-and-pcs-the-ultimate-toms-hardware-compilation/"><u>Mastering Gadgets and PCs: The Ultimate Tom's Hardware Compilation</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-technology-choices-top-insights-from-toms-hardware-reviews/"><u>Mastering Technology Choices: Top Insights From Tom's Hardware Reviews</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-computer-specs-and-gadgets-on-toms-hardware/"><u>Navigating Computer Specs and Gadgets on Tom's Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-electronics-wisdom-insights-from-toms-expert-hardware-reviews/"><u>Navigating Electronics Wisdom: Insights From Tom's Expert Hardware Reviews</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-the-latest-in-electronics-a-closer-look-by-tom/"><u>Navigating the Latest in Electronics - A Closer Look by Tom</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/revolutionary-innovation-enables-homemade-creation-of-robot-hands-in-one-simple-print-bringing-3d-bioprinting-closer-to-home/"><u>Revolutionary Innovation Enables Homemade Creation of Robot Hands in One Simple Print - Bringing 3D Bioprinting Closer to Home</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-insights-exploring-the-latest-in-hardware/"><u>Tom's Tech Insights: Exploring the Latest in Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-review-comprehensive-guide-to-the-latest-gadgets/"><u>Tom's Tech Review: Comprehensive Guide to the Latest Gadgets</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-tech-insights-the-complete-guide-from-toms-gadget-review/"><u>Top Tech Insights: The Complete Guide From Tom's Gadget Review</u></a></li>
<li><a href="https://fox-helps.techidaily.com/tread-lightly-in-the-digital-jungle-vr-fitness-machines-examined/"><u>Tread Lightly in the Digital Jungle  VR Fitness Machines Examined</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshoot-windows-usb-serial-not-working/"><u>Troubleshoot Windows USB Serial Not Working</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-tech-secrets-with-toms-gear-wisdom/"><u>Unveiling Tech Secrets with Tom's Gear Wisdom</u></a></li>
<li><a href="https://win-answers.techidaily.com/1723010322610-windows-11-users-rejoice-as-origin-opens-without-problems-solutions-inside/"><u>Windows 11 Users Rejoice as 'Origin' Opens Without Problems - Solutions Inside!</u></a></li>
</ul></div>
