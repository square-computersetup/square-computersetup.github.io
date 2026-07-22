---
title: "Okta FastPass"
permalink: /mac-okta-fastpass-page/
author_profile: true
sidebar:
  nav: "nav-mac"
header:
  overlay_color: "#333"
---
# Setting up Okta FastPass

Okta FastPass provides a quick, easy and secure way to sign in and helps protect you from phishing. Let's set it up before we configure Google Chrome.

## Set Google Chrome as your default browser

Signing in to Okta FastPass will open your web browser, so first make sure Google Chrome is set as your default browser.

* Open System Settings.
* In the search bar, type "Default web browser" and select the option that appears.
* Find the __Default web browser__ section and select Google Chrome to make it your default browser.

{% include figure url="/assets/images/default-web-browser.png" image_path="/assets/images/default-web-browser.png" %}

## Set up Okta Verify

__NOTE:__ Do not install Okta Verify from the App Store. It must be installed through the Managed Software Center. If you don't see Okta Verify on your computer, ensure you've completed all updates from the [Managed Software Center](/mac-installs/). If the Managed Software Center is not on your computer, please [contact IT](/help/) for further help.
{: .notice--warning}

On your MacBook, click the __Okta Verify__ app icon that appears in the top right area of your screen, then click __Open Okta Verify__.

<img src="/assets/images/mac-okta-icon-menu-bar.png" style="width: 192px !important; max-width: 192px !important;" />

{% include figure url="/assets/images/mac-okta-menu-bar.png" image_path="/assets/images/mac-okta-menu-bar.png" %}

{% include figure url="/assets/images/mac-oktafastpass-getstarted-new.png" image_path="/assets/images/mac-oktafastpass-getstarted-new.png" %}

From the welcome screen, add your account using the option that matches how you verify your identity &mdash; expand the one that applies to you:

<details markdown="1" style="border: 1px solid #e0e0e0; border-radius: 8px; padding: 0.75em 1em; margin: 1em 0;">
<summary style="cursor: pointer; font-size: 1.1em;"><strong>🔑 I have a YubiKey</strong></summary>

Click __Get started__ (or __Sign In__ on some versions) to add your account using your Okta credentials.

Enter __login.block.xyz__ as your organization's sign-in URL, then click [Next](){: .btn .btn--inverse .btn--small}.

Enter your __username__ and __password__, then click [Sign In](){: .btn .btn--inverse .btn--small}.

{% include figure url="/assets/images/okta-login-mac1.png" image_path="/assets/images/okta-login-mac1.png" %}

When asked to verify it's you, choose __Security Key or Biometric Authenticator__ and click [Select](){: .btn .btn--inverse .btn--small}

{% include figure url="/assets/images/okta-security-method.png" image_path="/assets/images/okta-security-method.png" %}

When prompted for additional verification, insert your __YubiKey__ and tap the metal contact to authenticate.

{% include figure url="/assets/images/security-key-activate.png" image_path="/assets/images/security-key-activate.png" %}

</details>

<details markdown="1" style="border: 1px solid #e0e0e0; border-radius: 8px; padding: 0.75em 1em; margin: 1em 0;">
<summary style="cursor: pointer; font-size: 1.1em;"><strong>📱 I have Okta Verify on my phone</strong></summary>

If you already use Okta Verify on your mobile phone, you can import your account to your MacBook over Bluetooth. Make sure Bluetooth is enabled on both devices.

1. On your __phone__, open Okta Verify and tap your Block account.
2. Tap __Export account__ and follow the instructions, then tap __Allow__ to approve the Bluetooth export. A QR code and an alphanumeric code will appear.
3. On your __MacBook__, click __Import account__ on the Okta Verify welcome screen, then follow the prompts.
4. Click __Continue__ to allow Bluetooth import. If asked to enable Bluetooth, click __OK__, then __Got it__.
5. Set up the account using the __alphanumeric code__ shown on your phone. When it succeeds, a __6-digit PIN__ appears on your MacBook.
6. Enter that 6-digit PIN into Okta Verify on your __phone__ to confirm the pairing.
7. You'll see a confirmation message on your MacBook once your account has been added.

__NOTE:__ Never enter a PIN given to you by anyone else.
{: .notice--warning}

</details>

__NOTE__: Biometrics (Touch ID) are preferred when using Okta FastPass. If you do not enable/use biometrics on your Block-issued device you will be prompted for another factor (password) when using Okta FastPass.
{: .notice--warning}

{% include figure url="/assets/images/okta-fp-touchid-1.png" image_path="/assets/images/okta-fp-touchid-1.png" %}

{% include figure url="/assets/images/enable-touch-id.png" image_path="/assets/images/enable-touch-id.png" %}

If you opted in for Touch ID, you will see the above screen &mdash; click [Enable Touch ID](){: .btn .btn--inverse .btn--small} and authenticate using Touch ID when prompted. If you skipped Touch ID, move to the next step.

Success! 🎉 You're all set up with Okta FastPass!

[Next Step &rarr;](/mac-chrome/){: .btn .btn--success .btn--large}
