---
title: "Windows Okta Fastpass"
permalink: /win-okta-fastpass/
author_profile: true
sidebar:
  nav: "nav-win"
header:
  overlay_color: "#333"
---

Let's set up __Okta Fastpass__. 

__Okta FastPass__ provides a quick, easy, and secure way to sign in and helps protect you from phishing.

First, make sure that you have Bluetooth enabled on __both your Windows machine and on your mobile device__. 
To confirm this on your Windows machine, click on the Control Center icon in the bottom-right corner.
Then confirm Bluetooth is also enabled on your mobile device. 

{% include figure url="/assets/images/ofp-win1.png" image_path="/assets/images/ofp-win1.png" %}

Open the __Okta Verify__ app on your Windows device by clicking the Start menu at the bottom of your screen, then searching for __Okta Verify__. 

{% include figure url="/assets/images/ofp-win3.png" image_path="/assets/images/ofp-win3.png" %}

Select __Add account from another device__.

{% include figure url="/assets/images/ofp-win4.png" image_path="/assets/images/ofp-win4.png" caption="(Note that Okta Verify Desktop can be run in Light or Dark mode)" %}

Now open Okta Verify on your mobile device, select your Block account (Eg. jsmith@block.xyz), then scroll down to select __Add Account to Another Device__.

{% include figure url="/assets/images/ofp-win5.png" image_path="/assets/images/ofp-win5.png" %}

You will now see an 8-character code below a QR code. 

{% include figure url="/assets/images/ofp-win6.png" image_path="/assets/images/ofp-win6.png" %}

Enter this code into Okta Verify desktop’s “Enter code” field.

{% include figure url="/assets/images/ofp-win7.png" image_path="/assets/images/ofp-win7.png" %}

You may be asked to enter a PIN shown on your desk into your mobile Okta Verify app:
{% include figure url="/assets/images/ofp-win8.png" image_path="/assets/images/ofp-win8.png" %}

__Note:__ Biometrics (Windows Hello) are preferred when using Okta FastPass. If you do not enable or use biometrics on your Block-issued device, you will be prompted for another factor (password) when using Okta FastPass.

{% include figure url="/assets/images/ofp-win9.png" image_path="/assets/images/ofp-win9.png" %}

{% include figure url="/assets/images/ofp-win10.png" image_path="/assets/images/ofp-win10.png" %}

If prompted, authenticate using Windows Hello.
Success! 🎉 You’re all setup with Okta Fastpass!

[Next](/win-chrome){: .btn .btn--success} 




