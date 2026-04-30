---
title: "Chrome Setup"
permalink: /mac-chrome/
author_profile: false
sidebar:
  nav: "nav-mac"
header:
  overlay_color: "#000"
---

<div class="welcome-page">

  <div class="welcome-section">
    <h2>Set Chrome as your default browser</h2>
    <div class="welcome-checklist">

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">1</span></div>
        <div>
          <strong>Open System Settings</strong>
          <p>Click the <strong>Apple menu</strong> in the top-left corner of your screen, then select <strong>System Settings</strong>.</p>
        </div>
      </div>

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">2</span></div>
        <div>
          <strong>Search for "Default web browser"</strong>
          <p>Type <strong>Default web browser</strong> in the search bar and select the option that appears. Change it to <strong>Google Chrome</strong>.</p>
        </div>
      </div>

{% include figure url="/assets/images/default-web-browser.png" image_path="/assets/images/default-web-browser.png" %}

    </div>
  </div>

  <div class="welcome-section">
    <h2>Set up Okta FastPass</h2>
    <p style="color: var(--g600, #6b7280); margin-bottom: 1.5em;">Okta FastPass provides quick, secure sign-in and helps protect you from phishing.</p>

    <div class="notice--warning" style="display:flex; gap:1em; align-items:flex-start; margin-bottom:1.5em;">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" style="width:24px; min-width:24px; height:24px; margin-top:0.1em;"><path d="M10.29 3.86L1.82 18a2 2 0 0 0 1.71 3h16.94a2 2 0 0 0 1.71-3L13.71 3.86a2 2 0 0 0-3.42 0z"/><line x1="12" y1="9" x2="12" y2="13"/><line x1="12" y1="17" x2="12.01" y2="17"/></svg>
      <div>
        <strong>Don't see Okta Verify on your Mac?</strong><br/>
        Do not install it from the App Store. Okta Verify must be installed through the Managed Software Center. Go back to <a href="/mac-installs/">Software Installation</a> if you haven't completed that step.
      </div>
    </div>

    <div class="welcome-checklist">

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">3</span></div>
        <div>
          <strong>Enable Bluetooth on your phone</strong>
          <p>Use your phone's Control Center or Settings to make sure Bluetooth is turned on.</p>
        </div>
      </div>

{% include figure url="/assets/images/bluetooth-mobile.png" image_path="/assets/images/bluetooth-mobile.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">4</span></div>
        <div>
          <strong>Open Okta Verify on your Mac</strong>
          <p>Click the <strong>Okta Verify</strong> icon in the menu bar at the top-right of your screen, then click <strong>Open Okta Verify</strong>.</p>
        </div>
      </div>

{% include figure url="/assets/images/mac-okta-icon-menu-bar.png" image_path="/assets/images/mac-okta-icon-menu-bar.png" %}
{% include figure url="/assets/images/mac-okta-menu-bar.png" image_path="/assets/images/mac-okta-menu-bar.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">5</span></div>
        <div>
          <strong>Add account from another device</strong>
          <p>Click <strong>Add account from another device</strong>, then allow the Bluetooth connection when prompted.</p>
        </div>
      </div>

{% include figure url="/assets/images/mac-oktafastpass-getstarted-new.png" image_path="/assets/images/mac-oktafastpass-getstarted-new.png" %}
{% include figure url="/assets/images/allow-bluetooth.png" image_path="/assets/images/allow-bluetooth.png" %}
{% include figure url="/assets/images/allow-bluetooth-popup.png" image_path="/assets/images/allow-bluetooth-popup.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">6</span></div>
        <div>
          <strong>Pair from your phone</strong>
          <p>Open the Okta Verify app on your phone, select your Block account, then scroll down and tap <strong>Add Account to Another Device</strong>. You'll see a QR code with an 8-character code below it — enter this code into the Okta Verify "Enter code" field on your Mac.</p>
        </div>
      </div>

{% include figure url="/assets/images/mac-okta-fastpass-add-mobile1.png" image_path="/assets/images/mac-okta-fastpass-add-mobile1.png" %}
{% include figure url="/assets/images/mac-okta-fastpass-add-mobile2.5.png" image_path="/assets/images/mac-okta-fastpass-add-mobile2.5.png" %}
{% include figure url="/assets/images/mac-okta-fastpass-add-mobile2.png" image_path="/assets/images/mac-okta-fastpass-add-mobile2.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">7</span></div>
        <div>
          <strong>Confirm the PIN</strong>
          <p>You may be asked to enter a PIN shown on your Mac into the Okta Verify app on your phone.</p>
        </div>
      </div>

{% include figure url="/assets/images/mac-okta-fastpass-add-mobile3.png" image_path="/assets/images/mac-okta-fastpass-add-mobile3.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">8</span></div>
        <div>
          <strong>Enable Touch ID</strong>
          <p>When prompted, click <strong>Enable Touch ID</strong> and authenticate with your fingerprint. Touch ID is the preferred method for Okta FastPass — if you skip it, you'll be prompted for your password each time instead.</p>
        </div>
      </div>

{% include figure url="/assets/images/okta-fp-touchid-1.png" image_path="/assets/images/okta-fp-touchid-1.png" %}
{% include figure url="/assets/images/enable-touch-id.png" image_path="/assets/images/enable-touch-id.png" %}

    </div>
  </div>

  <div class="welcome-section">
    <h2>Sign into Chrome</h2>
    <div class="welcome-checklist">

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">9</span></div>
        <div>
          <strong>Open Chrome and click Sign In</strong>
          <p>Launch <strong>Google Chrome</strong> and click the <strong>Sign In</strong> button.</p>
        </div>
      </div>

{% include figure url="/assets/images/chrome-signin.png" image_path="/assets/images/chrome-signin.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">10</span></div>
        <div>
          <strong>Enter your Block email</strong>
          <p>Type your full <strong>@squareup.com</strong> or <strong>@block.xyz</strong> email address, then select <strong>Use Okta FastPass</strong> when prompted. Verify with Touch ID or your password.</p>
        </div>
      </div>

{% include figure url="/assets/images/GWorkspace-Okta.png" image_path="/assets/images/GWorkspace-Okta.png" %}
{% include figure url="/assets/images/mac-chrome-15.png" image_path="/assets/images/mac-chrome-15.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">11</span></div>
        <div>
          <strong>Finish signing in</strong>
          <p>Chrome will reopen. Click <strong>Continue as [your name]</strong> and proceed through the prompts. If asked to keep browsing data separate, choose <strong>No, continue to work in this profile</strong>. On the "Turn on sync" screen, click <strong>Yes, I'm In</strong>.</p>
        </div>
      </div>

{% include figure url="/assets/images/mac-chrome-16.png" image_path="/assets/images/mac-chrome-16.png" %}
{% include figure url="/assets/images/mac-chrome-continue1" image_path="/assets/images/mac-chrome-continue1" %}
{% include figure url="/assets/images/mac-chrome-continue2" image_path="/assets/images/mac-chrome-continue2" %}
{% include figure url="/assets/images/mac-chrome-continue3" image_path="/assets/images/mac-chrome-continue3" %}
{% include figure url="/assets/images/mac-chrome-18.png" image_path="/assets/images/mac-chrome-18.png" %}

      <div class="checklist-item" style="background: #e8f5e9; border-color: #c8e6c9;">
        <div class="checklist-icon" style="background: #fff; border-color: #c8e6c9; color: #00a828;"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></div>
        <div>
          <strong>Chrome is ready!</strong>
          <p>You're signed in and your Chrome extensions (like Go Links) should be syncing automatically.</p>
        </div>
      </div>

{% include figure url="/assets/images/mac-chrome-20.png" image_path="/assets/images/mac-chrome-20.png" %}

    </div>
  </div>

  <div class="welcome-next">
    <a href="/mac-vpn" class="landing-card-btn welcome-next-btn">
      Next: VPN &rarr;
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
