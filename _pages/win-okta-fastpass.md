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

__Okta FastPass__ provides a quick, easy and secure way to sign in and helps protect you from phishing.


Open the __Okta Verify__ app on your Windows device. 
Select __Get Started__.

{% include figure url="/assets/images/win-okta1.png" image_path="/assets/images/win-okta1.png" %}

Select __Next.__

{% include figure url="/assets/images/win-okta2.png" image_path="/assets/images/win-okta2.png" %}

Type __login.block.xyz__ into the text box.
Select __Next.__

{% include figure url="/assets/images/win-okta3.png" image_path="/assets/images/win-okta3.png" %}


A browser window will open and you will be directed away from Okta Verify to login.

{% include figure url="/assets/images/win-okta4.png" image_path="/assets/images/win-okta4.png" %}


Verify your identity by entering your password.
Select __Verify__.
{% include figure url="/assets/images/win-okta5.png" image_path="/assets/images/win-okta5.png" %}


Continue verifying your identity by selecting an MFA option from the presented list.
Verify your identity using the chosen method.
You will be directed back to Okta Verify to complete the configuration.

{% include figure url="/assets/images/win-okta6.png" image_path="/assets/images/win-okta6.png" %}


Select __Enable__ when asked about __Windows Hello__. (Windows Hello use is required for passwordless on Block-issued devices)


Note: Windows Hello use is preferred when using Okta FastPass. Windows Hello allows use of an on-device PIN code, fingerprint scanner, and/or facial recognition. 

Biometrics are not required to use Windows Hello but are highly recommended for the most convenient and secure login experience. 
You may select __Not now__ but you will be prompted for your Okta password at each login.

{% include figure url="/assets/images/win-okta7.png" image_path="/assets/images/win-okta7.png" %}


You will be prompted to authenticate with Windows Hello facial recognition, fingerprint, or PIN code. Select "More choices" if you prefer to use a different authentication type. Authenticate using Windows Hello.

{% include figure url="/assets/images/win-okta8.png" image_path="/assets/images/win-okta7.png" %}


{% include figure url="/assets/images/win-okta8.png" image_path="/assets/images/win-okta8.png" %}

{% include figure url="/assets/images/win-okta9.png" image_path="/assets/images/win-okta9.png" %}

Success! 🎉 The above screen will appear when you have successfully enrolled Okta Verify on your Windows device.


[Next](/win-chrome){: .btn .btn--success} 




