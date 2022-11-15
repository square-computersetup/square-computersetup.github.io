---
title: "Device Management"
permalink: /mac-mdm2/
author_profile: true
sidebar:
  nav: "nav-mac"
header:
  overlay_color: "#333"
---

As you didn't get the notification, we can use another method to try enroll your device. 

First we are going to log into Slack.

In Safari you will need to go to: __square.enterprise.slack.com__ where you will be prompted to set up Okta.

{% include duosetup.md %}

After completing Okta setup you can open the appropriate Slack Workspace.

Next, in Safari you will need to go to this website: __go.sqprod.co/mdmold__

Once you get there you will be prompted to log in using Okta again. Enter the same login information you just used and __Send a Push__ when prompted.

{% include figure url="/assets/images/mac-enable-management.png" image_path="/assets/images/mac-enable-management.png" %}

After logging in you will be presented with a screen asking you to __Enable Device Management__. Click on [Redirect and Enable](){: .btn .btn--inverse} 

{% include figure url="/assets/images/mac-allow-airwatch.png" image_path="/assets/images/mac-allow-airwatch.png" %}

When prompted by Safari to allow downloads, click [Allow](){: .btn .btn--inverse} 

{% include figure url="/assets/images/mac-review-profile.png" image_path="/assets/images/mac-review-profile.png" %}

{% include figure url="/assets/images/mac-apple-menu.png" image_path="/assets/images/mac-apple-menu.png" %}

macOS will prompt you with a notification for __Profile Installation__. You will need to open __System Preferences__ to complete the installation. You can find System Preferences by clicking the __Apple logo__ in the top left corner of the screen.

{% include figure url="/assets/images/mac-system-preferences.png" image_path="/assets/images/mac-system-preferences.png" %}

In System Preferences, click the [Profiles](){: .btn .btn--inverse}  button in the bottom right corner.

{% include figure url="/assets/images/mac-workspace-services.png" image_path="/assets/images/mac-workspace-services.png" %}

Click [Install](){: .btn .btn--inverse}  on the Workspace Services Profile

{% include figure url="/assets/images/mac-device-manager.png" image_path="/assets/images/mac-device-manager.png" %}

Click [Install](){: .btn .btn--inverse}  when asked to install the Device Manager profile.

Enter your __laptop__ password when prompted

{% include figure url="/assets/images/mac-profiles.png" image_path="/assets/images/mac-profiles.png" %}

After several seconds, you should see the __Device Manager__ profile show that your device has been verified.

[Next Step &rarr;](/mac-installs){: .btn .btn--success .btn--large}
