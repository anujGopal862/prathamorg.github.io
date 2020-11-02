---
layout: post
title: Detect fake audio attribution
subtitle: Creating speaker profiles to test authenticity of audio files
tags: [speech,testing,deep learning,deep neural networks]
comments: true
---

**Objective:** To check if an audio clip attributed to an individual was actually spoken by the individual.

**Concept:** To create a tool to assign an authenticity score of an audio clip of an individual.
    Create a speaker profile through publicly available audio clips
    Compare the viral clip to the profile and assign a score

**Issues addressed:** To detect the authenticity of messages containing audio clips of a well-known individual. This will help in preventing the spread of misinformation through such misleading messages which have become very widespread especially in the current times.
**Tech Needs:**

<table>
  <tr>
    <td>Problem Statements</td>
    <td>Know-how</td>
  </tr>
  <tr>
    <td>Extract audio files of the speaker across websites (through web crawler/bot?)</td>
    <td>Creating/using non-text/audio crawlers</td>
  </tr>
  <tr>
    <td>Speaker diarization from the collected audio files</td>
    <td>Speech Signal processing,  Deep Neural Networks</td>
  </tr>
  <tr>
    <td>Create a tool to assign a score by comparing the viral audio clip to the speaker profile</td>
    <td>Speech signal processing, Machine Learning and Deep Learning Algorithms</td>
  </tr>
</table>


**Details:** In the current times, a lot of messages containing clips claiming to be that of well-known individuals are being widely circulated across various media platforms. Knowing the authenticity will help to prevent the spread and circulation of such messages. This is especially important during the COVID-19 pandemic so that false information (which is made to look legitimate with such videos) can be stopped from being spread. Creating speaker profiles through speaker diarization will be instrumental in ascertaining the authenticity of the viral audio clips. 


<h2><a href="https://docs.google.com/forms/d/e/1FAIpQLScKY71-Hq2lTdgP-k0JIcsVvoYNXaxtYLcRGVLf_xVGdciHlg/viewform?usp=pp_url&entry.123018661=Detect+fake+audio+attribution">
  Interested in this project? Register Here</a></h2>
