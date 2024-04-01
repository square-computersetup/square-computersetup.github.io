---
title: "macOS Setup"
permalink: /mac-setup/
author_profile: true
sidebar:
  nav: "nav-mac"
header:
  overlay_color: "#333"
---

The __Remote Management__ screen should indicate it is managed by __Block Inc.__:

{% include figure url="/assets/images/remote-management-block.png" image_path="/assets/images/remote-management-block.png" %}

Click [Continue](){: .btn .btn--inverse .btn--small} on the Remote Management screen to receive an Okta login screen:

{% include duosetup.md %}

After you are authenticated, wait just a few moments while Remote Management initializes.

Once complete, you should see this prompt to create a computer account:

{% include figure url="/assets/images/mac-account.png" image_path="/assets/images/mac-account.png" %}

Your __Full Name__ and __Account Name__ will be pre-filled (the latter should match the username of your Block email address).

__NOTE:__ Account Name __MUST__ match your Block username for proper configuration!
{: .notice--warning}

Select a strong password to unlock your MacBook. This does not need to be the same as your Okta password, but can be if you wish. We will refer to this as your __Laptop Password__ to differentiate from your Okta password.

Choose to enable Location Services, or set your Time Zone manually.

{% include figure url="/assets/images/mac-touchid.png" image_path="/assets/images/mac-touchid.png" %}

You will then be prompted to set up __Touch ID__. While this is optional, it will provide a seamless and easy login experience for you each day.

Please note that you will be asked for your __Laptop Password__ periodically even if you have Touch ID setup (just like an iPhone), so don't forget it!

{% include figure url="/assets/images/mac-lightdark.png" image_path="/assets/images/mac-lightdark.png" %}

You may also be asked if you wish to use a Light or Dark visual theme to your desktop. You may also make these changes later in System Preferences.

{% include figure url="/assets/images/mac-desktop.png" image_path="/assets/images/mac-desktop.png"  %}

After clicking through the remaining customization screens, you will arrive at the macOS desktop which will look similar to the above (perhaps with different wallpaper).

[Next Step &rarr;](/mac-installs){: .btn .btn--success .btn--large}
