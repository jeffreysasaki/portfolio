---
title: "Contact Me"
---
<form id="contact" name="contact" method="POST" data-netlify-recaptcha="true" data-netlify="true">
  <p>
    <label>Name:</label>
    <input type="text" name="name" />
  </p>
  <p>
    <label>Email:</label>
    <input type="email" name="email" />
  </p>
  <p>
    <label>Message:</label>
    <textarea rows="4" name="message"></textarea>
  </p>
  <p>
    <div data-netlify-recaptcha="true"></div>
    <button type="submit">Send</button>
  </p>
</form>