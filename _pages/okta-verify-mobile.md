---
permalink: /okta-verify-mobile/
title: "Okta Verify Mobile Setup"
layout: single
author_profile: false
classes: wide
header:
  overlay_color: "#000"
---

<div class="welcome-page">

  <div class="notice--warning" style="display:flex; gap:1em; align-items:flex-start; margin-bottom:2em;">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" style="width:24px; min-width:24px; height:24px; margin-top:0.1em;"><path d="M10.29 3.86L1.82 18a2 2 0 0 0 1.71 3h16.94a2 2 0 0 0 1.71-3L13.71 3.86a2 2 0 0 0-3.42 0z"/><line x1="12" y1="9" x2="12" y2="13"/><line x1="12" y1="17" x2="12.01" y2="17"/></svg>
    <div>
      <strong>Disconnect any VPN before continuing</strong><br/>
      If you have a VPN running on your device or network, turn it off now. Active VPN connections will prevent your device from reaching Block's sign-in domain.
    </div>
  </div>

  <div class="welcome-section">
    <h2>Step by step</h2>
    <div class="welcome-checklist">

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">1</span></div>
        <div>
          <strong>Tap the + icon</strong>
          <p>Open the Okta Verify app and tap the plus symbol near the top of the screen to add a new account.</p>
        </div>
      </div>

{% include figure url="/assets/images/ovm-1.png" image_path="/assets/images/ovm-1.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">2</span></div>
        <div>
          <strong>Select Organization</strong>
          <p>Choose the <strong>Organization</strong> account type.</p>
        </div>
      </div>

{% include figure url="/assets/images/ovm-2.png" image_path="/assets/images/ovm-2.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">3</span></div>
        <div>
          <strong>Skip the QR code step</strong>
          <p>Select <strong>No, Sign In Instead</strong>. A QR code cannot be used for this setup.</p>
        </div>
      </div>

{% include figure url="/assets/images/ovm-3.png" image_path="/assets/images/ovm-3.png" %}
{% include figure url="/assets/images/ovm-4.png" image_path="/assets/images/ovm-4.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">4</span></div>
        <div>
          <strong>Enter your sign-in URL</strong>
          <p>Type <code>login.block.xyz</code> as your organization's sign-in URL.</p>
        </div>
      </div>

{% include figure url="/assets/images/ovm-5.png" image_path="/assets/images/ovm-5.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">5</span></div>
        <div>
          <strong>Sign in with your Block credentials</strong>
          <p>Enter your Block username (e.g. <code>jsmith</code>) and your Okta password.</p>
        </div>
      </div>

{% include figure url="/assets/images/okta-mobile-username.jpg" image_path="/assets/images/okta-mobile-username.jpg" %}
{% include figure url="/assets/images/okta-mobile-password.jpg" image_path="/assets/images/okta-mobile-password.jpg" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">6</span></div>
        <div>
          <strong>Enable biometrics</strong>
          <p>If your device supports Face ID or fingerprint authentication, enable it when prompted.</p>
        </div>
      </div>

{% include figure url="/assets/images/ovm-8.png" image_path="/assets/images/ovm-8.png" %}

      <div class="checklist-item" style="background: #e8f5e9; border-color: #c8e6c9;">
        <div class="checklist-icon" style="background: #fff; border-color: #c8e6c9; color: #00a828;"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></div>
        <div>
          <strong>You're all set!</strong>
          <p>Okta Verify is configured. Now let's set up your new computer.</p>
        </div>
      </div>

{% include figure url="/assets/images/ovm-9.png" image_path="/assets/images/ovm-9.png" %}

    </div>
  </div>

  <div class="welcome-next">
    <a href="/os" class="landing-card-btn welcome-next-btn">
      Next: Select your device &rarr;
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
