## Objectives

1. Review all steps required to prepare for the Front End Web Development / Skills course, previously known as Nights and Weekends

### Introduction

This guide is meant to serve as a “meta-plan” behind the days of instruction within Flatiron Schools “skills-front-end-web-development” track. In the subsequent sections and topics of this track, we will present the arc of given days, the arc of the program, and provide reference materials and guidance for teachers.  The focus of this track is to offer extra support where they may find flexibility in delivery to accommodate the vagaries of class speed, pacing, student comprehension, and retention.

### Who Are Our Students?

This is a skills-focused course. The purpose is to create a meaningful delta in the students’ knowledge such that they are more capable in creating or altering front-end assets. Likely students are professionals who work in, or are interested in working in, web related positions looking to improve their abilities, including:

* Marketers tending and maintaining templates in a CMS or Mail application
* Graphic artists who are interested in transitioning to the web medium
* Hobbyists who are interested in maintaining newsletters, brochure sites, etc.
* Individuals curious as to whether they can find a place in the programming job ecosystem
* The currently-employed who see these skills as means to promotion

### Principal Arc

Our principal arc is this:

* Provide a short path to a meaningful display of creations appearing “on the internet”
* Provide enough background about the Web, HTTP, and HTML for students to have an informed interaction with the web
* Provide a fairly exhaustive series of experiences with the HTML5 element universe, while simultaneously utilizing git for version control
* Provide a safe practice space for learning to style HTML with CSS
* Provide exposure to the complexity of handling responsiveness in web design, utilizing CSS flexbox, grid, and @media
* Provide a lab class in which a brochure site is built
* Teach JavaScript in its native DOM context
* Work with JavaScript as a generalized programming language designed to manipulate the DOM as input
* Teach event handling
* Introduce AJAX and asynchrony
* Provide a final project which brings together HTML, CSS, and event-driven JavaScript

### Technology

In effort to reduce the “drag” of local, personal laptop setup / software download, the course will be taught within Flatiron School’s in-browser “LearnIDE” environment. Throughout, we refer to this as their “personal cloud computer.” These are stateful, dynamic, containers that are launched when a student opens the Learn IDE. Every lab has the ability to launch a “LearnIDE” session which looks like a Sublime- or Atom-style editor with file tree + a terminal. Because the IDE is web based, students will be able to complete all lessons and labs regardless of the operating system or type of laptop they have.

This solution also delays the introduction of deployment. Students will do their development within LearnIDE containers and serve the content via the built-in httpserver command. As such, we are able to delay discussions around purchasing and transferring files to remote servers (necessitating discussions of FTP, SFTP, pwd, etc.) until they have had the joyful feeling of something they have created appear on the internet.

#### Important Notes about the Learn IDE

When the Learn IDE is not open for a lab, they will not be able to access the web server that’s serving the content. So if they do a lab in Learn IDE, close their browser, and then try to look up the server on their phone while waiting for the train, it won’t work because the server will have been suspended. We cover deployment in week 4. While some students will certainly want to do this, others will be so challenged by the material that deployment will simply be another confusion to the core of HTML and CSS.

Whenever students need a scratch space, they should use their cloud instance and create a new directory, do work, and then share it with httpserver. However due to currently limitations in Learn IDE they should not clone repos. Learn IDE is not stateful for ther sub-contained cloned repos!

### Video and Technology

If there are videos in a lesson, it is possible that the video may include step by step instructions that differ from how students would complete the task using the Learn IDE.  Where the videos suggest a path that is not supported by the content, we should note this difference but not make a big deal about it. It’s rarely a feature that is of significance.

### Labs

Lessons come in 3 varieties: READMEs, Labs, and Code-Alongs. READMEs have no IDE access. Students read and click that they have read to move on. In the event that they need scratch server, they should use their own personal cloud instance. Labs and Code Alongs appear the same. Labs have tests that need to be passed before a PR can be submitted by the aggregate command `learn submit`. This flow will become obvious after the first portfolio project when students switch to wanting test-driven JavaScript labs. 

Before this (i.e. in HTML material) labs are a bit more confusing because there will be no feedback (i.e. “Green light”) to indicate solution. In this case, students should work to build their side in the Lab’s associated IDE environment. Once they have a site that’s how they want, they should issue `learn submit` wait for feedback of pull request having been received, and then refresh the page. They will then have the green light and understand to move on. This might need to be demonstrated. Points of demonstration are noted below per day.

### A Note About This Guide Track

The FEWD_Teacher's Guide materials are written originally by the curriculum team to assist our instructors, but there is no one better equipped to say what did and did not help than the instructors actually teaching the course.

As this course is launched in various environments to a variety of students, we 
encourage all instructors to add, modify, and contribute to these repositories.  There may be considerations, helpful bits of information, or materials that you discover that would be beneficial to all of our instructors in the future, so, if you can, after you've completed teaching a class, please update these repositories! There environment issues that we did not forsee. There also may be considerations for students of different skill levels or learning styles.  

With more information shared here, we can provide a better, more consistent experience for future students.

Thank you!




<p class='util--hide'>View <a href='https://learn.co/lessons/fewd-teacher-guide-introduction'>FEWD-Teacher-Guide-Introduction</a> on Learn.co and start learning to code for free.</p>
