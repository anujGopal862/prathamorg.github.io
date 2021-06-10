---
layout: post
title: Musical Skills Scoring
tags: [Audio Feature Extraction]
---

**Objective** : To identify and score children on the basis of their musical skills using Audio based Deep Learning Models, and to connect them with relevant opportunities

**Concept** : The musical skills in a child are mostly natural. Identifying those skills at an early age would be advantageous as the child can be provided with opportunities to excel in the field of their interest and pursue a career in music

**Issues addressed:**  Children often do not realize their musical skills at an early age, and if not provided with proper guidance, face difficulty in understanding the opportunities that are available in this field. With detailed scores and expert feedback, a child is more likely to understand and excel in music, which can be achieved through Audio based Deep Learning techniques using different audio files of children singing songs.

**Details** : Children below 10 years of age live in a crucial stage of neurodevelopment. Understanding the natural musical ability is necessary to characterize them and guide them towards a better career decision. It is important to devise processes using the latest technological advancements that could quantify, to an extent, the different factors that constitute musical perception of a child. 
According to study, children with specific language impairment (SLI) exhibit deficits in rhythmic cues in speech and music, and dyslexic children may have difficulties discriminating strong pitch changes that are easily discriminated by normal readers.

The initial step would be to understand the metric that would define the musical skills as closely as possible. The musical skills of a child would be scored on the following metrics:

Melody - The tune of the music, made up of collection of tones

Pitch – The frequency of the sound, making it a “High” or a “Low” pitch

Timbre – Tone color that distinguishes different music produced

Rhythm – Pattern of music on the scale of time

Loudness – Amplitude of sound or the magnitude 

Every factor mentioned above will be quantified, and an overall score will be generated based on an aggregation of all the factors. Machine Learning models will be trained on a large collection of audio-based data collected from the children. The web/app that we are building can be used by children to upload their song and get a musical score and expert feedback for their performance. 

**Quantification** 

Melody

A melody can be statistically broken down based on the occurrence of each tone. The statistical breakdown of a typical melody looks like this: 

G4 – 8/20 = 40%

A4 – 2/20 = 10%

B4 – 2/20 = 10%

C5 – 6/20 = 30%

D5 – 2/20 = 10%

Here, G4,A4,B4,C5 and D5 are the names of the musical tones and we also have the percentage and frequency of occurrence of each musical tone. Based on the precision of the audio sample, we can assign a number for each record of how accurately a child has been able to capture the melody.

Pitch

Pitch is the frequency of a musical tone. Each musical tone can be labelled and cross-checked with the audio sample received from a child. The statistical number will then represent the exactness of frequency of the observed audio compared to the original labelled audio sample. The idea is that there are higher and lower sounds, and that there is some way to measure the distance between them. The frequency or the pitch of a sound is measured in Hertz(Hz).



Timbre

As it is slightly difficult to quantify timbre of a sound, we can label the audio sample based on classes that we define for difference in timbre. A sound coming from violin can be labelled “Violin”, while a choir song can be labelled “Choir”. The machine will train based on classification problems to differentiate the tone color or timbre.

Rhythm

Rhythm is a pattern in which musical notes flow. Since it is measured on the scale of time, it is easier to quantify and assess rhythmic capabilities of an individual. A penalty score would be given every time the beat is missed and thus, we can generate a statistical number for every audio sample that we collect.

Loudness

Loudness of sound is measured in decibels (dB). This is actually a measure of intensity, which can be measured using mathematical formula involving intensity of a sound and power ratio. On an average, doubling the intensity usually results in a difference of 3 dB. 

**Project Plan:**

| Step | Know-how | Status |
| --- | --- | --- |
| Data collection - collect singing audios from children (labeled data) | Android Development | In-Progress |
| Develop and test Deep Learning Models to score musical skills of a child based on their singing audio | Machine Learning and Deep Learning Algorithms | Not Started |
| Conceptualize and integrate the designed ML model with an Android app. To make API call to get detailed musical score of a child (Deployment) | Android Development | Not Started |

