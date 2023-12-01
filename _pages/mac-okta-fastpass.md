---
title: "Mac Okta Fastpass"
permalink: /mac-okta-fastpass/
author_profile: true
sidebar:
  nav: "nav-mac"
header:
  overlay_color: "#333"
---
Let's set up __Okta Fastpass__. 

Okta FastPass provides a quick, easy and secure way to sign in and helps protect you from phishing.

Click the __Launchpad__ app in the dock at the bottom of your screen.

{% include figure url="/assets/images/launchpad.png" image_path="/assets/images/launchpad.png" %}

Next, click on __Okta Verify__ to open it, and click [Get Started](){: .btn .btn--inverse .btn--small}

{% include figure url="/assets/images/okta-verify-app.png" image_path="/assets/images/okta-verify-app.png" %}

Under __New account__ it should say __login.block.xyz__ as the sign-in URL. 
Click [Next](){: .btn .btn--inverse .btn--small} to continue with setup.

{% include figure url="/assets/images/okta-fp-signin.png" image_path="/assets/images/okta-fp-signin.png" %}

Now, it should open an Okta sign-in page in Safari. Sign in, and send a __Push notification__ using __Okta Verify mobile.__


Two options are available:

Select __Next__ to enable Touch ID (allows quick, passwordless logon on Block devices)

If you do not want to use Touch ID, Select __Skip__

Note: Biometrics (Touch ID) are preferred when using Okta FastPass. If you do not enable/use biometrics on your Block-issued device you will be prompted for another factor (password) when using Okta FastPass. 


{% include figure url="/assets/images/okta-fp-touchid-1.png" image_path="/assets/images/okta-fp-touchid-1.png" %}

{% include figure url="/assets/images/enable-touch-id.png" image_path="/assets/images/enable-touch-id.png" %}

If you opted-in for Touch ID you will see the above screen. If you skipped Touch ID, please move to the next step:

Click [Enable Touch ID](){: .btn .btn--inverse .btn--small}.

If prompted, authenticate using Touch ID.

Success! 🎉 You're all setup with Okta Fastpass! 

[Next](/mac-chrome){: .btn .btn--success} 
