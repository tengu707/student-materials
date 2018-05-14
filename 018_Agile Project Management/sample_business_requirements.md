# Title

## Executive Summary

The goal of this project is to create a dedicated system for exeter students to colaborate. These students are often seperated by large distances so face to face and typical social systems aren't possible. There are also many benefits of a web based system. It can be integrated into exeter, it can be quickly searchable and additional features can be added quickly. It should be completed in 3-4 weeks, but there is a risk of it taking longer. This risk can be minimized by adequetly distributing resources, most importantly having a security expert on the team.

## Business Objectives


Every student participates in a group project at the end of their course. These projects are often the most involved web projects that the students have ever created, and therefor have a huge impact on their portfolios. It also shows how they work in teams, so developing a highly functional and motivated team is critical for their success.

## Background

Every student participates in a group project at the end of their course. These projects are often the most involved web projects that the students have ever created, and therefor have a huge impact on their portfolios. It also shows how they work in teams, so developing a highly functional and motivated team is critical for their success. Historically industry standard tools have fallen short of this task. Facebook is too large to be useful even if it shares many features. Slack is greate for chats but isn't as good on searching and posting ideas. Thus a new tool is needed to fill this gap.

## Scope

The scope of the project is to create a dedicated system that completes the business objectives. Things not in the scope is video chatting, chatrooms or any other features that repeat the already existing and accessible functions the students are used to. The system should have an aestetic match wozu and exeter, but does not need to be integrated into them. It does not need to integrate into slack or facebook or any other system unless integrating would significantly reduce workload. It should have a back end and a database in order to contain and process all the user info. The matching scripts should be preran whenever possible to reduce user load times. Redesigning exeter in order to make our system work is not within the scope of the project.

## Functional requirements

The following goals are critical for success,
1. Students are able to post ideas
2. Students are able to edit or delete their ideas
3. Students are linked to similar ideas automatically
4. Students can search posted ideas
5. Students can follow and like ideas
6. Students can invite other users to collaborate
7. Every user(student) contains contact information of name, slack account and email
8. Only other users and administrators can see the info contained
9. All ideas, accounts and chat rooms are auto-deleted when a student graduates in order to keep the database fresh and small
10. An administrator not familar with coding can edit, delete and moderate all of the student posts as well as their own
11. A backend security system is created to ensure student info is kept private from outside users
12. Any user (with a unique user name) can be created with a password decided by the user
13. There will be a verification system with the administrator
14. The front end should be responsive
15. Administrator should be able to view a page of user info
16. Front end will be consistent with already existing systems

## Personnel requirements

I need a team of three to five developers for about 3-4 weeks. They should be familiar with front end, database and backend operations. There should also be one security expert. I also need access to a quality tester. The tester will only be needed for about a week. Access to the designer of the exeter systems front end would ensure a consistent product for the students. The designer will only need to be there for a few hours to begin with and be on call for the design phase. The designer should perform a breif quality review. All personel should have full access to a computer and internet, as well as be in person for kick off meetings and implementation.

## Delivery schedule

Stage 1 Basics - 6 days

Form the basic outline of the features. Focus on backend, database and security. Completion should allow a basic user profile to be created and able to perform CRUD functions on posts as well as related features like likes and follows. Features 1, 2, 5, 7, 10, 11, 12, and 15 are to be focused on.

Stage 2 Connection - 8 days

Focus on creating a search and linking function. If the users are linking to other systems they should be integrated at this point. By the end of this the user's should have full functionality. Administrators should be created at this point too, with a system to either automatically or by hand verify users as the administrator.  A major amount of time should be focused on the automatic linking function as it is the most complex feature. Features 3, 4, 6, 8, 9, and 13 are to be focused on.


Stage 3 Front End - 3 days

Developers will focus on finalizing any features and forming the front end in a way that matches woz-u/exeter. Remember the front end should be responsive. Features 14 and 16 are to be focused on.

Stage 4 Test - 2/3 days

Quality Tester should get access to the feature. Any last minute bugs should be taken care of. Designer also does a review to ensure front end vision is carried through. All features should be thoroughly tested.

Stage 5 Implement - 1 day

Product should be launched. With more users, some bugs may arise so the team should be on standby.

Stage 6 Control - 6 months

One developer should stay in order to solve last minute issues and train future administrators. Could also act as the first administrator. If time permits new minor features could be expiremented with and added as desired.

## Other requirements

Students are given basic requirements for their computer and need to have updated browsers. They can be expected to use multiple types of browsers though so ensure it can be used on the top five browsers. Mobile support is useful but the majority of users will have and use a desktop. 

## Assumptions

Assumptions made are that we have the freedom to specify what other systems the current system integrates with. Ideally it would be fully integrated into the exeter system and slack for ideal user interface and not having to double up on usernames. Our assumption is that initially it should be created seprately. I also assumed the coders would be able to complete what I could in an 8 hour day. This is a reasonable amount, but I could be off on it, especially in areas I have little experience in. One such area is the security portion. This is why it is vital to have a dedicated security expert.

## Limitations

We have limited knowledge on what resources are available. This really is limiting the amount of details I feel comfortable commiting to. 

## Risks

There is an extreme risk of overunning our timeline. This is a complicated feature being suggested. Our resources are being distributed thinly and any shortcomings will push out the delivery date. I do not suggest commiting to any deliveries until stage 2 is completed. Once stage 2 is completed then we should have an idea of how long it takes and how far off the estimations are. The greatest risk is that users will not find value in the system. This could be negated with some thorough research. Implementing a beta before the alpha release would substantially reduce this risk, but would also significantly push out the timeline.
