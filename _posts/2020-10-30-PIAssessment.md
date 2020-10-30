---
layout: post
title: Automated Assessment of Personal Interviews
tags: [video feature extraction]
---

**Objective** : To provide automated feedback on personal interview videos/audios of youth

**Concept** : Developing an android app that will take videos of personal interviews by youth, extract features (video, audio and text) from it, and generate automated feedback on their performance using Machine Learning models

**Issues addressed:**   Verbal along with non-verbal cues frequently reveal the intention of the youth and reflect his/her emotional reactions to and knowledge of any idea/topic. These can be used to evaluate their inter **-** personal skillsneeded to excel in their career and workplace. Without an automated evaluation tool, it is difficult for instructors/guide to identify these cues and provide guidance to the youth according to their need.

**Features List:**

| **Text** | **Audio** | **Video** |
| --- | --- | --- |
| Sentiment Analysis | Pitch detection | Eye contact |
| Grammar Mistakes | Pause duration | Smile detection |
| Answer Length | Emotion Detection | Hand gesture |
| Automated Answer Assessment |
 | Body posture |

**Project Plan:**

| Step | Know-how | Status |
| --- | --- | --- |
| Collect data of video and audio personal interview of youth for training of ML models |
 | Done |
| Transcribe the videos/audios using Speech to Text tools and human transcribers and translate the non-English transcriptions |
 | Done |
| Audio sample filtering - remove background noise and speaker diarization to extract the interviewee&#39;s part | Audio-signal processing | In-Progress |
| Text feature extraction (Sentiment analysis, Language Proficiency, Emotion Detection, Automated Assessment of Answer) | Natural Language Processing | In-Progress |
| Audio feature extraction (Pitch detection Audio emotion, Pause duration) | Audio Feature Extraction | Not Started |
| Video feature extraction (Smile detection, hand gestures, eye contact, body posture) | Video Feature Extraction | In-progress |
| Develop ML model to predict the interview performance based on the text, audio and video features extracted | Machine Learning | Not Started |
| Conceptualize and integrate the designed ML model with an Android app (Deployment) | Android Development | Not Started |

**Details** :

Personal Interviews are important part of hiring process. To improve employability, youth should be mentored to improve their interview skills. Youth need a platform to get feedback on how they are doing and where and how can they improve. Also, with the right tools, talents can be identified at scale and then connected to right opportunities.

Automated Assessment system for personal interviews will be highly customizable, trustworthy, secure, and can be accessed in multiple devices. It will prepare students with life&#39;s skills to excel in their careers and work environment. This app is a great solution for the scale at which Pratham works. Evaluation &amp; grading of personal interviews will become easy for the videos via mobile app.

**Progress** :

- Data Collection: Data of personal interviews in form of videos and audios have been collected in English, Hindi, Marathi and Kannada

Total videos: 56 (Videos: 23, audios:33)

English: 11, Hindi:32, Marathi:9, Kannada: 4

- Transcription: The Personal Interview videos/audios have been converted to text using Google/Azure Speech to Text and corrected by human transcribers and non-English transcriptions have been translated to English. Also, the interviewee and interviewer part has been separated.
- Text Features: Sentiment Analysis is performed on the transcriptions using various dictionary-based methods to get a score of positive/negative sentiment in the interview answers
- Video Features: Smile detection using Computer Vision is in process
