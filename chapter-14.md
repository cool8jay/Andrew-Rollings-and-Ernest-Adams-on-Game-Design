Construction and management simulations are games about processes. The player's goal is not to defeat an enemy, but to build something within the context of an ongoing process. The better the player understands and controls the process, the more success he will have at building.

建设和管理模拟游戏是关于过程的游戏。玩家的目标不是打败敌人，而是在一个持续的过程中建造一些东西。玩家对过程的理解和控制越好，就越能在建造过程中取得成功。

The first really successful computerized construction and management simulation (which we refer to as a CMS from now on) was [SimCity](https://en.wikipedia.org/wiki/SimCity). We'll look at it in some detail later in the chapter. [SimCity](https://en.wikipedia.org/wiki/SimCity) proved that computer games don't need high-speed action or violence to be a success; it succeeded in part because it didn't have those things and appealed to a broad audience.

第一个真正成功的计算机化建设和管理模拟游戏（我们从现在开始称之为 CMS）是[《模拟城市》](https://en.wikipedia.org/wiki/SimCity)。我们将在本章稍后部分详细介绍它。[《模拟城市》](https://en.wikipedia.org/wiki/SimCity)证明，电脑游戏不需要高速动作或暴力就能获得成功；它之所以成功，部分原因在于它没有这些东西，而且吸引了广大的受众。

At the end of this chapter, we also have a section called "Pure Business Simulations," devoted to games in which the player doesn't really "construct" anything, and another section called "Hybrid Games," about games that are a hybrid of CMS and war games, such as [Age of Empires](https://en.wikipedia.org/wiki/Age_of_Empires). Military strategy is addressed in [Chapter 10](chapter-10.md), "Strategy Games," but some of these hybrid games include interesting economic elements as well; we'll refer to them throughout this chapter, where appropriate.

在本章末尾，我们还有一节名为“纯商业模拟”的内容，专门介绍玩家并不真正“构建”任何东西的游戏；另一节名为“混合游戏”，介绍 CMS 和战争游戏的混合体，如[《帝国时代》](https://en.wikipedia.org/wiki/Age_of_Empires)。军事战略在[第十章](chapter-10.md) “策略游戏”中论述，但其中一些混合游戏也包含有趣的经济元素；我们将在本章适当的地方提到它们。

# The Common Elements of CMSs CMS 游戏的共同要素

Most CMSs give the player the chance to build and manage some entity—a city, a building, an anthill, or whatever—using two general sets of tools: one for building and one for managing. Building is easy, but managing is tricky indeed; we discuss that aspect of the simulation first.

大多数 CMS 游戏都让玩家有机会使用两套通用工具来建造和管理某个实体——城市、建筑、蚁穴或其他，其中一套用于建造，另一套用于管理。建造很简单，但管理确实很棘手；我们将首先讨论模拟的这一方面。

## Rules 规则

The rules of a CMS define its internal economy and the ways in which the player can influence that economy. Creating and balancing an economy is one of the most complex and difficult jobs a game designer can do, and you can be sure that no matter how carefully you have worked it out, there will be consequences and relationships that you never considered. This is sometimes called emergent behavior, and whether it's desirable or not is up to you. Only playtesting and tuning will get the game right in the end.

CMS 的规则定义了其内部经济以及玩家影响经济的方式。创建和平衡经济是游戏设计者所能做的最复杂、最困难的工作之一，而且可以肯定的是，无论你如何精心设计，都会出现你从未考虑过的结果和关系。这种情况有时被称为“涌现行为”，至于它是否可取，则取决于你自己。只有进行游戏测试和调整，才能最终让游戏变得正确。

### Resources 资源

An economy is a system in which resources are produced, consumed, and exchanged. In many CMSs, the primary resource is money. The characteristics of the resources affect the way a game is played. For example, resources can be tangible, requiring storage space that must be constructed and paid for, or intangible, occupying no physical space and costing nothing to move from place to place. Money is usually treated as an intangible resource, but food and building materials are generally treated as tangible entities. There are occasional exceptions: [Dungeon Keeper](https://en.wikipedia.org/wiki/Dungeon_Keeper) (another hybrid game) treated gold as a tangible resource that had to be mined and transported back to a treasury, and the player had to expand the treasury when it got full.

经济是一个生产、消费和交换资源的系统。在许多 CMS 中，主要资源是货币。资源的特性会影响游戏的方式。例如，资源可以是有形的，需要储存空间，必须建造并支付费用；也可以是无形的，不占用物理空间，从一个地方移动到另一个地方不需要花费任何费用。金钱通常被视为无形资源，但食物和建筑材料通常被视为有形实体。偶尔也有例外：[《地下城守护者》](https://en.wikipedia.org/wiki/Dungeon_Keeper)（另一款混合型游戏）将黄金视为有形资源，必须开采并运回金库，当金库满了之后，玩家必须扩充金库。

A number of games treat resources in a mixed fashion, sometimes tangible and sometimes intangible. Both [Dungeon Keeper](https://en.wikipedia.org/wiki/Dungeon_Keeper) and [Age of Empires](https://en.wikipedia.org/wiki/Age_of_Empires) required that resources be transported from their production points to a storage facility; during this period, the resource was vulnerable to destruction or seizure by an enemy. However, in [Age of Empires](https://en.wikipedia.org/wiki/Age_of_Empires), when a resource was stored, it could not be seized or destroyed even if the enemy demolished the storage pit. In effect, resources became intangible when they were stored.

许多游戏以混合的方式处理资源，有时是有形的，有时是无形的。[《地下城守护者》](https://en.wikipedia.org/wiki/Dungeon_Keeper)和[《帝国时代》](https://en.wikipedia.org/wiki/Age_of_Empires)都要求将资源从生产点运送到储存设施；在此期间，资源很容易被敌人破坏或夺取。然而，在[《帝国时代》](https://en.wikipedia.org/wiki/Age_of_Empires)中，当资源被储存起来后，即使敌人拆毁了储存坑，也无法夺取或毁坏它。实际上，当资源被储存起来时，它们就变得无形了。

Similarly, most CMSs don't require a resource to be physically transported to be spent or consumed; the commodity simply vanishes from its warehouse. When constructing a building in [Age of Empires](https://en.wikipedia.org/wiki/Age_of_Empires), the player doesn't need to transport the stone from the storage pit to the construction site. This takes an extra management burden off the player.

同样，大多数 CMS 都不需要通过实际运输来消耗资源，它只需从仓库中消失即可。在[《帝国时代》](https://en.wikipedia.org/wiki/Age_of_Empires)中建造建筑时，玩家不需要把石头从储藏坑运到建筑工地。这为玩家减轻了额外的管理负担。

One game that treats all resources as tangible, including money, is [The Settlers](https://en.wikipedia.org/wiki/The_Settlers) from Blue Byte Software. In [The Settlers](https://en.wikipedia.org/wiki/The_Settlers), every kind of resource (and there are many) must be transported from where it is produced, either to storage areas or directly to places where it is consumed. Grain, for example, must be carried from the grain farm to the windmill for grinding, the flour must be carried from the windmill to the bakery, and the bread must be carried from the bakery to the mines, where the miners eat it.

Blue Byte Software 公司出品的[《工人物语》](https://en.wikipedia.org/wiki/The_Settlers)是一款将包括金钱在内的所有资源都视为有形资源的游戏。在[《工人物语》](https://en.wikipedia.org/wiki/The_Settlers)中，每一种资源（有很多）都必须从生产地运输到储存地或直接运到消费地。例如，谷物必须从谷物农场运到风车碾磨，面粉必须从风车运到面包房，面包必须从面包房运到矿井，然后矿工们在矿井里食用。

### Sources 来源

Every resource, intangible or tangible, must have one or more sources—that is, ways in which they come into the game. In [Monopoly](https://en.wikipedia.org/wiki/Monopoly_(game)), for example, money comes into the game from the bank. All the players start with a certain amount of money, and they get more each time they pass Go. They can also mortgage their properties for money, and they might get more money from the bank through the actions of the Chance and Community Chest cards.

每种资源，无论是无形的还是有形的，都必须有一个或多个来源，即它们进入游戏的方式。例如，在[《大富翁》](https://en.wikipedia.org/wiki/Monopoly_(game))中，钱是从银行进入游戏的。所有玩家一开始都有一定数量的钱，每次路过“Go”都会得到更多钱。他们还可以抵押自己的房产换取资金，并通过“机会”牌和“社区宝箱”卡片的行动从银行获得更多钱。

Unlike [Monopoly](https://en.wikipedia.org/wiki/Monopoly_(game)), which is turn-based, CMSs usually have a production rate for each resource. This production rate can be fixed or variable, and rates can be different at different sources—that is, some sources might produce the resource faster than others.

与回合制的[《大富翁》](https://en.wikipedia.org/wiki/Monopoly_(game))不同，CMS 通常为每种资源设定一个生产率。该生产率可以是固定的，也可以是可变的，而且不同来源的生产率可能不同——也就是说，有些来源的资源生产速度可能比其他来源快。

Finally, regardless of production rate, sources can be limited or unlimited. A particular source might contain a limited amount of a resource and might cease production when it is depleted. If the entire game contains only a limited amount (that is, all possible sources contain limited amounts), the game can be said to be closed-ended. The game must eventually end or fail when the essential resource is gone. On the other hand, if the amount of the resource is unlimited, the game is open-ended—it can continue indefinitely. Dungeon Keeper again provides examples of both. Gold mines in [Dungeon Keeper](https://en.wikipedia.org/wiki/Dungeon_Keeper) produced only a certain amount of gold. Because various activities consumed gold, eventually the dungeon must run out of money. Some dungeons, however, contained gem mines as well as gold mines (a misnomer because what they actually produced was also gold). The difference was that a gem mine could never be exhausted. It continued to produce gold indefinitely.

最后，无论生产率如何，来源可能是有限的，也可能是无限的。某一特定来源可能包含有限数量的资源，并可能在资源耗尽时停止生产。如果整个游戏只包含有限的资源（即所有可能的来源都包含有限的资源），那么这个游戏可以说是封闭式的。当基本资源耗尽时，游戏最终必须结束或失败。另一方面，如果资源的数量是无限的，游戏就是开放式的——可以无限期地进行下去。[《地下城守护者》](https://en.wikipedia.org/wiki/Dungeon_Keeper)再次提供了这两种情况的例子。[《地下城守护者》](https://en.wikipedia.org/wiki/Dungeon_Keeper)中的金矿只能生产一定数量的黄金。由于各种活动都会消耗黄金，地牢最终会耗尽金钱。不过，有些地下城既有金矿，也有宝石矿（取名有误，因为宝石矿实际生产的也是黄金）。不同的是，宝石矿永远不会枯竭。它可以无限期地生产黄金。

### Drains 消耗

A drain is an activity that consumes resources. The two most common drains in CMSs are construction, building or buying new things to serve some purpose, and maintenance, ongoing spending required to prevent loss or decay. Construction happens only when the player wants it. Maintenance can be player-controlled, but it is often an automatic function that occurs whether the player wants it to or not.

消耗是指消耗资源的活动。CMS 中最常见的两种消耗是建造和维护，前者是指建造或购买新的东西来达到某种目的，后者是指为防止资源流失或衰减而持续进行的支出。建造只有在玩家需要时才会发生。维护可以由玩家控制，但通常是一种自动功能，无论玩家是否愿意都会发生。

Because resources are valuable, the player wants to know why a resource is disappearing from the world and what she is "getting" to compensate for its loss. In [Monopoly](https://en.wikipedia.org/wiki/Monopoly_(game)), players get money from the bank by passing Go—in effect, for no reason at all—but whenever a player has to give money back to the bank, a reason is given: The player has been fined, has to pay certain expenses, and so on.

因为资源是有价值的，所以玩家想知道为什么某种资源会从世界上消失，以及她“得到”了什么来补偿资源的损失。在[《大富翁》](https://en.wikipedia.org/wiki/Monopoly_(game))游戏中，玩家路过“Go”就能从银行获得钱——实际上是毫无理由的——但每当玩家必须把钱还给银行时，都会给出一个理由：玩家被罚款了，必须支付一定费用，等等。

Maintenance seems like a sort of meaningless cost. It bothers some players, who would rather buy something once and never have to worry about it again. If you characterize it as a "rental" rather than a purchase, it makes more sense to them. Paying employees is a good example of a maintenance cost. You can't own employees; you can only pay their wages on an ongoing basis.

维护似乎是一种毫无意义的成本。这让一些玩家感到困扰，他们宁愿只买一次东西，然后再也不用担心了。如果把它说成是“租赁”而不是购买，对他们来说就更有意义了。支付员工工资就是维护成本的一个很好的例子。你不能拥有员工，只能持续支付他们的工资。

### Converters 转换器

A converter is a location or activity that turns one or more resources into another. In effect, it drains one resource while serving as the source for another at the same time. [The Settlers](https://en.wikipedia.org/wiki/The_Settlers) is full of converters (see Figure 14.1). The bakery, for example, turns flour and water into bread. The iron smelter takes iron ore and coal (or charcoal) and produces iron bars. In designing a converter, you must specify the input-to-output ratio between resources consumed and resources produced, as well as its production rate. For example, the windmill in [The Settlers](https://en.wikipedia.org/wiki/The_Settlers) converts grain into flour at a rate of one to one: One bag of grain produces one bag of flour; none is wasted. This takes 15 or 20 seconds to do. The iron smelter turns one load of ore into one iron bar, consuming one load of coal in the process. However, if it is using charcoal instead of coal, it requires three loads of charcoal for each iron bar because charcoal is less efficient than coal. (That's the given reason, anyway; the real game-design reason is that charcoal is an unlimited resource because it comes from wood, which is renewable, whereas coal has to be mined and eventually runs out. To discourage players from simply using charcoal for everything, the designers made it a less efficient mechanism.)

转换器是将一种或多种资源转化为另一种资源的地点或活动。实际上，它在消耗一种资源的同时，也是另一种资源的来源。[《工人物语》](https://en.wikipedia.org/wiki/The_Settlers)中有很多转换器（见图 14.1）。例如，面包店可以把面粉和水变成面包。炼铁厂利用铁矿石和煤（或木炭）生产铁条。在设计转换器时，你必须明确消耗的资源和生产的资源之间的投入产出比以及生产率。例如，[《工人物语》](https://en.wikipedia.org/wiki/The_Settlers)中的风车以一比一的比率将谷物转化为面粉：一袋谷物生产一袋面粉，没有任何浪费。这需要 15 或 20 秒的时间。炼铁厂将一批矿石转化为一根铁棒，在此过程中会消耗一块煤。但是，如果用木炭代替煤炭，每块铁条就需要三块木炭，因为木炭的效率比煤炭低。(这是给出的原因，真正的游戏设计原因是木炭是一种无限资源，因为它来自木材，而木材是可再生的，而煤炭必须开采，最终会枯竭。为了阻止玩家简单地使用木炭来做任何事情，设计者让木炭成为了一种效率较低的机制。）

Figure 14.1. The Settlers III. The iron smelter is in the center. The coal and iron ore mines are immediately below. 图 14.1. 《工人物语三》。中间是炼铁厂。下面是煤矿和铁矿。

graphics/14fig01.gif

### Deadlocks 死锁

A deadlock is a condition that occurs when you need a resource to construct a production mechanism to produce more of the same resource, or when two processes are each waiting for the other to complete. The chicken-and-egg problem is a classic deadlock. To use an example from a real game, in [The Settlers](https://en.wikipedia.org/wiki/The_Settlers), a player must have stone to build a stonecutter's hut, which then produces more stone. Ordinarily, the game starts with some stone already in storage, so if the player builds a stonecutter's hut right away, it will produce the stone needed for other activities. However, if the player uses up all her stored stone constructing other buildings, she might not have enough to build a stonecutter's hut, and she will be in a deadlock. Fortunately, [The Settlers](https://en.wikipedia.org/wiki/The_Settlers) gives players a way to break the deadlock: They can demolish another building and get back enough stone to build a stonecutter's hut after all.

当你需要一种资源来构建生产机制以生产更多相同资源时，或者当两个进程都在等待对方完成时，就会出现死锁。鸡和蛋的问题就是典型的死锁。举个真实游戏中的例子，在[《工人物语》](https://en.wikipedia.org/wiki/The_Settlers)中，玩家必须拥有石头才能建造石匠小屋，然后生产更多的石头。通常情况下，游戏开始时已经储存了一些石头，因此如果玩家立即建造一座石匠小屋，就能生产出其他活动所需的石头。但是，如果玩家在建造其他建筑时用完了所有储存的石头，那么她可能就没有足够的石头来建造石匠小屋了，这样她就会陷入死锁。幸运的是，[《工人物语》](https://en.wikipedia.org/wiki/The_Settlers)为玩家提供了打破僵局的方法：他们可以拆除另一栋建筑，取回足够的石料来建造石匠小屋。

In designing a CMS, you need to watch out for deadlocks, which can occur whenever there's a loop in the production process. To avoid deadlocks, either avoid such loops or provide an alternative source for one of the resources, even if its value is minimal. This is the point of collecting \\$200 when you pass Go in [Monopoly](https://en.wikipedia.org/wiki/Monopoly_(game)). If you have no properties, you can't earn money by collecting rent, but if you can't collect rent, you can't buy properties. [Monopoly](https://en.wikipedia.org/wiki/Monopoly_(game)) solves this by giving the players money to start with and by giving them \\$200 every time they pass Go. As the game progresses, that \\$200 becomes less significant, but it is enough to break a deadlock.

在设计 CMS 时，你需要注意死锁，因为只要生产流程出现循环，就会出现死锁。为了避免死锁，要么避免这种循环，要么为其中一种资源提供替代来源，即使它的价值很小。这就是[《大富翁》](https://en.wikipedia.org/wiki/Monopoly_(game))中路过“Go”时领取 200 美元的意义所在。如果你没有房产，你就不能通过收租赚钱，但如果你不能收租，你就不能买房。[《大富翁》](https://en.wikipedia.org/wiki/Monopoly_(game))解决这个问题的方法是，一开始就给玩家钱，每次路过“Go”时都给他们 200 美元。随着游戏的进行，这 200 美元的作用会越来越小，但也足以打破僵局。

### Static and Dynamic Equilibrium 静态和动态平衡

It's possible to design a system in such a way that, left alone, it returns to a state of equilibrium. Static equilibrium is a state in which everything remains constantly the same: Resources are flowing steadily around without any significant change anywhere. Dynamic equilibrium occurs when the system fluctuates through a cycle. It's constantly changing, but it eventually returns to a starting point and begins again.

可以设计一个系统，使其在没有外力干预的情况下自行回到平衡状态。静态平衡是一种所有事物都保持不变的状态：资源稳定流动，任何地方都没有显著变化。当系统在一个周期内波动时，就会出现动态平衡。它不断变化，但最终会回到起点并重新开始。

Here's an example of static equilibrium. Suppose you have a miller grinding wheat to make flour, and a baker baking bread from the flour. If the bakery consumes the flour at exactly the same rate at which the mill produces it, then the amount of flour in the world at any one time will remain static. If we then perturb the system by stopping the bakery for a while, the flour will build up. When the bakery restarts, the amount of flour available will be static at the new level. The system returns to equilibrium because the key factors—the production and consumption rates of the mill and the bakery—are the same (see Figure 14.2).

下面是一个静态平衡的例子。假设一个磨坊工人磨小麦做面粉，一个面包师用面粉烤面包。如果面包店消耗面粉的速度与磨坊生产面粉的速度完全相同，那么世界上任何时候的面粉量都将保持静态。如果我们暂时停止面包店，对系统进行扰动，面粉就会增加。当面包店重新开张时，面粉的供应量将保持在新的水平上。由于关键因素——面粉厂和面包店的生产率和消耗率——相同，系统恢复平衡（见图 14.2）。

Figure 14.2. An example of static equilibrium. 图 14.2. 静态平衡示例。

graphics/14fig02.gif

Now let's suppose that there's only one person who has to do both jobs herself. She mills for a while, then she bakes for a while, then she mills again, and so on. This is an example of dynamic equilibrium: Things are changing all the time, but they always return to the same state after a while because the process is cyclic. If we tell the woman to stop baking and only mill for a while, and then resume baking again later, again the flour builds up. When she resumes baking, the system settles into a new state of dynamic equilibrium (see Figure 14.3).

现在我们假设只有一个人需要同时做这两份工作。她先碾磨一会儿，然后烘烤一会儿，接着再碾磨，以此类推。这就是一个动态平衡的例子：事情一直在变化，但由于过程是循环往复的，所以一段时间后总会回到原来的状态。如果我们让这位妇女停止烘焙，只磨粉一段时间，然后再继续烘焙，那么面粉又会堆积起来。当她重新开始烘焙时，系统就会进入新的动态平衡状态（见图 14.3）。

Figure 14.3. A new state of dynamic equilibrium. 图 14.3. 动态平衡的新状态。

graphics/14fig03.gif

When a CMS settles into a static equilibrium, players can easily judge the effect of their actions on the system by making one small change and watching the results. This makes the game easy to learn and play. Dynamic equilibrium is more difficult for players to handle. With the system in constant flux, it's hard to tell whether what they're seeing is the result of a natural process or something they've done. We have a similar problem making ecological decisions about our planet. For many years, people believed that the environment should be in a state of static equilibrium: that there should always be exactly enough plants for the herbivores and exactly enough herbivores for the carnivores, and any deviation from this was caused by environmental mismanagement. More recently, we've come to realize that there are natural fluctuations in the sizes of animal populations and that big changes are not necessarily the result of human actions; they can occur in the ordinary course of events. This makes environmental management all the more difficult.

当 CMS 进入静态平衡后，玩家只需做出一个小小的改变并观察结果，就能轻松判断自己的行为对系统的影响。这使得游戏易学易玩。对于玩家来说，动态平衡则更难处理。由于系统在不断变化，玩家很难分清他们所看到的是自然过程还是他们所做的事情的结果。我们在对地球进行生态决策时也会遇到类似的问题。多年来，人们一直认为环境应该处于静态平衡状态：食草动物应该有足够的植物，食肉动物应该有足够的食草动物，任何偏离这种状态的行为都是环境管理不善造成的。最近，我们逐渐认识到，动物种群的数量存在自然波动，巨大的变化并不一定是人类行为的结果，它们可能在正常的事件过程中发生。这使得环境管理变得更加困难。

If your system does settle into a state of equilibrium, static or dynamic, it takes the pressure off the player to do anything. She can simply watch it go for a while and make adjustments when she feels like it. Some CMSs do work that way, but most give the player more of a challenge. Rather than settling into equilibrium, there is an imbalance somewhere. Entropy in the system causes it to "run down" unless the player takes action to keep it going. To use our milling/baking metaphor, perhaps the player has to personally keep the mill supplied with wheat. If the player doesn't keep an eye on the wheat supply, both milling and baking come to a halt.

如果你的系统确实进入了静态或动态的平衡状态，那么玩家就没有任何压力去做任何事情了。她只需静观其变，并在自己喜欢的时候做出调整。有些 CMS 的确是这样，但大多数 CMS 给玩家带来的挑战更大。系统并没有达到平衡，而是在某个地方出现了失衡。系统中的熵会导致系统“衰竭”，除非玩家采取行动使其继续运转。用我们的“磨粉/烘焙”来比喻，也许玩家必须亲自维持磨坊的小麦供应。如果玩家不注意小麦的供应，磨粉和烘焙都会停止。

Whether your system settles into equilibrium or runs down without player action, one thing is certain: The player should always have to do something to obtain growth—he should have to press on the gas pedal of your game, as it were. If the system can grow of its own accord, there's no reason for the player to interfere. This is the player's essential challenge: figuring out how to produce growth using the many levers and knobs that you have given him. In effect, the player is himself an element of the simulation, and growth should be dependent on his active participation.

无论你的系统是进入了平衡状态，还是在没有玩家行动的情况下衰退，有一点是肯定的：玩家总是必须做些什么才能获得增长——他必须踩下游戏的油门。如果系统能够自行成长，玩家就没有理由进行干预。这就是玩家面临的基本挑战：如何利用你给他的许多杠杆和旋钮来实现增长。实际上，玩家本身就是模拟系统中的一个元素，系统的成长应该取决于玩家的积极参与。

### Disasters 灾难

Random disasters are another way to force the player to act. [SimCity](https://en.wikipedia.org/wiki/SimCity) tends to settle into a very slow decline if left alone, chiefly because the roads become worn out. To put more pressure on the player, fires, tornadoes and monster invasions crop up periodically, doing considerable damage. If the player does not take action to repair the damage, the city eventually dwindles down to nothing as a result of repeated disasters.

随机灾难是迫使玩家采取行动的另一种方式。如果任其发展，[《模拟城市》](https://en.wikipedia.org/wiki/SimCity)往往会缓慢衰退，这主要是因为道路变得破旧不堪。为了给玩家带来更大的压力，火灾、龙卷风和怪物入侵会定期出现，造成相当大的破坏。如果玩家不采取行动修复破坏，城市最终会在反复的灾难中逐渐衰败。

> **Case Study: Sim City 案例研究：《模拟城市》**
> 
> Although it isn't the oldest CMS, the spiritual father of them all is [SimCity](https://en.wikipedia.org/wiki/SimCity), published by Maxis (now a part of Electronic Arts). [SimCity](https://en.wikipedia.org/wiki/SimCity_(1989_video_game)) was originally designed for the Commodore 64, although it was most successful on the IBM PC, and the first version of the game is now playable for free on the Web. (Visit [http://simcity.ea.com/play/simcity_classic.php](http://simcity.ea.com/play/simcity_classic.php) if you're interested.) It was followed by a host of other games in the same mold: [SimAnt](https://en.wikipedia.org/wiki/SimAnt), [SimTower](https://en.wikipedia.org/wiki/SimTower), [SimFarm](https://en.wikipedia.org/wiki/SimFarm), and so on, which met with varying success.\
> 
> 虽然它不是最古老的 CMS，但所有这类游戏的的精神之父是 Maxis（现在是 Electronic Arts 的一部分）发行的[《模拟城市》](https://en.wikipedia.org/wiki/SimCity)。[《模拟城市》](https://en.wikipedia.org/wiki/SimCity_(1989_video_game))最初是为 Commodore 64 设计的，但它在 IBM PC 上的表现最为成功。(如果你有兴趣，请访问 [http://simcity.ea.com/play/simcity_classic.php](http://simcity.ea.com/play/simcity_classic.php)。）之后又推出了大量同类游戏：[《模拟蚂蚁》](https://en.wikipedia.org/wiki/SimAnt)、[《模拟大楼》](https://en.wikipedia.org/wiki/SimTower)、[《模拟农场》](https://en.wikipedia.org/wiki/SimFarm)等等，它们取得的成功各不相同。
> 
> The object of [SimCity](https://en.wikipedia.org/wiki/SimCity) is to build a city and attract people (called sims) to live and work there. The basic economic unit is money, which the player can spend in various ways to improve the city. The player's primary job is to zone tracts of land into one of three types: residential, commercial, or industrial. As people move into the city, these areas begin to be occupied and to produce tax revenue, thereby replenishing the city's coffers. This produces a straightforward positive feedback loop: Zoning costs money, but occupied zones produce more money, thereby enabling the player to do more zoning.\
> 
> [《模拟城市》](https://en.wikipedia.org/wiki/SimCity)的目标是建造一座城市，吸引人们（称为模拟人）到那里生活和工作。基本经济单位是金钱，玩家可以通过各种方式使用金钱来改善城市。玩家的主要工作是将土地划分为三种类型：住宅、商业或工业。随着人们迁入城市，这些区域开始被占用并产生税收，从而补充城市的国库。这就产生了一个直接的正反馈循环：分区需要花费资金，但被占用的区域会产生更多的资金，从而使玩家能够进行更多的分区。
> 
> The positive feedback is kept in check by other demands on the city's purse. Sims will not move into any zoned region; it has to have other benefits as well. Every zoned region requires electricity, and the player has to buy power plants and electrical lines to provide it. The sims also need a way to travel from the residential to the industrial zones to work and to the commercial zones to shop. This requires a road and a rail network, which also cost money. If the roads are inadequate to meet the traffic, or if the sims have to travel too far to work, they will begin to move out of the city, with a resulting loss of tax revenue. Finally, when the city reaches certain population thresholds, the sims begin to demand expensive amenities: a sports stadium, an airport, and so on. Again, if these are not provided, the sims begin to leave.\
> 
> 对城市资金的其他需求抑制了正反馈。模拟市民不会迁入任何一个分区，因为它还必须有其他好处。每个分区都需要电力，玩家必须购买发电厂和电线来提供电力。模拟市民还需要从住宅区前往工业区工作，以及前往商业区购物。这就需要公路和铁路网络，这也需要花钱。如果道路不能满足交通需求，或者模拟市民上班的路程太远，他们就会开始迁出城市，从而造成税收损失。最后，当城市人口达到一定的临界值时，模拟人开始要求提供昂贵的设施：体育场、机场等。同样，如果不提供这些设施，模拟人就会开始离开。
> 
> In addition to the electricity, roads, and civic amenities, there are other cost centers. Fires break out from time to time; if left unchecked, they destroy the buildings and leave the land unzoned. To combat this, the player has to build and maintain fire stations. Industrial areas are a source of crime, which depresses property values and reduces tax revenues. Crime can be suppressed by building police stations, at yet more cost. Industrial areas and roads also cause air pollution, which further depresses the value of nearby residential property. There is no way to reduce air pollution; you simply have to keep industrial and residential areas separate.\
> 
> 除了电力、道路和市政设施，还有其他成本中心。火灾时有发生；如果任其发展，不仅会毁坏建筑，还会使土地失去用途。为此，玩家需要建造和维护消防站。工业区是犯罪的源头，会降低财产价值，减少税收。可以通过建造警察局来遏制犯罪，但成本更高。工业区和道路还会造成空气污染，进一步降低附近住宅的价值。没有办法减少空气污染，只能将工业区和住宅区分开。
> 
> The vital calculations in the game are the ones that determine whether people move into the city or move out, and how valuable a given zone is. The more valuable a zone is, the higher its population density becomes and the more tax revenues it produces. The player can build parks and situate residential zones near woods and rivers to increase their attractiveness.\
> 
> 游戏中的关键计算是决定人们是否迁入城市或迁出，以及某个区域的价值有多大。一个区域的价值越高，人口密度就越大，税收也就越多。玩家可以在森林和河流附近建造公园和住宅区，以增加其吸引力。
> 
> Although [SimCity](https://en.wikipedia.org/wiki/SimCity) is now an old game, it serves as an excellent model to study (see Figure 14.4). Because it was designed for low-performance machines, it couldn't be too complex, and its internal economy is reasonably easy to understand.\
> 
> 虽然[《模拟城市》](https://en.wikipedia.org/wiki/SimCity)已经是一款老游戏，但它仍然是一个很好的研究模型（见图 14.4）。因为它是为低性能机器设计的，所以不会太复杂，其内部经济也相当容易理解。
> 
> Figure 14.4. The original Sim City, showing industrial, commercial, and residential zones. 图 14.4. 最初的《模拟城市》，显示了工业区、商业区和住宅区。
> 
> graphics/14fig04.jpg

## Setting 设定

It's easy enough to say that CMSs are about a process, but the process has to be meaningfully displayed on a computer screen, and it must fire the player's imagination. Most CMSs take place in the context of a physical space, usually a two-dimensional world in which buildings or other objects can be constructed. Caesar is about building an ancient Roman town, so the setting is a landscape near a river. [Civilization](https://en.wikipedia.org/wiki/Civilization_(series)) is about exploring a world while at the same time advancing a civilization both culturally and technologically, so its setting is an entire continent, or several of them.

说 CMS 是关于一个过程很容易，但这个过程必须在电脑屏幕上有意义地显示出来，而且必须激发玩家的想象力。大多数 CMS 都发生在一个物理空间中，通常是一个可以建造建筑物或其他物体的二维世界。《凯撒》讲述的是建造一座古罗马城镇的故事，因此游戏背景是河流附近的风景。[《文明》](https://en.wikipedia.org/wiki/Civilization_(series))的主题是探索一个世界，同时在文化和技术上推动一个文明的发展，因此它的背景是整个大陆或几个大陆。

A few pure business simulations don't take place in a physical setting, and they're discussed at the end of the chapter.

有几款纯商业模拟游戏不在物理环境中进行，本章最后将讨论它们。

## Gameplay 游戏性

The challenges in a CMS are largely economic. The player must understand how the internal economy of the game works and how to manipulate it to produce economic growth. Growth provides the resources required for the construction that is usually the overall goal of the game.

CMS 中的挑战主要是经济方面的。玩家必须了解游戏的内部经济是如何运作的，以及如何操纵它来实现经济增长。经济增长为建设提供所需资源，而建设通常是游戏的总体目标。

### Indirect Control 间接控制

A war game is a game of direct control. The players tell their troops exactly where to go and what to do, and they do it. The simulated soldiers have little or no autonomous behavior or artificial intelligence. If told to stand and wait someplace, they'll wait there forever.

战争游戏是一种直接控制游戏。玩家告诉他们的部队去哪里、做什么，他们就照办。模拟士兵几乎没有自主行为或人工智能。如果让他们站在某个地方等待，他们就会永远等在那里。

The majority of CMSs, on the other hand, are games of indirect control. The game simulates a process, and the player can alter that process only in limited ways. The process must be manipulated indirectly, and the player has to learn how the controls affect its inner workings. If there are simulated individuals in the game (see the "Simulating Individuals" section later in this chapter), for the most part, they can be controlled only indirectly. They have a behavior model that governs what they do, and it responds to stimuli, but they can't be given direct orders.

另一方面，大多数 CMS 是间接控制游戏。游戏模拟一个过程，而玩家只能以有限的方式改变这个过程。这个过程必须通过间接的方式来操纵，玩家必须了解控制是如何影响其内部运作的。如果游戏中存在模拟的个体（请参阅本章后面的“模拟个体”部分），在大多数情况下，他们也只能被间接控制。他们有一个行为模型来控制自己的行为，并对刺激做出反应，但不能直接向他们下达命令。

However, the dividing line between direct and indirect control is a fuzzy one. Certain player activities, such as choosing the location of new construction, will be direct. Others, such as trying to boost sales by reducing prices, will be indirect. Reducing prices is direct, but the (hoped for) consequent rise in sales is indirect.

然而，直接控制和间接控制之间的界限并不明显。某些玩家活动，如选择新建筑的地点，是直接控制。其他活动，如试图通过降价来提高销售额，则是间接的。降价是直接的，但（希望的）随之而来的销售额增长是间接的。

### Construction 建造

Construction itself isn't the challenge in a CMS; the challenge is in obtaining the resources needed for the construction. Construction is the part of the game that lets the player exercise her imagination and create something unique and personal. Accordingly, you, as the designer, need to find a way to make this easy and enjoyable.

在 CMS 中，建造本身并不是挑战，挑战在于获得建造所需的资源。在游戏中，“建造”是让玩家发挥想象力、创造独特个性的部分。因此，作为设计者，你需要想办法让玩家轻松愉快地完成这项工作。

Construction mechanisms in CMSs tend to be one of two types: buy or design-and-build. When the player buys an object (a segment of wall, say), the resources to build it are deducted from stockpiles, and the object immediately appears in a designated location. This lets her build rapidly, adding pieces like using Lego bricks. You should use this mechanism if construction is the primary activity in your game. If so, it needs to be easy and continuous, not something the player has to wait for. This is how Sim City worked: Zoning property and constructing civic amenities such as police stations and airports happened instantly because it was the primary activity in the game.

CMS 中的建造机制通常有两种：购买或设计，然后建造。当玩家购买一件物品（例如一段墙壁）时，用于建造它的资源就会从库存中扣除，物品会立即出现在指定位置。这样，玩家就可以像使用乐高积木一样，快速添加建筑材料。如果建造是游戏中的主要活动，就应该使用这种机制。如果是这样，它就需要简单且连续，而不是让玩家等待。《模拟城市》就是这样运作的：因为这是游戏中的主要活动，所以房产分区和警察局、机场等市政设施的建造都是瞬间发生的。

The design-and-build mechanism is more often seen in games in which the player does a little construction, then some management, then more construction, and so on. In design-and-build, the player marks out an area where new construction will appear. The game often displays the new building in a ghostly, semitransparent form to indicate that it is under construction. However, it takes time to build. If the game includes simulated people, you might be able to see them at work on it; if those people go away or die for some reason, the building might be left in a partially completed state.

设计-建造机制更多出现在游戏中，玩家在游戏中先进行少量建造，然后进行一些管理，接着进行更多建造，如此循环。在“设计-建造”游戏中，玩家会划出一个区域，在那里会出现新的建筑。游戏通常会以幽灵般的半透明形式显示新建筑，以表明它正在建造中。不过，建造过程需要时间。如果游戏中有模拟人，你可能会看到他们正在施工；如果这些人因某种原因离开或死亡，建筑物可能会处于部分完工的状态。

In design-and-build, you don't have to remove all the required resources from storage at once because the construction takes place over time. In The Settlers, wood and stone had to be physically transported a little at a time from stockpiles to the construction site. This puts an extra burden on the player to manage his resource flow, but it does give him more control. In contrast, [Age of Empires](https://en.wikipedia.org/wiki/Age_of_Empires) deducted the resources necessary for construction immediately when it was designed. They drained out of the game rather than being transported to the site. Although this was unrealistic, it meant that the player could build something only after he definitely had enough resources for it, and he didn't have to worry about moving things around all the time.

在“设计-建造”游戏中，你不必一次性从仓库中取出所有需要的资源，因为建造是随着时间的推移而进行的。而在《工人物语》中，木材和石材必须每次从仓库中一点点运到建筑工地。这给玩家带来了管理资源流的额外负担，但也给了玩家更多的控制权。相比之下，[《帝国时代》](https://en.wikipedia.org/wiki/Age_of_Empires)在设计时就会立即扣除建造所需的资源。它们从游戏中流出，而不是被运到工地。虽然这不现实，但这意味着玩家只有在确定有足够的资源后才能建造东西，而不必担心一直搬来搬去。

[Dungeon Keeper](https://en.wikipedia.org/wiki/Dungeon_Keeper) was particularly interesting because construction was actually excavation: It took place underground, and the player couldn't see the area he was excavating into. Excavations often led into immovable rock or to existing caves, underground rivers, or pools of lava. It was also irreversible: When an area had been excavated, there was no way to close it up again. This encouraged players to be cautious. Suddenly excavating into an area full of enemy creatures was a major hazard of the game.

[《地下城守护者》](https://en.wikipedia.org/wiki/Dungeon_Keeper) 特别有趣，因为它实际上是一种挖掘工程：挖掘是在地下进行的，玩家看不到挖掘的区域。挖掘通常会进入不可移动的岩石或已有洞穴、地下河流或熔岩池。挖掘也是不可逆的：当一个区域被挖掘出来后，就无法再将其封闭。这促使玩家谨慎行事。突然挖掘到一个充满敌方生物的区域是游戏的一大危险。

### Demolition 拆除

In addition to letting your players construct things, you might need to give them a way to demolish things. A big part of the fun of a CMS is building your city, theme park, or whatever the way you want to build it. If a construction decision is irreversible, it means whatever the player is building can get only bigger, never smaller, and the player cannot change his mind or react to new circumstances. This might be okay for strategy games (many war games, for example, allow you to build factories and defenses but not demolish them), but in CMSs, it prevents the player from exercising his full creative freedom; hence, the need for a demolition feature.

除了让玩家建造东西，你可能还需要给他们一种拆除东西的方法。CMS 的一大乐趣就是按照自己的意愿建造城市、主题公园或其他任何东西。如果建造决定是不可逆的，这就意味着玩家正在建造的东西只能变大，不能变小，而且玩家不能改变主意或对新情况做出反应。这对于策略游戏来说也许没什么问题（例如，许多战争游戏允许玩家建造工厂和防御设施，但却不允许拆除它们），但在 CMS 中，这就会妨碍玩家充分发挥其创造性自由；因此，就需要拆除功能。

You should consider whether you want demolition to cost something, cost nothing, or actually earn money. If it costs money to demolish something, you are, in effect, penalizing the player for changing his mind and perhaps encouraging him to plan more carefully in the future. He has lost not only his initial construction cost for the item, but the demolition costs as well. If it costs nothing, the player has lost only his construction costs. If he actually gets something back, it's usually called "selling" the item rather than demolishing it, and it further reduces the price the player pays for changing his mind. If he can sell it back for exactly as much as he paid, there is no net cost at all for building a thing and destroying it later. This is rare in CMSs because it removes some of the challenge. Players can build madly, secure in the knowledge that they can always get their money back by selling.

你应该考虑一下，你是希望拆除需要花钱，还是不花钱，抑或是真的能赚钱。如果拆卸物品需要花钱，那么实际上你是在惩罚玩家改变主意，也许是在鼓励他今后更谨慎地计划。他不仅损失了物品的初始建造成本，还损失了拆除费用。如果不花一分钱，玩家损失的只是建造成本。如果他真的拿回了一些东西，这通常被称为“出售”物品，而不是拆除物品，这也进一步降低了玩家因改变主意而付出的代价。如果他能以与付出相同的价格将物品卖出，那么建造一件物品并在之后将其销毁就完全没有净成本了。这在内容管理系统中并不多见，因为它消除了一些挑战。玩家可以疯狂地建造，因为他们知道卖掉总能把钱赚回来。

A player must never be able to sell an item back to the computer for more than he paid for it, unless he has expended further resources to upgrade it somehow. If the players can buy from and sell to the computer at will, and there exists any mechanism by which they can sell something for more than they paid for it, they will exploit this ruthlessly, piling up huge fortunes by endlessly buying and reselling and ignoring the rest of the game. There are various ways to prevent this. One is to make sure that it is simply impossible to make a profit; all sales must be for less than the original purchase price. If you want players to be able to make a limited profit, you have to place limits on the amount of buying and selling they can do. The computer can refuse to sell items to them after a while or can refuse to buy them back. The computer itself can have a limited amount of money and be unable to buy if it has run out. And in a multi-player game, you can let players buy and sell at a profit to one another, but not to the computer itself. Transactions among the players don't change the total amount of money in the game; it's selling things back to the computer that have the potential for abuse.

除非玩家花费了更多的资源对物品进行升级，否则绝不能以高于其支付的价格将物品卖回给电脑。如果玩家可以随意向电脑购买和出售物品，而且存在任何机制可以让他们以高于其支付的价格出售物品，那么他们就会无情地利用这一点，通过无休止地购买和转售来积累巨额财富，而忽略游戏的其他部分。防止这种情况的方法有很多。一种是确保玩家根本无法获利；所有销售都必须低于原始购买价格。如果想让玩家获得有限的利润，就必须限制他们的买卖量。电脑可以在一段时间后拒绝向玩家出售物品，也可以拒绝回购。电脑本身的资金也可能是有限的，如果用完了就无法购买。在多人游戏中，可以让玩家互相买卖并获利，但不能让他们从电脑身上获利。玩家之间的交易并不会改变游戏中的资金总额，而把东西卖回给电脑才有可能被滥用。

### Victory Conditions 胜利条件

A good many CMSs have no victory condition; the player simply builds whatever she likes as effectively as she can within the constraints of the system. These games might well have a loss condition, however: total depletion of resources (or, in monetary terms, bankruptcy). This is the loss condition in Monopoly, for example. Victory in Monopoly consists simply of bankrupting all the other players.

很多 CMS 都没有胜利条件；玩家只需在系统限制范围内尽可能有效地建造自己喜欢的东西。不过，这些游戏很可能有一个失败条件：资源完全耗尽（或者用货币术语来说，破产）。例如，这就是《大富翁》中的失败条件。在《大富翁》中，胜利仅仅是让所有其他玩家破产。

If you do want to define a victory condition, it's best to do it in the context of a scenario of some kind. Give the player a partially constructed city (or whatever) and a set of initial conditions, and then define the victory condition as achieving some other condition. It could be as simple as, "To win, your enterprise must be worth $5 billion," but it can be as complex as you like. You can also start the player in rapidly deteriorating conditions and challenge her to turn them around or simply to survive for a certain length of time.

如果你确实想定义一个胜利条件，最好是在某种场景下进行。给玩家一个部分建成的城市（或其他）和一组初始条件，然后将胜利条件定义为达到其他条件。可以简单到“要想获胜，你的企业必须价值 50 亿美元”，但也可以非常复杂。你也可以让玩家在迅速恶化的条件下开始游戏，并挑战她扭转局面或仅仅生存一定的时间。

### Competition Modes 竞争模式

CMSs are almost always single-player games. It's possible to make them two-player or even multi-player, but it's not a natural way to play. CMSs encourage planning and thought, not frantic action. If the players are competing for the same resources, it becomes a race to see who can grab the most, ignoring the other aspects of the game. If the players are separate and have symmetric starting and victory conditions, the game tends to be about optimizing efficiency. If the conditions are asymmetric, the game will be difficult to balance.

CMS 几乎都是单人游戏。双人甚至多人游戏也是可能的，但这并不是一种自然的游戏方式。CMS 鼓励计划和思考，而不是疯热的行动。如果玩家们都在争夺相同的资源，那么游戏就会变成一场看谁能抢到最多资源的竞赛，而忽略了游戏的其他方面。如果玩家是分开的，并且有对称的开始和胜利条件，那么游戏就会倾向于优化效率。如果条件不对称，游戏就难以平衡。

CMSs let the player be playful, to build and experiment in the world you've given him. That's seldom consistent with competition. One major exception is in hybrid games, those that have a military element as well as construction and management elements. They're discussed in the "Hybrid Games" section later in this chapter.

CMS 能让玩家尽情玩耍，在你给他的世界里建造和实验。这很少与竞争相关联。混合型游戏是一个主要的例外，这类游戏既有军事元素，也有建造和管理元素。本章后面的“混合游戏”部分将对其进行讨论。

## The Player's Role 玩家的角色

When designing any game, the first question you have to ask yourself is, what is the player going to do? The answer to this question usually arises out of a clear statement of the player's role in the game: pilot, general, adventurer, irradiated hedgehog, and so on. In a CMS, however, it's less easy to define the player's role because it seldom corresponds to an actual job in real life. The mayor of a city doesn't really lay out its streets or make zoning decisions personally.

在设计任何游戏时，你必须问自己的第一个问题是：玩家要做什么？要回答这个问题，通常需要明确说明玩家在游戏中的角色：飞行员、将军、冒险家、辐照刺猬等等。然而，在 CMS 中，玩家角色的定义就不那么容易了，因为它很少与现实生活中的实际工作相对应。一个城市的市长并不会亲自规划街道或做出分区决定。

This is one of the few genres in which we don't think you have to define the player's role in familiar terms. You still have to concern yourself with what the player is going to do, of course, but it doesn't matter that much what you call him.

我们认为，这是为数不多的不需要用我们熟悉的术语来定义玩家角色的游戏类型之一。当然，你仍然需要考虑玩家要做什么，但叫他什么并不重要。

### Interaction Model 交互模型

The player is almost always omniscient in a CMS because she needs to see what is happening all over the game world. It's difficult to control a global process from a local perspective. Most CMSs don't give the player any kind of avatar. Those that do usually make it temporary. If the player is building a city or a space station or some other structure, she could well want to see what it would look like from the perspective of someone inside it. For example, in [Dungeon Keeper](https://en.wikipedia.org/wiki/Dungeon_Keeper), it is possible for the player to "possess" a creature in her dungeon: to take control of that creature and walk around the dungeon in the first-person perspective (see Figure 14.5), seeing through its eyes. However, this feature is mostly cosmetic. It is occasionally useful in the military aspects of the game, but not at all in the management aspects. In short, we think the "down inside" view is a fun one and the player will enjoy it, but the primary interaction model in a CMS needs to be omnipresent.

在 CMS 中，玩家几乎总是无所不知的，因为她需要看到游戏世界中发生的一切。从局部视角控制全局进程是很困难的。大多数内容管理系统都不会给玩家提供任何化身。那些提供化身的系统通常都是临时性的。如果玩家正在建造一座城市、一个空间站或其他建筑，她很可能会想看看从里面的人的角度看会是什么样子。例如，在 [《地下城守护者》](https://en.wikipedia.org/wiki/Dungeon_Keeper)中，玩家可以“附身”地牢中的生物：控制该生物，以第一人称视角在地牢中走动（见图 14.5），通过它的眼睛来观察。不过，这一功能主要是装饰性的。它在游戏的军事方面偶尔有用，但在管理方面却完全没用。总之，我们认为“从内部”视角很有趣，玩家也会喜欢，但内容管理系统中的主要交互模式必须无所不在。

Figure 14.5. Dungeon Keeper 2, omnipresent view (top) and inside view (bottom). 图 14.5. 《地下城守护者 2》，全方位视图（上）和内部视图（下）。

graphics/14fig05.gif

## User Interface 用户界面

Because CMSs aren't trying to create an illusion of reality in the way that first-person shooters or flight simulators are, their user interfaces can be more "computerlike," using pull-down menus and rows of buttons along the edges of the screen. In a CMS, the emphasis is more on convenience than verisimilitude.

由于 CMS 并不像第一人称射击游戏或飞行模拟器那样试图营造真实的幻觉，因此其用户界面可能更像“电脑”，使用下拉菜单和屏幕边缘的一排按钮。在 CMS 中，强调的是方便性而不是真实性。

### Perspective 视角

The user's perspective in a CMS naturally depends on what's being simulated. Most CMSs simulate a process taking place over a land area—whether it's a city, a farm, or an entire planet. As a result, they tend to use an isometric perspective and enable you to view the world from one of four angles. The isometric perspective requires little CPU time, an advantage even in these days of 3D hardware accelerators, because CMSs do a lot more computation behind the scenes than other kinds of games. Its disadvantage, at least from a development standpoint, is that your art team will have to draw sprites of everything in the game from four different perspectives—and still more if you offer multiple zoom levels. It also doesn't let the player zoom in to any degree he likes. CMSs are sometimes frustrating in that the closest-in zoom level is a little too close, and the next one out is a little too far out.

用户在 CMS 中的视角自然取决于模拟的内容。大多数 CMS 模拟的是在陆地上发生的过程——无论是城市、农场还是整个星球。因此，它们倾向于使用等距视角，让你可以从四个角度之一来观察世界。等距视角只需要很少的 CPU 时间，即使在 3D 硬件加速的今天也是一个优势，因为 CMS 在幕后要比其他类型的游戏进行更多的计算。它的缺点是，至少从开发的角度来看，美术团队必须从四个不同的角度为游戏中的所有内容绘制精灵图，如果提供多种缩放级别，则绘制的精灵图数量会更多。此外，它还不能让玩家随意放大。CMS 有时会让人感到沮丧，因为最靠近的缩放级别有点太近，而下一个缩放级别又有点太远。

If your game simulates a process taking place in a three-dimensional space, you might find it useful to divide the space into layers (either physical or conceptual) to make it easier for the player to navigate around and view. It's also helpful to provide a button that returns the camera instantly to a default perspective so that the player can reorient himself if he gets lost.

如果你的游戏模拟的是一个在三维空间中发生的过程，你可能会发现将空间划分为不同的层次（物理层次或概念层次）是非常有用的，这样可以让玩家更容易浏览和查看。此外，提供一个按钮让摄像机立即返回到默认视角也很有帮助，这样玩家在迷失方向时就可以重新定位。

### Analysis Tools 分析工具

In a CMS, the player is trying to understand and control a mathematical model. To do this, she needs convenient access to key variables within the model. You should display the most important scalar (single-value) variables—for example, the amount of money she has to work with at the moment—on the screen at all times. The display can be in digits, if that's most appropriate, or a bar graph or some other kind of monitoring device, depending on the nature of the simulation.

在 CMS 中，玩家试图理解和控制一个数学模型。为此，她需要方便地访问模型中的关键变量。你应该随时在屏幕上显示最重要的标量（单值）变量——例如，她目前可以使用的资金数额。如果最合适的话，可以用数字显示，也可以用条形图或其他监测设备显示，这取决于模拟的性质。

Often the player needs to know not only the current value of a variable, but also how that variable has changed over time. This lets her track trends and respond to them before trouble occurs. In [Theme Park](https://en.wikipedia.org/wiki/Theme_Park_(video_game)), a business simulation about building and managing (surprise!) theme parks, visitors came in, spent a while in the park, and left again. The player could see them wandering around, but it was difficult to get a sense of the park's popularity just by counting heads. One of the information pop-ups available was a graph that showed how the population had changed over the past 1, 3, or 12 game years.

通常情况下，玩家不仅需要知道变量的当前值，还需要知道该变量随时间的变化情况。这可以让她跟踪趋势，并在问题发生之前做出反应。在[《主题公园》](https://en.wikipedia.org/wiki/Theme_Park_(video_game))这一有关主题公园建设和管理（令人吃惊！）的商业模拟游戏中，游客来到公园，在公园里待上一段时间，然后又离开。玩家可以看到他们四处游荡，但很难通过数人头来了解公园的受欢迎程度。弹出的信息之一是一张图表，显示过去 1、3 或 12 游戏年的人口变化情况。

With vector (multivalued) variables, you'll need a different approach. In Caesar, for example, every area of the Roman town that the player was trying to build needed a water supply of some sort. The amount of water available was therefore a vector; it had a separate value for each square on the grid. There were a variety of types of water supplies (wells, pipes, fountains, and so on), and each provided water to a given area around it. In the game's default perspective, showing all the buildings of the town, the player could see the structure supplying the water, but it was difficult for her to visualize exactly how far its coverage extended. To get a clearer picture, she could bring up a different view that hid most of the buildings and instead showed only the amount of water available in each area. The different values were indicated as squares in different shades of blue, from light blue, indicating very little water, to dark blue, indicating plenty. If an area had no water supply, there was no blue at all. The water supply buildings themselves were left visible on the map as landmarks.

对于矢量（多值）变量，你 需要采用不同的方法。例如，在《凯撒》中，玩家试图建造的罗马城镇的每个区域都需要某种形式的供水。因此，可用水量是一个矢量；网格上的每个方格都有一个单独的值。水源有多种类型（水井、水管、喷泉等），每种类型都能为其周围的特定区域供水。在游戏的默认视角下，玩家可以看到城镇的所有建筑，也可以看到供水结构，但很难想象它的覆盖范围到底有多广。为了获得更清晰的画面，她可以调出另一个视角，将大部分建筑隐藏起来，只显示每个区域的供水量。不同的数值以不同深浅的蓝色方格表示，从表示水量极少的浅蓝色到表示水量充足的深蓝色。如果一个地区没有供水，则没有任何蓝色。供水建筑本身作为地标留在地图上。

These sorts of analysis tools are essential to give the player an understanding of what's going on inside the simulation. Sim City had several: fire danger, crime, pollution, and so on. They allow the player to quickly locate trouble spots and take remedial action. These kinds of map overlays should not be a snapshot at a moment in time, but should be continuously updated by the simulation. That way, the player can watch them for a while and tell whether particular situations are getting better or worse—and, most important, whether her actions are having the desired effect.

这些分析工具对于让玩家了解模拟中发生的事情至关重要。《模拟城市》中就有几种：火灾危险、犯罪、污染等等。它们可以让玩家快速找到问题点并采取补救措施。这类地图覆盖不应是某一时刻的快照，而应由模拟不断更新。这样，玩家就可以观察一段时间，判断特定情况是在变好还是变坏——最重要的是，她的行动是否产生了预期效果。

# Special Design Considerations for CMSs CMS 的特殊设计考虑因素

The following sections discuss some design considerations particular to construction and management simulations.

以下各节将讨论建设和管理模拟游戏的一些特殊设计考虑因素。

## Simulating Individuals 模拟个体

Many CMSs simulate the behavior of a group of people (or, in the case of [SimAnt](https://en.wikipedia.org/wiki/SimAnt), ants) within an environment that the player is managing. If it's a very large number of people, as in the original [SimCity](https://en.wikipedia.org/wiki/SimCity_(1989_video_game)), behavior is usually modeled statistically and separate values are not kept for each person. However, you might want to simulate the actions of unique individuals that the player can see moving around and doing whatever it is that they do in your world. This will make your game a good deal more entertaining because there will be more for the player to see and because he can follow particular individuals around to watch what they do. It appeals to a sort of voyeuristic impulse and makes the consequences of the player's decisions seem more personal. It's particularly affecting when the player can actually see people who are unhappy packing up and leaving.

许多 CMS 都会模拟玩家所管理的环境中一群人（在[《模拟蚂蚁》](https://en.wikipedia.org/wiki/SimAnt)中则是蚂蚁）的行为。如果人数非常多，就像最初的[《模拟城市》](https://en.wikipedia.org/wiki/SimCity_(1989_video_game))那样，通常会对行为进行统计建模，而不会为每个人保留单独的数值。不过，你可能希望模拟单独的个人行为，让玩家看到他们在你的世界中四处走动，做着任何事情。这将使你的游戏更具娱乐性，因为玩家可以看到更多的东西，还可以跟随特定的人观看他们的行为。这迎合了一种偷窥的冲动，并使玩家的决定所产生的后果显得更加个人化。当玩家看到那些不开心的人打包离开时，这种感觉尤其强烈。

Modeling particular individuals rather than statistical aggregates adds considerably to your design job. You will need to create a behavioral model, usually including a scalar degree of happiness or unhappiness, and a set of needs that the person desires to have fulfilled. Various behaviors or circumstances can fulfill those needs. In some cases, the individual will be able to take an autonomous action that fulfills the need (driving from home to work fulfills the need to get to work); whereas in others, the player will have to provide something to fulfill the need (building a school provides educational opportunities). If a need goes unfulfilled, either through a problem that arises within the simulation (traffic jams prevent the person getting to work) or the player failing to act (no school has been built), there should be a negative consequence of some kind (the simulated person becomes unhappy).

为特定的个人建模，而不是为统计集合建模，会大大增加设计工作的难度。你需要创建一个行为模型，通常包括幸福或不幸福的标度，以及个人希望得到满足的一系列需求。各种行为或环境都可以满足这些需求。在某些情况下，个人能够采取自主行动来满足需求（从家里开车去上班满足了上班的需求）；而在另一些情况下，参与者必须提供一些东西来满足需求（建一所学校提供教育机会）。如果某项需求没有得到满足，无论是由于模拟中出现的问题（交通堵塞阻碍了人们上班），还是由于玩家没有采取行动（没有建造学校），都会产生某种负面后果（模拟人变得不快乐）。

Modeling individuals relieves you of the job of creating a statistical model because the behavior of the individuals collectively provides the statistics. However, balancing it will be a much more intricate job. You will probably discover emergent behaviors, unanticipated consequences of design decisions. Some of these will be fascinating and almost seem like intelligence, but others will clearly be degenerate: people locked in a tight behavioral loop, for example, only ever doing one or two things because your needs mechanism isn't balanced properly.

个人建模可以减轻创建统计模型的工作，因为个人的行为共同提供了统计数据。然而，平衡它将是一项复杂得多的工作。你很可能会发现涌现行为，即设计决策的意外后果。其中有些会很吸引人，几乎看起来就像智能一样，但有些显然是退化的：例如，人们被锁定在一个紧密的行为循环中，永远只做一两件事，因为你的需求机制没有平衡好。

Behavioral modeling is too big of a subject for us to address comprehensively here, and we suggest that you consult the bibliography at the end of this book for further reading.

行为建模是一个很大的课题，我们无法在此全面论述，建议你参阅本书末尾的参考书目，以便进一步阅读。

### Mind Reading 读心术

If the individuals you're simulating are visible on the screen and the player can select one with the mouse, you can offer another useful analysis tool: mind reading. To let the player know what's in that individual's mind, pop up an icon or even a whole dialog box showing his internal state: current goal, degree of happiness, or whatever other data might be useful to the player. This lets the player get a quick, rough sense of how the people are feeling without having to turn to a statistical analysis screen.

如果你模拟的人在屏幕上可见，而且玩家可以用鼠标选择其中一个，那么你就可以提供另一种有用的分析工具：读心术。为了让玩家了解这个人的想法，可以弹出一个图标甚至整个对话框，显示他的内心状态：当前目标、快乐程度或其他任何对玩家有用的数据。这样，玩家就可以快速、粗略地了解人们的感受，而不必转到统计分析界面。

> **Case Study: Theme Park, a Disgusting Example of Positive Feedback 案例研究：主题公园，积极反馈的恶心范例**
> 
> In [Bullfrog Productions](https://en.wikipedia.org/wiki/Bullfrog_Productions)'s CMS called [Theme Park](https://en.wikipedia.org/wiki/Theme_Park_(video_game)), the player was supposed to build a single theme park, ride by ride, into an empire of theme parks around the world. In addition to buying the rides, which attracted visitors, the player built shops and restaurants to extract money from them and hired maintenance and cleaning staff to keep the rides working and the park clean.
> 
> 在[牛蛙](https://en.wikipedia.org/wiki/Bullfrog_Productions)开发的名为[《主题公园》](https://en.wikipedia.org/wiki/Theme_Park_(video_game))的 CMS 中，玩家要把一个单一的主题公园，通过一个个游乐设施，建设成一个遍布全球的主题公园帝国。除了购买游乐设施吸引游客外，玩家还要建造商店和餐馆从中牟利，并雇佣维护和清洁人员来保持游乐设施的运行和公园的清洁。
>
> Each visitor to the park had a number of characteristics: how much money he had, how hungry or thirsty he was, and so on. One of these characteristics was "current degree of nausea." If a visitor became nauseated enough, he would vomit, leaving a mess on the ground that had to be cleaned up. Nausea could be caused by three things. Two of these were riding a particularly violent ride and being near an unclean bathroom. The third cause of nausea was—you guessed it—being near someone else's vomit. If the park was crowded and the player hadn't hired enough cleaning staff to keep the bathrooms clean and the vomit cleaned up, the result was chain-reaction vomiting by the visitors. This did nothing for the reputation of the park and tended to hurt future sales, but it did inject a degree of juvenile humor into what was otherwise a fairly straightforward business simulation.
> 
> 公园里的每个游客都有一些特征：他有多少钱、他有多饿或多渴，等等。其中一个特征是 “当前的恶心程度”。如果游客恶心到一定程度，他就会呕吐，在地上留下必须清理的脏物。引起恶心的原因有三种。其中两种是乘坐特别剧烈的游乐设施和靠近不干净的卫生间。导致恶心的第三个原因是--你猜对了--靠近别人的呕吐物。如果乐园里人很多，而乐园方又没有雇佣足够的清洁人员来保持卫生间的清洁和呕吐物的清理，那么结果就是游客的连锁呕吐。这对公园的声誉毫无益处，而且往往会损害未来的销售，但它确实为原本相当简单的商业模拟注入了一定程度的稚嫩幽默。

## Advisors 顾问

Another tool commonly found in CMSs is the advisor: a simulated character who pops up and gives the player advice from time to time (see Figure 14.6). Because problems are often localized in one area of the map, the player might be looking at another area when one occurs and not see it until it has grown severe. An advisor can warn of problem conditions wherever they occur. You should also consider including a screen button or menu item that jumps the screen to the most recently reported problem.

内容管理系统中另一个常见的工具是顾问：一个不时出现并向玩家提供建议的模拟角色（见图 14.6）。由于问题往往集中在地图的某个区域，当问题发生时，玩家可能正在查看另一个区域，直到问题变得严重时才发现。顾问可以在出现问题的地方发出警告。你还应该考虑加入一个屏幕按钮或菜单项，使屏幕跳转到最近报告的问题。

Figure 14.6. Theme Park World. Note the advisor in the lower-right corner. 图 14.6. 主题公园世界。注意右下角的顾问。

graphics/14fig06.gif

In addition to warning of emergencies, an advisor can give the player information about the general state of the game. "The people need more food," he can say, or "Prices are too high." This lets the player know of global problems without having to consult the analysis tools.

除了警告紧急情况，顾问还可以向玩家提供有关游戏总体状况的信息。他可以说 “人们需要更多的食物”，或者 “物价太高了”。这样，玩家就可以知道全局性的问题，而无需查阅分析工具。

To design an advisor, define both the local and the global problems that you think are important to let the player know about; then set the threshold levels at which the advisor will pop up. If the advisor is going to interrupt the player or say something aloud, don't set these thresholds too low, or the constant interruptions will become irritating. You should also make it possible for the player to turn off the advisor or to consult it only when wanted. Playing without the advisor adds an extra challenge to the game.

要设计一个顾问，首先要定义你认为应该让玩家知道的本地和全局问题；然后设定顾问弹出的阈值水平。如果顾问会打断玩家或大声说一些话，就不要把阈值设得太低，否则不断的打断会让人恼火。你还应该让玩家可以关闭顾问，或者只在需要时才咨询。在没有顾问的情况下进行游戏会给游戏增加额外的挑战。

You can also create an advisor that consists only of an indicator that remains constantly on the screen, displaying the most urgent global need at the moment.

你还可以创建一个仅由指示器组成的顾问，该指示器会持续显示在屏幕上，显示当前最紧迫的全球需求。

## Pure Business Simulations 纯商业模拟

A game like Theme Park World is a business simulation because it's about attracting customers and making profits. It's the building aspect of it that makes it a CMS. But there are also pure business simulations in which you construct only a financial fortune, not a visible world. The game Hollywood Mogul, for example, is about the business of making movies, but it consists only of a series of menu screens about hiring stars and making deals. The player never sees a set or a camera. Mr. Bigshot, shown in Figure 14.7, is a fairly simple stock market simulation.

像《主题公园世界》这样的游戏之所以是商业模拟游戏，是因为它以吸引顾客和赚取利润为目的。它的建设方面使其成为一款 CMS。但也有一些纯粹的商业模拟游戏，在这些游戏中，你只需构建一个财务财富，而不是一个可见的世界。例如，《好莱坞大亨》（Hollywood Mogul）这款游戏是关于电影制作的，但其中只有一系列关于聘请明星和进行交易的菜单屏幕。玩家永远看不到布景或摄影机。Bigshot 先生》如图 14.7 所示，是一款相当简单的股票市场模拟游戏。

Figure 14.7. Mr. Bigshot. 图 14.7. 大人物先生

graphics/14fig07.gif

Most of the challenges of designing a pure business simulation are the same as for any other management sim: You must devise an economy and mechanisms for manipulating it. The real trick is to find some way of making the subject visually interesting. Spreadsheets and pie charts have limited appeal, so if you're going to do a management simulation without a construction element, you should try to give it some kind of a setting or to find a visual representation of the process that will make it attractive and compelling. Mr. Bigshot accomplishes this with lots of animation, voiceover narration, music, and cartoon characters representing the player's opponents; as the player, you feel rather like a contestant on a TV game show.

设计纯粹的商业模拟游戏所面临的大部分挑战与其他任何管理模拟游戏都是一样的：你必须设计出一种经济和操纵经济的机制。真正的诀窍在于找到某种方法，使主题在视觉上变得有趣。电子表格和饼状图的吸引力有限，所以如果你要做一个没有建筑元素的管理模拟，你应该尝试给它某种设置，或者找到一种可视化的过程表现形式，使其具有吸引力和说服力。Bigshot 先生》通过大量动画、配音解说、音乐和代表玩家对手的卡通人物来实现这一点；作为玩家，你感觉自己就像电视游戏节目中的参赛者。

By contrast, Capitalism II (see Figure 14.8) is a huge, sprawling business sim covering all kinds of products and industries. In addition to showing pictures of them and all the raw materials that go into them, the game allows players to construct or purchase buildings in cities, so there's an attractive Sim City-like view as well.

相比之下，《资本论 II》（见图 14.8）是一款庞大的商业模拟游戏，涵盖了各种产品和行业。除了展示这些产品和行业的图片以及所有原材料外，游戏还允许玩家在城市中建造或购买建筑，因此也有一个类似模拟城市的吸引人的视角。

Figure 14.8. Capitalism II. 图 14.8. 资本主义 II

graphics/14fig08.gif

Business simulations will never have the pulse-pounding excitement of a first-person shooter, but they can be highly enjoyable games. As the designer, you'll need to work closely with the art director to make the essentially numeric nature of their gameplay more lively.

商业模拟游戏永远不会像第一人称射击游戏那样令人心跳加速，但它们可以是非常令人愉快的游戏。作为设计师，你需要与艺术总监密切合作，让本质上以数字为载体的游戏更加生动活泼。

## Hybrid Games 混合游戏

Civilization, Age of Empires, Dungeon Keeper, and The Settlers are all good examples of hybrid games: crosses between a CMS and a war game. In addition to their economic challenges, they all feature exploration and military challenges, varying somewhat from one game to another. The military aspect of The Settlers is quite simple, as it must be, given that the economic aspect is exceedingly complex. Age of Empires emphasizes warfare and military research more and is more of a real-time strategy game than a CMS, especially because natural resources are limited. Its people can be controlled directly, too. Dungeon Keeper is initially about constructing a dungeon, but in the later stages of each mission, it's actually about recruiting and training a balanced army, and then taking that army into battle. Control is a curious hybrid of direct and indirect: Creatures have a distinct behavior model, but they will obey orders as long as they're happy. (If they're unhappy, they might disobey or even desert.) However, Dungeon Keeper retains its economic challenges throughout: It's one of the very few games in which the soldiers have to be paid, fed, and given a place to sleep.

《文明》、《帝国时代》、《地下城守护者》和《工人物语》都是混合游戏的典范：CMS 和战争游戏的混合体。除了经济方面的挑战外，它们还都具有探索和军事方面的挑战，只是各款游戏之间略有不同。定居者》的军事方面非常简单，因为它的经济方面非常复杂。帝国时代》更强调战争和军事研究，更像是一款即时战略游戏，而不是 CMS，尤其是因为自然资源是有限的。游戏中的人也可以直接控制。地牢守护者》最初是关于建造一个地牢，但在每个任务的后期，它实际上是关于招募和训练一支均衡的军队，然后带着这支军队投入战斗。控制是直接和间接的奇妙混合体：生物有独特的行为模式，但只要它们高兴，就会服从命令。(然而，《地下城守护者》自始至终保留了其经济挑战性：它是为数不多的需要为士兵支付薪水、提供食物和睡觉场所的游戏之一。

If you're going to design a hybrid game, we encourage you to design the economic simulation first (unless it's really simple) and then add the other elements afterward. Because the other aspects of the game usually depend on the underlying economy, a mistake in the economic design can easily ruin the rest of the game. For example, a war game that includes an economy for weapons production might lose all its strategic challenge if the player is able to produce weapons too quickly. The player will exploit his economic strength and overwhelm the opposition with sheer numbers rather than strategic skill.

如果你要设计一款混合游戏，我们建议你先设计经济模拟（除非非常简单），然后再添加其他元素。因为游戏的其他方面通常都依赖于底层经济，经济设计上的失误很容易毁掉游戏的其他部分。例如，如果玩家能够过快地生产武器，那么包含武器生产经济的战争游戏可能会失去所有的战略挑战性。玩家会利用自己的经济实力，以数量而非战略技巧压倒对手。

> **Construction and Management Simulation Worksheet 建设与管理模拟游戏工作表**
> 
> When beginning the design of a construction and management simulation, consider the following questions:
> 
> 开始设计建设和管理模拟游戏时，请考虑以下问题：
>
> 1. What process is the player going to manage? What actions will the player take in managing that process?\
> 玩家要管理什么流程？玩家在管理该流程时将采取哪些行动？
> 
> 2. What resources exist in this process? For each resource, how is it produced, consumed, stored, transported, and converted into other resources? Is it tangible, intangible, or a hybrid? Is it limited or unlimited? What determines its production and consumption rates?\
> 该流程中有哪些资源？对于每种资源，它是如何生产、消耗、储存、运输以及转化为其他资源的？是有形的、无形的，还是混合的？它是有限的还是无限的？什么决定了它的生产率和消耗率？
> 
> 3. Which resources can the player manipulate and which can she not?\
> 玩家可以操作哪些资源，不能操作哪些？
> 
> 4. Will the process settle into a static or dynamic equilibrium, or will it run down if not tended by the player? Will disasters affect it?\
> 这个过程是会进入静态或是动态平衡，还是如果玩家不加以控制就会衰退？灾难会影响它吗？
> 
> 5. What will be player be constructing, and what function does the constructed item have? Will objects be purchased whole or designed and built over time? For each item that the player can construct, what does it cost and how long does it take to build?
> 玩家将建造什么，建造的物品有什么功能？物品是整体购买/设计和长期建造？玩家可以建造的每件物品的成本是多少，建造需要多长时间？
> 
> 6. Can the player demolish or sell things that she builds? Does this cost or earn resources for the player?\
> 玩家可以拆除或出售自己建造的物品吗？这需要花费玩家的资源还是为玩家赚取资源？
> 
> 7. Will the game have scenarios with victory conditions? What are they like?\
> 游戏中是否会有附带胜利条件的场景？它们是什么样的？
> 
> 8. What is the player's perspective and interaction model with the game? Is there a way to "get inside" the things she builds?\
> 玩家与游戏的视角和互动模式是什么？是否有办法“进入”她所建造的东西？
> 
> 9. What analysis tools are provided to help her understand the workings of the simulation?\
> 提供了哪些分析工具来帮助她了解模拟的效果？
> 
> 10. Is the simulated population modeled as individuals or as a statistical aggregate? If they are individuals, what is their behavior model? Are there multiple types of individuals? Can the player read their minds?\
> 模拟人口是作为个体建模还是作为统计总体建模？如果是个体，其行为模式是什么？是否有多种类型的个体？玩家能否读懂他们的思想？
> 
> 11. Will the game have advisors? What will they advise about?\
> 游戏中会有顾问吗？他们会提供哪些建议？
> 
> 12. Is this game a pure business simulation? Accounting and finance are often considered rather dull, so what makes this compelling? Does the game have a setting? If not, how can it be made visually interesting?\
> 这款游戏是纯粹的商业模拟游戏吗？会计和金融通常被认为相当枯燥，那么是什么让这款游戏引人注目？游戏有设定吗？如果没有，如何让它在视觉上更有趣？
> 
> 13. Is the game a hybrid with other sorts of games? What other elements in the game make it a hybrid (strategic problems, action challenges, puzzles, and so on)? How do they affect the way the game is controlled?\
> 该游戏是其他类型游戏的混合体吗？游戏中还有哪些其他元素（战略问题、动作挑战、谜题等）使其成为混合体？它们如何影响游戏的控制方式？

# Putting It Together 总结

Construction and management simulations seldom have splashy graphics, pounding music, or moments of high drama (except when disaster strikes). Instead, they call for observation, contemplation, and planning. To many gamers, that sounds terribly dull. Yet good CMSs are enormously popular and can make fortunes even without the latest 3D graphics. RollerCoaster Tycoon was a perfect example. What appeals about a CMS is not an adrenaline rush, but the fact that the player gets to make something of his own. Working carefully, tending and tweaking, he can build a tiny settlement on the banks of the Tiber into the glorious city that was Rome. Not the original Rome or the game designer's Rome, but his Rome—Rome as it would have been if he had been emperor. That's a different kind of achievement from blasting all the aliens in sight or winning a sports championship. The desire to create is at the heart of all CMS players. To design a CMS, first understand that desire.

建设和管理模拟很少有华丽的画面、震撼的音乐或戏剧性的时刻（除非发生灾难）。相反，它们需要的是观察、思考和计划。对许多游戏玩家来说，这听起来非常沉闷。然而，优秀的内容管理系统却大受欢迎，即使没有最新的 3D 图形，也能赚得盆满钵满。《过山车大亨》就是一个完美的例子。内容管理系统吸引人的地方不是让人肾上腺素飙升，而是让玩家可以制作属于自己的东西。他可以小心翼翼地工作、打理和调整，将台伯河畔的一个小定居点建成辉煌的罗马城。不是最初的罗马，也不是游戏设计者的罗马，而是他的罗马——如果他当了皇帝，就会是这样的罗马。这是一种不同于射杀所有外星人或赢得体育冠军的成就。创造的欲望是所有内容管理系统参与者的核心。要设计内容管理系统，首先要了解这种欲望。