---
layout: page
title: "Contact:"
permalink: /contact/
banner: /assets/images/background.jpg

---

<div style ="text-align:center">
<h1>About me:</h1>
<p>Currently I'm a student of the master M2<a href="https://www.master-mva.com/"> MVA;</a><br>
I'm picking courses in a large range of subjects but I'm much more familiar with topics as generatives models as GAN's and Techniques to solve Inverse Problems;</p>

</div>

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
