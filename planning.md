# Planning
Thinking about what you want to achieve with your project is an important step before you start development.

I highly recommend following agile development techniques such as [scrum](https://www.scrum.org/) for big projects. However smaller hobby projects can make use of the resources linked below. The tips and resources linked below are mostly based off of scrum principles.

## Use cases/User stories
A helpful step for planning out your project is writing down the exact goals of your project and what you want to achieve.
There are already heaps of templates available to achieve this.

[Use case guide](http://www.bridging-the-gap.com/what-is-a-use-case/)

[User story guide](https://www.mountaingoatsoftware.com/agile/user-stories)

Do some brainstorming and write down all requirements in use cases/user stories. This will help you refine the list of requirements. You should not put more than 8 hours of work into this step as these requirements may change throughout the development lifecycle.

## UML and finding the required objects
When developing in Java you will have to create different objects. To help with finding out what objects you need to create you may convert your written user stories to an UML domain model. A domain model is a diagram of models together with their relations to each other.

[Useful resource on how to create a domain model from user stories](http://agiledata.org/essays/agileDataModeling.html)

You should not put more than 4 hours of work into this step as these requirements may change.

## Tasks
After you exactly what you want to develop it is useful to create a list of tasks that need to done before the project is finished(based off of sprint backlogs). If you want to create new features while in development add those features onto the big tasks list.

I personally use the following format:
### Big tasks/challenges
This is a list of bigger features. Should be described without too much detail and ordered in sequence of what should be completed first. Example of such task: Create database scheme, setup production server, etc...

### Weekly work
List of more detailed tasks you picked from the bigger task list. These are some tasks you will be working on for the coming week. Example of such task: Write authentication service for app, write X feature for Y, etc...

### Daily work/for one programming session
You should be able to finish this list of tasks within one day or programming session. These are the most specific tasks to be completed. Examples would be: change X method to use Y, implement X interface into class Y so we can use Z, etc...

These tasks should be small and take no longer than a hour to implement.

## What is "Done"?
As a developer you may get stuck on a certain feature because it could be implemented better(code perfectionism). This can waste a lot of time.

The agile method called [scrum](https://www.scrum.org/) requires a definition of done to be set before development start. This definition is a list of checks that need to be completed before you can call a certain feature "done". When the definition of done is met the developer should go on to the next feature. The definition of done should be checked on the written use cases/user stories so we know that a feature has been implemented correctly.

Example definiton of done:
1. Does it meet the requirement written in the use case/user story?
2. Does it meet the set (custom) programming conventions.
3. Is it documented?
4. Is it tested/does it have written tests?

