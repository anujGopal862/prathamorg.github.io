---
layout: post
title: Automated Assessment of Personal Interviews
tags: [Computer Vision,Video Feature Extraction,Speech Recognition, Natural Language Processing]
---

**Objective** : To provide automated feedback on personal interview videos/audios of youth

**Concept** : Developing an android app that will take videos of personal interviews by youth, extract features from it, and generate automated feedback on their performance using Machine Learning models

**Issues addressed:**   Verbal along with non-verbal cues frequently reveal the intention of the youth and reflect his/her emotional reactions to and knowledge of any idea/topic. These can be used to evaluate their inter **-** personal skills needed to excel in their career and workplace. Without an automated evaluation tool, it is difficult for instructors/guide to identify these cues and provide guidance to the youth according to their need.

**Features List:**

| **Transcription of Speech** | **Audio** | **Video** |
| --- | --- | --- |
| Sentiment Analysis | Confidence detection | Eye contact |
| Grammar Mistakes |  | Smile detection |
| Answer Length |  | Hand gesture |
| | | Body posture |

**Project Plan:**

| Step | Know-how | Status |
| --- | --- | --- |
| Collect data of video and audio personal interview of youth for training of ML models |  | Done |
| Pipeline to convert video files to audio files, transcription of audio files to provide input to the NLP code  |  Automatic Speech Recognition | Done |
| Extracting features from the video transcriptions (Sentiment analysis, Language Proficiency) | Natural Language Processing | completed |
| Audio feature extraction (Confidence Detection) | Audio Feature Extraction | Features extracted, models indentified for confidence detection |
| Video feature extraction (Smile detection, hand gestures, eye contact, body posture) | Video Feature Extraction | completed |
| Web app design and functionality to submit video for processing  | Web app development | completed|
| Code Integration of different modules of the Web app  | App Integration | In progress|
| Deployment and Testing of Web app  | App Integration | In progress|
| Conceptualize and integrate the designed ML model with an Android app (Deployment) | Android Development | Not Started |

**Details** :

Personal Interviews are important part of hiring process. To improve employability, youth should be mentored to improve their interview skills. Youth need a platform to get feedback on how they are doing and where and how can they improve. Also, with the right tools, talents can be identified at scale and then connected to right opportunities.

Automated Assessment system for personal interviews will be highly customizable, trustworthy, secure, and can be accessed in multiple devices. It will prepare students with life&#39;s skills to excel in their careers and work environment. This app is a great solution for the scale at which Pratham works. Evaluation &amp; grading of personal interviews will become easy for the videos via mobile app.

**Progress** :

- Data Collection: Data of personal interviews in form of videos and audios have been collected in English, Hindi, Marathi

Total videos: 56 (Videos: 22, audios:33)

- Transcription: A pipeline to convert video files to audio files, transcript generation using Azure Speech to text has been created
- Text Features: Sentiment Analysis is performed on the transcriptions using various dictionary-based methods to get a score of positive/negative sentiment in the interview answers
- Video Features: Smile detection, Eye contact detection , lip bite detection, face obstruction detection has been completed using computer vision models and thresholds have been finalized
- Web app creation for video submission and report generation has beeen completed
- Integration of various modules is in progress
- Initial deployment to AWS was done
- Final deployment and testing to be done in coming days
