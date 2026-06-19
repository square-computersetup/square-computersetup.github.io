---
title: "Windows Okta Fastpass"
permalink: /win-okta-fastpass/
author_profile: true
sidebar:
  nav: "nav-win"
header:
  overlay_color: "#333"
---

# Windows Okta Fastpass

__Okta FastPass__ provides a quick, easy, and secure way to sign in and helps protect you from phishing.

Open the __Okta Verify__ app on your Windows device by clicking the Start menu at the bottom of your screen, then searching for __Okta Verify__. 

{% include figure url="/assets/images/ofp-win3.png" image_path="/assets/images/ofp-win3.png" %}

Select __Sign In__ to add your account using your Okta credentials.

{% include figure url="/assets/images/ofp-win4.png" image_path="/assets/images/ofp-win4.png" caption="(Note that Okta Verify Desktop can be run in Light or Dark mode)" %}

Enter __login.block.xyz__ as your organization's sign-in URL, then click [Next](){: .btn .btn--inverse .btn--small}.

Enter your __username__ and __password__, then click [Sign In](){: .btn .btn--inverse .btn--small}.

{% include figure url="/assets/images/okta-login-mac1.png" image_path="/assets/images/okta-login-mac1.png" %}

When prompted for additional verification, insert your __YubiKey__ and tap the metal contact to authenticate.

{% include figure url="/assets/images/security-key-allow.png" image_path="/assets/images/security-key-allow.png" %}

__Note:__ Biometrics (Windows Hello) are preferred when using Okta FastPass. If you do not enable or use biometrics on your Block-issued device, you will be prompted for another factor (password) when using Okta FastPass.

{% include figure url="/assets/images/ofp-win9.png" image_path="/assets/images/ofp-win9.png" %}

{% include figure url="/assets/images/ofp-win10.png" image_path="/assets/images/ofp-win10.png" %}

If prompted, authenticate using Windows Hello.
Success! 🎉 You're all setup with Okta Fastpass!

[Next](/win-chrome){: .btn .btn--success} 
