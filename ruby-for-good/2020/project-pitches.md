# Project Pitches

* All brownfield projects
* Will release a Google spreadsheet of issues the Thursday or Friday before the event with all the issues
  * Pair up and claim an issue to work on
  * Once done, claim a new issue
    * Can be on the same project or a different project
    * Can switch your pair or not

Looking for volunteer PR moderators for Hacktoberfest

## Projects

### DiaperBase/PartnerBase

* Provide diapers \(children's and adults'\) and period supplies free of charge
  * Not covered by WIC
* Reaches 2 million children and 50,000 women

#### Goals

* **Usability**: Think Steven Krug's book _Don't Make Me Think_
* **Inclusive Language**: Since the Alliance for Period Supplies \(the national organization in charge of period supply organizations\) is recommending our software we want to start updating/changing the language to make it inclusive
* **Composite Items**: Right now partners can only request single types of items \(size 1 diapers, size 2 diapers, etc.\). We are going to create the ability for banks to create "kits" that they assemble.
  * For example: A first time period kit with wipes, pads, and tampons in it.
* We also are looking for someone to spike out and test some Rails 6 multiple database functionality to link the apps better and make us less reliant on API calls.
* Lots, lots more

{% embed url="https://github.com/rubyforgood/diaper" %}

{% embed url="https://github.com/rubyforgood/partner" %}

### CASA \(Court Appointed Special Advocate\)

* Train and support volunteers to advocate in the best interest of youth in the foster care system
  * Goal is for children to exit the foster care system and be placed in homes
* Measure the efforts that volunteers are putting in to each case via a dashboard CMS system
* Will be pushed to production within days

{% embed url="https://pgcasa.org/" %}

#### Goals

* Building out a multi-tenancy platform
* Bug fixes
* System improvements
* New features
* Lots and lots of testing

{% embed url="https://github.com/rubyforgood/casa" %}

### Circulate

* Based in Chicago
* Software for lending libraries
  * Not necessarily books—can be tools, camping equipments, hobby items, etc.

#### Goals

* Build out member experience workflow
  * A lot of UX/UI in this project

{% embed url="https://github.com/rubyforgood/circulate" %}

### Abalone

* Sea snails that are tasty and important for the oceanic ecosystem

{% embed url="http://abalone-dev.herokuapp.com/" %}

#### Goals

* CSV-first in terms of data upload
  * Want to be offline-compatible
* Multi-tenancy
  * Potentially give direct SQL access
  * Investigate the Blazer gem
  * Investigate PostgreSQL

{% embed url="https://github.com/rubyforgood/abalone" %}

### Mutual Aid

* Focused on building community and helping your neighbors
* Places a strong emphasis on self-advocacy

{% embed url="https://docs.google.com/presentation/d/1iUakTWYsj1tMAyOUO-1gp4oxNJzwGTFsZnkkDJk8Ax8/edit\#slide=id.p" %}

#### Goals

* Authentication and authorization
* Incorporated a bit of Vue.js
* Very object-oriented, modular build
  * A unique build model

{% embed url="https://github.com/rubyforgood/mutual-aid" %}



