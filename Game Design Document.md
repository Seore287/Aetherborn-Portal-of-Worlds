# Game Design Document
## Game Concept
This is a 3D game situated in a strange and ancient environment. The player navigates dimensional regions using ancient portals. The game features exploration, puzzle solving, and a fascinating narrative. 
Players adopt an Aetherborn, traversing numerous realms connected by ancient doorways. The game also provides a distinctive experience by combining fantasy and science fiction themes, 
showcasing diverse realms that encourage exploration and discovery. The universe consists of several lands linked via volatile portals. The protagonist is assigned the responsibility of reestablishing 
stability in the world. These realms are experiencing chaos due to a mysterious factor precipitating the breakdown of the Aether. The player’s quest includes revealing the truth, engaging with creatures from several 
realms, and making decisions that influence the narrative. The player embodies Nyxen, an Aetherborn survivor capable of elemental manipulation and dimensional traversal. The player will navigate ethereal terrains, 
combat with numerous adversaries, tackle in-game puzzles, and uncover hidden truths behind the portals. 

### Key Features
- Interdimensional Travel: Players navigate via diverse realms using the secret portals. 
- Elemental Powers: Players harness legendary manipulation to resolve environmental challenges crucial for game advancement and narrative progression. 
- Dynamic Combat: Players partake in rapid battles employing a variety of weapons and skills.  
- Non-Linear Story: Diverse trajectories within the game and choices that influence the plot. 
- Environmental Challenges: Overcome diverse puzzles to unlock new regions and advance through the narrative.

### ​Genre/Theme
Primary Genre: Adventure 
Secondary Genre: Puzzle, Role Playing, and Exploration

### Platform
PC (Windows, macOS) 
Console (PlayStation, Xbox)

### ​Target Audience
15 and above 
Gamers who like immersive games and exploration.

## Gameplay Mechanics
###  ​Core Gameplay
Players will engage in real-time combat with enemies and solve puzzles. The game’s progression is tied to unlocking new abilities, travelling through portals, and defeating enemies guarding the new realms. 

### ​Characters
- Nyxen (Main Character): a trooper born from the Aether, able to wield elemental 
powers and dimensional abilities.
- Elder Protectors: These are ancient creatures protecting the balance of the 
realms. 
- Antagonists: a force seeking to manipulate the instability of the portals.

### ​EnemyAI
In-game antagonists vary from mindless entities indigenous to di erent realms to sentient beings protecting key areas. The NavMesh system and several AI components adjust to the player’s tactics, 
with some enemies using coordinated attacks and exploiting environmental advantages. 

### Gameplay Elements
- Combat and Strategy: Portals may be used in combat in specific situations. Nyxen can use portals to achieve a tactical edge by transitioning between dimensions to evade threats, ambush adversaries,or employ novel battle methods informed by the distinct characteristics of each world. 
- Dimensional Traversal: Portals enable players to traverse e ortlessly between realms with distinct physical and elemental characteristics. By transitioning between realms, gamers can reach regions that may be
concealed or unattainable in one dimension but accessible in another. A bridge may be present in one dimension but not another, necessitating players to transition between realms to advance. 
- Environmental Manipulation: Certain game problems necessitate the player's clever use of portals. They can modify the environmental state upon activation, including transforming terrain, opening doors,
or disclosing concealed pathways. Players must think critically about the timing and location for opening portals to manipulate objects or resolve multi-dimensional puzzles.

### Game Objects
The Fabled Hunter (A Legendary Tracker) 
- Role: A reclusive hunter who knows how to track and tame magical creatures.
- Appearance: A rugged traveler wearing an enchanted wolf pelt, carrying a bow infused with Aether energy.
- Interaction:
Teaches the player how to track rare creatures in the forest.
Offers hunting or tracking quests.
Helps the player tame Aether Creatures to use as temporary allies.

The Hollow Monarch (The Forgotten King) 
- Role: The spectral remnant of a ruler whose kingdom once thrived in the Aether Forest but was lost to a cataclysm.
- Appearance: A regal, ghostly figure clad in broken armor, holding a translucent blade.
- Lore Contribution:
Tells the tragic tale of his fallen people and why they vanished.
May have insight into an ancient Aetheric catastrophe.
Knows the origins of the Great Enemy (Morvain?).
- Interaction:
Grants a quest to restore a lost monument in his honor.
Might test the player’s worthiness through a battle or puzzle.
If honored, he gives the player his royal sigil, unlocking secret areas.

#### Game Enemies
Aether Spiders 
- Large, glowing, or crystalline spiders that can shoot web-like energy strands or phase in and out of sight. 
#### Attributes:  
- Health: Moderate 
- Speed: High 
- Damage: Medium 

Crystal Golems 
- Backstory: Ancient stone-and-crystal constructs, possibly guarding secrets deep in the forest.
#### Attributes:  
- Health: Extremely High 
- Speed: Low 
- Damage: High 

### Game Weapons
Ancient Axe
#### Attributes: 
- Damage: 50 - 70 
- Elemental Effect: 10 - 20 
- Range: Medium 
- Speed: Fast 
#### Behaviour:  
- Upon attacking, it can intricate an elemental detonation corresponding to the elemental a inity of the current realm.

## Player Controls
- Movement: WASD / Left Joystick 
- Jump: Space / RT button 
- Combat: Right or Left mouse / B button 
- Abilities: X / A button
- Interact: I / X button
- Camera Control: Mouse / Right Joystick 

## Scoring 
- Health Points: The life bar displays the player’s health, which depletes when damage is taken from game adversaries or hazards. 
- Life Points: The player possesses a finite number of life points which indicate the number of fatalities permissible before respawning at the most recent checkpoint. 

## Inventory
- Weapons are acquired during gameplay and can be stored in an inventory system.
- Special goods, such as artefacts, bestow upon the player distinct skills or lore related information. 
- Healing supplies such as potions or medkits can be equipped and used during combat.

## Level Overview
### Locations
- Aether Forest: a realm of nature overgrown with ancient ruins. 
- Crimson Desert: a barren desert a licted by fiery storms.
- Skyward City: a floating city built with sophistication. 
- Eclipse Ruins: a dark, crumbling fortress home to powerful game enemies.

### Puzzles
Each realm will have puzzles that require manipulating elemental forces, moving objects, and interacting with portals to progress.

## Sound and Music
### Overall Goals
- The sound within the game enhances the immersion of various realms, each having a unique ambience based on the environment.

### Sound effects and Music
- Music: Each realm has its theme that blends orchestral and electronic tones to evoke mystery and awe 
- Sound Effects: Portal sounds, weapon clashes, and elemental powers should feel impactful and immersive. 

## Graphical User Interface
### ​Maps and Views
- Mini map: a scaled-down view of immediate surroundings, indicating other NPCs and interactable objects. It is there to aid players navigate without needing to open the world map.
- World Map: a visual representation of all realms (Aether Forest, Crimson Desert, Skyward City, Eclipse Ruins) that the player can explore. Each area is marked with critical locations like portals, bosses, and puzzle spots. 
- Exploration View: the view may change between third-person or isometric, showcasing the surroundings and giving a clear sense of scale when navigating different environments. 
- HUD Elements: this includes the health bar, ability status icons and a Trailshard counter.

### ​Heads Up Display (HUD)
- Health Bar:  a visual display of the player’s current health, which will likely be positioned at the top-left corner of the screen. This will deplete when taking damage and regenerate with healing items.
- Power Indicator:  this shows the current elemental power being used and its status, like cooldown time or energy bar, which depletes as it is in use.
- Quest/Objective Indicator: displays the current mission or task that the player needs to complete.
  
### ​Menus
- Main Menu: Options for starting a new game, loading a saved game, settings, and credits.
- Pause Menu: Resume game, options, controls, and quit to main menu.
- Settings Menu: adjusts game settings like sound levels and graphic options.
- Inventory Menu:  a detailed display where players can view artefacts, weapons, and consumables.
- Quest Log: this keeps track of the player’s progress throughout the game, keeping a list of completed missions or side quests.
