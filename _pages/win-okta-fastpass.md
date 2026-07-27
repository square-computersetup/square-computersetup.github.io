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

{% include figure url="/assets/images/okta-export-account-button.png" image_path="/assets/images/okta-export-account-button.png" caption="(Okta Verify looks and works the same whether you're on Mac or Windows)" %}

Add your account using the option that matches how you verify your identity &mdash; expand the one that applies to you:

<details markdown="1" style="border: 1px solid #e0e0e0; border-radius: 8px; padding: 0.75em 1em; margin: 1em 0;">
<summary style="cursor: pointer; font-size: 1.1em;"><strong>🔑 I have a YubiKey</strong></summary>

Click __Get started__ to add your account using your Okta credentials.

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

If you already use Okta Verify on your mobile phone, you can import your account to your Windows device over Bluetooth. Make sure Bluetooth is enabled on both devices.

1. On your __phone__, open Okta Verify and tap your Block account.
2. Tap __Export account__ and follow the instructions, then tap __Allow__ to approve the Bluetooth export. A QR code and an alphanumeric code will appear.
3. On your __Windows device__, click __Add account from another device__ on the Okta Verify welcome screen, then follow the prompts.
4. Click __Continue__ to allow Bluetooth import. If asked to enable Bluetooth, click __OK__, then __Got it__.
5. Set up the account using the __alphanumeric code__ shown on your phone. When it succeeds, a __6-digit PIN__ appears on your Windows device.
6. Enter that 6-digit PIN into Okta Verify on your __phone__ to confirm the pairing.
7. You'll see a confirmation message on your Windows device once your account has been added.

__NOTE:__ Never enter a PIN given to you by anyone else.
{: .notice--warning}

</details>

<details markdown="1" style="border: 1px solid #e0e0e0; border-radius: 8px; padding: 0.75em 1em; margin: 1em 0;">
<summary style="cursor: pointer; font-size: 1.1em;"><strong>💻 I have Okta Verify on another device</strong></summary>

If you already use Okta Verify on another Mac or Windows device, you can import your account to your new Windows device over Bluetooth. Make sure Bluetooth is enabled on both devices.

1. On your __old device__, click the Okta Verify icon in the menu bar (Mac) or system tray (Windows), then click __Open Okta Verify__, and select your account.

   {% include figure url="/assets/images/okta-export-menu-bar.png" image_path="/assets/images/okta-export-menu-bar.png" %}

   {% include figure url="/assets/images/okta-export-account-select.png" image_path="/assets/images/okta-export-account-select.png" %}

2. Click __Export account__, then authenticate with __Touch ID__, __Windows Hello__, or your password when prompted.

   {% include figure url="/assets/images/okta-export-account-button.png" image_path="/assets/images/okta-export-account-button.png" %}

3. Click __Allow__ to approve the Bluetooth export. A QR code and an alphanumeric code will appear.

   {% include figure url="/assets/images/okta-export-qr-code.png" image_path="/assets/images/okta-export-qr-code.png" %}

4. On your __new Windows device__, click __Add account from another device__ on the Okta Verify welcome screen, then follow the prompts.
5. Click __Continue__ to allow Bluetooth import. If asked to enable Bluetooth, click __OK__, then __Got it__.
6. Set up the account using the __alphanumeric code__ shown on your old device. When it succeeds, a __6-digit PIN__ appears on your new Windows device.
7. Enter that 6-digit PIN into Okta Verify on your __old device__ to confirm the pairing.
8. You'll see a confirmation message on your new Windows device once your account has been added.

__NOTE:__ Never enter a PIN given to you by anyone else.
{: .notice--warning}

</details>

__Note:__ Biometrics (Windows Hello) are preferred when using Okta FastPass. If you do not enable or use biometrics on your Block-issued device, you will be prompted for another factor (password) when using Okta FastPass.

{% include figure url="/assets/images/ofp-win9.png" image_path="/assets/images/ofp-win9.png" %}

{% include figure url="/assets/images/ofp-win10.png" image_path="/assets/images/ofp-win10.png" %}

If prompted, authenticate using Windows Hello.
Success! 🎉 You're all setup with Okta Fastpass!

[Next](/win-chrome){: .btn .btn--success} 
