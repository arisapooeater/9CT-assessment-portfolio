# 9CT Assessment Task 4 Portfolio - ARISA
## Identifying and Defining 
### Identifying a Need
**BRAINSTORM**
- Pretty world in 3D with 2D elements where you explore the city, talk to people and pick up trash to spread awareness about urban pollution while calming players
- Volleyball-esque game on UNITY that is low-stakes, charming and simple that can be played to help people improve hand-eye coordination, and timing while still having fun.
- 

---
### Need Statement
**Need** - To develop hand eye coordination and a quick reaction timing in young children and adolescents through a fast-paced but low stakes

**Problem Statement** - Not all young children and adolescents have the time or ability to play beneficial and fun games as they often require a large investment of time and commitment. A fast-paced volleyball-esque game that requires players to react to the ball and move with precision against an AI opponent can allow children to develop fine motor skills and hand eye coordination in a fun, low pressure environment that they can easily engage with or leave anytime. 

**Skill Development** - To develop the knowledge and skills needed to create this game on Unity, I would complete the following tutorial(https://youtu.be/vj7TiUKMgl0?si=mcNP4yfY7dV47pd1) as a base for my game and update its graphics later by either learning to use Blender or finding resources online that I can modify to fit my game's style. 

---
### Requirements Outline
**Inputs** - The game will require the ↑ ↓ → ← keyboard keys for player movement as well as the space bar for jumping. It will also require mouse clicks for NPC conversations.

**Processes** - My project should be able to process keyboard inputs and calculate the new player position, check for the ball's collisions with ground to reset the simulation and rally score. It should also be able to identify when the ball goes over the net (through the use of colliders) and calculate the rally score accordingly. The game should also process player clicks on UI elements (speech choices) so NPC characters can respond accordingly.

**Outputs** - The game will display the player's rally score, position in game and updates such as 'Game Over'. 

**Storage** - The game will store the player's high scores locally, which they will be able to view in the start menu. The game will also store player settings, such as music and fx volume.

---
### Functional Requirements
1. **User interaction**

The user will interact with the game through a combination of keyboard commands and mouse clicks. The user can perform player movement through the directional keyboard keys ↑ ↓ → ← and can jump using the space bar. The player may also interact with their NPC opponent at the beginning/end of the game by clicking UI options to respond.

2. **Scoring and Feedback**

When the system detects the ball going over the net (using a collider), the player will receive updates in the rally scoreboard. When the system detects the ball colliding with the ground, it will trigger the feedback response 'GAME OVER!'. When the rally score becomes higher than a previously stored high score, the feedback 'NEW HIGH SCORE!' will be displayed on the screen.

3. **Saving and Loading Data**

The game will store high scores in the start menu and the game settings such as music and fx volume locally on the user's device. 

---
### Non-Functional
1. **Performance Requirements**

The game should load in around 2-4 seconds and should perform smoothly, responding to user inputs without a noticeable lag or any game glitches (eg. ball yeeting randomly). The character's movement shouldn't be choppy and should move according to the player inputs accurately.

2. **Usability Requirements**

The game should be extremely easy with an option for game instructions in the start menu for first time users. These instructions should outline game mechanics clearly, concisely and with personality, as well as example images on game play.

3. **Security Requirements**

The user data that will be in the game like the high score and game settings will be encrypted and stored securely without any sensitive information.

4. **Scalability Requirements**

The game should be able to scale to include possible future different intensities and modes like competitive or collaborative local multiplayer without affecting the game's performance or creating noticeable lag.

---
### Social and Ethical Issues (short paragraph for each)
#### Equity and accessibility - What does it mean?

``` Equity is the () ```

1. **Accessibility**
Consideration: Will your project be usable by people of all abilities?

Guidance: Ensure your project includes features like subtitles, alternative controls, or visual adjustments to accommodate users with disabilities.
The game should be usable for a diverse range of abilities and should be able to be adjusted in the settings for things like brightness, volume and text size. 

2. **Privacy and Data Protection**
Consideration: Will your project collect user data?
Guidance: If your game collects any personal information (e.g., high scores), ensure it's stored securely and only with user consent.
3. **Fairness and Representation**
Consideration: Does your project avoid stereotypes or bias?
Guidance: Make sure your characters and scenarios are diverse and avoid harmful stereotypes based on gender, race, or culture.

4. **Mental and Emotional Well-being**
Consideration: Could your game or simulation affect users’ mental health?
Guidance: Avoid distressing content and make sure the game promotes a positive experience (e.g., avoid excessive violence or manipulation).
5. **Cultural Sensitivities**
Consideration: Could any content be offensive to different cultures?
Guidance: Be mindful of symbols or themes that might be inappropriate or misunderstood by users from different cultural backgrounds.


## Researching and Planning 
### Exploration of Existing Ideas

|Existing ideas | Plus | Minus | Implication  |
|---------------|------|-------|--------------|
| A Short Hike (beach stick ball) ![A Short Hike](images/ashorthike.jpg)| A Short Hike has a cozy and warm game aesthetic that it pulls off really well. Combined with its simple point system and non-competitive nature (the NPC is rallying WITH you so you can both achieve 10 rallies), the beach stick ball game is really easy to play but still entertaining for players.  | The game is a little lenient in its rules, as when the ball touches the ground the player has a few seconds to hit the ball before the game is said to be over. | ill make an ugly version |
| Pon Pon Volley ![Pon Pon Volley](images/ponponvolley.png) | Pon Pon Volley has a cute game aesthetic and is very immersive in the storyline as it contains an introduction with sports commentators discussing the game with humorous remarks. It has a more competitive nature with the point system, which players may enjoy more, and has several modes that can be enjoyed including single player and multiplayer up to 4 players with different difficulty settings | Pon Pon Volley has a more complicated gameplay where it can touch the ground as long as its in the lined box area, however this was not outlined in the introduction to the game so it may be confusing for first time players. I'm also not sure about the colour palette as the green and brown clash a bit, but that's just a preference. | i can try |
| Pong ![Pong](images/pong.webp)| Pong is a classic video game that although a bit different to my game proposal, contains all the basic features I want in my game. I like how simple and smooth the game play is, and its multiplayer settings make it more exciting and spontaneous. | Pong has very minimalistic graphics that although iconic, is not the look I'm going for in my game. As it is an old video game, it's lack of a complex AI opponent may make the game also feel boring, repetitive and too easy for many players. | i can make it |

---
### Flowchart and Pseudocode

---
### Storyboards

---
### Gantt Chart

