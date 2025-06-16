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
  text-decoration: none;
  box-shadow: 0 2px 6px rgba(0,0,0,0.3);
  transition: transform 0.2s, box-shadow 0.2s;
  display: block;
}

.project-card:hover {
  transform: scale(1.03);
  box-shadow: 0 4px 12px rgba(0,0,0,0.5);
}

.project-card img {
  width: 100%;
  height: auto;
  border-radius: 4px;
  margin-bottom: 10px;
}

.project-card h3,
.project-card p {
  color: white;
  margin: 0.5em 0;
}

.project-card * {
  color: white;
}
</style>

# ⚡ Electrical Engineering Projects

<div class="project-grid">

  <a href="/projects/solar-harvester.html" class="project-card">
    <img src="/images/EE_Question.jpg" alt="ESP32 Solar Harvester">
    <h3>ESP32 Solar Harvester</h3>
    <p>Solar-powered telemetry with ESP32 and supercapacitor storage.</p>
  </a>

  <a href="/projects/fpga-retro-console.html" class="project-card">
    <img src="/images/EE_Question.jpg" alt="FPGA Retro Console">
    <h3>FPGA Retro Console</h3>
    <p>Game system SoC with VGA, audio, and input using Verilog on Arty A7.</p>
  </a>

  <a href="/projects/buck-converter.html" class="project-card">
    <img src="/images/EE_Question.jpg" alt="Buck Converter Design">
    <h3>Buck Converter Design</h3>
    <p>LTspice-modeled synchronous converter with 10W output and low ripple.</p>
  </a>

</div>
