---
layout: default
title: Projects
---

{% include navbar.html %}

<style>
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  padding: 1em;
}

.project-card {
  background-color: #222;
  padding: 1em;
  border-radius: 8px;
  color: white;
  text-align: center;
  box-shadow: 0 2px 6px rgba(0,0,0,0.3);
  transition: transform 0.2s;
}
.project-card:hover {
  transform: scale(1.02);
}
.project-card img {
  width: 100%;
  height: auto;
  border-radius: 4px;
  margin-bottom: 10px;
}
.project-card h3 {
  margin: 0.5em 0 0.2em;
}
.project-card a {
  color: #66ccff;
  text-decoration: none;
}
</style>

<div class="project-grid">

  <div class="project-card">
    <img src="/images/EE_Question.jpg" alt="ESP32 Solar Harvester">
    <h3>ESP32 Solar Harvester</h3>
    <p><a href="https://github.com/eenick/esp32-solar-harvester">View on GitHub</a></p>
  </div>

  <div class="project-card">
    <img src="/images/EE_Question.jpg" alt="FPGA Retro Console">
    <h3>FPGA Retro Console</h3>
    <p><a href="https://github.com/eenick/fpga-retro-console">View on GitHub</a></p>
  </div>

  <div class="project-card">
    <img src="/images/EE_Question.jpg" alt="Buck Converter">
    <h3>Buck Converter</h3>
    <p><a href="#">Design Details Coming Soon</a></p>
  </div>

</div>
