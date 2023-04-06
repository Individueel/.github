<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">

<style>
body {
    background-color: white;
}
</style>

<div class="alert alert-warning">
    <h1><strong>Portfolio</strong></h1>
    <br><h4>Mike van den Hoef</h4>
    <br><h4>Fontys Eindhoven</h4>
</div>

## Table of contents
- [Products](#products)
    - [IP Find your product](#find-your-product)
    - [GP Parking pals](#parking-pals)
    - [Learning Outcome 1: Web Application](#learning-outcome-1-web-application)
        - [GP](#1-GP)
            - [Front-end](#front-end)
            - [Back-end](#back-end)
        - [IP](#1-IP)
    - [Learning Outcome 2: Software Quality (GP)](#learning-outcome-2-software-quality)
        - [GP](#2-GP)
            - [Testing](#testing)
            - [Static Code Analysis](#static-code-analysis) 
            - [Code Reviews](#code-reviews)
        - [IP](#2-IP)
    - [Learning Outcome 4: CI/CD (GP)](#learning-outcome-4-cicd)
        - [GP](#4-GP)
            - [Continuous Integration](#continuous-integration)
            - [Continuous Deployment](#continuous-deployment)
        - [IP](#4-IP)
    - [Learning Outcome 6: Design (GP)](#learning-outcome-6-design)
        - [GP](#6-GP)
            - [Design](#design)
            - [Design Origin](#design-origin)
        - [IP](#6-IP)
    - [Learning Outcome 8: Professional (GP)](#learning-outcome-8-professional-ip)
        - [GP](#8-GP)
            - [Professional](#professional)
            - [Feedback](#feedback)
            - [Researches](#research)
        - [IP](#8-IP)
- [Research](#research)
    - [What is the most secure type of cryptographic encrypting](#which-cryptographic-encryption-is-best)
    - [What are the differences between SCRUM methods](#TODO)
- [Reflection](#reflection)
    - [What went good?](#what-went-good)
    - [What will I do different next time?](#what-will-i-do-different-next-time)
- [Epilogue](#epilogue)

# Products
This semester I had to realise all the learning outcomes of semester 3. Per product I will explain how I realised the corresponding learning outcome. One project I made by myself is called, find your product. Which is a website that compares different products with eachother. And can recommend items with machine learning predictions. While the other product is an app I made with a group. Which is a system for a parking garage. Where you can link your car to an account, and can just drive in and out to pay, and reservate a place in the garage all through the app.

# Find your product
I decided to make a website that compares different products with eachother. The benefit of this idea is that I can always change the type of products on my website. And the website will still be compatible. So it is a sort of template that can be used for various different product comparison websites.

# Parking Pals
For my group project, my team has to make a projecct for the company Mandiaan. We are making a monolith application that allows users to reservate for a parking space, in parking garages that uses the system. And it also allows users to simply pay by connecting a bank card to their account and then just driving out of the garage without the need of paying at the spot, in a machine.

# Learning Outcome 1: Web Application (IP)
*You design and build **user-friendly**, **full-stack** web applications.*

Clarification:

**User friendly**: You apply basic User experience testing and development techniques.

**Full-stack**: You design and build a full stack application using commonly accepted front end (JavaScript-based framework) and back end techniques (e.g. Object Relational Mapping) choosing and implementing relevant communication protocols and addressing asynchronous communication issues.

## Front-end
In this section I'll show some parts of my frontend, the bigger milestones.

### React
The front-end has been made in React.
Which is a JavaScript framework, that allows you to easily build a website.

## Back-end
..

### API Requests
To communicate my front-end to my back-end I make use of a REST api. Where my front-end makes various requests to the various microservices I made, to pull and push information. To secure these requests, I make use of JWT tokens. These introduce a role permission system to request certain information.

### External API
To 

### Communicate with Front-end
..

## UX-Testing
..

# Learning Outcome 2: Software Quality
*You use software **tooling and methodology** that continuously monitors and improve the software quality during software development.*

Clarification:

**Tooling and methodology**: Carry out, monitor and report on unit integration, regression and system tests, with attention for security and performance aspects, as well as applying static code analysis and code reviews.

## Testing
In this semester I have to make use of 4 types of tests, unit, integration, regression and system tests. If i have a good explanation for it I may decide to not use certain types of tests.

### Unit Testing 
..

### Regression Testing
...

### System Testing
...

#### End-to-End Testing
...

## Static Code Analysis
...

## Code Reviews
...

### Coding language
...

### API requests 
...

# Learning Outcome 4: CI/CD
*You **design and implement** a (semi)automated software release process that matches the needs of the project context.*

Clarification:

**Design and implement**: You design a release process and implement a continuous integration and deployment solution (using e.g. Gitlab CI and Docker).

## Continuous Integration
In my individual project I use github workflows to perform continous integration. For all my services, and my front-ends. I wrote tests which automatically run whenever I push, on github.
Here is one image of a workflow for my back-end, and beneeth is one of my front-end.

![image](./images/ci-cd.png)
![image](./images/ci-cd2.png)

## Continuous Deployment
In my group project, we deploy our front-end using render.com
This website pulls the latest version of the master branch, whenever it gets merged.
By simply connecting it to your github account and setting this continuous deployment up.

# Learning Outcome 6: Design
*You translate (non-functional) requirements to extend existing (architectural) designs and can validate them using **multiple types of test techniques**.*

## Architecture
I made an architecture diagram to determine what kind of structure, and stack I want my application to be be.

## Model
I made a container model, to describe the structure of my application.

![image](./images/architecture_model.png)

### User Interface
...

### UX-Testing
...

# Learning Outcome 8: Professional (IP)
*You act in a **professional manner** during software development and learning.*

Clarification:

**Professional manner**: You actively ask and apply feedback from stakeholders and advise them on the most optimal technical and design (architectural) solutions.
You choose and substantiate solutions for a given problem.

## Feedback
...

## Researches
...

# Learning Outcome 1: Web Application (GP)
*You design and build **user-friendly**, **full-stack** web applications.*

Clarification:

**User friendly**: You apply basic User experience testing and development techniques.

**Full-stack**: You design and build a full stack application using commonly accepted front end (JavaScript-based framework) and back end techniques (e.g. Object Relational Mapping) choosing and implementing relevant communication protocols and addressing asynchronous communication issues.

## Front-end (ROS)
...

## Back-end (ROS)
...
54
# Learning Outcome 3: Agile Method
*You can implement the software process for your project according to a given agile software development method.*

Clarification:

**Agile** method: You are aware of most popular agile methods and their underlying agile principles. You are able to implement the process of your software project according to a chosen methodology.

## Scrum
...

# Learning Outcome 5: Cultural Differences and Ethics
*You **recognize** and **take into account** cultural differences when working with multi-site teams and are aware of ethical aspects in software development.*

Clarification:

**Recognize**:  Recognition is based on theoretically substantiated awareness of cultural differences and ethical aspects in software engineering.

**Take into account**: Adapt your communication, working, and behaviour styles to work with other developers from different cultures; 
Address one of the standard Programming Ethical Guidelines (e.g., ACM Code of Ethics and Professional Conduct) in your work.  

# Learning Outcome 6: Requirements
*You translate (non-functional) requirements to extend existing (architectural) designs and can validate them using **multiple types of test techniques**.*

Clarification:

**Multiple types of test techniques**: You apply user acceptance testing and stakeholder feedback to validate the quality of the requirements. You evaluate the quality of the design (e.g., by testing or prototyping) taking into account the formulated quality properties like security and performance.

# Learning Outcome 7: Business processes
*You can explain **simple** business processes and **relate** them to the development of your software project.*

Clarification:

**Simple**: predominantly sequential processes with one or two alternative paths.

**Relate**: understanding the relationships between the process and software.

# Learning Outcome 8: Professional (GP)
*You act in a **professional manner** during software development and learning.*

Clarification:

**Professional manner**: You develop software as a team effort according to a prescribed software methodology and following team agreements. You are able to track your work progress and communicate your progress with the team. You actively ask and apply feedback from stakeholders and advise them on the most optimal technical and design (architectural) solutions. You choose and substantiate solutions for a given problem.

## Team Communication
...

# Research

# Reflection

## What went good?
...

# Epilogue
...