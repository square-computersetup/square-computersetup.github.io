---
title: "macOS Setup"
permalink: /mac-setup/
author_profile: true
sidebar:
  nav: "nav-mac"
header:
  overlay_image: /assets/images/splash_mac.jpg
---

The __Remote Management__ screen should indicating it is managed by __Square Inc.__:

{% include figure url="/assets/images/mac-04-remote-BigSur.jpg" image_path="/assets/images/mac-04-remote-BigSur.jpg" %}

Click [Continue](#duo){: .btn .btn--inverse .btn--small} on the Remote Management screen to receive a Duo SSO login screen:

<a name="duo"></a>
{% include figure url="/assets/images/duo-login2.jpg" image_path="/assets/images/duo-login2.jpg" caption="(this is the Duo Single Sign-On service you will encounter daily)" %}

Enter just your username (**without the** @squareup.com) and your password and click [Login](#push){: .btn .btn--inverse .btn--small}

If you have set up Duo previously, skip forward to the send a push section below.

<a name="push"></a>
{% include figure url="/assets/images/duo-setup1.jpg" image_path="/assets/images/duo-setup1.jpg" caption="(if you do not see these options, ask for [help](/help))" %}

Click [Start Setup](#push){: .btn .btn--inverse .btn--small} and go through the whole process.

* Choose **Mobile phone**
* Enter​ **Phone Number**
* Choose​ **phone type**
* Select​ **I have Duo Mobile installed**
* Open​ **Duo Mobile app on your phone and Click the +**
* Scan **QR Code**
* Select​ **Continue to Login**
* Click on [S​end Me a Push](#push){: .btn .btn--inverse .btn--small}
* Approve​ **Push notification on your phone**

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

[Next Step &rarr;](/mac-installs){: .btn .btn--success .btn--large}