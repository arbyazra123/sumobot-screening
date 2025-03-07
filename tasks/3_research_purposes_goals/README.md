# Research definitions, purpose, and goals

## 1. Improving Pacing-based level in Sumobot

Since we have pacing aspects: threat, tempo, and impetus (optional), we have to know what's possible element that can supply to the those aspects (except player and enemy), currently set to none.

Let's define every elements that may exist inside a level of sumobot:

1. An Arena
2. Audiences (crowd)
3. Sumo-bots (player and enemy), only two, or can contains more?, free for all?, tag team?
4. Actions chosen by players
5. Duration taken by players to decide an action
6. Define a hidden-winner each simultaneous action. To know, compare the players that closer to the border of arena?
7. Distance between the players
8. Position / distance the players until they fall (outside of the arena)
9. Duration of the game elapsed (if there's another level)

Let's categorize with three rules:

1. Model things that controlled by players
2. Model things that player can't control, but it affects to the player
3. Don’t model things that are not controlled by the players and have no effect on it.

We should define first what element(s) included in `Don’t model things that are not controlled by any players and have no effect on it.` which is "Audiences (crowd)", since Audience is currently an outsider, we don't want to consider it. So the rest is might be quantifiable and considerable.

1. `Model things that controlled by player`
   
   A. Actions chosen by players
   
   B. Duration taken by players to decide an action
   
   C. Define a hidden-winner each simultaneous action. To know, compare the players that closer to the border of arena?

2. `Model things that player can't control, but it affects to the player`

   A. Arena: it may not must to be circle, can be in any shape, it may has a hole that might be an advantage to player if they can handle, either they falls.

   B. Distance between the players
   
   C. Duration of the game elapsed
   
   D. Position / distance the players until they fall (outside of the arena)