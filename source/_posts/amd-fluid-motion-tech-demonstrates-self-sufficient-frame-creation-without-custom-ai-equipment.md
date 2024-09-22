---
title: AMD Fluid Motion Tech Demonstrates Self-Sufficient Frame Creation Without Custom AI Equipment
date: 2024-09-15T04:21:12.063Z
updated: 2024-09-21T23:00:45.193Z
tags:
  - hardware
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/an-amd-graphics-card-with-the-text-fluid-motion-frames-and-some-no-ai-icons-1.jpg
---

## AMD Fluid Motion Tech Demonstrates Self-Sufficient Frame Creation Without Custom AI Equipment

### Quick Links

* [What Is AMD Fluid Motion Frames?](https://article-knowledge.techidaily.com/updated-is-auroras-hdr-enhancing-your-viewing-experience-for-2024/)
* [AFMF 2 Isn’t Out Yet, but You Can Try the Preview](https://fix-guide.techidaily.com/how-to-unbrick-a-dead-lava-blaze-2-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/)
* [Testing AFMF 2 in Games](https://youtube-video-recordings.techidaily.com/new-constructing-a-custom-youtube-subscription-url/)

### Key Takeaways

* AMD Fluid Motion Frames (AFMF) generates interpolated frames to double FPS on all RDNA 2 GPUs.
* AFMF 2 adds "AI-optimized enhancements" with a 28% latency reduction compared to AFMF 1.
* AFMF 2 supports multiple modes, including Search Mode for "fallback" adjustment and Performance Mode for performance and quality preference.

 While NVIDIA has been working hard on their AI frame generation technology in the form of DLSS 3, which is only supported on the latest RTX 40-Series GPUs, AMD is essentially doing the opposite with driver-based Fluid Motion Frames. The technology has just been updated. Let's see if it's good.

##  What Is AMD Fluid Motion Frames?

 AMD Fluid Motion Frames (AFMF) is a frame generation algorithm that interpolates frames similarly to AMD's upscaling technology [FSR](https://review-topics.techidaily.com/how-to-update-iphone-xs-max-to-the-latest-iosipados-version-drfone-by-drfone-ios-system-repair-ios-system-repair/). In simple terms, AFMF adds an additional interpolated frame between two real frames to, quite literally, give you more frames per second. It can literally double your FPS. AFMF is not the same as FSR, as it doesn't rely on upscaling from a lower resolution, which sounds like it should work better at lower resolutions, like 1080p.

 What makes AFMF different from NVIDIA's DLSS is that it doesn't rely on hardware-accelerated AI powered by fancy AI Tensor Cores. Instead, AFMF is a driver-based solution, which is how AMD was able to add it to my aging RX 6600 XT. AFMF works on all RDNA 2 (and presumably newer) GPUs, which includes the RX 6000 and 7000 Series graphics cards, and select [APUs](https://youtube-videos.techidaily.com/diy-split-screen-video-tutorials-for-youtube-enthusiasts-for-2024/) with Radeon graphics.

 AFMF was released in January of this year, and it frankly wasn't that good. James Archer from [Rock Paper Shotgun](https://www.rockpapershotgun.com/should-you-bother-with-amd-fluid-motion-frames) said that it filled his games with jittery images and constant stutter. The good news is that AMD has now released a preview of [Fluid Motion Frames 2](https://community.amd.com/t5/gaming/amd-fluid-motion-frames-2-technical-preview-now-available/ba-p/697448/jump-to/first-unread-message), which has added "AI-optimized enhancements," promising to improve both image fidelity and performance. For instance, it promises an average 28% reduction in latency compared to AFMF 1\. However, we'll have to see independent tests to see if the claim is true.

![AFMF 2 Cyberpunk 2077 latency.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/afmf-2-cyberpunk-2077-latency-chart3.png) 

AMD

 A major change is the addition of two new modes, Search Mode and Performance Mode. AMD calls them "modes," but you can think of them as settings that adjust how AFMF works. The first iteration of the technology was just an on/off toggle, so it's great to see some options.

 Search Mode adjusts "fallback," which describes when AFMF gets temporarily disabled to minimize jitter in intense scenes. You can select between "Standard" and "High" or leave it on Auto. "High" reduces fallback and is recommended on resolutions of 1400p or above, whereas "Standard" is for 1080p.

 Performance Mode also has an "Auto" option, but you can choose between "Quality" and "Performance," depending on whether you want a better image or more FPS. "Performance" is primarily designed for APUs, so leave it on "Quality" or "Auto" if you have a dedicated graphics card.

 Since AFMF is part of the [AMD HYPR-RX](https://www.amd.com/en/products/software/adrenalin/hypr-rx.html) product stack, it best works in conjunction with other AMD technologies. AFMF works really well with Anti-Lag, which reduces input lag by aligning the pace of the CPU with the GPU. Anti-Lag is only compatible with an AMD CPU, and the latest iteration, Anti-Lag 2, can further reduce input lag because it's now [integrated into select games](https://community.amd.com/t5/gaming/amd-radeon-anti-lag-2-technical-preview-now-available-in-counter/ba-p/686012), and it won't [get you banned](https://www.theverge.com/2023/10/14/23916966/cs2-counter-strike-2-anti-lag-plus-ban-amd-gpu-radeon-rx-7000) as Anti-Lag+ did.

![The AMD RX 6600 XT Phantom Gaming D graphics card inside of a computer.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/rsz_img20240413025619.jpg) 

Ismar Hrnjicevic / How-To Geek

 Another technology that AFMF works well with is Chill, which is AMD's built-in frame limiter. When it detects motion, it aims to reach your "Peak FPS" setting, and when the screen is idle, Chill targets the "Idle FPS" instead.

 The reason why you want to use Chill with AFMF is to limit your maximum frame rate to avoid screen tearing in games where your FPS exceeds your screen's refresh rate. Just note that it should be set to half of your maximum refresh rate when AFMF is enabled.

 For instance, I have a 144Hz monitor, so I set my Idle and Peak FPS to 71 FPS, which gives me a bit of headroom by limiting my maximum FPS with AFMF to 142\. The only caveat is that Chill currently doesn't work with Anti-Lag, so only use Chill if you exceed your maximum refresh rate at the highest in-game graphics settings.

![AMD Chill set to 71 FPS.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/chill.png) 

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1013424/11832" target="_top" id="1013424">
  <img src="//a.impactradius-go.com/display-ad/11832-1013424" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1013424/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  AFMF 2 Isn’t Out Yet, but You Can Try the Preview

 AFMF 2 isn't out yet, but you can already [download the Preview Driver](https://www.amd.com/en/resources/support-articles/release-notes/RN-RAD-WIN-AFMF2-TECH-Preview.html) and try it, assuming you have a compatible AMD GPU (RX 6000 or 7000 Series) or APU (AMD 700M). Once you've downloaded and installed the driver, restart your PC. Next, open AMD Software and head over to Gaming > Graphics > Custom. Look for "AMD Fluid Motion Frames" and click on the toggle to enable it.

![Enabling Fluid Motion Frames 2 in AMD Software.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/enable-fmf.png) 

 AFMF 2 should work in most games, as it now supports OpenGL and Vulkan in addition to DirectX 11 and 12\. [Vulkan](https://tiktok-videos.techidaily.com/2024-approved-mastering-tiktok-update-your-video-framing/) is a low-overhead API that already boasts significant FPS improvements in select titles compared to DirectX and OpenGL. Adding AFMF 2 into the mix could bring select titles to even the weakest of AMD's hardware.

<!-- affiliate ads begin -->
<span id="1516072">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1516072.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1516072">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1516072.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1516072%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1516072/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Testing AFMF 2 in Games

 Enough talk; it's time to give AFMF 2 a shot by testing it in a few games. I'll use my RX 6600 XT graphics card (which doesn't support Anti-Lag 2) on my 1080p 144Hz monitor for these tests. The first game I tested was _Fallout 76_, a game that still has serious performance issues.

 I tested my FPS in a busy area with lots of enemies and got an average FPS of 48\. I enabled AFMF 2 by simply alt-tabbing to the driver, and my FPS immediately doubled to an average of 96 without even having to restart the game. I saw similar results in _Returnal_, where my average FPS went from 40–45 to around 90.

![A screenshot from the game 'Fallout 76.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/f76.png) 

 AMD's performance overlay suggested that AFMF 2 added about 8–13 ms of frame generation lag, but I couldn't notice it. I didn't see any noticeable visual artifacts, either. What I _did_ notice was the significantly smoother performance. The only weird thing is that Fallout 76 would get extremely choppy in situations where my FPS dropped to 60–70, but this is more of an issue with the game itself. I see similar frame drops when AFMF 2 is disabled, and if anything, AFMF 2 makes it slightly less choppy.

 I tried enabling AMD Chill, but the game became noticeably blurry, and I could now feel the increased input lag. I figured _Hades 2_ would be a better game to test Chill, as I consistently got 144 FPS without AFMF 2, but the game kept crashing my whole system with AFMF 2 enabled. I suppose early access games and preview drivers don't mix. _Battlefield V_ felt like I was playing in slow-motion with AFMF 2, but it's an older game that doesn't handle Anti-Lag, either. So, I tried AFMF 2 and Chill in _Rocket League_ instead.

 To my great surprise, Rocket League ran perfectly when I combined AFMF 2 and Chill. I alternated between running the game with AFMF 2 and Chill enabled and without them, and I couldn't feel or see a difference. The frame gen lag was around 7–8ms, low enough that you likely can't notice it. Granted, this isn't a game where I'd use AFMF 2 because I don't need it, but I was still impressed by the result. If you play Rocket League with AFMF 2, you won't be able to blame a missed shot on the technology!

---

 While the high FPS achieved through AFMF 2 doesn't feel _exactly_ as smooth as when you play on powerful hardware that can achieve it without frame generation, it can still do wonders on cheap hardware. AFMF 2 is a significant step-up compared to AFMF 1, and I can honestly recommend trying it in your favorite games if your hardware supports it. At the very least, try it in demanding single-player games where you don't mind adding a bit of unnoticeable input lag.

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
<li><a href="https://facebook-video-recording.techidaily.com/new-a-compre-market-leaders-guide-to-the-most-effective-fb-video-ad-approaches-for-2024/"><u>[New] A Compre Market Leader's Guide to the Most Effective FB Video Ad Approaches for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-breakdown-of-youtubes-money-making-mechanisms-cpm/"><u>[New] In 2024, Breakdown of YouTube’s Money-Making Mechanisms (CPM)</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-10-groundbreaking-examples-of-the-metaverse-unpacked/"><u>2024 Approved 10 Groundbreaking Examples of the Metaverse Unpacked</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/amazonbasics-tripod-review-easy-photography-setup/"><u>AmazonBasics Tripod Review - Easy Photography Setup</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/bring-your-videos-to-life-border-magic-on-ig/"><u>Bring Your Videos to Life Border Magic on IG</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/epic-game-pass-offers-free-trial-of-popular-pc-building-simulator-app/"><u>Epic Game Pass Offers Free Trial of Popular PC Building Simulator App</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-insights-on-computing-rig-configurations-with-jon-bach-from-puget-systems/"><u>Expert Insights on Computing Rig Configurations with Jon Bach From Puget Systems</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-pocket-playlist-portraits-actors-and-audio-art/"><u>In 2024, Pocket Playlist Portraits Actors & Audio Art</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-resolved-faulty-obs-camera/"><u>In 2024, Resolved Faulty OBS Camera</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/innovative-craftsman-designs-bespoke-star-trek-computer-enclosure/"><u>Innovative Craftsman Designs Bespoke Star Trek Computer Enclosure</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/inside-look-at-advanced-computing-components-with-toms-gadget-analysis/"><u>Inside Look at Advanced Computing Components with Tom's Gadget Analysis</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/integrating-obs-streams-with-the-worlds-largest-social-network-fb/"><u>Integrating OBS Streams with the World's Largest Social Network, FB</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/is-it-time-to-make-the-switch-to-amds-next-gen-ryzen-processors/"><u>Is It Time to Make the Switch to AMD's Next-Gen Ryzen Processors?</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-review-in-depth-analysis-of-cutting-edge-components/"><u>Tom's Tech Review: In-Depth Analysis of Cutting-Edge Components</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshoot-and-fix-windows-10-audio-issues-a-comprehensive-guide/"><u>Troubleshoot & Fix Windows 10 Audio Issues – A Comprehensive Guide</u></a></li>
</ul></div>

