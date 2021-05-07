---
title: "Device Management"
permalink: /mac-mdm/
author_profile: true
sidebar:
  nav: "nav-mac"
header:
  overlay_image: /assets/images/splash_mac.jpg
---

We have to do some extra steps to get your Macbook enrolled with our Mobile Device Management (MDM) system.

First you will need to open Safari, it should be located in the dock along the bottom (with a blue compass icon).

Now lets type __newcomputer.square.com/mdmfix__ into the address bar in Safari.

__insert image__

Click [Download](#mdmfix){: .btn .btn--inverse .btn--small} on the page and once the download completes, click on the package name (in the bottom-left of your web browser) to start the package installation:

<a name="mdmfix"></a>
{% include figure url="/assets/images/mdm-fix.gif" image_path="/assets/images/mdm-fix.gif"  %}

Click on [Continue](#enrol){: .btn .btn--inverse .btn--small} a few times and then [Install](#enrol1){: .btn .btn--inverse .btn--small} in the package installation display. You may be prompted for your __Laptop Password__ to allow the installation to continue.


<a name="enrol1"></a>
{% include figure url="/assets/images/mac-enrol1.jpg" image_path="/assets/images/mac-enrol1.jpg"  %}

If there are no errors during installaation, you will see a notification appear in the top-right corner of your screen, near the clock. Click [Details](#enrol2){: .btn .btn--inverse .btn--small} on the notification pop-up to open the __System Preferences__ control panel.

<a name="enrol2"></a>
{% include figure url="/assets/images/mac-enrol2.jpg" image_path="/assets/images/mac-enrol2.jpg"  %}

Click [Allow](#duo){: .btn .btn--inverse .btn--small} to authorize the device enrollment. You will be prompted to login with Duo:

<a name="duo"></a>
{% include figure url="/assets/images/duo-login2.jpg" image_path="/assets/images/duo-login2.jpg" %}

Enter just your username (**without the** @squareup.com) and your temporary password and click [Login](#push){: .btn .btn--inverse .btn--small}

If you have set up Duo previously, skip forward to the send a push section below.

Click [Start Setup](#push){: .btn .btn--inverse .btn--small} and go through the whole process.

* Choose **Mobile phone**
* Enter **Phone Number**
* Choose **phone type**
* Select **I have Duo Mobile installed**
* Open **Duo Mobile app on your phone and Click the +**
* Scan **QR Code**
* Select **Continue to Login**
* Click on [Send Me a Push](#push){: .btn .btn--inverse .btn--small}
* Approve **Push notification on your phone**

<a name="push"></a>
{% include figure url="/assets/images/duo-push.jpg" image_path="/assets/images/duo-push.jpg" caption="(if you do not see these options, ask for [help](/help))" %}

<a name="push"></a>
{% include figure url="/assets/images/duo-push.jpg" image_path="/assets/images/duo-push.jpg"  %}

Choose one of the authentication methods, such as sending a push notice to your mobile app.

{% include figure url="/assets/images/mac-device.jpg" image_path="/assets/images/mac-device.jpg" %}

After several seconds, you should see a __Device Manager__ display showing that your device has been verified.

[Next Step &rarr;](/mac-installs){: .btn .btn--success .btn--large}
