---
layout: default
title: Projects
---

{% include navbar.html %}

<style>

body > .container {
  max-width: 1200px !important;
  width: 95% !important;
}
  
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

  
.project-card img {
  display: block;
  margin: 0 auto 10px auto;  /* centers the image horizontally */
  max-width: 80%;            /* optional: shrink slightly inside the card */
  height: auto;
  border-radius: 4px;
}

</style>

# ⚡ Electrical Engineering Projects

<div class="project-grid">

  <a href="/projects/Solar_Power_Conditioning.html" class="project-card">
    <img src="/images/EE_Question.jpg" alt="ESP32 Solar Harvester">
    <h3>ESP32 Solar Harvester</h3>
    <p>Solar-powered telemetry with ESP32 and supercapacitor storage.</p>
  </a>

  <a href="/projects/Retro_Handheld_RP_CM5.html" class="project-card">
    <img src="/images/EE_Question.jpg" alt="Retro Handheld Design">
    <h3>Retro Handheld w/ Raspberry Pi CM5 </h3>
    <p>Game system handheld using Raspberry Pi CM5 and custom made IO board.</p>
  </a>

  <a href="/projects/USB_C_Wall_Adaptor_Charger.html" class="project-card">
    <img src="/images/EE_Question.jpg" alt="USB C Power Brick">
    <h3>USB-C Power Adaptor Design </h3>
    <p>USB-C Power Adaptor Design </p>
  </a>

  <a href="/projects/USB_C_Wall_Adaptor_Charger.html" class="project-card">
    <img src="/images/EE_Question.jpg" alt="USB C Power Brick">
    <h3>USB-C Power Adaptor Design </h3>
    <p>USB-C Power Adaptor Design </p>
  </a>

  <a href="/projects/USB_C_Wall_Adaptor_Charger.html" class="project-card">
    <img src="/images/EE_Question.jpg" alt="USB C Power Brick">
    <h3>USB-C Power Adaptor Design </h3>
    <p>USB-C Power Adaptor Design </p>
  </a>

  <a href="/projects/USB_C_Wall_Adaptor_Charger.html" class="project-card">
    <img src="/images/EE_Question.jpg" alt="USB C Power Brick">
    <h3>USB-C Power Adaptor Design </h3>
    <p>USB-C Power Adaptor Design </p>
  </a>

</div>
