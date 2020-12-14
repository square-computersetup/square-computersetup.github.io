---
title: "Windows VPN"
permalink: /win-vpn/
author_profile: true
sidebar:
  nav: "nav-win"
header:
  overlay_image: /assets/images/splash_mac.jpg
---

Virtual Private Network (VPN) is a tunnel that creates a private connection between your device and some other network. You may have used this heavily at other jobs, but there are very few services that require VPN at Square. No Customer Success tools require the VPN and even members of IT rarely use the VPN.  The wireless networks in the offices use certificates issued by the VPN to allow you to connect, so it's still a good idea to set things up even if you don't need to access the VPN.

Click the Pulse Secure (White S logo) icon in the taskbar. (You may need to click the ^ arrow to expand the list)

Open Pulse Secure, hit the + to the top right to add a new VPN.

Enter the following:
- Name: Remote Onboard
- Server URL: https://vpn.east.squareup.com/onboard

If the Remote Onboard VPN is already there, skip this step

Connect to Remote Onboard VPN, your user/pass is your square username and password. (make sure all other VPN connections are disconnected)

Once connected go to https://clearpass01.corp.squareup.com/guest/laptop_provisioning.php?_browser=1 in Chrome

Sign in with your Square username and password

Click to download the Aruba Quick Connect software

Open the Aruba Quick Connect software, making sure to click Allow when prompted to allow the application to make changes to the computer

Click Next in the app and allow it to install

Now disocnnect from the remote onboard VPN connect to the Square VPN AWS
