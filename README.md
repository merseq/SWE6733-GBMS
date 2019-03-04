#	Gaming Behavioral Matchmaking System. 

##	Project Team Roles

1. Amritraj - Product Owner
2. Merlyn Sequeira - Scrum Master
3. Abdulaziz Houbani - Developer
4. Eyerusalem Woldu - Quality Assurance
5. Vincent Ogonor - Developer


##  Short-term Product Vision 

Our short term goal is to build a gaming platform that primarily provides the following features:
1.  A second to none matchmaking experience which incorporates human behaviors, player skill level and player community standing.
2.  Players would have the ability to form parties or lobbies with their friends, so that they can have the best gaming experience with like minded people.
3.  Players would be able to add other players to their friends list or gaming groups.
4.  Players would have the ability to rate their team-mates after each match which would lay the foundation for behavioral matchmaking.


##  Long-term Product Vision 

In the near future the product will expand to incorporate the following features:
1.  A digital marketplace for buying and selling videogames for the PC, X Box One and PlaySatation 4 platforms.
2.  A secondary marketplace for buying and selling Digital in-game items.
3.  A trading environment that would allow players to trade or exchange their digital items.
4.  A social media platform that would allow players to post and share their gameplay with the gaming community.
5.  A forum where players could discuss topics realted to gaming.


## Product Backlog  

The figure below shows the Product backlog based on User Stories:
![alt text](/resources/images/Product%20backlog.png "Product Backlog (User Stories)")

### [Click here to see Product Backlog (User Stories)](https://dev.azure.com/SWE6733/Gaming%20Behavioral%20Matchmaking%20System/_backlogs/backlog/Gaming%20Behavioral%20Matchmaking%20System%20Team/Stories)


The figure below shows the Product backlog based on Features:
![alt text](/resources/images/features.png "Product Backlog (Features)")

### [Click here to see Product Backlog (Features)](https://dev.azure.com/SWE6733/Gaming%20Behavioral%20Matchmaking%20System/_backlogs/backlog/Gaming%20Behavioral%20Matchmaking%20System%20Team/Features)


## Rationale for backlog order  
	
User Story 1, 2, 3, 4 and Feature 1 and 2 are the highest pririty work items as these form the core fuctionality of this system without the implementation of which the rest of the requirements are either meaningless or not achievable. For instance, Implementation `User Story 6` which highlights the requirement that allows a player to search, view and add new players to their friends list would be un-achievable if `Feature 1` i.e. a player profile interface hasn't been developed. Similarly, implementation `User Story 7` which allows a player to send play invites to friends would be meaningless if `User Story 2` hasn't been implemented first.

Hence, based on such careful evaluations, we have decided to prioritize our `User Stories` and `Features` in the following manner of Sprint cycle implementations:

### Sprint 1
The following Work Items will be implemented in Sprint 1 of this project which kicks off on `5th March 2019` and ends on `24th March 2019`. 

1.  `User Story 1`: Allows a player to select a game that they would like to play a match in.
2.  `User Story 2`: Matches a player with other players based on closest or comparative skill level, play-style, preferences and attitude, so that the player has an enjoyable and competitive gaming experience.
3.  `User Story 3`: Provides a player with the ability to `Accept` or `Reject` a match found by the system.
4.  `User Story 4`: Would enable our system to collect player `Behavioral data` such as `play-style`, `preferences` and `attitude`, which will be combined with their skill level, community and game standing and total number of hours spent playing a particular game to find matches with the most appropriate players.
5.  `Feature 1`: Defines the interface we will be building to outline player profiles. All critical data for matchmaking will be imported from a player's profile while the system looks for a match for them.
6.  `Feature 2`: Defines the game interface which will be incorporated into a player's profile to provide game specific data such as skill level and total number of hours spent playing a particular game.

### Sprint 2
The following Work Items will be implemented in Sprint 2 of this project which kicks off on `25th March 2019` and ends on `14th April 2019`. 

1.  `User Story 5`: Highlights the requirement for having a secure login (username and a password) for a player's account.
2.  `User Story 6`: Allows a player to search for other players, view their profiles and add them to their friends list or gaming groups.
3.  `User Story 7`: Allows a player to send play invites to other players from their friends list.
4.  `User Story 8`: Allows a player to search and add players from other games to their friends list or gaming groups.
5.  `User Story 9`: Allows a player to form gaming groups with other players.

## Sprint 3
The following Work Items will be implemented in Sprint 2 of this project which kicks off on `15th April 2019` and ends on `30th April 2019`. 

1.  `User Story 10`: Allows a player to look at other player's gaming profile.

---
# GBMS Project Specifications and Commands

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.2.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

---