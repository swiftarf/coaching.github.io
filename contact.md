---
layout: page
title: Contact
subtitle: Book a free discovery call
permalink: /contact/
---
Fill in the form and your message will be emailed to {{ site.contact_email }}.

<form class="contact-form" action="https://formspree.io/{{ site.contact_email }}" method="POST">
  <input type="hidden" name="_subject" value="New enquiry from {{ site.title }}">
  <input type="hidden" name="_next" value="{{ '/thanks/' | absolute_url }}">
  <input type="text" name="_gotcha" class="hidden" tabindex="-1" autocomplete="off">
  <label for="name">Name</label>
  <input id="name" type="text" name="name" required>
  <label for="email">Email</label>
  <input id="email" type="email" name="_replyto" required>
  <label for="message">Message</label>
  <textarea id="message" name="message" rows="6" required></textarea>
  <p><button class="btn primary" type="submit">Send message</button></p>
</form>
