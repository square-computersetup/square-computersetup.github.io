---
title: "Account Setup"
permalink: /mac-setup/
author_profile: false
sidebar:
  nav: "nav-mac"
header:
  overlay_color: "#000"
---

<div class="welcome-page">

  <div class="welcome-section">
    <h2>Sign in with Okta</h2>
    <div class="welcome-checklist">

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">1</span></div>
        <div>
          <strong>Enter your credentials</strong>
          <p>After clicking Enroll on the Remote Management screen, the Okta login screen will appear. Enter your <strong>username</strong> and <strong>password</strong>, then click <strong>Sign in</strong>.</p>
        </div>
      </div>

      <div class="notice--warning" style="display:flex; gap:1em; align-items:flex-start;">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" style="width:24px; min-width:24px; height:24px; margin-top:0.1em;"><path d="M10.29 3.86L1.82 18a2 2 0 0 0 1.71 3h16.94a2 2 0 0 0 1.71-3L13.71 3.86a2 2 0 0 0-3.42 0z"/><line x1="12" y1="9" x2="12" y2="13"/><line x1="12" y1="17" x2="12.01" y2="17"/></svg>
        <div>
          <strong>Do not select "Sign in with FastPass"</strong><br/>
          FastPass is not available yet and will be set up at a later stage.
        </div>
      </div>

{% include figure url="/assets/images/okta-login-mac1.png" image_path="/assets/images/okta-login-mac1.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">2</span></div>
        <div>
          <strong>Verify with Okta Verify</strong>
          <p>Since you already set up Okta Verify on your phone, use it to authenticate. Choose the matching number on your mobile device that corresponds to the one on your laptop screen.</p>
        </div>
      </div>

{% include figure url="/assets/images/okta-login-mac2.png" image_path="/assets/images/okta-login-mac2.png" %}
{% include figure url="/assets/images/okta-login-mac3.png" image_path="/assets/images/okta-login-mac3.png" %}

    </div>
  </div>

  <div class="welcome-section">
    <h2>Create your Mac account</h2>
    <div class="welcome-checklist">

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">3</span></div>
        <div>
          <strong>Verify your account name</strong>
          <p>After authentication, Remote Management will initialize. You'll then see a prompt to create a computer account. Your <strong>Full Name</strong> and <strong>Account Name</strong> will be pre-filled.</p>
        </div>
      </div>

      <div class="notice--danger" style="display:flex; gap:1em; align-items:flex-start;">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" style="width:24px; min-width:24px; height:24px; margin-top:0.1em;"><circle cx="12" cy="12" r="10"/><line x1="12" y1="8" x2="12" y2="12"/><line x1="12" y1="16" x2="12.01" y2="16"/></svg>
        <div>
          <strong>Your Account Name must match your Block username</strong><br/>
          This is required for proper configuration. Do not change the pre-filled Account Name.
        </div>
      </div>

{% include figure url="/assets/images/mac-account-new.png" image_path="/assets/images/mac-account-new.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">4</span></div>
        <div>
          <strong>Set your Mac password</strong>
          <p>Choose a strong password to unlock your MacBook. We recommend using the same password as your Okta account, but you can choose a different one. We'll refer to this as your <strong>Mac/Laptop Password</strong> going forward.</p>
        </div>
      </div>

      <div class="notice--warning" style="display:flex; gap:1em; align-items:flex-start;">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" style="width:24px; min-width:24px; height:24px; margin-top:0.1em;"><path d="M10.29 3.86L1.82 18a2 2 0 0 0 1.71 3h16.94a2 2 0 0 0 1.71-3L13.71 3.86a2 2 0 0 0-3.42 0z"/><line x1="12" y1="9" x2="12" y2="13"/><line x1="12" y1="17" x2="12.01" y2="17"/></svg>
        <div>
          <strong>Remember your password</strong><br/>
          Don't rely on the password hint — it isn't shown on the login screen.
        </div>
      </div>

    </div>
  </div>

  <div class="welcome-section">
    <h2>Finishing touches</h2>
    <div class="welcome-checklist">

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">5</span></div>
        <div>
          <strong>Enable Location Services</strong>
          <p>We strongly recommend enabling Location Services, as some Block applications require accurate time settings to function properly.</p>
        </div>
      </div>

{% include figure url="/assets/images/location-services-mac.png" image_path="/assets/images/location-services-mac.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">6</span></div>
        <div>
          <strong>Set up Touch ID</strong>
          <p>This is optional but recommended for a faster daily login experience. You'll still be asked for your Mac password periodically, even with Touch ID enabled.</p>
        </div>
      </div>

{% include figure url="/assets/images/mac-touchid-new.png" image_path="/assets/images/mac-touchid-new.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">7</span></div>
        <div>
          <strong>Choose your theme</strong>
          <p>Pick Light or Dark mode. You can always change this later in System Settings.</p>
        </div>
      </div>

{% include figure url="/assets/images/mac-lightdark.png" image_path="/assets/images/mac-lightdark.png" %}

      <div class="checklist-item" style="background: #e8f5e9; border-color: #c8e6c9;">
        <div class="checklist-icon" style="background: #fff; border-color: #c8e6c9; color: #00a828;"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></div>
        <div>
          <strong>Welcome to your Mac!</strong>
          <p>After clicking through any remaining screens, you'll arrive at the macOS desktop. Next we'll install the software you need.</p>
        </div>
      </div>

{% include figure url="/assets/images/sonoma-homescreen.png" image_path="/assets/images/sonoma-homescreen.png" %}

    </div>
  </div>

  <div class="welcome-next">
    <a href="/mac-installs" class="landing-card-btn welcome-next-btn">
      Next: Software Installation &rarr;
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
