---
layout: post
title:  Breathing Visualizer
categories: interactive
type: "Case Study"
caption: ""
intro: ""
team: []
course: "Interactive Media II"
institution: "University of California, Davis"
year: 2017
thumbnail: thumbnails/thumb-breathing.gif
tools: ["Adobe Illustrator"]
languages: ["HTML", "CSS", "JavaScript"]
---

![Final prototype](/images/breathing/demo2.gif)

### How can I design a digital interface that helps people take control of their anxiety?

## Background
I wanted to create something that helped people experiencing anxiety by making them aware of their physical symptoms, including their heart and respiratory rate.

## Comparative Research
I started searching for ways that I could read in a user's heart rate and respiratory rate, and how I could use that data to help people take control of their anxiety.

[eXHaLeR](http://xhalr.com/) is an online breathing exercise application that guides users through breathing techniques with simple "Inhale"/"Exhale" instructions accompanying a calming visualization.

The NeuroSky MindWave Mobile is an EEG device. This [android application](http://store.neurosky.com/products/brainwave-visualizer-android) creates graph visualizations based on data read from the device.

![Comparative research collage](/images/breathing/precedents.jpg)

## Exploration
During my research I found stethoscopes that could record heart rate data, but cost constrains lead me to explore other ways of reading in data from people. Playing around with the [p5.js-sound library](https://p5js.org/reference/#/libraries/p5.sound), I realized I could use audio input from a small headphone microphone to record "breathing" - specifically when people exhale. Using with the p5.js-sound library, I found that I could manipulate shapes using the audio input of people exhaling.

![p5-js - prototype 1](/images/breathing/proto2.jpg)

## Site Map, User Flow, and Wireframes
I initially called this interface "Visualizing Anxiety". I wanted people to notice their breathing patterns while anxious, complete a breathing exercise, then notice their breathing patterns again. Constraints, such as the lack of being able to measure heart rate and only being able to measure exhales, lead me to narrow the scope of this project later on.

The following site map, user flow, and wireframes all represent the ideal direction for this project if my headphone microphone solution could measure more data more accurately.

![Site map](/images/breathing/site-map.gif)

![User flow](/images/breathing/user-flow.gif)

![Wireframes 1](/images/breathing/mockup1.gif)
![Wireframes 2](/images/breathing/mockup2.gif)

![Wireframes 3](/images/breathing/mockup3.gif)

![Primary navigation wireframe](/images/breathing/navigation.gif)

## Paper Prototyping
I created paper prototypes and had users test these with the headphone microphone.

A key insight from the first round of paper prototypes was the connection between anxiety and timers. I included a timer that counts down as part of a breathing exercise, but a user expressed that she would perceive the countdown negatively. We discussed creating a visual counter (such as a bar that fills up) as an alternative.

<div markdown="1" style="display: flex; justify-content: center;">
![Paper prototyping example](/images/breathing/prototyping4.png)

![Paper prototyping example](/images/breathing/prototyping3.png)
</div>

## Digital Prototype
I created the following stylistic mockups, and decided to go with the darker interface as I found it more visually soothing.

![Style tile and developing a visual style](/images/breathing/styletile.jpg)

![Final prototype demonstration](/images/breathing/proto1.jpg)

# Reflection
Without time constraints, I would like to revisit this project and expand on its visual solution. I would play more with the p5.js-sound library to create a more interesting, soothing visualization that accompanies the breathing. I'd also like to implement the breathing exercise as I didn't get a chance to with this project.
