---
title: "Contact Me"
slug: "contact"
---
<form id="contact" name="contact" method="POST" data-netlify-recaptcha="true" data-netlify="true">
  <p>
    <label>Name:</label>
    <input type="text" name="name" required/>
  </p>
  <p>
    <label>Email:</label>
    <input type="email" name="email" required/>
  </p>
  <p>
    <label>Message:</label>
    <textarea rows="4" name="message" required></textarea>
  </p>
  <p>
    <div class="g-recaptcha" data-sitekey="6Lf7hc4ZAAAAAMxUugUmTgi-CoRz7rMebzYO3S1c"></div>
    <button type="submit">Send</button>
  </p>
</form>