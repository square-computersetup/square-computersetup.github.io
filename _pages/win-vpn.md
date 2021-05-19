---
title: "Windows VPN"
permalink: /win-vpn/
author_profile: true
sidebar:
  nav: "nav-win"
header:
  overlay_color: "#333"
---

Virtual Private Network (VPN) is a tunnel that creates a private connection between your device and some other network. You may have used this heavily at other jobs, but there are very few services that require VPN at Square. No Customer Success tools require the VPN and even members of IT rarely use the VPN.  The wireless networks in the offices use certificates issued by the VPN to allow you to connect, so it's still a good idea to set things up even if you don't need to access the VPN.

Search for __Pulse Secure__ using Windows search in the bottom left of the desktop.

{% include figure url="/assets/images/win-vpn-search.png" image_path="/assets/images/win-vpn-search.png" %}

Click __Connect__ next to __Onboard__, your username and password is your Square username and password.

{% include figure url="/assets/images/win-vpn-aws.png" image_path="/assets/images/win-vpn-aws.png" %}

{% include figure url="/assets/images/win-vpn-onboard-login.png" image_path="/assets/images/win-vpn-onboard-login.png" %}

Once connected go to __go/vpnsetup__ in Chrome

{% include figure url="/assets/images/win-vpn-golink.png" image_path="/assets/images/win-vpn-golink.png" %}

Sign in with Duo again if required and then sign in again your Square username and password

{% include figure url="/assets/images/win-vpn-login.png" image_path="/assets/images/win-vpn-login.png" %}

Click to __Download Quick Connect__ software

{% include figure url="/assets/images/win-vpn-download.png" image_path="/assets/images/win-vpn-download.png" %}

Open the __ArubaQuickConnect.exe__ software, making sure to click __Yes__ when prompted to allow the application to make changes to the computer

{% include figure url="/assets/images/win-vpn-quickconnect.png" image_path="/assets/images/win-vpn-quickconnect.png" %}

Click Next in the app and allow it to install; you may get some security warning's, on which you can click __Yes__.

{% include figure url="/assets/images/win-vpn-security.png" image_path="/assets/images/win-vpn-security.png" %}

Once its done, click __Finish__.

{% include figure url="/assets/images/win-vpn-quickconnectfinish.png" image_path="/assets/images/win-vpn-quickconnectfinish.png" %}

Now re-open pulse secure again, and __Disconnect__ from the Onboard VPN and click __Connect__ on the __Square VPN AWS__. You will be prompted for a Secondary Password, which is just your Square password.
Note: If you dont see the Square AWS VPN, you may need to wait 10-15 minutes for it to show up.

{% include figure url="/assets/images/win-vpn-aws.png" image_path="/assets/images/win-vpn-aws.png" %}

{% include figure url="/assets/images/win-vpn-secondary.png" image_path="/assets/images/win-vpn-secondary.png" %}

[Next Step &rarr;](/win-druva/){: .btn .btn--success .btn--large}
