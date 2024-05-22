The origin of strategy games is rooted in their close cousins, board games. If there is any format of game that is closest to the original pre-computer form (where that existed), it is the strategy game. This chapter is the most PC-centric chapter in the entire book, but for good reason: Most strategy games are released for the PC. Console efforts so far have been few and far between.

策略游戏起源于它们的近亲——棋盘游戏。如果说有什么游戏形式最接近电脑前的原始形式（如果有的话），那就是策略游戏了。本章是全书中最以 PC 为中心的一章，但这是有道理的：大多数策略游戏都是针对 PC 发布的，而在游戏机上的策略游戏少之又少。

The benefits that the computer has brought to the strategy game genre include the capability to impartially manage complex rule-sets that would be next to impossible for a human to manage without bogging down the game to a level at which it is no longer fun to play.

电脑给策略游戏带来的好处包括，它可以公正地管理复杂的规则集，而人类几乎不可能管理这些规则集，否则就会使游戏陷入困境，玩起来不再有趣。

On the computer, the strategy game has since diversified into two main forms: classical turn-based strategy games and real-time strategy games. Chronologically, the real-time strategy game arrived on the scene after the turn-based strategy game. Our discussion considers both of these forms.

在电脑上，战略游戏后来发展成两种主要形式：传统的回合制战略游戏和即时战略游戏。从时间上看，即时战略游戏是在回合制战略游戏之后出现的。我们的讨论将考虑这两种形式。

The archetypal example of a computer strategy game is the [Civilization](https://en.wikipedia.org/wiki/Civilization_(series)) series, originally developed by Sid Meier, before splitting off into the watered-down Call to Power offshoots. Fortunately, games such as Alpha Centauri and [Civilization III](https://en.wikipedia.org/wiki/Civilization_III) from Firaxis rescued the franchise from a quiet demise.

电脑策略游戏的典型代表是[《文明》](https://en.wikipedia.org/wiki/Civilization_(series))系列，该系列最初由席德·梅尔开发，后来又衍生出《权力的呼唤》（Call to Power）等掺水的分支游戏。幸运的是，Firaxis 公司推出的[《半人马座阿尔法》](https://en.wikipedia.org/wiki/Sid_Meier%27s_Alpha_Centauri)和[《文明三》](https://en.wikipedia.org/wiki/Civilization_III)等游戏将该系列游戏从悄然消亡中拯救出来。

Intriguingly, the computer game [Civilization III](https://en.wikipedia.org/wiki/Civilization_III) has made a rare transition: from a computer game to a board game. [Civilization III: The Board Game](https://boardgamegeek.com/boardgame/3633/sid-meiers-civilization-the-boardgame) was released in October 2002, featuring three sets of rules (basic, standard, and advanced) and 784 plastic miniature pieces. Not surprisingly, Civilization III: The Board Game is significantly more complex than [Advanced Civilization](https://en.wikipedia.org/wiki/Advanced_Civilization), the board game that the original Sid Meier's [Civilization](https://en.wikipedia.org/wiki/Civilization_(series)) game was based on in the first place. This is good evidence that although translating and enhancing board games to the computer is an excellent method of producing compelling and fun strategy games, the converse is not necessarily true.

耐人寻味的是，电脑游戏[《文明三》](https://en.wikipedia.org/wiki/Civilization_III)罕见地实现了从电脑游戏到棋盘游戏的转变。[《文明三：棋盘游戏》](https://boardgamegeek.com/boardgame/3633/sid-meiers-civilization-the-boardgame)于 2002 年 10 月发行，有三套规则（基本规则、标准规则和高级规则）和 784 个塑料小棋子。毫不奇怪，[《文明三：棋盘游戏》](https://boardgamegeek.com/boardgame/3633/sid-meiers-civilization-the-boardgame)要比[《高级文明》](https://en.wikipedia.org/wiki/Advanced_Civilization)复杂得多，而[《高级文明》](https://en.wikipedia.org/wiki/Advanced_Civilization)正是席德·梅尔的[《文明》](https://en.wikipedia.org/wiki/Civilization_(series))游戏的原型。这充分证明，虽然将棋盘游戏转换到电脑上并对其进行改进，是制作引人入胜且有趣的策略游戏的绝佳方法，但反之亦然。

However, the comparative simplicity of the rules of computer-based strategy games (compared to other genres) lends itself to a good analysis of the effectiveness of the rules of play. In essence, strategy games are the easiest genre in which to generate a consistent and balanced rule-set. That is not to say that they are easier to design. However, the rules are easier to analyze for balance, mainly due to the discrete turn-based nature of the gameplay that most strategy games exhibit.

不过，电脑策略游戏的规则相对简单（与其他类型游戏相比），这就为分析游戏规则的有效性提供了很好的依据。从本质上讲，策略游戏是最容易产生一致且平衡的规则集的游戏类型。这并不是说它们更容易设计。然而，主要由于大多数策略游戏都具有离散的回合制游戏性质，因此更容易对规则进行平衡分析。

As a general rule, pure strategy games tend to be turn-based rather than real-time. Strategic thinking, at least in the arena of gameplay, does not lend itself well to real-time action. The player often prefers to mull over his moves, considering the impact of one choice over another. In board games, this can result in frustrating "analysis paralysis," in which one player spends a large amount of time min-maxing his move and breaks the flow of the game. Fortunately, computers are infinitely patient, so this sort of behavior should be tolerated—although it should not be required by the game design.

一般来说，纯策略游戏倾向于回合制而非即时制。至少在游戏领域，战略思维并不适合实时操作。玩家通常更喜欢琢磨自己的行动，考虑一个选择对另一个选择的影响。在棋盘游戏中，这可能会导致令人沮丧的“分析瘫痪”，即一名玩家花费大量时间对自己的棋步进行最小化，从而破坏了游戏的流畅性。幸运的是，计算机有无限的耐心，因此这种行为应该被容忍——尽管游戏设计不应该要求这样做。

{% hint style="info" %}
译者注：min-max，是一种策略，通常用于游戏理论和决策过程中，尤其是在那些涉及竞争和优化决策的场景中。这个术语是由数学家约翰·冯·诺伊曼在博弈论的背景下提出的。

在"min-max"策略中，玩家尝试最小化可能的最大损失（minimize the maximum loss），或者在某些情况下，最大化可能的最小收益（maximize the minimum gain）。换句话说，玩家在制定策略时会考虑最坏的情况，并试图在这个最坏情况下实现最佳结果。
{% endhint %}

An offshoot of the turn-based strategy game concept is the real-time strategy (RTS) genre. Westwood's Dune II is considered to be the first true real-time strategy game, although we believe that the game Battlemaster (screens from which are shown in Figure 10.1), released in 1990 for the Commodore Amiga and Atari ST computers, marks the true origin of the RTS genre.

回合制战略游戏概念的一个分支是实时战略（RTS）类型。韦斯特伍德的《沙丘 II》被认为是第一款真正意义上的即时战略游戏，不过我们认为，1990 年在 Commodore Amiga 和 Atari ST 电脑上发布的游戏《Battlemaster》（其画面如图 10.1 所示）才是即时战略类型的真正起源。

Figure 10.1. Battlemaster. 图 10.1. Battlemaster.

graphics/10fig01.jpg

RTS games are differentiated from pure strategy games in that time is a constant pressure. There are no "turns" during which the player can ponder his moves—everything happens at once. Consequently, reaction time and quick action are as important as strategic thinking.

Although the RTS game breathed new life into the strategy genre, and although titles such as Dune II, Warcraft, and Age of Empires propelled it into mass-market acceptance, there has been little innovation to maintain this momentum over the past few years.

Aside from growing more complex, prettier, and larger over the years, the fundamental design of the RTS has remained virtually unchanged since the beginning.