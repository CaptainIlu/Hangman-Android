Hangman
=======

 Native App Studios 
_Hangman is an application for Android based on the classic Hangman game for the course Native App Studios_

###How to run the Hangman android application###
- Clone the repository: git clone git@github.com:CaptainIlu/Hangman-Android.git
- Get Eclipse and the ADT plugin, see instructions here: http://developer.android.com/sdk/installing/installing-adt.html
- Open Eclipse (eclipse.exe)
- New > Project> Android > Android Project from Existing Code
- Select the hangman app located in the cloned folder in the map 'Hangman'
- Run the app on your mobile or set up a virtual android device and run it there.

###Features###
- placeholders for yet-unguessed letters that make clear the word�s length.
- displays how many guesses left until you lose
- displays all letters you already guessed
- User can give input guesses via an on-screen keyboard.
- app only accepts single alphabetical characters as valid input (case-insensitively).
- Congratulation popup after you win
- Changable settings, like the length of words to be guessed and the maximum number of incorrect guesses allowed
- Option to start a new game in settings menu
- Maintains a history of high scores that�s displayed anytime a game is won or lost. 

###Technologies###
- Android SDK (java)
- Canvas with SurfaceView (http://developer.android.com/guide/topics/graphics/2d-graphics.html)

###Mockups###
####Main Activity####
![Hangman](doc/hangman.png "Main Activity")

####Settings####
![Settings](doc/settings.png "Settings")

####Highscores####
![Highscores](doc/highscores.png "Highscores")