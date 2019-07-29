# Summary
   Will be an online multiplayer 10 man battle royale. The theme will be placed in a medievl setting while using silly graphics that provide a delightful amount of gore and violence using stickfigures as the playable characters. Only 4 types of weapons available for the players to slaughter each other with. Each providing a unique style and mechanic, that gives players incentive to seek out their weapon of choice. Players will come equipped with a dagger upon the beggining of each game to defend themselves as they seek out weapons. 
    The weapons will consist of a Long Sword , a Bow, a Fire staff, and an ice staff. Every 45 seconds the perimeter of the playable portion of the map will shrink, pushing the players toward each other, forcing players to encounter and eliminate each other until there is only one left standing.
    
### Team Members & Roles
* Brian Alexander: Controls and Firebase Integration
* Austin DeWitt: Design and Animation, Multiplayer Service Integration
* Trey Page: Android construction and Google Integration
* John Bailey: Map creation and Libgx integration. 

### Who are the users?
  This game will provide a quick competitive match for mobile users.


### Why is this intersesting/important/valuable
  With battle royale games taking over the markets, this app aims to provide a quick satisfying match lasting about an average of 3      minutes. The goals and aims of the group to create this game was to increase knowledge of using Firebase, as well as learning how to create an android game. Other goals were increased understanding of rendering and creating images and animations in Android as well as intuitive user controls. Notably skills in Firebase database is a valuable skill as a developer to possess, as well as learning to give live data feedback to multiple users to keep latency low. 

### What will be gained by some porton of this application running in the cloud?
  Anytime any where gameplay

### What will be on the user side?
  * The user will come equiped with on-screen responsive controls
  * A set of characters to choose from
  * Settings to control gameplay.

### What platform?
This will be an android app

### What external data/services will be used
* Google play sign in to Authenticate.
* Firebase NoSQL Horizontal scaling database to observe/subscrube to a collection via multiple users. 
    * Sign in integrated through firebase to give users read/write authorization. 
    * Database is structured in 'Collections' which hold 'Documents' inside of them which can hold references to other collections. 
* Google Multiplayer Play service to initiate a 'Room' for a creation of a game instance to then place the necessary data into Firebase.
* TODO flush this out Brian.....!!!!!

### Current State of Completion
* 
* 

### Future Aesthetic Improvements
* 
* 

### Functional Stretch Goals
* 
* 

### Test Platforms
* Google Pixel 2 running Android Version 9, API 28
* Emulated Nexus5X API 28
* 



### Firebase Connection
Current display of Firebase interaction is in textview in the menu screen.


[User Stories](/Docs/userstories.md)

[LotS Ground Rules](/Docs/LordOfTheSticksRules.md)

[Wireframes](/Docs/wireframes.md)

[Entity Relationship Diagram](/Docs/entitydiagram.md)

[User Instructions](Docs/userinstructions.md)

[Build Instructions](Docs/buildinstructions.md)
