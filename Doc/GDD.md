# Game Design Document
This document describes the upcoming console game developed by Rise Labs, codenamed **"Volley"**. It contains textual description of gameplay, art style, characters. It's expected it will change gradually as the project evolves. The latest version will always be hosted in the project's Git repository.

## Project Description
*This session contains a brief summary of what this game is about. More details can be found at later sessions.*

"Volley" (commercial name is TBD) is a 3D, beach volleyball game for current generation consoles and PC. It will be developed sing the Unity engine. The player controls a pair of volleyball athletes and and plays against another pair, controlled by either a different person or by the CPU. The player wins by scoring 21 points before their opponents do.

Each athlete is an in-game character, and the player choose 2 for their team before starting a match. The game will feature a number from 4 to 12 pre-made characters, each with unique appearance and abilities. Additionally, the player will be able to create their own avatar through an in-game Character Editor.

Game modes include exhibition matches (a quick match against the CPU or another person), championship (a series of matches with gradually increasing difficulty, with a boss in the end) or training mode (where they can play the same match indefinitely for practice purposes).

## Gameplay
While in match, you control one of the characters from your pair of athletes. Using the directional pad or the left analog, you can move them in the 3D environment. Pressing "X" (assuming the DualShock 4 joystick layout) makes the character jump, and pressing "Square" will attempt to throw the ball to the other side. Pressing "Circle" will attempt to pass the ball to your teammate, and pressing "L1" will switch which character you are controlling.

## Player Skills
* **Serve**: put the ball into play by striking it with the hand or arm from behind the rear court boundary. The higher the level, the more precision and speed the ball will have.
* **Force**: force to hit the ball. The level implies the speed applied to the ball.
* **Resistence (IDEA)**: the players get tired during the match. The higher the resistance, the less fatigue.
* **Speed (IDEA)**: player's speed. The higher the level, the greater the speed when walking along the court.
* **Block**: score a direct point by directing an attack by the opposing attacker back into their court, or channel the ball to the defender by "taking away" part of the court, or slow the ball down so the defender has time to chase down the ball. The level adjusts how much the player can jump and penetrate in the opponent's field.

## Art Style and Aesthetic Decisions
The volleyball matches in be played in virtual representations of Brazil's most popular beaches. Important details are yet to be decided:

* Whether we will include beaches from Salvador only, or from different Brazilian regions
* If we want to sacrifice visual accuracy to show touristic features from certain beaches*
* Whether we will follow a more realistic art style (like *FIFA* or *Madden* - both popular sports games) or a more cartoonist style (like *Mario Party*). Commercial and technical perspectives should be evaluated before taking a decision.

*For some locations, having the volleyball match being played in the beach itself means not showing important landmarks (because they aren't visible from the beach). We could either:

* change their positions so they are visible from the beach, even if it means inaccuracy
* make the match happen close to the beach, but not directly on top of it. This allows the game to show landmarks like Farol da Barra in the background of a match
* Do it accurately, and only show these landmarks during pauses.
