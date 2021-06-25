---
title: "Device Management"
permalink: /mac-mdm2/
author_profile: true
sidebar:
  nav: "nav-mac"
header:
  overlay_color: "#333"
---

As you didn't get the notification we can use another method to try enroll your device. 

In Safari you will need to go to this website: __https://ds1506.awmdm.com/DeviceManagement/Enrollment?Gid=squa4021__

Make sure you try spell it all correctly, and once you get there you will be prompted to log in using Duo.

{% include duosetup.md %}

{% include figure url="/assets/images/mac-enable-management.png" image_path="/assets/images/mac-enable-management.png" %}

After setting up Duo and logging in you will be presented with a screen asking you to __Enable Device Management__. Click on [Redirect and Enable](){: .btn .btn--inverse} 

{% include figure url="/assets/images/mac-allow-airwatch.png" image_path="/assets/images/mac-allow-airwatch.png" %}

When prompted by Safari to allow downloads click [Allow](){: .btn .btn--inverse} 

{% include figure url="/assets/images/mac-review-profile.png" image_path="/assets/images/mac-review-profile.png" %}

{% include figure url="/assets/images/mac-apple-menu.png" image_path="/assets/images/mac-apple-menu.png" %}

Then macOS will prompt you with a notification for Profile Installation, you will need to open System Preferences to complete the installation. You can find System Preferences by clicking the Apple logo in the top right corner of the screen.

{% include figure url="/assets/images/mac-system-preferences.png" image_path="/assets/images/mac-system-preferences.png" %}

In System Preferences click the Profiles button in the bottom right corner.

{% include figure url="/assets/images/mac-workspace-services.png" image_path="/assets/images/mac-workspace-services.png" %}

Click Install on the Workspace Services Profile

{% include figure url="/assets/images/mac-device-manager.png" image_path="/assets/images/mac-device-manager.png" %}

Click Install when asked to install the Device Manager profile.

Enter your __laptop__ password when prompted

{% include figure url="/assets/images/mac-profiles.png" image_path="/assets/images/mac-profiles.png" %}

After several seconds, you should see a __Device Manager__ display showing that your device has been verified.

[Next Step &rarr;](/mac-installs){: .btn .btn--success .btn--large}
