<a name="Okta"></a>
## Single Sign-On (SSO)

Single Sign-On (SSO) is a system that allows you to use just one company-wide password to access many different resources. Think of it as your Block Passport that you show at different airports. We use Okta for SSO, so we need to set that up first.

## Okta Enrollment


<a name="login"></a>
{% include figure url="/assets/images/duo-login2.jpg" image_path="/assets/images/duo-login2.jpg" caption="(this is the Okta Single Sign-On service you will encounter daily)" %}


Enter just your username (**without the** @squareup.com) and your password, then click [Login](#setup1){: .btn .btn--inverse .btn--small}.

<a name="setup1"></a>
{% include figure url="/assets/images/duo-setup1.jpg" image_path="/assets/images/duo-setup1.jpg" caption="(if you do not see these options, ask for [help](/help))" %}

Click [Set up](#setup2){: .btn .btn--inverse .btn--small}



Install the __Okta Verify__ app from the [Apple App Store](https://apps.apple.com/us/app/okta-verify/id490179405){:target="_blank"} or [Google Play Store](https://play.google.com/store/apps/details?id=com.okta.android.auth&hl=en_US&gl=US&pli=1){:target="_blank"}.



Open the __Okta Verify__ app on your phone and follow these instructions to add your account. 
Select Get Started

Select Add Account

Choose __Organization__ as the "Account Type"

Select __Yes, Ready to Scan__ and allow Okta Verify to access the camera on your mobile device.

Scan the QR code on your computer with your mobile device, and allow push notifications when prompted

{% if include.os == "alt" %}
If everything worked, you should see your Gmail inbox. You may already have a number of emails waiting for you!
{% endif %}

If something didn't work, please ask for [help](/help). 

[Next Step &rarr;](/alt-chrome/){: .btn .btn--success .btn--large}

