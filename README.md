# jetpack-kev

Thanks for taking the time to check out my project, I made this for a friend of mine in 2 weeks, I wanted to see how much of a game I could finish in that time. I developed the graphics and the programming for the game. I haven't included every single script because there are about 50 objects with only a few lines of code in each because of how gamemaker studio 2 works, so I just included some of the more interesting scripts for you to have a look at.

About the game
I wanted to make a procedurally generated world and i'm quite happy with the results, the game utilizes a variation of the drunk walk algorithm in order to make randomized levels, basically two "drunk" walkers are represented within an array, they will walk in a random direction based on a few variables and everywhere they walk is marked as the floor, everywhere else is then assumed to be a wall. After the walkers have done there job filling in the array, another script is called which spawns objects to represent the array in a physical way. Next some extra objects like spikes and doorways are placed at random in places that would be appropriate for them, there is also a wizard that appears in each level, so don't forget to look out for him!

Each time the game makes a new level it will save the information in an ini file, which will be loaded each time you start the game again.

The goal of the game is basically to find the portal to the next level, open portals take you to new levels, locked portals take you to previous levels.

the controls
Movement: WASD 
Toggle fullscreen: ALT-ENTER / F8
enter doorway: ENTER

If you have have any other questions for me about the project please let me know, I hope you enjoy it!
