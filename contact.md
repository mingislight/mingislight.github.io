---
layout: default
title: "Contact"
permalink: /contact/
---

## Contact

Use the form. I will reply as soon as I can.

<form action="https://formspree.io/f/your_form_id" method="POST">
  <label>Your name
    <input type="text" name="name" required>
  </label><br>
  <label>Your email
    <input type="email" name="email" required>
  </label><br>
  <label>Message
    <textarea name="message" rows="6" required></textarea>
  </label><br>
  <!-- Honeypot -->
  <input type="text" name="_gotcha" style="display:none">
  <button type="submit">Send</button>
</form>
