---
title: "Windows Setup"
permalink: /win/
author_profile: false
sidebar:
  nav: "nav-win"
header:
  overlay_color: "#000"
---

<div class="welcome-page">

  <div class="notice--warning" style="display:flex; gap:1em; align-items:flex-start; margin-bottom:1em;">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" style="width:24px; min-width:24px; height:24px; margin-top:0.1em;"><path d="M10.29 3.86L1.82 18a2 2 0 0 0 1.71 3h16.94a2 2 0 0 0 1.71-3L13.71 3.86a2 2 0 0 0-3.42 0z"/><line x1="12" y1="9" x2="12" y2="13"/><line x1="12" y1="17" x2="12.01" y2="17"/></svg>
    <div>
      <strong>YubiKey required</strong><br/>
      You will need a YubiKey to set up your Windows device. If you didn't receive one, contact <a href="mailto:mission-control@squareup.com">mission-control@squareup.com</a> before proceeding.
    </div>
  </div>

  <div class="notice--danger" style="display:flex; gap:1em; align-items:flex-start; margin-bottom:2em;">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" style="width:24px; min-width:24px; height:24px; margin-top:0.1em;"><circle cx="12" cy="12" r="10"/><line x1="15" y1="9" x2="9" y2="15"/><line x1="9" y1="9" x2="15" y2="15"/></svg>
    <div>
      <strong>Internet connection required</strong><br/>
      Your device must be connected to the internet to continue setup. If you have a VPN running on your network, turn it off — active VPN connections will prevent your laptop from completing enrollment.
    </div>
  </div>

  <div class="welcome-section">
    <h2>Initial Setup</h2>
    <div class="welcome-checklist">

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">1</span></div>
        <div>
          <strong>Power on and select your region</strong>
          <p>Press the <strong>power</strong> button, then select the country you reside in and choose your keyboard layout.</p>
        </div>
      </div>

{% include figure url="/assets/images/win-setup-01.png" image_path="/assets/images/win-setup-01.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">2</span></div>
        <div>
          <strong>Connect to a network</strong>
          <p>Connect your device to a wireless network (your home WiFi or Block-Guest) with internet access. The computer will check for updates and may reboot.</p>
        </div>
      </div>

    </div>
  </div>

  <div class="welcome-section" style="margin-top: 2.5em;">
    <h2>Enroll your device</h2>
    <div class="welcome-checklist">

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">3</span></div>
        <div>
          <strong>"Let's get things set up for your work or school"</strong>
          <p>You should see a screen with the Square or Block logo. Enter your <strong>@squareup.com</strong> or <strong>@block.xyz</strong> email address into the Microsoft login page.</p>
        </div>
      </div>

      <div class="notice--danger" style="display:flex; gap:1em; align-items:flex-start;">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" style="width:24px; min-width:24px; height:24px; margin-top:0.1em;"><circle cx="12" cy="12" r="10"/><line x1="15" y1="9" x2="9" y2="15"/><line x1="9" y1="9" x2="15" y2="15"/></svg>
        <div>
          <strong>Don't see the Block or Square logo?</strong><br/>
          Do not proceed. Contact <a href="mailto:mission-control@squareup.com">mission-control@squareup.com</a> for assistance.
        </div>
      </div>

{% include figure url="/assets/images/win-setup-02.png" image_path="/assets/images/win-setup-02.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">4</span></div>
        <div>
          <strong>Sign in with Okta</strong>
          <p>You'll be taken to an Okta login page. Enter your <strong>username</strong> (e.g. if your email is johndoe@block.xyz, enter <strong>johndoe</strong>) and the password from your welcome email.</p>
        </div>
      </div>

{% include figure url="/assets/images/win-setup-03.png" image_path="/assets/images/win-setup-03.png" %}
{% include figure url="/assets/images/win-setup-04.png" image_path="/assets/images/win-setup-04.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">5</span></div>
        <div>
          <strong>Select Security Key or Biometric Authenticator</strong>
          <p>After entering your credentials, you'll be asked to verify your identity. You'll see two options — select <strong>Security Key or Biometric Authenticator</strong>.</p>
        </div>
      </div>

      <div class="notice--danger" style="display:flex; gap:1em; align-items:flex-start;">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" style="width:24px; min-width:24px; height:24px; margin-top:0.1em;"><circle cx="12" cy="12" r="10"/><line x1="15" y1="9" x2="9" y2="15"/><line x1="9" y1="9" x2="15" y2="15"/></svg>
        <div>
          <strong>Do not select Okta FastPass</strong><br/>
          You must use the <strong>Security Key or Biometric Authenticator</strong> option. Okta FastPass will not work at this stage.
        </div>
      </div>

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">6</span></div>
        <div>
          <strong>Choose Security Key</strong>
          <p>A "Choose a passkey" screen will appear with two options — <strong>iPhone, iPad, or Android device</strong> and <strong>Security key</strong>. Select <strong>Security key</strong>, then insert your YubiKey when prompted.</p>
        </div>
      </div>

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">7</span></div>
        <div>
          <strong>Set up your YubiKey PIN</strong>
          <p>Since this is a new YubiKey, you'll be prompted to create a PIN. Enter a <strong>4-digit number</strong> as your PIN, then confirm it. You'll use this PIN each time you authenticate with your YubiKey. Once set, tap the YubiKey when prompted to complete verification.</p>
        </div>
      </div>

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">8</span></div>
        <div>
          <strong>Wait for setup to complete</strong>
          <p>You should now see a "Setting up for Work or School" screen. Let the computer complete this process — it may take several minutes and restart on its own. Eventually, a Windows login screen will appear showing "Other user." Enter your <strong>work email address</strong> and <strong>Okta password</strong> to sign in.</p>
        </div>
      </div>

{% include figure url="/assets/images/win-setup-05.png" image_path="/assets/images/win-setup-05.png" %}
{% include figure url="/assets/images/win-setup-06.png" image_path="/assets/images/win-setup-06.png" %}
{% include figure url="/assets/images/win-setup-07.png" image_path="/assets/images/win-setup-07.png" %}
{% include figure url="/assets/images/win-setup-08.png" image_path="/assets/images/win-setup-08.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">9</span></div>
        <div>
          <strong>Sign in with Okta again</strong>
          <p>The "Setting up for Work or School" screen will return. An Okta login window will then appear — enter your <strong>username</strong> and <strong>password</strong> once more, then verify with your <strong>YubiKey</strong> when prompted.</p>
        </div>
      </div>

{% include figure url="/assets/images/win-setup-09.png" image_path="/assets/images/win-setup-09.png" %}

    </div>
  </div>

  <div class="welcome-section">
    <h2>Set up Windows Hello &amp; PIN</h2>
    <div class="welcome-checklist">

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">10</span></div>
        <div>
          <strong>Set up Windows Hello</strong>
          <p>When prompted, press <strong>OK</strong> to begin Windows Hello setup. Depending on your laptop, you can set up fingerprint or facial recognition. It's recommended to enable biometrics as it will be used for Okta FastPass later.</p>
        </div>
      </div>

{% include figure url="/assets/images/win-setup-10.png" image_path="/assets/images/win-setup-10.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">11</span></div>
        <div>
          <strong>Set up a PIN</strong>
          <p>Create a PIN that is at least <strong>8 characters</strong> long. You can include letters by checking the box. This PIN will be used to log into your computer — it's recommended to match your Okta password for consistency.</p>
        </div>
      </div>

{% include figure url="/assets/images/win-setup-11.png" image_path="/assets/images/win-setup-11.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">12</span></div>
        <div>
          <strong>Finish setup</strong>
          <p>Click <strong>OK</strong> on the next screen to be taken to the Windows desktop.</p>
        </div>
      </div>

{% include figure url="/assets/images/win-setup-12.png" image_path="/assets/images/win-setup-12.png" %}

      <div class="checklist-item" style="background: #e8f5e9; border-color: #c8e6c9;">
        <div class="checklist-icon" style="background: #fff; border-color: #c8e6c9; color: #00a828;"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></div>
        <div>
          <strong>Windows is set up!</strong>
          <p>You're signed in and on the desktop. Let's continue with updates and app setup.</p>
        </div>
      </div>

    </div>
  </div>

  <div class="welcome-next">
    <a href="/win-updates" class="landing-card-btn welcome-next-btn">
      Next: Windows Updates &rarr;
    </a>
  </div>

  <section class="landing-help" style="padding: 2em 0 0; max-width: 100%;">
    <div class="landing-help-inner">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" class="landing-help-icon"><circle cx="12" cy="12" r="10"/><path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"/><line x1="12" y1="17" x2="12.01" y2="17"/></svg>
      <div>
        <strong>Need help?</strong>
        <span>Contact <a href="mailto:mission-control@squareup.com">mission-control@squareup.com</a></span>
      </div>
    </div>
  </section>

</div>
