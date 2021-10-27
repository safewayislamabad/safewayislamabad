---
layout: default
title: "Find Us"
permalink: /fins-us/
---


<!doctype html>
<!--
  Minimal Mistakes Jekyll Theme 4.24.0 by Michael Rose
  Copyright 2013-2020 Michael Rose - mademistakes.com | @mmistakes
  Free for personal and commercial use under the MIT license
  https://github.com/mmistakes/minimal-mistakes/blob/master/LICENSE
-->
<html lang="{{ site.locale | slice: 0,2 | default: "en" }}" class="no-js">
  <head>
    {% include head.html %}
    {% include head/custom.html %}
  </head>

  <body class="layout--{{ page.layout | default: layout.layout }}{% if page.classes or layout.classes %}{{ page.classes | default: layout.classes | join: ' ' | prepend: ' ' }}{% endif %}">
    {% include_cached skip-links.html %}
    {% include_cached browser-upgrade.html %}
    {% include_cached masthead.html %}
    
    {% include page__hero.html %}

    <div class="initial-content">
      <center>
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3319.940114900411!2d73.04013321455454!3d33.68461478070752!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x38dfbff918838da7%3A0x54e2a2c8aaf168e7!2sSafeway%20Pharmacy%20%26%20Cosmetics%20G-9%2F4!5e0!3m2!1sen!2s!4v1635337558937!5m2!1sen!2s" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
        </center>

        <hr>

        # Proprietor
        Jamil ur Rehman<br> 
        <a href="tel:+923335173717" target="_blank">0333 517 3717</a><br>
        <a href="mailto:jamilqureshi55@gmail.com" target="_blank">jamilqureshi55@gmail.com</a><br><br>

        ## Accounts Manager:
        Umer Farooq <br>
        <a href="tel:+923215191287" target="_blank">0321 519 1287</a><br><br>

        ## Manager Pharmacy: 
        Shehbaz Mughal<br>
        <a href="tel:+923463141020" target="_blank">0346 314 1020</a><br>
        <a href="mailto:jamilqureshi55@gmail.com" target="_blank">shahbazmughal020@gmail.com</a><br><br>
    </div>
    


    {% if site.search == true %}
      <div class="search-content">
        {% include_cached search/search_form.html %}
      </div>
    {% endif %}

    <div id="footer" class="page__footer">
      <footer>
        {% include footer/custom.html %}
        {% include_cached footer.html %}
      </footer>
    </div>

    {% include scripts.html %}

  </body>
</html>



