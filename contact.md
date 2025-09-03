---
layout: page
title: "Contact"
permalink: /contact/
---

<div style="text-align:center">
  <h1>Social media and personal email:</h1>
  <div class="contact-icons">
    {% for social in site.data.navigator.social %}
      <a href="{{ social.url }}" target="_blank" title="{{ social.title }}">
        <i class="{{ social.icon }}"></i>
      </a>
    {% endfor %}
  </div>
</div>
