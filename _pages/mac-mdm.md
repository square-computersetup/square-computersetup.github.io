---
title: "Mac MDM"
permalink: /mac-mdm/
author_profile: true
sidebar:
  nav: "nav-shared"
header:
  overlay_image: /assets/images/splash_mac.jpg
---

We have to do some extra steps to get your Macbook enrolled with our Mobile Device Management (MDM) system. Open the Safari web browser (look for the _compass_ icon in the bottom system tray) and in the address bar at the top, enter __go.sqprod.co/mdmfix__ 

{% include figure url="/assets/images/go-mdmfix.jpg" image_path="/assets/images/go-mdmfix.jpg" caption="(in a future setup, we will configure even shorter __go/__ links)" %}

__NOTE:__ You may be prompted to authenticate to Duo SSO again. You may check the box that says __Remember me for 12 hours__ to avoid authenticating more than once daily.
{: .notice--warning}

Click [Download](#mdmfix){: .btn .btn--inverse .btn--small} and once the download completes, click on the package name (in the bottom-left of your web browser) to start the package installation:

<a name="mdmfix"></a> 
{% include figure url="/assets/images/mdm-fix.gif" image_path="/assets/images/mdm-fix.gif"  %}

Click on [Continue](#enrol){: .btn .btn--inverse .btn--small} a few times and then [Install](#enrol1){: .btn .btn--inverse .btn--small} in the package installation display. You may be prompted for your __Laptop Password__ to allow the installation to continue (remember this may be different from your Duo SSO password). 

<a name="enrol1"></a> 
{% include figure url="/assets/images/mac-enrol1.jpg" image_path="/assets/images/mac-enrol1.jpg"  %}

If there are no errors during installaation, you will see a notification appear in the top-right corner of your screen, near the clock. Click [Details](#enrol2){: .btn .btn--inverse .btn--small} on the notification pop-up to open the __System Preferences__ control panel. 

<a name="enrol2"></a> 
{% include figure url="/assets/images/mac-enrol2.jpg" image_path="/assets/images/mac-enrol2.jpg"  %}

Click [Allow](#duo){: .btn .btn--inverse .btn--small} to authorize the device enrollment. You will be prompted to login with Duo once again:

<a name="duo"></a> 
{% include figure url="/assets/images/duo-login.jpg" image_path="/assets/images/duo-login.jpg" %}

Enter just your username (jsmith not jsmith@squareup.com) and your password and click [Login](#push){: .btn .btn--inverse .btn--small}

<a name="push"></a> 
{% include figure url="/assets/images/duo-push.jpg" image_path="/assets/images/duo-push.jpg"  %}

Choose one of the authentication methods, such as sending a push notice to your mobile app. 

{% include figure url="/assets/images/mac-device.jpg" image_path="/assets/images/mac-device.jpg" %}

After several seconds, you should see a __Device Manager__ display showing that your device has been verified. 

[Next Step &rarr;](/mac-mgmt){: .btn .btn--success .btn--large}
