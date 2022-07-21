---
title: "Chrome VPN"
permalink: /chrome-vpn/
author_profile: true
sidebar:
  nav: "nav-chrome"
header:
  overlay_color: "#333"
---

Virtual Private Network (VPN) is a tunnel that creates a private connection between your device and some other network. You may have used this heavily at other jobs, but there are very few services that require VPN at Square. No Customer Success tools require the VPN and even members of IT rarely use the VPN.  The wireless networks in the offices use certificates issued by the VPN to allow you to connect, so it's still a good idea to set things up even if you don't need to access the VPN.

{% include figure url="/assets/images/chrome-04-tray.jpg" image_path="/assets/images/chrome-04-tray.jpg" %}

Start by clicking on the clock in the bottom-right corner of your desktop to open the control panel, then click on the __VPN__ icon:

{% include figure url="/assets/images/chrome-05-vpn.jpg" image_path="/assets/images/chrome-05-vpn.png" %}

From the network list under __Pulse Secure__, click on __Square Remote Onboard__

{% include figure url="/assets/images/vpn-login.jpg" image_path="/assets/images/vpn-login.jpg" %}

Enter just your username (jsmith not jsmith@squareup.com) and your password. Then, click __Continue__. This may take up to 30 seconds.

If successful, open up the Chrome web browser and in the address bar at the top, enter __go.sqprod.co/vpnsetup__ 

{% include figure url="/assets/images/go-vpnsetup.jpg" image_path="/assets/images/go-vpnsetup.jpg" caption="(in a future setup, we will configure even shorter __go/__ links)" %}

__NOTE:__ You may be prompted to authenticate to Duo SSO again. You may check the box that says __Remember me for 12 hours__ to avoid authenticating more than once daily.
{: .notice--warning}

{% include figure url="/assets/images/wifi1.jpg" image_path="/assets/images/wifi1.jpg" caption="(if this page does not appear after a minute, reload the page)" %}

Enter just your username (jsmith not jsmith@squareup.com) and your password. Then, click __Let's Go__

{% include figure url="/assets/images/wifi2.jpg" image_path="/assets/images/wifi2.jpg" %}

Click the large __Square WiFi Profile__ button, and then click __OK__ in the pop-up prompt:

{% include figure url="/assets/images/wifi3.jpg" image_path="/assets/images/wifi3.jpg" %}

After a few minutes, you will see a success message that says __Device Provisioning Complete__. Click on the clock and go to the VPN icon in the control panel. 

{% include figure url="/assets/images/chrome-06-vpn.jpg" image_path="/assets/images/chrome-06-vpn.png" %}

Click on the __Disconnect__ button. Now to test that your provisioning works on an _actual_ VPN and not just the special onboarding VPN, select the __Square East Coast VPN__ (or any other).

{% include figure url="/assets/images/vpn-cert.jpg" image_path="/assets/images/vpn-cert.jpg" %}

You will be prompted to select the certificate to use to authenticate -- as you only have one, select it and then click __OK__

{% include figure url="/assets/images/vpn-secondary.jpg" image_path="/assets/images/vpn-secondary.jpg" %}

Next, enter just your password for a __Secondary Credential__ (the username will be disabled).

{% include figure url="/assets/images/chrome-07-vpn.jpg" image_path="/assets/images/chrome-07-vpn.png" %}

If all goes according to plan, you have now confirmed that you have provisioned a certificate for VPN and in-office WiFi. Hey, you're pretty good at this! Click __Disconnect__ before continuing to the next step.

[Next Step &rarr;](/chrome-yubikey/){: .btn .btn--success .btn--large}
