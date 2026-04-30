---
title: "Software Installation"
permalink: /mac-installs/
author_profile: false
sidebar:
  nav: "nav-mac"
header:
  overlay_color: "#000"
---

<div class="welcome-page">

  <div class="notice--info" style="display:flex; gap:1em; align-items:flex-start; margin-bottom:2em;">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" style="width:24px; min-width:24px; height:24px; margin-top:0.1em;"><circle cx="12" cy="12" r="10"/><line x1="12" y1="16" x2="12" y2="12"/><line x1="12" y1="8" x2="12.01" y2="8"/></svg>
    <div>
      <strong>Safari opened by itself?</strong><br/>
      During installation, Cloudflare WARP may open Safari with a connection error. This is normal — <strong>close or ignore Safari</strong> and do not follow any prompts in the browser. The setup will continue on its own.
    </div>
  </div>

{% include figure url="/assets/images/cloudflare-error.png" image_path="assets/images/cloudflare-error.png" %}

  <div class="welcome-section">
    <h2>Managed Software Center</h2>
    <div class="welcome-checklist">

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">1</span></div>
        <div>
          <strong>Wait for Managed Software Center to open</strong>
          <p>It should launch automatically after you've signed in and completed the previous steps.</p>
        </div>
      </div>

{% include figure url="/assets/images/msc.png" image_path="assets/images/msc.png" %}

      <div class="notice--warning" style="display:flex; gap:1em; align-items:flex-start;">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" style="width:24px; min-width:24px; height:24px; margin-top:0.1em;"><path d="M10.29 3.86L1.82 18a2 2 0 0 0 1.71 3h16.94a2 2 0 0 0 1.71-3L13.71 3.86a2 2 0 0 0-3.42 0z"/><line x1="12" y1="9" x2="12" y2="13"/><line x1="12" y1="17" x2="12.01" y2="17"/></svg>
        <div>
          <strong>Didn't open automatically?</strong><br/>
          Look for the Managed Software Center icon in the toolbar. If you don't see it, open Launchpad and click <strong>Managed Software Center</strong> to launch it manually.
        </div>
      </div>

{% include figure url="/assets/images/Launchpad Toolbar.png" image_path="assets/images/Launchpad Toolbar.png" %}
{% include figure url="/assets/images/MSC Launchpad.png" image_path="assets/images/MSC Launchpad.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">2</span></div>
        <div>
          <strong>Log out for mandatory installs</strong>
          <p>Once the updates finish, you'll be prompted about a <strong>Forced logout for mandatory install</strong>. Click <strong>Log out and Update Now</strong> to let the installer restart your laptop.</p>
        </div>
      </div>

{% include figure url="/assets/images/mac-installs-forced.png" image_path="/assets/images/mac-installs-forced.png" %}
{% include figure url="/assets/images/mac-installs-logout.png" image_path="/assets/images/mac-installs-logout.png" %}

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">3</span></div>
        <div>
          <strong>Log back in and verify</strong>
          <p>Wait for any visual update activity to finish, then log in again using your <strong>Mac/Laptop Password</strong>. Open Managed Software Center and click <strong>Check again</strong> to confirm all updates are complete.</p>
        </div>
      </div>

      <div class="checklist-item" style="background: #e8f5e9; border-color: #c8e6c9;">
        <div class="checklist-icon" style="background: #fff; border-color: #c8e6c9; color: #00a828;"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></div>
        <div>
          <strong>Software installation complete!</strong>
          <p>Managed Software Center is up to date. Let's continue setting up your apps.</p>
        </div>
      </div>

    </div>
  </div>

  <div class="welcome-next">
    <a href="/mac-chrome" class="landing-card-btn welcome-next-btn">
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
