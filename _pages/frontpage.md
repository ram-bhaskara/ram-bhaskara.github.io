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
      <a href="https://github.com/{{ site.ram-bhaskara }}" target="_blank">
        <i class="fab fa-github" style="font-size: 25px; margin: 0 10px;"></i>
      </a>
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


Hi! I am Posdoctoral Researcher in the [RISc Lab](https://rcweb.dartmouth.edu/RISCLab/) at Dartmouth, working with Profs. [Adithya Pediredla](https://faculty-directory.dartmouth.edu/adithya-k-pediredla) and [Wojciech Jarosz](https://cs.dartmouth.edu/~wjarosz/). My research spans computational sensing, rendering, and navigation.


I earned my PhD in Aerospace Engineering from Texas A&M University under Prof. [Manoranjan Majji](https://engineering.tamu.edu/aerospace/profiles/majji-manoranjan.html). My dissertation focused on digital signal processing and state estimation using FPGA-based embedded systems. Here is a brief outline of my doctoral work: [Technical Note](./assets/imgs/pubs/Ram_Dissertation_Poster.pdf "Poster").

During graduate school, I also worked extensively on sensor simulation and computational vision for space robotics. As a visiting researcher at NASA JPL, I worked with Drs. [Georgios Georgakis](https://www-robotics.jpl.nasa.gov/who-we-are/people/georgios-georgakis/), and Anup Katake on the [Europa Lander](https://www.jpl.nasa.gov/missions/europa-lander/) concept mission, focusing on perception for vision-based localization and velocimeter LiDAR projects. 

#I also contributed briefly to JPL’s [RACER](https://www-robotics.jpl.nasa.gov/what-we-do/research-tasks/racer/) program for off-road autonomous vehicles.


I am broadly interested in intelligent sensing for perceptually challenging environments, with the goal of enabling precise navigation and science-driven autonomous operations.