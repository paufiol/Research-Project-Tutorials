# Research Tutorial Design
---

## Problem Description

Tutorials are often the first contact a player has with a game, especially gameplay. This first impressions are key in order to engage the player from the start and theach them the necessary content to play. This segments are tipically short but very information dense, making mistakes common. In addition, failing to give a solid tutorial will harm the player experience of the whole game.

As with many other aspects of game design, this is no exact science. The approaches provided here are not perfect. However, by better understanding the concepts and play and mistakes and successes for the past we can learn to provide a smoother experience.


## Proposed approach

### Topics

A tutorial should intriduce the player to the plot or context, the mechanics and the controls. Keeping in mind these at all times will help have a compact tutorial, where everything is made to serve more than one purpose.

- **Context:** Allow the player to view the world he is set in, its basic rules (i.e. gravity), the character, and if necessary the plot.
 Often cinematics or scripted sequences can be placed before the tutorial to address this, at least partly. _(Defend the village from the horde!)_
- **Mechanics:** Show the rules of the game. Avoid forcing them to use them. Instead, strive for the player to discover by providing tips and with good level design. _(By firing the catapults)_
- **Controls:** Show the player how to interact with the game. In this aspect is specially key to limit how much information we give at once. Give only what is necessary, and let the player try by themselves. _(That aim using A-D, fire with W)_

Keep in mind that a tutorial is not limited to the start of the game. The tutorial only needs to teach you whatever is necessary at a given time. Your goal only needs to give momentum to the player until new elements are added to the board.

A good aim is to try to incorporate them as often as possible. For example, if the three examples above are put togheter they provide more information than the tree of them isolated. An opposite example would be mobile tutorials where arrows pop up and tell you where you tap. Since you only focus on tapping, only controls are explained and the user is left with little clue about what is he supposed to do.


### Goals 
![venn diagram](https://raw.githubusercontent.com/paufiol/Research-Tutorial-Design/master/docs/images/venn_diagram.png)
You can imagine our goals as this two sets of opposite concepts. A good tutorial will aim to offer a balance between these opposites, or choose one side over the other to reinforce some game pillar.

---

- **Teach - Respect:** Teaching is the most obvious goal of a tutorial. But when teaching the player, you must also respect them. Players do not like to feel understimated, belittled or limited. They want to be clever. Allowing to skip the tutorial is the most basic form of this. "We are aware that you may know this, so I don't force you to do it". A way better approach is to avoid interrupting the player when he's exploring, and instead offer a helping hand. 

In Zelda: Breath of the Wild, you are left in an open world map very early. However, in order to progress you will have to use certain mechanics (the player has freedom of choice). When getting close to interactable elements, a discrete dialog will appear with a simple action _(Grab)_ and they key in the keypad that is associated with. With these small boxes you give a hint to the player, and teach them the controls without having to look away from Link.

Another common mistake is over explaining. Players don't need to know minor details or interactions that you as a developer might have insight in. When a mechanic is introduced show the bases first, and possibly avoid telling small details alltogheter. More experienced players will learn those by themselves given them _a sense of pride and accomplishment_.

Example on good vs bad cases:

[![Half Life 2](https://i.pinimg.com/originals/d6/06/e3/d606e3ba47fdda6f76d785f754013c8f.jpg)](https://www.youtube.com/watch?v=kz71F34UyIM)

[![Dead Space](https://steamuserimages-a.akamaihd.net/ugc/275096611232409534/67A38DCB41269B357435303856617E8FD6CCEC85/?imw=1024&imh=578&ima=fit&impolicy=Letterbox&imcolor=%23000000&letterbox=true)](https://imgur.com/gallery/hlxvF/comment/292991808)

---

- **Comfort - Excite:** The user should feel safe, or comfortable. There are essentially too ways of achieving this: you either provide a safe, deathless environment or punish very little for losing. That being said, without any challenge or goal the player will feel soon disengaged. So on the other hand we have to provide exciment. A very effective way is to promise better experiences after the tutorial is completed _(If you learn to use this sword, I'll give it to you.)_. You can also provide content that is not yet necessary without explanation, so if players figure it out on their own they will feel good and have a small advantage. 

Again, this is about equilibrium. If we look at Dark Souls III, for example, has a side room in the tutorial area with a strong enemy which is really hard to take at early levels. However, hints exist on how to kill it, and for more experienced players this may suppose a challenge. If succesfull you will get an upgrade item, which is a good reward, but totally prescindible. However, new player will feel frustrated if they have to face it, so it should be obvius that is not a requirement to kill it.

A good Equilibrium example: DOOM (2016)
[![DOOM (2016)](https://i1.wp.com/twincitiesgeek.com/wp-content/uploads/2016/05/DOOM-Beginning-Kill.gif?fit=500%2C282)](https://youtu.be/c8uBO8grqd8?t=15)


### How to convey information
---
![Spatial and Diegetic](https://raw.githubusercontent.com/paufiol/Research-Tutorial-Design/master/docs/images/info_chart_multiexample.PNG)

**Spatial:** Exists in the same space that the game does.
**Diegetic:** Is part of the world / narrative.

Players dislike being taught, so the best way to give it is making him believe he created it. To do so, one can set hints as elements of the game (diegetic, spatial elements) that lead the player to a deduction. Achieving this will result in a more fluid experience to the gameplay, since it was never interrupted.
Sometimes text is requiered, _(for controls often times)_, but in order to keep the pace of the game agile you want to avoid pop ups. A solution can be to use spatial text; that is, text that appears within the world, so the game is not interrupted.

You can disguise the tutorial by incorporating it into the plot. Common examples are masters/mentors, or boot camps for military games.
Another disguise is turning them into puzzles, where the mechanic is key to solving it. Having the user think about the mechanic this way will help them interiorise it. Tipically, this second approach is used in strategy games. 

Always give context within the game. If its non diegetic and non spatial then has very little connection to your game. Avoid them whenever possible. 

### Follow standards & common sense
---

This is an obvious one, but sometimes is hard to remember. 

All users will have previous experiences that we can take advantage of. For example, we don't need to explain the user how to click, because we assume he has launched the game and thus knows hot to use a mouse. In the same way, if standards are followed _(WASD for moving for example)_ you might not need to explain it, depending on the expected user profile and how literate is it.

Following common sense is there to prevent us from overexplaning implicit concepts _(lava is hot)_ and respecting the player.

![Mario dies in lava](https://24.media.tumblr.com/e8465cc29bc5552f10156b83715a40a9/tumblr_mtn3uhJGKA1sjqlxio1_500.gif)


### Too long; Didn't Read
---

- Keep in mind lore, mechanics and controls at all times
- Give players a sense of safety and an exciting goal
- Incorporate as much tutorial into the world as you can
- Avoid stopping the player for too long (hand holding)
- Allow room for self-discovery; (no time pressure, no overexplaining, or locking the player)
- Follow common sense
- Follow standards
- Break any of these rules after understanding them  


### Bibliography
--- 

- [2016 GDC Europe talk, Nicolae Berbece](https://www.youtube.com/watch?v=VM1pV_6IE34)
- [GDC 2014, Asher Vollmer](https://www.youtube.com/watch?v=Uf7xLHUpKHE)
- [Half-Life 2's Invisible Tutorial | Teaching Players, Game Maker's Toolkit](https://www.youtube.com/watch?v=MMggqenxuZc)
- [Gamasutra; Video Game Tutorials: How Do They Teach?, Nathan Hedges](https://www.gamasutra.com/blogs/NathanHedges/20171013/307378/Video_Game_Tutorials_How_Do_They_Teach.php)
