# backendtest-symfony
Symfony Test for Backend Developer at Bradleydyer

##Test Instructions

Create new Symfony2+ Project named symfonytest. Remove `AcmeDemoBundle` should it have been added during installation. Add new Bundle to the project using following namespace: vendor: `BradleyDyer` and name: `EntityTestBundle`. Once the bundle is ready add entities and repositories to fit scenario described below. Create and submit your pull request.

###Scenario
We have been asked to develop application that will allow our client to test potential applicants. Each applicant will answer short multiple choice test consisting of `Questions` and `Answers`. Each `Question` will have up to 5 answers of which exactly one will be correct. The Applicant will have a limited time to answer each question. Both questions and answers may contain an image (url/path to that image). The recruitment manager may add, delete and undelete questions and answers at any time.

###Objectives
1. Create Doctrine entities in your `EntityTestBundle` to represent the scenario above (questions and answers only).
2. Create repository method that allows manager to get all questions that have been added last month.
3. Add doctrine migrations to the project dependencies and generate migration to reflect database changes (Make sure to include migration in your pull request).

###Please note
There is no need to implement the front-end interface (No controllers or views).

##Setup for Developers

 - fork the repo

    Click Fork in GitHub, and choose your username if asked

 - Read the Contributing guidelines

[CONTRIBUTING.md](https://github.com/bradleydyer/backendtest-symfony/blob/master/CONTRIBUTING.md)

- Write code

- Be awesome
