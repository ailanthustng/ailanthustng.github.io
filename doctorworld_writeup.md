---
layout: inner
title: DoctorWorld Internship
permalink: /internships/doctorworld/
---

# DoctorWorld Internship

##### _Duration: 01 Jun - 31 Jul 2020_

### Software Engineer Intern

---

## Company Information

DoctorWorld's mission is to make heathcare more convenient, accessible and affordable through technology. As a digital platform provider, DoctorWorld connects patients to a trust network of healthcare providers via a secure and integrated mobile application. DoctorWorld provides services such as:

- Teleconsultation: Video-calling a doctor
- eQueue: Acquiring a queue ticket at clinics
- Maintaining users' personal health records
- Provision of health and travel advisories
- Other healthcare services

<br>
<div class="fade-rule"></div>
<br>

## Internship Description

<br>

### What I worked on

During my internship, I worked on one major project - the Telehealth Kiosk, which were to be stationed in foreign worker dormitories during the COVID-19 pandemic. Within this project, I worked on three parts:

1. Sourcing of Android tablets and subsquently, the imagining and designing of the kiosk prototypes for deployment.

   ![Kiosk Prototype v1 scaled](/img/internships/kiosk_example_v1.png "Kiosk Prototype v1")

   _Kiosk Prototype v1_

   ![Kiosk Prototype v2 scaled](/img/internships/kiosk_example_v2.png "Kiosk Prototype v2")

   _Kiosk Prototype v2_

2. Setting the tablet up and locking the RafflesConnect web application in Kiosk Mode using the Android Mangement API to prevent unauthorised usage or abuse of mobile data.

3. Redesigning and refactoring of the existing RafflesConnect web application to provide a better user interface and user experience for use on tablets.

<br>

The techniques I utilised to solve the above problems were:

1. I brainstormed on how kiosks should be used, using a user profile of a foreign worker who wanted to make a teleconsultation call. This helped me in imagining how the kiosk should be presented in the best and most user friendly method.

   ![Kiosk Prototype](/img/internships/kiosk_prototype.jpg "Kiosk Prototype")
   _An example of the actual kiosk prototype_

2. I was able to understand the API documentation, which helped me greatly in being able to set up and lock the purchased Android tablets into the Kiosk Mode. Within the Kiosk Mode, users are only able to use the web application provided (RafflesConnect) and nothinng else. They would also be unable to access the settings. Subsequently, policies can be pushed to the tablets to make changes as to how these tablets are used.

3. Having used React before, I was able to understand and refactor the existing code base to fit the new design with relative ease. With my limited knowledge of design and the available React components, I was happy to be able to chip in ideas to the redesign of the existing web application.

   ![Ongoing Call](/img/internships/ongoing-call.png "Ongoing Call")
   _Left: Existing design. Right: New design of Ongoing Call page. (Screenshot was captured during the development phase, hence there was no on-going call)_

<br>

### Working with different teams

1. For the sourcing of tablets and designing of the kiosk, I mainly worked with my supervisor, Charles. The process was as such: I would prototype kiosk designs and pass it to Charles. Charles would then give his input on the pros, cons, what to look out for and how to improve the general design of the kiosk. This went on for roughly 4 iterations.

2. I was tasked by the CTO Daniel to figure out how to remotely manage an Android tablet, and my work here was mostly an individual process consisting of research and testing.

3. Our Tech Lead Indra provided me with the existing code base, and from then on I was given the responsibility of refactoring the code on my own. However, I still remained in contact with Indra as I went about refactoring the code, asking questions ranging from proper methods of coding to design-based questions. I also worked with another supervisor, Bangun, who was the Frontend Engineer. He guided me through many procedures, such as the deployment pipeline for development and production. Next, I also worked with Phong, a mobile developer to do the testing of the new web application, such as testing on different devices, and whether or not the user interface worked well, etc.

<br>
<div class="fade-rule"></div>
<br>

## Reflections

<br>

### What I Learned

I would categorise my learnings into three main points:

1. **Code Structure**

   - Having access to the code base allowed me to dive deep into industry-level of code structuring - how components are organised and structured, the standardisation of how functions are written, etc.

2. **React and CSS styling**

   - CSS styling was one of my weakest points. However, I was able to learn much from the existing code base and was even able to extend my knowledge to styling my own components to fit the new design.

   - Insight on the many React libraries and APIs out there for use - NRIC validation, Twilio, react-redux, react-device-detect, etc. It was amazing to see how these different libraries came together in a working product to carry out its functions.

3. **Structure of a startup**

   - As someone who is interested in working in a startup, it was interesting to see the structure of one, whereby the hierarchy is rather flat, everybody chipping in to each other's work, helping one another out, having design workshops that were available for everyone to attend and learn from together.

   - Having stand ups also aided in being able to learn off from one another. Merely listening to what others were working on or how they were going about doing their work gave me insight on the workflow of the various concurrent projects, as
     well as the thought processes of each individual. All these helped me to better plan the way I work and how I work.

<br>

### Challenges faced

The challenges I faced were mainly technical:

1. **Viewheight (vh) vs window.innerHeight**

   - The existing code was styled using `100vh`, which in practice, worked fine on desktop devices. However, on mobile devices, this caused a white box at the bottom due to overflow.
   - This usually happens when multiple components were styled using `vh`, affecting the overall height of the page.
   - Using the React Developer Tools, I figured out which components were causing the problem and fixed it by using `window.innerHeight` to get the height of the screen and passed it down to the styling of the component.

2. **iOS vs Android**
   - An extension of the above point. What I learnt here was that iOS devices have different inner window heights as compared to Android devices.
   - For example, Android devices do not consider the navigation bar as part of the screen height, while iOS devices do.
   - The React library `react-device-detect` helped me out here as I could conditionally style the components for different operating systems.

<br>
<div class="fade-rule"></div>
<br>

## Experience with Remote Working

<br>

We had standups every morning at 11am, which was moved forward to 10am halfway through my internship. The standups were sometimes coupled with presentations (such as on competitor apps, the direction of the company, etc).

The standups were particularly interesting as there were many things that I could learn from, as I have mentioned above. Standups also gave the opportunity for everyone to see each other, especially since this was a very remote team with many people working from various countries. I think it was particularly heartwarming to see how everyone still managed to click with one another, making jokes and laughing together despite the challenges faced in these unprecedented times.

![Remote Internship](/img/internships/remote-working.png "Working remotely")

The presentations were also helpful in giving everyone a good idea of what everyone was working on individually or as a group. Competitor applications were also presented to give everyone a heads up on what kind of market we were venturing in.

In addtion, some presentations were about the designing of the application (mainly the Dashboard), and I think it was amazing to see the industrial workflow of producing an application in action - from research, all the way to production (how user feedback was taken in and worked upon to create an application with better UI/UX, which was subsequently built by the engineers)

Seeing as how the COVID-19 situation was evolving, I think there was no better way to run the company than by doing it remotely. However, personally I feel that nothing would be able to replace being able to sit down together in an office and work together, learning from one another and optimising work efficiency. It was a waste to be unable to work in the office. However, overall the experience was still great!

<br>
<div class="fade-rule"></div>
<br>

## Closing words

Being my first internship, it gave me an idea on what I am interested in, which is software engineering. I've always wanted to work in a startup and this has really been an eye-opening experience and a stepping stone for me.

Yet I know I am still far from there. I am still lacking in many aspects - not working hard enough, having to gain more understanding and knowledge on the backend side of software engineering, as well as having many things to polish up on the frontend side as well.

Overall, the internship gave me an idea on which areas to improve for myself and also confirmed my desire to work in a startup. It also solidified my interest in pursuing a specialisation in software engineering.

Moving forward, I really need to brush up my skills and overall improve my attitude on learning and working, and I hope to be able to put everything I learnt into future use, taking on more internships and software engineering opportunities.
