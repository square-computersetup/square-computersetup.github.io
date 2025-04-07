---
title: "Mac Chrome"
permalink: /mac-chrome/
author_profile: true
sidebar:
  nav: "nav-mac"
header:
  overlay_color: "#333"
---
# Google Chrome

## Setting Up Google Chrome as your Default Browser
Before we move forward, it's critical to set Google Chrome as your Default Browser.
* Open System Settings. 
* In the search bar, type “Default web browser” and select the option that appears.

{% include figure url="/assets/images/mac-chrome-01.png" image_path="/assets/images/mac-chrome-01.png" %}

* Scroll down to the Default web browser section and select Google Chrome to make it your default browser.

{% include figure url="/assets/images/mac-chrome-02.png" image_path="/assets/images/mac-chrome-02.png" %}

## Setting up Okta Fastpass to work with Google Chrome

__Note:__ If you don’t see the Okta Verify app on your computer, please don't install it from the App store. Ensure that you have completed all updates from the [Managed Software Center &rarr;](/mac-installs.md). If the Managed Software Center is not on your computer, please follow this [link &rarr;](/mac-mdm.md) to manually install it. It is critical for Okta Verify to be installed by the Managed Software Center.  

{% include mac-okta-fastpass.md %}

## Signing into Google Chrome
* Open Google Chrome
* Click the profile icon in the top right corner
* Click “Turn on sync…”

{% include figure url="/assets/images/mac-chrome-13.png" image_path="/assets/images/mac-chrome-13.png" %}

* Select “Use Okta Fastpass”

{% include figure url="/assets/images/mac-chrome-14.png" image_path="/assets/images/mac-chrome-14.png" %}

* An Okta Verify screen will appear. Use your Touch ID or password to verify your identity.

{% include figure url="/assets/images/mac-chrome-15.png" image_path="/assets/images/mac-chrome-15.png" %}

* Once verified, Google Chrome will reopen. Click “Continue” on the Identity Verification screen.

{% include figure url="/assets/images/mac-chrome-16.png" image_path="/assets/images/mac-chrome-16.png" %}

* Click “Continue” on the “Your organization will manage this profile” screen.

{% include figure url="/assets/images/mac-chrome-17.png" image_path="/assets/images/mac-chrome-17.png" %}

* Click “Yes, I’m In” on the “Turn on sync” screen.

{% include figure url="/assets/images/mac-chrome-18.png" image_path="/assets/images/mac-chrome-18.png" %}

* After signing in, you will see your Chrome extensions installed, such as the Square Go Links extension.

{% include figure url="/assets/images/mac-chrome-20.png" image_path="/assets/images/mac-chrome-20.png" %}

[Next Step &rarr;](/mac-go/){: .btn .btn--success .btn--large}
