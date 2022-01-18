<a name="duo"></a>
## Single Sign-On (SSO)

Single Sign-On (SSO) is a system that allows you to use just one company-wide password to access many different resources. Think of it as your Block Passport that you show at different airports. We use Cisco's Duo identify provider for SSO, so we need to set that up first.

## Duo Enrollment

Let's start with a brief 97 second video overview:

{% include video id="22HGUqMMySc" provider="youtube" %}

<a name="login"></a>
{% include figure url="/assets/images/duo-login2.jpg" image_path="/assets/images/duo-login2.jpg" caption="(this is the Duo Single Sign-On service you will encounter daily)" %}

Enter just your username (**without the** @squareup.com) and your __temporary__ password and click [Login](#setup1){: .btn .btn--inverse .btn--small}

<a name="setup1"></a>
{% include figure url="/assets/images/duo-setup1.jpg" image_path="/assets/images/duo-setup1.jpg" caption="(if you do not see these options, ask for [help](/help))" %}

Click [Start Setup](#setup2){: .btn .btn--inverse .btn--small}

<a name="setup2"></a>
{% include figure url="/assets/images/duo-setup2.jpg" image_path="/assets/images/duo-setup2.jpg" %}

Choose **Mobile phone** and click [Continue](#setup3){: .btn .btn--inverse .btn--small}

<a name="setup3"></a>
{% include figure url="/assets/images/duo-setup3.jpg" image_path="/assets/images/duo-setup3.jpg" %}

Enter your **phone number** and click [Continue](#setup4){: .btn .btn--inverse .btn--small}

<a name="setup4"></a>
{% include figure url="/assets/images/duo-setup4.jpg" image_path="/assets/images/duo-setup4.jpg" %}

Choose your phone type and click [Continue](#setup5){: .btn .btn--inverse .btn--small}

<a name="setup5"></a>
{% include figure url="/assets/images/duo-setup5.jpg" image_path="/assets/images/duo-setup5.jpg" %}

Install the __Duo Mobile__ app from the [Apple App Store](https://apps.apple.com/us/app/duo-mobile/id422663827){:target="_blank"} or [Google Play Store](https://play.google.com/store/apps/details?id=com.duosecurity.duomobile){:target="_blank"}.

Then, click [I have Duo Mobile installed](#setup6){: .btn .btn--inverse .btn--small}

<a name="setup6"></a>
{% include figure url="/assets/images/duo-setup6.jpg" image_path="/assets/images/duo-setup6.jpg" %}

Open the __Duo Mobile__ app on your phone, tap the __+__, and aim your phone at the QR code. 

Once the code is scanned, you may click [Continue](#setup7){: .btn .btn--inverse .btn--small}

<a name="setup7"></a>
{% include figure url="/assets/images/duo-setup7.jpg" image_path="/assets/images/duo-setup7.jpg" %}

Click [Continue to Login](#setup8){: .btn .btn--inverse .btn--small}

<a name="setup8"></a>
{% include figure url="/assets/images/duo-setup8.jpg" image_path="/assets/images/duo-setup8.jpg" %}

Click [Send Me a Push](#push){: .btn .btn--inverse .btn--small}

<a name="push"></a>
{% include figure url="/assets/images/duo-push.jpg" image_path="/assets/images/duo-push.jpg" %}

On your mobile device, tap [Approve](#approve){: .btn .btn--inverse .btn--small} when prompted, as shown below:

<a name="approve"></a>
{% include figure url="https://guide.duo.com/static/images/en/android-push-full_2x.png" image_path="https://guide.duo.com/static/images/en/android-push-full_2x.png" %}

{% if include.os == "alt" %}
If everything worked, you should see your Gmail inbox. You may already have a number of emails waiting for you!
{% endif %}

If something didn't work, please ask for [help](/help). 

[Next Step &rarr;](/{{ include.os }}-{{ include.next }}){: .btn .btn--success .btn--large}

