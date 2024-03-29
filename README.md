Methodology
===========


###User Story / Bug / Task Definition of Done

* All acceptance criteria are met
* Exploratory testing by someone other than the team member who worked on the story
* Code and db revisions as migration scripts merged into master
* Unit test coverage of business logic
* Integration test coverage for all acceptance criteria
* No spec automated test broken
* Deployment instructions (if any) defined in the story in our ALM 
* Ready to deploy to production


###Process for Adding Story to Backlog

Any team member can add a story to the backlog. The way one would go about doing this is entering [Target Process](https://orchardmile.tpondemand.com) and selecting the 'Backlog Stories' view from the left hand navigation.

Once in the Backlog Stories view, click the green plus box in the bottom right corner of the stories list and add a story using traditional As a.... I want.... So that.... sturcture. Once added please Shift + Drag the story to the _bottom_ of the backlog as stories are by default added to the top of the backlog.  

###Plannings / Grooming / Product Discovery

**Planning** is the result of Product Discovery and Grooming as the session(s) in which a sprint is estimated, tasked out and divided into a suite of User Stories ready to be worked.

**Grooming** occurs before Plannings and its goal is to get User Stories and Spikes ready for a planning session. In order to have User Stories or Spikes for the planning it is necessary that these fulfill a minimum prerrequisites: 
* A Title that summarizes the WHAT is the story/spike about
* A Description that includes WHO, WHAT and WHY the story/spike must be carried out from the business value perspective and if possible from the user stand-point. 
* An Acceptance Criteria that responds to the question *How do I know that this story/spike is complete?*

```gherkin
User Story: Sign in
As a shopper
I want to sign in into the site
In order to start shopping

Acceptance Criteria
-A modal will show a text box and a button
-When clicking the button validations are triggered
-When credentials are correct user is logged in
-When credentials are incorrect validation messages state: "Incorrect user or password"
```
As a general rule, everything that is not meant to happen during a grooming or planning session it will in a **Product Discovery** session.

In addition to the 3 rules above, we can use the following **principles to manage the uncertainties** during a grooming or planning session in the following and excluding order:
* Include the uncertainty in the estimate
* Create a spike and the output will be one or more stories
* Have a Product discovery session about it
