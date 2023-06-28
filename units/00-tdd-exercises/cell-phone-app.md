# Project: Simple Cell Phones 

Simple Cell Phones is a project intended to be developed as a team.  It should have a back end for CRUDl operations, and a front end user inteface.  This first phase is meant to get you started, and, since you have just learned about TDD and Pipelines, will give you an opportunity to show off your new skills.  After this phase, you will learn how to containerize your application with Docker, and then deploy it with PCF, Kubernettes (K8s) and Conducktor, and possibly others.  

[Use this openAPI specification as your guide](https://gitlab.com/tmobile/workforce-transformation/onboarding-bootcamps/simple-cell-phones/api-contracts/-/blob/tmo/master/simple-cell-phones-openapi.yaml).  Feel free to improve upon the design, but be carful to not over commit yourself, and your team.  If your application does not work, it will make things difficult for the remainder of the course.

## General Requirements

All code should be written with strict test driven development methods, and should follow T-Mobile's Trunked Based Development practices reguarding source control.  You should start your pipeline for build and test.  For now, leave off the deployment step, as we will cover that in future units.

This is a team project, tasks should be accomplished in pairs. Divide up the tasks We will be looking at commit history for evidence of each team members commits.  If you are not represented in the commit history, you will not receive credit for the exercise.

Keep thing simple.  The goal of this project is to practice pairing and test driven development.  You can refactor your code later IF you have a good suite of tests to protect you.

1. Don't write any production code until you have a failing test 
1. Write only enough code to make the test pass

Commit your code frequently to source control using T-Mobile best practices (feature branches), and push to GitLab as you and your partner change roles.  Merge code to tmo/master when it makes sense.

## Back End Requirements

Your implementation should include, at a minnimum, the data, and endpoints described in the open-api documentation mentioned above. It should be RESTFul, with input and outputs as JSON objects.  Unless your manager has told you otherwise, it should be written in Spring Boot and Java.  

## Front End Requirements

For this first phase, keep things simple.  Don't worry too much about layout, or grapics.  A simple list of phones for the search, with a simple click for details is sufficient.

### Helpful resources

- [Creating a Spring CRUD REST API with TDD](https://www.youtube.com/playlist?list=PLRtsrIYWornUe1Qt8Irn1WrGzVXm0R9wg)
- [Creating an Angular CRUD Front end with TDD](https://www.youtube.com/playlist?list=PLpI_XwP0EB6IFQdg3o0uLepjb_xJcL4yW)

<!--BEGIN CHALLENGE-->

### !challenge

* type: project
* id: 71a8ffa2-e384-40fb-a178-9abb64da9622
* title: Submit your code
* points: 4
<!--Other optional fields (checkpoints only) -->
<!--`points: 1`: the number of points for scoring as a checkpoint-->
<!--`topics: python, pandas`: the topics for analyzing points-->

##### !question

Submit the URL to your GitLab project

##### !end-question

##### !placeholder

https://gitlab.com/<your ntid>/cell-phone-application

##### !end-placeholder

<!--optional-->
##### !hint

##### !end-hint

<!--optional, checkpoints only-->
##### !rubric

* Pairing
* Test quality
* Commits - Each student should be represented, and messages should be descriptive
* Code quality

##### !end-rubric

<!--optional-->
##### !explanation

##### !end-explanation

### !end-challenge

<!--END CHALLENGE-->

