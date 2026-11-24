---
layout: about
title: about
permalink: /
subtitle: PhD Student, <a href='https://www.roboticmanipulation.org/'>Harada Laboratory</a>, The University of Osaka

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true # crops the image to make it circular
  more_info: >
    <p>Graduate School of Engineering Science</p>
    <p>The University of Osaka</p>
    <p>Toyonaka, Osaka, Japan</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

I am a PhD student at the [Harada Laboratory](https://www.roboticmanipulation.org/), The University of Osaka, where I also completed my Master's degree. My research focuses on **contact-rich robotic manipulation**, combining **reinforcement learning**, **force sensing**, and **probabilistic state estimation** so that robots can handle tasks where the right motion cannot be seen and has to be felt.

During my Master's, I developed a belief-augmented reinforcement learning framework for **force-driven robotic disassembly**. In this framework, a particle filter estimates the hidden direction in which a part can be extracted using only wrist force/torque sensing, and the policy uses this belief to guide its motion. The policy is trained entirely in MuJoCo simulation on a robot-agnostic simple peg-in-hole pair and transferred zero-shot to a real KUKA LBR iiwa 14 robot and an End-of-Life AirCon unit.

Before coming to Japan, I received my B.Sc. in Mechatronics Engineering from the Benha Faculty of Engineering, Benha University, Egypt, where I worked as a Teaching Assistant for one year.

**Research interests:** reinforcement learning for manipulation, sim-to-real transfer, force-based perception, and robotic disassembly for recycling and remanufacturing.


<div style="clear: both;"></div>

<p style="margin-top: 1.5rem;">
  <a href="#portfolio">Portfolio</a> &nbsp;·&nbsp;
  <a href="#biography">Biography</a> &nbsp;·&nbsp;
  <a href="#news-and-publications">News &amp; Publications</a>
</p>

---

## Portfolio

<div class="row mt-3">
  <div class="col-md-6 mb-4">
    <img src="{{ '/assets/img/portfolio/disassembly.gif' | relative_url }}" class="img-fluid rounded z-depth-1" width="100%" alt="Robotic disassembly demo" loading="lazy">
    <h5 class="mt-2">Belief-Augmented RL for Force-Driven Robotic Disassembly</h5>
    <p>A particle filter estimates the hidden direction in which a part can be extracted, using only wrist force/torque sensing, and an RL policy uses this belief to guide its motion. Trained in MuJoCo and deployed zero-shot on a KUKA LBR iiwa 14.</p>
    <p>
      <a href="https://arxiv.org/abs/2610.38513">[arXiv]</a>
      <a href="{{ '/assets/video/disassembly.mp4' | relative_url }}">[Video]</a>
    </p>
  </div>
</div>

---

## Biography

- **2026 – present** &nbsp; PhD student, Harada Laboratory, The University of Osaka
- **2024 – 2026** &nbsp; M.S., Harada Laboratory, The University of Osaka
- **2023 – 2024** &nbsp; Teaching Assistant, Benha Faculty of Engineering, Benha University, Egypt
- **2018 – 2023** &nbsp; B.Sc. in Mechatronics Engineering, Benha Faculty of Engineering, Benha University, Egypt

---

<h2 id="news-and-publications">News &amp; Publications</h2>

<style>
  .profile img {
    aspect-ratio: 1 / 1;
    object-fit: cover;
    object-position: top center;
    border-radius: 50%;
  }
</style>