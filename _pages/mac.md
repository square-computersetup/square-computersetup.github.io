---
title: "Mac"
permalink: /mac/
author_profile: true
sidebar:
  nav: "nav-shared"
header:
  overlay_image: /assets/images/splash_mac.jpg
---

Let's get your Macbook setup!

Press the __power__ button at the top-right corner of the keyboard: 

{% include figure url="/assets/images/mac-01-power.jpg" image_path="/assets/images/mac-01-power.jpg" caption="(if you have a Mac Mini, the power button is in the rear)" %}

Shortly after boot-up, you will be asked to select your home and preferred language:

{% include figure url="/assets/images/mac-02-locale.jpg" image_path="/assets/images/mac-02-locale.jpg"  %}

Connect your device to a wireless network (either your home WiFi or the Square office) with Internet access.

{% include figure url="/assets/images/mac-03-wifi.jpg" image_path="/assets/images/mac-03-wifi.jpg"  %}

Next, some Mac devices will display a __Data &amp; Privacy__ screen:

{% include figure url="/assets/images/mac-05-privacy.jpg" image_path="/assets/images/mac-05-privacy.jpg" %}

If you see this screen above, click [Data &amp; Privacy](/mac-privacy){: .btn .btn--inverse .btn--small} for the next page of instructions and stop reading here. 

If instead you see a __Remote Management__ screen indicating it is managed by __Square Inc.__:

{% include figure url="/assets/images/mac-04-remote.jpg" image_path="/assets/images/mac-04-remote.jpg" %}

Click [Continue](#duo){: .btn .btn--inverse .btn--small} on the Remote Management screen to receive a Duo SSO login screen:

<a name="duo"></a> 
{% include figure url="/assets/images/duo-login.jpg" image_path="/assets/images/duo-login.jpg" caption="(this is the Duo Single Sign-On service you will encounter daily)" %}

Enter just your username (jsmith not jsmith@squareup.com) and your password and click [Login](#push){: .btn .btn--inverse .btn--small}

<a name="push"></a> 
{% include figure url="/assets/images/duo-push.jpg" image_path="/assets/images/duo-push.jpg" caption="(if you do not see these options, ask for [help](/help))" %}

Choose one of the authentication methods, such as sending a push notice to your mobile app. Once authenticated, you should see this prompt to create a computer account:

{% include figure url="/assets/images/mac-06-account.jpg" image_path="/assets/images/mac-06-account.jpg" %}

Your __Full Name__ and __Account Name__ will be pre-filled (the latter should match the username of your Square email address).

__NOTE:__ Account Name __MUST__ match your Square username for proper configuration!
{: .notice--warning}

Select a strong password to unlock your Macbook. This does not need to be the same as your Duo SSO password, but can be if you wish. We will refer to this as your __Laptop Password__ to differentiate from your SSO password.

{% include figure url="/assets/images/mac-touch.jpg" image_path="/assets/images/mac-touch.jpg" %}

If your Macbook has a fingerprint sensor, you will be prompted to setup __Touch ID__ (optional). This allows you to quickly unlock your laptop without entering your __Laptop password__. Please note that you will be asked for your __Laptop Password__ periodically even if you have Touch ID setup (just like an iPhone), so don't forget it!

{% include figure url="/assets/images/mac-dark.jpg" image_path="/assets/images/mac-dark.jpg" %}

You may also be asked if you wish to use a Light or Dark visual theme to your desktop. You may also make these changes later in the System Preferences control panel. 

{% include figure url="/assets/images/mac-desktop.jpg" image_path="/assets/images/mac-desktop.jpg"  %}

After clicking through the remaining customization screens, you will arrive at the MacOS desktop which will look similar to the above (perhaps with different wallpaper). 

[Next Step &rarr;](/mac-tips){: .btn .btn--success .btn--large}
