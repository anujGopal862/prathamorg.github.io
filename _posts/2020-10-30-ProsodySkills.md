---
layout: post
title: Assessment of Prosody Skills
tags: [audio feature extraction]
---

**Objective:** To measure prosodic skills of children&#39;s oral reading

**Concept:**  To develop test tools for the effective and comprehensive assessment of prosody of children&#39;s oral reading in English as well as Indic languages.

**Issues addressed:**  Accurate perception and production of the ranging aspects of prosody are a significant component of successful social communication. The need of trained evaluators for the same, puts a limit on the number of children that can be evaluated. Without a diagnostic evaluation it is difficult for teachers to provide learning content according to the child&#39;s need.

**Project Plan:**

| Steps | Know-how | Status |
| --- | --- | --- |
| Project Conceptualization - which prosodic skills to look for and what should be the labels | Prosodic Skills Expert | Done |
| An android app to collect labeled dataset to be used for testing and training the ML model | Android Development Done |
| Audio sample filtering - remove background noise to extract only child&#39;s voice | Audio-signal processing | Done |
| Develop and test ML Model to take filtered audio samples and corresponding labels as input and predict the prosodic skills and areas of improvement | Machine Learning and Deep Learning Algorithms | In Progress |
| Conceptualize and integrate the designed ML model with an Android app (Deployment) | Android Development | Not Started |

**Details:**  Pitch, duration, and stress are the phonetic correlates of prosody. The physical correlates of these features are the speech&#39;s fundamental frequency (F0), syllable duration, and intensity, respectively. Phonological correlates of prosody include the variations in pitch, length, and loudness that are produced in speech for conveying subtle changes in the meaning of spoken messages independent of words and grammatical order. In other words, stress and intonation are used to convey the grammatical, affective, and pragmatic functions of language. We aim to design a model in which the functions of prosody are identified at the grammatical and affective levels of communication.

The grammatical functions of prosody include:

(a) determining the boundaries of phrases, clauses, or sentences, particularly when there is ambiguity (e.g., /FRUIT, SALAD and MILK/ vs. /FRUIT-SALAD and MILK/) and

(b) hesitation in speech if any, whether the child is reading like a sentence or a string-of-words

(c) how expressive is the child while reading

(d) pace of reading, whether child is reading too fast or too slow

The affective function of prosody is the use of prosodic features such as pitch contour, pauses, and word stress to express the speaker&#39;s emotions and attitudes. Prosodic patterns convey different emotions. Happiness, for example, is characterized by a fast speaking rate, rising pitch, high variability, and fast voice onsets, and sadness is nearly the opposite. Such models could help teachers identify which students are making adequate progress.
