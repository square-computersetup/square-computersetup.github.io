---
title: "Mac VPN"
permalink: /mac-vpn/
author_profile: true
sidebar:
  nav: "nav-mac"
header:
  overlay_color: "#333"
---

Virtual Private Network (VPN) is a tunnel that creates a private connection between your device and some other network. You may have used this heavily at other jobs, but there are very few services that require VPN at Block. No Customer Success tools require the VPN and even members of IT rarely use the VPN.  The wireless networks in the offices use certificates issued by the VPN to allow you to connect, so it's still a good idea to set things up even if you don't need to access the VPN.

Let's start by clicking on the Pulse Secure icon <img src="/assets/images/Pulse Secure.png" width='25' height='25' /> near the clock in the top-right corner of your Macbook desktop.

{::comment}

{% include figure url="/assets/images/vpn-onboard.jpg" image_path="/assets/images/vpn-onboard.jpg" %}

Select the __Onboard__ network, and then select __Connect__

{% include figure url="/assets/images/vpn-onboard-login.jpg" image_path="/assets/images/vpn-onboard-login.jpg" %}

Enter just your username (jsmith not jsmith@squareup.com) and your password.  This is __NOT__ your Laptop Password, but rather the password you have used with Duo SSO.

{% include figure url="/assets/images/vpn-tray.jpg" image_path="/assets/images/vpn-tray.jpg" %}

After a few seconds, the Pulse Secure icon will change to have a green arrow superimposed, to indicate you are currently connected to a VPN.

Open up the Chrome web browser and in the address bar at the top, enter __go.sqprod.co/vpnsetup__

{% include figure url="/assets/images/go-vpnsetup.jpg" image_path="/assets/images/go-vpnsetup.jpg" caption="(in a future setup, we will configure even shorter __go/__ links)" %}

__NOTE:__ You may be prompted to authenticate to Duo SSO again. You may check the box that says __Remember me for 12 hours__ to avoid authenticating more than once daily.
{: .notice--warning}

{% include figure url="/assets/images/wifi1.jpg" image_path="/assets/images/wifi1.jpg" caption="(if this page does not appear after a minute, reload the page)" %}

Enter just your username (jsmith not jsmith@squareup.com) and your password. Then, click __Let's Go__

{% include figure url="/assets/images/wifi5.jpg" image_path="/assets/images/wifi5.jpg" %}

Click on the large __Root Certificate__ button to download (although we will ignore this file)

{% include figure url="/assets/images/wifi6.jpg" image_path="/assets/images/wifi6.jpg" %}

Click the large __Square WiFi Profile__ button to download (click __Keep__ if prompted by the browser)

{% include figure url="/assets/images/wifi7.jpg" image_path="/assets/images/wifi7.jpg" %}

Click on __Square.mobileconfig__ in the bottom-left of your browser window to start the process

{% include figure url="/assets/images/profiles1.jpg" image_path="/assets/images/profiles1.jpg" %}

At the warning prompt, click [Continue](#profile){: .btn .btn--inverse .btn--small}

<a name="profile"></a>
{% include figure url="/assets/images/profiles2.jpg" image_path="/assets/images/profiles2.jpg" %}

At the second warning, click [Install](#changes){: .btn .btn--inverse .btn--small} to install the profile

<a name="changes"></a>
{% include figure url="/assets/images/profiles3.jpg" image_path="/assets/images/profiles3.jpg" %}

At the prompt, enter your __Laptop Password__ (which may not match your Duo SSO) and click [OK](#installed){: .btn .btn--inverse .btn--small} to allow the changes

<a name="installed"></a>
{% include figure url="/assets/images/profiles4.jpg" image_path="/assets/images/profiles4.jpg" %}

Confirm that you have a profile called __Square Wifi__ installed (it is normal and expected for it to show as _unverified_)

{% include figure url="/assets/images/vpn-disco.jpg" image_path="/assets/images/vpn-disco.jpg" %}

Return to the Pulse Secure icon near the clock, click on __Onboard__ and then click __Disconnect__


Now to test that your provisioning works on an _actual_ VPN and not just the special onboarding VPN,
{:/comment}

{% include figure url="/assets/images/Block VPN.png" image_path="/assets/images/Block VPN.png" %}

Select the __Block VPN AWS__.

<a name="always"></a>
{% include figure url="assets/images/vpn-login.png" image_path="assets/images/vpn-login.png" %}

Each time you connect to the VPN, you will be asked to enter your username and password into the __Secondary User Name__ and __Secondary Password__ fields. This is the password that you use for Okta SSO (and __NOT__ your Laptop Password).

{% include figure url="assets/images/aws-green.jpg" image_path="assets/images/aws-green.jpg" %}

If the Pulse Secure icon shows the green arrow superimposed, you have successfully authenticated to the VPN. Hey, you're pretty good at this!

{% include figure url="assets/images/aws-disconnect.jpg" image_path="assets/images/aws-disconnect.jpg" %}

Return to the Pulse Secure icon near the clock, click on the active VPN, and then click __Disconnect__


