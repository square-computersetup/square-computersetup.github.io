---
title: "macOS Setup"
permalink: /mac-setup/
author_profile: true
sidebar:
  nav: "nav-mac"
header:
  overlay_color: "#333"
---

The __Remote Management__ screen should indicate it is managed by __Square Inc.__:

{% include figure url="/assets/images/mac-04-remote-BigSur.jpg" image_path="/assets/images/mac-04-remote-BigSur.jpg" %}

Click [Continue](){: .btn .btn--inverse .btn--small} on the Remote Management screen to receive a Duo SSO login screen:

{% include duosetup.md %}

Once authenticated, you should see this prompt to create a computer account:

{% include figure url="/assets/images/mac-account.png" image_path="/assets/images/mac-account.png" %}

Your __Full Name__ and __Account Name__ will be pre-filled (the latter should match the username of your Square email address).

__NOTE:__ Account Name __MUST__ match your Square username for proper configuration!
{: .notice--warning}

Select a strong password to unlock your Macbook. This does not need to be the same as your Duo SSO password, but can be if you wish. We will refer to this as your __Laptop Password__ to differentiate from your Duo password.

{% include figure url="/assets/images/mac-touchid.png" image_path="/assets/images/mac-touchid.png" %}

You will be prompted to setup __Touch ID__ (optional). This allows you to quickly unlock your laptop without entering your __Laptop password__. Please note that you will be asked for your __Laptop Password__ periodically even if you have Touch ID setup (just like an iPhone), so don't forget it!

{% include figure url="/assets/images/mac-lightdark.png" image_path="/assets/images/mac-lightdark.png" %}

You may also be asked if you wish to use a Light or Dark visual theme to your desktop. You may also make these changes later in System Preferences.

{% include figure url="/assets/images/mac-desktop.png" image_path="/assets/images/mac-desktop.png"  %}

After clicking through the remaining customization screens, you will arrive at the MacOS desktop which will look similar to the above (perhaps with different wallpaper).

[Next Step &rarr;](/mac-installs){: .btn .btn--success .btn--large}