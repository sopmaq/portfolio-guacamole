---
layout: post
title:  myEnrolment Redesign
categories: interaction
type: "Case Study"
caption: "Prototyping and wireframing a better way for design students to register for classes."
intro: "This is a redesign of MyEnrolment at Massey University."
team: ["Keriana Salisbury"]
course: "Interaction and Interface"
institution: "Massey University, New Zealand"
year: 2017
thumbnail: thumbnails/thumb-myenrolment2.gif
prototyping: ["Figma", "Adobe Illustrator", "Invision"]
---
![Screen during interaction](/images/myenrolment/mac2.jpg)

## Problem
A few weeks before I embarked to my exchange in New Zealand and I was in tears. myEnrolment, the online course registration tool, was confusing.

Keriana, a second year at Massey University College of Creative Arts (CoCa Massey), also had issues understanding how to complete myEnrolment. Every year she had to fill the form while searching for classes on a separate course directory *and* a separate timetable tool.

**We wanted to redesign myEnrolment to guide incoming CoCa Massey students through the unfamiliar process of choosing courses for the upcoming year.**

## What is myEnrolment?
myEnrolment is an online class registering system for Massey University that students must complete every year to register for courses for the following year.

In this case study I use New Zealand academic terminology:
- enrol = enroll
- paper/course = course
- degree programme = degree
- timetable = schedule

#### Existing Problems
Students need to juggle three browsers to register for courses: one for myEnrolment, one for the course directory, and one for the timetable tool.

![Screen during interaction](/images/myenrolment/oldmyenrolment2.png)
![Screen during interaction](/images/myenrolment/directory-timetable.jpg)

The purpose of myEnrolment isn't clear. The progress tracker appears helpful, but sections like "Fees" and "Contact Details" confused me.

CoCa Massey students have a specific degree structure for each year. Below is the structure for the first year.

![Screen during interaction](/images/myenrolment/structure.gif)

Massey University has three campuses that span New Zealand, but all three use the same myEnrolment interface. CoCa Massey students have specific needs like understanding their degree structure that differ from the rest of the Massey campuses.

## Design Process Overview

Our final solution is the culmination of four rounds of iterative prototyping and user testing. We started out creating paper prototypes by physically cutting up sections from the Massey University course directory booklet, and progressed towards digital, clickable prototypes by user testing each iteration on Massey students and faculty.

![Screen during interaction](/images/myenrolment/sketches7.jpg)
![Screen during interaction](/images/myenrolment/prototyping-rounds3.jpg)

## Design Considerations and Decisions
#### Defining the Scope

When we first started our redesign, we had two main goals: allow students to register for their courses for the upcoming year and plan out future courses for their degree. From user-testing we realized that this scope and audience would be too large of a focus- an incoming first year doesn't have the same needs as someone ready to enter their fourth year.

Audience
- An incoming first year CoCa Massey student

User Goals
- Register for courses for their first year
- Preview major options

#### Structure
To help incoming CoCa Massey students navigate an unfamiliar interface and process, we learned from early prototypes and user testing that every single step should be simplified and that our interface should guide users through the process.

To meet this need, we structured our interface as a series of steps: register for your Core Courses, then for your Electives, and so on. We found it necessary to break down each steps into even smaller tasks during user testing, so we incorporated a system where users can't move forward to their next task until they've read instructions and clicked an "OK" button.

To avoid overwhelming our users with new information and choices, we kept parts of the interface in focus and parts of the screen inaccessible by graying them out - a decision we incorporated in later prototypes that we found successful.

We also realized that our interface needed to provide the user with feedback as they interact with it - each time the user clicks or drags something, we made sure that our interface would respond back with pop-up tooltips, color changes, or reveals.

![Screen during interaction](/images/myenrolment/paper-proto2.gif)

![Screen during interaction](/images/myenrolment/layout2.png)


#### Progress Bar

Because it was crucial to for our interface to guide our users through smaller steps, we incorporated and tested different progress bars.

We began with a linear checklist progress bar that we later changed into a progress bar implied by tabs - a choice we made to make the process feel less linear to encourage users to go back and play around with their course selection as they progressed through the interface and learned more about their first year structure. We also used a course outline that fills up with the user's chosen courses, and also serves as another implied progress bar.

![Screen during interaction](/images/myenrolment/progress.png)


#### Drag and Drop

Our first two prototypes had radio boxes for users to choose courses from that would fill up their course outline in a different location. We found problems with this: users were looking at one part of the screen while making changes to another part of the screen, and having to mentally map this was confusing for our testers.

We changed our course selection into a drag and drop task to make sure users stayed focused on their current task.

![Screen during interaction](/images/myenrolment/paper-proto-6.jpg)
![Screen during interaction](/images/myenrolment/drag-and-drop.png)


#### Previewing Major Options

A problem we wanted to address with myEnrolment was helping new students understand prerequesites and how their course selection would affect the major they choose during their second year. Our early prototypes used a list of major choices that would narrow down based on which Core Courses the user chose, but we changed this to be a degree recommendation later on.

User testing helped us decide where this task should fit, since it wasn't one of the key steps to registering for classes. Our first prototypes included it at the end with the submission page, but we chose to keep it as an optional page that becomes accessible for the user to open up and come back to once the user chooses their four Core Courses.

![Screen during interaction](/images/myenrolment/majors.png)


#### Course information
A major problem with the existing myEnrolment process is that it requires users to search for courses on an external website. To make the course regristration process more straightforward, we wanted to include course information to be available in our interface.

We started out with course descriptions next to their name, but we noticed that it wasn't enough information for people to make informed decisions. In the course selection area, we tried pop ups and later decided to use accordian folds. We also included an example image of the work that past students created in these courses, as our audience would be taking primarily design studio courses.

![Screen during interaction](/images/myenrolment/paper-proto.gif)
![Screen during interaction](/images/myenrolment/dragdrop.png)

#### Language

We noticed early on that Lorem Ipsum wouldn't cut it for our prototypes - language is an important aspect of a user's experience!

To make the class registration process less complex for our audience, we aimed for a balance between brief text and supportive language by including reminders that users could go back and make changes to their choices and that their course registration could be changed after they submitted it. We also needed to be cognizant of consistency, as CoCa Massey had recently switched terms from "Papers" to "Courses".  

![Screen during interaction](/images/myenrolment/language.jpg)
![Screen during interaction](/images/myenrolment/6a.jpg)

## Final Solution
Our iterative process culminated in the following final prototype, where we present myEnrolment as a series of steps and guide students through it slowly.

Because of time constraints, we used a Bootstrap UI Kit when designing the final prototype because we wanted to focus on our changes to myEnrolment's usability rather than its presentation. If we had more time, Keriana and I would spend it designing our own components for the interface instead.

![Screen during interaction](/images/myenrolment/mac.jpg)

[Download PDF](/images/myenrolment/myenrolment-demo.pdf)


## Reflection
My biggest takeaway from this project is learning how important it is to understand the system that an interface exists in. A student's experience doesn't start with logging into myEnrolment and end with pressing the "Submit" button.

If Keriana and I continued to work on this project, I'd like to involve people at the CoCa Massey registrar to learn more about the registration process before and after a student completes myEnrolment - how students get from an acceptance letter to myEnrolemnt, how exactly prerequesites work, how Core Courses affect major choice - so that our interface could be more informed by the system it lives in.
