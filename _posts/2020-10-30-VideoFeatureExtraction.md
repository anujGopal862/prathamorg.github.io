---
layout: post
title: Engagement Analysis of Pratham Open School Videos
tags: [video feature extraction]
---

**Objective:** Understanding the effect of video features such as colors, objects, persons on the viewership of Pratham Open School videos on Youtube

**Concept:** Using Computer Vision, identify objects, colors and number of persons in Pratham Open School videos. This data can be associated with the number of views of these videos on Youtube to see which video features improve the number of views.

**Project Plan:**

| Step | Know-how | Status |
| --- | --- | --- |
| Extract Pratham Open School Videos from Youtube |    | Done |
| Script for extraction of colors data from POS youtube channel |    | Done |
| Script to identify objects in POS videos  | Video Feature Extraction |Done |
| Running color detection and Object detection scripts on all POS videos consolidation of data  | Video Feature Extraction |Not started |
| Finding corelation between colors, objects and number of views | Video Feature Extraction |To be done |
| Create a dashboard using the data generated through the video feature extraction along with the video number of views from Youtube | Data Visualization | Not Started |

**Details:**

Pratham Open School is a Youtube channel with videos on various educational topics. To ensure better outreach of these videos, it is important to understand how the video features affect its viewership on Youtube. This can be achieved using video feature extraction technique.

Object identification is one of the feature extraction method that labels the objects present in the video. Other features that can be extracted are the colors present in the video and the number of persons. By generating data on these video features of the Pratham Open School videos, we can visualize the relationship between these videos features and the Youtube viewership. The insights derived from these visualizations can help strategize modifications in the videos to improve their outreach on Youtube.

**Progress** :

- A demo of color identification in videos using YOLO algorithm and OpenCV library in Python has been performed
