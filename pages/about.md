---
layout: page
title: About this Project
permalink: /about/
---
The Unionist Unified was created by Jennifer Rycenga in collaboration with the [Digital Scholarship Services](https://library.sjsu.edu/about/digital-scholarship-services) group at the SJSU Martin Luther King, Jr. Library.

- Jennifer Rycenga, Professor, Humanities Department, San José State University
- Nick Szydlowski, Digital Scholarship Librarian, Martin Luther King, Jr. Library, San José State University
- Sharesly Rodriquez, User Experience Librarian, Martin Luther King, Jr. Library, San José State University

<hr/>
<div class='about-logos'>
<p class='logos'>
  {% for item in site.footer.logos %}
  {% assign link = item.link | default: '#' %}
  <a href="{{ link | absolute_url }}" aria-label="Logo link to resource">
    <img src='{{ item.img | absolute_url }}' alt="logo"/>
  </a>
  {% endfor %}
</p>
<div>
  <a href="https://portal.ct.gov/DECD/Content/Historic-Preservation/04_State_Museums/Prudence-Crandall-Museum">Prudence Crandall Museum</a>
  </div>
</div>
