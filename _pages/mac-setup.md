---
title: "macOS Setup"
permalink: /mac-setup/
author_profile: true
sidebar:
  nav: "nav-mac"
header:
  overlay_color: "#333"
---

# Macbook Setup

After clicking [Enroll](){: .btn .btn--inverse .btn--small} on the Remote Management screen the Okta login screen will appear:

{% include duo-setup-new.md %}

After authentication, wait just a few moments while Remote Management initializes.

Once complete, you should see this prompt to create a computer account:

{% include figure url="/assets/images/mac-account.png" image_path="/assets/images/mac-account.png" %}

Your __Full Name__ and __Account Name__ will be pre-filled (the latter should match the username of your Block email address).

__NOTE:__ The Account Name __MUST__ match your Block username for proper configuration!
{: .notice--warning}

Choose a strong password to unlock your MacBook. While it is __strongly recommended__ to use the same password as your Okta account, you may choose a different one if preferred. To avoid confusion, we will refer to this as your __Mac/Laptop Password__.

__NOTE:__ Make sure you remember your password and do not rely on the password hint. The password hint is not shown when you are logging in.
{: .notice--warning}

Choose to enable Location Services, or set your Time Zone manually.

__NOTE:__ It is __strongly recommended__ to enable Location Services, as some Block applications require accurate time settings to function properly.
{: .notice--warning}

You will then be prompted to set up __Touch ID__. While this is optional, it will provide a seamless and easy login experience each day.

{% include figure url="/assets/images/mac-touchid.png" image_path="/assets/images/mac-touchid.png" %}

__NOTE:__ Please note that you will be asked for your __Laptop Password__ periodically even if you have Touch ID setup (just like an iPhone), so don't forget it!
{: .notice--warning}

You may be prompted to choose between a Light or Dark desktop theme. If needed, you can change this later in System Settings.

{% include figure url="/assets/images/mac-lightdark.png" image_path="/assets/images/mac-lightdark.png" %}

After clicking through the remaining customization screens, you will arrive at the macOS desktop which will look similar to the above (perhaps with different wallpaper).

{% include figure url="/assets/images/sonoma-homescreen.png" image_path="/assets/images/sonoma-homescreen.png"  %}

[Next Step &rarr;](/mac-installs){: .btn .btn--success .btn--large}