# First Assignment

## Introduction
Below are the instructions for this first assignment/mini-projet. The commands to execute are not explicitly mentioned but you should be able to find those informations online (such as how to git clone a project). Toward the end of the project, you will need to do more research to achieve the goals.

## Execution
This is an individual assignment, questions at the end of the assignment must be done individually. You can help each other in case you have issues in understanding but you must execute all actions indivudally.

## Prerequisites to install
- git bash
- IntelliJ Community Edition
- Docker (on Windows or on WSL if you have it)
- Java JDK 20 + Configure Windows "PATH"

## Optionally
- WSL (Ubuntu integrated in Windows and can be used as a terminal)

## Setup
1. Fork this project (top right corner of the page)
2. Go to the newly created project, from your personal account.
3. Clone it to your local laptop

## First push
1. Make a local change to the readme, for example by adding your name
2. Push the new change to your personal repository
    - Use an explicit commit message (for example "Add author name to README.md" and not "first commit")

## Run your application
1. Open the project from IntelliJ
3. Check that you see a message "Hello World!" in the intellij console

## Make your project a maven and make a jar
1. Follow https://www.jetbrains.com/help/idea/convert-a-regular-project-into-a-maven-project.html#develop_with_maven
2. Execute your generated jar from the terminal (cmd or other), check that "Hello World" is displayed

 ## Build a docker running your code
 1. Build a docker image that will run your code, include your first name in the docker image.
 2. Run a docker container from that image
 3. Check that "Hello World" is displayed

## Add functionnalities to your code
1. to be completed

 ## Export docker image
 1. Export your docker image in a file
 2. Send it to another person of your choice, i.e. through Discord
 3. Ask that person to run it, and compare the behavior of your container locally and the one running on your partner. The behavior should be the same.


 ## Deliverable
 At the end of the Readme.md, add this following element :
 - A screenshot of your docker image and docker running (from the command line)
 - A screenshot of your app output
 - Answer to those questions :
    - What is the prerequisite for another machine to run your application if you provide it the docker image ?
        - In term of Operating System, pre-installed app, etc...
    - What is the difference between a virtual machine and a docker container ?
- Refer to https://www.markdownguide.org/basic-syntax/ to learn about markdown syntax (ie. how to include pictures)