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
In this research, I compare different cryptographic encryptions. And I will explain which one is the best in general.
As a result of this research, I will be able to make a better decision on which cryptographic encryption to use in my projects.

## What are the differences between scrum methods






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

## Static code analysis
A simple way to analyze your code is to make use of static code analysis. This is a method to inspect code without actually running the code.
The same kind of stuff that lints do but than a bit more advanced and in depth. I made use of sonarcloud to realise static code analysis.
And upon using this I immediately saw that my code was not perfect.

![image](./images/sonarcloud.png)

As you can see I had 13 bugs and 22 code smells. And due to this information I could track all these issues down and fix them. And now my code is a lot better.
And has 0 bugs and 0 code smells left.

## Different kinds of tests
There are a lot of different kinds of tests in software development. And I will explain the most important ones.

1. Unit Tests
You often hear of unit tests, this is a very low level straightforward test. It tests a single unit of code. So it basically checks whether a single function in your code runs as expected.

2. Integration Tests
An integration test basically tests multiple units together. So it tests whether multiple functions work together as expected.

3. UI Tests
A UI test tests the user interface of your application. This can be done automatically or manually by asking others to test your application.

4. System Tests
A system test tests the whole system. So it tests whether the whole application works as expected.

## What tests are useful in my project?
- Unit tests are useful for my restful microservices. By testing endpoints I can verify that they do what they are supposed to do. And I can also verify that they don't do what they are not supposed to do. This is very useful to make sure I receive and post the data I want to receive and post. I for example have a user service, that retrieves information from google oauth and stores basic user information. It is useful to unit test this, to make sure I don't retrieve personal data from a user. As that would be a security risk. And it is also useful to test whether I retrieve the correct information from google oauth. As that would be a bug if I don't.
- UI tests are also quite useful in my project. As my website has a lot of different pages and functionalities. It is useful to test whether these work as expected. And it is also useful to test whether the website looks good on different devices. As I have made my website responsive, it is useful to test whether it looks good on different devices.

## Testing
In my individual project I am making use of two testing methods. To test my crud microservices, I used postman, swagger and unit tests. This allowed me to make sure my endpoints were doing what they are supposed to do. For my front-end I let other people test my website to find any problems they encounter. Since I am not the best yet at writing front-end tests I believe doing manual testing with other people is more useful. As tests only work if they are well written. To further improve my skills I am using tests in my group project though. Also because our stakeholders were asking it to ensure the quality of our code. Yet as I expected, at the moment still a lot of bugs pass through since our tests aren't the best yet. But this is something we are slowly learning, and getting better at. I think being very good at tests can make you a whole better of a programmer. 

## No testing
After doing research online on the topics of testing, I came across a small group of successful people who claim to barely test their code. This peeked my interest so I have listened to a podcast about the subject. They claim that in smaller teams it can be very beneficial to abandon tests because this doubles the time they have to code new functionalities. By having a team that is on one line on code quality and skills, it is claimed to be possible to not use tests and still have reliable software. How you may ask. They acknowledge that every website, tested or not will have bugs. And instead of being afraid of it, you are better off to embrace it.
Ensuring an infrastructure where bugs can be fixed within minutes, that in the end has less impact on time, than the hours you would normally spend on writing tests.
I believe that in larger teams this type of working can be dramatic, as it's hard to ensure the quality of a team the more members it has. I would certainly like trying this approach, but in the end I personally think that having a fine balance between no tests and usefull tests is the method that works best. But who knows, probably whenever I finish this study, tests are probably fully generated by AI. And the topic of discussion about tests may be gone. Increasing the productivity of software engineers.

## Unit Testing 
As said above unit tests are useful in my project because I use restful microservices. But as I learnt 100% code coverage ain't that good either. As it is very hard to test every possible scenario. And that sometimes it's not worth the time for simpler code. Because my user service is required to have access to the website by logging in on the website. I found it important that retrieving users correctly works as expected. So I wrote a unit test for this. 
![image](./images/user_tests.png)

These above tests simply tests whether the user service retrieves the correct user, or retrieves an error when the user does not exist.

![image](./images/user_tests_create.png)

And this tests checks whether creating a user works as expected.

[!image](./images/tests_passed.png)

Finally when running the tests locally or trough ci/cd all the checks pass.
Which means that all my written tests work as expected.

## Code Reviews
In my group project at first we didn't do code reviews at all. We used to just look at our own code and merge it to the main, without asking someone to have a second look to it. But as we encountered when one of our team members quit the study, some code was really poorly written. This is why we started using code reviews from this point on. Every pull requested had to be checked by someone else before merging it to the main branch. And this helped us ensure the quality of our code.




# Learning Outcome 3: Agile method
*You apply **agile** software development principles and practices.*

## Agile
Agile is a way of developing software, it is a sort of guide for software engineers to improve the way of working within a team.
On Fontys I was led towards using SCRUM starting from semester 1. But after many conversations with people who work in ICT. I discovered that pure SCRUM is not agile at all. And that most companies use either no SCRUM at all or a super set of it. There also seems to be a division between on one side people who love agile, and on one side people who hate agile. 

## Why people dislike pure SCRUM
If you implement pure SCRUM in your development traject you opt to have lots of meetings to keep the team on a line, to ensure that people are transparant towards each other what everyone is working on. Sometimes you can have up to 3 meetings per week which can take hours up on hours. And here is the problem. These meetings can use up a lot of time of a team in a week. While you could also spend these hours working on your product. You could say that these meetings try to make up for the fact that people individually aren't communicating enough. Instead of having meetings on a strict schedule, it is way more useful to have a meeting when the demand is high. 

## What to like about Agile working
Agile was created because a lot of projects failed to complete or took too long to complete.
This was because with waterfall the scope was too wide. And focussing on one part of a product helps to improve the quality of this part and focusses all the attention and complexity on this part of a product only.

## Our choice of Agile
At the start of our group project we did a small research to find out which Agile method to use. But we quickly came to the solution to use Scrum.
The reason for this is that, the entire group was familiar with it, due to the use of Scrum in other semesters aswell. We used Jira to control our process of Scrum by having a sprint board, and a backlog. We also had a daily standup meeting to keep each other up to date on what we were working on. And we had a retrospective meeting every week to discuss what went well and what could be improved. We also had a sprint planning meeting every two weeks to plan the next sprint. And we had a sprint review meeting every two weeks to show our progress to our stakeholders.


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

## What is culture
The beliefs and characteristics of a group of people shared around a place or time.

## What are ethics
Ethics are a bundle of beliefs that determine whether something is good or bad in someone's eyes.

## Ethics in a world full of a code
From the start of this ICT course on Fontys we already came in contact with ethics.
Projects are encouraged to be useful and positive in favor of the future of this world.
The reason is that we live in an era where everyone is influenced by tech.
With upcoming technology such as AI this influence is only being increased.
The demand for laws and regulation of ethics is growing bigger and bigger due to this.
According to the website DataReportal, The average human is almost 7 hours on the internet each day.
This is more than 1/3 of a day.
During this time people are influenced by apps, websites, advertisements etc.
The last 3 years we have seen how the use of internet can split groups of people in parts.
Where people live in their own bubble of apps, websites and accounts they follow on social media, that ultimately guide the opinions and beliefs of people.
If this influence is guided towards behavior considered non ethical, it could become dangerous very quickly.

## The use of ethics for the best
As ethics are so important within software engineering, it's important to use ethics in the right way.
But that leads the question, what is the right way.
As opinions are different, the morals of engineers are different.
This can cause problems when working in groups.
There are generally three options used that tackles this problem.
- In some big companies it all comes down to the investers, and they decide the ethical path a company may lead to.
A great example of this is twitter.
When Elon Musk took over Twitter, the initial idea was complete freedom of speech. But investers found this to be dangerous and stopped backing twitter.
Causing a great loss of income source for Twitter.
This caused Twitter to set a new set of rules for Twitter, and added a new regulation system within the platform.
And due this investers are slowly crawling back to the platform.
This shows that the regulation and ethics of a company were heavily influenced by their investers.

- In teams where control is in the hands of the team, there are two options left. 
Usually teams have the same lines of ethics, and when someone applies for the job they are aware of this set of ethics.
People tend to apply for jobs that fall in the same line as their own ethics.
- The other option is simply great communication. If you have a team with differentiating ethics you have to make sacrifices.
With great communication a team can find a middleground between the different ethics in the group. And together can make a standard ethics guide out of this.

## Ethics and culture in my project
In my personal project I am making a website that compares different producs with eachother.
It is an ethical question whether I should sort the order of appearance of products on my pages in various ways.
Such as prioritizing products that were made in an eco friendly way, or sorting based off fees I get paid.
Also the way I collect data from users can clash with ethics of users regarding privacy.

In my group project I am creating a parking garage app.
Here it is an ethical question whether people who have an electric car, should have a special spot for their cars, and whether they should be at the front of the garage, as often is seen.
In terms of my team, there are some minor cultural differences.
Where certain people tend to work more individualistic and owe up for their own work.
Where others need the rest of the group to tell them what to do, and how to do it.

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
In my group project we have a sprint review every 2 weeks, where we receive a lot of feedback from our stakeholders. And we also have a sprint retrospective after this meeting to discuss topics in the team and give eachother feedback aswell. This allows us to improve our product, and our team. And it also allows us to improve our individual and team skills. 

## Substantiating solutions
During the project, and especially at the start we have spent a substantial amount of time on researching the best solutions for our problems. We have done this by looking at the pros and cons of different solutions, and by looking at the requirements of the project. An example of this is our architecture model we made and finetuned in the first weeks of the project. Which we refined based on feedback, and based on our own research. 

## Problems in team
During the project I encountered many problems in my team. I have tried to solve these problems by communicating with my team. And by trying to find a middleground between the different opinions. I have also tried to solve these problems by giving feedback to my teammembers. And by trying to help them improve their skills.
When it was required I took a leading role in the team, and tried to guide the team in the right direction. And when I was not sure about what decisions to make I went to my teacher for advice. 

## Team communication
To remain professional in this project, I made sure to communicate about issues, and asked for help when needed. Whenever I had problems with public transport I always made sure to let my team know on time. When team mates were not doing their work, I made sure to communicate this with them. And when I was not sure about what to do, I made sure to ask help from the teacher. We had a few occurences where team members failed to do their work, and in these situations I took it upon myself to do their work. And to plan meetings with the project owners to make sure we were still on track. All with all, I think I have acted in a professional manner during this project. And I think I have done everything I could to make sure the project was a success.

## Individual communication
During this semester I tried to have a meeting with my teachers for my individual project every two weeks. This way I would have enough work to show him, while still seeing him often. This allowed me to get feedback on my work, and to get help when I was stuck. I had two occurences where work of the group project got in the way of the individual project, and this caused me to skipped a meeting with my teacher. These 2 times I should have communicated this with my teacher, and should have told him that I wanted to wait another week before having a meeting. But I did not do this, and this is something I should improve on in the future.

# Reflection

## What went good?
TODO

## What will I do different next time?
TODO

## What did I learn?
TODO





# Epilogue
TODO