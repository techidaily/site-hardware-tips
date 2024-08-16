---
title: Advanced Computing Tips From Tom's Hardware Experts
date: 2024-08-15T06:20:32.722Z
updated: 2024-08-16T06:20:32.722Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/7e6hjesKEr55uQWxGUPanF-320-80.jpg
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

<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Intel statement on 13th- and 14th-Gen instability

 _"Based on extensive analysis of Intel Core 13th/14th Gen desktop processors returned to us due to instability issues, we have determined that elevated operating voltage is causing instability issues in some 13th/14th Gen desktop processors. Our analysis of returned processors confirms that the elevated operating voltage is stemming from a microcode algorithm resulting in incorrect voltage requests to the processor."_

 _"Intel is delivering a microcode patch which addresses the root cause of exposure to elevated voltages. We are continuing validation to ensure that scenarios of instability reported to Intel regarding its Core 13th/14th Gen desktop processors are addressed. Intel is currently targeting mid-August for patch release to partners following full validation."_

 _"Intel is committed to making this right with our customers, and we continue asking any customers currently experiencing instability issues on their Intel Core 13th/14th Gen desktop processors reach out to Intel Customer Support for further assistance."_

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-data.techidaily.com/024-approved-crafting-a-digital-identity-simple-steps-to-create-businesspersonal-youtube-channels-on-smartphones/"><u>[New] 2024 Approved  Crafting a Digital Identity  Simple Steps to Create Business/Personal YouTube Channels on Smartphones</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-expert-guide-to-crafting-immersive-experiences-through-instagram-vids/"><u>[New] 2024 Approved  Expert Guide to Crafting Immersive Experiences Through Instagram Vids</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-top-5-zoom-transcribing-tools-free-and-paid-options-for-2024/"><u>[New] Top 5 Zoom Transcribing Tools  Free & Paid Options for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2023s-premier-8-hidden-video-downloaders-for-2024/"><u>[Updated] 2023'S Premier 8 Hidden-Video Downloaders for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-analyzing-youtube-rankings-what-drives-top-placement-in-2024/"><u>[Updated] Analyzing YouTube Rankings  What Drives Top Placement, In 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-facetime-call-screen-recording-the-beginners-guide-for-2024/"><u>[Updated] FaceTime Call Screen Recording  The Beginner's Guide for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-quick-guide-automating-mac-screenshot-via-shortcuts/"><u>[Updated] Quick Guide  Automating Mac Screenshot via Shortcuts</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-dynamic-enhancements-for-your-tiktok-projects/"><u>2024 Approved  Dynamic Enhancements for Your TikTok Projects</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/advanced-tech-analysis-by-professionals-at-toms-equipment-reviews/"><u>Advanced Tech Analysis by Professionals at Tom's Equipment Reviews</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/affordable-ice-floe-iceberg-thermal-unit-reviews-evaluating-the-quiet-cool-power-of-models-240-and-360/"><u>Affordable Ice FLOe Iceberg Thermal Unit Reviews: Evaluating the Quiet Cool Power of Models 240 & 360</u></a></li>
<li><a href="https://android-unlock.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-huawei-nova-y91-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Huawei Nova Y91</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/comprehensive-guide-to-the-corsair-air-a115-cpu-cooler-powerful-and-silent-but-costly/"><u>Comprehensive Guide to the Corsair Air A115 CPU Cooler: Powerful & Silent but Costly</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/comprehensive-hardware-insights-from-toms-computer-and-peripherals-blog/"><u>Comprehensive Hardware Insights From Tom's Computer & Peripherals Blog</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/comprehensive-review-the-new-standard-of-overclocking-with-id-coolings-frozn-a620-pro-se-ultimate-value-for-gamers-and-enthusiasts/"><u>Comprehensive Review: The New Standard of Overclocking with ID-Cooling's Frozn A620 Pro SE - Ultimate Value for Gamers and Enthusiasts</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/direct-die-and-grizzly-heatsinks-an-admission-of-error-by-der8auer/"><u>Direct Die and Grizzly Heatsinks – An Admission of Error by Der8auer</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ek-direct-die-aio-cooler-delivers-stellar-performance-boost-your-13900ks-with-up-to-20-degrees-of-improved-cooling-efficiency/"><u>EK Direct Die AiO Cooler Delivers Stellar Performance: Boost Your 13900KS with Up to 20 Degrees of Improved Cooling Efficiency</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-analysis-of-computer-hardware-by-tom/"><u>Expert Analysis of Computer Hardware by Tom</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-insights-on-gadgets-with-toms-hardware-guide/"><u>Expert Insights on Gadgets with Tom's Hardware Guide</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-computer-hardware-with-tom-comprehensive-guides-and-insights/"><u>Exploring Computer Hardware with Tom - Comprehensive Guides & Insights</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-computing-gear-with-tom-in-depth-hardware-analysis/"><u>Exploring Computing Gear with Tom - In-Depth Hardware Analysis</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-high-tech-equipment-the-ultimate-guide-by-tom-hardware/"><u>Exploring High-Tech Equipment - The Ultimate Guide by Tom Hardware</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/fixing-iphone-call-alert-issues-top-tricks-to-get-notifications-working-again/"><u>Fixing iPhone Call Alert Issues: Top Tricks to Get Notifications Working Again</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/get-the-cutting-edge-8k-sonic-mini-s-resin-printer-by-phrozen-at-an-unbeatable-low-of-325/"><u>Get the Cutting-Edge 8K Sonic Mini S RESIN Printer by Phrozen at an Unbeatable Low of $325!</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-forgotten-pin-of-your-vivo-x100-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Vivo X100</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-vivo-y17s-drfone-by-drfone-virtual/"><u>In 2024, 10 Fake GPS Location Apps on Android Of your Vivo Y17s | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-mastering-hero-10-ultimate-guide-for-l-slow-cinematography/"><u>In 2024, Mastering Hero 10  Ultimate Guide for L-Slow Cinematography</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-sharper-images-richer-minescapes-zoom-techniques-revealed/"><u>In 2024, Sharper Images, Richer Minescapes  Zoom Techniques Revealed</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/in-depth-analysis-of-bambu-lab-x1-carbon-3d-printer-the-industrys-top-performer/"><u>In-Depth Analysis of Bambu Lab X1-Carbon 3D Printer: The Industry's Top Performer</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/lamptrons-deceitful-tactics-unveiled-counterfeit-software-keys-for-new-screen-gadgets/"><u>Lamptron's Deceitful Tactics Unveiled – Counterfeit Software Keys for New Screen Gadgets</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/leading-hdd-options-best-picks-for-optimizing-your-pc-and-nas-systems/"><u>Leading HDD Options : Best Picks for Optimizing Your PC and NAS Systems</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/leading-laser-cutting-systems-in-2e24-buyers-guide/"><u>Leading Laser Cutting Systems in 2E24 - Buyer's Guide</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/low-cost-tech-fun-design-and-assemble-your-own-animation-ready-3d-printer-shaped-charger-with-bambu-labs-at-under-50/"><u>Low-Cost Tech Fun: Design and Assemble Your Own Animation-Ready 3D Printer Shaped Charger with Bambu Labs at Under $50</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/most-efficient-power-units-to-boost-your-crypto-mining-ventures-with-ethereum-and-bitcoin/"><u>Most Efficient Power Units to Boost Your Crypto Mining Ventures with Ethereum and Bitcoin</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-computer-specs-and-gadgets-at-toms-hardware-hub/"><u>Navigating Computer Specs & Gadgets at Tom's Hardware Hub</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-technology-with-toms-hardware-insight/"><u>Navigating Technology with Tom's Hardware Insight</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-mac-green-screen-software-top-picks-and-reviews/"><u>New 2024 Approved Mac Green Screen Software Top Picks and Reviews</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/new-report-exposes-misleading-material-claims-for-majority-of-tested-desktop-cooling-solutions-copper-scarcity-highlighted/"><u>New Report Exposes Misleading Material Claims for Majority of Tested Desktop Cooling Solutions, Copper Scarcity Highlighted</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/pioneering-computer-wisdom-from-toms-hardware-experts/"><u>Pioneering Computer Wisdom From Tom's Hardware Experts</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/revolutionary-quick-print-method-developed-by-mit-researchers-featuring-reusable-metal-scraps-and-bed-of-fine-glass-particles/"><u>Revolutionary Quick-Print Method Developed by MIT Researchers, Featuring Reusable Metal Scraps and Bed of Fine Glass Particles</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/revolutionizing-aerospace-the-international-space-station-welcomes-its-first-metal-3d-printer-engineered-by-airbus-and-the-esa/"><u>Revolutionizing Aerospace: The International Space Station Welcomes Its First Metal 3D Printer, Engineered by Airbus and the ESA</u></a></li>
<li><a href="https://fix-guide.techidaily.com/simple-solutions-to-fix-android-systemui-has-stopped-error-for-lava-blaze-2-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Simple Solutions to Fix Android SystemUI Has Stopped Error For Lava Blaze 2 Pro | Dr.fone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/slide-under-budget-stay-cool-below-45-with-the-deepcool-as500-plus-cpu-fan-on-amazon/"><u>Slide Under Budget: Stay Cool Below $45 with the DeepCool AS500 Plus CPU Fan on Amazon</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-guide-to-choosing-between-scythe-mugen-6-or-mugen-6-black-stylish-silent-solutions-for-savvy-shoppers/"><u>The Ultimate Guide to Choosing Between Scythe Mugen 6 or Mugen 6 Black: Stylish Silent Solutions for Savvy Shoppers</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-resource-for-hardware-comparisons-toms-tech-hub/"><u>The Ultimate Resource for Hardware Comparisons - Tom's Tech Hub</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-resource-for-top-tier-hardware-advice-by-toms-experts/"><u>The Ultimate Resource for Top-Tier Hardware Advice by Tom's Experts</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-review-in-depth-insights-into-cutting-edge-hardware/"><u>Tom's Tech Review: In-Depth Insights Into Cutting-Edge Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-rated-thermal-compounds-for-processors-comprehensive-ranking-of-90-options/"><u>Top-Rated Thermal Compounds for Processors - Comprehensive Ranking of 90 Options</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ultimate-selection-the-finest-raspberry-pi-cases-for-2n45s/"><u>Ultimate Selection: The Finest Raspberry Pi Cases for 2N45s</u></a></li>
<li><a href="https://unlock-android.techidaily.com/universal-unlock-pattern-for-tecno-pop-7-pro-by-drfone-android/"><u>Universal Unlock Pattern for Tecno Pop 7 Pro</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unlocking-gadget-secrets-a-look-at-toms-hardware/"><u>Unlocking Gadget Secrets: A Look at Tom's Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unlocking-tech-secrets-in-depth-reviews-from-toms-hardware/"><u>Unlocking Tech Secrets: In-Depth Reviews From Tom's Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unraveling-the-world-of-electronics-with-toms-equipment-insights/"><u>Unraveling the World of Electronics with Tom's Equipment Insights</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-latest-gadgets-with-tom-a-comprehensive-guide/"><u>Unveiling the Latest Gadgets with Tom - A Comprehensive Guide</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-latest-in-technology-a-trip-through-toms-hardware-world/"><u>Unveiling the Latest in Technology: A Trip Through Tom's Hardware World</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/your-ultimate-guide-to-hardware-evaluations-with-toms-insights/"><u>Your Ultimate Guide to Hardware Evaluations with Tom's Insights</u></a></li>
</ul></div>
