---
title: "Device Management"
permalink: /mac-mdm/
author_profile: true
sidebar:
  nav: "nav-mac"
header:
  overlay_color: "#333"
---

We have to do some extra steps to get your MacBook enrolled with our Mobile Device Management (MDM) system.

{% include figure url="/assets/images/mac-safari.png" image_path="/assets/images/mac-safari.png"  %}

First, you will need to open Safari. It should be located in the Dock along the bottom (with a blue compass icon).

{% include figure url="/assets/images/mac-mdmfixsafari.png" image_path="/assets/images/mac-mdmfixsafari.png"  %}

Now let's type __newcomputer.square.com/mdmfix__ into the address bar in Safari.

{% include figure url="/assets/images/mac-mdmfixdownloads.png" image_path="/assets/images/mac-mdmfixdownloads.png"  %}

Click [Download](){: .btn .btn--inverse .btn--small} on the page and once the download completes, open the file out of your downloads folder in the Dock.

{% include figure url="/assets/images/mdm-fix.gif" image_path="/assets/images/mdm-fix.gif"  %}

Click on [Continue](){: .btn .btn--inverse .btn--small} a few times and then [Install](){: .btn .btn--inverse .btn--small} in the package installation display. You may be prompted for your __Laptop Password__ to allow the installation to continue.

{% include figure url="/assets/images/mac-enrollmentnotification.png" image_path="/assets/images/mac-enrollmentnotification.png"  %}

If there are no errors during installation, you will see a notification appear in the top-right corner of your screen, near the clock. Click on the notification pop-up to open the __System Preferences__ control panel.

If you don't see the notification after 2 minutes: [Click Here](/mac-mdm2){: .btn .btn--success}

{% include figure url="/assets/images/mac-deviceenrollment.png" image_path="/assets/images/mac-deviceenrollment.png"  %}

If you do see the notification, click [Allow](){: .btn .btn--inverse .btn--small} to authorize the device enrollment. You will be prompted for your laptop password and then to login with Duo:

{% include duosetup.md %}

{% include figure url="/assets/images/mac-profiles.png" image_path="/assets/images/mac-profiles.png" %}

After several seconds, you should see a __Device Manager__ display showing that your device has been verified.

[Next Step &rarr;](/mac-installs){: .btn .btn--success .btn--large}
