---
layout: page
title: Contact Me
permalink: /contact/
feature-img: "img/sample_feature_img.png"
---
If you'd like to get in touch with me, please do so using the form below!

<form action="https://getsimpleform.com/messages?form_api_token=50e870271c4a9f00a6d69e43a0d22e2a" method="post">
  <!-- the redirect_to is optional, the form will redirect to the referrer on submission -->
  <input type='hidden' name='redirect_to' value='{{ "/thank-you/" | absolute_url }}' />
  <input type='text' name='name' placeholder='Your full name' style="padding: 5px;"/>
  <input type='email' name='email' placeholder='Your e-mail address' style="padding: 5px;"/>
  <textarea name='message' placeholder='Your message ...' style="display: block; width: 100%; height: 130px; margin: 10px 0; padding: 5px;"></textarea>
  <input type='submit' value='Send Message' style="padding: 5px;"/>
</form>
