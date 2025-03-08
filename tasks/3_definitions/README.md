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
9. Duration of the game elapsed

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


We have successfuly assumed for the elements that can be considered to be a pacing aspects. Then, let's breakdown the possible values of each pacing aspects:

1. **Threat**
   
   This came from the source of the threat itself, such what elements might the player/enemy feel a threat & danger?. Like us (human), we mostly feel threat / danger from the external source (such a competition, or straightly getting threatened by other human). It may contructs our perception that can be used in the future to be more aware. But sometimes we may overthink about our future, this kind of source that can lead us to be in a danger (feeling unsafe about the future). Based on the three rules, we can assume that we have:

   A. Distance between the players (external)

   B. Duration of the game elapsed (external)
   
   C. Actions chosen by players (internal)

   D. Duration taken by players to decide an action (internal)

2. **Tempo**
   
   In Rhythm Game, there are beats of the song, objects that may be an obstacles, visual effects that rush our feeling, etc. Those can be considered as an aspect of Tempo. Mostly the elements can be considered as a Tempo is something out of our control. Let's assume that we have:

   A. Duration of the game elapsed

   B. Arena

   C. Actions chosen by players but not us

   D. Distance between the players

3. **Impetus?**

   It's something why the players want to move (desire/will), since impetus might be hard to quantify. But let's discuss how we might get it. 

   A. Duration of the game elapsed?

   B. TBD


## 2. PCG Experimentation to Enhance Replayability in Sumobot through player designed pacing. (TBD)


## 3. Strategy modelling in Sumobot