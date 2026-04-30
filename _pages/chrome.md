---
title: "ChromeOS Setup"
permalink: /chrome/
author_profile: false
sidebar:
  nav: "nav-chrome"
header:
  overlay_color: "#000"
---

<div class="welcome-container" markdown="0">

  <h1 class="welcome-title">Chromebook Setup</h1>
  <p class="welcome-subtitle">Power on your Chromebook and sign in with your Block account.</p>

  <div class="notice--danger" style="display:flex; gap:1em; align-items:flex-start;">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" style="width:24px; min-width:24px; height:24px; margin-top:0.1em;"><circle cx="12" cy="12" r="10"/><line x1="15" y1="9" x2="9" y2="15"/><line x1="9" y1="9" x2="15" y2="15"/></svg>
    <div>
      <strong>YubiKey required</strong><br/>
      You'll need the <strong>YubiKey</strong> that was included with your Chromebook to complete setup. If you didn't receive one, contact <a href="mailto:mission-control@squareup.com"><strong>mission-control@squareup.com</strong></a> before proceeding.
    </div>
  </div>

  <div class="welcome-section">
    <h2>Initial setup</h2>
    <div class="welcome-checklist">

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">1</span></div>
        <div>
          <strong>Power on your device</strong>
          <p>Press the <strong>power button</strong> at the top-right corner of the keyboard. If you have a ChromeBox, the power button is on the device itself.</p>
        </div>
      </div>

{% include figure url="/assets/images/pixelbookgo-power.jpg" image_path="/assets/images/pixelbookgo-power.jpg" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">2</span></div>
        <div>
          <strong>Connect to a network</strong>
          <p>Connect to a wireless network (your home WiFi or Block-Guest) with internet access.</p>
        </div>
      </div>

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">3</span></div>
        <div>
          <strong>Confirm managed device</strong>
          <p>Your device should show <strong>"Managed by squareup.com"</strong> on the login screen. If you don't see this message, contact <a href="mailto:mission-control@squareup.com">mission-control@squareup.com</a> for assistance.</p>
        </div>
      </div>

{% include figure url="/assets/images/chrome-01-login.jpg" image_path="/assets/images/chrome-01-login.jpg" %}

    </div>
  </div>

  <div class="welcome-section">
    <h2>Sign in with Okta</h2>
    <div class="welcome-checklist">

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">4</span></div>
        <div>
          <strong>Enter your email</strong>
          <p>Enter your full <strong>@squareup.com</strong> or <strong>@block.xyz</strong> email address and click <strong>Next</strong>.</p>
        </div>
      </div>

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">5</span></div>
        <div>
          <strong>Sign in with Okta</strong>
          <p>Enter your <strong>username</strong> and the password from your welcome email, then click <strong>Verify</strong>.</p>
        </div>
      </div>

{% include figure url="/assets/images/duo-login2.jpg" image_path="/assets/images/duo-login2.jpg" %}

    </div>
  </div>

  <div class="welcome-section">
    <h2>Set up your Security Key</h2>
    <div class="welcome-checklist">

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">6</span></div>
        <div>
          <strong>Begin Security Key setup</strong>
          <p>When prompted to set up a Security Key or Biometric Authenticator, click <strong>Set Up</strong>.</p>
        </div>
      </div>

{% include figure url="/assets/images/security-key-setup.png" image_path="/assets/images/security-key-setup.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">7</span></div>
        <div>
          <strong>Choose USB Security Key</strong>
          <p>Select <strong>USB Security Key</strong>, then insert your YubiKey into the USB port on your Chromebook.</p>
        </div>
      </div>

{% include figure url="/assets/images/yubikey-5c-nfc.png" image_path="/assets/images/yubikey-5c-nfc.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">8</span></div>
        <div>
          <strong>Tap the YubiKey and allow access</strong>
          <p>When prompted, touch the <strong>gold sensor</strong> on the YubiKey. Click <strong>Allow</strong> when asked if the site can use your Security Key.</p>
        </div>
      </div>

{% include figure url="/assets/images/security-key-allow.png" image_path="/assets/images/security-key-allow.png" %}

    </div>
  </div>

  <div class="welcome-section">
    <h2>Finish sign-in</h2>
    <div class="welcome-checklist">

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">9</span></div>
        <div>
          <strong>Accept and continue</strong>
          <p>Once signed in, click <strong>Accept and Continue</strong>. You may hear the Google Assistant announce it has been disabled — press the <strong>mute button</strong> (above the "0" key) to silence the audio.</p>
        </div>
      </div>

{% include figure url="/assets/images/chrome-02-signin.jpg" image_path="/assets/images/chrome-02-signin.jpg" %}

      <div class="checklist-item" style="background: #e8f5e9; border-color: #c8e6c9;">
        <div class="checklist-icon" style="background: #fff; border-color: #c8e6c9; color: #00a828;"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></div>
        <div>
          <strong>You're signed in!</strong>
          <p>Your Chromebook is ready. Let's set up your browser next.</p>
        </div>
      </div>

    </div>
  </div>

  <div class="welcome-next">
    <a href="/chrome-browser" class="landing-card-btn welcome-next-btn">
      Next: Browser Setup &rarr;
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
