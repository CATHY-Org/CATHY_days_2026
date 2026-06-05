---
custom_page_title: "CATHY days 2026"
exclude_h1: true
template: base.html
---
{%- import "macros.html" as macros %}

<style>
  /* ── Shared palette (mirrors agenda) ── */
  :root {
    --c-navy:    #1a2e44;
    --c-blue-lt: #eef4fb;
    --c-blue-md: #3a5a80;
    --c-amber:   #fdf3e3;
    --c-amber-dk:#6b4400;
    --c-green-lt:#e9f6ef;
    --c-green-dk:#0d4a25;
    --c-purple-lt:#f0ebfa;
    --c-purple-dk:#3b1a72;
    --c-red-lt:  #fde8e8;
    --c-tag-br:  #f5c97a;
    --c-tag-so:  #82d9a8;
    --c-tag-op:  #c5adee;
  }

  /* callout override */
  .callout { background: var(--c-blue-lt); border-left: 4px solid var(--c-blue-md); border-radius: 6px; padding: 14px 18px; }
  .callout-success { background: var(--c-green-lt); border-left: 4px solid #2a9e5e; }

  /* key-dates banner */
  .key-dates {
    border-left: 4px solid var(--c-navy);
    background: var(--c-purple-lt);
    padding: 14px 18px;
    border-radius: 6px;
    font-size: 0.97rem;
  }
  .key-dates strong { color: var(--c-navy); }

  /* section headers accent */
  h2 { border-bottom: 2px solid var(--c-blue-md); padding-bottom: 4px; color: var(--c-navy); }

  /* venue card */
  .venue-card {
    background: var(--c-blue-lt);
    border-left: 4px solid var(--c-blue-md);
    border-radius: 6px;
    padding: 14px 18px;
  }
  .venue-card a { color: var(--c-blue-md); font-weight: 600; }

  /* transport table */
  .transport-table { width: 100%; border-collapse: separate; border-spacing: 0 5px; font-size: 0.91rem; font-family: inherit; }
  .transport-table thead th { background: var(--c-navy); color: #fff; padding: 9px 14px; text-align: left; font-size: 0.78rem; letter-spacing: 0.04em; text-transform: uppercase; }
  .transport-table thead th:first-child { border-radius: 8px 0 0 8px; }
  .transport-table thead th:last-child  { border-radius: 0 8px 8px 0; }
  .transport-table tbody td { padding: 10px 14px; vertical-align: top; line-height: 1.45; }
  .transport-table tbody td:first-child { border-radius: 8px 0 0 8px; font-weight: 600; white-space: nowrap; }
  .transport-table tbody td:last-child  { border-radius: 0 8px 8px 0; }
  .tr-train  { background: var(--c-blue-lt);   } .tr-train:hover  { background: #ddeaf7; }
  .tr-plane  { background: var(--c-amber);     } .tr-plane:hover  { background: #fae8cc; }
  .tr-car    { background: var(--c-green-lt);  } .tr-car:hover    { background: #d4edde; }
  .tr-local  { background: var(--c-purple-lt); } .tr-local:hover  { background: #e3d8f5; }
  .transport-table tbody tr { transition: background 0.15s ease; }
  .mode-icon { font-size: 1.2em; margin-right: 6px; }

  img { border-radius: 4px; width: 150px; }
  #envitam { width: 450px; }
</style>


<div class="row mb-3 align-items-center">
<div class="col-md-9 col-sm-8 col-8">

# CATHY days 2026

<p class="lead">
We are thrilled to announce that in **2026** we will renew the tradition and organise the <b>CATchment HYdrology (CATHY) days</b>!
</p>

</div>
<div class="col-md-3 col-sm-4 col-4">
  <img alt="Seminar logo" src="{{ config.logo }}">
  <small><i>[1]</i></small>
</div>
</div>


## About this event

<div class="callout callout-success">

This informal meeting will bring together researchers interested in or working on topics connected to **integrated surface-subsurface hydrological modeling**.

The meeting will be focused on a number of talks that will address current progress and challenges in coupled surface–subsurface hydrological modeling, solute transport modeling, data assimilation, and catchment hydrology at large. Plus, we'll make sure plenty of time is left for open discussion.

</div>

<hr>

## Key dates

<div class="key-dates">
  <strong>⚠️ Registration deadline:</strong> March 31st, 2026<br>
  <strong>📅 Seminar days:</strong> July 3rd, 2026
</div>

<hr>

## Registration

<div class="callout callout-success">

There is <span style="color:red;">no registration fee</span> for the workshop; however, the number of **in-person participants is limited to 40**, due to the maximum capacity of the venue. Therefore, respondents will be assigned a spot on a first-come-first-serve basis.

</div>

Want to join? [Registration are open](https://saco.csic.es/apps/forms/s/naAyMppTzXwKPdssZeDPfKrY)!

<hr>

## Venue: Modena (IT)

<div class="venue-card">
  📍 The workshop will be held at the <strong>Department of Engineering "Enzo Ferrari"</strong><br>
  <a href="https://maps.app.goo.gl/HpBkeiKqQnsJjVPq6" target="_blank">Via Vivarelli 10, 41125 Modena (IT)</a>
</div>

<br>

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2836.4!2d10.9481!3d44.6285!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x477fef3b2b5b5b5b%3A0x1!2sVia+Vivarelli+10%2C+41125+Modena!5e1!3m2!1sen!2ses" width="100%" height="380" style="border:0; border-radius:8px;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

<hr>

## How to get there

<table class="transport-table">
  <thead>
    <tr>
      <th>Mode</th>
      <th>From</th>
      <th>Details</th>
    </tr>
  </thead>
  <tbody>
    <tr class="tr-train">
      <td><span class="mode-icon">🚆</span> Train</td>
      <td><strong>Bologna Centrale</strong></td>
      <td>Direct regional trains to <em>Modena station</em> run every 20–30 min (~25 min journey). From Modena station, the Engineering Department is a 15-min walk or a short taxi/bus ride.</td>
    </tr>
    <tr class="tr-train">
      <td><span class="mode-icon">🚆</span> Train</td>
      <td><strong>Milano Centrale</strong></td>
      <td>High-speed trains (Frecciarossa/Italo) to <em>Bologna</em> (~1 h), then regional to Modena. Alternatively, direct intercity trains to Modena (~1 h 40 min).</td>
    </tr>
    <tr class="tr-plane">
      <td><span class="mode-icon">✈️</span> Plane</td>
      <td><strong>Bologna Airport (BLQ)</strong></td>
      <td>Closest international airport (~40 km). Take the Marconi Express to Bologna Centrale (~7 min), then a regional train to Modena (~25 min). Total door-to-door ≈ 1 h.</td>
    </tr>
  </tbody>
</table>

<hr>

## Sponsors 🙌

<style>
  .sponsor-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 2rem;
    align-items: center;
    margin-top: 1.2rem;
  }
  .sponsor-item {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 0.5rem;
    background: var(--c-blue-lt);
    border: 1px solid #d0e4f7;
    border-radius: 10px;
    padding: 1.2rem 2rem;
    text-decoration: none;
    transition: box-shadow 0.15s ease, transform 0.15s ease;
  }
  .sponsor-item:hover {
    box-shadow: 0 4px 16px rgba(26,46,68,0.12);
    transform: translateY(-2px);
  }
  .sponsor-item svg {
    height: 64px;
    width: auto;
  }
  .sponsor-name {
    font-size: 0.72rem;
    font-weight: 700;
    color: var(--c-blue-md);
    letter-spacing: 0.06em;
    text-transform: uppercase;
    margin-top: 2px;
  }
  .sponsor-full {
    font-size: 0.72rem;
    color: #666;
    text-align: center;
    max-width: 180px;
    line-height: 1.3;
  }
</style>

<div class="sponsor-grid">

  <!-- UNIMORE -->
  <a class="sponsor-item" href="https://www.unimore.it/en" target="_blank">
  <img src="./images/unimore.png">
  </a>

  <!-- UNIPD -->
  <a class="sponsor-item" href="https://www.unipd.it/en" target="_blank">
  <img src="./images/unipd.png">
  </a>

</div>

<hr>

## Useful links

<a href="https://github.com/CATHY-Org">Github CATHY group organisation</a>

<hr>

<small><i>[1] Camporese et al. 2019 [10.1029/2019WR025726, fig. 6]</i></small>

## Contact

<p class="lead">
Interested in participating? Get in touch with a committee member directly.
</p>

{%- import "macros.html" as macros %}
{{ macros.make_people_list(page.people.current) }}

<hr class="mb-5">
