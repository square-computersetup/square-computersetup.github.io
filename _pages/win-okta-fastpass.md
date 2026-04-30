---
title: "Okta FastPass"
permalink: /win-okta-fastpass/
author_profile: false
sidebar:
  nav: "nav-win"
header:
  overlay_color: "#000"
---

<div class="welcome-container" markdown="0">

  <h1 class="welcome-title">Okta FastPass</h1>
  <p class="welcome-subtitle">Set up Okta FastPass for quick, secure, phishing-resistant sign-in.</p>

  <div class="notice--info" style="display:flex; gap:1em; align-items:flex-start;">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" style="width:24px; min-width:24px; height:24px; margin-top:0.1em;"><circle cx="12" cy="12" r="10"/><line x1="12" y1="16" x2="12" y2="12"/><line x1="12" y1="8" x2="12.01" y2="8"/></svg>
    <div>
      <strong>Bluetooth required</strong><br/>
      Make sure Bluetooth is enabled on <strong>both</strong> your Windows laptop and your mobile device before starting. On Windows, click the <strong>Control Center</strong> icon in the bottom-right corner of the taskbar to check.
    </div>
  </div>

  <div class="welcome-section">
    <h2>Set up Okta FastPass</h2>
    <div class="welcome-checklist">

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">1</span></div>
        <div>
          <strong>Open Okta Verify on your computer</strong>
          <p>Click the <strong>Start menu</strong>, search for <strong>Okta Verify</strong>, and open the app.</p>
        </div>
      </div>

{% include figure url="/assets/images/ofp-win3.png" image_path="/assets/images/ofp-win3.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">2</span></div>
        <div>
          <strong>Select "Add account from another device"</strong>
          <p>On the Okta Verify welcome screen, select <strong>Add account from another device</strong>.</p>
        </div>
      </div>

{% include figure url="/assets/images/ofp-win4.png" image_path="/assets/images/ofp-win4.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">3</span></div>
        <div>
          <strong>Open Okta Verify on your mobile device</strong>
          <p>On your phone, open <strong>Okta Verify</strong>, select your Block account (e.g. jsmith@block.xyz), then scroll down and tap <strong>Add Account to Another Device</strong>.</p>
        </div>
      </div>

{% include figure url="/assets/images/ofp-win5.png" image_path="/assets/images/ofp-win5.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">4</span></div>
        <div>
          <strong>Enter the pairing code</strong>
          <p>Your phone will display a QR code with an <strong>8-character code</strong> below it. Enter this code into the "Enter code" field in Okta Verify on your computer.</p>
        </div>
      </div>

{% include figure url="/assets/images/ofp-win6.png" image_path="/assets/images/ofp-win6.png" %}
{% include figure url="/assets/images/ofp-win7.png" image_path="/assets/images/ofp-win7.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">5</span></div>
        <div>
          <strong>Confirm the PIN on your phone</strong>
          <p>A PIN may appear on your laptop screen. If prompted, enter this PIN into Okta Verify on your mobile device to confirm the pairing.</p>
        </div>
      </div>

{% include figure url="/assets/images/ofp-win8.png" image_path="/assets/images/ofp-win8.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">6</span></div>
        <div>
          <strong>Authenticate with Windows Hello</strong>
          <p>If prompted, verify your identity using <strong>Windows Hello</strong> (fingerprint, facial recognition, or your PIN).</p>
        </div>
      </div>

{% include figure url="/assets/images/ofp-win9.png" image_path="/assets/images/ofp-win9.png" %}
{% include figure url="/assets/images/ofp-win10.png" image_path="/assets/images/ofp-win10.png" %}

      <div class="notice--info" style="display:flex; gap:1em; align-items:flex-start;">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" style="width:24px; min-width:24px; height:24px; margin-top:0.1em;"><circle cx="12" cy="12" r="10"/><line x1="12" y1="16" x2="12" y2="12"/><line x1="12" y1="8" x2="12.01" y2="8"/></svg>
        <div>
          <strong>Biometrics recommended</strong><br/>
          Windows Hello biometrics (fingerprint or facial recognition) are preferred for Okta FastPass. If you don't enable biometrics, you'll be prompted for your password each time you use FastPass.
        </div>
      </div>

      <div class="checklist-item" style="background: #e8f5e9; border-color: #c8e6c9;">
        <div class="checklist-icon" style="background: #fff; border-color: #c8e6c9; color: #00a828;"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></div>
        <div>
          <strong>Okta FastPass is set up!</strong>
          <p>You can now sign in quickly and securely across Block apps.</p>
        </div>
      </div>

    </div>
  </div>

  <div class="welcome-next">
    <a href="/win-chrome" class="landing-card-btn welcome-next-btn">
      Next: Chrome Setup &rarr;
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
