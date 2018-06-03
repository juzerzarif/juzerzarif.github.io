---
title: Contact
order: 4
icon: fa-envelope
cover-photo: /images/contact-bg.jpg
cover-photo-alt: background-image
---

<form method="post" action="https://formspree.io/{{ site.email }}">
  <div class="row">
    <div class="12u 12u$(mobile)" style="margin-bottom:10px"><input type="text" name="name" placeholder="Name" /></div>
    <div class="12u 12u$(mobile)" style="margin-bottom:10px"><input type="text" name="email" placeholder="Email" /></div>
    <div class="12u$" style="margin-bottom:10px">
      <textarea name="message" placeholder="Message"></textarea>
    </div>
    <div class="12u$">
      <input type="submit" value="Send" />
    </div>
  </div>
</form>