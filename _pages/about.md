---
layout: about
title: About
permalink: /
subtitle: Biomedical optics · optical instrumentation · scientific computing
selected_papers: false
social: false
announcements:
  enabled: false
latest_posts:
  enabled: false
---

<link rel="stylesheet" href="{{ '/assets/css/site.css' | relative_url }}">

<p class="lead-intro">I build optical instruments, and the acquisition and analysis software around them, for biomedical measurements. I currently work in Prof. Ulas Sunar’s group at Stony Brook University on time-gated speckle contrast optical spectroscopy (SCOS) and on synchronizing optical acquisition with EEG.</p>

<ul class="contact-line" aria-label="Contact">
  <li><a href="mailto:{{ site.data.socials.email }}">{{ site.data.socials.email }}</a></li>
  <li><a href="https://github.com/{{ site.data.socials.github_username }}">github.com/{{ site.data.socials.github_username }}</a></li>
</ul>

<section class="feature" aria-labelledby="current-project">
  <p class="tag">Current project</p>
  <p class="kicker">Stony Brook University · Prof. Ulas Sunar’s group</p>
  <h2 class="feature-title" id="current-project"><a href="{{ '/research/scos-eeg/' | relative_url }}">Time-gated SCOS with synchronized EEG acquisition</a></h2>
  <p>I write the Python NI-DAQ control that synchronizes the camera with the galvanometer and automates alignment, and the MATLAB routines that check and process the acquired data. I am now building and debugging an acquisition workflow that records SCOS and EEG together.</p>
  <p class="more"><a href="{{ '/research/scos-eeg/' | relative_url }}">Read about this project <span aria-hidden="true">→</span></a></p>
</section>

## Instrument and lab experience

<ul class="exp-list">
  <li>
    <h3>Optical acquisition and hardware timing</h3>
    <p>NI-DAQ control in Python for camera–galvanometer synchronization and automated alignment; troubleshooting residual frames and mismatched frame tags in high-speed C-RED 2 acquisition; SCOS–EEG acquisition in progress.</p>
  </li>
  <li>
    <h3>Nanoscale infrared instrumentation</h3>
    <p>Alignment and calibration work on AFM-IR and s-SNOM instruments; a hardware-triggered, 1,024-point FFT implemented on Moku:Go.</p>
  </li>
  <li>
    <h3>Camera-based physiological measurement</h3>
    <p>A Python pipeline that extracts pulse waveforms from imaging photoplethysmography data, and a LabVIEW interface for live display and automated logging, integrated with the experimental hardware.</p>
  </li>
  <li>
    <h3>Analysis and scientific computing</h3>
    <p>MATLAB data quality control and processing; evidence audits for gene–disease relation extraction; a Python implementation of SpatialPCA compared numerically with the R implementation.</p>
  </li>
</ul>

<p class="more"><a href="{{ '/research/' | relative_url }}">All research projects <span aria-hidden="true">→</span></a></p>

## Education

<ul class="edu-list">
  <li><span class="where">Stony Brook University</span> <span class="what">B.S. in Physics, 2026</span></li>
  <li><span class="where">Anhui University</span> <span class="what">B.S. in Applied Physics, 2026</span></li>
</ul>

## Contact

<p>The best way to reach me is by email: <a href="mailto:{{ site.data.socials.email }}">{{ site.data.socials.email }}</a>. Code is on GitHub at <a href="https://github.com/{{ site.data.socials.github_username }}">github.com/{{ site.data.socials.github_username }}</a>.</p>
