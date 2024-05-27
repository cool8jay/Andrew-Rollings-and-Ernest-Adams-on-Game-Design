Construction and management simulations are games about processes. The player's goal is not to defeat an enemy, but to build something within the context of an ongoing process. The better the player understands and controls the process, the more success he will have at building.

建筑和管理模拟游戏是关于过程的游戏。玩家的目标不是打败敌人，而是在一个持续的过程中建造一些东西。玩家对过程的理解和控制越好，就越能在建造过程中取得成功。

The first really successful computerized construction and management simulation (which we refer to as a CMS from now on) was [SimCity](https://en.wikipedia.org/wiki/SimCity). We'll look at it in some detail later in the chapter. [SimCity](https://en.wikipedia.org/wiki/SimCity) proved that computer games don't need high-speed action or violence to be a success; it succeeded in part because it didn't have those things and appealed to a broad audience.

第一个真正成功的计算机化建筑和管理模拟游戏（我们从现在开始称之为 CMS）是[《模拟城市》](https://en.wikipedia.org/wiki/SimCity)。我们将在本章稍后部分详细介绍它。[《模拟城市》](https://en.wikipedia.org/wiki/SimCity)证明，电脑游戏不需要高速动作或暴力就能获得成功；它之所以成功，部分原因在于它没有这些东西，而且吸引了广大的受众。

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
> Although it isn't the oldest CMS, the spiritual father of them all is [SimCity](https://en.wikipedia.org/wiki/SimCity), published by Maxis (now a part of Electronic Arts). Sim City was originally designed for the Commodore 64, although it was most successful on the IBM PC, and the first version of the game is now playable for free on the Web. (Visit [http://simcity.ea.com/play/simcity_classic.php](http://simcity.ea.com/play/simcity_classic.php) if you're interested.) It was followed by a host of other games in the same mold: SimAnt, SimTower, SimFarm, and so on, which met with varying success.\
> 
> 虽然它不是最古老的 CMS，但所有这类游戏的的精神之父是 Maxis（现在是 Electronic Arts 的一部分）发行的[《模拟城市》](https://en.wikipedia.org/wiki/SimCity)。[《模拟城市》](https://en.wikipedia.org/wiki/SimCity)最初是为 Commodore 64 设计的，但它在 IBM PC 上的表现最为成功。(如果您有兴趣，请访问 [http://simcity.ea.com/play/simcity_classic.php](http://simcity.ea.com/play/simcity_classic.php)。）之后又推出了大量同类游戏：《模拟蚂蚁》、《模拟大楼》、《模拟农场》等等，它们取得的成功各不相同。
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

It's easy enough to say that CMSs are about a process, but the process has to be meaningfully displayed on a computer screen, and it must fire the player's imagination. Most CMSs take place in the context of a physical space, usually a two-dimensional world in which buildings or other objects can be constructed. Caesar is about building an ancient Roman town, so the setting is a landscape near a river. Civilization is about exploring a world while at the same time advancing a civilization both culturally and technologically, so its setting is an entire continent, or several of them.

A few pure business simulations don't take place in a physical setting, and they're discussed at the end of the chapter.

## Gameplay

The challenges in a CMS are largely economic. The player must understand how the internal economy of the game works and how to manipulate it to produce economic growth. Growth provides the resources required for the construction that is usually the overall goal of the game.

### Indirect Control

A war game is a game of direct control. The players tell their troops exactly where to go and what to do, and they do it. The simulated soldiers have little or no autonomous behavior or artificial intelligence. If told to stand and wait someplace, they'll wait there forever.

The majority of CMSs, on the other hand, are games of indirect control. The game simulates a process, and the player can alter that process only in limited ways. The process must be manipulated indirectly, and the player has to learn how the controls affect its inner workings. If there are simulated individuals in the game (see the "Simulating Individuals" section later in this chapter), for the most part, they can be controlled only indirectly. They have a behavior model that governs what they do, and it responds to stimuli, but they can't be given direct orders.

However, the dividing line between direct and indirect control is a fuzzy one. Certain player activities, such as choosing the location of new construction, will be direct. Others, such as trying to boost sales by reducing prices, will be indirect. Reducing prices is direct, but the (hoped for) consequent rise in sales is indirect.

### Construction

Construction itself isn't the challenge in a CMS; the challenge is in obtaining the resources needed for the construction. Construction is the part of the game that lets the player exercise her imagination and create something unique and personal. Accordingly, you, as the designer, need to find a way to make this easy and enjoyable.

Construction mechanisms in CMSs tend to be one of two types: buy or design-and-build. When the player buys an object (a segment of wall, say), the resources to build it are deducted from stockpiles, and the object immediately appears in a designated location. This lets her build rapidly, adding pieces like using Lego bricks. You should use this mechanism if construction is the primary activity in your game. If so, it needs to be easy and continuous, not something the player has to wait for. This is how Sim City worked: Zoning property and constructing civic amenities such as police stations and airports happened instantly because it was the primary activity in the game.

The design-and-build mechanism is more often seen in games in which the player does a little construction, then some management, then more construction, and so on. In design-and-build, the player marks out an area where new construction will appear. The game often displays the new building in a ghostly, semitransparent form to indicate that it is under construction. However, it takes time to build. If the game includes simulated people, you might be able to see them at work on it; if those people go away or die for some reason, the building might be left in a partially completed state.

In design-and-build, you don't have to remove all the required resources from storage at once because the construction takes place over time. In The Settlers, wood and stone had to be physically transported a little at a time from stockpiles to the construction site. This puts an extra burden on the player to manage his resource flow, but it does give him more control. In contrast, [Age of Empires](https://en.wikipedia.org/wiki/Age_of_Empires) deducted the resources necessary for construction immediately when it was designed. They drained out of the game rather than being transported to the site. Although this was unrealistic, it meant that the player could build something only after he definitely had enough resources for it, and he didn't have to worry about moving things around all the time.

[Dungeon Keeper](https://en.wikipedia.org/wiki/Dungeon_Keeper) was particularly interesting because construction was actually excavation: It took place underground, and the player couldn't see the area he was excavating into. Excavations often led into immovable rock or to existing caves, underground rivers, or pools of lava. It was also irreversible: When an area had been excavated, there was no way to close it up again. This encouraged players to be cautious. Suddenly excavating into an area full of enemy creatures was a major hazard of the game.

### Demolition

In addition to letting your players construct things, you might need to give them a way to demolish things. A big part of the fun of a CMS is building your city, theme park, or whatever the way you want to build it. If a construction decision is irreversible, it means whatever the player is building can get only bigger, never smaller, and the player cannot change his mind or react to new circumstances. This might be okay for strategy games (many war games, for example, allow you to build factories and defenses but not demolish them), but in CMSs, it prevents the player from exercising his full creative freedom; hence, the need for a demolition feature.

You should consider whether you want demolition to cost something, cost nothing, or actually earn money. If it costs money to demolish something, you are, in effect, penalizing the player for changing his mind and perhaps encouraging him to plan more carefully in the future. He has lost not only his initial construction cost for the item, but the demolition costs as well. If it costs nothing, the player has lost only his construction costs. If he actually gets something back, it's usually called "selling" the item rather than demolishing it, and it further reduces the price the player pays for changing his mind. If he can sell it back for exactly as much as he paid, there is no net cost at all for building a thing and destroying it later. This is rare in CMSs because it removes some of the challenge. Players can build madly, secure in the knowledge that they can always get their money back by selling.

A player must never be able to sell an item back to the computer for more than he paid for it, unless he has expended further resources to upgrade it somehow. If the players can buy from and sell to the computer at will, and there exists any mechanism by which they can sell something for more than they paid for it, they will exploit this ruthlessly, piling up huge fortunes by endlessly buying and reselling and ignoring the rest of the game. There are various ways to prevent this. One is to make sure that it is simply impossible to make a profit; all sales must be for less than the original purchase price. If you want players to be able to make a limited profit, you have to place limits on the amount of buying and selling they can do. The computer can refuse to sell items to them after a while or can refuse to buy them back. The computer itself can have a limited amount of money and be unable to buy if it has run out. And in a multi-player game, you can let players buy and sell at a profit to one another, but not to the computer itself. Transactions among the players don't change the total amount of money in the game; it's selling things back to the computer that have the potential for abuse.

### Victory Conditions

A good many CMSs have no victory condition; the player simply builds whatever she likes as effectively as she can within the constraints of the system. These games might well have a loss condition, however: total depletion of resources (or, in monetary terms, bankruptcy). This is the loss condition in Monopoly, for example. Victory in Monopoly consists simply of bankrupting all the other players.

If you do want to define a victory condition, it's best to do it in the context of a scenario of some kind. Give the player a partially constructed city (or whatever) and a set of initial conditions, and then define the victory condition as achieving some other condition. It could be as simple as, "To win, your enterprise must be worth $5 billion," but it can be as complex as you like. You can also start the player in rapidly deteriorating conditions and challenge her to turn them around or simply to survive for a certain length of time.

### Competition Modes

CMSs are almost always single-player games. It's possible to make them two-player or even multi-player, but it's not a natural way to play. CMSs encourage planning and thought, not frantic action. If the players are competing for the same resources, it becomes a race to see who can grab the most, ignoring the other aspects of the game. If the players are separate and have symmetric starting and victory conditions, the game tends to be about optimizing efficiency. If the conditions are asymmetric, the game will be difficult to balance.

CMSs let the player be playful, to build and experiment in the world you've given him. That's seldom consistent with competition. One major exception is in hybrid games, those that have a military element as well as construction and management elements. They're discussed in the "Hybrid Games" section later in this chapter.

## The Player's Role

When designing any game, the first question you have to ask yourself is, what is the player going to do? The answer to this question usually arises out of a clear statement of the player's role in the game: pilot, general, adventurer, irradiated hedgehog, and so on. In a CMS, however, it's less easy to define the player's role because it seldom corresponds to an actual job in real life. The mayor of a city doesn't really lay out its streets or make zoning decisions personally.

This is one of the few genres in which we don't think you have to define the player's role in familiar terms. You still have to concern yourself with what the player is going to do, of course, but it doesn't matter that much what you call him.

### Interaction Model

The player is almost always omniscient in a CMS because she needs to see what is happening all over the game world. It's difficult to control a global process from a local perspective. Most CMSs don't give the player any kind of avatar. Those that do usually make it temporary. If the player is building a city or a space station or some other structure, she could well want to see what it would look like from the perspective of someone inside it. For example, in [Dungeon Keeper](https://en.wikipedia.org/wiki/Dungeon_Keeper), it is possible for the player to "possess" a creature in her dungeon: to take control of that creature and walk around the dungeon in the first-person perspective (see Figure 14.5), seeing through its eyes. However, this feature is mostly cosmetic. It is occasionally useful in the military aspects of the game, but not at all in the management aspects. In short, we think the "down inside" view is a fun one and the player will enjoy it, but the primary interaction model in a CMS needs to be omnipresent.

Figure 14.5. Dungeon Keeper 2, omnipresent view (top) and inside view (bottom).

graphics/14fig05.gif

## User Interface 用户界面

Because CMSs aren't trying to create an illusion of reality in the way that first-person shooters or flight simulators are, their user interfaces can be more "computerlike," using pull-down menus and rows of buttons along the edges of the screen. In a CMS, the emphasis is more on convenience than verisimilitude.

### Perspective 视角

The user's perspective in a CMS naturally depends on what's being simulated. Most CMSs simulate a process taking place over a land area—whether it's a city, a farm, or an entire planet. As a result, they tend to use an isometric perspective and enable you to view the world from one of four angles. The isometric perspective requires little CPU time, an advantage even in these days of 3D hardware accelerators, because CMSs do a lot more computation behind the scenes than other kinds of games. Its disadvantage, at least from a development standpoint, is that your art team will have to draw sprites of everything in the game from four different perspectives—and still more if you offer multiple zoom levels. It also doesn't let the player zoom in to any degree he likes. CMSs are sometimes frustrating in that the closest-in zoom level is a little too close, and the next one out is a little too far out.

If your game simulates a process taking place in a three-dimensional space, you might find it useful to divide the space into layers (either physical or conceptual) to make it easier for the player to navigate around and view. It's also helpful to provide a button that returns the camera instantly to a default perspective so that the player can reorient himself if he gets lost.

### Analysis Tools 分析工具

In a CMS, the player is trying to understand and control a mathematical model. To do this, she needs convenient access to key variables within the model. You should display the most important scalar (single-value) variables—for example, the amount of money she has to work with at the moment—on the screen at all times. The display can be in digits, if that's most appropriate, or a bar graph or some other kind of monitoring device, depending on the nature of the simulation.

Often the player needs to know not only the current value of a variable, but also how that variable has changed over time. This lets her track trends and respond to them before trouble occurs. In Theme Park, a business simulation about building and managing (surprise!) theme parks, visitors came in, spent a while in the park, and left again. The player could see them wandering around, but it was difficult to get a sense of the park's popularity just by counting heads. One of the information pop-ups available was a graph that showed how the population had changed over the past 1, 3, or 12 game years.

With vector (multivalued) variables, you'll need a different approach. In Caesar, for example, every area of the Roman town that the player was trying to build needed a water supply of some sort. The amount of water available was therefore a vector; it had a separate value for each square on the grid. There were a variety of types of water supplies (wells, pipes, fountains, and so on), and each provided water to a given area around it. In the game's default perspective, showing all the buildings of the town, the player could see the structure supplying the water, but it was difficult for her to visualize exactly how far its coverage extended. To get a clearer picture, she could bring up a different view that hid most of the buildings and instead showed only the amount of water available in each area. The different values were indicated as squares in different shades of blue, from light blue, indicating very little water, to dark blue, indicating plenty. If an area had no water supply, there was no blue at all. The water supply buildings themselves were left visible on the map as landmarks.

These sorts of analysis tools are essential to give the player an understanding of what's going on inside the simulation. Sim City had several: fire danger, crime, pollution, and so on. They allow the player to quickly locate trouble spots and take remedial action. These kinds of map overlays should not be a snapshot at a moment in time, but should be continuously updated by the simulation. That way, the player can watch them for a while and tell whether particular situations are getting better or worse—and, most important, whether her actions are having the desired effect.

