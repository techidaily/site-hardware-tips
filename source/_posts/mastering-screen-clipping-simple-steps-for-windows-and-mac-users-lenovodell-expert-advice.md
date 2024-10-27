---
title: "Mastering Screen Clipping: Simple Steps for Windows and Mac Users (Lenovo/Dell) - Expert Advice"
date: 2024-10-22T00:50:12.193Z
updated: 2024-10-26T16:23:39.983Z
tags:
  - laptops
categories:
  - tech
thumbnail: https://thmb.techidaily.com/185bd2e3ee5add750b89a3f134c1fcf3132bd93146cc3a0d22887acdb0a82b64.jpg
---

## Protecting Your Privacy: Expert Tips on Completely Wiping a Windows Computer Without Spending - Free Advice

![delete key on keyboard](https://www.zdnet.com/a/img/resize/d63e45ef5eb131dc96ab27bda73125ed344a82c5/2024/09/29/d681f9f6-c785-48e5-b76d-2d11b529a893/gettyimages-172972238.jpg?auto=webp&width=1280)

monkeypics/Getty Images

When you replace your old but still functional Windows PC with a shiny new model, you have several options for that gently used device. You can give it away to a friend or family member. You can donate it to a charitable organization like Goodwill (which partners with [Dell Reconnect](https://shop-links.co/link/?exclusive=1&publisher_slug=itechdaily19598&url=https%3A%2F%2Fwww.dell.com%2Fen-us%2Fdt%2Fcorporate%2Fsocial-impact%2Fadvancing-sustainability%2Fhow-to-recycle%2Ffaq.htm%23tab0%3D1)). You can even trade it in for credit or sell it on a third-party site like [Swappa](https://swappa.com/sell/laptop) or [Back Market](https://www.awin1.com/awclick.php?mid=18275&id=423585&clickref=zd-%5F%5FCOM%5FCLICK%5FID%5F%5F-dtp&ued=https%3A%2F%2Fwww.backmarket.com%2Fen-us%2Fbuyback%2Fhome). 

**Also: [Microsoft to start charging for Windows 10 updates next year. Here's how much](https://www.zdnet.com/article/microsoft-to-start-charging-for-windows-10-updates-next-year-heres-how-much/)**

Whichever course of action you take, though, your most important task is to **_permanently delete all your personal files_** from that PC before you pass it along. With a desktop PC, that might be as easy as swapping out the system drive for a new one. But that's usually not an option with a laptop, where replacing storage can be impossible or prohibitively expensive. 

For laptops and for desktops where you aren't replacing the system drive, the simplest route is to reset the PC, choosing the option to remove personal files and reinstall Windows. On a PC running Windows 10, go to Settings > Update & Security > Recovery. On a Windows 11 device, the Reset PC option is under Settings > System > Recovery. Make sure you choose the Remove Everything option, as shown here.

When you're resetting a PC to give away or sell, be sure to choose the Remove Everything option.

Screenshot by Ed Bott/ZDNET

It takes several prompts before you get to the actual reset option (you don't want to do this accidentally, after all) and if you dig through the settings you can find a Clean Disk option designed to remove all data in addition to removing your files. As an alternative, you can boot from Windows installation media, remove all existing disk partitions, and then perform a clean install.

Either option removes existing personal files, but Microsoft's documentation cautions that "the data erasure functionality is targeted at consumers and does not meet government and industry data erasure standards." As a result, it's possible that someone with advanced technical skills could use forensic tools or data recovery software to access some of the deleted information.

**Also: [How to upgrade your 'incompatible' Windows 10 PC to Windows 11](https://www.zdnet.com/article/how-to-upgrade-your-incompatible-windows-10-pc-to-windows-11/)**

On modern systems with solid-state drives, you can often find a management utility that includes a Secure Erase command. For Samsung SSDs, use the [Samsung Magician](https://shop-links.co/link/?exclusive=1&publisher_slug=itechdaily19598&url=https%3A%2F%2Fsemiconductor.samsung.com%2Fconsumer-storage%2Fmagician%2F) program. For Intel SSDs, download and install the [Intel Memory and Storage Tool](https://www.intel.com/content/www/us/en/download/19543/intel-memory-and-storage-tool-gui.html?v=t). SSDs from Crucial use the [Crucial Storage Executive utility](https://www.crucial.com/support/storage-executive). Microsoft Surface devices support a custom tool called the [Microsoft Surface Data Eraser](https://learn.microsoft.com/en-us/surface/surface-it-toolkit-data-eraser); check the download links in that article to determine whether you need the newer IT Toolkit or the Legacy version for older Surface devices.

Some third-party partition management tools include the option to wipe a disk completely. My favorite for this task is [MiniTool Partition Wizard](https://www.partitionwizard.com/), which includes the Wipe Disk option in free and paid versions.

**Also: [Ditch the Wi-Fi: How to add a wired network to your home without Ethernet cable](https://www.zdnet.com/home-and-office/work-life/ditch-the-wi-fi-how-to-add-a-wired-network-to-your-home-without-ethernet-cable/)**

You also can use Windows' built-in encryption tools to ensure that the entire system drive, including unused disk space, is encrypted before performing a clean install. That extra step requires some additional time, but it ensures that any data recovered from anywhere on the drive will be unreadable. And you don't need any third-party software to get the job done.

Your system drive is fully encrypted by default if you've signed in to Windows with a Microsoft account on a modern device that supports BitLocker Device Encryption (BDE). To confirm that your device supports BDE, run the System Information utility (Msinfo32.exe) as an administrator and check the Device Encryption Support entry at the bottom of the System Summary page.

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

On a system running Windows 10 Pro or Windows 11 Pro, you can use the Manage BitLocker utility (type BitLocker in the search box to find it) to encrypt the system drive and any data drives. Be sure to choose the option to encrypt the entire drive and not just the space that currently contains data.

**Also: [Where's your BitLocker recovery key? How to save a copy before the next Windows meltdown](https://www.zdnet.com/article/wheres-your-bitlocker-recovery-key-how-to-save-a-copy-before-the-next-windows-meltdown/)**

If Device Encryption isn't available, open a command prompt using the Run As Administrator option and enter this command:

**Cipher /W:C:\\**

That command "zeroes out" unused disk space, overwriting it so that it can't be recovered. This process can take a long time, so consider letting it run overnight while you concentrate on more important tasks.

_This article was originally published on May 12, 2022, and last updated on September 29, 2024\._ 

#### Featured

[Why I'm recommending the standard iPhone 16 over the Pro this year (and I'm not alone)](https://www.zdnet.com/article/why-im-recommending-the-standard-iphone-16-over-the-pro-this-year-and-im-not-alone/ "Why I'm recommending the standard iPhone 16 over the Pro this year (and I'm not alone)")

[Is OneDrive messing with your files? How to get your Windows storage under control](https://www.zdnet.com/article/is-onedrive-messing-with-your-files-how-to-get-your-windows-storage-under-control/ "Is OneDrive messing with your files? How to get your Windows storage under control")

[Best early Prime Day deals under $50 to shop in October 2024](https://www.zdnet.com/article/best-early-prime-day-deals-under-50/ "Best early Prime Day deals under $50 to shop in October 2024")

[Rust in Linux now: Progress, pitfalls, and why devs and maintainers need each other](https://www.zdnet.com/article/rust-in-linux-now-progress-pitfalls-and-why-devs-and-maintainers-need-each-other/ "Rust in Linux now: Progress, pitfalls, and why devs and maintainers need each other")

* [Why I'm recommending the standard iPhone 16 over the Pro this year (and I'm not alone)](https://www.zdnet.com/article/why-im-recommending-the-standard-iphone-16-over-the-pro-this-year-and-im-not-alone/ "Why I'm recommending the standard iPhone 16 over the Pro this year (and I'm not alone)")
* [Is OneDrive messing with your files? How to get your Windows storage under control](https://www.zdnet.com/article/is-onedrive-messing-with-your-files-how-to-get-your-windows-storage-under-control/ "Is OneDrive messing with your files? How to get your Windows storage under control")
* [Best early Prime Day deals under $50 to shop in October 2024](https://www.zdnet.com/article/best-early-prime-day-deals-under-50/ "Best early Prime Day deals under $50 to shop in October 2024")
* [Rust in Linux now: Progress, pitfalls, and why devs and maintainers need each other](https://www.zdnet.com/article/rust-in-linux-now-progress-pitfalls-and-why-devs-and-maintainers-need-each-other/ "Rust in Linux now: Progress, pitfalls, and why devs and maintainers need each other")

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
<li><a href="https://article-helps.techidaily.com/new-a-comprehensive-list-of-15-competitors-to-gopro-cameras-for-2024/"><u>[New] A Comprehensive List of 15 Competitors to GoPro Cameras for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-go-live-in-style-a-detailed-guide-to-youtubes-full-sphere-videos/"><u>[Updated] Go Live in Style A Detailed Guide to YouTube's Full-Sphere Videos</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-mastering-monetization-a-beginners-guide-to-facebook-revenue/"><u>2024 Approved Mastering Monetization A Beginner’s Guide to Facebook Revenue</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/advanced-insights-from-toms-hardware-for-gamers-and-professionals/"><u>Advanced Insights From Tom's Hardware for Gamers and Professionals</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/beyond-the-headlines-cooler-master-addresses-the-ai-thermal-paste-miscommunication-in-cryofuze-5-specs/"><u>Beyond the Headlines: Cooler Master Addresses the 'AI Thermal Paste' Miscommunication in CryoFuze 5 Specs</u></a></li>
<li><a href="https://tech-revival.techidaily.com/comment-transformer-avec-elegance-votre-video-hevc-en-un-fichier-mp4-clair-sans-deterioration-visuelle/"><u>Comment Transformer Avec Élégance Votre Vidéo HEVC en Un Fichier MP4 Clair Sans Détérioration Visuelle</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/cookiebot-driven-website-optimization-boosting-your-online-presence/"><u>Cookiebot-Driven Website Optimization: Boosting Your Online Presence</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/decoding-digital-advancements-through-toms-perspective/"><u>Decoding Digital Advancements Through Tom's Perspective</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/economical-precision-the-elegoo-neptune-4-pro-laser-priced-at-284/"><u>Economical Precision: The Elegoo Neptune 4 Pro Laser Priced at $284</u></a></li>
<li><a href="https://discover-exclusive.techidaily.com/expert-tipps-wiederherstellung-von-flash-speicherpartitionen-mit-command-prompt/"><u>Expert Tipps: Wiederherstellung Von Flash-Speicherpartitionen Mit Command Prompt</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/explore-the-worlds-biggest-event-for-3d-enthusiasts-rapid-plus-tct-2024-highlights-and-innovations/"><u>Explore the World's Biggest Event for 3D Enthusiasts: Rapid + TCT 2024 Highlights and Innovations</u></a></li>
<li><a href="https://win-solutions.techidaily.com/fixes-for-mir4-crashing-issues-expert-solutions/"><u>Fixes for Mir4 Crashing Issues: Expert Solutions</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-rootjunky-apk-to-bypass-google-frp-lock-for-oneplus-by-drfone-android/"><u>In 2024, Rootjunky APK To Bypass Google FRP Lock For OnePlus</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-technology-trends-with-toms-hardware-reviews/"><u>Mastering Technology Trends with Tom's Hardware Reviews</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigate-the-complexity-of-ai-with-googles-browser-extension/"><u>Navigate the Complexity of AI with Google’s Browser Extension</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-guide-to-perfect-blemish-free-3d-printing-results/"><u>The Ultimate Guide to Perfect, Blemish-Free 3D Printing Results</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2112008/7443" target="_top" id="2112008">
  <img src="//a.impactradius-go.com/display-ad/7443-2112008" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2112008/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

