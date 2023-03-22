---
title: "Mac Chrome"
permalink: /mac-chrome/
author_profile: true
sidebar:
  nav: "nav-mac"
header:
  overlay_color: "#333"
---

Now, some extra steps to get Google Chrome properly set up for use as your primary web browser. Let's start with accessing __Spotlight Search__ by pressing __Command__ + __Spacebar__ on your keyboard.

{% include figure url="/assets/images/command+spacebar.png" image_path="/assets/images/command+spacebar.png" %}

{% include figure url="/assets/images/mac-chrome-spotlight.png" image_path="/assets/images/mac-chrome-spotlight.png" %}

Type in __Chrome__ and then click on the top hit, which is the application itself.

{% include figure url="/assets/images/mac-chrome-firewall.png" image_path="/assets/images/mac-chrome-firewall.png" %}

Click [Allow](){: .btn .btn--inverse .btn--small} if you see a one-time warning that Google Chrome wishes to accept incoming network connections. This is normal and expected.

{% include figure url="/assets/images/mac-chrome-welcome.png" image_path="/assets/images/mac-chrome-welcome.png"  %}

On the __Welcome to Google Chrome__ screen, click [Start Google Chrome](){: .btn .btn--inverse .btn--small}.

{% include figure url="/assets/images/mac-chrome-default.png" image_path="/assets/images/mac-chrome-default.png"  %}

Click on [Use Chrome](){: .btn .btn--inverse .btn--small} to set the default web browser.

{% include figure url="/assets/images/mac-chrome-notification.png" image_path="/assets/images/mac-chrome-notification.png"  %}

You will get a notification in the top right of your screen to allow Chrome to send you notifications, click [Allow](){: .btn .btn--inverse .btn--small}

Next, we will sign-in to Google Chrome to link it to Block's Google Workplace (formerly "GSuite").

{% include figure url="/assets/images/mac-chrome-signin.png" image_path="/assets/images/mac-chrome-signin.png"  %}

Click on the text __Already a Chrome user? Sign In__ on the __Make Chrome your own__ page.

Login to Google using your full Block email address (jsmith@squareup.com). Then you will be redirected to Okta:

{% include figure url="/assets/images/duo-login2.jpg" image_path="/assets/images/duo-login2.jpg" %}

Enter email and your password and click [Sign In](){: .btn .btn--inverse .btn--small}

{% include figure url="/assets/images/duo-push.jpg" image_path="/assets/images/duo-push.jpg"  %}

Choose one of the authentication methods, such as sending a push notice to your mobile app.

{% include figure url="/assets/images/mac-chrome-password.png" image_path="/assets/images/mac-chrome-password.png"  %}

Chrome will ask if you'd like to save this password. While it is acceptable to save passwords to Chrome in the future if you would like, we will skip this step for now. Click the small __X__ to decline this action.

{% include figure url="/assets/images/mac-chrome-link.png" image_path="/assets/images/mac-chrome-link.png"  %}

When prompted to sync your browser with Block's Google services, click on [Link Data](){: .btn .btn--inverse .btn--small}.

{% include figure url="/assets/images/mac-chrome-sync.png" image_path="/assets/images/mac-chrome-sync.png"  %}

Click on [Yes I'm in](){: .btn .btn--inverse .btn--small} to confirm a sync with Block's Google services.

{% include chromeext.md %}

[Next Step &rarr;](/mac-go/){: .btn .btn--success .btn--large}
