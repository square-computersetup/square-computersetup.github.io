---
title: "Mac VPN"
permalink: /mac-vpn/
author_profile: true
sidebar:
  nav: "nav-shared"
header:
  overlay_image: /assets/images/splash_mac.jpg
---

Virtual Private Network (VPN) is a tunnel that creates a private connection between your device and some other network. You may have used this heavily at other jobs, but there are very few services that require VPN at Square. No Customer Success tools require the VPN and even members of IT rarely use the VPN.  The wireless networks in the offices use certificates issued by the VPN to allow you to connect, so it's still a good idea to set things up even if you don't need to access the VPN.



{% include figure url="/assets/images/mac-mgmt.jpg" image_path="/assets/images/mac-mgmt.jpg" caption="(if you do not see this after five minutes, restart your Macbook and wait another five minutes)" %}

This installer will spend 10-45 minutes (depending on your Internet speed) retrieving and installing tools.

{% include figure url="/assets/images/mac-git.jpg" image_path="/assets/images/mac-git.jpg" caption="(you may or may not see this prompt)" %}

If prompted to install __Developer Tools__, click [Install](#updates){: .btn .btn--inverse .btn--small}

<a name="updates"></a> 
{% include figure url="/assets/images/mac-updates.jpg" image_path="/assets/images/mac-updates.jpg" caption="(you may or may not see this prompt)" %}

If you see the __Updates Available__ notification, click [Later](#installer){: .btn .btn--inverse .btn--small} to defer the installation.

<a name="installer"></a> 
Once the installer has completed, it will thank you for your patience. Click [Quit](#logout){: .btn .btn--inverse .btn--small} to exit the installer.

<a name="logout"></a> 
{% include figure url="/assets/images/mac-logout.jpg" image_path="/assets/images/mac-logout.jpg"  %}

Click <img src='/assets/images/apple.png' width='20' height='20'> in the top-left corner of the desktop, and then click [Logout](#login){: .btn .btn--inverse .btn--small}.

<a name="login"></a> 
You may see some updates happening after you logout. After you no longer see any visual indication an update is happening, __Login__ again using your __Laptop Password__ (which may be differen than your Duo SSO password).


[Next Step &rarr;](/mac-chrome){: .btn .btn--success .btn--large}
