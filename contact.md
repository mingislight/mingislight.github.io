---
layout: default
title: "Contact"
permalink: /contact/
---

<div class="contact-wrap">
  <h1>Contact</h1>
  <p class="contact-intro">Use the form and I’ll reply as soon as I can.</p>

  <form
    class="contact-form"
    action="https://formspree.io/f/mzzvydye"
    method="POST"
  >
    <label>
      Your name
      <input type="text" name="name" autocomplete="name" required />
    </label>

    <label>
      Your email
      <input type="email" name="email" autocomplete="email" required />
    </label>

    <label>
      Message
      <textarea name="message" rows="6" required></textarea>
    </label>

    <input type="hidden" name="_subject" value="New message from mingislight.com" />
    <input type="hidden" name="_redirect" value="https://mingislight.com/thanks/" />
    <input type="text" name="_gotcha" style="display:none" tabindex="-1" autocomplete="off" />

    <button type="submit">Send</button>
  </form>
</div>
