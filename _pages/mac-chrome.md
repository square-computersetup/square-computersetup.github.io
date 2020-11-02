---
title: "Mac Chrome"
permalink: /mac-chrome/
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

You will have to wait 4-5 minutes for the next step to launch on its own. This delay is normal and expected. 

{% include figure url="/assets/images/mac-mgmt.jpg" image_path="/assets/images/mac-mgmt.jpg" caption="(if you do not see this after five minutes, restart your Macbook and wait another five minutes)" %}

This installer will spend 10-45 minutes (depending on your Internet speed) retrieving and installing tools.

{% include figure url="/assets/images/mac-git.jpg" image_path="/assets/images/mac-git.jpg" caption="(you may or may not see this prompt)" %}

If prompted to install __Developer Tools__, click [Install](#updates){: .btn .btn--inverse .btn--small}

<a name="updates"></a> 
{% include figure url="/assets/images/mac-updates.jpg" image_path="/assets/images/mac-updates.jpg" caption="(you may or may not see this prompt)" %}

If you see the __Updates Available__ notification, click [Later](#installer){: .btn .btn--inverse .btn--small} to defer the installation.

<a name="installer"></a> 
Once the installer has completed, it will thank you for your patience. Click [Quit](#logout){: .btn .btn--inverse .btn--small} to exit the installer.

<a name="logout"></a> 
{% include figure url="/assets/images/mac-logout.jpg" image_path="/assets/images/mac-logout.jpg"  %}

Click the <img src='/assets/images/apple.png' width='15' height='15'> symbol in the very top-left cover of your Macbook, and then click [Logout](#login){: .btn .btn--inverse .btn--small}.

<a name="login"></a> 
You may see some updates happening after you logout. After you no longer see any visual indication an update is happening, __Login__ again using your __Laptop Password__ (which may be differen than your Duo SSO password).


[Next Step &rarr;](/mac-chrome){: .btn .btn--success .btn--large}
