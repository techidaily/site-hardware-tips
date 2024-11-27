---
title: Comprehensive Update Resolves Major Flaws in Over 150 HP Printer Models by Printing Shellz | ZDNet
date: 2024-11-25T19:14:01.299Z
updated: 2024-11-27T18:39:58.785Z
tags:
  - printer
categories:
  - tech
thumbnail: https://thmb.techidaily.com/7e3fbcfe204dfbd52573599aedc96b853d77272f3befed715bed50ff29c06e5a.jpg
---

## Comprehensive Update Resolves Major Flaws in Over 150 HP Printer Models by Printing Shellz | ZDNet

![screenshot-2021-11-18-at-12-24-33.png](https://www.zdnet.com/a/img/resize/b638bc1117340e3e7e411473e389e70a5a0ceaa7/2021/11/18/34f27153-3810-4fdd-8223-40800769b2c5/screenshot-2021-11-18-at-12-24-33.png?auto=webp&width=1280)

F-Secure

HP has patched critical flaws impacting approximately 150 printer models. 

Printers are usually connected to business networks -- and potentially forgotten when it comes to security -- so they can easily provide an avenue of attack. Highlighting this issue is [PrintNightmare](https://www.zdnet.com/article/microsoft-fixes-windows-10-printnightmare-flaw-with-this-update/), CVE-2021-34481, a Windows Print Spooler service vulnerability that permits attackers to escalate privileges to system level, which was patched in August. In addition, HP patched a separate, 16-year-old privilege escalation[driver flaw in July](https://www.zdnet.com/article/hp-patches-vulnerable-printer-driver-impacting-millions-of-devices/). 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/58KlTPHv8dU?si=7ICagyNgrao7OkVO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Security

* [The best VPN services of 2024: Expert tested](https://www.zdnet.com/article/best-vpn/)
* [How to turn on Private DNS Mode on Android (and why you should)](https://www.zdnet.com/article/how-to-turn-on-private-dns-mode-on-android-and-why-you-should/)
* [The best antivirus software and apps you can buy](https://www.zdnet.com/article/best-antivirus/)
* [The best VPN routers you can buy](https://www.zdnet.com/article/best-vpn-router/)
* [How to find and remove spyware from your phone](https://www.zdnet.com/article/how-to-find-and-remove-spyware-from-your-phone/)

**Also:** [**Microsoft just revealed another Print Spooler bug**](https://www.zdnet.com/article/windows-10-microsoft-just-revealed-another-print-spooler-bug/)

Now, researchers from F-Secure have documented "[Printing Shellz](https://labs.f-secure.com/publications/printing-shellz)," a set of vulnerabilities impacting multifunction printers (MFPs). 

On Thursday, the research team said that their tests involved the HP MFP M725z. However, the vulnerabilities -- dating back to 2013 -- impact an estimated 150 products. These include models in the HP Color LaserJet Enterprise, HP LaserJet Enterprise, HP PageWide, HP OfficeJet Enterprise Color, and HP ScanJet Enterprise 8500 FN1 Document Capture Workstation ranges. 

The first issue the researchers discovered was [CVE-2021-39238](https://nvd.nist.gov/vuln/detail/CVE-2021-39238). Assigned a CVSS severity score of 9.3, this potential buffer overflow issue could allow the creation of a "self-propagating network worm capable of independently spreading to other vulnerable MFPs on the same network," according to F-Secure researchers Alexander Bolshev and Timo Hirvonen. 

The second issue, [CVE-2021-39237](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-39237) (CVSS 7.1), is described by HP as an information disclosure bug. F-Secure says this flaw was caused by exposed physical ports, so local access is required as an avenue for attack. 

It's possible to exploit these flaws locally via physical access to the device, such as by printing from USB. And when it comes to CVE-2021-39238, another potential attack vector involves sending an exploit payload directly from a browser via cross-site printing (XSP). 

"These vulnerabilities give attackers an effective way to steal information: defenders are unlikely to proactively examine the security of a printer, and so the attacker can simply sit back and steal whatever information it comes across (via employees printing, scanning, etc)," F-Secure comments. "They could also use the MFP as a pivot point to move through the corporate network." 

HP was informed of F-Secure's discoveries on April 29 and has since released two advisories ([1](https://support.hp.com/us-en/document/ish%5F5000383-5000409-16/hpsbpi03749),[2](https://support.hp.com/us-en/document/ish%5F5000124-5000148-16/hpsbpi03748)), detailing the vulnerabilities. Patches and firmware updates were released in November. 

There is no evidence of exploitation in the wild. 

"Any organizations using affected devices should install the patches as soon as they're available," the researchers say. "While exploiting these issues is somewhat difficult, the public disclosure of these vulnerabilities will help threat actors know what to look for to attack vulnerable organizations." 

---

**Have a tip?** Get in touch securely via WhatsApp | Signal at +447713 025 499, or over at Keybase: charlie0 

---

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
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-optimize-broadcasting-twitch-sessions-on-fb/"><u>[Updated] In 2024, Optimize Broadcasting Twitch Sessions on FB</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-personalize-your-online-story-mastery-in-fb-memories/"><u>[Updated] Personalize Your Online Story Mastery in FB Memories</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/adapting-office-equipment-for-the-age-of-artificial-intelligence-future-trends-and-insights/"><u>Adapting Office Equipment for the Age of Artificial Intelligence: Future Trends and Insights</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/beyond-the-ordinary-why-this-remarkably-sturdy-and-tailorable-laptop-outshines-getacs-in-real-user-reviews-zdnet-insights/"><u>Beyond the Ordinary: Why This Remarkably Sturdy and Tailorable Laptop Outshines Getacs in Real User Reviews | ZDNet Insights</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/cutting-edge-laptop-coolers-on-sale-this-cyber-weekend-beat-the-heat-with-top-picks/"><u>Cutting-Edge Laptop Coolers on Sale This Cyber Weekend - Beat the Heat with Top Picks !</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/discover-the-acer-swift-x-top-3-stunning-performance-revelations-in-my-testing-experience/"><u>Discover the Acer Swift X: Top 3 Stunning Performance Revelations in My Testing Experience</u></a></li>
<li><a href="https://fox-that.techidaily.com/fixing-fast-top-solutions-for-non-functional-predictive-emoji-on-ios-devices/"><u>Fixing Fast: Top Solutions for Non-Functional Predictive Emoji on iOS Devices</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-tecno-camon-20-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on Tecno Camon 20 online without jailbreak</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-poco-m6-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Poco M6 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-the-insiders-guide-to-slow-motion-with-photos-and-web-tools/"><u>In 2024, The Insider's Guide to Slow Motion with Photos & Web Tools</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-10-password-cracking-tools-for-motorola-moto-g14-by-drfone-android/"><u>In 2024, Top 10 Password Cracking Tools For Motorola Moto G14</u></a></li>
<li><a href="https://some-approaches.techidaily.com/samsung-unveils-a-giant-leap-forward-with-new-galaxy-ring-fold-and-flip-phones/"><u>Samsung Unveils a Giant Leap Forward with New Galaxy Ring, Fold & Flip Phones!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/samsungs-latest-innovation-the-copilotplus-laptop-an-unbeatable-bargain-for-windows-users-discover-why-at-zdnet/"><u>Samsung's Latest Innovation: The Copilot+ Laptop - An Unbeatable Bargain for Windows Users! Discover Why at ZDNet</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/unlock-your-boost-mobile-apple-iphone-6s-plus-before-the-plan-expires-by-drfone-ios/"><u>Unlock Your Boost Mobile Apple iPhone 6s Plus Before the Plan Expires</u></a></li>
</ul></div>

