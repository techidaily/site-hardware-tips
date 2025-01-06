---
title: Inside Tips on Electronics From Tom's Hardware Experts
date: 2025-01-04T12:12:26.020Z
updated: 2025-01-05T16:42:18.710Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/MC9WwgK8bJ99PhUas7KVcb-320-80.png
---

## Master the Latest Tech Trends with Tom's Hardware Reviews & Tips

Intel has[announced that it has found the root](https://community.intel.com/t5/Processors/July-2024-Update-on-Instability-Reports-on-Intel-Core-13th-and/m-p/1617113#M74792) [cause](https://community.intel.com/t5/Processors/July-2024-Update-on-Instability-Reports-on-Intel-Core-13th-and/m-p/1617113#M74792) of the crashing issues plaguing its CPUs. The company will issue a microcode update to address the issues by mid-August, ostensibly ending the long-running saga that began when the first sporadic reports of CPU crashing errors surfaced in December 2022 and grew to a crescendo by the end of 2023\. Intel's response comes after complaints about the issue, which causes PCs to inexplicably crash/BSOD during gaming and other workloads,[reached a fever pitch](https://www.tomshardware.com/pc-components/cpus/game-publisher-claims-100-crash-rate-with-intel-cpus-alderon-games-says-company-sells-defective-13th-and-14th-gen-chips) in recent weeks. However, the microcode update will not repair impacted processors. Intel also confirmed a rumored issue with via oxidation in its 7nm node, but said those issues were corrected in 2023 and didn't contribute to the failures.

 Intel's advisory says an erroneous CPU microcode is the root cause of the incessant instability issues. The microcode caused the CPU to request elevated voltage levels, resulting in the processor operating outside its safe boundaries. Intel is now validating a microcode patch to correct the issues, with its release slated for mid-August. This patch will be distributed through BIOS updates from motherboard OEMs and via Windows updates, so the timing for end-user availability could vary.

 The bug causes irreversible degradation of the impacted processors. We're told that the microcode patch will_not_ repair processors already experiencing crashes, but it is expected to prevent issues on processors that aren't currently impacted by the issue. For now, it is unclear if CPUs exposed to excessive voltage have suffered from invisible degradation or damage that hasn't resulted in crashes yet but could lead to errors or crashes in the future.

 Intel advises all customers having issues to seek help from its customer support. Because the microcode update will not repair impacted processors, the company will continue to replace them. Intel has pledged to grant RMAs to all impacted customers.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

 The company had previously advised its customers to stick with the basic power guidelines for its processors, rather than running them at fully unlocked settings, as it worked through the issues. Those instructions, [which you can see here](https://www.tomshardware.com/pc-components/cpus/intel-issues-official-statement-on-core-k-series-crashes-stick-to-intels-official-power-profiles) , remain in effect for now, and Intel hasn't issued any new workarounds for impacted customers. It is unclear if Intel will lift the existing restrictions after it issues the patch.

 Intel had previously[fixed an eTVB bug](https://www.tomshardware.com/pc-components/cpus/intel-denies-reports-that-it-identified-a-root-cause-for-core-i9-crashing-issues-investigation-continues) that contributed to the problems, but now says microcode is the root cause. We're told that the microcode patch currently doesn't exhibit any adverse performance impact (i.e., the chip running slower), but testing is ongoing. We can expect Intel to share more information about performance in the future.

 Intel isn't sharing many deep-dive details about the bug yet but says it will continue its validation process to ensure the microcode fully addresses the issues. The company will release more details about the bug itself in the future.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Stay On the Cutting Edge: Get the Tom's Hardware Newsletter

 Get Tom's Hardware's best news and in-depth reviews, straight to your inbox.

 Contact me with news and offers from other Future brands  Receive email from us on behalf of our trusted partners or sponsors

 By submitting your information you agree to the[Terms & Conditions](https://futureplc.com/terms-conditions/) and[Privacy Policy](https://futureplc.com/privacy-policy/) and are aged 16 or over.

 Today, the company also posted to Reddit that it had encountered rumored issues via oxidation in its Intel 7 process node in 2023\. Intel says that the issue was resolved and isn't the source of the Raptor Lake crashes.

 Intel has not issued a recall of its processors; sources close to the matter tell us that isn't expected. We have both of Intel's statements below.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UUPt2zKtJ5k?si=LLHdsFDLzVByJsKj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Intel statement on 13th- and 14th-Gen instability

 _"Based on extensive analysis of Intel Core 13th/14th Gen desktop processors returned to us due to instability issues, we have determined that elevated operating voltage is causing instability issues in some 13th/14th Gen desktop processors. Our analysis of returned processors confirms that the elevated operating voltage is stemming from a microcode algorithm resulting in incorrect voltage requests to the processor."_

 _"Intel is delivering a microcode patch which addresses the root cause of exposure to elevated voltages. We are continuing validation to ensure that scenarios of instability reported to Intel regarding its Core 13th/14th Gen desktop processors are addressed. Intel is currently targeting mid-August for patch release to partners following full validation."_

 _"Intel is committed to making this right with our customers, and we continue asking any customers currently experiencing instability issues on their Intel Core 13th/14th Gen desktop processors reach out to Intel Customer Support for further assistance."_

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-blue.techidaily.com/new-weaving-individual-snaps-into-a-cohesive-tapestry/"><u>[New] Weaving Individual Snaps Into a Cohesive Tapestry</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-cutting-edge-recording-win-11s-superior-camcorders-for-2024/"><u>[Updated] Cutting-Edge Recording Win 11'S Superior Camcorders for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-masterclass-enhancing-live-streams-with-360-cameras/"><u>2024 Approved Masterclass Enhancing Live Streams with 360° Cameras</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-the-science-behind-sharing-memes-unveiled/"><u>2024 Approved The Science Behind Sharing Memes Unveiled</u></a></li>
<li><a href="https://extra-information.techidaily.com/complete-visual-storytellers-guide-to-vsco-app/"><u>Complete Visual Storyteller's Guide to VSCO App</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/factory-reset-on-iphone-11-pro-max-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>Factory Reset on iPhone 11 Pro Max | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-disabled-apple-iphone-15-proipad-without-computer-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Disabled Apple iPhone 15 Pro/iPad Without Computer | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-complete-guide-to-usb-20-exploring-velocity-cabling-and-adapters/"><u>The Complete Guide to USB 2.0: Exploring Velocity, Cabling, and Adapters</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ultimate-picks-a-parent-and-pro-review-of-leading-kids-tablets-for-educational-fun-zdnet/"><u>Ultimate Picks: A Parent and Pro Review of Leading Kids' Tablets for Educational Fun | ZDNet</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unbelievable-sale-alert-secure-the-amazon-fire-hd-8-plus-for-less-than-half-price-zdnet-deals/"><u>Unbelievable Sale Alert: Secure the Amazon Fire HD 8 Plus for Less Than Half Price – ZDNet Deals</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unlikely-top-picks-for-film-buffs-discover-the-best-unexpected-tablet-reviewed-by-zdnet/"><u>Unlikely Top Picks for Film Buffs! Discover the Best Unexpected Tablet Reviewed by ZDnet</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unlocking-the-mystery-of-smart-sound-devices-in-apples-latest-computers-and-tablets/"><u>Unlocking the Mystery of Smart Sound Devices in Apple's Latest Computers and Tablets</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-elite-android-tablet-lineup-for-2eplus24-professional-evaluations-and-rankings-zdnet/"><u>Unveiling the Elite Android Tablet Lineup for 2E+24: Professional Evaluations and Rankings | ZDNET</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-revolutionary-blue-light-free-pc-with-dynamic-120hz-paper-like-screen-a-leap-forward-in-eye-comfort-and-vision-health/"><u>Unveiling the Revolutionary Blue-Light-Free PC with Dynamic 120Hz Paper-Like Screen: A Leap Forward in Eye Comfort and Vision Health</u></a></li>
</ul></div>

