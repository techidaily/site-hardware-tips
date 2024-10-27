---
title: Rebinding the Command Key on Apple's Latest Mac Models – Easy Tutorial From ZDNet
date: 2024-10-24T22:27:45.958Z
updated: 2024-10-26T17:57:03.363Z
tags:
  - laptops
categories:
  - tech
thumbnail: https://www.zdnet.com/a/img/resize/b3d2215a7561e2f41c0d49f901f359a22cb0ec42/2022/12/08/ed2bb1d6-08c2-4a29-ac44-7f88c9bc5626/pxl-20221208-204842960.jpg?auto=webp&fit=crop&frame=1&height=172&precrop=3391,1905,x304,y163&width=306
---

## Ensuring Complete Data Removal From Your Windows Laptop: The Best Free Methods – Insights

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
<li><a href="https://youtube-data.techidaily.com/raphical-forecast-the-dominant-23-social-themes-for-2024/"><u>[New] Graphical Forecast The Dominant '23 Social Themes for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-transform-your-mac-with-the-latest-macos-11-big-sur-overview/"><u>[New] Transform Your Mac with the Latest MacOS 11 Big Sur Overview</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-pioneering-pedagogy-through-film-in-the-classroom-for-2024/"><u>[Updated] Pioneering Pedagogy Through Film in the Classroom for 2024</u></a></li>
<li><a href="https://discover-best.techidaily.com/can-you-share-hevc-h265-videos-on-youtube-a-comprehensive-guide/"><u>Can You Share HEVC (H.265) Videos on YouTube? A Comprehensive Guide</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/divide-the-total-distance-traveled-by-all-vehicles-by-the-circumference-of-the-earth-to-find-how-many-times-around-the-earth-this-distance-would-go/"><u>Divide the Total Distance Traveled by All Vehicles by the Circumference of the Earth to Find How Many Times Around the Earth This Distance Would Go.</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/download-android-14-beta-2-without-owning-a-pixel-device-now-available/"><u>Download Android 14 Beta 2 Without Owning a Pixel Device - Now Available</u></a></li>
<li><a href="https://fox-search.techidaily.com/download-your-favorite-netflix-films-anytime-with-pcmac-compatible-app/"><u>Download Your Favorite Netflix Films Anytime with PC/Mac Compatible App</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/effective-strategies-to-block-unwanted-robocalls-on-your-android-device/"><u>Effective Strategies to Block Unwanted Robocalls on Your Android Device</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/efficiently-execute-tasks-with-a-simple-tap-at-the-rear-of-your-android-smartphone/"><u>Efficiently Execute Tasks with a Simple Tap at the Rear of Your Android Smartphone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/effortless-ways-to-enable-auto-connect-to-wi-fi-networks-on-your-android-device/"><u>Effortless Ways to Enable Auto-Connect to Wi-Fi Networks on Your Android Device</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/elevating-affordable-mobile-tech-how-qualcomms-snapdragon/"><u>Elevating Affordable Mobile Tech: How Qualcomm’s Snapdragon</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/enhanced-durability-and-display-unveiling-samsungs-upgraded-galaxy-z-fold-5-with-superior-hinge-design-and-more-luminous-screen-technology/"><u>Enhanced Durability and Display: Unveiling Samsung's Upgraded Galaxy Z Fold 5 with Superior Hinge Design and More Luminous Screen Technology</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/essential-samsung-tech-innovations-for-future-google-pixel-devices/"><u>Essential Samsung Tech Innovations for Future Google Pixel Devices</u></a></li>
<li><a href="https://android-frp.techidaily.com/full-guide-to-bypass-realme-11-proplus-frp-by-drfone-android/"><u>Full Guide to Bypass Realme 11 Pro+ FRP</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1722167816805-harness-the-power-of-chatgpt-from-your-phone-now-for-android-users/"><u>Harness the Power of ChatGPT From Your Phone – Now for Android Users</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/passfab-iphone-11-backup-unlocker-top-4-alternatives-drfone-by-drfone-ios/"><u>PassFab iPhone 11 Backup Unlocker Top 4 Alternatives | Dr.fone</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/be-live-thumbnails-a-comprehensive-look-for-2024/"><u>YouTube Live Thumbnails A Comprehensive Look for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118314/7443" target="_top" id="2118314">
  <img src="//a.impactradius-go.com/display-ad/7443-2118314" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118314/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

