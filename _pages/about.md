---
permalink: /
excerpt: About me
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Master student in the [Helping Hands Lab](https://www2.ccs.neu.edu/research/helpinghands/) at **Northeastern University**, advised by Professor [Robert Platt](https://www2.ccs.neu.edu/research/helpinghands/people/).  
My research focuses on robotic manipulation, tactile sensing, and exoskeleton systems, with an emphasis on developing sample-efficient and contact-aware policies that enable in-hand manipulation and cross-embodiment skill transfer.

<p class="contact-links">
  <a href="mailto:ye.zhang1@northeastern.edu"><i class="far fa-envelope icon-pad-right" aria-hidden="true"></i>Email</a> /
  <a href="https://scholar.google.com/"><i class="fas fa-graduation-cap icon-pad-right" aria-hidden="true"></i>Google Scholar</a> /
  <a href="https://github.com/evenjohnyz"><i class="fab fa-github icon-pad-right" aria-hidden="true"></i>GitHub</a> /
</p>

## Research Interests
- Robotic manipulation and contact-rich control  
- Tactile perception and in-hand pose estimation for dexterous manipulation  
- Imitation learning and policy generalization across embodiments  

## News
<style>
#news-list {
  margin-bottom: 0;
}
#news-list li:nth-child(n+6) {
  display: none;
}
#news-more {
  cursor: pointer;
  color: #52adc8;
  margin-left: 1.5em;
  margin-top: 0;
  display: inline-block;
}
.contact-links a {
  text-decoration: none;
  margin-right: 0.35em;
}
.contact-links .icon-pad-right {
  margin-right: 0.3em;
}
.project-img-container {
  width: 220px;
  display: flex;
  align-items: center;
  justify-content: center;
  float: right;
  margin-left: 1em;
  margin-bottom: 0.5em;
  background: transparent;
}
.project-img-container img {
  max-width: 100%;
  height: auto;
  display: block;
}
.button-cta {
  appearance: none;
  background-color: #fafbfc;
  border: 1px solid rgba(27, 31, 35, 0.15);
  border-radius: 6px;
  box-shadow: rgba(27, 31, 35, 0.04) 0 1px 0, rgba(255, 255, 255, 0.25) 0 1px 0 inset;
  box-sizing: border-box;
  color: #24292e;
  cursor: pointer;
  display: inline-block;
  font-family: -apple-system, system-ui, "Segoe UI", Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji";
  font-size: 16px;
  font-weight: 500;
  line-height: 20px;
  padding: 4px 8px;
  transition: background-color 0.2s cubic-bezier(0.3, 0, 0.5, 1);
  margin-right: 0.3em;
  margin-bottom: 0.4em;
}
.button-cta:hover {
  background-color: #f3f4f6;
  text-decoration: none;
  transition-duration: 0.1s;
}
.button-cta:active {
  background-color: #edeff2;
  box-shadow: rgba(225, 228, 232, 0.2) 0 1px 0 inset;
  transition: none 0s;
}
.button-cta:focus {
  outline: 1px transparent;
}
@media (max-width: 600px) {
  .project-img-container {
    float: none;
    margin-left: auto;
    margin-right: auto;
    margin-bottom: 1em;
    width: 100%;
  }
  .project-img-container img {
    width: 90vw;
    max-width: 320px;
    height: auto;
  }
}
</style>

<script>
document.addEventListener("DOMContentLoaded", function() {
  var showMore = document.getElementById("news-more");
  if (!showMore) return;
  showMore.addEventListener("click", function() {
    var hiddenItems = document.querySelectorAll('#news-list li:nth-child(n+6)');
    hiddenItems.forEach(function(item) {
      item.style.display = 'list-item';
    });
    showMore.style.display = 'none';
  });
});
</script>

## News
<ul id="news-list">
  <li>12/2024: Joined the <a href="https://www2.ccs.neu.edu/research/helpinghands/">Helping Hands Lab</a> at <strong>Northeastern University</strong> as a graduate researcher advised by Prof. Robert Platt.</li>
  <li>12/2024: Joined Northeastern University Robotics program.</li>
<a id="news-more" href="javascript:void(0)">more ▾</a>

