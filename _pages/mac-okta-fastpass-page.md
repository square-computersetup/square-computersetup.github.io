---
title: "Mac Okta Fastpass"
permalink: /mac-okta-fastpass-page/
author_profile: true
sidebar:
  nav: "nav-mac"
header:
  overlay_color: "#333"
---
Let's set up __Okta Fastpass__. 

Okta FastPass provides a quick, easy and secure way to sign in and helps protect you from phishing.

Before setting up Okta Verify, ensure that Bluetooth is enabled on both your MacBook and on your mobile device. 

To confirm this on your MacBook, click on the Control Center icon in the top right corner.

{% include figure url="/assets/images/bluetooth-mac.png" image_path="/assets/images/bluetooth-mac.png" %}
{% include figure url="/assets/images/bluetooth-mac2.png" image_path="/assets/images/bluetooth-mac.png2" %}

Now make sure Bluetooth is turned __on__ on your mobile device. Use your control center or mobile Settings to toggle Bluetooth on.
{% include figure url="/assets/images/bluetooth-mobile.png" image_path="/assets/images/bluetooth-mobile.png" %}

Back on your MacBook, Click the __Launchpad__ app in the dock at the bottom of your screen.

{% include figure url="/assets/images/launchpad.png" image_path="/assets/images/launchpad.png" %}

Next, click on __Okta Verify__ to open it, and click [Get Started](){: .btn .btn--inverse .btn--small}

{% include figure url="/assets/images/okta-verify-app.png" image_path="/assets/images/okta-verify-app.png" %}

Select __Add Account__ under Add account from another device.

{% include figure url="/assets/images/okta-fp-signin-new.png" image_path="/assets/images/okta-fp-signin-new.png" %}

Now open the Okta Verify app on your mobile device, select your Block account (Eg. jsmith@block.xyz), then scroll down to select __Add Account to Another Device__.

{% include figure url="/assets/images/mac-okta-fastpass-add-mobile1.png" image_path="/assets/images/mac-okta-fastpass-add-mobile1.png" %}

You will now see an 8 character code below a QR code. Enter this code into Okta Verify desktop’s “Enter code” field.
{% include figure url="/assets/images/mac-okta-fastpass-add-mobile2.5.png" image_path="/assets/images/mac-okta-fastpass-add-mobile2.5.png" %}
{% include figure url="/assets/images/mac-okta-fastpass-add-mobile2.png" image_path="/assets/images/mac-okta-fastpass-add-mobile2.png" %}

Next, you may be asked to enter a PIN shown on your MacBook into your mobile Okta Verify app:
{% include figure url="/assets/images/mac-okta-fastpass-add-mobile3.png" image_path="/assets/images/mac-okta-fastpass-add-mobile3.png" %}


Note: Biometrics (Touch ID) are preferred when using Okta FastPass. If you do not enable/use biometrics on your Block-issued device you will be prompted for another factor (password) when using Okta FastPass. 


{% include figure url="/assets/images/okta-fp-touchid-1.png" image_path="/assets/images/okta-fp-touchid-1.png" %}

{% include figure url="/assets/images/enable-touch-id.png" image_path="/assets/images/enable-touch-id.png" %}

If you opted-in for Touch ID, you will see the above screen. If you skipped Touch ID, please move to the next step:

Click [Enable Touch ID](){: .btn .btn--inverse .btn--small}.

If prompted, authenticate using Touch ID.

Success! 🎉 You're all setup with Okta Fastpass! 

[Next](/mac-chrome){: .btn .btn--success} 
