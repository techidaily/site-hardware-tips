---
title: "Mac Keyboard Guide: Step-by-Step Process of Reconfiguring Your Command Key"
date: 2024-10-20T04:52:28.842Z
updated: 2024-10-20T20:59:11.571Z
tags:
  - laptops
categories:
  - tech
thumbnail: https://thmb.techidaily.com/d4c7cd2172ccba4bdb571077b4ff8032d0659877fcac86bca6c901b3999fdda4.jpg
---

## Securely Erase Sensitive Information From Your Windows PC: A Step-by-Step Guide to Protecting Privacy Without Cost - Insights

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
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-embarking-on-a-virtual-odyssey-through-yt-stories/"><u>[New] In 2024, Embarking on a Virtual Odyssey Through YT Stories</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-will-facebook-vids-air-on-tv-this-year-or-later/"><u>[New] In 2024, Will Facebook Vids Air On TV This Year or Later?</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-talent-release-form-for-filming-and-video-to-free-download/"><u>[New] Talent Release Form for Filming and Video to Free Download</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-the-ultimate-connectivity-handbook-for-insta-and-tik/"><u>[Updated] 2024 Approved The Ultimate Connectivity Handbook for Insta & Tik</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-speedy-shots-for-immersive-narratives/"><u>2024 Approved Speedy Shots for Immersive Narratives</u></a></li>
<li><a href="https://facebook.techidaily.com/facebook-app-accessing-spotifys-music-library/"><u>Facebook App: Accessing Spotify's Music Library</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-premier-iphone-x8-series-gif-apps-reviewed/"><u>In 2024, Premier iPhone X/8 Series GIF Apps Reviewed</u></a></li>
<li><a href="https://data-wizards.techidaily.com/rectifying-damaged-media-files-on-mac-systems/"><u>Rectifying Damaged Media Files on Mac Systems</u></a></li>
<li><a href="https://app-tips.techidaily.com/revolutionizing-work-how-ai-agents-forge-a-new-era-in-employment-insights-from-zdnet/"><u>Revolutionizing Work: How AI Agents Forge a New Era in Employment - Insights From ZDNet</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/tackling-thick-footprint-troubles-a-how-to-on-3d-print-perfection/"><u>Tackling Thick Footprint Troubles: A How-To on 3D Print Perfection</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/teamgroup-unveils-the-future-of-pc-maintenance-with-magnetic-features-on-their-iconic-t-force-siren-aio-cpu-coolers/"><u>TeamGroup Unveils the Future of PC Maintenance with Magnetic Features on Their Iconic T-Force Siren AIO CPU Coolers</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-comprehensive-guide-to-electronics-toms-insights/"><u>The Comprehensive Guide to Electronics - Tom's Insights</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/the-ultimate-list-of-5-benefits-that-make-buying-a-veil-printer-irresistible-this-black-friday/"><u>The Ultimate List of 5 Benefits That Make Buying a Veil Printer Irresistible This Black Friday</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-precision-tools-for-computers-and-hardware-enthusiasts/"><u>Tom's Precision Tools for Computers and Hardware Enthusiasts</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-rated-sweeping-game-displays-of-2024/"><u>Top Rated Sweeping Game Displays of 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/under-65-cooling-mastery-comparative-review-of-thermalrights-frozen-notte-and-the-aqua-elite-e360-v3/"><u>Under $65 Cooling Mastery: Comparative Review of Thermalright's Frozen Notte and the Aqua Elite E360 V3</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123740/7443" target="_top" id="2123740">
  <img src="//a.impactradius-go.com/display-ad/7443-2123740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

