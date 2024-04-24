# Introduction 序言

Every game player is a potential game designer, and that means you.

每个游戏玩家都是潜在的游戏设计师，这也包括你。

When you were a kid, you probably started many a game of whiffle ball or Monopoly with a little negotiation over the rules. “If the ball gets stuck in a tree, it's an out,” “Chance and Community Chest fines go into a pool, and whoever lands on Free Parking gets the money,” and so on. Kids don't hesitate to change the rules of existing games to make them more enjoyable. The participatory nature of playing a game encourages us to think about, and sometimes modify, its rules—that is, its design. And that's just as true of video games, too. We've all played games that we thought could be improved by a few adjustments.

当你还是个孩子的时候，你可能会在玩威浮球或大富翁游戏时，就游戏规则进行一番协商。“如果球卡在树上，那就是出局”，“机会和公益金的罚金都会进入一个池子，谁在免费停车上拿到了钱”，等等。孩子们会毫不犹豫地改变现有游戏的规则，使其更加有趣。玩游戏的参与性促使我们思考，有时甚至修改游戏规则，也就是游戏的设计。电子游戏也是如此。我们都玩过一些游戏，我们认为只要稍作调整就能改进游戏。

But some people want to do more than alter the rules; they want to create entirely new games and even new kinds of games. Their heads are full of worlds to play in, characters to encounter, challenges to meet. Because you're reading this, you're almost certainly one of those people. Chances are that right this minute, you've got a great idea for a game your head—maybe half a dozen of them. But how do you turn a game idea into a game design?

但有些人想做的不仅仅是改变规则，他们还想创造全新的游戏，甚至是新种类的游戏。他们的脑子里充满了要玩的世界、要遇到的角色、要迎接的挑战。因为你正在阅读这篇文章，所以几乎可以肯定，你就是这些人中的一员。很可能此时此刻，你的脑子里已经有了一个很棒的游戏创意——也许有六七个之多。但如何将游戏创意转化为游戏设计呢？

## From Idea to Design 从创意到设计

We wrote this book to answer that question, specifically for people who want to design computer and video games. We discuss both the theory and the practice of game design: the why and the how. A design is much more than an idea; it's a blueprint for building an enjoyable and challenging game. We'll give you practical advice about how to design a game, what kinds of decisions you'll face as you go along, and how to write it all down in a design document. The design document communicates your intentions to the people who will build your game, and even if you plan to build it by yourself, you still need to keep a record of the choices you've made—and those you still need to make. By the end of this book, you will have the tools you need to design many kinds of games, and to create a professional-quality game design document.

我们专门为想要设计电脑和视频游戏的人编写了这本书来回答这个问题。我们讨论了游戏设计的理论和实践：为什么和怎么做。设计远不止是一个想法，它是构建一个愉快而富有挑战性的游戏的蓝图。我们将为你提供实用的建议，告诉你如何设计一款游戏，在设计过程中你将面临哪些抉择，以及如何将这一切写入设计文档。设计文档可以向制作游戏的人传达你的意图，即使你打算自己制作游戏，你仍然需要记录你已经做出的选择，以及你仍然需要做出的选择。在本书结束时，你将掌握设计多种游戏所需的工具，并制作出专业品质的游戏设计文档。

## What This Book Is (and Isn't) About 这本书是什么（不是什么）？

Andrew Rollings and Ernest Adams on Game Design contains our combined thoughts on the important issues that relate to designing games. We don't claim that it's the final word on game design. No book could be. We have chosen to address areas that we believe are important and under-served, and we don't expect everyone to agree with us on every point. That's the beauty and the terror of game design: There are no right answers.

《安德鲁·罗林斯和欧内斯特·亚当斯论游戏设计》包含了我们对游戏设计相关重要问题的综合思考。我们并不宣称这是游戏设计方面的定论。没有一本书可以做到这一点。我们选择了一些我们认为重要且未得到充分关注的领域，我们并不期望每个人都同意我们的观点。这正是游戏设计的美妙和可怕之处： 没有正确的答案。

We offer a game design methodology intended to spur your thinking and get your creative juices flowing. In this book, you will not find step-by-step instructions on how to create the next Doom or Tetris clone. Instead, we discuss the central issues that every game designer must face, and we pose a series of questions for you to ask yourself about the game that's in your head. The answers to those questions will move you along the path from idea to design.

我们提供的游戏设计方法旨在激发你的思考，让你的创意源源不断。在本书中，你不会看到如何创造下一个《毁灭战士》或《俄罗斯方块》翻版的分步指导。相反，我们讨论了每个游戏设计师必须面对的核心问题，并提出了一系列问题，让你就脑海中的游戏自问自答。这些问题的答案将推动你从创意走向设计。

One area that we have not addressed is level design. The reason for this is simple: There is no one standard way to design levels. Level design considerations are different for each genre of game, and we simply don't have the space to address them all properly. By examining the essential elements of a genre, we hope to give you the tools to design enjoyable levels, but the process itself is, as they say, “left as an exercise for the reader.”

我们尚未涉及的一个领域是关卡设计。原因很简单：没有一种标准的关卡设计方法。每种类型的游戏都有不同的关卡设计考虑因素，我们根本没有足够的篇幅来一一详述。通过研究某一类型游戏的基本要素，我们希望能为您提供设计愉快关卡的工具，但正如他们所说的那样，这个过程本身“留给读者练习”。

You are at the beginning of a voyage of discovery. Our book is a map with white space beyond the borders. We are sharing what we know about game design in order to enable you to navigate through the familiar regions and then to press on into terra incognita. We hope that you will in turn transmit your own learning to others, continuing to fill in the map and helping to push out the boundaries of game design. The journey begins here.

你正处于探索之旅的起点。我们的书就像一张地图，边界之外还有空白区域。我们分享我们所知的游戏设计知识，帮助您探索熟悉的区域，然后勇闯未知之地。我们希望你能将自己的所学传授给他人，继续填满地图，帮助拓展游戏设计的边界。旅程从这里开始。

## How This Book Is Organized 本书的编排方式

Andrew Rollings and Ernest Adams on Game Design is divided into two parts. The first eight chapters are about designing games in general: what a game is, how it works, and what kinds of decisions you have to make to create one. The next ten chapters are about different genres of games and the design considerations peculiar to each genre.

《安德鲁·罗林斯和欧内斯特·亚当斯论游戏设计》分为两部分。前八章是关于一般的游戏设计：什么是游戏、游戏是如何运行的以及制作游戏需要做出哪些决定。接下来的十章是关于不同类型的游戏以及每种类型的游戏在设计时所需要考虑的因素。

### Part One: The Elements of Game Design 第一部分：游戏设计的要素

Chapter 1 provides an introduction to game design: what the designer needs to do and why. It also discusses the key talents and skills that game designers should have.

[第一章](chapter-1.md)介绍了游戏设计：设计师需要做什么以及为什么要做。它还讨论了游戏设计师应具备的关键才能和技能。

Chapter 2 is about game concepts: where the idea for a game comes from and how to refine it. The audience and the target hardware (the machine the game will run on) both have a strong influence on the direction the game will take.

[第二章](chapter-2.md)是关于游戏概念：游戏创意的来源以及如何完善创意。受众和目标硬件（游戏运行的机器）都会对游戏的方向产生很大影响。

Chapter 3 is about the game's setting and world: the place where the gameplay happens, and the way things work there. As the designer, you're the god of your world, and it's up to you to define its concepts of time and space, mechanics, and natural laws, as well as many other things: its logic, emotions, culture, and values.

[第三章](chapter-3.md)是关于游戏的背景和世界：游戏发生的地方，以及游戏的运行方式。作为设计者，你就是你的世界之神，你要定义这个世界的时间和空间概念、运作方式和自然法则，以及许多其他东西：它的逻辑、情感、文化和价值观。

Chapter 4 delves into the problems of storytelling and narrative: how to create a compelling storyline, and how to balance the inevitable tension between your desire for control as a designer, and the player's desire for freedom as an actor in your world.

第四章深入探讨了讲故事和叙事的问题：如何创造引人入胜的故事情节，以及如何平衡你作为设计师的控制欲和玩家作为你世界中的演员的自由欲之间不可避免的紧张关系。

Chapter 5 addresses character design: inventing the people, or beings, that populate your game world—especially the character who will represent the player there (his avatar), if there is one. Every successful entertainer from Homer onward has understood the importance of having an appealing protagonist.

第五章讲述角色设计：创造游戏世界中的人或生物——尤其玩家扮演的角色（他的化身），如果有的话。

从《荷马史诗》开始，每个成功作品的创作者都明白拥有一个迷人主角的重要性。

Chapter 6 is about user interface design: the way that the player experiences and interacts with the game world. A bad user interface can kill an otherwise brilliant game, so you must get this right.

第六章是关于用户界面设计：玩家体验游戏世界并与之互动的方式。糟糕的用户界面可能会扼杀一款出色的游戏，因此你必须做好这一点。&#x20;

Chapter 7 discusses gameplay, the heart of the player's mental experience of a game: the challenges he faces and the actions he takes to overcome them.

第七章讨论游戏玩法，即玩家在游戏中的核心心理体验：玩家面临的挑战和克服挑战的行动。

Chapter 8 looks at the internal economy or core mechanics of a game, and the flow of resources (money, points, ammunition, or whatever) throughout the game. It also addresses the key issue essential to all games: game balance.

第八章探讨游戏的内部经济或核心机制，以及整个游戏中资源（金钱、点数、弹药或其他）的流动。这一章还讨论了对所有游戏都至关重要的关键问题：游戏平衡。

### Part Two: The Genres of Games 第二部分：游戏类型

Chapter 9 is about the earliest, and still the most popular, genre of interactive entertainment: action games.

第九章讲述的是最早的，也是目前最流行的，互动娱乐类型：动作游戏。&#x20;

Chapter 10 discusses another genre that has been part of gaming since the beginning: strategy games, both real-time and turn-based.

第十章讨论了另一种从一开始就属于游戏的类型：策略游戏，包括即时战略游戏和回合制游戏。

Chapter 11 is about role-playing games, a natural outgrowth of pencil and paper games such as Dungeons & Dragons.

第十一章介绍角色扮演游戏，它是纸笔游戏（如龙与地下城）的自然产物。&#x20;

Chapter 12 looks at sports games, which have a number of peculiar design challenges. The actual contest itself is designed by others; the trick is to map human athletic activities onto a screen and control devices.

第十二章介绍体育游戏，体育游戏在设计上面临许多特殊的挑战。真实比赛本身是由他人设计的；诀窍在于将人类的运动活动映射到屏幕和控制设备上。

Chapter 13 addresses vehicle simulations: cars, planes, boats, and other, more exotic modes of transportation such as tanks and mechs.

第十三章涉及交通工具模拟：汽车、飞机、轮船以及其他更奇特的交通工具，如坦克和机甲。

Chapter 14 is about construction and management simulations, in which the player tries to build and maintain something—a city, a theme park, a planet—within the limitations of an economic system.

第十四章是关于建筑和管理模拟，在这种游戏中，玩家要在经济系统的限制范围内建造和维护一些东西——城市、主题公园、星球。&#x20;

Chapter 15 explores adventure games, an old and unique genre of gaming recently given new life by the creation of a hybrid type, the action adventure.

第十五章探讨冒险游戏，这是一种古老而独特的游戏类型，最近一种混合类型——动作冒险游戏的诞生赋予了它新的生命。

Chapter 16 examines a variety of other types of games: artificial life, software toys, puzzle games, and so on.

第十六章探讨了其他各种类型的游戏：人造生命、软件玩具、益智游戏等。

Chapter 17 is devoted to online games, which is not a genre but a technology. Online games enable people to play with, or against, each other in numbers from two up to hundreds of thousands. Playing against real people that you cannot see has enormous consequences for the game's design. The second half of the chapter addresses the particular problems of persistent worlds like EverQuest.

&#x20;第十七章专门讨论网络游戏，这不是一种类型，而是一种技术。网络游戏可以让人们相互之间进行游戏或对战，游戏人数从两个人到数十万人不等。与看不见的真人对战对游戏的设计产生了巨大的影响。本章的后半部分讨论了像 EverQuest 这样的持久世界的特殊问题。

Chapter 18 takes a look at the future of gaming and where we believe the medium will go, both in the short and long term.

第十八章探讨了游戏的未来，以及我们认为游戏媒体的短期和长期发展方向。

### Part Three: Appendixes 第三部分：附录 附录

Appendix A includes sample design documents and an extensive discussion of what they're used for.

附录 A 包括示例设计文档，以及对其用途的广泛讨论。

Appendix B is a bibliography of works that either we used in writing this book, or that we find particularly useful in creating our own designs.

附录 B 是一份参考书目，收录了我们在编写本书时使用过的作品，或者我们认为对我们自己的设计特别有用的作品。

## Non-Computer Games, Too! 非电脑游戏也是如此

This book is primarily about designing interactive entertainment: computer and video games of various kinds. You will notice, however, that we frequently refer to non-computerized games as well—card games like poker, board games like Monopoly, and so on. We do this for three reasons:

本书的主要内容是设计互动娱乐：各种计算机和视频游戏。不过，你会注意到，我们也经常提到非电脑化的游戏——扑克牌之类的纸牌游戏、大富翁之类的棋盘游戏，等等。我们这样做有三个原因：

First, those games are likely to be familiar to the largest number of people. Not all of our readers will have played computer games such as Planescape: Torment, and some will be too young to remember Colossal Cave, but everyone has heard of chess.

首先，这些游戏可能为最多的人所熟悉。并不是所有的读者都玩过电脑游戏，如《异域镇魂曲》之类的电脑游戏，有些人还太小，不记得《巨洞冒险》，但每个人都听说过国际象棋。

Second, simpler, non-computerized games tend to be designed around a single principle, so they serve to illustrate that principle well.

其次，较简单的非电脑化游戏往往是围绕一个原则设计的，因此它们可以很好地说明这一原则。

Finally, we believe that the essence of game design has little to do with the game's delivery medium. The principles that are common to all good games are independent of the means by which they are presented. A good game designer should be able to design board games, card games, pencil-and-paper games, and computer games with equal facility.

最后，我们认为游戏设计的精髓与游戏的传播媒介关系不大。所有优秀游戏的共同原则都与游戏的表现形式无关。一个优秀的游戏设计师应该能够同样出色地设计棋盘游戏、卡牌游戏、纸笔游戏和电脑游戏。

## A Word About Pronouns 关于代词

Because English doesn't include a gender-neutral pronoun applicable to humans, we have chosen to alternate, more or less randomly, between the use of “he” and “she” when speaking of indefinite individuals such as “the player” and “the designer.” After we have designated “the player” to be male or female in a given context, we retain that usage throughout the section in order to avoid confusion. We feel that constructions such as “s/he” and “he or she” are awkward and distracting. However, if you find yourself pulled up short by the idea of a female player of sports games or a male designer of Barbie games, that's all to the good. We don't believe that games should be segregated into pink genres for women and blue genres for men, and as a designer you should be aware that your game could be played by anyone, male or female.

由于英语缺乏适用于人类的性别中立代词，因此我们在谈论“玩家”和“设计师”等非特定个体时，或多或少随机交替使用“他”和“她”。一旦我们在特定情境中将“玩家”指定为男性或女性，我们就会在整个章节中保持这种用法以避免混淆。我们认为，“s/he”和“he or she”这样的结构很别扭，会分散注意力。不过，如果你发现自己被体育游戏的女性玩家或芭比娃娃游戏的男性设计师的想法所困扰，这也是好事。我们不认为游戏应该分为粉色的女性游戏和蓝色的男性游戏，作为一名设计师，你应该意识到你的游戏可以被任何人玩，无论男女。

As for ourselves—well, we describe ourselves as “we.” Andrew wrote some chapters and Ernest wrote others, and then we swapped them around and traded comments and suggestions. But we haven't identified who wrote what; we each take responsibility for the whole book.

至于我们自己，我们用“我们”来形容自己。安德鲁写了一些章节，欧内斯特写了另一些章节，然后我们互换章节并讨论意见和建议。但我们没有标注谁写了什么；我们每个人都对整本书负责。

Enjoy!

尽情享受吧！
