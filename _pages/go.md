---
title: "Go Links"
permalink: /go/
author_profile: true
sidebar:
  nav: "nav-shared"
---

Square has a handy shared bookmark system that makes use of __go/example__ links (swap in different bookmark names in place of "example"). There are a number of very helpful __go/__ links that you will use often. First, we need to do a one-time setup. Start the __Chrome__ web browser (usually located in the system tray at the bottom). 

{% include figure url="/assets/images/go-links.jpg" image_path="/assets/images/go-links.jpg" %}

In the address bar at the top, type in __go/go__ but do __NOT__ press enter on your keyboard. You'll notice that you have two auto-complete suggestions from the web browser. Using the cursor, click on the option that does __NOT__ say "Google Search". In the future, __go/example__ links will use the bookmark service.

__NOTE:__ You may be prompted to authenticate to Duo SSO again. You may check the box that says __Remember me for 12 hours__ to avoid authenticating more than once daily.
{: .notice--warning}

{% include figure url="/assets/images/go-go.jpg" image_path="/assets/images/go-go.jpg" %}

If things worked properly, you should see our internal __Wiki__ site (our intranet). This is a great resource for all Squares, but especially for new Squares. If instead you landed at the Google search results for the popular all-female rock band [The Go-Go's](https://en.wikipedia.org/wiki/The_Go-Go%27s) something went wrong. 

Square runs a __Device Attestation Service__ (DAS) that asks your device to present a certificate (like a passport when you enter a country) proving it is an authorized and Square-owned device. Next, try accessing the restricted __go/it__ link. 

{% include figure url="/assets/images/go-it.jpg" image_path="/assets/images/go-it.jpg" %}

If your device's certificate is properly issued and valid, you should see the __IT Help Center__ shown above. This is where you would submit any help requests (called "tickets") should you have issues in the future. If everything seems to be working, [skip to the bottom](#done) of this page.

{% include figure url="/assets/images/das-trouble.jpg" image_path="/assets/images/das-trouble.jpg" %}

If you see __We're having trouble identifying your device__, it means your device did not present a valid certificate (passport). Let's do some [DAS identity](/das-trouble/) troubleshooting before we continue.

{% include figure url="/assets/images/das-update.jpg" image_path="/assets/images/das-update.jpg" %}

If you see __Looks like your device needs some maintenance__, it means your device has a valid certificate (passport), but [needs updates](/das-update/).



<a name="done"></a>
Fantastic! Now that you have __go/__ links working, keep an eye out for a list of handy __go/__ links at the end of this setup guide.

[Next Step &rarr;](/slack){: .btn .btn--success .btn--large}
