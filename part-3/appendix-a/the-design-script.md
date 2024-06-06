# The Design Script 设计脚本

This is the real McCoy—the document that officially, formally records your game's design. Whereas the high-concept document and the treatment are primarily sales tools, the script is primarily a development tool (although publishers often want to see a completed script before funding the next phase of a project). As we said in [Chapter 1](/part-1/chapter-1.md), it is a record of decisions made (and not yet made), a way of transmitting the design to the rest of the team, and a reference work for bringing new people up to speed as they join the team late in the development process.

这是真正的麦考伊——正式记录游戏设计的文件。高概念和综述文档主要是销售工具，而脚本则主要是开发工具（尽管发行商通常希望在资助项目的下一阶段之前看到已完成的脚本）。正如我们在[第一章](/part-1/chapter-1.md)中所说的，它是已做决定（和未做决定）的记录，是将设计传递给团队其他成员的一种方式，也是在开发过程后期让新加入团队的人员尽快了解情况的参考资料。

If you already have a design script, even a partial one, bring it along to the pitch meeting to show how far along you are. Although it's not intended as a sales tool, a producer will appreciate getting a look at a well-organized design script. The producer might also bring along a programmer as a technical advisor to the meeting, who will ask you questions about your development plans.

如果你已经有了设计脚本，哪怕是部分脚本，也可以带着它参加推介会，以显示你的进展情况。虽然这不是一个销售工具，但制作人会很高兴看到一个条理清晰的设计脚本。制作人可能还会带一名程序员作为技术顾问参加会议，他会向你询问有关开发计划的问题。

## How Big Should It Be? 它应该有多大？

In the earliest days of computer gaming, there were no design scripts. A programmer had an idea for a game and started coding it immediately. In a few weeks or months, it was done and that was that. The program code was all of the design document that there would ever be, but because games were very small and usually were built by one person, it didn't matter much.

在电脑游戏的早期，没有设计脚本。程序员有了一个游戏创意，就会立即开始编码。几周或几个月后，游戏就完成了。程序代码就是所有的设计文档，但由于当时的游戏非常小，通常由一个人制作，所以这并不重要。

As games and their development teams grew in size, people started to realize that they needed careful planning. Publishers began to insist that a game have an entirely comprehensive script before any programming or other work began. The script became the deliverable at the first milestone in the project. Design documents grew enormously, especially if the publisher was relying on an outside developer that it couldn't keep a close eye on. Scripts went from 50 to 100 to 200 pages in the early 1990s.

随着游戏及其开发团队规模的不断扩大，人们开始意识到他们需要精心策划。发行商开始坚持要求游戏在开始编程或其他工作之前必须有一个完整的脚本。脚本成为项目第一个里程碑的交付成果。设计文档大量增加，尤其是当发行商依赖于外部开发商而无法密切关注时。20 世纪 90 年代初，脚本从 50 页增加到 100 页再到 200 页。

Since then, scripts have shrunk somewhat and also have become fragmented. Instead of one single monster document, many development groups create smaller documents to cover particular areas of the game: character design, for example, or core mechanics. There are a couple of reasons for this. Now that many games are using licensed game engines, there's no need to document the functional characteristics of a 3D environment in excruciating detail—this material is provided for you in the engine. Second, the last 10 years has seen tremendous growth in the use of level-editing tools to create the game's missions or scenarios. It used to be that the progression of a game was hardwired into the code, so it was also documented extensively in the design script. Games have now become data-driven; that is, the software implements the AI, user interface, and core mechanics of the game, but the actual experience of playing each level—its appearance, challenges, and victory condition—are stored in data files created by the level editor. As a result, there's no need to define these things in advance in a design document. The script can focus on the elements that make up the game, and the level designers create the concrete challenge of playing it.

从那时起，脚本就开始有所缩减，也变得支离破碎。许多开发小组不再使用单一的怪物文档，而是创建更小的文档来涵盖游戏的特定领域：例如角色设计或核心机制。这有几个原因。现在许多游戏都使用授权游戏引擎，因此没有必要详细记录 3D 环境的功能特性，引擎会为你提供这些材料。其次，在过去的 10 年中，使用关卡编辑工具来创建游戏任务或场景的做法得到了极大的发展。过去，游戏的进程都是硬连入代码中的，因此在设计脚本中也有大量的记录。现在，游戏已经变成了数据驱动型游戏；也就是说，软件实现了游戏的人工智能、用户界面和核心机制，但每个关卡的实际游戏体验--其外观、挑战和胜利条件--都存储在关卡编辑器创建的数据文件中。因此，无需在设计文档中事先定义这些内容。脚本可以专注于构成游戏的元素，而关卡设计师则可以创造出游戏的具体挑战。

In short, there's no longer a clear rule about how many pages long a script should be. If a script is a part of a milestone deliverable, though, the fatter it is, the more likely it is that the publisher will think you've done your homework. A game that claims to offer 50 or 60 hours of gameplay and a vast number of characters, locations, weapons, and player options had better have more than 20 pages of documentation. Obviously, you shouldn't pad it out with fluff, but thoroughness is always appreciated by people who are expecting to invest a million dollars or more in a product.

简而言之，现在已经没有关于剧本篇幅的明确规定。不过，如果脚本是里程碑式交付成果的一部分，那么它越长，发行商就越有可能认为你已经做足了功课。一款游戏如果声称能提供 50 或 60 小时的游戏时间，以及大量的角色、地点、武器和玩家选项，那么它的文档最好超过 20 页。很明显，你不应该用花哨的东西来充数，但对于那些期望在产品上投资一百万美元或更多的人来说，详尽的资料总是值得赞赏的。

## The Design Web Site  设计网站

Unless you have a particular need for paper copies, you might consider writing not a document, but a design web site. The web site has many advantages. For one thing, multiple people can work on different parts of it at the same time. It's very easy and convenient to add material to in a nonlinear fashion. It's also easy to add pictures. Hyperlinks enables you to cross-reference one page with another.

除非你特别需要纸质副本，否则你可以考虑不编写文档，而是编写一个设计网站。网站有很多优点。首先，多人可以同时处理网站的不同部分。以非线性方式添加材料非常简单方便。添加图片也很容易。通过超链接，你可以将一个页面与另一个页面相互参照。

The disadvantage of a design web site is that it's difficult to take home and mark up with a pencil, and if your material is sensitive, you had better be darn sure that the site is secure. A Microsoft Word or Adobe Acrobat file can be protected and encrypted easily; a web site is vulnerable to being hacked if it's stored on a server available to the Internet.

设计网站的缺点是很难带回家用铅笔标注，如果你的资料比较敏感，你最好确保网站是安全的。Microsoft Word 或 Adobe Acrobat 文件可以很容易地进行保护和加密；而网站如果存储在互联网服务器上，就很容易被黑客攻击。

## Chris Taylor's Template 克里斯·泰勒的模板

A great many game design templates are available on the Internet, in varying degrees of detail. Rather than write yet another one of our own, we've chosen to refer you to a template from a famous game designer with a string of hits to his name. Chris Taylor was the man behind [Total Annihilation](https://en.wikipedia.org/wiki/Total_Annihilation), [Fallout Tactics](https://en.wikipedia.org/wiki/Fallout_Tactics:_Brotherhood_of_Steel), and [Dungeon Siege](https://en.wikipedia.org/wiki/Dungeon_Siege). We think that his template is the most comprehensive (and also the funniest) currently available. It's primarily intended for a large game in a big world, with many characters, weapons, monsters, and so on, so obviously much of it will be unnecessary if you're designing a 10-minute Java-based trivia game. However, you can ignore anything that you don't need.

互联网上有大量的游戏设计模板，其详细程度各不相同。与其自己再写一个，我们不如向你推荐一位名声显赫的著名游戏设计师的模板。克里斯·泰勒是[《横扫千军》](https://en.wikipedia.org/wiki/Total_Annihilation)、[《辐射战略版》](https://en.wikipedia.org/wiki/Fallout_Tactics:_Brotherhood_of_Steel)和[《地牢围攻》](https://en.wikipedia.org/wiki/Dungeon_Siege)的幕后功臣。我们认为他的模板是目前最全面的（也是最有趣的）。它主要是为一个大世界中的大型游戏而设计的，其中有许多角色、武器、怪物等等，因此如果你要设计一款基于 Java 的 10 分钟小游戏，显然其中的许多内容都是不必要的。不过，你可以忽略任何你不需要的东西。

Chris Taylor's template is too long to include here, and you wouldn't want to type it all in anyway. You can download a copy in Microsoft Word format at www.designersnotebook.com/ctaylordesign.zip.

克里斯·泰勒的模板太长了，这里就不一一列举了，反正你也不想全部打进去。你可以在 www.designersnotebook.com/ctaylordesign.zip 下载 Microsoft Word 格式的副本。
