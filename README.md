# Four Kingdoms

A top-down medieval open-world RPG in a single HTML file. You play a poorly equipped knight on a continent split between four rival kingdoms (Albion, Valoria, Draven and Eldoria). Explore, clear bandit camps, take quests, trade and build your reputation, while the kingdoms ally, feud and go to war around you.

## Play

Play online at **https://cksarge.github.io/Four-Kingdoms/**, or download `index.html` and open it in a modern browser. There is nothing to install and no server. Progress and settings save to your browser's local storage; *Settings → Delete All Save Data* wipes everything and starts fresh.

## Game modes

When you start a new game you choose a mode:

- **Story Mode**: a hedge knight finds a dying royal courier, and the trail leads to an ancient conspiracy. The story runs in three acts, about 35 main quests in all, and a full playthrough lasts several hours and many in-game weeks.
  - **Act I:** a shared opening splits into three storylines depending on your choices: unmasking the Ashen Circle, stopping the Hollow King, or seizing power yourself.
  - **Act II, *The Long War*:** every storyline passes through this act. Two crowns go to war, and you choose a side or try to broker peace. Your decisions settle the fate of a captive heir, a Hollow blight in the fens, the Bone Wyrm, the Pale Hand's secret roll, and a siege of a royal capital. It ends at the Council of Winter.
  - **Act III:** each storyline continues with its own quests and bosses, including the Ashen Seneschal, Rimeheart, a poisoned feast and a crown council. It ends in a final battle against the Hollow King, who rises a second time. The allies who fight beside you depend on the choices you made in Act II.
  - **The final battle** is meant to be a real test of skill. The allies you earned in Act II fight beside you through the first two waves of the Hollow host. Then Aurek rises, the grave-mist seals the barrow and freezes your allies, and you face him alone:
    - **His attacks:** sword combos, a charge, a frost blast, volleys of frost bolts, grave hands that burst from the ground, and a step through the mist to land behind you. Each is marked on the ground first. Gold marks can be blocked, at a heavy stamina cost; red marks must be dodged.
    - **Fighting him:** his guard is up unless he is attacking, so the opening comes right after an attack. Enough damage in a short burst staggers him.
    - **Limits in the arena:** healing has a cooldown, your horse will not come near, and he calls up more dead as his health falls.
    - **If you fall,** you wake at the edge of the barrow-field and the fight starts again from the moment he rises.
    - **Difficulty:** it sets how long his warnings last, how often he attacks, how long his combos run and how long the healing cooldown is.
  - **22 endings:** which one you get depends on your choices and on the state of the world, meaning its wars, alliances and your reputation with each kingdom.
  - **Epilogue:** a closing section of several pages covers how it ended, what became of each kingdom, the fates of the people you met, and your legacy and deeds.
  - When the story ends you can keep playing the same world as a sandbox or return to the main menu.
- **Sandbox**: the open world with no story.
- **Tutorial**: a five-minute lesson with a drill sergeant in a training yard (movement, sprinting, combat, blocking and dodging, archery, riding and the menus). When it ends, the same world carries on as an endless sandbox game. It uses Knight difficulty and a Medium world, and shares the sandbox save slot.

There are five save slots, and each can hold a story or a sandbox game. The game also saves itself whenever the tab is hidden or closed. Saves can be downloaded as a file and loaded back from the main menu, so you can keep backups or move a game between a phone and a computer. The pause menu's *Save Slots* page lets you switch to another game without quitting, and deleting a slot (or all save data, in Settings) always asks first. Finishing the story turns that slot into a sandbox game, marked *Formerly Story*, so you can keep playing in the world you shaped.

## New game options

Before a new game you can set:

- **Difficulty**, in six levels: Peasant, Squire, Knight (the standard game), Champion, Warlord and Forsaken. Difficulty changes damage taken and dealt, enemy health, health and stamina regeneration, stamina costs, healing, how much gold you lose when you fall, your starting gear and gold, and how friendly the four kingdoms are at the start. Forsaken is an Ironman mode: you get one life, and dying erases the save.
- **World size**, from Extra Small to Extra Large. Larger worlds have more villages, ruins and bandit camps.
- **Homeland**, the kingdom you start in (sandbox only; the story always begins in Albion).
- **Wildlife** (scarce, normal or abundant), **day length** (short, normal or long), **starting season** (spring, summer, autumn or winter), and whether to **start with the map explored**.

## Controls

| Key | Action |
| --- | --- |
| WASD | Move |
| Mouse | Aim |
| Left click | Attack (hold to chain). With a bow: hold to draw, release to shoot |
| Right click | Block (not with a bow, which needs both hands) |
| R | Switch arrow type |
| Tab | Swap to your sidearm (drag a second weapon onto the Sidearm slot) |
| C | Special move: sword whirlwind, axe or greatsword crushing blow, spear lunge, piercing arrow. While blocking: shield bash |
| Space | Dodge (time it just as a blow lands to take no damage) |
| E | Interact |
| F | Mount / dismount / call horse |
| I | Inventory |
| M | Map |
| K | Diplomacy |
| J | Journal: quests and the chronicle |
| L | Journal: bestiary and lore |
| 1 / 2 / 3 | Eat food / drink potion / use bandage |
| Shift (hold) | Sprint, draining stamina |
| Q + left click | Hit characters who aren't hostile, such as villagers, guards or peaceful animals. Normally your attacks pass through them. Attacking people costs reputation and turns guards against you |
| G | Companions: follow me / hold position |
| P | Skills |
| Esc | Pause |

On the world map: right-click sets a waypoint, Shift+right-click pins a note (click a pin to edit it).

**Controller:** left stick moves, right stick aims, RT attacks or draws a bow, LT blocks, A dodges, X interacts, B mounts, Y swaps weapons, LB switches arrows, RB sprints, clicking the right stick uses your special, clicking the left stick commands companions, Back opens the map and Start pauses. In menus, the D-pad moves between buttons, A selects and B goes back.

**Phones and tablets:** touch controls turn on the first time you touch the screen. Play in landscape.
- **Moving:** drag anywhere on the left of the screen.
- **Combat:** ⚔ attacks (hold it to draw a bow, then let go to shoot), 🛡 blocks, ↻ dodges and ✦ uses your special move. Attacks and arrows aim at the nearest foe by themselves.
- **Interacting:** ✋ talks and interacts, or you can tap the prompt.
- **Small buttons:** sprint, mount, swap weapons, switch arrows, eat, drink a potion, call your companions, and go fullscreen.
- **Map:** drag to pan, pinch to zoom, tap a place for details, and press and hold to set a waypoint.

## Features

- A new map is generated for each game, with castles, villages, rivers, mountain passes, ruins, bandit camps and hidden locations to discover. Every new world is ringed by at least a league of open sea, and the ocean carries on past the edge of the map.
- Each kingdom has its own landscape: Albion's green countryside, Valoria's plains broken by desert (with cacti, scorpions, jackals and camels), Draven's mountain-walled forests with snowfields in its high country (snow pines, snowfall, snow wolves, ice bears and mountain goats), and Eldoria's swamps.
- Kingdom relations change on their own over time, and your actions affect them. The Diplomacy screen shows a live relationship graph and offers actions such as gifts, alliances, peace talks and swearing allegiance.
- Real-time combat with blocking, stamina and dodging, plus gear, horses and loot that change both your stats and how your knight looks.
- Bows, from the Short Bow to the Yew War Bow. Draw longer for more range and damage. Six arrow types: standard, broadhead (strong against beasts and bandits), bodkin (strong against armor), fire (burns), venom (poisons and slows) and frost (chills). The frost villages of Draven's snowfields make rimewood bows and frost arrows. Missed arrows can sometimes be picked back up (more often on easier difficulties); arrows that hit are lost. The Recurve Bow is built for horse archery.
- Tougher bandits: crossbowmen, and shieldbearers who block blows from the front (flank them, use a heavy blow or bodkin arrows).
- Legendary enchanted weapons, including a burning sword, a venom blade, a frost longsword, a life-draining axe and a lightning bow.
- Each castle sits at the heart of a busy royal city. It has cobbled streets and dirt alleys packed with townhouses, a market plaza with a fountain, the founder's statue and a row of stalls, a tourney field, and a great cathedral.
  - **Shops:** there are shops for every trade: a baker, butcher, fruit seller, fishmonger, cheesemonger, flower seller, apothecary, tailor, jeweller, bowyer, vintner and spice merchant.
  - **Taverns:** every city has a tavern with meals, rumours, rounds for the house and a dice table.
  - **Inns:** every city also has an inn. Its rooms range from a common-room bunk to a royal suite that leaves you rested, blessed and lucky, and the inn becomes your respawn point.
  - **People:** crowds of townsfolk, children, nobles and patrolling guards fill the streets, along with a bard, a town crier, a beggar and the cathedral's priest.
  - **Things to do:** you can knock on doors, toss a coin in the fountain for luck, read the statue's plaque, and pray or give alms at the cathedral.
- **Walk-in interiors:**
  - The tavern has a bar, a bard on stage, patrons and a dice table, and fills up at night.
  - The inn has rooms upstairs; the cathedral has pews, choristers and the priest at the altar.
  - The bakery, apothecary and jeweller are walk-in shops.
  - Your own house has a bed, your stash, a hearth and a trophy room displaying relics of the bosses and champions you have defeated.
- **Cities by day and night:** at dusk the shops shut and the streets empty, the night watch patrols with torches, the tavern fills up, and cutpurses come out.
- **Crime and justice:**
  - Assault, murder, pickpocketing and breaking in earn a bounty in that kingdom, shown on the HUD.
  - Guards who spot you offer three choices: pay the fine, serve a day or more in the cells (losing stolen goods and a little XP), or resist.
  - A thieves' guild recruits in taverns after dark. Its four jobs lead to lockpicks, a guild cloak, a fence for stolen goods, and a heist on the crown's tax wagon, unless you betray the guild to the captain.
- **Festivals:** a spring fair, a harvest market and a winter solstice fill the royal cities with decorations, stalls and games (an archery contest, pie eating, and at midwinter the strongman bell or a snowball toss at pop-up snowmen), with prizes to win. The garland, harvest charm, solstice lantern and wool scarf can be worn from your pack, and the lantern lights your way at night; so can the thieves' guild cloak.
- **Roadside encounters:** travelling the roads turns up short events with choices: a wounded knight, a lost child to escort home, a toll gang, a fleeing thief, a broken-down merchant, a pilgrim, a fortune teller and a deserter.
- **A nemesis:** a rival knight (a Sir or a Dame) ambushes you on the road every few days.
  - They grow stronger and earn epithets each time they beat you, and they taunt you about where they left you for dead.
  - After three defeats they demand a final duel, which ends with you killing, sparing or exiling them.
  - Spare them and they turn up every week or so as a friend, with a gift, news of places you have not found, or their sword at your side until nightfall.
- **World bosses:** every few weeks the Ashen Wyvern (fire breath) or the Hill Giant (boulders and ground slams) roams from village to village, ravaging them. It is marked on your map, and slaying it wins gold, the thanks of every crown, a legendary weapon and a trophy.
- **The Journal** (J or L, or from the pause menu): your quests, the chronicle of the realm, and:
  - **Bestiary:** every creature you see gets an entry, with its portrait, where it lives, what it drops, how many you have slain and tips for fighting it. Creatures you have not met appear as silhouettes.
  - **Lore:** 32 scrolls about the four kingdoms, the First King and the Ember Crown, the saints, the Ashen Circle and life on the road. They are found at ruins, camps and hidden places, in each cathedral's library and in dungeon guardians' hoards. The royal scribe in each city plaza sells copies of rare texts and, for a few coins, marks the nearest lost scroll on your map.
- Watchtowers guard the roads into each castle and the border crossings. Bowmen on the towers and castle walls shoot at bandits, enemy soldiers and outlaws.
- Quests, random world events and a day/night cycle.
- Seasons that change every six days: spring blossom, summer, golden autumn (cheap food) and snowy winter (slower travel off the roads, dear bread).
- Regional weather: rain and thunderstorms, morning fog in the marshes, sandstorms in the desert and blizzards in the snowfields. Fog and storms shorten how far enemies see and archers shoot; rain puts out fires.
- Carriages for fast travel between towns you have discovered (the castle coachman or any village signpost), for a fee by the league.
- Bounty boards on every signpost: bandit captains, wanted outlaws and dangerous beasts.
- Dungeons to explore underground: smugglers' caves, spider caves, crypts, abandoned mines and an ice cave in the snowfields. Each is a torch-lit maze with traps (spike plates, dart launchers, webs), side chests and a boss guarding a hoard. The first boss of each kind drops a legendary weapon. Saving underground returns you to the entrance.
- Live sieges: when a war would take a fort near you, or your liege is involved, armies march and fight for it while a capture meter fills. Fight for either side to earn reputation. Bandits may also raid a fort you own.
- Tournaments (sandbox): every eight days a castle holds a tourney. Win three bouts for gold, a rare prize and renown.
  - The second bout is a mounted joust over three passes.
  - Hold attack to lower your lance and let go as you meet: early for a shield strike (1 point), late for a helm strike (2), or at the last moment to unhorse your opponent and win outright. A meter shows your rival closing in on the blue, gold and red strike zones.
- **Horse races:** the royal stablemaster runs races to the next castle along the road, against three riders.
  - Entry costs 20 gold, and you need a horse.
  - Ride through every checkpoint flag in order; skip one or leave the course and you are disqualified. The top three win prizes, and the winner also gets a cup for the trophy room.
- **Ferries and ships:**
  - Ferrymen pole you across wide rivers far from any bridge, for 3 gold.
  - Seaside towns have a harbour with a ship, its captain and a deckhand. Ships sail to other harbours for a fare, and your horse and companions come along.
  - Voyages take a day or more. Beware storms that wash supplies overboard, and pirates waiting at the docks.
  - Both are marked on the map.
- Fiefs: sworn knights with reputation 80 can ask their ruler for a village to hold. Set its taxes, keep its people loyal (feasts help, raids hurt) and collect its income every week.
- Skills: a point every level for Swordsmanship, Archery, Riding, Leadership and Trade.
- Companions and soldiers: hire spearmen, bowmen and knights from castle captains (daily pay), or recruit four named sellswords found in the villages, including a healer and a venom archer. Named companions are knocked down, never killed.
- Property: buy a house in a friendly village (rest, a safe stash, and you wake there if you fall), or restore a ruined fort that pays a daily income and can be garrisoned.
- Crafting: fletch every arrow type at market benches, and at the royal forges improve gear up to Masterwork or bind a dungeon relic into a blade to enchant it.
- Fishing at little jetties on rivers, lakes and the coast (buy a rod at a village market), and hermits in the wilds who sell tonics, training and secrets.
- **Settings:**
  - Battery Saver (30 fps, fewer particles, lighter weather) and optional chattering NPC voices with their own volume.
  - Accessibility: rebindable keys, text size, reduced flashing and motion, and colourblind-friendly colours, with a different pattern for each kingdom on the map.
- About 45 music tracks, all generated in code: rotating day and night overworld songs, combat and boss themes, a village, castle and fort theme for each kingdom, and story-mode themes. The music changes with where you are and what you're doing.

## Achievements and statistics

56 achievements are shared by every game in your browser (see the main menu or pause menu). The pause menu's *Your Journey* page tracks time played, distance, kills, arrows, dungeons, sieges, tourneys and more, and the story's closing screen shows it too.

## License

[MIT](LICENSE)
