This chapter is an introduction to the tools and techniques that we will use in later chapters when discussing the balancing of specific game genres. Different genres require different modes of balance, but in many cases, the common thread that binds them is the same.

本章是对工具和技术的介绍，我们将在后面的章节中讨论特定游戏类型的平衡问题。不同类型的游戏需要不同的平衡模式，但在许多情况下，将它们联系在一起的共同点是相同的。

The methods discussed in this chapter provide a basis for us to examine the issue of balance in games:

本章讨论的方法为我们研究游戏平衡问题提供了基础：

* What exactly do we mean by balance?\
 我们所说的平衡到底是什么意思？
* How do we define balance?\
 我们如何定义平衡？
* How can we say that one game is well balanced where another is not?\
我们怎么确定一种游戏很平衡，而另一种游戏却不平衡呢？

These are not easy questions to answer; an answer that may be correct for one person may be completely incorrect for another. In some ways, there can be no definitive answers to the questions. Like so many other questions in game design, the answer contains an unknown quantity: the player.

这些问题并不容易回答；对一个人来说可能正确的答案，对另一个人来说可能完全不正确。从某种程度上说，这些问题不可能有明确的答案。就像游戏设计中的许多其他问题一样，答案包含了一个未知数：玩家。

Although we can attempt to anticipate what sort of people will play our game, we will never be able to satisfy all of them. However, as fallacious as it may seem, we have to start somewhere. In balancing a game, we have to assume the existence of an average player and target the balance to suit that player. Remember, however, that your average player will not be anywhere near as skilled at computer games as you and your team. Don't fall for the extremely common mistake of "making a game that you enjoy playing." This statement has been the epithet for many promising games. The danger of aiming to make a game that you enjoy playing is that you run the risk of making a game that only you enjoy playing. A significant level of "dumbing down" may be required to make your game as accessible as possible to the average player. Do not be alarmed by this; you can cater for extremes by providing different difficulty settings, as necessary. So with this in mind, let's explore the subject of game balancing in more detail.

尽管我们可以尝试预测什么样的人会玩我们的游戏，但我们永远无法满足所有的人。然而，尽管看起来有些谬误，但我们总得有个起点。在平衡游戏时，我们必须假定存在一个普通玩家，并针对这个玩家来平衡游戏。但请记住，普通玩家的电脑游戏水平远不及你和你的团队。不要陷入“做自己喜欢玩的游戏”这一极其常见的错误。这句话是许多有前途游戏的代名词。以制作自己喜欢玩的游戏为目标的危险在于，你有可能制作出只有你自己喜欢玩的游戏。为了让普通玩家也能玩到你的游戏，你可能需要进行相当程度的“简化”。对此不要惊慌；你可以根据需要提供不同的难度设置，以满足极端情况的需要。有鉴于此，让我们来详细探讨一下游戏平衡的问题。

# What Is Game Balance? 什么是游戏平衡？

Many games are released each year that commit fundamental game design errors. These games are fatally flawed from the outset, and short of a monumental marketing campaign and a small spate of miracles, they are doomed to failure. There are many obvious reasons for this kind of spectacular failure, such as bad coding, buggy software, poor quality control, and substandard graphics.

However, on many occasions, the cause of failure is not so immediately obvious. The game may look okay, sound okay, and even to some extent play okay, but it still fails commercially. One of the reasons for failure (and the one we are going to concern ourselves with here) is poor game design. In Chapter 7, "Gameplay," we introduced the elements of gameplay that we expect to find in games. We also touched a little on the subject of game balance. Including all the expected elements in a game does no good if they are not in balance with one another and with the player.

But what exactly do we mean by a balanced game? A balanced game is one where the main determining factor for the success of the player is the skill level of that player. That does not mean that random events cannot occur, but a better player should ordinarily be more successful than a poor one unless he has an unusually long run of bad luck.

Traditionally, game balance has been very much a trial-and-error process. The game is played, the game is tweaked, the game is played, the game is tweaked, and then finally, when time runs out, the game is released (and usually tweaked further in the form of patches).

So why are there no formalized, scientifically rigorous methods of game balancing? Well, for a start, it's an extremely difficult and complex process. Essentially, game balancing is a problem involving a fantastically large number of independent variables. It's an optimization problem in n-dimensional space where n is a very large number. No formal rules govern game balancing, except in a very small number of abstract mathematical scenarios.

Classical game theory is simply not suited to this kind of problem. Most areas of research concern themselves with games in which there are discrete player turns and a limited number of variables. This type of theory is ideal for analyzing games of chance, such as poker and coin-toss games, but it would be nearly impossible to use for the analysis of more complex games, such as computer games, which are more often continuous and have hundreds, if not thousands, of independent variables. Also, the majority of game theory is concerned with finding the optimum way to play a game. Using game theory to balance a game would be like playing a twisted version of Jeopardy—starting with the answer and working back to the best possible question. (It's possible that one day there might be some sort of "game calculus" invented to handle these problems, but we're not going to hold our collective breath. Besides, that still doesn't solve the problem of how to break down the game into a list of strategies and variables to fit into the equations.)

This sort of n-dimensional optimization problem occurs in many areas of science, and it is from these areas that we can borrow techniques to help us solve the problem. This is not to say that all game-balancing problems can be solved by the blanket application of a sterile algorithm. A healthy measure of human finesse is still required in order to make a game feel "just right." Just because a result is mathematically correct does not automatically make it aesthetically pleasing.

In fact, the tweak-play-tweak method of game balancing is a valid approach (and is pretty much the only approach so far). The only problem is that this method is time- and resource-intensive and is extremely prone to error. Worse still, balancing a game is a very difficult concept to grasp. After all, what are you balancing it against? Are you balancing it against itself? The player? And how exactly are you balancing it? Are you balancing it so that it is a fair game? Are you balancing it so that it provides a consistent experience to the player no matter what her ability? The answers to these questions are—at least to some degree—subjective and depend upon the nature of the game. For example, a historically accurate simulation of the Anglo-Zulu wars would not be a fair game. The Zulus would have to lose, which would be a bit depressing for the Zulu player.

Even a nonrealistic game has to take some liberties in order to obtain balance. For example, a hypothetical game that simulates the invasion of modern-day Earth by a race of aliens has to give the humans a chance to win. And in spite of what you've seen in films like Independence Day, any race that is advanced enough to move huge ships across hundreds or thousands of light-years probably wouldn't have much difficulty mopping up a small planet like ours—and they certainly wouldn't have computers that interfaced with an Apple Macintosh, conveniently allowing us to destroy their whole operation. In order to base a game around such a scenario, we'd have to stretch credibility to the breaking point, in that with today's technology we could actually defeat a race of advanced aliens whose sole specialty is enslaving entire worlds. Human "pluck" will only take us so far.

Before we get into the gritty detail, we should briefly describe what it is that we are actually balancing. There are several ways of implementing balance in a game, centered around how the equilibrium is maintained. In particular, there are two broad classes of balance that we will be discussing: static balance and dynamic balance. Traditionally, balance has not been differentiated in this fashion; when game balance is referred to, it is usually referred to as a whole, comprising both the static and the dynamic balance. Often, you will hear discussion in terms of the opening, the midgame, and the endgame, much as you would in chess. This is a perfectly valid, if a little rudimentary, approach; it's fine for the discussion of a game that has already been written, but when we are designing a new game, we would like to be able to go to a finer grain of detail. It has often been said, however, that the degree of understanding of a subject is directly proportional to the sophistication of the available language used to describe it. For our discussion, referring to balance as a whole rather than distinguishing between the two areas of balance is an unnecessary handicap that we would rather avoid.

# Static Balance 静态平衡

Static balance is concerned with the rules of the game and how they interact with each other. These are specifically time invariant. In other words, these are the rules of the game that can be written down and documented to aid play—the usual strategy guide fodder.

A concrete example would be a comparison of the relative strengths of units in a war game, or the average jumping distance of Mario in relation to the average distance between platforms. Generally, when game balance is spoken about, most people are unconsciously referring to the static balance (sometimes mixed with a little of the dynamic balance).

Static balance is the classic game balance that is talked about in other books, including Game Architecture and Design, also from New Riders (although we did delve somewhat into the subject of dynamic balance in that book, without specifically naming it as such). This is the process whereby we ensure that the game is fair and all elements interlock seamlessly to avoid dominant and recessive strategies that can ruin a game.

## Randomness and Average Values 机性和平均值

In the following few sections, we are going to discuss balancing gameplay elements using payoff matrices to demonstrate some of the points. Payoff matrices are used to illustrate the balance between elements of the game.

For example, let's take a symmetrical game involving two players: red and blue. Each of these players has two strategies that it can use: R1, R2, B1, and B2.

Let's say that R2 beats B1 with a payoff of 3, B2 beats R1 with a payoff of -2, B1 draws with R1, and R2 draws with B2, as shown in Table 8.1.

Table 8.1. A Simple Net Payoff Matrix

||B1|B2|
|---|---|---|
|R1|0|-2|
|R2|3|0|

Note that negative numbers indicate a win to blue, and positive numbers indicate a win to red.

This doesn't have to mean that for each play of the game, R2 beats B1—occasionally the converse could occur. It depends on the nature of the game. What it is generally taken to mean is that the net payoff is that value. In some cases, the strategy B1 could pay more or less against the strategy R1 (subject to the whims of chance), but the average value of the payoff over time would tend to the specified value.

This is especially important to realize when we are considering net payoff strategies for computer games. We have to deal with a large number of random events that do not necessarily all have the same result, but that will tend toward a certain value; hence, the net payoff tends toward a discrete value. If we were to attempt to examine each of the separate results as an individual strategy, rather than taking an average of all similar events (for example, knight versus archer combat), then the analysis would soon become unmanageable (and without meaning).

## Dominant Strategies

Dominant strategy is a term from classic game theory. A dominant strategy is one that surpasses all others by being the best one to choose under any circumstances. That does not mean that it guarantees winning, but it should guarantee not losing. (To be exact, a strongly dominant strategy guarantees winning, while a weakly dominant strategy guarantees not losing.)

A strongly dominant strategy is never desirable, but care should be taken when excising weakly dominant strategies—sometimes they can be valuable (for example, forcing a draw in chess). When eliminating a weakly dominant strategy, make sure you're not throwing the baby out with the bath water.

The difficulty in applying these concepts from classic game theory to real games is the massive increase in complexity. A typical game theory example deals with a simple game with known parameters, such as the tossing of a coin, whereas a game such as Westwood's Command and Conquer: Red Alert has many hundreds of variables—too many, in fact to be able to deal with rigorously—and the values that they take are effectively continuous, not discrete like the heads or tails of a coin toss. To us, this means that the labeling of strategies as dominant takes on a bit of fuzziness. There is no discrete boundary. What would be a dominant strategy in the hands of one player is a guaranteed loser in the hands of another.

The ideal solution to this would be to talk in terms of an idealized perfect player who only makes perfect decisions. Unfortunately, although that would result in mathematically correct games, they almost certainly would not be fun. The players of our games are real people, with different attitudes, abilities, likes, and dislikes, and we would be doing them (and ourselves) a great disservice by trying to shoehorn them into a particular box to fit some theory. And that's the biggest problem we have in balancing a game: No matter how much perfect math and science we can apply to the problem, it will only take us so far. The rest is up to us, as game designers. In fact, it's this final stage of game balancing that really distinguishes the greats of game design, such as Shigeru Miyamoto, Brian Reynolds, Sid Meier, and Dani Berry.

Let's look at a trivial example of a dominant strategy and then look at some real-world games that also have dominant strategies.

You're returning home from a busy day at the office, when suddenly you wonder whether it's your wife's birthday today. Should you buy flowers or not?

The risks you take are as follows: If it is your wife's birthday, and you buy flowers, you win 10 brownie points, because you remembered her birthday. If it's not her birthday, you will win 20 brownie points, because you have surprised her with your thoughtfulness.

Alternatively, you could decide that it is not her birthday and you don't need to buy any flowers. In this case, if you are wrong and it actually is her birthday, you take a big hit in brownie points—you lose 100 of them. If it's not her birthday and you don't buy her flowers, then everything is normal when you get home, and you neither gain nor lose any brownie points.

The net payoff matrix for this game is shown in Table 8.2.


||Wife's Birthday|Not Wife's Birthday|
|---|---|---|
|Buy Flowers|10|20|
|Don't Buy Flowers|-100|0|

Quite clearly, the dominant strategy is to always buy flowers, because you will always get a positive payoff. (An even more obvious strategy, although outside the bounds of this example, is to make sure you remember your wife's birthday in the first place.)

The second strategy—don't buy flowers—would be immediately discounted by any rational game player; the strategy only guarantees a zero payoff at best, and a massive loss in the worst-case scenario.

Of course, to turn this example into a real game decision (by eliminating the dominant strategy), we would have to attribute some cost to the flowers so that buying flowers when it is not her birthday results in a negative payoff. We'd also have to figure out the exchange rate between dollars and brownie points.

Unfortunately, only the most trivial examples can be broken down into a simple payoff matrix. For a more complicated example, we should examine the previously mentioned Red Alert (see Figure 8.1). This game is famed for a particular dominant (or near dominant) strategy, which has become known as the tank rush (a name that has spread to similar strategies in other games).

Figure 8.1. Red Alert.

graphics/08fig01.gif

An experienced player playing as the Soviet side could devote all of her energies to producing a large force of tanks in the early part of the game, and then use those tanks to attack the nascent enemy base en masse. Against an unprepared opponent, this almost always guarantees a victory. Of course, because of the immense number of variables involved, we cannot say with certainty that this is a dominant strategy—that is, it may not be the best strategy to play regardless of what the opponent does—but it is certainly near dominant.

Another real-world example, again from a real-time strategy game, occurred because of relative unit strength mismatches. In the original Warcraft game from Blizzard Entertainment, the Orc player was almost always guaranteed victory if he was able to produce warlocks (see Figure 8.2). Once a warlock was in play, it could be used to create an army of powerful demons. This almost always guaranteed a win for the Orc player and was a strategy worth playing, whatever the opposing player did. In fact, we found that the only way to guarantee a fair game in the original Warcraft was to explicitly agree to disallow any magical warfare.

Figure 8.2. Warcraft.

graphics/08fig02.gif

These examples are both from real-time strategy games. This type of game is often the easiest to analyze, because it so closely matches the areas of research in conventional military game theory. However, we don't want to give the impression that we are only concerned with real-time strategy games, so our last example of a dominant strategy is one that affected an old side-scrolling space shooter game on the Nintendo Super NES. In this game (which we will not name to prevent embarrassment on the part of the individuals responsible), it was possible to make your way through the entire game by upgrading your weapons to a certain level and then, going as low on the screen as possible, keeping your finger on the fire button. In this position, you were invulnerable to the enemy attacks and could finish the game on a single life. This is a clear example of a dominant strategy.

All these examples show why dominant strategies are a bad thing, and why we must strive to avoid them in our games. They ruin gameplay. The presence of a single dominant strategy is enough to render a good portion of our intended gameplay obsolete. All other strategies that may potentially be used in the same circumstances are recessive strategies, and no rational player would choose to use them.

An interesting point to examine is where to draw the line between a valid (but undesirable) dominant strategy and plain cheating. For example, some players may view the strategies mentioned earlier as cheating, whereas others would be of the view that if the game system allows it, it is a valid strategy. The question is, where does this leave the classic "God Mode" present in virtually all first-person shooters since the original Wolfenstein 3D (see Figure 8.3)? Taken from a game theory purist point of view, the obvious dominant strategy is to use the God Mode when playing the game. Why? Because it guarantees that you will not lose and is consequently the best approach to take, regardless of what the opponent is doing. However, this extreme case also demonstrates effectively how a dominant strategy ruins gameplay: You are not experiencing the game as the designer intended (and it's also the reason why we disapprove of cheat modes in games, but that's another story entirely). Of course, this assumes that people play just to win. However, for most people, a major reason for playing is to have fun, not just to win.

Figure 8.3. Wolfenstein 3D.

graphics/08fig03.jpg

Occasionally, a bug in a game can be exploited to the benefit of the player. For example, in the game Super Turbo Street Fighter 2, the secret character Akuma is completely out of balance with the rest of the characters in the game (see Figure 8.4). This character has an unbeatable attack, the air fireball, which is so superior to the rest of the characters' attacks that they don't stand a chance. Using Akuma is the dominant strategy—if the opponent chooses any other character, she is pretty much assured a loss. If the opponent chooses Akuma also, then given equal skill levels, a draw is the likely outcome. The only option to ensure a fair result is to ban the use of that character in any serious competitive game. It's not that this is the only game that has an unbalanced character, but in other games, the superior character isn't so far out of balance that it ruins the game for other players.

Figure 8.4. Super Turbo Street Fighter 2.

graphics/08fig04.gif

Traditionally, the only way to remove dominant strategies in nontrivial examples is thorough play testing. Unfortunately, there is always some chance that flaws will slip through the net. This chapter covers some of the ways that we can try to prevent this from occurring.

Symmetry

Symmetry is the simplest way of balancing a game. Each player (including the computer) is given the same starting conditions and abilities. This ensures that the outcome of the game is dependent only on the relative skill level of the players. Sounds ideal, doesn't it?

Unfortunately, this approach only works in abstract games such as chess. Can you imagine simulating a real battle with the infantry, knights, and archers lined up facing each other over a perfectly symmetrical field? It would feel unnatural and would quickly become boring. Even though pure symmetry is limited in use to the abstract, there is a way that symmetry can be used to ensure balance without appearing to be contrived.

Pure symmetry works very well for sport simulations. You would expect that two teams playing the same game would be very similar to one another in both form and function. However, the highly standardized world of sport is about the only situation where this pure symmetry is appropriate. In a real-world situation, pure symmetry stands out like a sore thumb.

In Game Architecture and Design, we talked about functional symmetry. This is a form of symmetry where the abilities of the player are roughly—but not exactly—mirrored. That is, they are functionally equivalent, not exactly equivalent.

The example used in Game Architecture and Design concerns a real-time strategy game with various types of landmass—water, mountain, and plain. We can use this as the basis of our example here. All units can travel over the plain, but only air units can travel over mountains, and only water units can travel over water (assume that they are hovercraft that can travel over plain as well as water). Do you see the functional symmetry? Each side has units that are functionally equivalent, but depending on the layout of the level (one player could be surrounded by mountains, the other could be bordered by sea), the way and the proportions in which those units would be used would be different.

Symmetry is mainly useful in balancing n-player games. It can also be used in balancing single player games; it's a good starting point to ensure that the computer-controlled entities are roughly in balance with the player. However, symmetry is a fairly unsophisticated approach and leads to a limited number of directly confrontational strategies. The player runs the risk of being restricted to a simple game of tit-for-tat. The computer throws X at me, so I have to respond with Y, which encourages the computer to throw more X at me, and so on. This does not lead to particularly interesting gameplay, and it shuts out a number of the more interesting gameplay dynamics we could expect if we were to use a more advanced balancing technique in conjunction with functional symmetry.

Transitive Relationships

In a nutshell, a transitive relationship defines a one-way relationship between two or more entities. A can beat B, B can beat C, and C cannot beat anyone (and hence, by implication, A can beat C), as shown in Figure 8.5 and Table 8.3.

Figure 8.5. Transitive relationships.

graphics/08fig05.gif

Table 8.3. Net Payoff Matrix for A, B, and C

 	
A

B

C

A

0

1

1

B

-1

0

1

C

-1

-1

0


Taken at face value, it would seem that transitive relationships are not very useful. Why would anyone want to use C when they could use A? That's where the balancing comes in. So how do you balance the relationship? The more effective entity comes at a higher cost. Note that we don't necessarily mean a direct dollar or points or score cost; the cost could be in the lives of the people sent to fetch the prized entity, or the trials and difficulties that the player has to endure to reach the entity. There is no way of directly quantifying these indirect costs—known as shadow costs—but they should be sufficiently high as to justify the reward. Note that shadow costs are the end result of a number of other factors. They can be measured, but cannot be directly modified.

Pure transitive relationships, without shadow costs to balance them out, lead to trivial and undemanding gameplay choices, which serve to undermine balance. However, shadow costs, together with the possibility of being knocked back down the ladder, allow for an interesting progression/regression dynamic that can lead to some taut and suspenseful gameplay. Care should be taken to ensure that the player can reestablish her previous level. Games such as Diablo from Blizzard Entertainment do this by allowing the player to retrieve her possessions from the corpse of the previous incarnation.

Transitive relationships are very common in games, especially games such as first-person shooters. Think back to the original Doom from id Software. The player starts the game with a relatively weak pistol. Sure, the player can get a little way with it, but each monster takes more than one shot to dispatch, and initial progress is tricky. A little way into the game, the player finds a shotgun, which is a much more effective weapon. The player can now dispatch the monsters with relative ease, allowing him to get further into the game. Now the monsters become harder to kill, and shotgun ammunition becomes scarce.

We're back where we started—with a relatively weak weapon—and we need to search for another stronger weapon to make the same progress we were making before. This is how the game draws us in and impels us to keep playing.

Transitive relationships are mainly used in games with a need to continually drive the player forward toward a goal. The player responds to that need and is rewarded with upgrades and progress, until eventually she reaches the goal, and the game is over.

As such, transitive relationships are only really useful in games that have a definite end point (which is most of them). They are rarely (if at all) used in open-ended games without some way of closing the loop and returning the player back to square one. An example is in the multiplayer arenas of games such as Quake III and Unreal Tournament. Here, the loop is closed by the death of the player, as he is respawned with only the basic weaponry and has to fight his way back up the transitive relationship ladder.

Any game that involves upgrading or augmenting the player's capabilities within the game makes use of transitive relationships. We can think of plenty of examples of games that operate in this fashion. For example:

Super Mario. A series of side-scrolling platform games (see Figure 8.6). The progression is of Mario's abilities. With the first mushroom, he doubles in size, and with subsequent items, his abilities improve further to include flying and invulnerability. These abilities are lost in stages when Mario collides with an enemy.

Figure 8.6. Super Mario Advance.

graphics/08fig06.gif

Legend of Zelda. A series of top-down arcade style role-playing games (except for the Nintendo 64 and GameCube versions, which were full 3D), as shown in Figure 8.7. Link (the hero) collects items to enhance his skills and stamina. The basis of the game is to solve the overall quest by adventuring through a series of dungeons. In general, the prize for each dungeon is a magical item that enhances Link's abilities. A nice little game design touch is that the ability upgraded is the ability that would have been most useful in traversing the dungeon in which it was secreted.

Figure 8.7. Legend of Zelda.

graphics/08fig07.gif

R-Type. A side-scrolling space-based shoot 'em-up (see Figure 8.8). As the player defeats enemies, they drop pods containing weapons upgrades for the player's ship. The cumulative upgrades are lost when your ship is destroyed.

Figure 8.8. R-Type.

graphics/08fig08.gif

Diablo. An isometric 3D action-adventure game (see Figure 8.9). As the player battles through the dungeons, the innovative skill and leveling systems allow you to spend experience points, gained while adventuring, on improving your character.

Figure 8.9. Diablo.

graphics/08fig09.gif

Doom, Quake, Half-Life, and so on. First-person shooters (see Figure 8.10). As you progress through the game, successively better weapons can be found that scale the player's firepower with that of the enemy. You lose the advanced weapons when your avatar is killed.

Figure 8.10. Doom.

graphics/08fig10.gif

The Sims. A "family simulator" that lets the player build and furnish a house and manage the family living within it (see Figure 8.11). For each household item you can purchase, there are upgrades available that function more efficiently. The more money you spend on an item, the more efficiently it does its job—it could take up less space, be prettier, or perform a double function.

Figure 8.11. The Sims.

graphics/08fig11.gif

Intransitive Relationships: Rock, Paper, Scissors

Almost everyone is familiar with the children's game Rock, Paper, Scissors (sometimes called Scissors, Paper, Stone). For those of you who managed to miss this one, the rules are basically summarized as follows: scissors cut paper, paper wraps stone, stone blunts scissors. Two players, the red player and the blue player, choose one of the three glyphs and score the game depending on the rules.

This gives us a balanced, three-way intransitive relationship, as shown in Figure 8.12.

Figure 8.12. Three-way intransitive relationship in Rock, Paper, Scissors.

graphics/08fig12.gif

The net payoff matrix for Rock, Paper, Scissors is shown in Table 8.4.

Table 8.4. Rock, Paper, Scissors

 	
Scissors

Paper

Rock

Scissors

0

1

-1

Paper

-1

0

1

Rock

1

-1

0


Rock, Paper, Scissors is a zero sum game. That is, if the red player wins, the blue player has to lose. If the blue player wins, the red player has to lose. And if the blue player draws, then the red player has to draw as well (and vice versa). Most interesting games are zero sum: The player wins (or player team wins) and the computer (or opposing player/team) loses—or at least, that's the idea.

The three-way intransitive relationship of Rock, Paper, Scissors has been the model for most real-time strategy game balancing and has also been used in other game genres, such as racing games and role-playing games, for many years. Static intransitive relationships—although more aesthetically pleasing than transitive relationships—do not lead to innovative gameplay. It's far too easy for the player to learn the simple relationships between units and figure out the best strategy to use. The game becomes a one-trick pony. The solution to this is to dynamically vary the relationship.

The other problem with the three-way intransitive relationship in its unmodified form that can lead to uninteresting gameplay is that each strategy tends to be used equally, and the pattern can become predictable. In order to make the decisions more interesting, we can vary the shadow costs to alter the likelihood that the particular strategy is chosen.

Let's consider an example of altering shadow cost to affect the relationship. Imagine a confrontation between two craft, A and B. These craft are capable of operating as aircraft or submersibles. Craft A is optimized for flight and is more efficient in the air than in the water. Craft B is optimized for submersible operation and is not as maneuverable in the air. In an air combat situation, A can regularly defeat B. In a submerged combat situation, B regularly defeats A. By altering the environment (and hence, the shadow costs of operating the craft), we introduce an interesting dynamic in the relationship between them. Now, this is just a binary relationship (imagine it as a isolated link in an n-way intransitive relationship); that is, A beats B or B beats A. However, it is not difficult to imagine how this binary relationship could be stretched out over a continuum. For example, if we transferred both craft into a hypothetical semifluid environment that was neither air nor water, where the abilities of both craft cancelled out, we would get a stalemate between them. From here, we could vary the medium's properties one way or the other, giving one of the craft a variable advantage over the other.

Trade-Offs

Not all relationships between entities are a transition between an inferior and a superior entity. One entity might be better than another in some ways and not in others, but a general improvement can sometimes be gained by the transition, depending on the circumstances. (For example, a pistol is great on land compared with a harpoon, but the roles are reversed underwater.)

A good trade-off example can be found in The Sims. When the player earns money and chooses to upgrade the living environment for her Sims, she has a choice of many items of household furniture. Some of these items are better than others in some areas and inferior in others. For example, an expensive couch could improve the appearance of a room (making it more aesthetically pleasing for the Sims), but could be less comfortable than a slightly cheaper and less beauteous couch. The player then has to decide which of the two parameters to maximize.

This sort of balancing act (or stats juggling, as it's affectionately known) is very common in role-playing games. First, the player usually has to generate a character to play with. This is done with a combination of simulated dice rolls and the distribution of a number of points among a number of attributes, such as strength, stamina, and intelligence. After this is done, the player is normally allowed to shift points from one area to another in order to balance out the points.

As a method of achieving balance, point distribution has some merits. Note that it does not have to be restricted to role-playing games and other such number-crunching games. In fact, the player does not even need to know that there has been a point distribution system used. It can be hidden behind the scenes. In most games, there is no need for the player even to be aware (except at the most superficial level) that there is any such distribution of points in place. For example, consider a simple platform game where the player is pitched against a number of different enemies. For each level, the enemies could have a fixed number of points to divide between two attributes, speed and jumping power. This would give us a nice range of enemies of different abilities. In order to ramp up difficulty as the player progresses through the game, the fixed number of points available to distribute could increase with the level. Some of Nintendo's Mario platform games use something close to this approach: The player is given a choice of several characters to play—such as Mario, Luigi, Toad, and Peach—and each character has different levels of ability in jumping, running, and floating.

A few caveats need to be considered, however. In order for the point distribution system to work effectively, all of the attributes must be orthogonal. That is to say, they must be independent attributes. An attribute should not affect the domain of another attribute. Having two closely related attributes, such as weight and floating ability, undermines the point system. The player (or designer) should not be able to gain the same effect by pumping points into one attribute as she could by pumping the points into another.

You also want to make sure that spending a point on one attribute has a similar magnitude of effect as it would on any other attribute. This means that, for example, adding a point to strength should increase the character's strength by the same factor as spending the same amount on improving the character's intelligence.

Combination

Transitive and intransitive relationships don't necessarily have to involve single entities. That is to say, you don't have to specify that one archer beats one unit of infantry. In some cases, two or more entities can be treated as a single entity when balancing a game. For example, even though one unit of infantry may not be enough to beat one archer, you might be able to use a unit of infantry in combination with another unit.

As a designer, you wouldn't necessarily be expected to explicitly design in all of the possible combinations of entities within your game. You do, however, have to be aware of them and to balance the more troublesome ones by modifying the entities themselves and using shadow costs to equalize them. The previously mentioned tank rush from Red Alert could have been avoided by modifying the shadow costs of tanks so that they were much more expensive to produce in the early stages of the game. In the single-player game, this was attempted by disallowing certain units in the earlier levels (a clumsy approach), but multiplayer games are a free-for-all, and the imbalance comes to the fore.

In general, combinatorial effects in your game will not be a significant problem if you pay attention to the basic balance. If your foundation is strong and balanced, the chances are good that you won't run into any major difficulties with combinatorial effects and emergence.

Emergence

Emergence is the action of simple rules combining to produce complex results. The classic example in the computer world is Conway's Game of Life. In this cellular automata simulation (which the majority of people will be familiar with), a few simple rules produce some astoundingly complex results.

"We ended up with a game that I didn't know how to win. I didn't know which were the best strategies or tactics, even though I designed all the game's systems. That is what makes a good strategy game."

—Julian Gollop, referring to X-Com: UFO Defense

Of course, the phenomenon of emergence is not restricted to the domain of the computer. Emergence is ubiquitous in nature. Literally everything you see, touch, taste, hear, and feel is a direct result of emergence. From a few simple rules, the amazing complexity of the universe emerges. The motion of the planets is accurately predicted by the general theory of relativity, our genetic code determines our body shape and size, and a few simple electrochemical interactions in our brains produce our consciousness and personality.

In Chapters 1, "What Is Game Design?" and 2, "Game Concepts," we encouraged you to look for inspiration from many diverse sources. The use (or more accurately, the taming) of emergence is a prime example of this directive. Emergence is a natural phenomenon in its own right. It occurs everywhere, and games that use it effectively are among the best of their type. A good reference work for this phenomenon is Steven Johnson's book Emergence: The Connected Lives of Ants, Brains, Cities, and Software (Touchstone Books).

Let's consider a simple example to illustrate the point. Imagine that our character is on one side of a locked wooden door and wants to get to the other side of the door. There are a number of ways to approach this, ranging from the obvious to the obscure. First, we could find the key and open the door. That's the simplest solution. But let's say we cannot find the key. Let's try picking the lock—no luck there, because we're not skilled enough. Okay, another approach: We'll try and cast our magic Open Sesame spell and open the door magically. Nope—we're fresh out of magic.

In most games, that would be as far as we get. If our progression in the game depended on our getting through that door, we would be stuck and consequently would be forced to go and search for the key, find some way of improving our lock-picking skills, or find a way to replenish our magic and try the spell again. (See the section "Avoiding Stagnation," later in this chapter.)

However, in reality, we know that there would be other ways to get through the door. We could attempt to break it down with an axe or a mace. We could attempt to burn through it using fire or acid. We could try casting a spell to turn it to stone or glass and then shatter it. We could attempt to unscrew the hinges or the lock. We could attempt to use acid to burn through the hinges or the lock. We could try and break our way through the wall next to the door. We could attempt to cast a "ghost" spell on ourselves that lets us pass through solid objects. And these are just the first ideas that came to us—just imagine what else your players will think of.

As game designers, we get away with allowing only a small range of free will for one main reason: The power of the world simulation is limited by hardware and software considerations. We're going to ignore the argument that restricting the range of gameplay choices can also improve gameplay; it's valid in some cases, but here it would be sophistry.

So what does this have to do with emergence? Imagine that we designed our simulation so that we took into account a limited subset of fundamental properties of matter and handled our interactions between objects in that fashion. Then we would consider the door as a collection of connected objects: the hinge, the door itself, and the lock. The door is made of wood. Wood has a set of properties somewhat like this: flammability (high), resistance to acid (average), and strength (average). That takes care of the door. We've stated that it can be burnt, that it can be destroyed with acid, and that it's possible to smash through it, provided that the physics engine handles things at this level. Similarly, the lock and hinges would be made of metal. Metal would have the following properties: flammability (low), resistance to acid (poor), and strength (high). Hence, we could not burn the lock or hinges, but we could melt them with acid, and good luck trying to smash them. Similarly, you could assign properties to the stone wall holding the door that detail whether it could be broken through or not.

This is not a rigorous example, but it forms the basis of a workable system. What we are demonstrating here is the power of emergent properties. You don't need to go overboard trying to cover every conceivable property of matter—just choose a few that make sense within the bounds of your world model. We took three simple properties (flammability, resistance to acid, and strength) and showed how they could determine a wide range of behaviors. In fact, they would let us get to the other side of the door in a number of ways that we may not have even thought of. And that's the power of emergence: complex behaviors resulting from a simple model. Imagine if we had a model that had a few more properties—which would pretty much cover every conceivable way of getting through the door—including bombarding it with frozen marshmallows, if the fancy took us.

As with all tools, emergence has to be used with care. In the prior example, the fact that the player could imagine ways that we haven't considered in order to get through the door makes it difficult for us to control the gameplay directly. If we wanted the door to be a particularly tricky puzzle, we risk undermining the gameplay by providing the player with the freedom to figure out his own way through the door. Emergence is both the bane and the savior of game design. In our opinion, it is the single most valuable tool for taking your game beyond the ordinary, but it can be a double-edged sword. Emergence has its dark side, and in the wrong place, it can undermine gameplay, leading to undesirable dominant strategies or, worse, fatal gameplay flaws.

For example, a series of artificial life games, the Creatures series from CyberLife, relies heavily on emergence (see Figure 8.13). The behavior of the life-forms, the Norns, is determined by a neural network. Although this is a prime example of emergence, it also gives us an example of why emergence isn't the universal panacea it is claimed to be. The problem stems from the fact that Norns learn by positive and negative reinforcement: If something feels good, they'll keep doing it, and if something feels bad, they won't. There's nothing inherently wrong with this—in fact, it's probably the only sensible approach, because it seems to work well enough in the real world. However, within the simplified world of the Norns, it has some unfortunate side effects.

Figure 8.13. Creatures.

graphics/08fig13.gif

For example, in one of the games, there is a still that produces alcoholic beverages. The pleasure reward from drinking at the still is so immediate that all Norns who find their way to the still would simply stay there and get drunk. Unfortunately, this is not nearly as entertaining as it sounds (well, not for long anyway). They get drunk. They fall down. And that's about it. Clearly, this is an undesirable example of emergence. It does not add anything interesting to the game and, in fact, detracts from it.

Feedback Loops

The basic progression of a game is that it starts statically and dynamically balanced and then gets out of balance, first one way and then the other. It goes backward and forward like a seesaw, with one player ahead and then the other, until someone eventually gets so far ahead that it is impossible for the other to catch up.

Often, being ahead tends to make things easier for the player in that position and harder for the other. This is positive feedback that helps the leading player. That is, "the rich get richer and the poor get poorer," as in Monopoly. The more money you have, the more hotels you can put up, which produces more money, and so on. This is a desirable trait as long as it doesn't happen too fast and doesn't leave the player who's behind with no way to catch up. In chess, taking an opponent's piece gives the taker a slight advantage: The other side doesn't have that piece to play with anymore. But in Japanese chess, when you take an opponent's piece, you move it to your side of the board, and it becomes your piece (although it turns into a weaker piece). This confers an additional advantage: Not only does the enemy not have that piece, but you have an extra piece to play with. If you did this with Western chess, the games would be very short indeed.

Therefore, you want positive feedback so that the game will end eventually, but not too much. Most war games, for example Warcraft, don't let you take and use enemy factories; they only let you damage and destroy them. If you could use enemy factories to build armies, the game would become unbalanced too quickly.

You need the keep the players in the balance sweet spot for as long as is practical in order to keep the game fun and let the underdogs have a chance to catch up. A game where the slightest advantage leads to a runaway victory for one player would not be fun. In summary, if you are going to use positive feedback loops in your design, make sure they have a reasonable response time delay before they kick into action.

Or you can counter positive feedback with negative feedback, as well. Suppose taking an enemy piece enables you to use it, but there is a price to be paid for it: It must be supported somehow. This means that taking it is not "free." This was found in Dungeon Keeper: You could torture enemy creatures to convert them to your side, but once you did, they had to have food and money and a place to sleep. The process of converting them also took time, and if you weren't careful, you might kill them without converting them. As a result, it wasn't a strongly dominant strategy. It was a weakly dominant one that was well worthwhile but not absolutely necessary (we won't comment on the morals of simulated torture of imaginary creatures).

Another example is the venerable game of 8-ball pool: The more you get ahead, the more difficult it is to keep sinking shots because you have less balls to target and your opponent has more balls to get in the way.

Another solution to too much positive feedback is to include a random factor that gives the player who's behind a chance to catch up just through sheer luck: throwing double sixes in backgammon, for example. Of course, if the random factor is fair, it might put the player even further behind, too, but at least it adds variety and uncertainty to the game. But the random factor must not be too great, or it overrides the value of good play in the first place and discourages a good player. Why play well if the result amounts to flipping a coin anyway? Poker is a good example of a game with a well-balanced random factor: In any given game, randomness plays a large role, but smart players don't bet large amounts on a single game. Rather, they count on the cumulative effect of good play over many games to reward good players and take money from poor ones. The major factor that determines winners (averaged over a statistically significant number of games) is player skill.

Summary of Static Balance

Static balance boils down to the fact that the balance in most games is simply a dynamic tension (by means of feedback loops) between the transitive and intransitive relationships and the shadow costs for obtaining and transitioning between entities.

Static game balance is only half the story. Setting up the static balance ensures that the initial starting position for the game is in equilibrium. And then along comes a player whose sole aim is to destroy your carefully constructed balance by actually playing the game. So now it's time to set the machine in motion. The next section on dynamic balance covers how to handle balance issues while the player is interacting with the system.