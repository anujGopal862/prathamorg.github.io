---
layout: post
title: Biodiversity App
tags: [object recognition, vision, classification]
---

**Objective:** To help children enhance their interest, awareness and knowledge of their local biodiversity

**Concept:** Children can check out local biodiversity wherever they are with an app that says all about the species of animals and plants they find.

**Issues addressed:** Children are natural born explorers. Children wonder which species of bird it is that they keep seeing in their village. They want to know more about the mammals that call their surroundings. They keep asking their parents or elders nearby but get limited information about the same. We need an app that can help children quickly and easily identify flora and fauna, record their findings and learn more about them.

**Tech Needs:**

<table>
  <tr>
    <td>Projects</td>
    <td>Know-how</td>
    <td>Status</td>
  </tr>
  <tr>
    <td>Data collection - develop platform to collect pictures of local flora and fauna along with their names (labeled data)</td>
    <td>Android Development</td>
    <td>App development has started. Initial design has been shared by the Apps team</td>
  </tr>
  <tr>
    <td>Develop and test Deep Learning Models to classify images of Plants and Birds into their corresponding species </td>
    <td>Machine Learning and Deep Learning Algorithms</td>
    <td>Close to 16000 images for 87 plant species and 103 bird species have been scraped from google images for training of the models. Pre-Trained deep learning models trained on the iNaturalist Dataset have been identified and fintuned for Plants and Birds Species. The accuraccy of plants model was ~80% and the birds model was ~85%. The models have been deployed to a web app using flask. Further testing on new data to be done  </td>
  </tr>
  <tr>
    <td>Conceptualize and integrate the designed ML model with an Android app. To make API call to get detailed info about the species found (Deployment)</td>
    <td>Android Development</td>
    <td>Not Started</td>
  </tr>
</table>


**Details:**
With a novel modelling and mapping platform covering tens of thousands of species -- everything from mammals and birds to plants, amphibians, reptiles, and fish, the app presents localised species detailed information. This system will enable children search through and learn more about the species they just spotted. They can just take photo and the app will run wikipedia for them. Moreover, it can be used to scroll through the photographs, learn more about the species, and also see which more species live nearby their villages.
