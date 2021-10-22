# AndroidChess
Chess
You will continue working in pairs.
You MUST use Git/Bitbucket to manage your repository. Your app MUST run correcty on the Nexus 4 (4.7 inch, 768x1280, xhdpi) device emulator that comes with Android Studio. Make sure your app runs on Android API Level 29 (Android 10.0 - Q) We will test only for this level.
You may serialize the data used in your app, but are not required to do so - you can use alternative formats for storage on the device.
Javadoc and UML are not required. Lateness penalties same as for Chess and Photos.

Chess
Port the terminal-based Chess program to Android: a chess app that lets two people play chess with each other on the phone. You need to carry over all the functionality from the Chess project, and implement some other new functionality.

Playing chess (120 pts)
30 pts Two humans can use your app to play a game of Chess - this is all the functionality from the Chess assignment.
20 pts Your app must draw the board with icons for the pieces, and correctly shaded squares.
20 pts Players must move their pieces using touch input - either dragging a piece or touching first the piece's original square and then its destination.
10 pts Provide an 'undo' function that will undo the last move (but no farther).
10 pts Provide an 'AI' button that will choose a move for the current player. Choosing randomly from the set of legal moves is sufficient.
20 pts Provide functional 'draw' and 'resign' buttons.
10 pts When the game is over, report the outcome.


Recording games (50 pts)
20 pts Record all games as they're being played.
10 pts At the conclusion of a game, offer to store it and prompt the user for a game title.
20 pts List all recorded games, sorted by both date and by title (user can select which view to choose).


Game playback (30 pts)
A function that allows the user to play a selected recorded game. The selected game should be playable one move at a time, per player. The user of the app will click each time they want to see the next move (i.e. the moves are not auto-animated.)
