# Summary
   Will be an online multiplayer 10 man battle royale. The theme will be placed in a mid-evil setting while using silly graphics that provide a delightful amount of gore and violence using stickfigures as the playable characters. Only 4 types of weapons available for the players to slaughter each other with. Each providing a unique style and mechanic, that gives players incentive to seek out their weapon of choice. Players will come equipped with a dagger upon the beggining of each game to defend themselves as they seek out weapons. 
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

### Current State of Completion
* The app is running with no crashes outside of the game.
   * The settings button and shop button currently go to nowhere.
* The gameplay is still very much a work in progress.
   * We are only getting one stick figure in the game.
   * Our map has had a number of issues that we eventually got working but not the way we want it to look.
   * The game itself isn't connected to firebase, only the applicaiton is.

### Future Aesthetic Improvements
* The game map should be updated visually and functionally
* The shop and settings screen should show something.

### Functional Stretch Goals
* The shop screen should allow users to purchase accessories for their sticks.
* The settings screen should allow the user to change their display name in game and on a leaderboard
* Adding post game results screen
* Adding player stats into the profile screen

### Test Platforms
* Google Pixel 2 running Android Version 9, API 28
* Emulated Nexus5X API 28
* 



### Firebase Connection
* Current display of Firebase interaction is in textview in the menu screen.
* The app sends playerID, roomID, and player email to firebase when a room is joined.

[JavaDoc](LordOfTheSticks/docs/api/overview-summary.html)

[User Stories](/Docs/userstories.md)

[LotS Ground Rules](/Docs/LordOfTheSticksRules.md)

[Wireframes](/Docs/wireframes.md)

[Entity Relationship Diagram](/Docs/entitydiagram.md)

[User Instructions](Docs/userinstructions.md)

[Build Instructions](Docs/buildinstructions.md)
