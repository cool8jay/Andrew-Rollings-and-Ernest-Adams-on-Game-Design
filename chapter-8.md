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

这些问题并不容易回答；对一个人来说可能正确的答案，对另一个人来说可能完全不正确。从某种程度上说，这些问题不可能有最终确定的答案。就像游戏设计中的许多其他问题一样，答案包含了一个未知数：玩家。

Although we can attempt to anticipate what sort of people will play our game, we will never be able to satisfy all of them. However, as fallacious as it may seem, we have to start somewhere. In balancing a game, we have to assume the existence of an average player and target the balance to suit that player. Remember, however, that your average player will not be anywhere near as skilled at computer games as you and your team. Don't fall for the extremely common mistake of "making a game that you enjoy playing." This statement has been the epithet for many promising games. The danger of aiming to make a game that you enjoy playing is that you run the risk of making a game that only you enjoy playing. A significant level of "dumbing down" may be required to make your game as accessible as possible to the average player. Do not be alarmed by this; you can cater for extremes by providing different difficulty settings, as necessary. So with this in mind, let's explore the subject of game balancing in more detail.

尽管我们可以尝试预测什么样的人会玩我们的游戏，但我们永远无法满足所有的人。然而，尽管看起来有些谬误，但我们总得有个起点。在平衡游戏时，我们必须假定存在一个普通玩家，并针对这个玩家来平衡游戏。但请记住，普通玩家的电脑游戏水平远不及你和你的团队。不要陷入“做自己喜欢玩的游戏”这一极其常见的错误。这句话是许多有前途游戏的代名词。以制作自己喜欢玩的游戏为目标的危险在于，你有可能制作出只有你自己喜欢玩的游戏。为了让普通玩家也能玩到你的游戏，你可能需要进行相当程度的“简化”。对此不要惊慌；你可以根据需要提供不同的难度设置，以满足极端情况的需要。有鉴于此，让我们来详细探讨一下游戏平衡的问题。

# What Is Game Balance? 什么是游戏平衡？

Many games are released each year that commit fundamental game design errors. These games are fatally flawed from the outset, and short of a monumental marketing campaign and a small spate of miracles, they are doomed to failure. There are many obvious reasons for this kind of spectacular failure, such as bad coding, buggy software, poor quality control, and substandard graphics.

每年都有许多游戏在发布时犯了基本的游戏设计错误。这些游戏从一开始就存在致命的缺陷，如果没有巨大的营销活动和一连串的奇迹，它们注定要失败。造成这种重大失败的原因显而易见，如糟糕的编码、漏洞百出的软件、糟糕的质量控制和不合格的画面。

However, on many occasions, the cause of failure is not so immediately obvious. The game may look okay, sound okay, and even to some extent play okay, but it still fails commercially. One of the reasons for failure (and the one we are going to concern ourselves with here) is poor game design. In [Chapter 7](chapter-7.md), "Gameplay," we introduced the elements of gameplay that we expect to find in games. We also touched a little on the subject of game balance. Including all the expected elements in a game does no good if they are not in balance with one another and with the player.

然而，在许多情况下，失败的原因并不那么显而易见。游戏可能看起来还行，听起来还行，甚至在某种程度上玩起来还行，但在商业上仍然失败了。失败的原因之一（也是我们在这里要讨论的原因）是游戏设计不佳。在[第七章](chapter-7.md)“游戏性”中，我们介绍了我们期望在游戏中发现的游戏性要素。我们还略微谈到了游戏平衡的问题。如果游戏中的所有预期元素不能相互平衡，也不能与玩家平衡，那么在游戏中加入所有这些元素都是没有用的。

But what exactly do we mean by a balanced game? A balanced game is one where the main determining factor for the success of the player is the skill level of that player. That does not mean that random events cannot occur, but a better player should ordinarily be more successful than a poor one unless he has an unusually long run of bad luck.

但我们所说的平衡的游戏到底是什么意思呢？平衡的游戏是指决定玩家成败的主要因素是玩家的技术水平。这并不意味着随机事件不可能发生，但通常情况下，一个较好的玩家应该比一个较差的玩家更容易成功，除非他的运气异常糟糕。

Traditionally, game balance has been very much a trial-and-error process. The game is played, the game is tweaked, the game is played, the game is tweaked, and then finally, when time runs out, the game is released (and usually tweaked further in the form of patches).

传统上，游戏平衡在很大程度上是一个试错过程。游戏被玩，游戏被调整，游戏被玩，游戏被调整，最后，当时间耗尽时，游戏被发布（通常以补丁的形式进一步调整）。

So why are there no formalized, scientifically rigorous methods of game balancing? Well, for a start, it's an extremely difficult and complex process. Essentially, game balancing is a problem involving a fantastically large number of independent variables. It's an optimization problem in n-dimensional space where n is a very large number. No formal rules govern game balancing, except in a very small number of abstract mathematical scenarios.

那么，为什么没有正式的、科学严谨的游戏平衡方法呢？首先，这是一个极其困难和复杂的过程。从本质上讲，游戏平衡是一个涉及大量独立变量的问题。它是 n 维空间中的一个优化问题，其中 n 是一个非常大的数字。除了极少数抽象的数学场景之外，游戏平衡没有正式的规则可循。

Classical game theory is simply not suited to this kind of problem. Most areas of research concern themselves with games in which there are discrete player turns and a limited number of variables. This type of theory is ideal for analyzing games of chance, such as poker and coin-toss games, but it would be nearly impossible to use for the analysis of more complex games, such as computer games, which are more often continuous and have hundreds, if not thousands, of independent variables. Also, the majority of game theory is concerned with finding the optimum way to play a game. Using game theory to balance a game would be like playing a twisted version of Jeopardy—starting with the answer and working back to the best possible question. (It's possible that one day there might be some sort of "game calculus" invented to handle these problems, but we're not going to hold our collective breath. Besides, that still doesn't solve the problem of how to break down the game into a list of strategies and variables to fit into the equations.)

经典博弈论根本不适合这类问题。大多数研究领域关注的是玩家回合离散、变量数量有限的博弈。这类理论非常适合分析扑克牌和投掷硬币游戏等偶然性游戏，但几乎不可能用来分析电脑游戏等更复杂的游戏，因为电脑游戏通常是连续的，有成百上千个独立变量。此外，博弈论的大部分内容都与寻找最佳游戏方式有关。用博弈论来平衡一个游戏，就像是在玩一个改版的[危险边缘](https://en.wikipedia.org/wiki/Jeopardy!)——从答案开始，再回到最佳可能的问题。(也许有一天会发明出某种“游戏微积分”来处理这些问题，但我们不会集体屏息以待。此外，这仍然无法解决如何将游戏分解成一系列策略和变量来纳入方程的问题）。

This sort of n-dimensional optimization problem occurs in many areas of science, and it is from these areas that we can borrow techniques to help us solve the problem. This is not to say that all game-balancing problems can be solved by the blanket application of a sterile algorithm. A healthy measure of human finesse is still required in order to make a game feel "just right." Just because a result is mathematically correct does not automatically make it aesthetically pleasing.

这种 n 维优化问题出现在许多科学领域，我们可以从这些领域借鉴技术来帮助我们解决问题。这并不是说，所有的游戏平衡问题都可以一概采用无菌算法来解决。为了让游戏感觉“恰到好处”，仍然需要一定程度的人为技巧。一个结果在数学上是正确的，但并不意味着它在美学上也是令人愉悦的。

In fact, the tweak-play-tweak method of game balancing is a valid approach (and is pretty much the only approach so far). The only problem is that this method is time- and resource-intensive and is extremely prone to error. Worse still, balancing a game is a very difficult concept to grasp. After all, what are you balancing it against? Are you balancing it against itself? The player? And how exactly are you balancing it? Are you balancing it so that it is a fair game? Are you balancing it so that it provides a consistent experience to the player no matter what her ability? The answers to these questions are—at least to some degree—subjective and depend upon the nature of the game. For example, a historically accurate simulation of the Anglo-Zulu wars would not be a fair game. The Zulus would have to lose, which would be a bit depressing for the Zulu player.

事实上，“调整——游戏——调整”的游戏平衡方法是一种有效的方法（而且几乎是目前唯一的方法）。唯一的问题是，这种方法需要耗费大量时间和资源，而且极易出错。更糟糕的是，平衡游戏是一个很难掌握的概念。毕竟，你在平衡什么？是平衡游戏本身？还是玩家？你到底是如何平衡的？你是在平衡游戏的公平性？你是否在平衡它，以便无论玩家的能力如何，都能为其提供一致的体验？这些问题的答案至少在某种程度上是主观的，而且取决于游戏的性质。例如，一个符合历史的盎格鲁-祖鲁战争模拟游戏就不会是一个公平的游戏。祖鲁人必须输，这对祖鲁人玩家来说有点令人沮丧。

Even a nonrealistic game has to take some liberties in order to obtain balance. For example, a hypothetical game that simulates the invasion of modern-day Earth by a race of aliens has to give the humans a chance to win. And in spite of what you've seen in films like Independence Day, any race that is advanced enough to move huge ships across hundreds or thousands of light-years probably wouldn't have much difficulty mopping up a small planet like ours—and they certainly wouldn't have computers that interfaced with an Apple Macintosh, conveniently allowing us to destroy their whole operation. In order to base a game around such a scenario, we'd have to stretch credibility to the breaking point, in that with today's technology we could actually defeat a race of advanced aliens whose sole specialty is enslaving entire worlds. Human "pluck" will only take us so far.

即使是非现实主义的游戏，也必须进行一些改动以取得平衡。例如，一款模拟外星人入侵现代地球的假想游戏必须给人类以获胜的机会。尽管你曾在《独立日》等电影中看到过，但任何先进到可以移动巨大飞船穿越数百或数千光年的种族，在攻占像我们这样的小星球时可能毫不费力——而且他们肯定不会拥有能与苹果 Macintosh 电脑连接的电脑，方便我们摧毁他们的整个行动。如果要围绕这样的场景来制作游戏，我们就必须把可信度提高到极致，那就是以现在的技术，我们真的可以打败一个专门奴役整个世界的先进外星种族。人类的“勇气”只能到此为止。

Before we get into the gritty detail, we should briefly describe what it is that we are actually balancing. There are several ways of implementing balance in a game, centered around how the equilibrium is maintained. In particular, there are two broad classes of balance that we will be discussing: static balance and dynamic balance. Traditionally, balance has not been differentiated in this fashion; when game balance is referred to, it is usually referred to as a whole, comprising both the static and the dynamic balance. Often, you will hear discussion in terms of the opening, the midgame, and the endgame, much as you would in chess. This is a perfectly valid, if a little rudimentary, approach; it's fine for the discussion of a game that has already been written, but when we are designing a new game, we would like to be able to go to a finer grain of detail. It has often been said, however, that the degree of understanding of a subject is directly proportional to the sophistication of the available language used to describe it. For our discussion, referring to balance as a whole rather than distinguishing between the two areas of balance is an unnecessary handicap that we would rather avoid.

在深入探讨具体细节之前，我们应该简要介绍一下我们究竟要平衡什么。在游戏中实现平衡有几种方法，其核心是如何保持平衡。具体来说，我们将讨论两大类平衡：静态平衡和动态平衡。传统上，平衡并不是以这种方式区分的；当提到游戏平衡时，通常指的是由静态平衡和动态平衡组成的一个整体。你经常会听到关于开局、中盘和尾盘的讨论，就像在国际象棋中一样。这种方法完全正确，尽管有些粗略；对于讨论已经制作好的游戏来说，这种方法还不错，但当我们设计新游戏时，我们希望能对细节进行更精细的处理。不过，人们常说，对某一主题的理解程度与描述该主题的可用语言的复杂程度成正比。在我们的讨论中，将平衡作为一个整体来提及，而不是区分平衡的两个方面，是一种不必要的障碍，我们宁愿避免这种障碍。

# Static Balance 静态平衡

Static balance is concerned with the rules of the game and how they interact with each other. These are specifically time invariant. In other words, these are the rules of the game that can be written down and documented to aid play—the usual strategy guide fodder.

静态平衡关注的是游戏规则及其如何相互作用。这些规则不受时间变化影响。换句话说，这些游戏规则可以写下来并记录在案，以帮助玩家进行游戏——通常的策略指南的内容。

A concrete example would be a comparison of the relative strengths of units in a war game, or the average jumping distance of Mario in relation to the average distance between platforms. Generally, when game balance is spoken about, most people are unconsciously referring to the static balance (sometimes mixed with a little of the dynamic balance).

一个具体的例子就是比较战争游戏中各单位的相对实力，或者马里奥的平均跳跃距离与平台之间的平均距离的关系。一般来说，当谈到游戏平衡时，大多数人都会不自觉地提到静态平衡（有时会掺杂一点动态平衡）。

Static balance is the classic game balance that is talked about in other books, including Game Architecture and Design, also from New Riders (although we did delve somewhat into the subject of dynamic balance in that book, without specifically naming it as such). This is the process whereby we ensure that the game is fair and all elements interlock seamlessly to avoid dominant and recessive strategies that can ruin a game.

静态平衡是经典的游戏平衡，在其他书籍中也有提及，包括同样出自 New Riders 的《游戏架构与设计》（尽管我们在该书中也稍微探讨了动态平衡的主题，但并没有明确将其命名为如此）。在这个过程中，我们要确保游戏是公平的，所有元素都能无缝衔接，避免出现可能毁掉一个游戏的优势策略和劣势策略。

## Randomness and Average Values 随机性和平均值

In the following few sections, we are going to discuss balancing gameplay elements using payoff matrices to demonstrate some of the points. Payoff matrices are used to illustrate the balance between elements of the game.

在接下来的几节中，我们将使用回报矩阵来讨论平衡游戏元素的问题，以说明其中的一些要点。回报矩阵用于说明游戏元素之间的平衡。

For example, let's take a symmetrical game involving two players: red and blue. Each of these players has two strategies that it can use: R1, R2, B1, and B2.

例如，让我们以一个对称游戏为例，游戏中有两名玩家：红方和蓝方。每个玩家都有两种策略可以使用： R1、R2、B1 和 B2。

Let's say that R2 beats B1 with a payoff of 3, B2 beats R1 with a payoff of -2, B1 draws with R1, and R2 draws with B2, as shown in Table 8.1.

假设 R2 以 3 的回报击败 B1，B2 以 -2 的回报击败 R1，B1 与 R1 平局，R2 与 B2 平局，如表 8.1 所示。

Table 8.1. A Simple Net Payoff Matrix 表 8.1. 简单净收益矩阵

||B1|B2|
|---|---|---|
|R1|0|-2|
|R2|3|0|

Note that negative numbers indicate a win to blue, and positive numbers indicate a win to red.

注意，负数表示蓝方获胜，正数表示红方获胜。

This doesn't have to mean that for each play of the game, R2 beats B1—occasionally the converse could occur. It depends on the nature of the game. What it is generally taken to mean is that the net payoff is that value. In some cases, the strategy B1 could pay more or less against the strategy R1 (subject to the whims of chance), but the average value of the payoff over time would tend to the specified value.

这并不意味着每次下棋时，R2 都能击败 B1，偶尔也会出现相反的情况。这取决于游戏的性质。一般来说，这意味着净收益就是这个值。在某些情况下，策略 B1 对策略 R1 的收益可能多一些，也可能少一些（取决于偶然性），但随着时间的推移，收益的平均值会趋向于指定值。

This is especially important to realize when we are considering net payoff strategies for computer games. We have to deal with a large number of random events that do not necessarily all have the same result, but that will tend toward a certain value; hence, the net payoff tends toward a discrete value. If we were to attempt to examine each of the separate results as an individual strategy, rather than taking an average of all similar events (for example, knight versus archer combat), then the analysis would soon become unmanageable (and without meaning).

当我们考虑电脑游戏的净收益策略时，认识到这一点尤为重要。我们必须处理大量的随机事件，这些事件不一定都有相同的结果，但都会趋向于某个值；因此，净收益会趋向于一个离散值。如果我们试图把每个独立的结果都作为一个单独的策略来研究，而不是对所有类似事件（例如，骑士对弓箭手的战斗）进行平均，那么分析很快就会变得难以管理（而且没有意义）。

## Dominant Strategies 优势策略

Dominant strategy is a term from classic game theory. A dominant strategy is one that surpasses all others by being the best one to choose under any circumstances. That does not mean that it guarantees winning, but it should guarantee not losing. (To be exact, a strongly dominant strategy guarantees winning, while a weakly dominant strategy guarantees not losing.)

优势策略是经典博弈论中的一个术语。优势策略是指在任何情况下都能超越其他策略，成为最佳选择的策略。这并不意味着它一定能赢，但它应该能保证不输。(确切地说，强优势策略保证赢，而弱优势策略保证不输）。

A strongly dominant strategy is never desirable, but care should be taken when excising weakly dominant strategies—sometimes they can be valuable (for example, forcing a draw in chess). When eliminating a weakly dominant strategy, make sure you're not throwing the baby out with the bath water.

强优势策略从来都不是（设计者）想要的，但在剔除弱优势策略时应小心谨慎——有时它们可能很有价值（例如，在国际象棋中迫使对手和棋）。在剔除弱优势策略时，要确保不会把孩子和洗澡水一起倒掉。

The difficulty in applying these concepts from classic game theory to real games is the massive increase in complexity. A typical game theory example deals with a simple game with known parameters, such as the tossing of a coin, whereas a game such as Westwood's [Command and Conquer: Red Alert](https://en.wikipedia.org/wiki/Command_%26_Conquer:_Red_Alert) has many hundreds of variables—too many, in fact to be able to deal with rigorously—and the values that they take are effectively continuous, not discrete like the heads or tails of a coin toss. To us, this means that the labeling of strategies as dominant takes on a bit of fuzziness. There is no discrete boundary. What would be a dominant strategy in the hands of one player is a guaranteed loser in the hands of another.

将经典博弈论中的这些概念应用到现实游戏中的困难在于复杂性的大幅增加。一个典型的博弈论例子涉及的是一个已知参数的简单游戏，比如掷硬币，而西木的[《命令与征服：红色警戒》](https://en.wikipedia.org/wiki/Command_%26_Conquer:_Red_Alert)等游戏则有数以百计的变量，多到无法严格处理，而且这些变量的取值实际上是连续的，而不是像抛硬币的正反面那样离散。对我们来说，这意味着将策略标注为优势策略的做法有些模糊。没有离散的边界。在一个玩家手中是占优的策略，在另一个玩家手中就一定是输家。

The ideal solution to this would be to talk in terms of an idealized perfect player who only makes perfect decisions. Unfortunately, although that would result in mathematically correct games, they almost certainly would not be fun. The players of our games are real people, with different attitudes, abilities, likes, and dislikes, and we would be doing them (and ourselves) a great disservice by trying to shoehorn them into a particular box to fit some theory. And that's the biggest problem we have in balancing a game: No matter how much perfect math and science we can apply to the problem, it will only take us so far. The rest is up to us, as game designers. In fact, it's this final stage of game balancing that really distinguishes the greats of game design, such as Shigeru Miyamoto, Brian Reynolds, Sid Meier, and Dani Berry.

解决这个问题的理想办法是用理想化的完美玩家来说话，他只会做出完美的决定。不幸的是，虽然这样做会产生数学上正确的游戏，但几乎可以肯定它们不会有趣。我们游戏中的玩家都是真实的人，他们有着不同的态度、能力、喜好和厌恶，如果我们试图把他们塞进一个特定的框框里来迎合某些理论，那就是对他们（和我们自己）的极大伤害。这就是我们在平衡游戏时遇到的最大问题： 无论我们能把多么完美的数学和科学应用到这个问题上，也只能做到这一步。剩下的就要靠我们游戏设计师自己了。事实上，正是游戏平衡的最后阶段让宫本茂、布莱恩·雷诺兹、席德·梅尔和丹妮·贝瑞等游戏设计大师脱颖而出。

Let's look at a trivial example of a dominant strategy and then look at some real-world games that also have dominant strategies.

让我们来看一个微小的优势策略的例子，然后再看看现实世界中也有优势策略的一些游戏。

You're returning home from a busy day at the office, when suddenly you wonder whether it's your wife's birthday today. Should you buy flowers or not?

在办公室忙碌了一天的你回到家，突然想知道今天是不是妻子的生日。到底要不要买花呢？

The risks you take are as follows: If it is your wife's birthday, and you buy flowers, you win 10 brownie points, because you remembered her birthday. If it's not her birthday, you will win 20 brownie points, because you have surprised her with your thoughtfulness.

你要承担的风险如下：如果今天是你妻子的生日，你买了花，你就赢得了 10 布朗尼分，因为你记得她的生日。如果不是她的生日，你会赢得 20 布朗尼分，因为你的体贴给了她一个惊喜。

Alternatively, you could decide that it is not her birthday and you don't need to buy any flowers. In this case, if you are wrong and it actually is her birthday, you take a big hit in brownie points—you lose 100 of them. If it's not her birthday and you don't buy her flowers, then everything is normal when you get home, and you neither gain nor lose any brownie points.

或者，你也可以认为今天不是她的生日，不需要买花。在这种情况下，如果你错了，今天确实是她的生日，你的积分就会大打折扣——失去 100 分。如果不是她的生日，你也没有给她买花，那么回家后一切正常，你既不会获得也不会失去任何布朗尼积分。

{% hint style="info" %}
译者注：brownie points，布朗尼积分，用来描述在人际关系中通过做某些事情来赢得（通常是配偶）好感或优势的行为。
{% endhint %}

The net payoff matrix for this game is shown in Table 8.2.

该游戏的净收益矩阵如表 8.2 所示。

||Wife's Birthday 是妻子的生日|Not Wife's Birthday 不是妻子的生日|
|---|---|---|
|Buy Flowers 买花|10|20|
|Don't Buy Flowers 不买花|-100|0|

Quite clearly, the dominant strategy is to always buy flowers, because you will always get a positive payoff. (An even more obvious strategy, although outside the bounds of this example, is to make sure you remember your wife's birthday in the first place.)

很明显，优势策略是总是买花，因为你总是会得到正回报。(还有一个更明显的策略，虽然不在本例的讨论范围之内，那就是首先确保你记得你妻子的生日）。

The second strategy—don't buy flowers—would be immediately discounted by any rational game player; the strategy only guarantees a zero payoff at best, and a massive loss in the worst-case scenario.

第二种策略——不买花——会立即被任何理性的玩家所否定；这种策略最多只能保证零回报，而在最坏的情况下则会造成巨大损失。

Of course, to turn this example into a real game decision (by eliminating the dominant strategy), we would have to attribute some cost to the flowers so that buying flowers when it is not her birthday results in a negative payoff. We'd also have to figure out the exchange rate between dollars and brownie points.

当然，如果要把这个例子变成一个真实的博弈决策（通过消除优势策略），我们就必须为鲜花赋予一定的成本，这样在不是她生日的时候买花就会带来负收益。我们还必须计算出美元和布朗尼积分之间的汇率。

Unfortunately, only the most trivial examples can be broken down into a simple payoff matrix. For a more complicated example, we should examine the previously mentioned Red Alert (see Figure 8.1). This game is famed for a particular dominant (or near dominant) strategy, which has become known as the tank rush (a name that has spread to similar strategies in other games).

遗憾的是，只有最微小的例子才能分解成一个简单的回报矩阵。对于更为复杂的例子，我们应该看看前面提到的[《红色警戒》](https://en.wikipedia.org/wiki/Command_%26_Conquer:_Red_Alert)（见图 8.1）。这款游戏因一种特别的优势（或接近优势）策略而闻名，这种策略被称为“坦克快攻”（这一名称已扩展到其他游戏中的类似策略）。

Figure 8.1. Red Alert. 图 8.1. 《红色警戒》。

graphics/08fig01.gif

An experienced player playing as the Soviet side could devote all of her energies to producing a large force of tanks in the early part of the game, and then use those tanks to attack the nascent enemy base en masse. Against an unprepared opponent, this almost always guarantees a victory. Of course, because of the immense number of variables involved, we cannot say with certainty that this is a dominant strategy—that is, it may not be the best strategy to play regardless of what the opponent does—but it is certainly near dominant.

一名经验丰富的苏联方玩家可以在游戏初期投入全部精力生产大量坦克，然后利用这些坦克大举进攻新生的敌方基地。面对毫无准备的对手，这样做几乎总能获胜。当然，由于其中涉及大量变量，我们不能肯定说这是一种优势策略，也就是说，无论对手怎么做，这都不一定是最佳策略，但肯定是接近占优势的策略。

Another real-world example, again from a real-time strategy game, occurred because of relative unit strength mismatches. In the original Warcraft game from Blizzard Entertainment, the Orc player was almost always guaranteed victory if he was able to produce warlocks (see Figure 8.2). Once a warlock was in play, it could be used to create an army of powerful demons. This almost always guaranteed a win for the Orc player and was a strategy worth playing, whatever the opposing player did. In fact, we found that the only way to guarantee a fair game in the original Warcraft was to explicitly agree to disallow any magical warfare.

另一个现实世界中的例子同样来自于即时战略游戏，这是因为相对的单位实力不匹配造成的。在暴雪娱乐公司最初推出的《魔兽争霸》游戏中，如果半兽人玩家能够生产术士，那么他几乎总是能保证取得胜利（见图 8.2）。一旦有了术士，它就可以用来组建一支强大的恶魔大军。这几乎总能保证半兽人玩家获胜，无论对方玩家做什么，这都是值得一试的策略。事实上，我们发现在最初的《魔兽争霸》中，保证游戏公平的唯一方法就是明确同意不允许任何魔法战。

Figure 8.2. Warcraft. 图 8.2. 《魔兽争霸》。

graphics/08fig02.gif

These examples are both from real-time strategy games. This type of game is often the easiest to analyze, because it so closely matches the areas of research in conventional military game theory. However, we don't want to give the impression that we are only concerned with real-time strategy games, so our last example of a dominant strategy is one that affected an old side-scrolling space shooter game on the Nintendo Super NES. In this game (which we will not name to prevent embarrassment on the part of the individuals responsible), it was possible to make your way through the entire game by upgrading your weapons to a certain level and then, going as low on the screen as possible, keeping your finger on the fire button. In this position, you were invulnerable to the enemy attacks and could finish the game on a single life. This is a clear example of a dominant strategy.

这些例子都来自即时战略游戏。这类游戏通常最容易分析，因为它与传统军事博弈论的研究领域非常吻合。不过，我们不想给人留下我们只关注即时战略游戏的印象，所以我们最后一个优势策略的例子是任天堂超级 NES 上的一款老式横向卷轴太空射击游戏。在这款游戏中（为避免相关责任人尴尬，我们就不点名了），只要把武器升级到一定级别，然后尽可能地降低屏幕高度，把手指放在开火按钮上，就可以通关整个游戏。在这种情况下，你对敌人的攻击无懈可击，并且可以用一条命完成游戏。这就是优势策略的一个明显例子。

All these examples show why dominant strategies are a bad thing, and why we must strive to avoid them in our games. They ruin gameplay. The presence of a single dominant strategy is enough to render a good portion of our intended gameplay obsolete. All other strategies that may potentially be used in the same circumstances are recessive strategies, and no rational player would choose to use them.

所有这些例子都说明了为什么优势策略是一件坏事，为什么我们必须在游戏中努力避免它们。它们会破坏游戏性。单单一个优势策略的存在足以使我们的大部分游戏玩法变得无效。在相同情况下可能使用的所有其他策略都是劣势策略，没有理性的玩家会选择使用它们。

An interesting point to examine is where to draw the line between a valid (but undesirable) dominant strategy and plain cheating. For example, some players may view the strategies mentioned earlier as cheating, whereas others would be of the view that if the game system allows it, it is a valid strategy. The question is, where does this leave the classic "God Mode" present in virtually all first-person shooters since the original [Wolfenstein 3D](https://en.wikipedia.org/wiki/Wolfenstein_3D) (see Figure 8.3)? Taken from a game theory purist point of view, the obvious dominant strategy is to use the God Mode when playing the game. Why? Because it guarantees that you will not lose and is consequently the best approach to take, regardless of what the opponent is doing. However, this extreme case also demonstrates effectively how a dominant strategy ruins gameplay: You are not experiencing the game as the designer intended (and it's also the reason why we disapprove of cheat modes in games, but that's another story entirely). Of course, this assumes that people play just to win. However, for most people, a major reason for playing is to have fun, not just to win.

一个值得研究的问题是，在有效（但不可取）的优势策略和纯粹的作弊之间，该如何划清界限。例如，一些玩家可能会把前面提到的策略视为作弊，而另一些玩家则认为，如果游戏系统允许，这就是有效的策略。问题是，自最初的[《德军总部 3D》](https://en.wikipedia.org/wiki/Wolfenstein_3D)（见图 8.3）以来，几乎所有第一人称射击游戏中都有经典的“上帝模式”，那么这种模式将何去何从？从游戏理论纯粹主义的角度来看，显而易见的优势策略就是在玩游戏时使用“上帝模式”。为什么呢？因为它能保证你不会输，因此无论对手在做什么，它都是最佳策略。然而，这种极端情况也有效地说明了优势策略是如何破坏游戏性的：你并没有按照设计者的意图来体验游戏（这也是我们不赞成在游戏中使用作弊模式的原因，但这完全是另一回事）。当然，这只是假设人们玩游戏只是为了赢。然而，对大多数人来说，玩游戏的主要目的是为了开心，而不仅仅是为了赢。

Figure 8.3. Wolfenstein 3D. 图 8.3. 《德军总部 3D》。

graphics/08fig03.jpg

Occasionally, a bug in a game can be exploited to the benefit of the player. For example, in the game Super Turbo Street Fighter 2, the secret character Akuma is completely out of balance with the rest of the characters in the game (see Figure 8.4). This character has an unbeatable attack, the air fireball, which is so superior to the rest of the characters' attacks that they don't stand a chance. Using Akuma is the dominant strategy—if the opponent chooses any other character, she is pretty much assured a loss. If the opponent chooses Akuma also, then given equal skill levels, a draw is the likely outcome. The only option to ensure a fair result is to ban the use of that character in any serious competitive game. It's not that this is the only game that has an unbalanced character, but in other games, the superior character isn't so far out of balance that it ruins the game for other players.

有时，游戏中的错误会被玩家利用，使其获益。例如，在游戏《超级街头霸王 2》中，秘密角色豪鬼与游戏中的其他角色完全不平衡（见图 8.4）。这个角色有一种无敌的攻击方式——空中火球，比其他角色的攻击方式高出一筹，让他们毫无胜算。使用豪鬼是优势策略——如果对手选择了其他任何角色，她都会输得很惨。如果对手也选择豪鬼，那么在技能水平相当的情况下，很可能会出现平局。要确保结果公平，唯一的选择就是禁止在任何严肃的竞技游戏中使用该角色。这并不是说只有这款游戏中存在不平衡的角色，但在其他游戏中，优势角色还不至于失衡到毁了其他玩家的游戏。

Figure 8.4. Super Turbo Street Fighter 2. 图 8.4. 《超级街头霸王 2》。

graphics/08fig04.gif

Traditionally, the only way to remove dominant strategies in nontrivial examples is thorough play testing. Unfortunately, there is always some chance that flaws will slip through the net. This chapter covers some of the ways that we can try to prevent this from occurring.

传统上，在非微观实例中去除优势策略的唯一方法就是彻底的游玩测试。不幸的是，总有一些缺陷会漏网。本章将介绍一些防止这种情况发生的方法。

## Symmetry 对称

Symmetry is the simplest way of balancing a game. Each player (including the computer) is given the same starting conditions and abilities. This ensures that the outcome of the game is dependent only on the relative skill level of the players. Sounds ideal, doesn't it?

对称是平衡游戏的最简单方法。每个玩家（包括电脑）的起始条件和能力都相同。这样可以确保游戏结果只取决于玩家的相对技能水平。听起来很理想，不是吗？

Unfortunately, this approach only works in abstract games such as chess. Can you imagine simulating a real battle with the infantry, knights, and archers lined up facing each other over a perfectly symmetrical field? It would feel unnatural and would quickly become boring. Even though pure symmetry is limited in use to the abstract, there is a way that symmetry can be used to ensure balance without appearing to be contrived.

遗憾的是，这种方法只适用于国际象棋这样的抽象游戏。你能想象模拟一场真实的战斗，步兵、骑士和弓箭手在完全对称的场地上面对面排开吗？这会让人感觉不自然，而且很快就会变得无聊。尽管纯粹的对称仅限于抽象的应用，但有一种方法可以利用对称来确保平衡，而不会显得矫揉造作。

Pure symmetry works very well for sport simulations. You would expect that two teams playing the same game would be very similar to one another in both form and function. However, the highly standardized world of sport is about the only situation where this pure symmetry is appropriate. In a real-world situation, pure symmetry stands out like a sore thumb.

纯对称在体育模拟中非常有效。你可能会认为，进行同一场比赛的两支球队在形式和功能上都会非常相似。然而，高度标准化的体育世界是唯一适合采用纯对称的情况。在现实世界中，纯粹的对称会显得格外突兀。

{% hint style="info" %}
译者注：a sore thumb，字面意思是“疼痛的大拇指”，实际使用中通常比喻为“不协调的部分”或“显眼的事物”。这个短语源自于当你的大拇指受伤时，它通常会肿胀并且变得比其它手指更显眼，因此更容易被注意到。
{% endhint %}

In Game Architecture and Design, we talked about functional symmetry. This is a form of symmetry where the abilities of the player are roughly—but not exactly—mirrored. That is, they are functionally equivalent, not exactly equivalent.

在《游戏架构与设计》中，我们谈到了功能对称。这是一种对称形式，即玩家的能力大致相同，但不完全相同。也就是说，它们在功能上是等同的，而不是完全等同的。

The example used in Game Architecture and Design concerns a real-time strategy game with various types of landmass—water, mountain, and plain. We can use this as the basis of our example here. All units can travel over the plain, but only air units can travel over mountains, and only water units can travel over water (assume that they are hovercraft that can travel over plain as well as water). Do you see the functional symmetry? Each side has units that are functionally equivalent, but depending on the layout of the level (one player could be surrounded by mountains, the other could be bordered by sea), the way and the proportions in which those units would be used would be different.

《游戏架构与设计》一书中使用的例子涉及一款即时战略游戏，游戏中有各种类型的陆地——水域、山地和平原。在这里，我们可以以此为基础来举例说明。所有单位都可以在平原上行驶，但只有空中单位可以在山地上行驶，只有水上单位可以在水面上行驶（假设它们是气垫船，既可以在平原上行驶，也可以在水面上行驶）。你看到功能对称了吗？每一方都有功能等同的单位，但根据关卡的布局（一方可能四面环山，另一方可能四面环海），这些单位的使用方式和比例会有所不同。

Symmetry is mainly useful in balancing n-player games. It can also be used in balancing single player games; it's a good starting point to ensure that the computer-controlled entities are roughly in balance with the player. However, symmetry is a fairly unsophisticated approach and leads to a limited number of directly confrontational strategies. The player runs the risk of being restricted to a simple game of tit-for-tat. The computer throws X at me, so I have to respond with Y, which encourages the computer to throw more X at me, and so on. This does not lead to particularly interesting gameplay, and it shuts out a number of the more interesting gameplay dynamics we could expect if we were to use a more advanced balancing technique in conjunction with functional symmetry.

对称性主要用于平衡多人游戏。它也可以用于平衡单人游戏；这是一个很好的起点，可以确保电脑控制的实体与玩家大致平衡。不过，对称是一种相当不成熟的方法，导致直接对抗的策略数量有限。玩家有可能被限制在简单的针锋相对游戏中。电脑向我扔 X，所以我必须用 Y 来回应，这样电脑就会向我扔更多的 X，以此类推。这并不会带来特别有趣的游戏玩法，而且如果我们将更先进的平衡技术与功能对称性结合起来使用，它还会屏蔽掉许多更有趣的游戏动态。

## Transitive Relationships 传递关系

In a nutshell, a transitive relationship defines a one-way relationship between two or more entities. A can beat B, B can beat C, and C cannot beat anyone (and hence, by implication, A can beat C), as shown in Figure 8.5 and Table 8.3.

简而言之，传递关系定义了两个或多个实体之间的单向关系。如图 8.5 和表 8.3 所示，A 可以打败 B，B 可以打败 C，而 C 不能打败任何人（因此，隐含地说，A 可以打败 C）。

Figure 8.5. Transitive relationships. 图 8.5. 传递关系

graphics/08fig05.gif

Table 8.3. Net Payoff Matrix for A, B, and C 表 8.3. A，B，C的净收益矩阵

|| A | B | C |
|---|---|---|---|
|A|0|1|1|
|B|-1|0|1|
|C|-1|-1|0|

Taken at face value, it would seem that transitive relationships are not very useful. Why would anyone want to use C when they could use A? That's where the balancing comes in. So how do you balance the relationship? The more effective entity comes at a higher cost. Note that we don't necessarily mean a direct dollar or points or score cost; the cost could be in the lives of the people sent to fetch the prized entity, or the trials and difficulties that the player has to endure to reach the entity. There is no way of directly quantifying these indirect costs—known as shadow costs—but they should be sufficiently high as to justify the reward. Note that shadow costs are the end result of a number of other factors. They can be measured, but cannot be directly modified.

从表面上看，传递关系似乎并没有什么用处。既然可以用 A，为什么还要用 C 呢？这就是需要平衡的地方。那么如何平衡这种关系呢？更有效的实体需要付出更高的代价。请注意，我们指的并不一定是直接的金钱、积分或分数成本；这种成本可能是派去获取珍贵实体的人的生命，也可能是玩家为获取实体所经历的考验和困难。我们无法直接量化这些间接成本，它们被称为“影子成本”，但它们应该足够高，以证明奖励的合理性。请注意，影子成本是许多其他因素的最终结果。它们可以衡量，但不能直接改变。

Pure transitive relationships, without shadow costs to balance them out, lead to trivial and undemanding gameplay choices, which serve to undermine balance. However, shadow costs, together with the possibility of being knocked back down the ladder, allow for an interesting progression/regression dynamic that can lead to some taut and suspenseful gameplay. Care should be taken to ensure that the player can reestablish her previous level. Games such as Diablo from Blizzard Entertainment do this by allowing the player to retrieve her possessions from the corpse of the previous incarnation.

如果没有影子成本来平衡纯粹的传递关系，就会导致琐碎和不费力的游戏选择，从而破坏平衡。然而，影子成本加上被受挫的可能性，可以产生一种有趣的进步/退步动态，从而带来一些紧张而充满悬念的游戏。应注意确保玩家能重新达到之前的水平。暴雪娱乐公司出品的《暗黑破坏神》等游戏就是这样做的，它允许玩家从上一个化身的尸体上取回自己的物品。

Transitive relationships are very common in games, especially games such as first-person shooters. Think back to the original Doom from id Software. The player starts the game with a relatively weak pistol. Sure, the player can get a little way with it, but each monster takes more than one shot to dispatch, and initial progress is tricky. A little way into the game, the player finds a shotgun, which is a much more effective weapon. The player can now dispatch the monsters with relative ease, allowing him to get further into the game. Now the monsters become harder to kill, and shotgun ammunition becomes scarce.

传递关系在游戏中非常常见，尤其是第一人称射击游戏。回想一下 id Software 公司出品的原版《毁灭战士》。游戏开始时，玩家只有一把相对较弱的手枪。当然，玩家可以用它走一段路，但每只怪物都需要一枪以上才能击退，初期的进展非常棘手。游戏开始后，玩家发现了一把霰弹枪，这是一种更有效的武器。现在，玩家可以相对轻松地击退怪物，从而在游戏中继续前进。现在，怪物变得更难杀死，霰弹枪的弹药也变得越来越少。

We're back where we started—with a relatively weak weapon—and we need to search for another stronger weapon to make the same progress we were making before. This is how the game draws us in and impels us to keep playing.

我们又回到了起点——使用相对较弱的武器——我们需要寻找另一种更强的武器，以取得与之前相同的进展。这就是游戏吸引我们并促使我们继续玩下去的方式。

Transitive relationships are mainly used in games with a need to continually drive the player forward toward a goal. The player responds to that need and is rewarded with upgrades and progress, until eventually she reaches the goal, and the game is over.

传递关系主要用于需要不断推动玩家向目标前进的游戏中。玩家对这种需求做出回应，并获得升级和进步的奖励，直到最终达到目标，游戏结束。

As such, transitive relationships are only really useful in games that have a definite end point (which is most of them). They are rarely (if at all) used in open-ended games without some way of closing the loop and returning the player back to square one. An example is in the multiplayer arenas of games such as Quake III and Unreal Tournament. Here, the loop is closed by the death of the player, as he is respawned with only the basic weaponry and has to fight his way back up the transitive relationship ladder.

因此，传递关系只有在有明确终点的游戏中才真正有用（大多数游戏都是如此）。在开放式游戏中，如果没有关闭循环并让玩家回到原点的方法，就很少（如果有的话）使用它们。《雷神之锤 III》和《虚幻竞技场》等游戏的多人竞技场就是一个例子。在这些游戏中，玩家的死亡是游戏循环的终结，因为玩家重生时只有基本的武器装备，并且必须在传递关系的阶梯上奋力向上攀登。

Any game that involves upgrading or augmenting the player's capabilities within the game makes use of transitive relationships. We can think of plenty of examples of games that operate in this fashion. For example:

任何涉及在游戏中升级或增强玩家能力的游戏都会用到传递关系。我们可以想到很多以这种方式运行的游戏。例如：

* Super Mario. A series of side-scrolling platform games (see Figure 8.6). The progression is of Mario's abilities. With the first mushroom, he doubles in size, and with subsequent items, his abilities improve further to include flying and invulnerability. These abilities are lost in stages when Mario collides with an enemy.\
《超级马里奥》。这是一系列卷轴平台游戏（见图 8.6）。马里奥的能力在不断进步。有了第一个蘑菇，他的体型就会增加一倍，有了随后的物品，他的能力就会进一步提高，包括飞行和无敌。当马里奥与敌人相撞时，这些能力就会分阶段丧失。

Figure 8.6. Super Mario Advance. 图 8.6. 《超级马里奥Advance》

graphics/08fig06.gif

* Legend of Zelda. A series of top-down arcade style role-playing games (except for the Nintendo 64 and GameCube versions, which were full 3D), as shown in Figure 8.7. Link (the hero) collects items to enhance his skills and stamina. The basis of the game is to solve the overall quest by adventuring through a series of dungeons. In general, the prize for each dungeon is a magical item that enhances Link's abilities. A nice little game design touch is that the ability upgraded is the ability that would have been most useful in traversing the dungeon in which it was secreted.\
《塞尔达传说》。这是一系列俯视视角街机风格角色扮演游戏（任天堂 64 和 GameCube 版本除外，这些是全 3D 版本），如图 8.7 所示。林克（主人公）通过收集物品来增强自己的技能和体力。游戏的基础是通过在一系列地牢中冒险来完成整个任务。一般来说，每个地下城的奖品都是能增强林克能力的魔法物品。游戏设计的一个小亮点是，所提升的能力正是在探索隐藏该物品的地下城时最有用的那种能力。

Figure 8.7. Legend of Zelda. 图 8.7. 《塞尔达传说》。

graphics/08fig07.gif

* R-Type. A side-scrolling space-based shoot 'em-up (see Figure 8.8). As the player defeats enemies, they drop pods containing weapons upgrades for the player's ship. The cumulative upgrades are lost when your ship is destroyed.\
《异形战机》。一款卷轴太空射击游戏（见图 8.8）。当玩家击败敌人时，敌人会掉落装有玩家飞船升级武器的吊舱。当你的飞船被摧毁时，累积的升级就会丢失。

Figure 8.8. R-Type. 图 8.8. 《异形战机》

graphics/08fig08.gif

* Diablo. An isometric 3D action-adventure game (see Figure 8.9). As the player battles through the dungeons, the innovative skill and leveling systems allow you to spend experience points, gained while adventuring, on improving your character.\
《暗黑破坏神》一款等距 3D 动作冒险游戏（见图 8.9）。当玩家在地牢中战斗时，创新的技能和等级系统可以让你把冒险时获得的经验值用于提升角色。

Figure 8.9. Diablo. 图 8.9. 《暗黑破坏神》

graphics/08fig09.gif

* Doom, Quake, Half-Life, and so on. First-person shooters (see Figure 8.10). As you progress through the game, successively better weapons can be found that scale the player's firepower with that of the enemy. You lose the advanced weapons when your avatar is killed.\
《毁灭战士》，《雷神之锤》，《半条命》等。第一人称射击游戏（见图 8.10）。随着游戏进程的推进，玩家可以陆续找到更好的武器，使玩家的火力与敌人的火力相匹配。当你的化身被杀死时，你就会失去高级武器。

Figure 8.10. Doom. 图 8.10. 《毁灭战士》。

graphics/08fig10.gif

* The Sims. A "family simulator" that lets the player build and furnish a house and manage the family living within it (see Figure 8.11). For each household item you can purchase, there are upgrades available that function more efficiently. The more money you spend on an item, the more efficiently it does its job—it could take up less space, be prettier, or perform a double function.\
《模拟人生》是一款“家庭模拟器”，让玩家建造和布置房屋，并管理住在其中的家人（见图 8.11）。每购买一件家居用品，都可以升级以提高功能效率。你在一件物品上花的钱越多，它的工作效率就越高——它可以占用更少的空间，变得更漂亮，或者实现双重功能。

Figure 8.11. The Sims. 图 8.11. 《模拟人生》。

graphics/08fig11.gif

## Intransitive Relationships: Rock, Paper, Scissors 非传递关系：石头，布，剪刀

Almost everyone is familiar with the children's game Rock, Paper, Scissors (sometimes called Scissors, Paper, Stone). For those of you who managed to miss this one, the rules are basically summarized as follows: scissors cut paper, paper wraps stone, stone blunts scissors. Two players, the red player and the blue player, choose one of the three glyphs and score the game depending on the rules.

几乎每个人都熟悉儿童游戏“石头、布、剪子”（有时也叫 “剪刀、布、石头”）。对于那些错过了这个游戏的人来说，游戏规则基本上可以概括如下：剪刀剪纸，布包石头，石头砸剪刀。两名玩家，即红色玩家和蓝色玩家，从三个符号中选择一个，并根据规则得分。

This gives us a balanced, three-way intransitive relationship, as shown in Figure 8.12.

这样，我们就得到了一个平衡的三方非传递关系，如图 8.12 所示。

Figure 8.12. Three-way intransitive relationship in Rock, Paper, Scissors. 图 8.12. 石头、剪子、布中的三向不等式关系。

graphics/08fig12.gif

The net payoff matrix for Rock, Paper, Scissors is shown in Table 8.4.

剪刀石头布的净收益矩阵如表 8.4 所示。

Table 8.4. Rock, Paper, Scissors 表 8.4. 石头、剪子、布

|| Scissors 剪刀 | Paper 布 | Rock 石头|
|---|---|---|---|
|Scissors 剪刀|0|1|-1|
|Paper 布|-1|0|1|
|Rock 石头|1|-1|0|

Rock, Paper, Scissors is a zero sum game. That is, if the red player wins, the blue player has to lose. If the blue player wins, the red player has to lose. And if the blue player draws, then the red player has to draw as well (and vice versa). Most interesting games are zero sum: The player wins (or player team wins) and the computer (or opposing player/team) loses—or at least, that's the idea.

剪刀石头布是一个零和游戏。也就是说，如果红方赢了，蓝方就输了。如果蓝方玩家赢了，红方玩家必须输。如果蓝方玩家平局，那么红方玩家也必须平局（反之亦然）。大多数有趣的游戏都是零和游戏：玩家赢（或玩家团队赢），电脑（或对方玩家/团队）输——或者至少是这样。

The three-way intransitive relationship of Rock, Paper, Scissors has been the model for most real-time strategy game balancing and has also been used in other game genres, such as racing games and role-playing games, for many years. Static intransitive relationships—although more aesthetically pleasing than transitive relationships—do not lead to innovative gameplay. It's far too easy for the player to learn the simple relationships between units and figure out the best strategy to use. The game becomes a one-trick pony. The solution to this is to dynamically vary the relationship.

多年来，“石头、剪子、布 ”的三方不等式关系一直是大多数即时战略游戏的平衡模式，也被用于其他类型的游戏，如赛车游戏和角色扮演游戏。静态的不传递关系虽然比传递关系更美观，但并不能带来创新的游戏玩法。玩家很容易就能学会单位之间的简单关系，并找出最佳策略。游戏变成了一招鲜。解决这个问题的办法就是动态地改变关系。

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