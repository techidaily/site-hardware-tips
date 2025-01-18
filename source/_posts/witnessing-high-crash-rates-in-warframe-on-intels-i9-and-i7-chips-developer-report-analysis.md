---
title: "Witnessing High Crash Rates in Warframe on Intel's I9 and I7 Chips: Developer Report Analysis"
date: 2025-01-15T17:02:51.770Z
updated: 2025-01-18T16:02:04.533Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Stay On the Cutting Edge: Get the Tom's Hardware Newsletter

 Get Tom's Hardware's best news and in-depth reviews, straight to your inbox.

 Contact me with news and offers from other Future brands  Receive email from us on behalf of our trusted partners or sponsors

 By submitting your information you agree to the[Terms & Conditions](https://futureplc.com/terms-conditions/) and[Privacy Policy](https://futureplc.com/privacy-policy/) and are aged 16 or over.

 Today, the company also posted to Reddit that it had encountered rumored issues via oxidation in its Intel 7 process node in 2023\. Intel says that the issue was resolved and isn't the source of the Raptor Lake crashes.

 Intel has not issued a recall of its processors; sources close to the matter tell us that isn't expected. We have both of Intel's statements below.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Intel statement on 13th- and 14th-Gen instability

 _"Based on extensive analysis of Intel Core 13th/14th Gen desktop processors returned to us due to instability issues, we have determined that elevated operating voltage is causing instability issues in some 13th/14th Gen desktop processors. Our analysis of returned processors confirms that the elevated operating voltage is stemming from a microcode algorithm resulting in incorrect voltage requests to the processor."_

 _"Intel is delivering a microcode patch which addresses the root cause of exposure to elevated voltages. We are continuing validation to ensure that scenarios of instability reported to Intel regarding its Core 13th/14th Gen desktop processors are addressed. Intel is currently targeting mid-August for patch release to partners following full validation."_

 _"Intel is committed to making this right with our customers, and we continue asking any customers currently experiencing instability issues on their Intel Core 13th/14th Gen desktop processors reach out to Intel Customer Support for further assistance."_

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/58KlTPHv8dU?si=7ICagyNgrao7OkVO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-redirect-saved-image-to-custom-folder-on-mac/"><u>[New] In 2024, Redirect Saved Image to Custom Folder on Mac</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-uncovering-untapped-territories-in-meme-culture/"><u>[New] Uncovering Untapped Territories in Meme Culture</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-elevate-your-digital-identity-top-101-masterclass-in-personal-bios-for-2024/"><u>[Updated] Elevate Your Digital Identity Top 101 Masterclass in Personal Bios for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-navigating-the-process-of-verifying-your-youtube-id/"><u>[Updated] Navigating the Process of Verifying Your YouTube ID</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-streamlined-social-media-prime-twitter-unfollow-tools-overview/"><u>[Updated] Streamlined Social Media Prime Twitter Unfollow Tools Overview</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/benchmarking-the-future-in-depth-analysis-on-top-gaming-laptops-in-202/"><u>Benchmarking The Future: In-Depth Analysis on Top Gaming Laptops in 202</u></a></li>
<li><a href="https://tech-revival.techidaily.com/convert-amr-audio-files-to-mp3-top-4-methods-for-all-devices/"><u>Convert AMR Audio Files to MP3: Top 4 Methods for All Devices</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/dominating-desktops-top-performance-analysis-of-the-id-cooling-frozn-series-a720-and-a620-air-cooling-unleashed/"><u>Dominating Desktops: Top Performance Analysis of the ID-Cooling FROZN Series (A720 & A620) - Air Cooling Unleashed</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/high-performance-vs-low-cost-gaming-ram-of-2024-options-and-reviews/"><u>High Performance Vs. Low Cost Gaming RAM of 2024: Options and Reviews</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-apple-iphone-15-pro-max-data-from-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Apple iPhone 15 Pro Max Data From iCloud? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-call-logs-from-your-redmi-note-12-5g-by-fonelab-android-recover-call-logs/"><u>How to recover old call logs from your Redmi Note 12 5G?</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-apple-iphone-14-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, Additional Tips About Sinnoh Stone For Apple iPhone 14 Plus | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-reset-a-locked-tecno-spark-10c-phone-by-drfone-android/"><u>In 2024, How to Reset a Locked Tecno Spark 10C Phone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/master-the-art-of-merging-multiple-filaments-into-a-single-cylinder-quickly-and-easily/"><u>Master the Art of Merging Multiple Filaments Into a Single Cylinder Quickly and Easily</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/master-your-pcs-temperature-with-the-latest-id-cooling-review-a720-and-a620-series-unveiled/"><u>Master Your PC's Temperature with the Latest ID-Cooling Review: A720 and A620 Series Unveiled</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-selection-of-premium-3d-printing-filaments/"><u>The Ultimate Selection of Premium 3D Printing Filaments</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-hub-a-detailed-look-at-comprehensive-computer-insights/"><u>Tom's Tech Hub: A Detailed Look at Comprehensive Computer Insights</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unlocking-performance-the-complete-guide-from-toms-hardware/"><u>Unlocking Performance: The Complete Guide From Tom's Hardware</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-lamptrons-misuse-of-fake-aida64-license-keys-in-their-display-units/"><u>Unveiling Lamptron's Misuse of Fake AIDA64 License Keys in Their Display Units</u></a></li>
</ul></div>

