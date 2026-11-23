---
layout: page
title: "Time-gated SCOS and EEG"
description: "Optical acquisition and hardware synchronization at Stony Brook University"
permalink: /research/scos-eeg/
importance: 1
kicker: "Stony Brook University · Prof. Ulas Sunar’s group · 2026–present"
subject: "Time-gated speckle contrast optical spectroscopy (SCOS), and how to acquire it in synchrony with EEG."
contribution: "Python NI-DAQ control for camera–galvanometer synchronization and automated alignment; MATLAB quality control and processing; investigation of residual frames and mismatched frame tags on a C-RED 2 camera; building the combined SCOS–EEG acquisition."
---

<p class="lead-intro">In Prof. Ulas Sunar’s group I work on the acquisition side of a time-gated speckle contrast optical spectroscopy (SCOS) system: the control software that synchronizes the hardware, the routines that check and process the data, and an acquisition workflow that combines SCOS with EEG.</p>

<dl class="facts">
  <div><dt>Where</dt><dd>Stony Brook University</dd></div>
  <div><dt>Group</dt><dd>Prof. Ulas Sunar</dd></div>
  <div><dt>Period</dt><dd>2026–present</dd></div>
  <div><dt>Tools</dt><dd>Python, NI-DAQ, MATLAB, C-RED 2 camera, galvanometer, EEG</dd></div>
</dl>

## What I do

<ul class="work-list">
  <li><strong>Hardware synchronization.</strong> I develop Python-based NI-DAQ control that synchronizes the camera with the galvanometer.</li>
  <li><strong>Automated alignment.</strong> The same NI-DAQ control code supports automated alignment.</li>
  <li><strong>Data quality control and processing.</strong> I write MATLAB routines for data quality control and processing.</li>
  <li><strong>Acquisition debugging.</strong> I investigated residual frames and mismatched frame tags in high-speed acquisition with a C-RED 2 camera.</li>
  <li><strong>SCOS with EEG.</strong> I am building and debugging acquisition that combines SCOS and EEG. This part is in progress.</li>
</ul>

## How the pieces fit

<figure class="schematic">
  <ol class="chain" aria-label="Acquisition chain, from control to processing">
    <li>
      <p class="stage">Control</p>
      <ul>
        <li>Python control software</li>
        <li>NI-DAQ</li>
      </ul>
    </li>
    <li>
      <p class="stage">Synchronized hardware</p>
      <ul>
        <li>C-RED 2 camera</li>
        <li>Galvanometer</li>
        <li class="pending">EEG <em>(integration in progress)</em></li>
      </ul>
    </li>
    <li>
      <p class="stage">Checks and processing</p>
      <ul>
        <li>MATLAB data quality control</li>
        <li>MATLAB processing</li>
      </ul>
    </li>
  </ol>
  <figcaption>Schematic only. An illustrative block diagram of the roles described on this page, drawn for this site; it is not a wiring diagram and shows no measured data.</figcaption>
</figure>

## Status

<p class="status-note">This is ongoing work. Results, instrument figures, and publications are not posted here yet.</p>

<p class="back-link"><a href="{{ '/research/' | relative_url }}"><span aria-hidden="true">←</span> All research projects</a></p>
