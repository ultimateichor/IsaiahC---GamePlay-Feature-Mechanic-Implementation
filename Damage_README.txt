The README files are getting serious now.

====================================

Contributions:
Isaiah Carr - Scripts, UI Visuals, States, and now Input/Damage

====================================

Unity Engine Version:
Unity 6.2 (6000.2.7f2)

====================================

Reflection:
A new input system was added, allowing a player (green square) to move around. In addition, pressing H simulates
damage and reaching 0 health results in an automatic switch to the GameOver state.

The biggest challenge encountered was resetting the player's health after the GameOver state was entered, as
it would originally remain 0 even when the game was "reset" out of the state. This was resolved by adding a
currentState update function.