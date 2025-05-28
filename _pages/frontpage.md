---
permalink: /
layout: newHome
title: 
list_title: 
---

<div style="text-align: center;">
  <img src="./assets/imgs/img1_rcb.png" alt="YoDontScamMe" style="width:200px; height:200px; border-radius:50%; object-fit:cover;">
  <br><br>
  <div class="social-icons">
    {% if site.github_username %}
      <!--a href="https://github.com/{{ site.github_username }}" target="_blank">
        <i class="fab fa-github" style="font-size: 30px; margin: 0 10px;"></i>
      </a-->
    {% endif %}
    {% if site.email %}
      <a href="mailto:{{ site.email }}" target="_blank">
        <i class="fas fa-envelope" style="font-size: 25px; margin: 0 10px;"></i>
      </a>
    {% if site.linkedin_username %}
      <a href="https://www.linkedin.com/in/{{ site.linkedin_username }}" target="_blank">
        <i class="fab fa-linkedin" style="font-size: 25px; margin: 0 10px;"></i>
      </a>
    {% endif %}
    {% endif %}
    {% if site.google_scholar %}
      <a href="https://scholar.google.com/citations?user={{ site.google_scholar }}" target="_blank">
        <i class="fas fa-graduation-cap" style="font-size: 25px; margin: 0 10px;"></i>
      </a>
    {% endif %}
  </div>
</div>

&nbsp;


I'm a PhD candidate in Aerospace Engineering at Texas A&M University - graduating in August 2025. My research focuses on on-board signal processing and state estimation using FPGA embedded systems. I also work on computer graphics and computer vision for space robotics.

Here is a brief outline of my dissertation research: [Technical Note](./assets/imgs/pubs/Ram_Dissertation_Poster.pdf "Poster").

Previously, I was a visiting research intern at NASA JPL, where I worked on planetary surface and sensor modeling, as well as perception for offroad autonomous vehicles.

**I am seeking full-time** (or) **postdoctoral opportunities** starting in August 2025: 
- Sensor algorithms and signal processing
- State estimation and robotic navigation
- Sensor and environment modeling (autonomous vehicles or planetary science)
&nbsp;

[comment]: This is a template and some instructions for running Github Pages with the [`minima` theme][minima].

[gh-site]: https://pages.github.com/
[minima]: https://github.com/jekyll/minima/tree/2.5-stable
[jk]: https://jekyllrb.com/
[gh]: https://help.github.com/en/github/working-with-github-pages
[issue]: https://github.com/jsanz/gh-pages-minima-starter/issues/new/choose
[contact]: https://jorgesanz.net/contact/