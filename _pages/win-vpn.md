---
title: "Windows VPN"
permalink: /win-vpn/
author_profile: true
sidebar:
  nav: "nav-win"
header:
  overlay_image: /assets/images/splash_win.jpg
---

Virtual Private Network (VPN) is a tunnel that creates a private connection between your device and some other network. You may have used this heavily at other jobs, but there are very few services that require VPN at Square. No Customer Success tools require the VPN and even members of IT rarely use the VPN.  The wireless networks in the offices use certificates issued by the VPN to allow you to connect, so it's still a good idea to set things up even if you don't need to access the VPN.

Search for __Pulse Secure__ using Windows search in the bottom left of the desktop.

Click __Connect__ next to __Onboard__, your username and password is your Square username and password.

Once connected go to __go/vpnsetup__ in Chrome

Sign in with Duo again if required and then sign in again your Square username and password

Click to __Download Quick Connect__ software

Open the __ArubaQuickConnect.exe__ software, making sure to click __Yes__ when prompted to allow the application to make changes to the computer

Click Next in the app and allow it to install; you may get some security warning's, on which you can click __Yes__.

Once its done, click __Finish__.

Now re-open pulse secure again, and __Disconnect__ from the Onboard VPN and click __Connect__ on the __Square VPN AWS__. You will be prompted for a Secondary Password, which is just your Square password.
Note: If you dont see the Square AWS VPN, you may need to wait 10-15 minutes for it to show up.

[Next Step &rarr;](/win-druva/){: .btn .btn--success .btn--large}
