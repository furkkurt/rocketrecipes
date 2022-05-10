# Firebase vs MongoDB Realm

* Status: accepted
* Deciders: Mihir, Luis, Dennis
* Date: 2022-05-09

## Context and Problem Statement

A big feature is to move recipes to the cloud and to also include a true user function. This requires choosing and implementing an existing cloud database solution.

## Decision Drivers 

* We need to allow users to share recipes with each other 
* We need to enable true user authentication 

## Considered Options

* Firebase 
* MongoDB Realm

## Decision Outcome

Chosen option: Firebase, primarily because of existing team experience. Additionally, team on #12 took a vote and Firebase won 2-1.


## Pros and Cons of the Options <!-- optional -->

### Firebase

{example | description | pointer to more information | …} <!-- optional -->

* Good, because authenticatin built in
* Good, because set up is lightweight and other team members have experience
* Good, because there is a REST API can reduce dependencies
### MongoDB Realm

{example | description | pointer to more information | …} <!-- optional -->

* Good, because same features as Firebase
* Good, because better free tier
* Good, because Luis already has a small POC
* Bad, because team does not have experience with it

