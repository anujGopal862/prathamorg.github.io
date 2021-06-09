---
layout: post
title: Automated Diagnostic Tool to measure Numeracy Level among children
tags: [Speech Recognition]
---

**Objective** : Create an automated diagnostic tool to measure Numeracy Levels in Children 

**Concept** : Developing an Android-app based tool integrated with an ML model that would be trained on ASER Numeracy Data.

**Numeracy Level**:
This tool can be utilized as a standalone testing tool and as a part of adaptive learning solutions for basic numeracy. The tool will accept audios of students reading basic numeracy questions like Identifying Single Digit and Double Digit Numbers and doing basic mathematical problems like two digit substraction and three digit division by a single digit and will automatically provide numeracy proficiency of children.

**Issues addressed:** Basic oral evaluation of fundamental numeracy skills (identification of Single Digit and Double Digits) will pave the way for teachers to provide content to children according to the child's level. This would help in the implemetation of Teaching at the Right Level approach. 


**Details** : Automated assesment of Numeracy levels in children would aid evaluation of learning outcomes of student in the area of mathematics and basic numeracy. An automated tool can transform automated assessment of numeracy levels amongst individual and groups of children at scale.

Numeracy Level:
For the assesment of numeracy levels of children, the model will consume audio samples of a child and predict his/her basic numeracy. The numeracy levels would fall in the following categories (Beginner, Single Number recognition(0-9), Double Number recognition(11-99), two digits number subtraction with borrowing, three digit number division by one digit number).The features used for classification to these categories would be the correctness of the math problems and the identification of the correct number. 

**Project Plan:**

Numeracy Level:

| Step | Know-how | Status |
| --- | --- | --- |
| An android app to collect audio data to be used for testing and training the ML model | Android Development | Done |
| Develop web-portals to annotate the audios and get all the data annotated | Web Development | Done |
| Audio sample filtering - remove background noise and remove silences | Audio-signal processing | In-Progress |
| Calculation of accuracy of Google STT and Azure STT on Numeracy Data  | Speech Recognition | Completed |
| Research on Acoustic models for number identification from audios  | Speech Recognition | In progress |
| Assess the numeracy level of the child by comparing the Ground Truth with the child's answers | - | Not Started |
| Conceptualize and integrate the designed model with an Android app (Deployment) | Android Development | Not Started |

**Progress: **

- Data Collection: An Android app has been designed to collect human evaluated training data. This app is being used in different villages of India (Maharashtra, Uttar Pradesh and Rajasthan) to collect audio samples of children reading out different levels of text (letter, word, paragraph and story), numbers (two digit, single digit) and solution to basic numeric problems(subtraction and division) along with the proficiency level marked by the evaluator.
- Data Annotation: The process of manually annotating the numeracy audios and transcribing the reading audios is in process using the web-portals. The interns are actively working on it. Dashboards have been developed to monitor the progress of annotations and transcriptions and assess quality of the data.
- Speech to Text (Numeracy): The accuracy of Google and Azure Speech to Text tools have been tested for our dataset, however both tools did not perform well for both English and regional languages. Several machine learning models for speech recognition have been explored to train on our dataset to get better accuracy. The maximum accuracy achieved so far is 76% using Tensorflow speech commands model. This step is still in progress.
- Speech to Text (Numeracy): Since the accuracy of Google and Azure STT is low. Research to implement acoustic models for number identification from audio files is ongoing

Next Steps:
- Complete annotation for the collected data.
- For numeracy level, we will work on improving quality of the audios by removing noise and silence. Further we will try to improve the accuracy of the models by using more good quality training data. Once we achieve accuracy of > 90%, this model will be deployed on the app.
- After the ML models are developed, these will be deployed on an Android App
