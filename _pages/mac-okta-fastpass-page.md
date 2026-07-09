---
title: "Mac Okta Fastpass"
permalink: /mac-okta-fastpass-page/
author_profile: true
sidebar:
  nav: "nav-mac"
header:
  overlay_color: "#333"
---
Let's set up __Okta Fastpass__. 

Okta FastPass provides a quick, easy and secure way to sign in and helps protect you from phishing.

On your MacBook, click the __Okta Verify__ app icon that appears in the top right area of your screen.

{% include figure url="/assets/images/mac-okta-icon-menu-bar.png" image_path="/assets/images/mac-okta-icon-menu-bar.png" %}
{% include figure url="/assets/images/mac-okta-menu-bar.png" image_path="/assets/images/mac-okta-menu-bar.png" %}

Next, click on __Open Okta Verify__ to open it, and click [Get Started](){: .btn .btn--inverse .btn--small}

{% include figure url="/assets/images/mac-oktafastpass-getstarted.png" image_path="/assets/images/mac-oktafastpass-getstarted.png" %}

Select __Sign In__ to add your account using your Okta credentials.

{% include figure url="/assets/images/okta-fp-signin-new.png" image_path="/assets/images/okta-fp-signin-new.png" %}

Enter __login.block.xyz__ as your organization's sign-in URL, then click [Next](){: .btn .btn--inverse .btn--small}.

Enter your __username__ and __password__, then click [Sign In](){: .btn .btn--inverse .btn--small}.

{% include figure url="/assets/images/okta-login-mac1.png" image_path="/assets/images/okta-login-mac1.png" %}

When asked to verify it's you, choose __Security Key or Biometric Authenticator__ and click [Select](){: .btn .btn--inverse .btn--small}

{% include figure url="/assets/images/okta-security-method.png" image_path="/assets/images/okta-security-method.png" %}

When prompted for additional verification, insert your __YubiKey__ and tap the metal contact to authenticate.

{% include figure url="/assets/images/security-key-allow.png" image_path="/assets/images/security-key-allow.png" %}

__NOTE__: Biometrics (Touch ID) are preferred when using Okta FastPass. If you do not enable/use biometrics on your Block-issued device you will be prompted for another factor (password) when using Okta FastPass. 


{% include figure url="/assets/images/okta-fp-touchid-1.png" image_path="/assets/images/okta-fp-touchid-1.png" %}

{% include figure url="/assets/images/enable-touch-id.png" image_path="/assets/images/enable-touch-id.png" %}

If you opted-in for Touch ID, you will see the above screen. If you skipped Touch ID, please move to the next step:

Click [Enable Touch ID](){: .btn .btn--inverse .btn--small}.

If prompted, authenticate using Touch ID.

Success! 🎉 You're all setup with Okta Fastpass! 

[Next](/mac-chrome){: .btn .btn--success} 
