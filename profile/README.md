# Portfolio - Mike vd Hoef

## Table of contents
- [Products](#products)
    - [IP Find your product](#find-your-product)
    - [GP Parking pals](#parking-pals)

- [Researches](#research)
    - [What is the most secure type of cryptographic encrypting](#which-cryptographic-encryption-is-best)
    - [What are the differences between SCRUM methods](#what-are-the-differences-between-scrum-methods)

- [Learning Outcome 1: Web Application](#learning-outcome-1-web-application)
    - [User Interface](#user-interface)
    - [Front-end](#front-end)
    - [Back-end](#back-end)
        - [Swagger](#swagger)
        - [Gateway](#gateway)
    - [API Requests](#api-requests)
    - [External API](#external-api)
        
- [Learning Outcome 2: Software Quality](#learning-outcome-2-software-quality)
    - [Testing](#testing)
    - [Unit Testing](#unit-testing)

- [Learning Outcome 3: Agile method](#learning-outcome-3-agile-method)
    - [Agile method](#agile-method)
            
- [Learning Outcome 4: CI/CD](#learning-outcome-4-cicd)
    - [Continuous Integration](#continuous-integration)
    - [Continuous Deployment](#continuous-deployment)

- [Learning Outcome 5: Cultural differences and ethics](#learning-outcome-5-cultural-differences-and-ethics)
    - [Cultural differences](#cultural-differences)
    - [Ethics](#ethics)

- [Learning Outcome 6: Design](#learning-outcome-6-design)
    - [Architecture](#architecture)
    - [Model](#model)

- [Learning Outcome 7: Business processes](#learning-outcome-7-business-processes)
    - [Business processes](#business-processes)

- [Learning Outcome 8: Professional](#learning-outcome-8-professional-ip)
    - [Professional](#professional)
    - [Feedback](#feedback)
    - [Researches](#research)

- [Reflection](#reflection)
    - [What went good?](#what-went-good)
    - [What will I do different next time?](#what-will-i-do-different-next-time)
    - [What did I learn?](#what-did-i-learn)
- [Epilogue](#epilogue)





# Products
This semester I had to realise all the learning outcomes of semester 3. Per product I will explain how I realised the corresponding learning outcome. One project I made by myself is called, find your product. Which is a website that compares different products with eachother. And can recommend items with machine learning predictions. While the other product is an app I made with a group. Which is a system for a parking garage. Where you can link your car to an account, and can just drive in and out to pay, and reservate a place in the garage all through the app.

## Find your product
I decided to make a website that compares different products with eachother. The benefit of this idea is that I can always change the type of products on my website. And the website will still be compatible. So it is a sort of template that can be used for various different product comparison websites.

## Parking Pals
For my group project, my team has to make a projecct for the company Mandiaan. We are making a monolith application that allows users to reservate for a parking space, in parking garages that uses the system. And it also allows users to simply pay by connecting a bank card to their account and then just driving out of the garage without the need of paying at the spot, in a machine.





# Research
For my projects, I had to make a few researches. I will explain the researches I made.

## Which cryptographic encryption is best
TODO

## What are the differences between scrum methods
TODO





# Learning Outcome 1: Web Application
*You design and build **user-friendly**, **full-stack** web applications.*

Clarification:

**User friendly**: You apply basic User experience testing and development techniques.

**Full-stack**: You design and build a full stack application using commonly accepted front end (JavaScript-based framework) and back end techniques (e.g. Object Relational Mapping) choosing and implementing relevant communication protocols and addressing asynchronous communication issues.

## User Interface
To improve the user experience of my application, I decided to make use of front-end designs. To do this I made use of Figma. Which is a tool that allows you to easily design a website. And it also allows you to easily export the css to help you build a website. To figure out what kind of designs I first did some research into popular websites. Most websites have a similar design, especially on the landing page. So I started with a design for that.

![image](./images/front-end-design.png)

## Front-end
My front-end has been made in React.
Which is a JavaScript framework, that allows you to easily build a website. It has a lot of features that make it easy to build a website. Like a lot of pre-made components that you can use to build your website. And it also has a lot of pre-made classes that you can use to build your website. Which is called a state management system. Which allows you to easily manage the state of your website. And it also allows you to easily make requests to your back-end. The first thing you see on a website is a landing page, and based off designs I made I made a first version of it for my website.

![image](./images/homepage.png)

My first iteration of my landing page was nice, but not like I wanted it to be. So in the second iteraction I made some changes to it. And now it looks more like the designs I came up with.
![image](./images/homepage2.png)

![image](./images/products.png)

## Back-end
My back-end has been made in Spring Boot. Which is a Java framework that allows you to easily build a back-end. It has a lot of features that make it easy to build a back-end. Like a lot of pre-made classes that you can use to build your back-end. And it also has a lot of pre-made classes that you can use to build your database. Which is called an ORM. Which stands for Object Relational Mapping. This allows you to easily map your database to your Java classes. And you can easily make queries to your database.

### Swagger
To improve the user experience of my back-end, I decided to make use of Swagger. Which is a tool that allows you to easily document your API. And it also allows you to test your API. Which is very useful for testing your API in a quicker and simpler way.

### Gateway
To make my back-end more secure, I decided to make use of a gateway. Which is a microservice that acts as a gateway to my back-end. It allows me to make use of a JWT token. Which is a token that allows me to secure my API. And it also allows me to make use of a role permission system. Which allows me to give certain roles certain permissions.

![image](./images/gateway.png)

## API Requests
To communicate my front-end to my back-end I make use of a REST api. Where my front-end makes various requests to the various microservices I made, to pull and push information. To secure these requests, I make use of JWT tokens. These introduce a role permission system to request certain information.

## External API
To login and register, I decided to use Google Oauth2. This allows users to login with their google account. And I can use the information from their google account to create a user in my database. This way I don't have to store passwords, and I can use the information from their google account to create a user in my database.





# Learning Outcome 2: Software Quality
*You use software **tooling and methodology** that continuously monitors and improve the software quality during software development.*

Clarification:

**Tooling and methodology**: Carry out, monitor and report on unit integration, regression and system tests, with attention for security and performance aspects, as well as applying static code analysis and code reviews.

## Testing
In this semester I have to make use of 4 types of tests, unit, integration, regression and system tests. If i have a good explanation for it I may decide to not use certain types of tests.

### Unit Testing 
TODO

### Regression Testing
TODO

### System Testing
TODO

#### End-to-End Testing
TODO

## Static Code Analysis
TODO

## Code Reviews
TODO

### Coding language
TODO

### API requests 
TODO





# Learning Outcome 3: Agile method
*You apply **agile** software development principles and practices.*

Clarification:
..





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





# Learning Outcome 5: Cultural differences and ethics
*You are aware of **cultural differences** and **ethical issues** in software development.*

Clarification:
..






# Learning Outcome 6: Design
*You translate (non-functional) requirements to extend existing (architectural) designs and can validate them using **multiple types of test techniques**.*

## Architecture
I made an architecture diagram to determine what kind of structure, and stack I want my application to be be.

## Model
I made a container model, to describe the structure of my application.

![image](./images/architecture_modelv1.png)

After receiving feedback from my teacher, I decided to make some changes to my architecture. I decided to make use of a gateway, to make my back-end more secure. 

![image](./images/architecture_modelv2.png)

And later on I also decided to make use of a discovery server, as this allows me to easily scale my application. And it also allows me to easily make use of a load balancer. Which allows me to easily distribute the load over my microservices. And lastly it also gives me the ability to change the port of my microservices, without having to change the ports in my gateway.

![image](./images/architecture_modelv3.png)

## UX-Testing
TODO




# Learning Outcome 7: Business processes
*You can **translate** business requirements to software requirements and **validate** them using **multiple types of test techniques**.*

Clarification:
..






# Learning Outcome 8: Professional
*You act in a **professional manner** during software development and learning.*

Clarification:

**Professional manner**: You actively ask and apply feedback from stakeholders and advise them on the most optimal technical and design (architectural) solutions.
You choose and substantiate solutions for a given problem.

## Feedback
TODO

## Team Communication
TODO






# Reflection

## What went good?
TODO

## What will I do different next time?

## What did I learn?






# Epilogue
TODO