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
![Final prototype solution](/images/myenrolment/mac2.jpg)

### How can we redesign myEnrolment to better guide incoming CoCa Massey students through the unfamiliar process of choosing courses for the upcoming year?

## Background
myEnrolment is an online class registering system for Massey University that students must complete every year to register for courses for the following year.

## Problem
I found myself in tears just a few weeks before I embarked on my exchange to New Zealand - I spent a few hours trying to figure out how to register for my classes and I *still* couldn't figure myEnrolment out!

I met Keriana, a second year at Massey University College of Creative Arts (CoCa Massey), and found that she also had trouble completing myEnrolment each year. Both passionately disappointed about the lack of usability of myEnrolment, we set out to improve it.

In this case study I use New Zealand academic terminology:
- enrol = enroll
- paper/course = course
- timetable = schedule

#### Too many tabs
Students need to juggle three browsers to register for courses: one for myEnrolment, one for the course directory, and one for the timetable tool.

![myEnrolment](/images/myenrolment/oldmyenrolment2.png)
![Course directory and timetable](/images/myenrolment/directory-timetable.jpg)

#### Unclear purpose and confusing interface
The purpose of myEnrolment isn't clear. The progress tracker appears helpful, but sections like "Fees" and "Contact Details" confused me. I found myself overwhelmed by the information on each page and step of the process - and the instructions only being presented before the process began didn't help me either!

#### Too broad of an audience
CoCa Massey students have a specific degree structure for each year. Massey University has three campuses that span New Zealand, but all three use the same myEnrolment interface. CoCa Massey students have specific needs like understanding their degree structure that differ from the rest of the Massey campuses.

![CoCa Massey first year design degree structure](/images/myenrolment/structure.gif)

## Design Process Overview
Keriana and I redesigned myEnrolment through four rounds of iterative prototyping and user testing. We started out creating paper prototypes by physically cutting up sections from the printed Massey University course directory booklet, then progressed towards digital, clickable prototypes by user testing each iteration on Massey students and faculty.

![Wireframes](/images/myenrolment/sketches7.jpg)
![Four rounds of prototyping](/images/myenrolment/prototyping-rounds3.jpg)

## Design Considerations and Decisions
### Defining the Scope
When we first started our redesign, we had two main goals: allow students to register for their courses for the upcoming year and plan out future courses for their degree. From user-testing we realized that this scope and audience would be too large of a focus- an incoming first year doesn't have the same needs as someone ready to enter their fourth year.

#### Audience
- An incoming first year CoCa Massey student

#### User Goals
- Primary: Register for courses for their first year
- Secondary: Preview major options

### Structure
To help incoming CoCa Massey students navigate an unfamiliar interface and process, we learned from early prototypes and user testing that every single step should be simplified and that our interface should guide users through the process.

![An early paper prototype](/images/myenrolment/paper-proto2.gif)

To meet this need, we structured our interface as a series of steps: register for your Core Courses, then for your Electives, and so on. We found it necessary to break down each steps into even smaller tasks during user testing, so we incorporated a system where users can't move forward to their next task until they've read instructions and clicked an "OK" button.

To avoid overwhelming our users with new information and choices, we kept parts of the interface in focus and parts of the screen inaccessible by graying them out.

We also realized that our interface needed to provide the user with feedback as they interact with it - each time the user clicks or drags something, we made sure that our interface would respond back with pop-up tooltips, color changes, or reveals.

![Structure prototype progress](/images/myenrolment/layout2.png)

### Progress Bar
Because it was crucial to for our interface to guide our users through smaller steps, we incorporated and tested different progress bars.

We began with a linear checklist progress bar that we later changed into a progress bar implied by tabs - a choice we made to make the process feel less linear to encourage users to go back and play around with their course selection as they progressed through the interface and learned more about their first year structure.

In each iteration we also included a course outline that fills up with the user's chosen courses, which serves as another implied progress bar.

![Progress bar prototype progress](/images/myenrolment/progress.png)

### Drag and Drop

Our first two prototypes had radio boxes for users to choose courses from that would fill up their course outline in a different location. We found problems with this: users were looking at one part of the screen while making changes to another part of the screen, and having to mentally map this was confusing for our testers.

We changed our course selection into a drag and drop task to make sure users stayed focused on their current task.

![drag and drop paper prototype](/images/myenrolment/paper-proto-6.jpg)
![drag and drop digital prototype](/images/myenrolment/drag-and-drop.png)

### Previewing Major Options
A problem we wanted to address with myEnrolment was helping new CoCa Massey students understand their degree structure. We wanted to educate users on how their course selection would affect the major they choose during their second year.

Our early prototypes used a list of degree Major choices that would narrow down based on which Core Courses the user chose, but we changed this to be a course recommendation later on because we didn't know enough about the prerequisite system.

User testing helped us decide where this task should fit in the process, since we considered it a secondary goal. Our first prototypes included it at the end with the submission page, but we chose to keep it as an optional page that becomes accessible for the user to open up and come back to once the user chooses their four Core Courses.

![Major preview option](/images/myenrolment/majors.png)


### Course information
A major problem with the existing myEnrolment process is that it requires users to search for courses on an external website. To make this process more straightforward, we wanted to include course information within myEnrolment.

We quickly found that course descriptions weren't enough information for users to make informed decisions, so we incorporated pop-ups and accordian folds instead. We also included an example image of the work that past students created in these courses, as our audience would be taking primarily design studio courses.

![Paper prototyping in action](/images/myenrolment/paper-proto.gif)
![Progression of course descriptions](/images/myenrolment/dragdrop.png)

### Language
We noticed early on that Lorem Ipsum wouldn't cut it for our prototypes - language is an important aspect of a user's experience!

To make the class registration process less complex for our audience, we aimed for a balance between brief text and supportive language by including reminders that users could go back and make changes to their choices before and after submitting their myEnrolment. We also needed to be cognizant of consistency, as CoCa Massey had recently switched terms from "Papers" to "Courses".  

![Pop up "OK" example](/images/myenrolment/language.jpg)
![Paper prototype with notes on language](/images/myenrolment/6a.jpg)

## Final Solution
Our iterative process culminated in the following final prototype, where we present myEnrolment as a series of steps and guide students through it slowly.

Because of time constraints, we used a Bootstrap UI Kit when designing the final prototype because we wanted to focus on our changes to myEnrolment's usability rather than its presentation. If we had more time, Keriana and I would spend it designing our own components for the interface instead.

![Final prototype](/images/myenrolment/mac.jpg)

## Reflection
My biggest takeaway from this project is learning how important it is to understand the system that an interface exists in. A student's experience doesn't start with logging into myEnrolment and end with pressing the "Submit" button.

If Keriana and I continued to work on this project, I'd like to involve people at the CoCa Massey registrar to learn more about the registration process and find out exactly what happens before and after a student completes myEnrolment - how students get from an acceptance letter to myEnrolment, how prerequisites work, how Core Courses affect major choice - so that our interface could be more informed by the system it lives in.
