---
title: "Mac Chrome"
permalink: /mac-chrome/
author_profile: true
sidebar:
  nav: "nav-mac"
header:
  overlay_image: /assets/images/splash_mac.jpg
---

Now, some extra steps to get Google Chrome properly setup for use as your primary web browser. Let's start with accessing __Spotlight__ by clicking on the magnifying glass icon in the extreme top-right corner of the desktop:

{% include figure url="/assets/images/mac-spotlight.jpg" image_path="/assets/images/mac-spotlight.jpg" caption="(Spotlight is the built-in search tool for MacOS)" %}

{% include figure url="/assets/images/mac-chrome-search.jpg" image_path="/assets/images/mac-chrome-search.jpg" %}

Type in __Chrome__ and then click on the top hit, which is the application itself.

{% include figure url="/assets/images/mac-chrome-firewall.jpg" image_path="/assets/images/mac-chrome-firewall.jpg" %}

Click [Allow](#install){: .btn .btn--inverse .btn--small} when you see a one-time warning that Google Chrome wishes to accept incoming network connections. This is normal and expected.

<a name="install"></a>
{% include figure url="/assets/images/mac-chrome-install.jpg" image_path="/assets/images/mac-chrome-install.jpg"  %}

On the __Welcome to Google Chrome__ screen, click [Start Google Chrome](#default){: .btn .btn--inverse .btn--small}.

<a name="default"></a>
{% include figure url="/assets/images/mac-chrome-default.jpg" image_path="/assets/images/mac-chrome-default.jpg"  %}

Click on [Use Chrome](#notify){: .btn .btn--inverse .btn--small} to set the default web browser.

<a name="notify"></a>
{% include figure url="/assets/images/mac-chrome-notify.jpg" image_path="/assets/images/mac-chrome-notify.jpg"  %}

Click on [Allow](#sync){: .btn .btn--inverse .btn--small} to permit website notifications.

<a name="sync"></a>
Next, we will sign-in to Google Chrome to link it to Square's Google Workplace (formerly "GSuite").

{% include figure url="/assets/images/mac-chrome-login.jpg" image_path="/assets/images/mac-chrome-login.jpg"  %}

Click on the person icon in the top-right corner of the Chrome browser, then click [Turn on sync...](#synced){: .btn .btn--inverse .btn--small}

<a name="synced"></a>
First, login to Google using your full Square email address (jsmith@squareup.com). Then you will be redirected to Duo SSO:

<a name="duo"></a>
{% include figure url="/assets/images/duo-login2.jpg" image_path="/assets/images/duo-login2.jpg" %}

Enter just your username (**without the** @squareup.com) and your password and click [Login](#push){: .btn .btn--inverse .btn--small}

<a name="push"></a>
{% include figure url="/assets/images/duo-push.jpg" image_path="/assets/images/duo-push.jpg"  %}

Choose one of the authentication methods, such as sending a push notice to your mobile app.

{% include figure url="/assets/images/mac-chrome-password.jpg" image_path="/assets/images/mac-chrome-password.jpg"  %}

Chrome will ask if you'd like to save this password. While it is acceptable to save passwords to Chrome in the future if you would like, we will skip this step for now. Click the small __X__ to decline this action.

{% include figure url="/assets/images/mac-chrome-link.jpg" image_path="/assets/images/mac-chrome-link.jpg"  %}

When prompted to sync your browser with Square's Google services, click on [Link Data](#link){: .btn .btn--inverse .btn--small}.

<a name="link"></a>
{% include figure url="/assets/images/mac-chrome-sync.jpg" image_path="/assets/images/mac-chrome-sync.jpg"  %}

Click on [Yes I'm in](#yes){: .btn .btn--inverse .btn--small} to confirm a sync with Square's Google services.

<a name="yes"></a>
Within a minute, you will see some mandatory Chrome extensions installed in the top-right corner of Google Chrome.

{% include figure url="/assets/images/chrome-extensions.jpg" image_path="/assets/images/chrome-extensions.jpg" caption="(if no Square logo appears within two minutes, enter __chrome://restart__ in the address bar, press enter, and wait a few more minutes)" %}

Once you see the Square logo, your Chrome web browser is properly configured and ready for use.


[Next Step &rarr;](/go/){: .btn .btn--success .btn--large}
