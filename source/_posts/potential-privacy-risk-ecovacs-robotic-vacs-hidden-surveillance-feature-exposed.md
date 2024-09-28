---
title: "Potential Privacy Risk: Ecovacs Robotic Vac's Hidden Surveillance Feature Exposed"
date: 2024-09-17T03:18:26.016Z
updated: 2024-09-22T09:14:16.342Z
tags:
  - hardware
categories:
  - tech
thumbnail: https://thmb.techidaily.com/2d6e3d004fe41d35820dae54c2391ec61920df6e01f9e64b7d28d591e44b8418.png
---

## Potential Privacy Risk: Ecovacs Robotic Vac's Hidden Surveillance Feature Exposed

A pair of security researchers have discovered that Ecovacs vacuums and lawn mowers can be hijacked over a Bluetooth connection. These devices, which contain cameras and microphones, may be utilized for "spying" if compromised. Concerningly, Ecovacs has not acknowledged the problem.

 The security researchers in question—[Dennis Giese and Braelynn](https://x.com/dgi%5FDE/status/1822385479519776868)—identified _several_ vulnerabilities in Ecovacs products and cloud-based services. The Bluetooth takeover flaw is simply the most notable of the bunch. Hackers can hijack Ecovacs robotic vacuums and mowers by sending a malicious payload over Bluetooth from a smartphone. Once an Ecovac robot is compromised, hackers may access its cameras and microphones. They may also drive the robot like an RC car, download its room-mapping data, tinker with its filesystem, or use it to hack nearby Ecovacs devices.

 Importantly, an attacker must be within Bluetooth range (less than 450 feet) to perform this hack. Ecovacs vacuums regularly disable their Bluetooth connection throughout the day, so an attacker needs to be fairly patient, and _some_ Ecovacs robots play a repetitive warning noise when their camera is turned on. However, attackers can set up Wi-Fi remote access after completing the Bluetooth hack. They only need to be in physical proximity for a few minutes. And because a hacker can dig through a compromised robot's filesystem, they may delete the files associated with the "camera-on" warning noise.

 Plus, Bluetooth hijacking is just one of many flaws discovered by Giese and Braelynn. The duo found that cloud-based user data and authentication tokens _are not discarded_ when a user deletes their Ecovacs account. If Ecovacs' servers are compromised, _former_ customers may have their private data exposed. And if you sell an Ecovacs vacuum to someone, you can use your old authentication token to spy through the vacuum.

 Giese and Braelynn attempted to bring these findings to Ecovacs' attention. The company didn't thank or consult the researchers. In fact, the researchers were met with radio silence. Ecovacs has not publicly acknowledged its security flaws, and it has not responded to inquires from _TechCrunch_ (the first outlet to cover this story) or other publications.

 Admittedly, the vulnerabilities discovered by Giese and Braelynn may only affect a small portion of Ecovacs users. The most concerning part of this story is Ecovacs' slow response and aloof attitude. Robot vacuums with integrated cameras are, by nature, a [fantastic target for hackers](https://review-topics.techidaily.com/in-2024-how-to-stop-life360-from-tracking-you-on-apple-iphone-xs-max-drfone-by-drfone-virtual-ios/). Ecovacs' products _should_ offer top-notch security. And Ecovacs, as a smart home company, _should_ be receptive to vulnerability disclosures.

 Note that Giese and Braelynn have only tested 11 Ecovacs devices: Ecovacs Deebot 900 Series, Ecovacs Deebot N8/T8, Ecovacs Deebot N9/T9, Ecovacs Deebot N10/T10, Ecovacs Deebot X1, Ecovacs Deebot T20, Ecovacs Deebot X2, Ecovacs Goat G1, Ecovacs Spybot Airbot Z1, Ecovacs Airbot AVA, and the Ecovacs Airbot ANDY. Other Ecovacs products may not be impacted by any of the aforementioned vulnerabilities.

 We've reached out to Ecovacs and are awaiting a response. This article will be updated as we learn new information about the Ecovacs vulnerabilities.

 Source: Dennis Giese and Braelynn via [TechCrunch](https://techcrunch.com/2024/08/09/ecovacs-home-robots-can-be-hacked-to-spy-on-their-owners-researchers-say/)

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



<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129741/7443" target="_top" id="2129741">
  <img src="//a.impactradius-go.com/display-ad/7443-2129741" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129741/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

