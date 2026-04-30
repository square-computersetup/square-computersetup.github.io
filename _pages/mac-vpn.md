---
title: "VPN"
permalink: /mac-vpn/
author_profile: false
sidebar:
  nav: "nav-mac"
header:
  overlay_color: "#000"
---

<div class="welcome-page">

  <div class="welcome-section">
    <h2>Connect to WARP</h2>
    <div class="welcome-checklist">

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">1</span></div>
        <div>
          <strong>Open Cloudflare WARP</strong>
          <p>Click the <strong>Cloudflare WARP</strong> icon near the clock in the top-right corner of your screen.</p>
        </div>
      </div>

      <div class="checklist-item">
        <div class="checklist-icon"><span style="font-weight:700; font-size:1rem;">2</span></div>
        <div>
          <strong>Authenticate with Okta</strong>
          <p>You'll be prompted to sign in via Okta the first time. After that, WARP will ask you to re-authenticate once daily.</p>
        </div>
      </div>

{% include figure url="assets/images/warp-02.png" image_path="assets/images/warp-02.png" %}

      <div class="checklist-item" style="background: #e8f5e9; border-color: #c8e6c9;">
        <div class="checklist-icon" style="background: #fff; border-color: #c8e6c9; color: #00a828;"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg></div>
        <div>
          <strong>You're connected!</strong>
          <p>As long as it says <strong>Connected</strong>, you're all set. WARP runs continuously in the background — no need to reconnect manually.</p>
        </div>
      </div>

{% include figure url="assets/images/warp-01.png" image_path="assets/images/warp-01.png" %}

    </div>
  </div>

  <div class="welcome-next">
    <a href="/mac-slack" class="landing-card-btn welcome-next-btn">
      Next: Slack &rarr;
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
