---
title: CS 4803/8803 3DU Syllabus
excerpt: Details you need to know
permalink: /syllabus/
layout: single
---

<!-- TOC -->

- [1. Course Description](#1-course-description)
    - [1.1. Course Expectations expanding on what is in Banner](#11-course-expectations-expanding-on-what-is-in-banner)
    - [1.2. VR Displays](#12-vr-displays)
- [2. Course Goals](#2-course-goals)
- [3. Required Textbooks](#3-required-textbooks)
- [4. Grading](#4-grading)
    - [4.1. Exams](#41-exams)
- [5. Homework Assignments](#5-homework-assignments)
    - [5.1. Academic Integrity, Collaboration and Web Resources](#51-academic-integrity-collaboration-and-web-resources)
    - [5.2. Use of Code You Did Not Write Yourself](#52-use-of-code-you-did-not-write-yourself)
    - [5.3. Use of Media and Text you Did Not Create Yourself](#53-use-of-media-and-text-you-did-not-create-yourself)
    - [5.4. Late Policy](#54-late-policy)
- [6. Grad Project for CS8803](#6-grad-project-for-cs8803)
    - [6.1. Human Subjects Training](#61-human-subjects-training)
- [7. Attendance](#7-attendance)
- [8. Accommodations for Students with Disabilities](#8-accommodations-for-students-with-disabilities)
- [9. Anti-Harassment Policy](#9-anti-harassment-policy)
- [10. Student Illness or Exposure to Covid-19](#10-student-illness-or-exposure-to-covid-19)
- [11. CARE Center, Counseling Center, Stamps Health Services, and the Student Center](#11-care-center-counseling-center-stamps-health-services-and-the-student-center)
- [12. Contacting the Instructor and TAs](#12-contacting-the-instructor-and-tas)

<!-- /TOC -->

# 1. Course Description

This class will cover the design and implementation of 3D user interfaces on a variety of devices, from desktops and laptops to phones and tablets to head-worn AR and VR displays. The primary focus will be immersive 3D interfaces and interactions. Topics will include the history of 3D UIs and VR, 3D applications, design and implementation of interaction techniques, with some discussion of human factors, design, security, privacy, ethics.  
 
Students will do assignments and programming projects using traditional 2D devices (computers, phones and/or tablets) and modern VR head-worn displays. Programming and development will be done with web-based technology (Javascript/Typescript, WebGL, WebXR, and tools like three.js and babylon.js).  
 
Students must have experience doing 3D programming. Background in HCI is recommended, but the text has chapters that can provide enough of an overview for those without an HCI class or work experience.
 
For undergraduates in CS4803-3DUI, CS 3451 is required, and CS 3750 is beneficial (but not required).  This class will count as a pick-list course for either the Media or People Threads.  The professor taught CS 3451 last fall, the material is on github [here](https://cs3451.github.io).
 
For graduate students in CS8803-3DUI, either CS6491 or an undergraduate course in computer graphics is required, and a graduate or undergraduate HCI class in recommended (but not required).  This class will count as an elective in either the Computer Graphics or HCI Specializations.

## 1.1. Course Expectations (expanding on what is in Banner)
<!-- This class is a remote synchronous class. Lectures will be pre-recorded so that you can watch them asynchronously outside of class time. Synchronous class time will be used for additional activities, including tutorials, student presentations, and virtual poster sessions. Attendance is expected, via video or in social 3D virtual environments. You will need a reasonable internet connection and 3D-capable computer. Programming will be done with web tech, using WebGL-based libraries. -->
<!-- This class is a remote synchronous class. However, you will need to pick up (or arrange for someone to pick up) a VR display from campus if you do not own one, and drop it off at the end of the semester.

Lectures will be pre-recorded so that you can watch them asynchronously outside of class time. Synchronous class time will be used for additional activities, including tutorials, student presentations, and virtual poster sessions. Attendance is expected, via video or in social 3D virtual environments. 

You will need a reasonable internet connection and 3D-capable computer. Programming will be done with web technology, using WebGL-based libraries.-->

The practical requirements and opportunities of this class stem from the 3D UI material:
- This class is being run as a remote synchronous class. 
- Each student will use a VR display for assignments and projects, and to experience 3D user interfaces and social VR. We have enough to provide one to every student who does not have their own. _You will need to pick up (or arrange for someone to pick up) a VR display from campus if you do not own one, and drop it off at the end of the semester_.
- Most lectures will be pre-recorded so that you can watch them asynchronously outside of class time. Any required material during class time will be recorded and posted after class.
- Synchronous class time will be used for additional activities, including tutorials, student presentations, and virtual poster sessions. Attendance during class time is encouraged, and will be required for specific session we will note on the schedule. We will give advance notice of which classes are required; usually only the ones where students are presenting.
- Each class will use a mix of video conferencing or take place in social 3D virtual environments (depending on the goals of the day). We will give advance notice of which mode we will use each class.
- Social 3D virtual environments will either be desktop based (e.g., Mozilla Hubs, which runs in a browser window) or VR based (e.g., Hubs, or other systems like Rec Room, Big Screen, and so on).
- You will need a reasonable internet connection and 3D-capable computer. You should verify that your computer is capable of running Mozilla's Hubs 3D Social VR software (visit hubs.mozilla.com).
- We will use Microsoft Teams for video conferencing, whiteboards, OneNote, file sharing, and so on.  You should install the Teams app on your computer (Teams video requires it).

## 1.2. VR Displays

Fully immersive VR displays come in two sorts;  3-degree-of-freedom (you can look around, but they don't let you move) and 6-degree-of-freedom (you can look and move around).  We will use the later sort for this class. 

You will need a display that has a web browser that lets you program with [WebXR](https://immersiveweb.dev/), the web API for virtual and augmented reality.  Possibilities include VR displays connected to a Windows 10 desktop (e.g., HTC Vive, Vive Pro, or Cosmos; Oculus Rift; Valve Index; one of many Windows MR displays) or a stand-alone display such as the Oculus Quest or the Pico Neo2.

VR devices that don't support a Web browser with WebXR will not work for this class (e.g., the PSVR for the PS4).  VR devices that are only 3DoF (e.g., orientation only) or do not have two 6DoF controllers (e.g., Gear VR, Daydream, Oculus GO, older Pico displays) will not work for this class.

If you have a device that will work, great! If you don't we will provide one. There is a survey on canvas that includes questions about your technology setup, that will help us figure out which display to send you.  We will sort this out after the first week, once we have a final list of who is registered for the class.

Mac and Linux users will need to use a standalone device like the Quest;  if you have a [Windows MR capable Windows 10 machine](https://support.microsoft.com/en-us/help/4039260/windows-10-mixed-reality-pc-hardware-guidelines) you may also use a Windows MR display. We have both Oculus Quests and Windows MR displays, but not enough of either for the whole class, so we will allocate them as best we can. There are pros and cons to each type of display, so don't worry too much about which one you end up with.

# 2. Course Goals

- Develop a broad understanding of the human, architectural, and algorithmic principles behind the development of the 3-dimensional graphical user interface
- Gain experience programming in modern 3D toolkits and development environments
- Exposure to a variety of advanced topics for 3D, VR, and AR systems

# 3. Required Textbooks

We will use two textbooks, both of which are available online via Georgia Tech library subscriptions.  Both textbooks are pre-loaded into Perusall in the class site on Canvas.

The first textbook is required and will be the one we most closely follow:
- *3D User Interfaces, Second Edition*, by Joseph LaViola, Ernst Kruijff, Ryan McMahan, Doug Bowman, and Ivan Poupyrev. 
Available via O'Reilly Learning [here](https://learning.oreilly.com/library/view/3d-user-interfaces/9780134034478/).

The second text is supplemental, but may have some assignment readings as well:
- *Understanding Virtual Reality: Interface, Application, and Design, 2nd Edition*, William R. Sherman and Alan B. Craig, 2018.
Available via Science Direct [here](https://www.sciencedirect.com/book/9780128009659/understanding-virtual-reality).

# 4. Grading

|Section|Component|Grade|
|:--------|:---|----:|
|Grad & Ugrad| Programming Assignments:|25% (3% for A0, 12% for A1, 10% for A2)|
| | Poster Presentations (and feedback):|14% (7% each)|
| | Other Assignments (conference viewing, journal, project feedback):|16%|
| | Quizzes:|15%|
|Grad|Project (5 deliverables)|30%|
|Ugrad|Additional Assignments:|30% (10% each for A3, A4, A5)|

For final letter grades, an overall average of 90-100 will result in an A, between 80-89 a B, between 70-79 a C, between 60-69 a D.

Students taking the class pass/fail must receive a C or better to pass. Students auditing the class will not be required to complete homework or exams (nor are they expected to do these assignments, so that the instructor and TAs can devote grading time to students taking the class for a letter grade or P/F).

## 4.1. Exams

There will be no midterms or final. We will have regular quizzes throughout the semester, based on material in the textbooks and lecture recordings, each one of which will count for a small number of points. Each quiz can be retaken multiple times, and should be treated as an opportunity to learn.

We may use the final exam period for presentation of the Graduate Projects.  I expect undergraduate students to attend, and will ask them to provide written peer feedback on the projects as part of their "Other assignment" grades.

# 5. Homework Assignments

3D interaction and interactive system creation are learned best by a combination of understanding the principles on which they are based, using them to accomplish tasks in 3D, and programming them.  Each of these will be addressed directly. A more detailed summary of the assignments you will do can be [found and the assignments page](/assignments/).

For "principles", students will do [small written assignments](/assignments/#5-other-assignments), and [poster presentations](/assignments/#4-posters) on different topics.  These will likely include feedback on other student projects, as well as short reports on conference talks (assuming we get access; more later).

For "use", we will use difference 3D systems throughout the semester, both desktop and immersive. For some of that usage, students will be asked to do written assignments about their experiences. A part of this will involve keeping a [social VR journal](/assignments#51-social-vr-journal) over the course of the semester.  We will also have students keep a [VR privacy journal](/assignments#53-vr-privacy-journal) collect images and notes as to where they use the VR displays, for use in a privacy and ethics discussion in class.

For "programming", each student will complete [three initial programming projects](/assignments#2-programming-assignments), written in Javascript and/or an object-oriented superset of Javascript called [Typescript](http://www.typescriptlang.org).

After the first programming projects, students in CS8803 will do a [group project](/project/).  Undergraduate students will complete [three additional programming assignments](/assignments#2-programming-assignments).

There will be one warm-up project handed out during the first week of class, aimed at helping you self-assess your preparation for the class. For the warm-up, you should try to do as much as possible on your own, but please do not struggle too long with technical and software details. You should try to diagnose problems using web searches, but please ask for help when you need it.  For all assignments, students may talk with one another software and technical issues, and about any of the concepts required for the programming projects, but each student should perform the actual programming of this assignment on their own. 

Students must write all of the code for each assignment themselves without any form of code sharing by electronic, written, verbal or any other means. The only code from others that may be used in these assignments are those that are given by the instructor. Note that it is impossible to get an A in this course without completing all of the programming assignments.

## 5.1. Academic Integrity, Collaboration and Web Resources

Students are expected to follow Georgia Tech's [code of academic conduct](http://www.honor.gatech.edu/). All code submitted for homeworks, all writing, and media creation such as posters and VR rooms, must be written by you alone.

- Do not give your code (or a portion of your code) to another student; do not allow another student to look at your code; do not look at or accept anyone else's code.
- Do not upload your code to public GitHub repositories or place it on repositories that may be accessible to other students.
- You can (and are encouraged to!) ask other students questions about how they did the assignment, and explain using words, pictures, and diagrams how you did the assignment, as long as you do not share code. You can also look up resources on the Internet that may help. In these cases, please list details about who helped you or the URLs of what resources you used in the comments of your assignment. See "Use of Code You Did Not Write Yourself" below.

The Homework 0 assignment provides more details on the collaboration policy for this class; completion of this Homework is a necessary prerequisite for all of the other assignments in the class.

I am required to forward all suspected cases of academic misconduct to the Office of Student Integrity, where they will be pursued to resolution. This is a very unpleasant process for all involved, so please do not put us in this situation.

If in doubt, ask.

## 5.2. Use of Code You Did Not Write Yourself

We will tell you explicitly what sample code and resources you may use in your assignments. Aside from this, you are expected to implement the "intellectual core" part of each assignment yourself; extra libraries (e.g., 2D web layout libraries like jquery, or audio libraries if you wish to add sounds) can be used if you desire, but they should not solve or simplify a core part of the assignment.   

If you find an library or sample code from somewhere that you want to use (such as in a tutorial or web page or on github), you should verify with the instructor and/or TA that it is acceptable before using it, and then document what you got and where. 

The goal of the assignments is for YOU to demonstrate that you have learned how to do the relevant work, not for you to piece together other peoples code.  

If in doubt, ask.

## 5.3. Use of Media and Text you Did Not Create Yourself

In the written assignments and poster and VR creation, you are expected to cite all material (images, text, etc) that you did not create yourself.  As with code, if in doubt, ask!

## 5.4. Late Policy

The grade on a late assignment will drop 5% of the maximum grade for the assignment for each day beyond the due date (e.g., if an assignment is graded out of 10, you will lose 0.5 points per day). A day ends exactly 24 hours after the assignment is due. Assignments will typically be due at 11:59pm the night **before** the Tuesday/Thursday they are listed on the syllabus (the exact date and time will be shown on the assignment itself).

Assignments can be submitted up to three days late.  No late assignments will be accepted four days or later after the date and time that the assignment was due, without prior approval. 

That said, if you know in advance you will have difficulty meeting a deadline, please contact the instructor to arrange for an extension.

# 6. Grad Project for CS8803

Graduate students in the class will be expected to complete a multi-part project during the semester, in teams of two. The project structure will be presented and discussed in one of the class sessions. The project consists of separate milestones, including a project proposal, implementation, demo, and final writeup. While I can try to help facilitate team matching, it is students' responsibility to find a project partner early in the semester (well before the first milestones).  

## 6.1. Human Subjects Training

Before graduate students (those taking CS8803) start working on their projects they will need to provide documentation regarding successful completion of CITI IRB Training — specifically the following courses need to be completed (or refreshed):
- Responsible Conduct of Research (1 — Basic Course)
- Human Research (Group 2 Social / Behavioral Investigators and Key Personnel — 1 Basic Course)

Graduate students will have three weeks (at the beginning of the semester) to complete the IRB training and submit their certificates (PDF) through Canvas (see the [grad project page](/project) for more information).

The CITI IRB online training can be accessed through [GT's Research Integrity site](http://researchintegrity.gatech.edu/about-irb/irb-required-training) and should not take longer than two hours to complete. Students who already have valid, that is not expired, certificates for the aforementioned courses can submit their certificates directly.

Important: Without valid CITI certification students cannot work on their projects and as such will not be able to fulfill the requirements of all project-related assignments!

# 7. Attendance 

You are expected to attend class time virtually. The class time will not be used for lectures; the instructor will record lectures ahead of time and make them available via Canvas (most likely via Perusall, so they can be collaboratively annotated).  Instead, class time will be used for activities, presentations, tutorials, discussions, and so on.  Some classes, we will use the time for informal discussion and help.  Other times we will use class time as an opportunity to socialize in 3D VR environments, both to experience using "3D UIs" and to get to know your classmates, TAs, and instructor (since those are traditionally difficult in a remote class).

If the instructor clarifies an assignment or discusses anything else during class, you are expected to know it. We will try to update the website as appropriate, try to record class time, and post announcements/videos to canvas, but do not guarantee this will happen. If you miss class, check with your classmates to find out what you missed.  

A portion of the learning in any upper level or graduate class comes from discussion and experiences during the class. If you don't attend class, you cannot participate, and your learning experience may reflect that. I expect that each student will make an effort to attend all classes and contribute constructively to the discussion.  

# 8. Accommodations for Students with Disabilities

If you are a student with learning needs that require special accommodation, contact the [Office of Disability Services](http://disabilityservices.gatech.edu/) (via web or at (404)894-2563), as soon as possible, to make an appointment to discuss your special needs and to obtain an accommodations letter. Please also e-mail me as soon as possible in order to set up a time to discuss your learning needs.

# 9. Anti-Harassment Policy

We will implement a strict anti-harassment, zero tolerance policy in line with the institution’s general anti harassment policy as it is defined [here](http://titleix.gatech.edu/anti-harassment-policy).

# 10. Student Illness or Exposure to Covid-19

During the semester, you may be required to quarantine or self-isolate to avoid the risk of infection to others.  Quarantine is the separation of those who have been exposed to someone with Covid-19 but who are not ill; isolation is the separation of those who have tested positive for Covid-19 or been diagnosed with Covid-19 by symptoms.

If you have not tested positive but are ill or have been exposed to someone who is ill, please follow the Covid-19 Exposure Decision Tree for reporting your illness.

During the quarantine or isolation period you may feel completely well, ill but able to work as usual, or too ill to work until you recover.  Unless you are too ill to work, you should be able to complete your remote work while in quarantine or isolation.

If you are ill and unable to do course work this will be treated similarly to any student illness. The Dean of Students will have been contacted when you report your positive test or are told that it is necessary to quarantine and will notify your instructor that you may be unable to attend class events or finish your work as the result of a health issue. Your instructor will not be told the reason. We have asked all faculty to be lenient and understanding when setting work deadlines or expecting students to finish work, and so you should be able to catch up with any work that you miss while in quarantine or isolation. Your instructor may make available any video recordings of classes or slides that have been used while you are absent, and may prepare some complementary asynchronous assignments that compensate for your inability to participate in class sessions. Ask your instructor for the details.

# 11. CARE Center, Counseling Center, Stamps Health Services, and the Student Center

These uncertain times can be difficult, and many students may need help in dealing with stress and mental health. The CARE Center and the Counseling Center, and Stamps Health Services will offer both in-person and virtual appointments. Face-to-face appointments will require wearing a face covering and social distancing, with exceptions for medical examinations. Student Center services and operations are available on the Student Center website. For more information on these and other student services, contact the Vice President and Dean of Students or the Division of Student Life.

# 12. Contacting the Instructor and TAs

The instructor and TAs are available via email and Teams. However, please do not expect immediate answers on any of these forums, especially nights and weekends. We will check the various forums regularly, especially 9am-5pm M-F, and endeavor as a group to reply promptly. But please remember that each of us also has classes, assignments, work and other things that we will also need to focus on.  

That said, we will try to be as available as possible, and if a message has not been replied to in more than a day (during the week), please feel free to send a "polite reminder" if you are still in need of a reply.