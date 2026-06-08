---
title: Program overview
template: base.html
---

# {{ page.custom_page_title }}


## July 3rd, 2026

<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600&family=DM+Serif+Display&display=swap" rel="stylesheet">

<style>
  .agenda-wrap { font-family: 'DM Sans', sans-serif; max-width: 860px; margin: 2rem auto; }
  .agenda-table { width: 100%; border-collapse: separate; border-spacing: 0 5px; font-size: 0.92rem; }
  .agenda-table thead tr th { background: #1a2e44; color: #fff; padding: 10px 16px; text-align: left; font-weight: 600; letter-spacing: 0.04em; text-transform: uppercase; font-size: 0.78rem; }
  .agenda-table thead tr th:first-child { border-radius: 8px 0 0 8px; }
  .agenda-table thead tr th:last-child  { border-radius: 0 8px 8px 0; }
  .agenda-table tbody tr td { padding: 10px 16px; vertical-align: top; line-height: 1.45; }
  .agenda-table tbody tr td:first-child { border-radius: 8px 0 0 8px; white-space: nowrap; font-variant-numeric: tabular-nums; font-weight: 600; }
  .agenda-table tbody tr td:last-child  { border-radius: 0 8px 8px 0; }
  .row-talk    { background: #eef4fb; } .row-talk:hover    { background: #ddeaf7; }
  .row-break   { background: #fdf3e3; } .row-break:hover   { background: #fae8cc; }
  .row-social  { background: #e9f6ef; } .row-social:hover  { background: #d4edde; }
  .row-opening { background: #f0ebfa; } .row-opening:hover { background: #e3d8f5; }
  .row-wrapup  { background: #fde8e8; } .row-wrapup:hover  { background: #facece; }
  .row-talk, .row-break, .row-social, .row-opening, .row-wrapup { transition: background 0.15s ease; cursor: default; }
  .time-col { color: #3a5a80; min-width: 130px; }
  .spk-col  { color: #2d2d2d; min-width: 170px; }
  .affil { color: #777; font-style: italic; font-size: 0.85em; }
  .tag { display: inline-block; font-size: 0.7rem; font-weight: 700; letter-spacing: 0.06em; text-transform: uppercase; padding: 2px 7px; border-radius: 20px; margin-right: 6px; vertical-align: middle; }
  .tag-break  { background: #f5c97a; color: #6b4400; }
  .tag-social { background: #82d9a8; color: #0d4a25; }
  .tag-open   { background: #c5adee; color: #3b1a72; }
  .tag-wrap   { background: #f09c9c; color: #6b0000; }
</style>

<div class="agenda-wrap">
  <table class="agenda-table">
    <thead>
      <tr>
        <th class="time-col">Time</th>
        <th class="spk-col">Speaker</th>
        <th>Talk / Session</th>
      </tr>
    </thead>
    <tbody>
      <tr class="row-opening">
        <td class="time-col">09:15 – 09:30</td>
        <td class="spk-col">Stefano, Mario, Matteo, Claudio</td>
        <td><span class="tag tag-open">Welcome</span> Opening remarks</td>
      </tr>
      <tr class="row-talk">
        <td class="time-col">09:30 – 09:50</td>
        <td class="spk-col">Stefano Orlandini<br><span class="affil">UNIMORE</span></td>
        <td>Upscaling CATHY to the Po River Drainage Basin?</td>
      </tr>
      <tr class="row-talk">
        <td class="time-col">09:50 – 10:10</td>
        <td class="spk-col">Matteo Camporese<br><span class="affil">UNIPD</span></td>
        <td>Earth Observation–Driven Representation of Irrigation Dynamics in Coupled Surface–Subsurface Hydrological Models</td>
      </tr>
      <tr class="row-talk">
        <td class="time-col">10:10 – 10:30</td>
        <td class="spk-col">Riccardo Gasperoni<br><span class="affil">UNIMORE</span></td>
        <td>Terrain-Informed Smoothing of Automatically Extracted Thalwegs and Ridges in High-Resolution DEMs for Optimal Surface Flow Mesh Generation</td>
      </tr>
      <tr class="row-break">
        <td class="time-col">10:30 – 11:00</td>
        <td class="spk-col">—</td>
        <td><span class="tag tag-break">☕ Break</span> Discussions + Coffee Break</td>
      </tr>
      <tr class="row-talk">
        <td class="time-col">11:00 – 11:20</td>
        <td class="spk-col">Matthew W Farthing</td>
        <td>TBA</td>
      </tr>
      <tr class="row-talk">
        <td class="time-col">11:20 – 11:40</td>
        <td class="spk-col">Elena Bachini<br><span class="affil">UNIPD</span></td>
        <td>Geometric Shallow Water vs Zero-Inertia Approximations for Coupled Surface–Subsurface Hydrological Simulations</td>
      </tr>
      <tr class="row-talk">
        <td class="time-col">11:40 – 12:00</td>
        <td class="spk-col">Rachit Soni<br><span class="affil">UNIMORE</span></td>
        <td>Levee Reliability Under Flood and Burrowing Mammal Erosion</td>
      </tr>
      <tr class="row-talk">
        <td class="time-col">14:40 – 15:00</td>
        <td class="spk-col">Hadi Nasser<br><span class="affil">INRAE</span></td>
        <td>A Gaussian Process-based Metamodel for CATHY with High-Dimensional Spatio-Temporal Data</td>
      </tr>
      <tr class="row-break">
        <td class="time-col">12:20 – 12:40</td>
        <td class="spk-col">—</td>
        <td><span class="tag tag-break">💬 Discuss</span> Open Discussions</td>
      </tr>
      <tr class="row-break">
        <td class="time-col">12:40 – 14:00</td>
        <td class="spk-col">—</td>
        <td><span class="tag tag-break">🍽️ Lunch</span> Lunch Break</td>
      </tr>
      <tr class="row-talk">
        <td class="time-col">14:00 – 14:20</td>
        <td class="spk-col">Daniele la Cecilia<br><span class="affil">UNIMORE</span></td>
        <td>Recent Additions to CATHY (Irrigation Module, Monod Kinetics, Plant Uptake)</td>
      </tr>
      <tr class="row-talk">
        <td class="time-col">14:20 – 14:40</td>
        <td class="spk-col">Benjamin Mary<br><span class="affil">CSIC</span></td>
        <td>pyCATHY: A Python Wrapper for Data Assimilation in CATHY</td>
      </tr>
      <tr class="row-talk">
        <td class="time-col">12:00 – 12:20</td>
        <td class="spk-col">Lauvernet Claire<br><span class="affil">INRAE</span></td>
        <td>Comparison of Two Classes of Integrated Surface–Subsurface Flow and Solute Transport Models Using Uncertainty Quantification Methods</td>
      </tr>
      <tr class="row-wrapup">
        <td class="time-col">15:00</td>
        <td class="spk-col">—</td>
        <td><span class="tag tag-wrap">Wrap Up</span> CATHY Day Wrap Up</td>
      </tr>
      <tr class="row-social">
        <td class="time-col">Evening</td>
        <td class="spk-col">—</td>
        <td><span class="tag tag-social">🔭 Social</span> Visit Geophysical Observatory + Social Dinner</td>
      </tr>
    </tbody>
  </table>
</div>
