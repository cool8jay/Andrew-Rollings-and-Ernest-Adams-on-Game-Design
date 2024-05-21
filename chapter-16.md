This chapter is about a few game genres that aren't as popular as the ones we've already covered: artificial life, puzzle games, and games for girls. That doesn't mean there's anything wrong with them; they have produced some extremely successful games. In fact, because there are fewer games in these categories, the market isn't crowded with look-alike products. Working in one of these genres, you actually have a better chance of creating something distinctly new. However, you might have trouble persuading a conservative producer that a really good puzzle game is a better bet than yet another first-person shooter.

Because we're covering several genres in this chapter, we don't have room to explore the elements of each one; instead, we'll just hit the highlights.

# Artificial Life Games

Artificial life is a branch of computer science research, just as artificial intelligence is. Artificial life, or A-life, as it is sometimes called, involves modeling biological processes, often to simulate the life cycles of living things. A-life researchers hope to discover new ways of using computers by using biological mechanisms—mutation and natural selection, for example—rather than algorithmic ones. In particular, A-life is the study of emergent properties, unanticipated qualities or behaviors that arise out of the interaction of complex systems. Life itself is considered an emergent property of the planet Earth.

The most famous (though not the first) A-life game is called simply Life and was created by a mathematician named John Conway. It depicts cellular automata, simulated beings that "live" on a grid. All they do is survive, reproduce, and die according to three very simple rules. When people first began playing with the game, they quickly discovered that it had a number of emergent properties even though it had such simple rules. Certain patterns of cells could move across the grid ("gliders"), and some ("glider guns") could even generate an endless stream of new cells.

Because they're intended for entertainment rather than research, commercial A-life games implement only a subset of what A-life research investigates. There aren't any commercial A-life games about observing thousands of generations of one-celled animals evolving in an environment, for example. Typically, A-life games are about maintaining and growing a manageable population of organisms, each of which is unique.

## Artificial Pets

One subcategory of artificial life game is the artificial pet. Artificial pets are simulated animals that live on your computer, either in an environment of their own or on your desktop. They can be simulations of real animals, as in the Petz series developed by PF.Magic, or fantasy ones like the Tamagotchi, a tiny and very simple computer game built into a keychain.

Artificial pets are almost always cute. The nature of their gameplay concentrates on training and maintenance, and watching them do endearing things. They seldom reproduce or die, and the player usually wants to interact with only one or two at once. (Games about whole populations of organisms, in which they do reproduce and die, are discussed in the section "Genetic A-Life Games," later in this chapter.)

If the player is going to spend much time looking at an artificial pet, then the pet needs to have quite a lot of AI: a variety of things that stimulate it and behaviors that it exhibits. An artificial pet should have a number of emotions, or moods, that the player can learn by observation and can influence by interacting with it somehow. It also needs to interact meaningfully with others of its own kind: teasing, playing, grooming, fighting, and so on. Above all, it needs to be able to learn, so there must be a way for the player to show it how to do things. The learning process must not be too long (or the player will get frustrated and think his pet is stupid) or too short (or the player will run through everything he can teach it very quickly). (Tamagotchi, being so tiny and inexpensive, are obviously an exception to this principle!)

This quality of rich artificial intelligence distinguishes artificial pets from other kinds of A-life, in which individuals have simple rules but the population as a whole develops emergent properties. Artificial pets can have properties that appear only after they have been around for a while, but typically these are preprogrammed and are not truly emergent.

Because an artificial pet doesn't have much of a challenge or a victory condition (apart from training it to do something specific), it's a software toy rather than a game. ("Software toy" is a term coined by Will Wright, the original designer of Sim City, for entertainment software that you just play around with, without trying to defeat an opponent or achieve victory.) The entertainment of an artificial pet comes from watching it do things and interacting with it. In Petz, shown in Figure 16.1, you can see three cats, all of which are interacting with things in their environments. One is simply sitting on a rug, but it knows that it is a rug and has chosen to sit on it rather than somewhere else. An artificial pet has a large number of behaviors that the player sees repeatedly, and others that occur more rarely. Part of balancing it—making sure that the player doesn't get bored with it—is making sure that these rare behaviors occur often enough that the player does get to see them but doesn't take them for granted.

Figure 16.1. Petz from PF.Magic.

graphics/16fig01.gif

## The Sims

The Sims is almost the only game of its kind. There was one game a bit like it, Little Computer People, many years ago on the Commodore 64, but it wasn't nearly as rich as The Sims. If The Sims can be said to belong to a class, it is a virtual dollhouse: It simulates a family in a suburban home. You can make the people move around, cause them to complete certain tasks, tell them when to go to bed and when to get up, and so on. You can indirectly influence their relationships by making them talk to each other—the big difference is that you can't decide what they say, and you can't guarantee that they will like each other. Each simulated person has her own personality, likes, and dislikes.

One of the best things about The Sims is that there are multiple ways to play with it. It's sort of a cross between an artificial pet and a construction and management simulation. You need money to build additions to the house and to buy new furniture for it. The family has to earn that money by at least one member having a job. You can spend quite a lot of time in the buying-and-building mode, if you can afford it, which has nothing at all to do with artificial life. Some players, the particularly goal-oriented ones, really concentrate on this aspect, working hard to construct a mansion and fill it with luxuries. Others are more interested in the interactions among the people. In Figure 8.11 in Chapter 8, "The Internal Economy of Games and Game Balancing," you can see two sims dancing in their kitchen. This might have been spontaneous behavior, but it was more likely in response to an instruction given by the player.

### Needs

The main challenge of The Sims is to manage this group of slightly incompetent people and to improve their career prospects by teaching them things that will help them get better jobs. Each person, called a "sim," has eight needs that she must meet on an ongoing basis: hunger, comfort, hygiene, bladder, energy level, fun, social interaction, and room (which, in effect, means uncrowded, attractive surroundings). These needs drive her behavior. When a sim feels a need, she takes actions to meet it somehow. If the need goes unmet for too long, the sim becomes unhappy and can even die (in the case of hunger). Each sim always has a queue of things to do to meet her current needs, unless they're all met at the moment. The player can also give the sim orders, in effect inserting a behavior at the front of the queue. This need-based AI is at the heart of most simple behavior simulations, whether of people or animals; if implemented properly, it works very well.

### Skills

Unlike with an artificial pet, it isn't necessary to teach the sims by repeatedly showing them something. Instead, the trick is finding the time for them to improve their skills, which they can do by a variety of means. The sims have six skills: cooking, repair, charisma, body (physical strength and dexterity), logic, and creativity. These skills influence the jobs that they can take and, consequently, the amount of money that they can earn. Unfortunately, the sims are so busy and do everything so slowly that often they don't get enough leisure time to study or work out. The game is very much an exercise in time management.

### Personalities

Unlike almost every other computer game, The Sims tries to simulate relationships among individual people. These relationships are not terribly sophisticated, but they do include such concepts as jealousy, anger, and love. Each sim's personality is defined by five key variables: neat, outgoing, active, playful, and nice. These determine how they react to one another and whether they're likely to get along. The Sims also encourages the player to develop friendships among his fellow sims because career advancement is conditional upon having a certain number of friends.

### The Success of The Sims

The Sims has been a huge success, which we believe it owes to two things. First, it enables the player to exercise his creativity in a familiar sphere: the ordinary suburban home. In addition to building and furnishing a house, players can design their own "skins" for the sims, creating people who look like themselves (or anyone else). The game actually offers more creative play than Sim City or Sim Tower, for example, just because there are more different kinds of things to do. Players can also take photographs of their houses and store them in albums, along with written commentary that they supply, effectively creating illustrated stories. And they can share all these things over the Internet. The game offers more scope for personal creativity on the part of the player than just about any other on the market.

The second reason for the success of The Sims is that it is about human relationships. The player's immediate objective in playing The Sims is to make sure his sims' physical needs are met, but his secondary, longer-term objective is to meet the sims' mental or emotional needs: fun, social interaction, and quality living space. The need for social interaction is considerably more complex because it involves building relationships with other people rather than simply interacting with objects, and those social interactions can produce emergent properties. Players enjoy watching and influencing these interactions. In fact, the player's imagination plays a very large role in the game, just as it does in playing with dolls. The sims are not terribly complex simulations, but players give them names and personalities and ascribe many more characteristics to them than they actually possess. This quality of imaginative play is actually another form of creativity that contributes strongly to its success, especially among female players.

## Genetic A-Life Games

Some A-life games are about managing a population of creatures over time. Rather than concentrating so much on individuals, the object of the game is to achieve certain things with the population as a whole. By far, the most successful of these is the Creatures series from Creature Labs (formerly Cyberlife). In Creatures, you manage a small group of beings called Norns. Norns have a certain amount of AI, and they can be taught things through repetition, like the animals in Petz. Norns also have distinct genetic characteristics. Unlike either the people in The Sims or the animals in Petz, they have a limited life span, so the game is about breeding generation after generation of Norns and exploring and manipulating their world indirectly through them.

### Designing a Genome

To create a game in which you crossbreed creatures and get new, unique individuals, you need to devise a genome: a set of descriptors (genes) that define all the important characteristics of the creature. These characteristics should include everything about the creature that can vary from individual to individual: shape, size, coloration, and so on. You can leave out details that are common to all creatures. For example, if all your creatures will have two eyes and that will never change, there's no need to store a gene called Number of Eyes. Genes can have any number of possible values, from two (striped or spotted?) to floating-point numbers (height of creature in meters).

When two individuals reproduce, they mix their genes somehow, and you will need to define how this is done. For a quantitative value such as height, the initial temptation is to average them. Don't do this. Within a very few generations, all your creatures will be the same height, or very nearly. In fact, human genetics works differently. We have not one value for each characteristic, but two, one inherited from the mother and one from the father. These two values are called alleles. If a person's two alleles for the same trait don't match, one of them dominates according to a rule (the allele for brown eyes dominates the allele for blue, so people with one brown allele and one blue allele will have brown eyes). When a human reproduces, one of the two alleles is chosen at random to go on to the next generation. This means that it's possible for a brown-eyed person to still pass on the allele for blue eyes. Otherwise, the allele for blue eyes would disappear from the population almost immediately.

As for quantitative values such as weight, in humans, they tend to be controlled by multiple genes and influenced by environmental factors as well. You can define these mechanisms any way you like; you certainly don't have to do it the way humans do. As research goes on, geneticists are finding that mechanisms for genetic recombination and expression are quite complex and vary a lot even within a single species.

### Mutation

Mutation is a change to a gene that occurs as a result of some environmental factor. Radiation is well known as being mutagenic; so are some chemicals. Mutation has the benefit that it introduces random new values into the gene pool. Bear in mind that mutation doesn't normally affect the individual whose genes are mutated; it affects only his offspring. Of course, some of these changes can be detrimental or even lethal to the individual that inherits them. For the purposes of your game, you probably don't want to allow lethal mutations—those that produce miscarriages or stillborn offspring. If your creatures' gestation period is long, it wastes time and doesn't add anything of value to the gene pool.

### Life Span, Maturity, and Natural Selection

Each of your creatures needs a natural life span, or your population will explode. (In Creatures, the life span of a Norn is about 30 real-time minutes.) If you want your population to evolve through natural selection—that is, to become better adapted to its environment—then your creatures also need a period of immaturity, when they are not fertile, followed by a period of maturity, when they are. Natural selection works only if it kills off creatures with maladaptive genes before they are old enough to reproduce. If creatures could reproduce immediately after they were born, maladaptive genes would never leave the gene pool. For example, suppose that a creature's genes are such that it is unable to recognize food. This creature should die of starvation very soon. Whatever genetic values determine its food-recognition ability are clearly maladaptive. However, if it can reproduce immediately, those genes will be passed on. For natural selection to take place, you will have to design environmental hazards or other mechanisms (such as starvation) that tend to kill off young individuals with poor genes before they get the chance to pass on those genes.

(One of the reasons there are so many diseases associated with aging in humans is that those diseases catch you only after you have had the chance to reproduce. There's no natural selection against genes for arthritis and osteoporosis because those are diseases that occur later in life, after people have already had children.)

If there's one thing we know about evolution, it's that it's very slow—at least, if it works purely through random mutation and natural selection (evidence is growing to suggest that it's more complex than that). The life span of the Norns in Creatures is really too long for the player to breed hundreds of generations. If you want evolution to be a part of your game, you'll need to find ways of making it work nonrandomly or keep the life span of your creatures very short. Of course, the shorter the lifespan is, the less chance a given creature has to exhibit an interesting behavior, so there's a balance to be struck.

### Inheritance of Acquired Characteristics

> Long ago, in the morning of the world, the first zebra was pure white. But one day, there was a great fire amid the grasses of the savanna. The zebra stood deep in a pond for safety. When she came out, she was very wet. And as she passed through the burned grasses and reeds on the shore of the pond, the cinders left black stripes all along her sides. And from that day to this, all zebras have had black stripes along their sides.


Inheritance of acquired characteristics is a fancy term for this old children's-story idea. People used to think it was how evolution worked—if giraffes stretched up their necks to get food, the next generation of giraffes would have slightly longer necks, and so on. In fact, the opposite is true: Giraffes with short necks tend to starve without reproducing, leaving only giraffes with long necks in the gene pool. The outcome is the same, but the mechanism is entirely different. Stretching your neck doesn't change your genes.

However, you're designing a computer game. There's no reason you can't include inheritance of acquired characteristics if you want to. If the player pours blue ink over one of his creatures, that could change the creature's genes to produce blue offspring. In fact, this provides a convenient way for the player to do his own genetic engineering. Instead of fiddling with the creature's genes in a rather artificial user interface, he can fiddle with the creature directly to change its genes.

### Learned Behavior

Notice that learned information is also an acquired characteristic. Humans are not born knowing arithmetic; they have to be taught it. When you teach a human arithmetic, unfortunately, that doesn't cause her children to be born knowing it because the learning goes into her brain, not into her genes. In a game, however, there's a good reason for storing learned behavior in genes as well. If your creatures need to learn something important to survive, it's unlikely that the player will want to teach each individual one by one. It would be better for the player to teach one individual and then for that learning to be expressed in the genes of its offspring so that the player never has to teach them again.

Alternatively, the creatures could store the information in their brains and then begin to teach each other. Of course, you could allow the content of the teaching to change over time, producing behaviors slightly different from what the player originally intended. If certain teachings produce adaptive behavior, they themselves could be selected for, just as genes are. (The notion that ideas behave the way genes do is called memetics and is a highly controversial topic in academic circles. We're talking about computer games, however, and we can do whatever we like.)

### How Many Sexes?

Sexual reproduction has the advantage over asexual reproduction in that it mixes up the genes and creates unique new individuals, which might be better adapted to their environment. You don't have to restrict your number of sexes to two, but it is the most efficient mechanism. Two is a convenient number of sexes because it has the maximum probability that two individuals of opposite sexes will find each other when roaming around their habitat.

Here's an example. Let's assume that you have equal numbers of each sex in the population, and it takes a certain amount of time for a given individual to find another one and determine whether it is a member of the opposite sex. In a two-sex species, there's a 50-50 chance that any other individual is of the opposite sex; that's not bad odds. But if three sexes are required for reproduction, it is harder for all three to find each other. A given individual would need to find two others, which takes longer, and the odds aren't as good, either. Suppose that I'm of sex A, and I need to find two other creatures of sexes B and C, respectively. When I find the first one, the chance is one third that it is also of sex A (no use to me) and two thirds that it is of sex B or C, either of which will do for now. Let's suppose that it's of sex B. Now the two of us have to go hunt for another creature of sex C. The chance of any given creature being of sex C is only one third. So, the total probability that I'll find members of the sexes I need when I bump into two random individuals is only two ninths (2/3 x 1/3) instead of 50%. And of course, it gets worse the more sexes you have.

You don't have to stick to that rule of having equal numbers of each sex, however. Beehives contain one fertile female (the queen), hundreds of infertile females (the workers), and a few fertile males (the drones). The sex of creatures need not be determined by their genes, either. The sex of many reptiles is determined by the temperatures of their eggs during gestation. Eggs at the top of the pile, nearer the sun, develop into females; the cooler ones at the bottom develop into males.

### What Does the Player Do?

A genetic A-life game might not seem to have much for the player to do: Wind it up and watch it go. However, there is actually a fair number of things she might do. For example, she can create completely new individuals and add them to the population to observe how their genes influence the population. She can add and remove environmental hazards that would tend to weed out certain genes. She can play with the rate and nature of mutation by adding or modifying mutagenic objects or areas of the environment. She can also mate particular individuals to select for particular characteristics (with animals, this is considered useful and is called breeding; with people, it is considered evil and is called eugenics).

# Puzzle Games

Many single-player computer games contain puzzles. In action games, you often have to figure out the boss opponent's weakness. Adventure games are full of puzzles, frequently about obtaining inaccessible objects or getting information from other people. Even first-person shooters have the occasional puzzle, figuring out how to get past locked doors and other obstacles. Puzzle design is an essential element of game design, and it's harder than it sounds.

Puzzle games are games that are primarily about puzzle solving, sometimes without incorporating the puzzles into a story line or larger goal. That doesn't mean that they're a random collection, however. Puzzle games are usually variations on a single theme. To be a commercial success, a puzzle game needs to be challenging (but not too hard), visually attractive, and, above all, enjoyable to play with. It also needs to be fresh and large enough to justify spending the money on. Although solitaire card games such as FreeCell belong in the class of puzzle games, unless you sell a lot of them together as a collection, people are unlikely to want to pay for them.

## Scott Kim's Eight Steps

Scott Kim is a designer who creates puzzles for the print media, web sites, and computer games. He has worked in the field for many years and has identified eight steps in puzzle game design. The first four steps comprise the process of specifying the rules, while the last four comprise the process of building the puzzles and the game itself:

1. Find inspiration. This can come from a variety of sources, including other games. Tetris, for example, was inspired by a noncomputer game called Pentominoes. You can be inspired by a piece of art (the drawings of M.C. Escher have a very puzzlelike feel), a story, or some particular subject matter. Another source of inspiration is a play dynamic of some kind: flipping switches, turning knobs, sliding objects around, or picking them up and putting them down. Or, there are more complex dynamics among objects: balancing, reflection, connection, and transmission.

2. Simplify. Suppose you have an idea for a puzzle: efficiently parking vehicles of different sizes in a crowded parking lot so that when someone asks you to retrieve their car, you have to move as few other cars as possible. Part of making this task fun is simplifying it to its essentials. First, identify the essential tricky core skill (in this case, space planning on the fly) and concentrate on that. Second, eliminate any irrelevant details. Don't make your player worry about crashing the cars, for example. Third, make the pieces uniform. Instead of having cars with infinitely variable shapes and sizes, it's better to have several standard types that conform to a square grid. Finally, simplify the controls. Figure out what the essential moves are, and devise controls that implement them with a minimum of fiddling.

3. Create a construction set. The only way to be sure that a puzzle concept works is to play it, but obviously you don't want to code up the whole game before you know whether it's fun. You can build a paper prototype or a simple version in something like Macromedia Flash to see if it works. The rule designer can play with it to tweak the rules, and later the level designer can use it to build levels. You can also code a construction set into the final game so that players can construct puzzles for each other.

4. Define the rules. This is the key part of puzzle design. Most puzzles are characterized in terms of four things: the board (Is it a grid? A network? Is it irregular? Or is there no board at all?), the pieces (How are they shaped? What pictures are on them? What other attributes do they have? Where do they come from?), the moves (What is allowed and what is not? Are they sequential or simultaneous? What side effects do they have?), and the goal or victory condition (Does it have to be an exact match, or will a partial one do?).

5. Construct the puzzles. A puzzle challenges the player to get from a problem to a solution, but, of course, the path isn't simple. Every puzzle requires that the player make choices, some of which lead to dead ends. In an adventure game, each puzzle appears in a larger context (the story) that gives it meaning, and solving it advances the plot somehow. Some puzzle games also offer an overall plot of sorts or won't let you try the next puzzle until you've completed the current one. Good puzzles require insight from the player, that "Aha!" moment that occurs when the player realizes how the puzzle works and how to solve it. But you mustn't require an insight that's too obscure, or it will feel unfair. If you tell the player that he's in a maze, it's unfair for the only solution to be to knock down the walls unless you indicate somehow that this is possible.

6. Test. Testing tells you several things. It tells you whether the puzzle is too easy or too hard (this can be difficult to predict in advance), and it also tells you whether it's fun in the first place. It helps you find out if there are alternate solutions that you didn't think of, and it helps you discover errors in the rules. And, of course, it lets people try out the user interface. Because puzzle actions tend to be repetitive, it's important that the interface be smooth and not frustrating.

7. Devise a sequence. Now it's time to order all your puzzles into a sequence. The most obvious arrangement is a linear or accelerating sequence going from easy to difficult, but in practice, that becomes tiring and discouraging. A better arrangement is a sawtooth shape, which gets difficult for a while, then goes back to an easy puzzle, and so on, over and over. And, of course, you can give the player the freedom to play the puzzles out of order or let her earn it. You also need to think about transitions between puzzles, something that will keep her moving on to the next one. War games and role-playing games often do this with a story line. Or, the player can be working on a metapuzzle in between the regular puzzles, which motivates her to complete the whole game.

8. Pay attention to presentation. Finally, of course, there are all the other details of game design: sound, graphical style, animation, user interface elements, story line (if any), and so on. If you're used to designing other kinds of games, it might be tempting to move this to an earlier point in the process, but with puzzle games, the puzzles are 90% of the battle. Get them right first, and the rest won't be nearly as hard.

## What Computers Bring to Puzzles

Computers enable us to make a lot of puzzles that would be impossible or very expensive to create in the real world—all the mechanical parts in The Incredible Machine, for example. But even if a puzzle is physically possible, the computer can add a number of useful features to make the gameplay easier and more enjoyable.

* Enable nonphysical or awkward moves. The computer can let players do things that don't correspond to physical actions in the real world—for example, changing the color of something. You can also let the player control several things at once with just one key, something that would be awkward to do in a physical implementation.

* Include computation features. You can use the computing power available to automatically generate new puzzles, find solutions to the current puzzle, or generate hints about what the player should do next.

* Enforce the rules. In a lot of physical puzzles, it's up to the player to enforce the rules on himself. Sometimes players make mistakes and break the rules accidentally. A computer game can make sure that never happens.

* Undo and record moves. This very useful feature for games involves moving objects around in a sequence, as in Solitaire.

* Structure the experience. The computer allows you to present the experience in a particular order, if necessary, passing automatically from one phase to another, if that's what your game requires. In the real world, the player would be looking at the instructions and saying, "Let's see, what am I supposed to do next?"

* Teach. You can include tutorial modes and step-by-step instructions to help your player get into the game.

* Utilize bells and whistles. Obviously, with sound and animation, you can make a puzzle much more aesthetically interesting on the computer than it would be as a physical object.

* Enable online play. The computer lets players compete against one another, compare solutions, and be part of a puzzle-solving community.

## Checking the Victory Condition

Bear in mind that players don't always find the solution to a puzzle the same way that you did when you invented it. There might be more than one path to the goal. When your game is checking to see whether the puzzle has been solved, you should test only to see if the player has met the victory condition you gave her, not that she has done it in the way you expected. Otherwise, you've cheated her, and she'll be very frustrated. She's managed to get to the correct solution state, but your game refuses to recognize it.

This problem occurred in the game Interstate '76. It wasn't a puzzle game, but one of the levels did contain a puzzle of sorts. The player was driving an armed and armored car around in an area enclosed by a concrete wall, and the victory condition for winning the level stated that (among other things) it was necessary to get out of the enclosed area somehow. The game's designers had put in a hidden ramp, which they wanted players to find and use to drive out of the area. However, players of the game discovered that there was another way to get out. If a player dropped a land mine near the wall and then drove toward it at full speed, the force of the explosion would lift the car high enough to clear the wall, and the car would fly over it and out. Unfortunately, the software didn't test for the solution state given: Is the car outside the wall? Instead, it tested to see if the ramp was being used. If a player got out without using the ramp, it didn't know that the level was finished, even though the victory condition had been met.

Of course, sometimes games contain bugs that allow a player to cheat in some way and reach a solution by a means that's completely outside the rules. In Interstate '76, however, the trick with the land mine wasn't a bug; it was just an innovative solution that the designers didn't consider. When the software is checking the victory condition, be sure it's checking the solution state that you told the player to achieve, not the way in which he achieved it.

> **Case Study: The Incredible Machine**

> The Incredible Machine is an excellent example of a puzzle game that is imaginative and clever and that has sold really well. In fact, it's not just a game, but a whole game franchise, with five editions so far. The current version is called Return of the Incredible Machine: Contraptions, and it's published by Sierra Entertainment (formerly Sierra On-Line).

> The game consists of a series of puzzles, each of which involves building a Rube Goldberg–like machine to accomplish a certain task. Each machine is constructed in a two-dimensional space upon which a variety of mechanical devices can be placed. (Some of these devices are actually animals, which can be frightened by noises or lured by food.) A few objects are already in position at the beginning of the puzzle, and the victory condition states what the player is trying to accomplish (for example, pop the balloon). The player is given a limited number of additional devices to place in the area. The object is to place them and hook them up in such a way that when the machine is set in motion, the goal is achieved. Playing the game consists of adding elements to the machine, trying them out, adjusting them, trying again, and so on. Figure 16.2 shows one of the scenarios in The Incredible Machine. The goal is given at the left. Available parts are in the area beneath the main workspace.

> Figure 16.2. The Incredible Machine.

> graphics/16fig02.gif

> Scott Kim has identified three key design decisions that he feels have made The Incredible Machine the prototypical construction puzzle game.

> 1. Allow the player to build things. This makes The Incredible Machine a construction game and differentiates it from, say, Tetris (an action puzzle game) or Marble Drop (a logic game in which you decide where and when to drop marbles into a mechanism). The player feels as if he is exercising his creativity.

> 2. Include no real-time decision making. Constructing the machine and running it take place in separate modes. The player can take as long as he wants to think about what he's doing. This is in contrast with Lemmings, which is also an excellent game but requires the player to solve the puzzle on the fly. Often if the player didn't get it figured out in time, he had to start over.

> 3. Allow players to design their own puzzles. Any time players can build their own elements, it adds value to the game and helps create a community of devoted fans. Players can exchange their puzzles by email, post them on web sites, run tournaments, and enjoy all kinds of other activities, all of which is free publicity for the game.

# Games for Girls

The game industry has always been overwhelmingly male, and male developers have tended to design games that they themselves would like (or would have liked when they were boys). For most of the industry's history, no one made an effort to design games specifically for girls, or to even to think much about what kinds of games girls would like. It was a Catch-22 situation: If you proposed a game for girls to a publisher, you would be met with the reply, "Girls don't play video games." But, of course, the reason they didn't play video games was that there weren't many games they liked to play—or, at least, that was the general perception. (Further research showed that this was an unfounded stereotype; far more girls played games than people realized, even though no one was considering their interests.)

In the mid-1990s, a number of people realized that girls represented an untapped market, and several companies were set up to exploit it. One in particular, Purple Moon, did a great deal of research to try to discover how girls play games and what kinds of games they would like. Unfortunately, the games that Purple Moon published on the basis of this research took little time to finish, and they offered less value for the money than most other games did. They didn't sell very well, and eventually Purple Moon got into financial trouble and was sold to Mattel, the toy company. Industry attention waned, and games for girls ceased to be a major subject of debate.

However, we think it's an area worth discussing because some people are continuing to make money with games for girls, and this remains an underserved market. Remember, however, that we're talking about girls, not women. Adults are more diverse than children are: They live in a larger world, and they've been exposed to more things and have a wider variety of interests. Don't make the assumption that what applies to girls also applies to women generally.

## Mattel's Approach

If you want to make games specifically for girls, as opposed to games that appeal to children of both sexes, you have to ask yourself what girls are especially interested in—and, perhaps more important, what they're not interested in. For the answer, you need look no farther than Mattel. Mattel is the manufacturer of Barbie®, the single most famous toy for girls in the world. Mattel has had great success developing games for girls because it understands its target market. (Mattel doesn't publish software itself anymore, but it licenses its brands to others.)

Part of the reason for Barbie's success is that she follows a proven, time-tested formula. She is aimed a core age group from four to eight years old; after that, girls' interests change, and Mattel does not try for a one-size-fits-all approach. The company has no social agenda and makes no claim of political correctness.

Jesyca Durchin is the owner of the consulting company Nena Media (www.nenamedia.com), which creates media content for young girls, and is a former executive producer for Mattel. At the 2000 Game Developers' Conference, she gave an extremely useful summary of what she had learned about how girls in this age group play games:

> **Developing Games for Girls**

> Girls Have a Wide Variety of Interests

> It is vital to identify what type of girl is interested in your type of game. Girls are much more fragmented in their interests than boys. Girls change more rapidly, and their emotional and intellectual growth happens differently. A girl will have different needs in her playtime almost every year of her childhood—loosely defining childhood to be ages 4 to 14.

> Hinge Interactivity on Proven Play Patterns

> A play pattern is a traditional and almost instinctual way a child will approach an object or an activity to entertain her. Girls traditionally value the following:

> * Fashion play

> * Glamour play

> * Nurture play

> * Adventure play

> * Action/twitch play

> * Collection play

> * Communication/social play

> As well as exercising their own imaginations, girls like to reproduce daily life in play. Barbie is a vehicle for projecting adult activities into a child's world. Don't be afraid of open-ended or non–goal-oriented play.

> **Girls Like Stuff**

> Stuff is what the girl can collect, display, or take away from the product. It is incredibly important for the girl to feel there is a reason for her to play. In some ways, collecting stuff replaces the concept of scoring in traditional boy's software. Collecting each one of a variety of shells, for example, is more interesting than trying to achieve a high, but abstract, numerical score.

> **Create Environments That Are Attractive to Girls**

> Girls like environments that are reality-based but either are beautiful or make sense to the story line. Symmetry and color coherency are important to girls. Not everything has to be pink, purple, and pretty, but each environment should give the girl the feeling of being in another place. Girls (and boys) are highly imaginative, and they will create alternative story lines in their own heads. Be aware that the girl's imagination will influence her view of your environment.

> **Girls Appreciate Sensual Interfaces**

> Girls tend to respond more positively to what I refer to as the sensual interface. They need colorful, sound-driven interfaces that "feel" good. The interface needs to feel magical and needs to have what I call the brrrring factor. Don't give girls a group of identical gray pushbuttons, no matter how logically organized they may be; give them buttons that ring and change shape and color.

> **Extend the Play from Existing Toys or Media into Software**

> Branding is becoming more and more important in the business of software. It is doubly important in the girl's software business because girls are still just getting involved in viewing the computer as an entertainment tool. Branding is important to rising above all the muck.

> **Don't Be Ashamed of Your Work**

> If you're embarrassed by what you're doing, it will show. Do it wholeheartedly or don't do it at all. Girls can tell if you're ashamed of making games for them. If you're uncomfortable using terms like "hair play" or "relationship games," don't bother.


## A Few Misconceptions

Because people see fewer girls playing hard-core games than boys, they have tended to jump to conclusions about what girls want.

* Girls don't like computer games because computers are techie. This is patently false. Although most girls and women generally are less fascinated by the technical details of computers than boys and men are, that doesn't discourage them from playing computer games any more than automotive specifications discourage them from driving cars.

* Girls don't like violence. No, what girls don't like is nonstop, meaningless violence. It's not so much that they're repulsed by it as that they're bored by it. It doesn't stimulate their imaginations. If you've seen one explosion, you've seen them all.

* Girls want everything to be happy and sweet. Not true. Ever see a group of girls setting up a party and planning to exclude someone? Girls are perfectly capable of being deliberately hurtful. If you read books written specifically for girls, you'll see that they're not just saccharine from one end to the other. Girls like stories filled with mystery, suspense, even danger—but again, it has to be meaningful, not just random or pointless.

* Girls don't like to be scared. This is only partially true. Jesyca Durchin makes a useful distinction between spooky and scary. Girls like things that are spooky but not scary. The abandoned house that contains a clue to the mystery, or the carnival at night, are spooky. Walking through dark streets with a murderer on the loose is scary. Spooky is about the possibility of being startled or frightened; scary is about the possibility of being hurt or killed.

## A Final Note

Bear in mind that these are generalities. In her 1989 book Gender Blending, Holly Devor quoted studies that showed that as many as 50% of heterosexual women identified themselves has having been tomboys as children. We wouldn't claim that the characteristics described previously appeal to all girls, but they certainly appeal to many. You should take them into consideration if you're trying to make a game for them.

Some developers, both male and female, are repulsed by the idea of making games about hair and clothing and makeup; they feel that this perpetuates a stereotype of femininity. Although there's some merit in that argument, goodness knows that a vastly larger number of games perpetuate a much more unfortunate stereotype of masculinity: They depict men (and reward players) who are violent, greedy, wanton, and monomaniacal. To condemn games for girls on the basis that they're stereotypical is to establish an unfair double standard.