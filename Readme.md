# Huh

This mod adds a few silly and obscenely OP characters to the game for you to play with.

**Characters:**
  - Edmund Blackadder (scottish)
  - Ulysses S. Grant (breton)
  - Mr. Spock (vulkan)
  - James Bond (english)
  - Mata Hari (dutch)
  - Bob Ross (saxon)
  - Jeanne d'Arc (frankish)
  - Wilhelm von Nassau (german)
  - Benedict Savelli (italian)

**Why did I create this?**

To learn about modding in CK2. It's interesting to see how much is available to adjustments.
Not everything is as easy as it looks though. Having to start the game many times over to test out a
new line of code is very cumbersome and time-consuming.
For the most part, this is just for shits 'n giggles and shouldn't be taken seriously. What started
off as a reading through the dynasty names, ended up in the various characters being created.

A few names have changed since I started:
  - Jacques de Villeneuve (5009, frankish) is replaced with Bob, as I did not want two french in court.
  - James Bond was first named Bonde (3811), but has since been modded.
  - Benedict Savelli was first named Bonifazi (803), since that was the most italian name to me.
    Also, his coa (black with white cross) matched nicely with Wilhelm's (full black).
  - Fernando Alonso (276, castillian) was replaced with Mr. Spock, as I did not like playing with the living.

As I continued with a basic court, I realized that I needed a possible spy wife. Who else is probably
better known than Mata Hari. And who else to lead my troops but shieldmaiden Joan of Arc :)

All the default court characters have the traits that best matches their profession. The spouse always
gets spymaster traits. The main trait will be at 75 with the others at 25.
Wilhelm tends to be used to store city titles and can act as a substitute treasurer. Benedict similarly
for holy titles who can act as a substitute spiritual. Both of them have their main stat at 50.
All created characters are immortal and can not marry. All characters receive a focus based on their role.

Jeanne d'Arc is something else entirely. With a starting personal combat skill of **161**, she is a force
to be reckoned with. She is given angelic guardian armor and the sword of a great conqueror. She is a
left-handed freckled shieldmaiden holy warrior, who for some reason I gave the homosexual trait.

**Family trees**

I went out of my way to invent a tiny family tree for each created individual.
Note this is still under heavy development.

Mata Hari, her parents and brothers.
James Bond with Ian Fleming as father.
Ambassador Spock with Leonard Nemoy as father.
Ulysses S. Grant and parents.
Edmund Blackadder with Rowan Atkinson as father.
Bob Ross and parents.
Jeanne d'Arc and her killer.
Wilhelm von Nassau and parents.

For Wilhelms father I was able to create a near matching coat of armor of the wiki.
I modded Jeanne's reason for dying, needing the killer. I was able to get Jeanne's killer the bishop
title he held at the time. Unfortunately I am unable to get Wilhelm's father to be Count of Nassau :(

Most characters have wiki links (DUH).

All spawned characters become children of the above with the exception of:
  - Edmund, who is too young
  - Benedict, who becomes the child of the in-game Pope Benedict II

I might change this in the future.

**Culture modding**

During testing with family trees, I came across the games habbit of adjusting the way children get their "last name".
After some digging on the wiki, I adjusted the patronym for some cultures so that the child naming of the characters
was "correct" (eg "Zelle" i.s.o. "Adamsdochter").

I also introduced a new culture "Vulkan", because why not. A "Logic" religion was added too.

**Used dates**
Where possible, I used actual dates from the wiki. Where needed, the year has been shortened by removing the leading 1.
In a few cases, living characters are mentioned hence their deathdate is set to 1066.9.14.
As a result of this, the game should start at least in the high middle ages (1066). Any earlier could pose unforeseen problems.

**Expectations**
To be fair; none. However, I'll write down some observations that I noticed.

- Giving Benedict a county title after giving him a lot of holy titles already.
  In one game, I managed to grab Rome and decided to give it to him. At the time he was already holding
  a fair amount of standalone bishop titles.
  Within a decade he conquered all of Italy and a large portion of North Africa.

- Warrior Lodge Jeanne is unstoppable!
  In one game playing as pagan, Jeanne managed to become leader of the Warrior Lodge. With her dueling
  experience racking up, I chose to reform to bloodthirsty gods and hold blood tournaments with her
  gaining even more personal combat ratings. I stopped looking when she passed 400...

- Bob Ross ends up being Pope
  In most of my catholic games so far, Bob is snithed from me as he will be appointed as the next Pope.

- Catholic Mata Hari is a beast!
  In one game as catholic, my wife ended up in charge of holy inquisitions!
----






----
**Creating a spymaster spouse**

This option is only available if you *have not* selected a spymaster (which happens to be James Bond).
Depending on your gender, you can choose between Mata Hari and James Bond. They marry you (matrilineal
for females) instantly and are assigned as your spymaster (replacing any existing character).

**Creating a chancellor**

Mr. Spock will ensure we live long and prosper. He is assigned as your chancellor.

**Creating a marshal maiden**

Jeanne d'Arc will crush any resistance. As the court's shieldmaiden, she is assigned as your marshal.

**Creating a marshal**

Ulysses S. Grant will lead your armies into victory. He is assigned as your marshal.

**Creating a treasurer**

Edmund Blackadder will ensure your court is run properly and accommodates the comedy :) He is assigned
as your treasurer.

**Creating a spymaster**

James Bond will serve, and be of service. He is assigned as your spymaster.

**Creating a spiritual**

Bob Ross will mellow our everyone with his amazing painting skills. He is assigned as your spiritual.

**Creating a spouse**

This option is only available if you *have* selected a spymaster (which happens to be James Bond).
A new spouse is created of your culture and religion and a random dynasty. They marry you instantly and
you are given the option to rename them. They will have the usual spymaster traits, just in case.

**Creating a commander maiden**

This option is only available if you have selected Ulysses as your marshal.
Jeanne d'Arc will crush any resistance. As the court's shieldmaiden, she is assigned as your commander.

**Creating a mayor**

Wilhelm von Nassau can be a great mayor if needed. He is assigned as your commander.

**Creating a vassal**

Benedict Savelli can be a great holy man if needed. He is assigned as your commander.

**Changelog**

- Rewrote most of the existing code into events
- Created the religion 'Logical' for Ambassador Spock
- Replaced Fernando Alonso with Mr. Spock/Leonard Nemoy
- Changing the way the mod enables by running an event chain at the start of the game
- Creating remaining events for all character types
- Expanded event to showing a window to the player
- Created first event driven code to react to chancellor dying or changing liege
- Settled to giving wilhelm's parents count titles in a similar way
- Gave Jeanne a blessed title (set_special_character_title)
- Changed Fernando's dynasty from 276 to 7042, and for his mother 7041. Removing my dynasty override.
- Gave various characters a shield looking trait cause it looks cool :)
- Fix more parenting and culture issues
- Gave all generated characters the reincarnation trait, cause why not :D
- Replaced parenting for several characters
- Created this Readme.md
- Removed fictive father for Jeanne and gave her the beatified trait after her death.
- While trying to create the Pope Benedict II character, I discovered they already exist and aborted any efforts.
- Having problems doing something similar for Nassau
- While creating Jeanne I managed to adjust her death reason and to get Jeanne's killer the Bishop title
  This was done by adding `history/titles/b_beauvais.txt`
- While creating Wilhem, I created first coat of armor by making one in the ruler designer
  I then copied over the data block from the save file :)
- Created the generic spouse option with renaming (I might revisit this)
- Created several other characters with wiki links obv.
- Tweaked first culture to fix last name
- Created first wiki entry for Mata Hari
- Created first dynasty Zelle
- Created initial character tree for Mata Hari
- Renamed Benedict Bonifazo to Benedict Savelli
- Replaced Jacques de Villeneuve with Bob Ross
- Added fire capability to quickly un-assign all commanders and counsil members
- Added icons ripped from the in-game decisions
- Added remaining characters as intrigue menu items
- Added "reset" capability to self and others to remove flags and immortality
- Created first intrigue menu item to create Mata Hari
- Created first self-targeted menu item
- Created initial mod as a directory structure after ripping apart the sketchy cheat menu mod
- Original characters created by stand-alone scripts for each

**Todo**

- For Edmund and James I opted to use birth/death dates according to the release of the first and last episode/movie.
  Now for James, this is not really a problem as he dies at 59. For Edmund however, well... he dies at 6!
- A similar problem exists for the living (Roan Atkinson).
  Roan is 111. I'm inclined to try and avoid living persons alltogether.
- Make parenting more consistent.
  Spawned Jeanne becomes generated Jeanne's daughter. The same happens for Benedict. But for others the actual parents are selected instead, even the fictive fathers for Edmund and James.
- Fix the count thingy for c_nassau/b_nassau, and have it named "Nassau" i.s.o. "Fritzlar"
  This is annoying me. I got it to work for Pierre. I only managed to see some changes if I adjusted the game files directly, but got stuck on the naming thing.
- Figure out how I can fix portraits of people so they remain constant between runs.
- Implement spawn husband, and also rething wether we want a random person or just Mata/James.
- Figure out why Pierre is getting random traits
- `set_focus` seems to get reset

