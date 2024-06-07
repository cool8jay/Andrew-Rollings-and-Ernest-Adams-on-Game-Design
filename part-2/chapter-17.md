Over the last seven years, online gaming has gone from a tiny fraction of the interactive entertainment business to a major market in its own right. It has many unique qualities, both good and bad, as well as unique design challenges. Because it's a technology rather than a genre, we don't look for design patterns in this chapter the way we did in the earlier ones. Instead, we address some of the design considerations that are peculiar to all kinds of online games, no matter what genre they belong to. It's a huge topic, how-ever; we could probably write an entire book about it. Unfortunately, we can cover only the highlights here.

在过去的七年里，在线游戏已经从互动娱乐行业的一小部分发展成为一个重要的市场。它有许多独特的品质，有好有坏，也有独特的设计挑战。由于它是一种技术而不是一种流派，我们在本章中不会像前面几章那样寻找设计模式。相反，我们将讨论所有类型的网络游戏所特有的一些设计考虑因素，无论它们属于哪种类型。无论如何，这是一个庞大的话题；我们也许可以写一整本书来讨论它。遗憾的是，我们在这里只能谈及重点。

The second half of the chapter is devoted to persistent worlds, also known as massively multi-player online role-playing games, or MMORPGs (although persistent worlds need not necessarily be about role playing). We're particularly indebted to Raph Koster, lead designer of both [Ultima Online](https://en.wikipedia.org/wiki/Ultima_Online) and [Star Wars Galaxies](https://en.wikipedia.org/wiki/Star_Wars_Galaxies), and Tess Snider, a long-time online role player and member of the WorldForge Project, for their help with this material. In his many years of working with online games, Koster has assembled a valuable collection of "laws" or observations about this particular form of interactive entertainment, and with his permission, we're going reprint many of them here. Some of these laws are originally his; others are credited to his colleagues. You'll see them scattered throughout this chapter like this:

本章的后半部分专门讨论“持久世界”，也称为“大型多人在线角色扮演游戏”或“MMORPG”（尽管“持久世界”并不一定与角色扮演有关）。我们要特别感谢[《网络创世纪》](https://en.wikipedia.org/wiki/Ultima_Online)和[《星球大战星系》](https://en.wikipedia.org/wiki/Star_Wars_Galaxies)的首席设计师拉斐尔·科斯特，以及长期在线角色扮演游戏玩家、WorldForge 项目成员苔丝·斯奈德，感谢他们为本资料提供的帮助。在与网络游戏打交道的多年中，科斯特收集了大量关于这种特殊互动娱乐形式的 “法则”或看法，经他同意，我们将在此转载其中的许多内容。其中一些法则是他的原创，另一些则归功于他的同事。你会看到它们像这样散落在本章中：

> Ola's Law About Laws: Any general law about virtual worlds should be read as a challenge rather than as a guideline. You'll learn more from attacking it than from accepting it.
> 
> 奥拉关于法律的定律：任何有关虚拟世界的一般法律都应被视为挑战而非准则。攻击它比接受它能学到更多东西。

You can read the complete set of laws at Koster's web site at [https://www.raphkoster.com/games/laws-of-online-world-design/the-laws-of-online-world-design/](https://www.raphkoster.com/games/laws-of-online-world-design/the-laws-of-online-world-design/).

你可以在科斯特的网站 [https://www.raphkoster.com/games/laws-of-online-world-design/the-laws-of-online-world-design/](https://www.raphkoster.com/games/laws-of-online-world-design/the-laws-of-online-world-design/) 上阅读整套法则。

# Advantages of Online Games 网络游戏的优点

As we said, online games have many positive qualities. Some of them are advantages to us as game developers; others are features that attract players who might not otherwise play computer games.

正如我们所说，网络游戏有许多正面的品质。其中一些是我们作为游戏开发者的优势，另一些则是吸引那些可能不会玩电脑游戏的玩家的特点。

## Player Socializing 玩家社交

The single greatest benefit of online play, as far as the players are concerned, is that it offers opportunities for social interaction. Of course, they can't talk as well as if they were in the same room together, and they can't give each other the high five, but these are minor considerations. The social aspect doesn't affect the internal economy of the game much, but it has a distinct effect on the players' enjoyment of the experience. One of the reasons that girls and women have traditionally been less interested in interactive entertainment, especially games for personal computers, is that it is often a solitary activity. But women represent a much greater proportion of the online game market than they do the single-player game market, chiefly for this reason: They enjoy interacting with others.

就玩家而言，在线游戏最大的好处就是提供了社交互动的机会。当然，他们不能像在同一个房间里那样畅所欲言，也不能互相击掌，但这些都是次要的考虑因素。社交方面对游戏的内部经济影响不大，但对玩家享受体验却有明显的影响。传统上，女孩和妇女对互动娱乐，尤其是个人电脑游戏不太感兴趣，原因之一是互动娱乐往往是一种孤独的活动。但在网络游戏市场上，女性所占的比例远远高于单机游戏市场，主要原因就在于此：她们喜欢与他人互动。

At the moment, this capability is usually limited to typing text ("chatting"), which is awkward while trying to play a fast-paced game, but a few games are beginning to include voice communication. When enough people get broadband access, they will probably include video as well. A time might come when we see players dressing appropriately to their roles in the game so that they'll look cool on camera.

目前，这种功能通常仅限于输入文字（“聊天”），这在玩快节奏游戏时很不方便，但也有一些游戏开始加入语音通信功能。当有足够多的人使用宽带时，他们可能也会加入视频功能。也许有一天，我们会看到玩家们根据自己在游戏中的角色穿着得体，以便在镜头前看起来很酷。

The social element makes online games more than just games. They become clubs, cafés, casinos—places where people get together for fun. As the creator of such spaces, you're more than just a game designer; you must also be a social architect. This is actually your toughest challenge, far more difficult than designing the core mechanics of a single-player game. An online game isn't an experience that you lead a player through; it's a Petri dish for growing social situations, and it's nearly impossible to predict in advance what will happen there. For further discussion of this topic, please read the excellent and insightful Community Building on the Web by Amy Jo Kim.

社交元素使网络游戏不仅仅是游戏。它们变成了俱乐部、咖啡馆、赌场--人们聚在一起消遣的地方。作为这类空间的创造者，你不仅仅是一名游戏设计师，还必须是一名社交架构师。这实际上是你最严峻的挑战，比设计单人游戏的核心机制要难得多。网络游戏不是你带领玩家体验的游戏，它是一个培养社会情境的培养皿，而你几乎不可能事先预测到游戏中会发生什么。如需进一步了解这一话题，请阅读 Amy Jo Kim 所著的《网络社区建设》一书，该书内容精彩，见解独到。

## Human Intelligence Instead of Artificial Intelligence 人类智能取代人工智能

In single-player games, the player competes against the computer, so the computer has to have enough artificial intelligence to be a good opponent. If the game is complex, building the AI is a huge programming task and is difficult to get right. If the players are competing against each other, as they are in most online games, you don't need any AI. The players provide all the intelligence required. This feature of online play is second only to the social aspect in terms of the benefit provided to the player.

在单人游戏中，玩家的对手是电脑，因此电脑必须具备足够的人工智能，才能成为优秀的对手。如果游戏很复杂，那么建立人工智能就是一项艰巨的编程任务，而且很难做到完美。如果玩家之间是相互竞争的，就像在大多数网络游戏中那样，你就不需要任何人工智能。玩家可以提供所需的所有智能。就为玩家带来的益处而言，在线游戏的这一特点仅次于社交方面。

Of course, you can still design the game in such a way that AI is required: You might have nonplayer characters (NPCs) who need to behave intelligently, or you might design a game in which all the players play cooperatively against an artificial opponent. But many online games rely on their players to provide the intelligence in the game, and this can make the game easier to develop.

当然，你仍然可以设计出需要人工智能的游戏： 你可以让非玩家角色（NPC）需要有智能行为，也可以设计一款游戏，让所有玩家合作对抗人工对手。但是，许多网络游戏都依赖玩家来提供游戏中的智能，这可以使游戏更容易开发。

> **Psychological Tactics 心理战术**
> 
> Intelligence, in gameplay terms, means more than just smarts; it means an understanding of human behavior. Computer software is particularly poor at this; humans are particularly good at it. Playing against other people, you can bluff, feint, ambush, lure opponents out of hiding with lame-duck tactics, and try all manner of ruses de guerre that would never work against an AI opponent (or, worse yet, would work consistently every time). You can learn another player's style and look for ways to exploit his tendencies—while being aware that he is learning from yours, too. Except in simple games, playing against human opponents is a richer, more subtle experience.
> 
> 用游戏术语来说，智力不仅仅意味着聪明，还意味着对人类行为的理解。计算机软件在这方面特别差，而人类却特别擅长。与其他人对战，你可以虚张声势、佯攻、埋伏、用蹩脚的战术引诱对手出击，并尝试各种对人工智能对手绝对不起作用（或者更糟的是，每次都能奏效）的诡计。你可以学习其他玩家的风格，寻找利用他的倾向的方法，同时也要意识到他也在学习你的风格。除了简单的游戏，与人类对手对战是一种更丰富、更微妙的体验。

## Online Gameplay Versus Local Multi-Player Gameplay 在线游戏与本地多人游戏

Multi-player gameplay offers great flexibility to the game designer: It allows purely competitive ("everyone for himself"), purely cooperative ("It's us against the machine"), or team-based play. Multi-player play can be either online or local. In online play, players are linked by a network and are (generally, but not necessarily) in separate locations. In local play, all the players sit in the same room, playing the game on the same machine and, most important, looking at the same screen. For the last 30 years, local play has been the standard mode of interaction for multi-player console games: Each player has a controller, and they all look at the TV. That could change as the new generation of consoles introduces network capability, but it's likely to remain the most common way people use them: It costs nothing and lets people play together in social groups.

多人游戏为游戏设计者提供了极大的灵活性： 它允许纯竞争（“人人为我”）、纯合作（“我们对抗机器”）或团队游戏。多人游戏可以是在线的，也可以是本地的。在联机游戏中，玩家通过网络连接在一起，并且（一般但不一定）位于不同的地点。在本地游戏中，所有玩家都坐在同一个房间里，在同一台机器上玩游戏，最重要的是，要看着同一个屏幕。在过去的 30 年里，本地游戏一直是多玩家控制台游戏的标准交互模式： 每个玩家都有一个控制器，他们都看着电视。随着新一代游戏机引入网络功能，这种情况可能会有所改变，但它很可能仍然是人们最常用的游戏方式： 它不需要任何成本，还能让人们在社交群组中一起游戏。

### Problems with Local Play 本地游戏的问题

From a design standpoint, however, local multi-player play has serious drawbacks. For one thing, because all the players share the same TV, any user interface elements have to be duplicated for each of them, taking up valuable screen space. If every player has a separate point of view, the screen must be subdivided into little windows. Each individual window is harder to see, and the other players' windows are a distraction.

不过，从设计的角度来看，本地多人游戏有严重的缺点。首先，由于所有玩家共用一台电视机，任何用户界面元素都必须为每个玩家复制，从而占用了宝贵的屏幕空间。如果每个玩家都有一个单独的视角，屏幕就必须细分为多个小窗口。每个窗口都很难看到，其他玩家的窗口也会分散注意力。

More important, however, in local play there is no hidden information. Each player can see what the others are doing. This is fine for fighting games, but not so good in any game in which players might want to keep their activities secret—war games, for example.

但更重要的是，在本地游戏中没有隐藏信息。每个玩家都能看到其他人在做什么。这对于格斗游戏来说很好，但对于任何玩家可能希望对自己的活动保密的游戏来说就不太好了，比如战争游戏。

(The Nintendo GameCube does allow players to plug in a Game Boy Advance and use it as a controller; the Game Boy's screen is then available for displaying hidden information to the player. However, this feature requires players to own both devices as well as the necessary cable. Although it solves the problem in theory, in practice any commercial game that requires it as a gameplay mechanism limits its market to those players who actually own all the gear.)

(任天堂 GameCube 确实允许玩家插入 Game Boy Advance 并将其用作控制器，这样 Game Boy 的屏幕就可以向玩家显示隐藏信息。不过，这项功能要求玩家同时拥有这两款设备和必要的连接线。虽然在理论上解决了这个问题，但实际上，任何商业游戏，如果需要把它作为一种游戏机制，其市场就会局限于那些真正拥有所有设备的玩家。）

Finally, local play necessarily imposes limits on the number of people who can participate at once. Consoles seldom support more than four players; PCs support even fewer. Even if you could add players indefinitely, the machine itself would be bogged down as the computing task grows.

最后，本地游戏必然会对同时参与游戏的人数造成限制。游戏机支持的玩家很少超过四人，个人电脑支持的玩家就更少了。即使你可以无限地增加玩家，随着计算任务的增加，机器本身也会陷入困境。

### Benefits of Networked Play 联网游戏的好处

Online gaming solves all these problems. Each player has her own screen, and the entire area is dedicated to supporting her gaming experience. The game can present her with her own unique perspective, including exactly as much information as she is supposed to have, and no more. And online games can support any number of people (although, if they require a central server, there are still some limits)—it's not uncommon for some games to have tens of thousands of players online at a time. With an online game, you can always find other people to play with at any hour of the day or night.

网络游戏解决了所有这些问题。每个玩家都有自己的屏幕，整个区域都用于支持她的游戏体验。游戏可以向她展示自己独特的视角，包括她应该获得的全部信息，仅此而已。而且，网络游戏可以支持任何数量的玩家（不过，如果需要中央服务器，还是会有一些限制）--有些游戏同时在线玩家数以万计的情况并不少见。有了网络游戏，无论白天黑夜，你总能找到其他人一起玩。

Of the three forms of player interaction (single-player, local multi-player, and online multi-player), online playing offers you the most flexibility as a designer. However, it is not without its problems, as we'll see in the next section.

在三种玩家互动形式（单人游戏、本地多人游戏和在线多人游戏）中，作为设计者，在线游戏为你提供了最大的灵活性。不过，它也不是没有问题，我们将在下一节中看到。

# Disadvantages of Online Games 网络游戏的缺点

Playing games over a network, especially the Internet, creates technical challenges that single-player or local multi-player games don't face. Playing with anonymous strangers can cause social friction, and if you provide an online game, you might have a serious legal obligation to make sure people don't use it to abuse children.

通过网络（尤其是互联网）玩游戏会遇到单人游戏或本地多人游戏不会遇到的技术挑战。与匿名陌生人一起玩游戏可能会引起社会摩擦，如果你提供网络游戏，你可能要承担严重的法律责任，确保人们不会利用游戏虐待儿童。

## Technical Issues 技术问题

Because this is a book about design, we won't go into the technical issues in detail, much less try to provide solutions for them. However, we think it's worth listing a few just to let you know what you're up against.

由于这是一本关于设计的书，我们不会详细讨论技术问题，更不会试图提供解决方案。不过，我们认为还是有必要列出几个问题，让你知道自己会遇到什么。

> **Murphy's Law:** Servers crash and don't restart only when you go out of town.
> 
> **墨菲定律：** 只有当你出城时，服务器才会崩溃，并且不会重启。

### Communication Models 交流模式

Your programming team will need to choose a communication model for the game. Two communication models are used in network gaming. One is client/server, in which each player runs a program, called the client, on his computer that communicates with a central program, the server, on a computer owned by a company providing the game service. In the client/server model, the server "owns" the game and the clients merely present it to the players. The other model is peer-to-peer, in which players' computers communicate directly with each other. Peer-to-peer (sometimes abbreviated P2P) is quite straightforward for two-player games, but it becomes more complicated as more players are involved. The players must somehow decide that one machine is the "host," controlling the game, and the others are guests; but if the host logs out of the network, one of the guests must take over and become the new host—preferably automatically and without anyone noticing (this is known as "automated host migration" and is already supplied by Microsoft's DirectPlay facilities). Some companies also operate "matchmaking" services in which the company server's only function is to allow players to find one another and connect together in peer-to-peer networks. All of this is programming work that offline games don't have to bother with.

你的编程团队需要为游戏选择一种通信模式。网络游戏中有两种通信模式。一种是客户机/服务器，即每个玩家在自己的电脑上运行一个称为客户机的程序，该程序与提供游戏服务的公司所拥有的电脑上的中央程序（即服务器）进行通信。在客户机/服务器模式中，服务器 “拥有 ”游戏，而客户机只是向玩家展示游戏。另一种模式是点对点模式，在这种模式下，玩家的电脑之间直接通信。点对点（有时缩写为 P2P）对于双人游戏来说非常简单，但当参与游戏的玩家越多，情况就越复杂。玩家必须以某种方式确定一台机器为 “主机”，控制游戏，其他机器为客人；但如果主机退出网络，其中一台客人必须接替主机，成为新的主机--最好是在无人察觉的情况下自动完成（这被称为 “自动主机迁移”，微软的 DirectPlay 设备已经提供了这种功能）。有些公司还提供 “匹配 ”服务，在这种服务中，公司服务器的唯一功能就是让玩家找到彼此，并在点对点网络中连接在一起。所有这些都是编程工作，离线游戏无需理会。

### Transmission Delay Times 传输延迟时间

The Internet was designed for redundancy rather than speed, and it doesn't make any guarantees about how long a given packet of data will take to get from one point to another. In many games, a faster connection translates into a gaming advantage, so players with high-speed connections are more likely to win the game. There are ways of designing around this: You can make your game turn-based or try to match opponents up on the basis of their connection speed. At the moment, however, there is no one satisfactory answer.

互联网的设计初衷是冗余而非速度，它无法保证特定数据包从一个点到另一个点需要多长时间。在许多游戏中，连接速度越快，游戏优势就越大，因此拥有高速连接的玩家更有可能赢得游戏。有一些方法可以解决这个问题： 你可以让你的游戏采用回合制，或者尝试根据连接速度来匹配对手。不过，目前还没有一个令人满意的答案。

### Dropped and Garbled Packets 丢失和乱码数据包

What happens to your game if it doesn't get some of the information it needs? Your system will require a mechanism for detecting that a packet has gone missing or contains bad data, and requesting that it be resent from the server. Packets can also arrive out of order, which can be confusing if your client receives information that a race car is about to cross the finish line, but the next packet tells it that the car is 100 yards back up the track instead. Every packet must have a unique serial number so that you can tell if one is missing or if they are arriving in the wrong order.

如果游戏得不到所需的某些信息，会发生什么情况？您的系统将需要一种机制来检测数据包是否丢失或包含错误数据，并请求服务器重新发送。数据包还可能不按顺序到达，如果您的客户端收到的信息是一辆赛车即将冲过终点线，但下一个数据包却告诉它赛车在赛道后方 100 码处，这就会造成混乱。每个数据包都必须有一个唯一的序列号，这样你才能知道是否丢失了一个数据包，或者它们是否以错误的顺序到达。

## It's Harder to Suspend Disbelief 更难沉浸

For some players, gaming is a form of escapism. They want to go away to a magical place, and they want it to stay magical while they're there. To them, it's particularly important that nothing occur in the game to break their suspension of disbelief. This is substantially harder to accomplish with online games because there will always be players who won't stay in character or who will talk about real-world issues and events while they're in the game. Unless there's a strong (and enforced) ethos of in-character role-playing, people who play in an online game have to accept that their imaginary world includes a lot of entirely real people.

对一些玩家来说，游戏是一种逃避现实的方式。他们想去一个神奇的地方，而且希望在那里的时候一直保持神奇。对他们来说，游戏中不发生任何打破他们悬着的不信任感的事情尤为重要。在网络游戏中要做到这一点要难得多，因为总有一些玩家在游戏中不会保持角色的原样，或者会谈论现实世界中的问题和事件。除非有一种强烈的（并强制执行的）角色扮演风气，否则玩网络游戏的人就必须接受他们的想象世界里有很多完全真实的人。

> **Koster's Law:** The quality of role playing is inversely proportional to the number of people playing.
> 
> **科斯特定律：** 角色扮演的质量与参与人数成反比。
> 
> **Enforcing role playing: **A role play–mandated world is essentially going to have to be a Fascist state. Whether or not this accords with your goals in creating such a world is a decision you will have to make.
> 
> **强制角色扮演：** 角色扮演强制世界本质上必须是一个法西斯国家。这是否符合你创建这样一个世界的目标，你必须做出决定。

## Misbehavior 不良行为

Unfortunately, playing with strangers—particularly anonymous strangers—creates opportunities for a variety of types of misbehavior that can ruin the game for others. These range from simple rudeness to harassment, cheating in various forms, and outright fraud. Rudeness might not sound very serious, but it does drive away other customers. (Raph Koster has stated, only partly joking, that the sole rule in [Star Wars Galaxies](https://en.wikipedia.org/wiki/Star_Wars_Galaxies) is, "Any behavior that hurts business is bad behavior.") Furthermore, if you want children to play your game, it is particularly important to make sure they have a safe environment to play in—and that means hiring customer service people to monitor them. Self-contained networks such as America Online have some tools at their disposal to manage these problems, but on open networks such as the Internet, it's much harder. We address some of these issues in the section on design issues, later in the chapter.

不幸的是，与陌生人（尤其是匿名陌生人）一起玩游戏会给各种类型的不当行为创造机会，从而破坏他人的游戏体验。这些行为包括粗鲁无礼、骚扰、各种形式的作弊以及赤裸裸的欺诈。粗鲁无礼听起来可能不是很严重，但确实会赶走其他顾客。(拉斐尔·科斯特曾说过，[《星球大战星系》](https://en.wikipedia.org/wiki/Star_Wars_Galaxies)的唯一规则就是“任何损害生意的行为都是不好的行为”，这只是部分开玩笑的说法）。此外，如果你想让孩子们玩你的游戏，确保他们有一个安全的游戏环境尤为重要--这就意味着要雇用客服人员来监督他们。像美国在线这样的独立网络可以利用一些工具来管理这些问题，但在互联网这样的开放网络上，就难上加难了。我们将在本章后面的设计问题部分讨论其中的一些问题。

> **John Hanke's Law:** In every aggregation of people online, there is an irreducible proportion of [jerks].
> 
> **约翰·汉克定律：** 在每一个网络人群的聚集地，都有一定比例的[混蛋]。

## The Need to Produce Content 制作内容的必要性

When you're building a game sold in retail stores, the project is over when the gold master disc goes off to manufacturing. The players buy the boxes, and you can go off to work on another project.

当你制作一款在零售店销售的游戏时，当黄金母盘被送往制造厂时，项目就结束了。玩家买了盒子，你就可以去做另一个项目了。

Online games don't work this way; they earn money either through advertising revenue or subscriptions (or both). To keep people interested, you have to change things, and that means producing new content on an ongoing basis. This is expensive to the service provider and ties up skilled development staff. The problem is most obvious with persistent worlds, but even simple games need to be kept fresh somehow. America Online used to run a suite of games called RabbitJack's Casino (no real money was awarded as prizes). Although the graphics didn't change, the game's managers held theme nights and gave away additional prizes when particular combinations of events occurred.

网络游戏则不是这样，它们通过广告收入或订阅（或两者兼而有之）来赚钱。为了保持玩家的兴趣，你必须不断改变，这就意味着要持续不断地制作新内容。这对服务提供商来说成本高昂，而且会束缚熟练开发人员的手脚。这个问题在持久世界中最为明显，但即使是简单的游戏也需要以某种方式保持新鲜感。美国在线曾经运营过一套名为 RabbitJack's Casino 的游戏（没有真钱作为奖品）。虽然画面没有变化，但游戏的管理者会举办主题之夜，并在出现特定事件组合时赠送额外的奖品。

> **Persistence means it never goes away:** When you open your online world, expect to keep your team on it indefinitely. Some of these games have never closed. And closing one prematurely could cost you the faith of your customers, damaging the prospects for other games in the same genre.
> 
> **坚持意味着永不放弃：** 当你打开你的在线世界时，希望能让你的团队无限期地留在上面。有些游戏从未关闭过。而过早关闭一款游戏可能会让你失去客户的信任，损害其他同类型游戏的前景。

## Customer Service 客户服务

All game companies require customer service staff to help players with problems, but online games need far, far more of them. With offline games, players mostly need help with technical difficulties; for gameplay problems, they can buy strategy guides or find hints on the Internet. But in a live, online environment, players expect to get help immediately, and they demand help for a much larger range of issues than they do in offline games. Players expect customer service people not only to solve technical problems, but also to explain the user interface, answer questions about game content, and enforce justice by investigating and punishing misbehavior by other players. With thousands of players logged on at any one time, it can become very expensive to provide these services.

所有游戏公司都需要客服人员帮助玩家解决问题，但网络游戏需要的客服人员要多得多。在离线游戏中，玩家需要的主要是技术问题的帮助；对于游戏问题，他们可以购买策略指南或在互联网上寻找提示。但在实时在线环境中，玩家希望立即得到帮助，而且他们需要帮助解决的问题比离线游戏要多得多。玩家希望客服人员不仅能解决技术问题，还能解释用户界面，回答有关游戏内容的问题，并通过调查和惩罚其他玩家的不当行为来伸张正义。任何时候都有成千上万的玩家登录，提供这些服务的成本会变得非常高昂。

> **Anonymity and in-game administrators:** The in-game administrator faces a bizarre problem. He is exercising power that the ordinary virtual citizen cannot, and he is looked to in many ways to provide a certain atmosphere and level of civility in the environment. Yet the fact remains that no matter how scrupulously honest he is, no matter how just he shows himself to be, and no matter how committed to the welfare of the virtual space he might prove himself, people will hate his guts. They will mistrust him precisely because he has power and they can never know him.
> 
> **匿名和游戏内管理员：** 游戏内管理员面临着一个奇怪的问题。他行使着普通虚拟公民无法行使的权力，而且在许多方面，人们都希望他能为游戏环境提供一定的氛围和文明程度。然而，无论他多么诚实，无论他表现得多么公正，无论他证明自己多么致力于虚拟空间的福利，人们都会对他恨之入骨。他们之所以不信任他，正是因为他拥有权力，而他们却永远无法了解他。

# Design Issues for Online Gaming 网络游戏的设计问题

In this section, we're going to address a hodgepodge of design issues that are peculiar to online games.

在本节中，我们将讨论网络游戏特有的各种设计问题。

## Arriving Players 玩家的到来

Players can log on wanting to play your game at any time, and the game has to be capable of dealing with them intelligently. In most noncomputer games, all the players must be present at the beginning of the match, or it won't be fair. In Monopoly, for example, anyone who entered the game late would be at a significant disadvantage—the others would have already grabbed the best properties, and the game's built-in inflation would swiftly bankrupt them.

玩家可以随时登录游戏，游戏必须能够智能地处理他们。在大多数非电脑游戏中，比赛开始时所有玩家都必须在场，否则比赛就不公平。例如，在《大富翁》游戏中，任何迟到的玩家都会处于非常不利的地位--其他人已经抢到了最好的房产，而游戏内置的通货膨胀会让他们迅速破产。

The usual solution is to start new matches at frequent intervals and to have a waiting area or "lounge" where the players can hang around while they wait for it to begin. If a game can be played with any number of players (bingo is a good example), you can simply start a new match every three minutes, say, with whoever is around to play. In games requiring a fixed number of players, such as bridge, you will need to establish a matchmaking service that allows them to form groups and to wait (more or less patiently) for enough players to join a particular group; the game begins as soon as the required number has arrived. The number of players needed for a game should be small, however, so that they don't have to wait too long. Any game that requires more than about eight players will have difficulties in this respect.

通常的解决办法是每隔一段时间就开始新的比赛，并设置一个等待区或 “休息室”，让玩家在等待比赛开始时可以在那里闲逛。如果一个游戏可以有任意数量的玩家参与（宾果游戏就是一个很好的例子），你可以简单地每隔三分钟开始一场新的比赛，比如说，谁在旁边谁就可以玩。如果游戏需要固定的玩家人数，比如桥牌，你就需要建立一个匹配服务，让他们组成小组，并（或多或少耐心地）等待足够的玩家加入某个小组；一旦达到所需的人数，游戏就开始了。不过，游戏所需的玩家人数应该很少，这样他们就不必等待太长时间。在这方面，任何需要超过 8 名玩家的游戏都会遇到困难。

In some games, players can join almost immediately without any disadvantage—poker, for example. Each hand takes little time, and new players can join as soon as the current hand is over. For games of indefinite duration, such as persistent worlds, nothing can be done about the fact that some players are ahead of other players. The players who were there the earliest and who have the most time to play will always have an advantage (unless you allow players to purchase prebuilt characters for real money on eBay, but that just shifts the advantage from players who have the most time to players who have the most money). There are a few ways of preventing this from spoiling the game for the players, however:

在某些游戏中，玩家几乎可以立即加入而不会有任何不利，例如扑克。每手牌花不了多少时间，新玩家可以在当前牌局结束后立即加入。对于持续时间不确定的游戏，比如持久世界，有些玩家比其他玩家先到，这一点是没有办法解决的。最早到场、游戏时间最长的玩家将始终占据优势（除非你允许玩家在 eBay 上用真钱购买预建角色，但这只是将优势从时间最长的玩家转移到了钱最多的玩家身上）。不过，有几种方法可以防止这种情况破坏玩家的游戏体验：

* **Get rid of the victory condition.** Without winners and losers, it ceases to be a game, per se, and becomes a different kind of entertainment. The player focuses on her own achievements rather than on defeating all the others. In this case, the old cliché becomes true: It's not whether you win or lose, but how you play the game. Persistent worlds, which we address later in the chapter, work like this.\
没有了输赢，游戏本身就不再是游戏，而变成了另一种娱乐。玩家关注的是自己的成就，而不是打败所有其他人。在这种情况下，老生常谈就成了真理：输赢不重要，重要的是你如何玩游戏。我们将在本章后面讨论的 “持久世界 ”是这样运作的。

* **Discourage competition between old-timers and newcomers.** You can measure the progress of your players and see to it that only those who are fairly matched come into direct conflict. This is why tournament chess has a ranking system. An old-timer who beats a newcomer gets little or no reward for it. The cliché description for this solution is, make players "pick on someone their own size.\
你可以衡量棋手的进步情况，确保只有那些实力相当的棋手才会发生直接冲突。这就是国际象棋锦标赛有等级分制度的原因。老棋手击败新棋手几乎得不到任何奖励。对这一解决方案的老生常谈的描述是，让棋手 “挑和自己体型相仿的人”。

* **Be sure that direct competition is consensual.** If old-timers do get the chance to compete directly with newcomers, the newcomers should have the option to refuse to play. No one should be forced to take part in an unfair competition.、
如果老玩家确实有机会与新玩家直接竞争，新玩家应该可以选择拒绝参加。任何人都不应被迫参加不公平的竞争。

## Disappearing Players 消失的玩家

Just as players can appear at any time, they can log off at any time. If possible, your game should deal with this neatly and with minimal disruption to the other players. Obviously, in games that require a fixed number of participants, your only options are to include an AI element that can take over for the missing player, or to shut down the game.

正如玩家可以随时出现一样，他们也可以随时注销。如果可能的话，您的游戏应妥善处理这一问题，并尽量减少对其他玩家的干扰。很明显，在需要固定参与人数的游戏中，您唯一的选择就是加入一个人工智能元素，让它代替失踪的玩家，或者关闭游戏。

However, in many games, such as racing games, players compete against one another in a free-for-all. The disappearance of one player doesn't make that much difference—his car vanishes from the track, and that's that. It's as if he pulled out with mechanical trouble. In effect, the player forfeits the race and the others continue. On the other hand, if the game is played in teams, the disappearance of one player could put his team at a serious disadvantage.

然而，在许多游戏（如赛车游戏）中，玩家之间是自由竞争的。一名玩家的失踪并不会造成太大的影响--他的赛车从赛道上消失，仅此而已。就好像他因机械故障而退出比赛一样。实际上，这位玩家放弃了比赛，其他人继续比赛。另一方面，如果比赛是以小组为单位进行的，一名选手的消失可能会使他所在的小组处于严重的劣势。

### Logging Out as a Form of Cheating 注销是一种作弊方式

Tournaments are another matter, though. If players are competing to get the best win-loss ratio, one might deliberately choose to log out rather than lose the game—which also denies the other person victory. Should the vanishing player be forced to forfeit? What if the disconnection was an accident, caused by a bad line? Unfortunately, there's no way to tell which it was.

不过，比赛则是另一回事。如果玩家们都在争夺最佳胜负率，其中一人可能会故意选择注销而不是输掉比赛--这也剥夺了另一人的胜利。是否应该强迫消失的玩家放弃比赛？如果断线是由于线路故障造成的意外呢？不幸的是，我们无法判断哪种情况。

In baseball, if a game is called off due to rain, it is considered finished if five or more innings have been played (four and a half, if the home team is ahead). Unlike baseball, however, most computer games don't have a distinct way of counting progress toward completion.

在棒球比赛中，如果一场比赛因下雨而取消，那么只要比赛进行了五局或五局以上（如果主队领先，则为四局半），比赛就算结束。不过，与棒球不同的是，大多数电脑游戏并没有明确的计算完成进度的方法。

### Responses to Vanishing Players 针对消失玩家的对策

Here are a variety of alternative suggestions for dealing with vanishing players:

以下是处理消失球员的各种备选建议：

* **The vanishing player forfeits.** Obviously, this is hard on players for whom it was an accident. Unless connections are extremely reliable and unlikely to break (such as in a game played on a local area network), you have to consider the possibility that it was unintentional.\
**消失的棋手弃权。** 显然，这对意外消失的棋手来说是很难接受的。除非连接极其可靠，不太可能断开（比如在局域网上进行的游戏），否则你就必须考虑到这是无意的可能性。

* **Institute a penalty for disconnections, less severe than forfeiture.** If you disconnect in the middle of combat during an EverQuest session, your avatar remains in the game for a minute, taking additional damage. Unfortunately, it doesn't fight very well by itself!\
**对断开连接实施惩罚，惩罚程度低于没收。** 如果您在 EverQuest 会话期间的战斗中断开连接，您的化身会在游戏中停留一分钟，并受到额外伤害。不幸的是，它自己并不能很好地战斗！

* **Award victory to whoever is ahead in the game.** The problem with this is that the moment someone goes ahead, she can disconnect to prevent her opponent from having a chance to catch up. Again, you should consider this only in circumstances in which it is difficult or impossible to disconnect intentionally.\
**谁在游戏中领先，谁就能获得胜利。** 这样做的问题是，一旦有人领先，她就可以断开连接，不让对手有机会追上。同样，只有在很难或不可能故意断开连接的情况下，你才应该考虑这样做。

* **Record it as a tie.** Obviously, this motivates a player who is behind in the game to disconnect intentionally. It is a fairly neutral solution, however.\
**记录为平局。** 显然，这会促使落后的棋手故意断开连接。不过，这是一个相当中性的解决方案。

* **Record it as a "disconnected game."** You then have to decide exactly what this means in the context of a tournament, say. If the records are visible to the players, they might notice when someone has a suspiciously high number of disconnections and avoid playing with that person.\
**记录为“断开连接的对局”。** 然后你必须决定这在比赛中到底意味着什么如果玩家可以看到这些记录，他们可能会注意到有人断开连接的次数很高，从而避免与此人进行游戏。

* **Abandon the game entirely.** This is the fairest solution in the case of accidental disconnections, but it is unfair to whoever is leading if the player who is behind pulls the plug.\
**完全放弃游戏。** 在意外断开连接的情况下，这是最公平的解决方案，但如果落后的玩家拔掉插头，则对领先的玩家不公平。

> **Questions to Ask Yourself 向自己提出问题**
> 
> There's no one right answer to this problem; it depends too much on the nature of the game. It's up to you as the designer to think about it and try to decide what's fair. Here are some questions to ask yourself:
> 
> 这个问题没有唯一的正确答案；它在很大程度上取决于游戏的性质。作为设计者，你应该好好考虑一下，并尝试决定怎样做才是公平的。下面是一些需要问自己的问题：
> 
> What will happen to the gameplay when a player vanishes? How will it affect the other players' experience of the game (what they see and hear)? Does it disrupt the balance of the game? Will it make the challenges easier or harder? Is the game even meaningful anymore?
> 
> 当一个玩家消失时，游戏会发生什么？它会如何影响其他玩家的游戏体验（他们的所见所闻）？它会破坏游戏的平衡吗？它会让挑战变得更容易还是更难？游戏是否还有意义？
> 
> What happens to the score when a player vanishes—the players' relative progress toward victory? Is the game still fair?
> 
> 玩家消失后，分数会发生什么变化？游戏还公平吗？
> 
> Does your game offer a player an advantage of some kind for intentionally disconnecting himself (whether by preventing himself from losing or by sealing his own victory)? Is there any way to minimize this without penalizing players who are disconnected accidentally?
> 
> 你的游戏是否会为故意断开连接的玩家提供某种优势（无论是通过防止自己输掉比赛还是通过封印自己的胜利）？有没有办法在不惩罚意外断开连接的玩家的情况下尽量减少这种情况？

## Real-Time Versus Turn-Based Games 实时游戏与回合制游戏

Many online games take place in real time, with each player acting simultaneously. This offers them maximum freedom; they always have something to do and can order their activities any way they like. It's also more immersive than turn-based gaming. Waiting your turn while other players act harms suspension of disbelief. Unfortunately, real-time gaming tends to make a strategy game into an action game. Whichever player moves his pieces fastest has the advantage. In games such as [Command and Conquer](https://en.wikipedia.org/wiki/Command_%26_Conquer), victory becomes a matter of establishing an efficient weapons-production system as quickly as possible.

许多在线游戏都是实时进行的，每个玩家同时行动。这为他们提供了最大的自由度；他们总是有事可做，可以随意安排他们的活动。这也比回合制游戏更能让玩家身临其境。在其他玩家行动时等待轮到自己，会让人产生不信任感。不幸的是，实时游戏往往会把策略游戏变成动作游戏。哪个玩家移动棋子的速度最快，哪个玩家就占优势。在[《命令与征服》](https://en.wikipedia.org/wiki/Command_%26_Conquer)等游戏中，胜利变成了尽快建立高效武器生产系统的问题。

Turn-based games seem rather old-fashioned nowadays, but there is still a demand for them. Many simpler online games are automated versions of noncomputerized card games and the like, and they still require players to take turns. For this to work smoothly, you must include certain features:

如今，回合制游戏似乎已经过时，但仍有需求。许多较简单的在线游戏是非电脑纸牌游戏等的自动版本，它们仍然需要玩家轮流进行。要想顺利进行，你必须加入某些功能：

* **Limit the number of players in one game.** Four or five is a good maximum. With more than this, players will have to wait too long between turns and will grow impatient.\
**限制一局游戏的玩家人数。** 最多四或五人即可。如果人数超过这个上限，玩家就不得不在两轮之间等待太长时间，从而变得不耐烦。

* **Set a time limit on the length of a player's turn.** They mustn't be allowed to hold up the game while taking their turn. Both the player whose turn it is and all the other players should be able to see a countdown timer. The length of time will naturally vary depending on the sort of game it is; for a card game such as Hearts, we recommend no more than 10 seconds.\
**对玩家的轮次设置时间限制。** 在轮到他们的时候，不能让他们耽误游戏。轮到自己的玩家和所有其他玩家都应能看到倒计时器。时间的长短自然会因游戏的种类而异；对于红心之类的纸牌游戏，我们建议不超过 10 秒。

* **Determine a reasonable default action if the player runs out of time.** In games in which it's allowed, this might simply be to pass without acting, but in a game such as checkers, in which a move is required, the game will have to choose one. It doesn't have to be a very smart move, however. It's up to the player to supply the intelligence; if he doesn't, it's his own fault.\
**如果玩家没时间了，确定一个合理的默认动作。** 在允许这样做的游戏中，这可能只是不采取行动而通过，但在像跳棋这样需要走一步棋的游戏中，游戏就必须选择一个。不过，这一步并不一定要走得很聪明。聪明与否取决于玩家；如果他不聪明，那就是他自己的错。

* **Let players do other things while waiting their turn.** They should definitely be allowed to chat with one another, study the battlefield, organize their units, or do anything else that doesn't actually influence the gameplay.\
**让玩家在等待轮到他们的时候做其他事情。** 肯定应该允许他们互相聊天、研究战场、组织他们的部队或做其他任何实际上不会影响游戏的事情。

* **Allow simultaneous turns.** This might sound like an oxymoron, but a few games, such as Age of Wonders II, allow all the players to take their turns simultaneously. The turn ends, and the results are computed and displayed when all of the players have input their moves.\
**允许同时回合。** 这听起来可能有点矛盾，但有些游戏，如《奇迹时代 II》，允许所有玩家同时回合。当所有玩家都输入了自己的棋步后，回合结束，结果将被计算并显示出来。

## Chat 聊天

Every multi-player game for machines that have a keyboard should include a chat feature—a mechanism that enables players to send messages to one another. Depending on the nature of the game, players should be able to send private messages to one other individual, messages only to members of their own team (if any), or general broadcast messages to all other players who might reasonably be interested. Obviously, if there are thousands of players in a game, any one player should be able to broadcast messages only to those in his "local vicinity," whatever that might mean in the context of the game.

每款有键盘的多人游戏都应包含聊天功能--一种能让玩家相互发送信息的机制。根据游戏的性质，玩家应能向一个人发送私人信息，或只向自己的团队成员（如果有的话）发送信息，或向所有其他可能感兴趣的玩家发送一般广播信息。显然，如果一个游戏中有成千上万的玩家，那么任何一个玩家都只能向他 “本地附近 ”的玩家发送信息，无论这在游戏中意味着什么。

Unfortunately, chat brings problems with it: rude, abusive, or harassing behavior. People who are paying to play your game have expectations that others will meet certain minimum standards of behavior. In a sporting event, this is enforced by the referee or, at minimum, by the collective authority of the other players. Online, it's much more difficult to enforce.

不幸的是，聊天也会带来问题：粗鲁、辱骂或骚扰行为。花钱玩游戏的人都希望其他人的行为符合某些最低标准。在体育比赛中，这可以通过裁判或其他玩家的集体权威来实现。而在网络上，执行起来要困难得多。

> **Psychological disinhibition:** People act like jerks more easily online because anonymity is intoxicating. It is easier to objectify other people and, therefore, to treat them badly. The only way to combat this is to get them to empathize more with other players.
> 
> **心理抑制：** 人们在网上更容易表现得像个混蛋，因为匿名性令人陶醉。人们更容易将他人物化，因此也更容易对他们不好。对付这种情况的唯一办法就是让他们更多地同情其他玩家。

### Dirty-Word Filters 脏话过滤器

Dirty-word filters have been tried, but they never work—and they sometimes produce laughable results. Words such as damn and hell are perfectly legitimate in a religious context, even if they're considered swearing in another context. In any case, people always get around such filters by misspelling the words. Don't bother trying to implement a dirty-word filter unless you also back it up by other means, such as online customer service representatives.

脏话过滤器曾被尝试过，但从未奏效，有时还会产生令人啼笑皆非的结果。在宗教语境中，“该死”（damn）和 “地狱”（hell）等词是完全合法的，即使它们在其他语境中被认为是脏话。无论如何，人们总是通过拼错这些词来绕过这些过滤器。除非你还通过其他方式（如在线客服代表）来支持脏话过滤器，否则不要费心去尝试实施脏话过滤器。

### Complaint and Warning Systems 投诉和警告系统

Some chat systems include mechanisms designed to discourage online rudeness. A complaint system enables players to push a "complain" button whenever they receive an offensive message. The message is automatically forwarded to someone with authority over the game (usually an online customer service person), who can then investigate and take appropriate action: warn the offender to mend his ways or even kick him offline.

有些聊天系统包含旨在阻止在线粗鲁行为的机制。投诉系统可以让玩家在收到攻击性信息时按下 “投诉 ”按钮。信息会自动转发给游戏中的权威人士（通常是在线客户服务人员），后者可以进行调查并采取适当措施：警告违规者改正错误，甚至将其踢下线。

The America Online Instant Messenger includes a fully automated system that allows users to warn each other, either anonymously or openly, when one of them is behaving badly. A user can be warned once per message that he sends; the more warnings he receives, the less frequently he is allowed to send messages. If he receives enough, he is unable to send any for several hours. The effect of the warnings fades over time.

美国在线即时信使包括一个全自动系统，当用户中有人行为不端时，可以匿名或公开警告对方。用户每发送一次信息，就会受到一次警告；收到的警告越多，允许他发送信息的次数就越少。如果收到的警告足够多，他就会在几个小时内无法发送任何信息。警告的效果会随着时间的推移而减弱。

### Ignoring Other Players 忽略其他玩家

A useful feature of some chat mechanisms is the capacity to ignore other people who are being offensive. The player simply selects the name of a person he wants to ignore, and he no longer receives chat messages from that person. You can permit this to take place silently (the other player doesn't know she's being ignored) or automatically send a message telling her that she has been ignored—the online equivalent of deliberately turning your back on someone. This is one of the most efficient mechanisms available because it doesn't require staff intervention.

某些聊天机制的一个有用功能是可以忽略其他正在冒犯自己的人。玩家只需选择想要忽略的人的名字，就不会再收到此人的聊天信息。你可以允许这种情况无声地发生（对方不知道自己被忽略了），也可以自动发送信息告诉她自己被忽略了--相当于在网上故意背对着某人。这是最有效的机制之一，因为它不需要工作人员的干预。

### Moderated Chat Spaces 有管控的聊天空间

The most effective, but also the most expensive, way of keeping order in a chat space is to give one person authority to discipline the others at all times. This feature is used on Internet Relay Chat, in which the creator of a chat room has the authority to kick people out of it. It is, however, subject to abuse. In a game that people are paying for, you can't safely hand over that authority to one of the players; the moderator has to be an impartial representative of the game's provider—a customer service agent, in effect, whether paid or unpaid.

维持聊天空间秩序最有效但也最昂贵的方法是授权一个人随时约束其他人。Internet Relay Chat 上就有这种功能，聊天室的创建者有权将他人踢出聊天室。不过，这也有可能被滥用。在人们付费的游戏中，你不能放心地把这个权力交给某个玩家；版主必须是游戏提供商的公正代表——实际上是客户服务人员，无论是否付费。

## Collusion 串通

Most games—true games, in which players compete for victory—are designed with an assumption that the players will try to beat one another and that there is never any reason for them to help each other. Often this assumption is formalized in the rules. For example, in Monopoly, one of the rules states, "No player may borrow from or lend money to another player." Collusion is a form of cheating in which players who are supposed to be opponents work together in violation of the rules. In Monopoly, what prevents collusion is the players' agreement to abide by the rules, the potential damage to their friendship if they don't, and the fact that they're all watching each other to prevent it. Unfortunately, you can't count on any of these factors in an online game. Some players will join a game with a deliberate, even avowed, intent to cheat. Because they're playing with strangers, there's nothing at stake, and because they're physically miles apart, no one can see them do it. If you cheat at a board game, you'll most likely be thrown out of the game and your friends won't ever play with you again. Unfortunately, these kinds of penalties are difficult to enforce in online games.

大多数游戏——真正的游戏，即玩家为胜利而竞争的游戏--在设计时都有一个假设，即玩家会试图打败对方，而且他们之间永远没有理由互相帮助。这种假设通常被正式写入游戏规则中。例如，在大富翁游戏中，其中一条规则规定：“任何玩家不得向其他玩家借钱或借钱给其他玩家”。串通是一种作弊行为，即本应是对手的玩家违反规则，共同合作。在《大富翁》中，防止串通的因素是玩家们同意遵守规则，如果不遵守规则，他们的友谊就可能受到损害，而且为了防止串通，他们都会互相监督。不幸的是，在网络游戏中，这些因素你都指望不上。有些玩家会故意加入游戏，甚至公然作弊。因为他们是在和陌生人玩游戏，没有什么利害关系，而且因为他们相隔万里，没有人能看到他们作弊。如果你在棋盘游戏中作弊，你很可能会被赶出游戏，你的朋友也不会再和你一起玩。不幸的是，这类惩罚在网络游戏中很难实施。

### Examples of Collusion 串通实例

Computer games seldom have written rules because the designers assume that the game will enforce the rules automatically: The players simply can't make illegal moves, for example. However, there's no way for the software to detect certain kinds of collusion between players. Consider an online multiple-choice trivia game. Each question has three possible answers. Each player receives the same question from the server and has a fixed length of time in which to enter an answer. When he enters it, he immediately learns whether he was right or wrong. Correct answers earn points, and the player with the largest number of points at the end of the game is the winner.

电脑游戏很少有成文的规则，因为设计者认为游戏会自动执行规则：例如，玩家根本无法做出非法动作。然而，软件却无法检测出玩家之间的某些串通行为。请看一款在线选择题游戏。每个问题都有三个可能的答案。每个玩家都会从服务器收到相同的问题，并有固定的时间输入答案。输入答案后，他将立即知道自己的答案是对是错。正确答案可获得积分，游戏结束时积分最高的玩家即为获胜者。

Four players can easily collude at this game to guarantee that one of them will win. They all play on different machines in the same physical location—an Internet café, for example. When a question appears, three of the players immediately enter a different response—A, B, or C—and the fourth one waits. When the software informs one of three players that she is correct, she immediately calls out her letter, and the fourth player enters it before the time runs out. This way the fourth player always enters the correct answer.

在这个游戏中，四个玩家可以很容易地串通起来，保证其中一个玩家获胜。他们可以在同一地点（例如网吧）的不同机器上进行游戏。当出现一个问题时，其中三个玩家立即输入不同的答案--A、B 或 C，第四个玩家则等待。当软件通知三位玩家中的一位正确时，她会立即喊出她的字母，第四位玩家会在时间结束前输入。这样，第四位玩家总是输入正确答案。

This form of collusion is easily defeated: You simply don't reveal the correct answer until the time has run out to enter it. Players who enter an answer early simply have to wait to find out whether they were right. But other forms of collusion can be more insidious. If you offer a prize for the player who wins the greatest number of chess games in a certain length of time, for example, two players can collude to play each other, with one always trying to lose to the other as quickly as possible.

这种形式的串通很容易被破解：你只需在输入正确答案的时间结束之前不公布答案即可。提前输入答案的玩家只需等待就能知道自己是否正确。但其他形式的串通可能更加隐蔽。例如，如果你为在一定时间内赢得最多棋局的棋手提供奖励，那么两位棋手就可以串通起来互相对弈，其中一位棋手总是试图尽快输给另一位棋手。

### Designing to Reduce Collusion 减少串通的设计

Part of your job as a designer of an online game is to try to anticipate collusion as much as possible. Unfortunately, experience has shown this to be an extremely difficult thing to do. There are no limits on players' ingenuity or the lengths to which some will go, and, of course, there are thousands of them to only one of you. Even if your game doesn't offer a chat feature, players can play from two machines in the same room or call each other on cellphones to collude.

作为网络游戏的设计者，你的工作之一就是尽可能地预测串通行为。不幸的是，经验表明这是一件极其困难的事情。玩家的聪明才智和某些人的不择手段都是无止境的，当然，他们有成千上万，而你只有一个。即使您的游戏不提供聊天功能，玩家也可以在同一房间的两台机器上进行游戏，或用手机互相通话进行串通。

You can't prevent players from colluding, but you can design the game to minimize its effects. Here are some types of collusion to consider:

你无法阻止玩家串通，但你可以在设计游戏时尽量减少其影响。以下是一些需要考虑的串通类型：

* **Sharing secret knowledge.** Does the player ever have secret knowledge that she can share to someone else's benefit? In the trivia game described previously, some players are given the correct answer before the time runs out. Withholding this information makes collusion pointless.\
**分享秘密知识。** 玩家是否曾经拥有可以分享给他人的秘密知识？在前面描述的琐事游戏中，一些玩家会在时间结束前得到正确答案。隐瞒这些信息会使串通变得毫无意义。

* **Passing cards (or anything else) under the table.** Does the game include mechanisms to transfer assets from one player to another? Is there any way to abuse these mechanisms?\
**桌下传牌（或其他任何东西）。** 游戏中是否包含将资产从一个玩家转移到另一个玩家的机制？是否有任何方法可以滥用这些机制？


* **Taking a dive.** What are the consequences if one player deliberately plays to lose? Obviously, this makes a huge difference if you allow gambling on matches (even if only with "play" money).\
**跳水。** 如果一方玩家故意输钱，会有什么后果？很明显，如果你允许在比赛中赌博（即使只用 “玩 ”钱），这就会产生巨大的不同。

If you're designing a game in which it's supposed to be every player for herself, try imagining what would happen if you made it a team game in which players were supposed to collaborate. If it's already a team game, try to imagine what would happen if one player on the team were a spy for the other team.

如果你正在设计一款游戏，而在这款游戏中，每个玩家都应该为自己而战，那么试着想象一下，如果你把它设计成一款团队游戏，让玩家们相互协作，会发生什么。如果这已经是一个团队游戏，那么试着想象一下，如果团队中的一个玩家是另一个团队的间谍，会发生什么。

## Technical Security 技术安全

For some reason, people feel a strong impulse to test the limits of computer software—to see what it will do with nonsensical data, for example. In playing a war game, it is a rare player who will not at some point try to order his troops to fire on his own side, just to see what will happen. Similarly, players often think of ways to do things in a manner that the designers never intended or expected. Sometimes these unanticipated maneuvers, such as using the rocket launcher to propel yourself upward in Quake, even become standard tactics.

出于某种原因，人们对测试计算机软件的极限有一种强烈的冲动——例如，看看它能对无意义的数据做些什么。在玩战争游戏时，很少有玩家不会在某些时候试图命令自己的部队向己方开火，看看会发生什么。同样，玩家经常会想出一些设计者从未想过或预料不到的方法。有时，这些意想不到的操作，如在 Quake 中使用火箭发射器将自己向上推进，甚至会成为标准战术。

Making unexpected but legal moves is still fair; one can argue that the designers should have anticipated these tactics or that the testers should have discovered them for themselves. Other forms of cheating, such as hacking the game's software or data files, are clearly unfair. In a single-player game, it doesn't really matter, however. It's rather like cheating at solitaire, and it says more about the player's character than anything else. It is a peculiarity of modern computer games that they are often so difficult that they must come with built-in cheats. Originally these cheats were built in during development to make testing easier and were removed when the game shipped, but now they are often left in for the public to use as well.

做出意料之外但合法的动作仍然是公平的；我们可以争辩说，设计者本应预料到这些战术，或者测试者本应自己发现这些战术。其他形式的作弊，如入侵游戏软件或数据文件，显然是不公平的。不过，在单人游戏中，这并不重要。这就像接龙游戏中的作弊行为，更能说明玩家的性格。现代电脑游戏的一个特点是，它们往往非常困难，以至于必须内置作弊器。最初，这些作弊器是在开发过程中为了方便测试而内置的，在游戏上市后就会被移除，但现在这些作弊器往往也会被保留下来，供公众使用。

The issue of cheating in multi-player games is considerably more serious. People who wouldn't dream of cheating their close friends in person—say, playing poker around the living room table—are happily willing to cheat strangers when protected by the distance and anonymity that an online game offers. There's still that temptation to try to break the software, especially because players have gotten used to the notion that computer games will enforce the rules for them. They assume that anything that they can do, they are allowed to do.

多人游戏中的作弊问题要严重得多。有些人做梦也不会想到要欺骗自己的好友--比如在客厅的桌子旁玩扑克--但在网络游戏提供的距离和匿名性的保护下，他们很乐意欺骗陌生人。试图破解软件的诱惑依然存在，尤其是因为玩家已经习惯了电脑游戏会为他们执行规则的观念。他们认为，只要他们能做的，他们就可以做。

This is a grave problem. Players have a moral right to expect a fair game when they're playing against other people, and they have a legal right to it as well if they're paying for the privilege of playing. This becomes even more true if they're playing for prizes. Although all game software comes with a disclaimer that it's sold "as-is" and without any warranty, the moment you start to give out prizes of real monetary value, you have to be very careful to make sure the game is fair.

这是一个严重的问题。当玩家与其他人进行游戏时，他们有道德权利要求游戏公平，如果他们为游戏特权付费，他们也有法律权利要求游戏公平。如果他们是为了奖品而玩游戏，这一点就更加正确。虽然所有游戏软件都附有免责声明，说明软件是 “按原样 ”出售的，没有任何保证，但当你开始发放具有实际货币价值的奖品时，你就必须非常小心，以确保游戏的公平性。

### Use a Secure Telecommunications Protocol 使用安全的通信协议

It takes an extremely dedicated hacker to tamper with the data stream between the client software and the server, but it takes only one. If the stakes are high enough, it can be well worth it. To foil this, your software must use a secure telecommunications protocol. Designing such a thing is a programming problem and is beyond the scope of this book, but we include a few suggestions.
要篡改客户端软件和服务器之间的数据流，需要非常专业的黑客，但这只需要一个人。如果赌注足够大，这样做是值得的。为了阻止这种情况，你的软件必须使用安全的电信协议。设计这样的协议是一个编程问题，超出了本书的讨论范围，但我们在此提出几点建议。

* First, all data should be encrypted to prevent users from understanding its contents. It should also include a suitable checksum, which will enable the software to detect whether it has been garbled in transmission.\
首先，所有数据都应加密，以防止用户理解其内容。数据还应包括适当的校验和，以便软件能够检测数据在传输过程中是否出现乱码。

* Second, you might want to consider a "heartbeat" mechanism in which your client software sends a short packet to your server at regular intervals, even when there is no data to be transmitted, simply to tell the server that the client is still present.\
其次，你可能需要考虑一种“心跳”机制，在这种机制下，即使没有数据需要传输，你的客户端软件也会每隔一段时间向服务器发送一个短数据包，目的只是告诉服务器客户端仍然存在。

* And as we described earlier, all packets should include a unique serial number to indicate what order they belong in and to prevent spurious packets from being inserted by unauthorized means.\
正如我们前面所描述的，所有数据包都应包含一个唯一的序列号，以表明其所属的顺序，并防止以未经授权的方式插入虚假数据包。

### Don't Store Sensitive Data on the Player's Computer 不要在玩家电脑上存储敏感数据

Typically two kinds of data about a player exist in a game. One kind is settings or preferences about the way the player appears and likes to play. The other is information that's actually relevant to the game state: the player's position, score, possessions, and so on. In Monopoly, for example, the player's playing piece (hat, shoe, car, and so on) belongs in the former category; it doesn't matter which token the player is using. However, the player's properties, cash, and position on the board belong in the latter; changes to them affect the player's status in the game.

游戏中通常存在两种关于玩家的数据。一种是关于玩家出场方式和喜欢的游戏方式的设置或偏好。另一种是与游戏状态实际相关的信息：玩家的位置、得分、占有率等。例如，在《大富翁》中，玩家的棋子（帽子、鞋子、汽车等）属于前一类；玩家使用的是哪种代币并不重要。然而，玩家的财产、现金和在棋盘上的位置则属于后者；它们的变化会影响玩家在游戏中的地位。

This second kind of information shouldn't be stored on the player's own computer. Even with encryption techniques, you have to assume that any data kept on the player's machine is subject to tampering and could be used to give the player an unfair advantage over others. If there's really too much sensitive data about each character to store it all on the server, at least store a checksum over the data when the player logs out so that when he logs back in again, you can check over his data and see if it has been improperly modified in the meantime.

第二类信息不应该存储在玩家自己的电脑上。即使使用了加密技术，你也必须假设任何保存在玩家机器上的数据都有可能被篡改，并可能被用来让玩家获得对其他人不公平的优势。如果每个角色的敏感数据真的太多，无法全部存储在服务器上，至少也要在玩家注销时对数据存储一个校验和，这样当他再次登录时，你就可以检查他的数据，看看是否在此期间被不适当地修改过。

### Don't Send the Player Data He Isn't Supposed to Have 不要向玩家发送他不该拥有的数据

A common characteristic of real-time strategy games is the "fog of war," in which unexplored areas of the map are dark and the movements of the enemy are not visible unless a friendly unit is nearby to see them. In single-player games, all this information is in the player's computer, of course; it's just not visible to the player. In an online game, any hidden information should not be sent to the player. If the player hacks the game to lift the fog of war, he can see unexplored areas and watch the movements of enemy units, which gives him a significant advantage over his opponents.

即时战略游戏的一个共同特点是 “战争迷雾”，在这种迷雾中，地图上未开发的区域一片漆黑，除非附近有友军部队，否则看不到敌人的动向。在单人游戏中，所有这些信息当然都在玩家的电脑中，只是玩家看不到而已。在网络游戏中，任何隐藏信息都不应发送给玩家。如果玩家黑进游戏，拨开战争迷雾，他就能看到未开发的区域，观察敌方单位的动向，从而在与对手的较量中占据明显优势。

### Don't Let the Client Perform Sensitive Operations 不要让客户端执行敏感操作

If you're designing a client/server game, there is always a balance to be struck between the amount of processing that the server does and the amount that the client does. It's clearly cheaper for you to offload as much of the processing work onto the client that you can. However, it isn't always safer. Suppose, for example, that you're designing a very simple role-playing game in which the player occasionally encounters monsters and must do battle with them. It's cheapest for the server to send the client some information about the current monster, and let the fight take place entirely on the player's computer. When the fight is over, the client sends a message back to the server saying whether the player won, lost, or ran away. However, this is obviously very dangerous. If the player has hacked his client, he could program it to report that he wins every fight. In fact, the server, not the client, should act out the fight and determine whether the player won or lost.

如果你正在设计一款客户端/服务器游戏，那么服务器的处理量和客户端的处理量之间总是需要取得平衡。对你来说，将尽可能多的处理工作卸载到客户端显然更省钱。但是，这并不总是更安全。例如，假设你正在设计一款非常简单的角色扮演游戏，在游戏中玩家偶尔会遇到怪物，并必须与之战斗。最便宜的做法是，服务器向客户端发送一些关于当前怪物的信息，然后让战斗完全在玩家的电脑上进行。战斗结束后，客户端会向服务器发送一条信息，说明玩家是赢了，输了，还是逃跑了。然而，这显然非常危险。如果玩家黑进了自己的客户端，他就可以通过编程让客户端报告自己赢得了每一场战斗。事实上，应该由服务器而不是客户端来执行战斗，并确定玩家是赢了还是输了。

> **Never trust the client:** Never put anything on the client. The client is in the hands of the enemy. Never ever forget this.
> 
> **永远不要相信客户端：** 永远不要把任何事情寄托在客户端身上。客户端掌握在敌人手中。永远不要忘记这一点。

The legitimate players aren't the enemy, of course, but the handful of cheaters are. We lock our doors at night not to protect us from the honest majority of the population, but to protect us from the dishonest minority. You will have to design your game with the same consideration in mind.

当然，合法玩家不是敌人，但少数作弊者才是。我们晚上锁门，不是为了保护我们不受诚实的大多数人的伤害，而是为了保护我们不受不诚实的少数人的伤害。你在设计游戏时也要考虑到这一点。