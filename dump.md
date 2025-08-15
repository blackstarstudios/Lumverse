# Titles

escaper of hell
challenger of god
final light



Power Class Distribution (8 Billion Total Beings)
Class	Population	Percentage	Description
F	7,160,910,000	89.51%	Civilians, children, non-combatants.
D	751,081,422	9.39%	Novice adventurers, guards, apprentices.
C	78,778,163	0.98%	Seasoned adventurers, skilled craftsmen, minor mages.
B	8,262,751	0.10%	Elite warriors, renowned guild leaders, powerful mages.
A	866,649	0.01%	Legendary heroes, archmages, rulers of small nations.
S	90,899	0.0011%	Demigods, ancient dragons, beings capable of destroying cities.
S+	9,534	0.00012%	Near-divine entities, elder liches, cosmic horrors.
U	1,000	0.000012%	True gods, primordial forces, omnipotent beings.
Key Features
Wealth-Gap Analogy:

F-class (89.5%): Equivalent to the "bottom 90%" in wealth inequality.

D-class (9.4%): The "middle class" of adventurers and skilled workers.

A-class and above (0.01%–0.000012%): The "1%" of power, with U-class beings rarer than billionaires.

Exponential Drop-off:
Each tier has ~8.5× fewer beings than the previous one. For example:

F → D: 7.16B → 751M (9.5× fewer)

B → A: 8.2M → 866K (9.5× fewer)

S+ → U: 9,534 → 1,000 (9.5× fewer)

Gameplay Implications:

Players start at D-class (novice) and work toward B/A-class (elite).

S/U-class entities are plot-critical forces, not common enemies.

Only 1,000 U-class beings exist globally, making divine encounters extraordinarily rare.

'''
# Define total population and classes
total_population = 8_000_000_000
classes = ['F', 'D', 'C', 'B', 'A', 'S', 'S+', 'U']  # Weakest to strongest

# Starting parameters (U-class = godlike beings)
base_population = 1000  # Initial U-class population
num_classes = len(classes)
ratio = 6.81  # Found through iterative calculation

# Generate population distribution
populations = []
current = base_population
for _ in range(num_classes):
    populations.append(int(current))
    current *= ratio

# Reverse to get F -> U order and scale to 8B
populations = populations[::-1]
scale_factor = total_population / sum(populations)
scaled_populations = [int(p * scale_factor) for p in populations]

# Final distribution
power_distribution = {
    'F': 4_800_000_000,  # 60% - Peasants/civilians
    'D': 705_000_000,    # 8.8% - Trained guards
    'C': 103_500_000,    # 1.3% - Veteran soldiers
    'B': 15_200_000,     # 0.19% - Elite warriors
    'A': 2_230_000,      # 0.028% - Heroes
    'S': 327_000,        # 0.0041% - Legendary champions
    'S+': 48_000,        # 0.0006% - Demigods
    'U': 7_000           # 0.00009% - True gods
}

# Access population counts
print(f"Peasants (F-class): {power_distribution['F']:,}")
print(f"True Gods (U-class): {power_distribution['U']:,}")

# Calculate party encounter odds
party_level = 'B'
encounter_chance = {
    level: (count / total_population)*100 
    for level, count in power_distribution.items()
}
'''


Item Grades
----------------


Item Power Class Distribution (80 Billion Total Items)
Class	Number of Items	Percentage	Description
F	71,609,100,000	89.51%	Everyday items: apples, ropes, common swords, basic clothes
D	7,510,814,220	9.39%	Sturdy tools, quality weapons, minor potions, journeyman gear
C	787,781,630	0.98%	Masterwork weapons, rare herbs, enchanted trinkets
B	82,627,510	0.10%	Unique magic items, relic tools, advanced potions
A	8,666,490	0.01%	Legendary weapons, artifacts, philosopher’s stones
S	908,990	0.0011%	World-famous relics, ancient tomes, dragonforged arms
S+	95,340	0.00012%	Mythic items, primordial stones, reality-bending artifacts
U	10,000	0.000012%	Divine relics, godforged tools, items of creation/destruction
Key Features
Mundane items (F-class): The overwhelming majority—basic tools, food, simple weapons, and everyday gear.

Adventurer’s gear (D, C, B): Quality and rare items, magical gear, and unique relics—rare but attainable for heroes.

Legendary & divine (A, S, S+, U):

A-class: Legendary items sought by kingdoms and guilds.

S-class: Iconic, world-altering relics—known by name in every land.

S+: Items of myth, possibly unique or lost to history.

U-class: Divine artifacts, each with world-shaping power; only a handful exist.

Summary Table
Class	% of Items	Example Items
F	89.5%	Apple, iron dagger, plain tunic
D	9.4%	Steel sword, healing potion, sturdy boots
C	1.0%	Masterwork bow, rare elixir, enchanted ring
B	0.10%	Flaming sword, cloak of invisibility, relic key
A	0.01%	Excalibur, philosopher’s stone, crown of kings
S	0.0011%	Orb of the Ancients, dragonforged armor
S+	0.00012%	Staff of Worlds, primordial heart
U	0.000012%	Godforge, chalice of creation, world seed


Exploration & Discovery
 Wanderlust: Visit 10 unique locations.

 Cartographer: Map 50% of the game world.

 Dungeon Delver: Explore your first dungeon.

 Seeker of Secrets: Discover 25 hidden rooms.

 Pathfinder: Unlock all fast-travel points.

 Skywatcher: Witness a meteor shower.

 Underdark Tourist: Survive a journey through the deepest caverns.

 Portal Hopper: Use 10 magical portals.

 Lorekeeper: Collect 100 books/scrolls.

 Eternal Pilgrim: Walk 1,000 miles in-game.

Combat & Survival
 First Blood: Win your first battle.

 Dragon Slayer: Defeat a dragon.

 Untouchable: Win a fight without taking damage.

 Pacifist: Complete a dungeon without killing anything.

 Crit Master: Land 100 critical hits.

 Zombie Bane: Defeat 100 undead.

 Elementalist: Kill enemies with all 5 elemental damage types.

 Last Stand: Survive with 1 HP.

 Boss Rush: Defeat 10 bosses.

 One-Man Army: Solo a raid-level encounter.

Crafting & Economy
 Apprentice Smith: Craft your first weapon.

 Master Artisan: Reach max crafting skill.

 Merchant Prince: Earn 10,000 gold from trading.

 Hoarder: Collect 1,000 items.

 Alchemist’s Spark: Brew 50 potions.

 Enchanting Novice: Enchant an item.

 Gemcutter: Perfectly cut 10 rare gems.

 Black Market: Sell a stolen item to a vendor.

 Philanthropist: Donate 1,000 gold to a temple.

 Monopoly: Own all shops in a city.

Quests & Story
 Hero of the Realm: Complete the main story.

 Side Quest Fanatic: Finish 50 side quests.

 Diplomat: Resolve a conflict peacefully.

 Betrayer: Side with the villain in a key quest.

 Cursebreaker: Lift a legendary curse.

 Prophesized One: Fulfill an ancient prophecy.

 Master Detective: Solve a murder mystery.

 Bard’s Tale: Hear 50 unique stories from NPCs.

 Royal Favor: Complete a quest for a king/queen.

 Eldritch Horror: Survive an encounter with a cosmic entity.

Social & Factions
 Friend to All: Reach max reputation with 3 factions.

 Notorious: Become hated by a major faction.

 Guildmaster: Lead a guild.

 Matchmaker: Arrange an NPC marriage.

 Spy Network: Uncover a treasonous plot.

 Puppetmaster: Manipulate a ruler into war.

 Traitor’s Reward: Betray your guild.

 Festival Goer: Attend 5 seasonal festivals.

 Drunkard: Get kicked out of a tavern.

 Legendary Bard: Have a song written about you.

Magic & Mysticism
 Arcane Initiate: Learn your first spell.

 Ritualist: Perform a forbidden ritual.

 Necromancer’s Apprentice: Raise your first undead.

 Druid’s Bond: Befriend a wild animal.

 Divine Intervention: Be resurrected by a god.

 Rune Master: Carve 50 magical runes.

 Mindflayer: Psychically dominate an enemy.

 Weather Mage: Summon a storm in battle.

 Planar Traveler: Visit the Feywild/Shadowfell.

 Wish Granter: Use a Wish spell.

Stealth & Thievery
 Pickpocket Pro: Steal 100 items.

 Ghost: Complete a heist undetected.

 Vault Cracker: Rob a royal treasury.

 Shadow Walker: Sneak past 50 enemies.

 Poisoner: Apply poison 25 times.

 Master Thief: Steal a legendary artifact.

 Escape Artist: Flee 50 battles.

 Doppelgänger: Impersonate an NPC.

 Trap Disarmer: Disarm 100 traps.

 Ninja Vanish: Escape a boss fight via stealth.

Humor & Easter Eggs
 Dinner’s Ready: Burn a meal while cooking.

 Oops...: Accidentally attack a friendly NPC.

 Mimic Hugger: Open 10 mimic chests.

 Fashion Disaster: Wear mismatched armor.

 Cat Herder: Collect 10 stray cats.

 Pun Master: Use a pun in dialogue.

 Potato Hoarder: Collect 500 potatoes.

 Rock Collector: Carry 100 “useless” rocks.

 Dancing Fool: Use /dance in a serious cutscene.

 Cheese Lord: Discover the Secret Cheese Dimension.

Epic Challenges
 Godslayer: Defeat a deity in combat.

 Dragon Emperor: Hoard 1,000,000 gold.

 Immortal: Survive 1,000 in-game years.

 Worldshaper: Reshape the landscape with magic.

 Chosen of the Ancients: Unlock all hidden lore.

 Arena Champion: Win 100 arena battles.

 Planeswalker: Visit all alternate dimensions.

 Harbinger of Chaos: Unleash an apocalypse.

 Legendary Crafter: Forge a mythic-tier item.

 True Hero: Unlock all achievements.


 status effects
---------------

Here’s a simplified list with **one-word status names** and categorized into two types:  

---

 *1. Regular Status Points* clear "good" state
  `Starving <-> Hunger <-> Full`  
  `Dehydrated <-> Thirst <-> Quenched`  
  `Exhausted <-> Energy <-> Energized`  
  `Insane <-> Sanity <-> Focused`  
  `Injured <-> Health <-> Healthy`  
  `Overburdened <-> Weight <-> Lightfooted`  
  `Filthy <-> Hygiene <-> Clean`  
  `Suffocating <-> Oxygen <-> Aerated`  
  `Sick <-> Immunity <-> Resilient`  
  `Depleted <-> Mana <-> Overflowing`  

 *2. Bipolar Status Points* two dangerous extremes
  `Freezing <-> Temperature <-> Burning`  
  `Dizzy <-> Balance <-> Vertigo`  
  `Crushed <-> Pressure <-> Exploding`  
  `Poisoned <-> Toxicity <-> Overdosed`  
  `Wild Surges <-> Magic Stability <-> Stagnant`  
  `Depressed <-> Emotions <-> Manic`  
  `Hypoglycemic <-> Blood Sugar <-> Hyperglycemic`  
  `Irradiated <-> Radiation <-> Mutating`  

Thresholds to trigger effects (e.g., `Temperature` below 20% = `Freezing`, above 80% = `Burning`).  

Bleeding <-> Blood Integrity <-> Coagulated
Radiation Sickness <-> Cellular Health <-> Radiant Vitality
Broken Bones <-> Skeletal Integrity <-> Reinforced Structure
Concussion <-> Neural Stability <-> Cognitive Precision
Sunburn <-> Skin Resilience <-> Solar Adaptation
Asphyxiation <-> Oxygen Levels <-> Aerated
Vertigo <-> Spatial Awareness <-> Grounded
Tremors <-> Motor Control <-> Steady Hands
Malnutrition <-> Nutrient Balance <-> Optimal Nourishment
Hallucinations <-> Perception Accuracy <-> True Sight
Necrosis <-> Tissue Vitality <-> Cellular Regeneration
Petrification <-> Bodily Flexibility <-> Stoneform Immunity
Suffocation <-> Air Supply <-> Breathe Easy
Lacerations <-> Dermal Integrity <-> Scarless Healing
Hemorrhage <-> Vascular Integrity <-> Clotting Factor
Sepsis <-> Blood Purity <-> Sterile System
Rabies <-> Neural Health <-> Viral Immunity
Dysentery <-> Gut Flora <-> Digestive Harmony
Pneumonia <-> Lung Capacity <-> Respiratory Efficiency
Frostbite <-> Extremity Circulation <-> Polar Adaptation
Heat Exhaustion <-> Core Temperature <-> Thermal Balance
Hypoxia <-> Oxygen Saturation <-> High-Altitude Adaptation
Tetanus <-> Muscle Relaxation <-> Contraction Control
Gangrene <-> Limb Vitality <-> Necrotic Resistance
Psionic Overload <-> Mental Shielding <-> Telepathic Clarity
Soul Drain <-> Spiritual Essence <-> Divine Connection
Arcane Burn <-> Mana Channels <-> Mystic Conduit
Reality Warping <-> Existential Anchor <-> Cosmic Alignment
Time Sickness <-> Temporal Sync <-> Chrono-Harmony
Gravity Crush <-> Inertial Resistance <-> Weightless Grace
Sonic Shock <-> Auditory Processing <-> Harmonic Resonance
Sensory Deprivation <-> Neural Input <-> Hyperawareness



Real-World Industries
Primary Sector (Raw Materials)
Agriculture (farming, crop production)

Animal Husbandry (ranching, livestock)

Fishing & Aquaculture

Forestry & Logging

Mining (coal, metals, gemstones)

Oil & Gas Extraction

Water Supply

Secondary Sector (Manufacturing & Construction)
Food & Beverage Manufacturing

Textile & Apparel Manufacturing

Chemical Manufacturing

Pharmaceutical Manufacturing

Construction (residential, commercial, infrastructure)

Automotive Manufacturing

Aerospace Manufacturing

Electronics Manufacturing

Shipbuilding

Steel & Metalworking

Furniture Manufacturing

Paper & Pulp Industry

Printing & Publishing

Plastics & Rubber Production

Industrial Equipment Manufacturing

Tertiary Sector (Services)
Retail & E-commerce

Wholesale & Distribution

Hospitality (hotels, lodging)

Food Services (restaurants, catering)

Health Care & Social Assistance

Education & Training

Financial Services (banking, insurance, investment)

Real Estate

Professional Services (legal, accounting, consulting)

Transportation (road, rail, air, maritime)

Warehousing & Logistics

Information Technology & Software

Telecommunications

Utilities (electricity, gas, water)

Media & Broadcasting

Entertainment & Leisure (theaters, amusement parks)

Sports & Recreation

Arts & Culture

Government & Public Administration

Defense & Security

Waste Management & Remediation

Environmental Services

Quaternary & Quinary Sectors (Knowledge, Innovation, Leadership)
Scientific Research & Development

Biotechnology

Artificial Intelligence & Machine Learning

Data Processing & Cloud Computing

Nonprofit & Humanitarian Services

Policy & Advocacy

Think Tanks & Research Institutes

Fantasy-World-Specific Industries
Magic & Arcane
Enchanting (magical item creation)

Spellcrafting & Scrollmaking

Potion Brewing & Alchemy

Magical Creature Husbandry (griffons, dragons, etc.)

Rune Carving & Glyphcraft

Mana Extraction & Distribution

Magical Education (wizard academies)

Divination & Prophecy Services

Cursebreaking & Hex Removal

Magical Security & Warding

Adventuring & Heroics
Dungeon Delving & Treasure Recovery

Monster Hunting & Bounty Services

Mercenary Guilds

Relic Appraisal & Restoration

Artifact Trading

Supernatural & Spiritual
Clerical & Divine Services (temple rites, blessings)

Spirit Mediumship & Necromancy

Resurrection & Healing Services

Exorcism & Demonology

Faith-based Pilgrimage Services

Exotic Materials & Crafting
Dragon Taming & Dragonriding

Skyship Building & Maintenance

Elemental Binding & Elemental Energy Harvesting

Golem Construction

Fae/Fey Goods Trading

Mythic Metalworking (mithril, adamantine, etc.)

Crystal Harvesting

Guilds & Secret Societies
Thieves’ Guild Operations

Assassins’ Guild

Spy Networks & Espionage

Smuggling & Black Market

Entertainment & Culture (Fantasy)
Bardic Colleges & Performance Troupes

Magical Festivals & Tournaments

Storytelling & Lorekeeping

Arena Combat (gladiators, magical duels)

Illusionist Shows

Transportation & Trade (Fantasy)
Portal Transportation Services

Airship & Skybarge Lines

Magical Courier Services

Beast of Burden Breeding (griffons, dire wolves)

Otherworldly & Planar
Planar Travel Agencies

Feywild/Faerie Trade

Underworld Ferrymen

Astral Navigation & Charting

Unique Fantasy Services
Curse Insurance

Magical Patent Offices

Legendary Beast Conservation

Time Manipulation Services

Weather Control Guilds


Inventory
-----------
Certainly! Here’s a simplified version of the inventory UI where all functionality is implemented as basic standalone functions (not inside a class), working with the previously defined inventory system (a 2D list of [item_name, count] with empty slots as [None, 0]).

python
class Item:
    """Class holding item names as class variables."""
    sword = "Sword"
    shield = "Shield"
    potion = "Potion"
    bow = "Bow"
    arrow = "Arrow"
    helmet = "Helmet"
    armor = "Armor"
    boots = "Boots"
    ring = "Ring"
    amulet = "Amulet"

# Initialize empty inventory: 10 slots, each [None, 0]
inventory = [[None, 0] for _ in range(10)]

# Globals for tracking favorites, crafted items, durability, quick slots, and location
favorites = set()
crafted_items = set()
durability = {}
quick_slots = [None] * 4
at_blacksmith = False
at_shop = False
show_advanced = False

# Example item attributes
item_attributes = {
    Item.sword: {"type": "Weapon", "grade": 3, "value": 100},
    Item.shield: {"type": "Armor", "grade": 2, "value": 80},
    Item.potion: {"type": "Consumable", "grade": 1, "value": 10},
    Item.bow: {"type": "Weapon", "grade": 2, "value": 90},
    # Add more as needed
}

def clean_inventory(inv):
    """Replace slots with zero or less count with [None, 0]."""
    for slot in inv:
        if slot[0] is not None and slot[1] <= 0:
            slot[0], slot[1] = None, 0

def display_inventory(inv):
    clean_inventory(inv)
    print("\n=== INVENTORY ===")
    for idx, (item, count) in enumerate(inv, 1):
        if item is None:
            print(f"[{idx}] Empty: 0")
        else:
            fav_mark = "*" if item in favorites else " "
            quick_mark = "(Q)" if item in quick_slots else ""
            print(f"[{idx}] {fav_mark}{item}: {count} {quick_mark}")
    print("\nActions: (U)se (I)nspect (M)ove (D)rop (T)ransfer (O)ptions (Q)uit")

def get_slot(prompt):
    try:
        slot = int(input(prompt)) - 1
        if 0 <= slot < len(inventory):
            return slot
    except ValueError:
        pass
    print("Invalid slot number.")
    return None

def use_item(slot):
    item, count = inventory[slot]
    if item is None or count <= 0:
        print("No item to use in this slot.")
        return
    if item == Item.potion:
        inventory[slot][1] -= 1
        print(f"You used a {item}. Remaining: {inventory[slot][1]}")
    else:
        print(f"Cannot use {item} right now.")

def inspect_item(slot):
    item, count = inventory[slot]
    if item is None:
        print("Empty slot.")
        return
    dur = durability.get(item, 100)
    print(f"Item: {item}\nCount: {count}\nDurability: {dur}%")
    attrs = item_attributes.get(item)
    if attrs:
        print(f"Type: {attrs['type']}, Grade: {attrs['grade']}, Value: {attrs['value']}")

def move_item(from_slot):
    to_slot = get_slot("Move to slot number: ")
    if to_slot is None or to_slot == from_slot:
        print("Invalid destination slot.")
        return
    if inventory[from_slot][0] in favorites:
        print("Cannot move a favorited item.")
        return
    inventory[from_slot], inventory[to_slot] = inventory[to_slot], inventory[from_slot]
    print(f"Moved item from slot {from_slot+1} to {to_slot+1}.")

def drop_item(slot):
    item, _ = inventory[slot]
    if item is None:
        print("Slot already empty.")
        return
    if item in favorites:
        print("Cannot drop a favorited item.")
        return
    inventory[slot] = [None, 0]
    print(f"Dropped item from slot {slot+1}.")

def transfer_item(slot):
    print("Transfer function not implemented yet.")

def toggle_advanced():
    global show_advanced
    show_advanced = not show_advanced
    print(f"Advanced options {'enabled' if show_advanced else 'disabled'}.")

def favorite_item(slot):
    item, _ = inventory[slot]
    if item is None:
        print("No item in this slot to favorite.")
        return
    favorites.add(item)
    print(f"Favorited {item}.")

def repair_item(slot):
    if not at_blacksmith:
        print("You must be at a blacksmith to repair items.")
        return
    item, _ = inventory[slot]
    if item is None:
        print("No item to repair in this slot.")
        return
    current_dur = durability.get(item, 100)
    if current_dur >= 100:
        print(f"{item} does not need repair.")
        return
    durability[item] = 100
    print(f"{item} repaired to 100% durability.")

def sell_item(slot):
    if not at_shop:
        print("You must be at a shop to sell items.")
        return
    item, count = inventory[slot]
    if item is None:
        print("No item to sell in this slot.")
        return
    attrs = item_attributes.get(item)
    if attrs:
        value = attrs['value'] * count
        print(f"Sold {count}x {item} for {value} gold.")
        inventory[slot] = [None, 0]
    else:
        print(f"Cannot sell {item}.")

def rename_item(slot):
    item, _ = inventory[slot]
    if item not in crafted_items:
        print(f"{item} cannot be renamed (not crafted).")
        return
    new_name = input("Enter new name: ").strip()
    if new_name:
        inventory[slot][0] = new_name
        print(f"Item renamed to {new_name}.")

def toggle_quick_slot(slot):
    item, _ = inventory[slot]
    if item is None:
        print("No item in this slot.")
        return
    if item in quick_slots:
        quick_slots[quick_slots.index(item)] = None
        print(f"Removed {item} from quick slots.")
    else:
        for i in range(len(quick_slots)):
            if quick_slots[i] is None:
                quick_slots[i] = item
                print(f"Added {item} to quick slot {i+1}.")
                break
        else:
            print("No empty quick slots available.")

def advanced_options(choice, slot):
    if choice == 'f':
        favorite_item(slot)
    elif choice == 'r':
        repair_item(slot)
    elif choice == 's':
        sell_item(slot)
    elif choice == 'n':
        rename_item(slot)
    elif choice == 'x':
        toggle_quick_slot(slot)
    else:
        print("Unknown advanced option.")

def inventory_ui_loop():
    global at_blacksmith, at_shop
    at_blacksmith = True  # For demo, set these as needed
    at_shop = True

    while True:
        display_inventory(inventory)
        choice = input("Choose action: ").strip().lower()
        if choice == 'q':
            print("Exiting inventory.")
            break
        elif choice == 'o':
            toggle_advanced()
            continue

        slot = get_slot("Select slot number: ")
        if slot is None:
            continue

        if choice == 'u':
            use_item(slot)
        elif choice == 'i':
            inspect_item(slot)
        elif choice == 'm':
            move_item(slot)
        elif choice == 'd':
            drop_item(slot)
        elif choice == 't':
            transfer_item(slot)
        elif show_advanced:
            advanced_options(choice, slot)
        else:
            print("Invalid action or toggle advanced options with 'O'.")

if __name__ == "__main__":
    # Demo inventory setup
    inventory[0] = [Item.sword, 2]
    inventory[1] = [Item.potion, 5]
    inventory[2] = [Item.bow, 1]
    crafted_items.add(Item.sword)  # Example crafted item

    inventory_ui_loop()
Explanation:
All UI logic and operations are implemented as independent functions.

Global variables track favorites, crafted items, durability, quick slots, and player location.

Inventory is a 2D list [item_name, count] with empty slots as [None, 0].

clean_inventory is called before display.

Basic actions: Use, Inspect, Move, Drop, Transfer (placeholder).

Advanced actions (toggle with O): Favorite, Repair, Sell, Rename, Quick slot toggle.

Input is slot-based (1-10).

Simple terminal prompts and feedback.

Save and Load
-----------

In player.py or game_state.py

import json

def save_game(state, filename="saves/savegame.json"):
    with open(filename, "w") as f:
        json.dump(state, f, indent=4)

def load_game(filename="saves/savegame.json"):
    with open(filename, "r") as f:
        return json.load(f)
Or, as a method:

python
class Player:
    # ... player attributes and methods ...

    def save(self, filename="saves/player_save.json"):
        with open(filename, "w") as f:
            json.dump(self.__dict__, f)

    @classmethod
    def load(cls, filename="saves/player_save.json"):
        with open(filename, "r") as f:
            data = json.load(f)
        player = cls()
        player.__dict__.update(data)
        return player
Summary Table
Folder/File	What Goes Here
/saves/	The actual save files (e.g., player1.json)
player.py/game_state.py	The save/load functions themselves
save_manager.py	(Optional) Centralized save/load logic



- Map screen displays
[Forest] [Forest] [Forest] [Forest]
[Forest] [Forest] [Forest] [Forest]
[Forest] [Forest] [ You  ] [Forest]
[Forest] [Forest] [Forest] [Forest]

- time (30 min/1 hr interval)
    global tile = 
    continental tile = 
    national tile = 
    regional tile = 
    local tile = 2 tiles/hr
    internal tile = 6 tiles/hr

Absolutely! Let’s streamline the table for your game context:

- **1 internal tile = 10 minutes of travel**
- **1 hour = 60 minutes**
- So, in 1 hour, a player can traverse:  
  $$ \frac{60}{10} = 6 $$ internal tiles per hour

Given this, and your previous info that a **local tile = 2 tiles/hr**, we can infer that larger tiles take more time to cross. Let’s build the table so that each level is 3× larger than the previous (since 6/2 = 3):

---

## Streamlined Travel Table

| Level         | Travel Time per Tile | Tiles per Hour   |
|---------------|---------------------|------------------|
| Internal      | 10 min              | 6                |
| Local         | 30 min              | 2                |
| Regional      | 1.5 hr (90 min)     | 0.67             |
| National      | 4.5 hr              | 0.22             |
| Continental   | 13.5 hr             | 0.074            |
| Global        | 40.5 hr             | 0.025            |

---

### How to Read This Table

- **Internal tile:** 10 minutes to cross, so 6 per hour.
- **Local tile:** 30 minutes to cross, so 2 per hour.
- **Regional tile:** 1.5 hours to cross, so 0.67 per hour.
- **National tile:** 4.5 hours to cross, so 0.22 per hour.
- **Continental tile:** 13.5 hours to cross, so 0.074 per hour.
- **Global tile:** 40.5 hours to cross, so 0.025 per hour.

**Each level is 3× larger (in travel time) than the previous.**

Let me know if you'd like to adjust the scaling or need more details for your game!


Common Fantasy Equipment Categories
1. Weapons
Swords, axes, bows, spears, daggers, etc.

2. Armor
Helmets, shields, breastplates, gauntlets, boots, etc.

3. Adventuring Gear
Ropes, grappling hooks, bedrolls, tents, lanterns, torches, backpacks, water skins.

4. Tools & Kits
Lockpicking kits, alchemist kits, smithing tools, herbalism kits, healer’s kits, fishing rods, cooking sets.

5. Magical Items
Rings, amulets, cloaks, boots, belts, stones, wands, scrolls, potions, enchanted gear.

6. Consumables
Potions, food, rations, bandages, antitoxins, scrolls.

7. Mounts & Travel Gear
Saddles, carts, wagons, boats, animal feed, travel cloaks, maps, compasses.

8. Trade Goods & Crafting Materials
Ingots, herbs, gems, fabrics, leather, rare components.

9. Household & Domestic Items
Cooking utensils, cleaning tools, candles, buckets, brooms.

10. Treasure & Valuables
Gems, coins, jewelry, art objects.

Why Categorize?
Clarity: Makes it easier for players to find what they need.

Balance: Helps GMs ensure variety and avoid redundancy.

Role Definition: Supports different character roles (e.g., thief with lockpicks, healer with medical kit).

Inventory Management: Simplifies encumbrance and slot systems.

Example: Categorizing a Few Items
Category	Example Items
Adventuring Gear	Rope, lantern, bedroll, tent
Tools & Kits	Lockpick set, smithing tools, healer’s kit
Magical Items	Ring of Feather Fall, Cloak of Invisibility
Consumables	Healing potion, rations, antitoxin
Travel Gear	Saddle, cart, compass, map
Crafting Materials	Iron ingot, rare herbs, dragon scales
Tips for Your Game
Group by function/use (e.g., "Tools" for anything that enables a skill or task).

Create subcategories for large groups (e.g., "Kits" under "Tools").

Keep categories broad for easy reference, but detailed enough to cover unique items.

Consider mechanical impact: If an item is only flavor, it might go in a "Miscellaneous" or "Personal Effects" group.

Review existing RPGs for inspiration and adapt to your setting and mechanics


- items can be dropped in a tile
    wont despawn for a day
- dungeons are procedurally generated
- character creation has multiple different uis for description, benefit, debuffs)
    race
    ambition
- item window shows an item all information
- work on an item id system
- blacksmith takes a day to repair items
  takes a few days for custom orders
- tames, companions, party (or raid party) all appear in menu
- homes can be bought or built depending on nation
- all beings gave a REP


Secular/National Holidays
New Year's Day (January 1)

Independence Day (varies by country; e.g., July 4 in the USA)

Constitution Day

National Day

Republic Day

Flag Day

Labor Day / International Workers' Day (May 1 in many countries)

Memorial Day

Veterans Day / Remembrance Day

Thanksgiving (fourth Thursday in November in the USA, October in Canada)

Election Day

King's/Queen's Birthday (varies by country)

Bastille Day (France, July 14)

Australia Day (January 26)

Canada Day (July 1)

Russia Day (June 12)

Liberation Day (varies)

Unity Day (varies)

Victory Day (varies)

National Foundation Day (varies)

Armed Forces Day

Religious Holidays
Christian
Christmas (December 25)

Easter (date varies)

Good Friday

Palm Sunday

Ash Wednesday

Lent

Pentecost

Epiphany / Three Kings Day (January 6)

All Saints' Day (November 1)

St. Patrick's Day (March 17)

Jewish
Passover (Pesach)

Rosh Hashanah (Jewish New Year)

Yom Kippur

Hanukkah

Purim

Sukkot

Muslim
Ramadan (month of fasting)

Eid al-Fitr (end of Ramadan)

Eid al-Adha (Festival of Sacrifice)

Islamic New Year

Hindu
Diwali

Holi

Navratri

Raksha Bandhan

Durga Puja

Ganesh Chaturthi

Makar Sankranti

Buddhist
Vesak (Buddha Day)

Magha Puja

Asalha Puja

Sikh
Vaisakhi

Gurpurab

Hola Mohalla

Baháʼí
Naw-Rúz

Ridván (1st, 9th, and 12th Days)

Birth of Bahá'u'lláh

Birth of the Báb

Pagan/Neopagan
Samhain / Halloween (October 31)

Yule / Winter Solstice

Imbolc / Candlemas

Ostara / Spring Equinox

Beltane / May Day

Litha / Summer Solstice

Lughnasadh / Lammas

Mabon / Autumn Equinox

Cultural and Observance Days
Valentine's Day (February 14)

Mother's Day (varies)

Father's Day (varies)

Groundhog Day (February 2)

St. Andrew's Day (Scotland, November 30)

St. Lucia’s Day (Scandinavian countries, December 13)

Lunar New Year / Chinese New Year (date varies)

Mid-Autumn Festival (China, date varies)

Carnival / Mardi Gras (date varies)

Day of the Dead / Dia de los Muertos (Mexico, November 1-2)

Halloween (October 31)

Black Friday (day after Thanksgiving, USA)

Cyber Monday (Monday after Thanksgiving, USA)

Singles' Day (China, November 11)

Friendship Day (varies)

Teacher's Day (varies)

Administrative Professionals Day (varies)

Earth Day (April 22)

International Women's Day (March 8)

Pride Month (June)

Juneteenth (June 19, USA)

International Workers' Day (May 1)

Notable US Federal Holidays (as an example):
New Year’s Day

Birthday of Martin Luther King, Jr.

Washington’s Birthday (Presidents’ Day)

Memorial Day

Independence Day

Labor Day

Columbus Day / Indigenous Peoples' Day

Veterans Day

Thanksgiving Day

Christmas Day


$1 = Apple
$10 = Leather Pouch
$100 = Healer’s Potion
$1,000 = Fine Warhorse
$10,000 = Modest Cottage
$100,000 = Small Village Estate
$1,000,000 = Grand Manor or Guildhall
$10,000,000 = Fully Outfitted Merchant Ship
$100,000,000 = Castle with Lands
$1,000,000,000 = Duchy or Small Fiefdom
$10,000,000,000 = Kingdom’s Annual Treasury
$100,000,000,000 = Legendary Relic or Royal Army
$1,000,000,000,000 = Crown of a Great Empire
$10,000,000,000,000 = Entire Continent’s Wealth
$100,000,000,000,000 = Mythic Artifact of World-Shaping Power

Wealth Distribution
-----------------------

Here is the readjusted economic breakdown for your fantasy world, factoring in a smaller gap between superpowers and powerful nations, and accounting for 15% of the world’s money being lost or unaccounted for (e.g., in dungeons):

Parameters
Total world money circulation: 100 trillion

Lost/unaccounted money (15%): 15 trillion

Available for nations (85%): 85 trillion

Number of countries: 23

Superpowers: 5 nations

Powerful Nations: 10 nations

Small Nations: 5 nations (stable but small)

Poor Nations: 3 nations (struggling economies)

GDP Distribution
Category	Number of Nations	GDP per Nation	Total GDP Contribution
Superpowers	5	8.6 trillion	43 trillion
Powerful Nations	10	3.3 trillion	33 trillion
Small Nations	5	1.5 trillion	7.5 trillion
Poor Nations	3	0.5 trillion	1.5 trillion
Lost/Unaccounted	—	—	15 trillion
World Total	23		100 trillion
Percentages of World Wealth
Superpowers: 43% of total wealth (43T/100T)

Powerful Nations: 33%

Small Nations: 7.5%

Poor Nations: 1.5%

Lost/Unaccounted: 15%

Category Descriptions
Superpowers (5):
Dominant global powers with vast resources, advanced magic/technology, and military might.
Examples: Dragon-ruled empires, celestial theocracies, planar trade hubs.

Powerful Nations (10):
Prosperous states with strong economies and regional influence.
Examples: Merchant republics, dwarven holds, elven forest kingdoms.

Small Nations (5):
Stable, compact nations with modest economies.
Examples: Island city-states, fortified mountain clans, enchanted enclaves.

Poor Nations (3):
Economically struggling, often due to war, curses, or resource scarcity.
Examples: Plague-ridden baronies, bandit-ravaged wastelands, cursed regions.

Lost/Unaccounted Wealth (15T):
Treasure hoarded in dungeons, dragon lairs, or lost to time.

Key Features
Balanced Hierarchy: Superpowers (43%) and powerful nations (33%) are closer in collective wealth, reflecting a multipolar world.

Clear Distinction: Small nations (1.5T each) are stable but limited, while poor nations (0.5T each) face significant challenges.

Adventure Hooks:

A poor nation hires players to recover lost treasure from a dragon’s hoard.

A small nation seeks alliances to avoid being absorbed by a superpower.

Example Realistic Rebalance:
Category	Number	GDP per Nation	Total GDP	% of World
Superpowers	5	8.5T	42.5T	42.5%
Powerful Nations	10	2.125T	21.25T	21.25%
Small Nations	5	1.25T	6.25T	6.25%
Poor Nations	3	0.5T	1.5T	1.5%
Lost/Unaccounted	—	—	15T	15%
World Total	23	—	100T	100%

- dropped money is placed in
    small coin pouch <=100
    coin pouch       <=500
    large coin pouch <=1,000
    small coin chest <=5,000
    coin chest       <=10,000
    large coin chest <=50,000
    small coin pile  <=100,000
    coin pile        <=500,000
    large coin pile  <=1,000,000



1. Assault (Melee Damage Dealers)
Focused on close-quarters combat and high burst damage.

Berserker

Duelist

Gladiator

Shadowblade

Battlemaster

Reaver

Blade Dancer

Savage

Warmonger

Blood Knight

Executioner

Samurai

Pit Fighter

Hellion

Rageborn

Warchief

Zealot

Chainbreaker

Ravager

Juggernaut

2. Tank (Defenders)
Absorb damage and protect allies.

Guardian

Bulwark

Fortress

Shieldbearer

Ironclad

Bastion

Stonewarden

Aegis

Colossus

Vanguard

Palisade

Rampart

Sentinel

Wardragon

Earthshaker

Titan

Immovable

Ironbound

Unbreakable

Paragon

3. Ranged (Physical/Magical)
Attack from a distance with precision or spells.

Sniper

Archer

Spellbow

Cannoneer

Grenadier

Stormcaller

Pyromancer

Frostweaver

Arcane Marksman

Artillerist

Crossbowmaster

Sharpshooter

Geomancer

Thunderlord

Sunstalker

Void Archer

Tinkerer

Flamecaster

Icewarden

Celestial Sniper

4. Support (Buffs/Debuffs)
Enhance allies or weaken enemies.

Bard

Tactician

Enchanter

Hexblade

Oracle

Herald

Luminary

Runemaster

Soulbinder

Mindbreaker

Aura Warden

Cursebringer

Harmonist

Sigil Sage

Fatespinner

Chantweaver

Glyphbearer

Resonance Mage

Doomcaller

Hopebringer

5. Healer (Restoration)
Focus on healing and sustaining allies.

Cleric

Lifeweaver

Divine Beacon

Vitalist

Renewer

Lightbringer

Sanctifier

Mender

Restoration Druid

Spirit Channeler

Purifier

Gracewarden

Soulmender

Radiant Priest

Herbologist

Resurgent

Revivifier

Harmony Sage

Celestial Healer

Pacifist

6. Control (Crowd Control)
Manipulate the battlefield with stuns, roots, or area denial.

Chronomancer

Icewarden

Earthbinder

Puppeteer

Gravity Mage

Stormlord

Webspinner

Mindflayer

Voidcaller

Entangler

Frostlock

Chain Warden

Illusionist

Tempest

Paralyzer

Dreadnought

Chaos Weaver

Stasis Mage

Trapmaster

Domination Priest

7. Summoner (Minions/Pets)
Command creatures or constructs.

Beastmaster

Necromancer

Golemancer

Soul Conjurer

Pack Leader

Elementalist

Familiar Binder

Hive Queen

Spirit Warden

Automaton Lord

Phantom Caller

Swarm Herald

Dragon Tamer

Clockwork Engineer

Shadow Summoner

Celestial Harbinger

Fungal Overlord

Demonologist

Totemcaller

Starforger

8. Stealth (Assassins/Scouts)
Strike from shadows or gather intelligence.

Nightblade

Infiltrator

Ghostwalker

Whisper Assassin

Saboteur

Shadowdancer

Stalker

Vanishblade

Silent Death

Trickster

Veilwalker

Phantom

Ambusher

Duskstalker

Cloakbearer

Poisonblade

Eclipse

Mirage

Voidstep Assassin

Unseen

9. Elementalist (Element-Based)
Wield fire, ice, lightning, or earth.

Pyromancer

Cryomancer

Stormcaller

Geomancer

Aquamancer

Magma Lord

Tempest

Frostfire Sage

Thundersoul

Obsidian Shaper

Vortex Weaver

Ashbringer

Tidecaller

Blizzardborn

Emberheart

Quakebringer

Galvanist

Solaris

Glacial Warden

Volcanic Fury

10. Hybrid (Multi-Role)
Combine two or more roles.

Spellsword

Arcane Archer

Battlemage

Paladin

Shadow Knight

Druid

Rune Knight

Hexblade

Blood Mage

War Priest

Monk

Warden

Technomancer

Chaos Knight

Soulknife

Sky Hunter

Frostfire Knight

Stormforged

Celestial Blade

Voidwalker

11. Necromancer (Undead/Dark Magic)
Raise and command the dead.

Bone Lord

Lich

Grave Caller

Plaguebearer

Soul Harvester

Wightmancer

Death Knight

Fleshshaper

Crypt Keeper

Reanimator

Blood Necromancer

Wraithbinder

Corpse Collector

Dark Ritualist

Souleater

Carrion Master

Pestilence Lord

Dread Summoner

Boneweaver

Shadow Lich

12. Engineer (Gadgets/Traps)
Use technology or mechanical tools.

Tinkerer

Alchemist

Grenadier

Clockwork Engineer

Trapsmith

Mechanist

Siege Master

Gadgeteer

Steam Knight

Pyrotechnician

Arcane Machinist

Bombardier

Gnomish Inventor

Gearforged

Automaton Smith

Firework Artificer

Rocket Jockey

Chain Engineer

Tesla Mage

Gravity Forger

variable_name = Archetype(name, type, effect, tree)
Where:

variable_name is a lowercase, underscore-separated version of the archetype name

name is the display name of the archetype

type is the category (e.g., "Assault", "Tank", etc.)

effect is a brief description of the primary effect or role

tree is the skill or advancement tree (can be the same as type or a relevant specialization)

Assault Archetypes
python
berserker = Archetype("Berserker", "Assault", "Unleashes rage for massive melee damage", "Fury")
duelist = Archetype("Duelist", "Assault", "Excels at single-target melee combat", "Precision")
gladiator = Archetype("Gladiator", "Assault", "Crowd control and arena tactics", "Arena")
shadowblade = Archetype("Shadowblade", "Assault", "Strikes from shadows for critical hits", "Shadow Arts")
battlemaster = Archetype("Battlemaster", "Assault", "Leads with tactical melee prowess", "Tactics")
reaver = Archetype("Reaver", "Assault", "Feeds on pain to increase damage", "Bloodlust")
blade_dancer = Archetype("Blade Dancer", "Assault", "Agile, flowing melee combos", "Dance of Blades")
savage = Archetype("Savage", "Assault", "Wild attacks that ignore defense", "Primal")
warmonger = Archetype("Warmonger", "Assault", "Thrives in large-scale battles", "Warcry")
blood_knight = Archetype("Blood Knight", "Assault", "Sacrifices health for power", "Blood Magic")
executioner = Archetype("Executioner", "Assault", "Deals bonus damage to weakened foes", "Judgment")
samurai = Archetype("Samurai", "Assault", "Disciplined, precise melee strikes", "Bushido")
pit_fighter = Archetype("Pit Fighter", "Assault", "Dirty tricks and survival tactics", "Brawler")
hellion = Archetype("Hellion", "Assault", "Channels demonic fury", "Inferno")
rageborn = Archetype("Rageborn", "Assault", "Gains strength as health drops", "Rage")
warchief = Archetype("Warchief", "Assault", "Buffs allies while attacking", "Leadership")
zealot = Archetype("Zealot", "Assault", "Fanatical attacks with holy fervor", "Zeal")
chainbreaker = Archetype("Chainbreaker", "Assault", "Excels at breaking free and retaliating", "Liberation")
ravager = Archetype("Ravager", "Assault", "Devastates with area melee attacks", "Destruction")
juggernaut = Archetype("Juggernaut", "Assault", "Unstoppable force in melee", "Momentum")
Tank Archetypes
python
guardian = Archetype("Guardian", "Tank", "Shields allies and absorbs damage", "Protection")
bulwark = Archetype("Bulwark", "Tank", "Immovable and resilient", "Fortitude")
fortress = Archetype("Fortress", "Tank", "Creates defensive barriers", "Bastion")
shieldbearer = Archetype("Shieldbearer", "Tank", "Excels with shields and blocks", "Shield Mastery")
ironclad = Archetype("Ironclad", "Tank", "Heavily armored and tough", "Iron Will")
bastion = Archetype("Bastion", "Tank", "Stands ground and buffs defense", "Defender")
stonewarden = Archetype("Stonewarden", "Tank", "Earth magic for defense", "Earth Ward")
aegis = Archetype("Aegis", "Tank", "Projects magical shields", "Aegis Arts")
colossus = Archetype("Colossus", "Tank", "Massive and hard to move", "Giant's Strength")
vanguard = Archetype("Vanguard", "Tank", "Leads the charge, draws fire", "Vanguard")
palisade = Archetype("Palisade", "Tank", "Sets up defensive positions", "Bulwark")
rampart = Archetype("Rampart", "Tank", "Absorbs and reflects damage", "Reflection")
sentinel = Archetype("Sentinel", "Tank", "Watches for threats, counters attacks", "Sentinel's Vigil")
wardragon = Archetype("Wardragon", "Tank", "Dragon-themed resilience", "Dragon Ward")
earthshaker = Archetype("Earthshaker", "Tank", "Shakes ground to disrupt foes", "Earthquake")
titan = Archetype("Titan", "Tank", "Colossal endurance and strength", "Titanic")
immovable = Archetype("Immovable", "Tank", "Cannot be displaced", "Immovability")
ironbound = Archetype("Ironbound", "Tank", "Bound by magical iron", "Iron Binding")
unbreakable = Archetype("Unbreakable", "Tank", "Never falters under pressure", "Resolve")
paragon = Archetype("Paragon", "Tank", "Inspires allies with defense", "Inspiration")
Ranged Archetypes
python
sniper = Archetype("Sniper", "Ranged", "Long-range precision shots", "Sharpshooting")
archer = Archetype("Archer", "Ranged", "Versatile with bows", "Archery")
spellbow = Archetype("Spellbow", "Ranged", "Combines archery and magic", "Spell Archery")
cannoneer = Archetype("Cannoneer", "Ranged", "Uses heavy ranged weapons", "Artillery")
grenadier = Archetype("Grenadier", "Ranged", "Throws explosives", "Demolition")
stormcaller = Archetype("Stormcaller", "Ranged", "Casts lightning from afar", "Storm Magic")
pyromancer = Archetype("Pyromancer", "Ranged", "Launches fire spells", "Fire Magic")
frostweaver = Archetype("Frostweaver", "Ranged", "Casts ice and frost spells", "Frost Magic")
arcane_marksman = Archetype("Arcane Marksman", "Ranged", "Magic-infused projectiles", "Arcane Archery")
artillerist = Archetype("Artillerist", "Ranged", "Deploys mechanical ranged weapons", "Engineering")
crossbowmaster = Archetype("Crossbowmaster", "Ranged", "Expert with crossbows", "Crossbowry")
sharpshooter = Archetype("Sharpshooter", "Ranged", "Extreme accuracy at distance", "Precision")
geomancer = Archetype("Geomancer", "Ranged", "Controls earth from afar", "Earth Magic")
thunderlord = Archetype("Thunderlord", "Ranged", "Commands thunder and lightning", "Thunder")
sunstalker = Archetype("Sunstalker", "Ranged", "Solar-powered ranged attacks", "Solar Magic")
void_archer = Archetype("Void Archer", "Ranged", "Fires arrows of void energy", "Void Archery")
tinkerer = Archetype("Tinkerer", "Ranged", "Uses gadgets and traps", "Gadgetry")
flamecaster = Archetype("Flamecaster", "Ranged", "Throws fire from a distance", "Pyromancy")
icewarden = Archetype("Icewarden", "Ranged", "Ranged ice control", "Cryomancy")
celestial_sniper = Archetype("Celestial Sniper", "Ranged", "Channels cosmic energy into shots", "Celestial")
Support Archetypes
python
bard = Archetype("Bard", "Support", "Buffs allies with music and magic", "Performance")
tactician = Archetype("Tactician", "Support", "Improves team strategy", "Tactics")
enchanter = Archetype("Enchanter", "Support", "Buffs and debuffs with enchantments", "Enchanting")
hexblade = Archetype("Hexblade", "Support", "Curses enemies, aids allies", "Hexes")
oracle = Archetype("Oracle", "Support", "Foresees and guides", "Prophecy")
herald = Archetype("Herald", "Support", "Boosts morale and stats", "Inspiration")
luminary = Archetype("Luminary", "Support", "Radiates beneficial auras", "Luminescence")
runemaster = Archetype("Runemaster", "Support", "Uses runes for buffs", "Runecraft")
soulbinder = Archetype("Soulbinder", "Support", "Links souls for shared effects", "Soul Magic")
mindbreaker = Archetype("Mindbreaker", "Support", "Disrupts enemy minds", "Psionics")
aura_warden = Archetype("Aura Warden", "Support", "Projects protective auras", "Aura Magic")
cursebringer = Archetype("Cursebringer", "Support", "Inflicts curses on enemies", "Cursing")
harmonist = Archetype("Harmonist", "Support", "Balances and harmonizes party", "Harmony")
sigil_sage = Archetype("Sigil Sage", "Support", "Draws sigils for effects", "Sigilcraft")
fatespinner = Archetype("Fatespinner", "Support", "Manipulates fate for allies", "Fateweaving")
chantweaver = Archetype("Chantweaver", "Support", "Empowers with chants", "Chanting")
glyphbearer = Archetype("Glyphbearer", "Support", "Uses glyphs for buffs", "Glyphcraft")
resonance_mage = Archetype("Resonance Mage", "Support", "Amplifies magic effects", "Resonance")
doomcaller = Archetype("Doomcaller", "Support", "Foretells and hastens doom", "Doom Magic")
hopebringer = Archetype("Hopebringer", "Support", "Inspires hope and resilience", "Hope")
Tank Archetypes
(Already provided above, but included for completeness.)

Healer Archetypes
python
cleric = Archetype("Cleric", "Healer", "Restores health and cures ailments", "Divine")
lifeweaver = Archetype("Lifeweaver", "Healer", "Manipulates life energy", "Life Magic")
divine_beacon = Archetype("Divine Beacon", "Healer", "Channels divine healing", "Divinity")
vitalist = Archetype("Vitalist", "Healer", "Boosts vitality and heals wounds", "Vitality")
renewer = Archetype("Renewer", "Healer", "Restores and rejuvenates", "Renewal")
lightbringer = Archetype("Lightbringer", "Healer", "Heals with holy light", "Light Magic")
sanctifier = Archetype("Sanctifier", "Healer", "Purifies and heals", "Sanctification")
mender = Archetype("Mender", "Healer", "Mends wounds quickly", "Mending")
restoration_druid = Archetype("Restoration Druid", "Healer", "Heals with nature's power", "Restoration")
spirit_channeler = Archetype("Spirit Channeler", "Healer", "Channels spirits to heal", "Spirit Magic")
purifier = Archetype("Purifier", "Healer", "Removes curses and heals", "Purification")
gracewarden = Archetype("Gracewarden", "Healer", "Protects and heals with grace", "Grace")
soulmender = Archetype("Soulmender", "Healer", "Heals soul wounds", "Soul Magic")
radiant_priest = Archetype("Radiant Priest", "Healer", "Radiates healing energy", "Radiance")
herbologist = Archetype("Herbologist", "Healer", "Uses herbs for healing", "Herbalism")
resurgent = Archetype("Resurgent", "Healer", "Recovers from defeat to heal others", "Resurgence")
revivifier = Archetype("Revivifier", "Healer", "Revives fallen allies", "Revival")
harmony_sage = Archetype("Harmony Sage", "Healer", "Heals through harmony", "Harmony")
celestial_healer = Archetype("Celestial Healer", "Healer", "Heals with cosmic energy", "Celestial")
pacifist = Archetype("Pacifist", "Healer", "Heals and avoids harm", "Pacifism")
Control Archetypes
python
chronomancer = Archetype("Chronomancer", "Control", "Manipulates time to control foes", "Time Magic")
icewarden = Archetype("Icewarden", "Control", "Freezes and slows enemies", "Cryomancy")
earthbinder = Archetype("Earthbinder", "Control", "Immobilizes with earth magic", "Geomancy")
puppeteer = Archetype("Puppeteer", "Control", "Controls enemies' actions", "Puppetry")
gravity_mage = Archetype("Gravity Mage", "Control", "Manipulates gravity fields", "Gravity Magic")
stormlord = Archetype("Stormlord", "Control", "Controls weather and storms", "Storm Magic")
webspinner = Archetype("Webspinner", "Control", "Traps with magical webs", "Webcraft")
mindflayer = Archetype("Mindflayer", "Control", "Overwhelms minds", "Psionics")
voidcaller = Archetype("Voidcaller", "Control", "Banishes or restrains with void energy", "Void Magic")
entangler = Archetype("Entangler", "Control", "Roots and restrains enemies", "Nature")
frostlock = Archetype("Frostlock", "Control", "Locks enemies in ice", "Cryomancy")
chain_warden = Archetype("Chain Warden", "Control", "Binds with magical chains", "Chain Magic")
illusionist = Archetype("Illusionist", "Control", "Confuses with illusions", "Illusion")
tempest = Archetype("Tempest", "Control", "Unleashes chaotic storms", "Tempest")
paralyzer = Archetype("Paralyzer", "Control", "Stuns and paralyzes", "Paralysis")
dreadnought = Archetype("Dreadnought", "Control", "Intimidates and slows foes", "Intimidation")
chaos_weaver = Archetype("Chaos Weaver", "Control", "Spreads magical chaos", "Chaos")
stasis_mage = Archetype("Stasis Mage", "Control", "Freezes time and motion", "Stasis")
trapmaster = Archetype("Trapmaster", "Control", "Sets and triggers traps", "Trapping")
domination_priest = Archetype("Domination Priest", "Control", "Controls with divine power", "Domination")
Summoner Archetypes
python
beastmaster = Archetype("Beastmaster", "Summoner", "Commands animal companions", "Beast Mastery")
necromancer = Archetype("Necromancer", "Summoner", "Raises undead minions", "Necromancy")
golemancer = Archetype("Golemancer", "Summoner", "Creates golem constructs", "Golemcraft")
soul_conjurer = Archetype("Soul Conjurer", "Summoner", "Summons spirits", "Soul Magic")
pack_leader = Archetype("Pack Leader", "Summoner", "Leads a pack of beasts", "Pack Tactics")
elementalist = Archetype("Elementalist", "Summoner", "Summons elemental beings", "Elementalism")
familiar_binder = Archetype("Familiar Binder", "Summoner", "Binds magical familiars", "Familiar Magic")
hive_queen = Archetype("Hive Queen", "Summoner", "Commands insect swarms", "Hive Mind")
spirit_warden = Archetype("Spirit Warden", "Summoner", "Guards with spirit allies", "Spirit Magic")
automaton_lord = Archetype("Automaton Lord", "Summoner", "Controls mechanical minions", "Automation")
phantom_caller = Archetype("Phantom Caller", "Summoner", "Summons phantoms", "Phantasm")
swarm_herald = Archetype("Swarm Herald", "Summoner", "Leads magical swarms", "Swarm Magic")
dragon_tamer = Archetype("Dragon Tamer", "Summoner", "Commands dragons", "Dragon Mastery")
clockwork_engineer = Archetype("Clockwork Engineer", "Summoner", "Builds clockwork minions", "Clockwork")
shadow_summoner = Archetype("Shadow Summoner", "Summoner", "Summons shadow creatures", "Shadow Magic")
celestial_harbinger = Archetype("Celestial Harbinger", "Summoner", "Summons celestial beings", "Celestial")
fungal_overlord = Archetype("Fungal Overlord", "Summoner", "Commands fungal minions", "Fungal Magic")
demonologist = Archetype("Demonologist", "Summoner", "Summons demons", "Demonology")
totemcaller = Archetype("Totemcaller", "Summoner", "Summons totems for aid", "Totem Magic")
starforger = Archetype("Starforger", "Summoner", "Summons cosmic entities", "Cosmic")


Organizations are globally recognized organizations that manage and take care of their specific focus of guild type

## Known Organizations

__Verteyes International Merchants Association__
> The organization that regulates all merchant guilds that is based in Raija

__Redheart United Adventurers Association__
> The organization that regulates all adventurer guilds that is based in Altin

__3Mercs Mercenaries League__
> The organization that regulates all mercenary companies that is based in Khasu

__Organics Tamers Association__
> The organization that regulates all taming guilds that is based in Ferrent

__Alue Runineers Society__
> The organization that regulates all runineers guilds that is based in Yumland

__Grayam Smiths Union__
> The organization that regulates all smithing guilds that is based in Metnir

__Blue Skies Allied Mages Society__
> The organization that regulates all mage guilds that is based in Alphi

__Redbaan Pirates__
> The infamous pirate crew that claims dominance over the most profitable seas. The military struggles to suppress such a group

__Filibuster__
> The pirate hunting crew that specializes in just that, pirate hunting. This group is famous for ending the most infamous of crews on the high seas

__9Head__
> A group without a single face. The ill-famed assasination guild operates from the shadows, taking on requests only for the "worthy". The group got its name from its original 9 founders

__Prey Raid__
> A well known air marauder crew that established itself in the Eastern hemisphere of Lumhuin. They specialize in pillaging aerial transportion vehicles

__ __
> Raiji's naval order is the famous naval unit that bravely fought off the staggering Khasian naval forces, despite being outnumbered, during the Great Sand War

__ __
> Khasu's Army

__ __
> Alphi's Air Force

__Little God Gang__
> Notorious bandit gang that terrorizes towns and cities, led by the infamous "Little God"

__Cyphon__
> The famous blackmarket guild that is known as the "Supplier of the Underworld". They claim that they have every item of the known world

__Black Iris Guild__
> A well known secret of a guild. Not many know of the name, little know where to go, and fewer know what to ask. But those who do, learned that if it exists, Black Iris knows. For the right price...the knowledge of this information guild can belong to you

__Goldsin Guild__
> Explorer guild

__Xoul__
> A bounty hunting guild that gained their prestige from bringing in big time criminals from all across Lumhuin

__Antiarch__
> "And when the nightstar reached it's peak, its light turned a deep white, beckoning the coming of the True Mad God". This verse from the Antibook, the scripture of Antiarch, embodies the groups true ideal: Bringing forth the being kown as the true 

__ARX__
> Vigilante organization

__Yordworks__
> Famous Forge business

__Godslayer Guild__
> Dungeon raiding guild

__Helliant Guild__
> Monster slaying guild

__Dragrion Guild__
> Lizard Taming guild

__Grey Blood__
> Undead slaying guild

__Voaustier__
> Noble clothing brand

__Runkitz Lab__
> Rune engineering lab

__Barri & Miel Guild__
> Merchant guild

__Wolves__
> Khasian Empire secret knight order that serves the emperor directly

__Apostles__
> Thesian holy knight commanders that report directly to the Queen

____
> Organized robbery crew

____
> Arms dealing crew

____
> Famous restaurant 

____
> Jewelry Company

____
> Magic Academy

____
> Knight Academy

____
> Rune Academy

__ __
> Bankers

__ __
> Arena Hosts

__ __
> Hospital

__ __
> Museum

__ __
> Auctioners

__ __
> Theatre Company

__ __
> Tavern

__ __
> Lawyers

__ __
> Head church

__ __
> Slave trading company

__ __
> Brothel

__ __
> Private Army for hire

__ __
> Casino

__Oracle__
> International authority

__ __
> Spa resort

__ __
> Theater

__ __
> Drug lord organization

__ __
> Golem fight organization 

__ __
> Underground monster fight operation

__ __
> Musical group

__ __
> farming company

__ __
> Religious Assassination Order 

__ __
> Anti-Beastman Hunting Group

__ __
> Pro Human Racist group

__ __
> Council of Mages

__ __
> Top 100 strongest ranking

__ __
> Famous Alchemy shop

__ __
> Alchemist Academy

__ __
> Martial Academy

__ __
> Law School

__ __
> Major University

__ __
> Famous coach carriages

__ __
> Famous tame breeders/sellers

__ __
> Wine Brewer

__ __
> Alcohol brewer 

__ __
> Association of South Kingdoms

__ __
> Association of Central Kingdoms

__ __
> Association of Eastern Kingdoms

__ __
> Association of Northern Kingdoms

__ __
> Association of Wester Kingdoms

__ __
> Bakery

__ __
> Bar Tavern

__ __
> Hotel

__ __
> National Marina

__ __
> Meat Butcher/Shop

__ __
> Bakery

__ __
> Caravan Escort Guild

__ __
> Church Alliance

__ __
> Fancy Boat shot


Sunfell
Autian
Feua
Ehona Plum
Ekryaim
Wyntolm
Balawyn
Yaaonhel
Aloore

## Northern Continent
### Alphi, Nickname
Climate, Landscape: Very Cold, White Alps
Goverment: Magocracy - Mage society
Lordmage: Rheflyn, Horus Chronus (Azureen)
Top Guardmage: Obeah, Glaucius (Azureen) 
Capital: 
Economy, Export: $$, Grimoires
Population: Azureen, Avikin, Replikin
Attraction(s): Magic Academy, Magical Advances, Aurora Lights

### Colmere
Climate, Landscape: Very Cold, Glacial Desert
Goverment: Despotism - Dictatorship
Dictator: Tosul, The King of 100 Treasures (Azureen)
Top Guard: Liann, Gate of Colmere (Polar Clan)
Capital: Glisscar
Economy, Export: $$$$, Rare minerals
Population: Azureen, Polar Clan, Ivor 
Attraction(s): Mineral mines, rare gems, Sustainability Domes

### Torfrost
Climate, Landscape: Very Cold, Snowtops 
Goverment: Kleptocracy - Pirate Society
Ruler: Kinnard, The Crimson King (Ivor)
Top Maurader: Borkus, The Northern Beast (Orc) 
Capital: Tulmir
Economy, Export: $$, Resold loot
Population: Ivorans, Orcs, Polar Clan, Wolf Clan
Attraction(s): Unlawful country

## Northwestern Continent
### Yaleick
Climate, Landscape: Chilly, Darkwoods
Goverment: 
Leader:
Top Soldier:
Capital: Monogoro
Economy, Export:
Population: Dark Elves
Attraction(s):

### Godgeram
Climate, Landscape: Cool, Talltrees
Goverment:
Leader:
Top Soldier:
Capital:
Economy, Export: $$, Strong tallwood lumber
Population:
Attraction(s): Gigantic historic trees

### Druen
Climate, Landscape: Warm, Lostlands
Goverment: Divided Anarchy - Sectioned off to different Faction Leaders 
Leader:
Top Soldier:
Capital: Ighura
Economy, Export: $, 
Population:
Attraction(s): Lwaless nation, Debauchery central

### Halerane
Climate, Landscape: Hot, Moltwrens
Goverment: 
Leader:
Top Soldier:
Capital:
Economy, Export: , Rare earth materials
Population:
Attraction(s):

## Southwestern Continent

### Baterie
Climate, Landscape: Hot, Wilds
Goverment: Stratocracy - Chief Leadership
Head Chieftain: Geshrew, The Greech Wing (Parrot Clan)
Top Warrior: Pseosippe, The Whistling Spear (Parakere)
Capital: Wajado
Economy, Export: $$, Artifacts
Population: Parakere, Avikin
Attraction(s): Lost ruins
⁃ Birdkin, orcs
⁃ Ancient world Ruins

### Gerkin
Climate, Landscape: Warm, Bogwamps 
Goverment: Tribalism - Tribe Leadership
Overlord: Igbias, The Devil King (Tazmanian Clan) 
Top Warrior: Cabal, The Black Middle (Gator Clan)
Capital: Shawtrie
Economy, Export: $, Mercenaries
Population: Replikin, Rodikin, Insectikin
Attraction(s): Mercenary bands and savage handlings

## Central Continent
### Metnir
Climate, Landscape: Cold, Grand Mounts
Goverment: Autocracy - Skill Leadership
King: Daggril, The King Mountain (Dwarf)
Top Knight: Wearld, The Golem Slayer (Dwarf)
Capital: Urgerand
Economy, Export: $$$, Rare metals 
Population: Dwarves, Avikin
Attraction(s): Blacksmithing and craftmanship

### Ferrent
Climate, Landscape: Cool, Calmplains
Goverment: Monarchy
King: Eliyas, The Dueling King (Laudquin)
Top Knight: Gualtier, The First Sword (Laudquin)
Capital: Wyvillan
Economy, Export: $$$, Politics
Population: Laudquin, 
Attraction(s): Cultural mixing

### Theses
Climate, Landscape: Chilly, Runhills
Goverment: Theocracy - Church Leadership
Holy Crown: Bryra, The Golden Saintius (Lauquin)
Top Paladin: Phanuel, The White Knight (Marron)
Capital: Oprea
Economy, Export: $$, Religon
Population: Laudquin
Attraction(s): Large Central Church

### Evern
Climate, Landscape: Cool, Magiwoods
Goverment: Gerontocracy - Elder Leadership
Grand Elder: Ezua, Branch of Guidance (Dark Elf)
Top Keeper: Aolis, _ of Judgment (Elf)
Capital: 
Economy, Export: $, Potions
Population: Elves, Faries
Attraction(s): Mothertree

### Millsweet
Climate, Landscape: Cool, Lowfields
Goverment: Timocracy - Landowner Leadership
Sovereign: Ettore, Mr. Proprietor (Giant)
Top Guardsman: Hias, Death Stomp (Giant)
Capital: Proshire
Economy, Export: $$$, Milk and Honey
Population: Giants
Attraction(s): Foods

### Yumland
Climate, Landscape: Hot, Blue Tropics
Goverment: Geniocracy - Intellectual Leadership
Monarch: Leieth, Light Mind (Angler Clan)
Top Guardineer: Cyraenan, Eight Headed Demon (Octopus Clan)
Capital: Bahen
Economy, Export: $$$$, Rune Technolgy
Population: Merkin, Tearans
Attraction(s): Tech Innovations, Bio Dome

### Raijia
Climate, Landscape: Warm, Goldcoasts
Goverment: Plutocracy - Wealthy Leadership
King: _, Puppet King (Carmisean)
Underground Ruler: William Knightmond, The Marquis (Carmisean)
Top Sailor: Aeces, Serrated Fin (Swordfish Clan)
Capital: Sa Raiza
Economy, Export: $$$$, 
Population: Carmisseans, Merkin
Attraction(s): Economic Hub, Navy

### Bacombe
Climate, Landscape: Blazing, Sunbarrens
Goverment: Stratocracy - Military Leadership
Chieftian: Moffari, Apexalon (Lion Clan)
Top Warrior: Eryam, Man of Prey (Ivor)
Capital: Buckwick
Economy, Export: $$, Soldiers 
Population: Beastkin
Attraction(s): Arenas, Festivals
Bacombe Prairie
⁃ Africans, WBeastkin
⁃ Animal Haven

### Leardon
Climate, Landscape: Warm, Lushwoods
Goverment:
Leader:
Top Soldier:
Capital:
Economy, Export:
Population:
Attraction(s):

## Eastern Continent
### Tynfell
Climate, Landscape: Cold, Peakspires
Goverment: 
Leader: 
Top Soldier:
Capital:
Economy, Export:
Population: Hunyadi, Avikin
Attraction(s): Battle Arts

### Altin
Climate, Landscape: Chilly, Riverwells
Goverment: Diarchy - CoPolitical and CoMilitary Leadership
Mahara (Lord): Uyemura, Honorable Lord (Hunyadi)
Elotai (General): Yuguro, Honorable General (Ogre)
Top Soldier: Jihro, Clean Blade (Hunyadi)
Capital: Bahaura 
Economy, Export: $$$
Population: Hunyadi, Ogres
Attraction(s): Culture
Marshplains

## Southern Continent
### Ionforte
Climate, Landscape: Hot, Spritshores
Goverment:
Leader:
Top Soldier:
Capital:
Economy, Export: $$$, Tourism
Population: Carmisseans,
Attraction(s): Resorts, History museums

### Noena
Climate, Landscape: Dry, Cragliffs
Goverment: Feudalism - Lord Leadership
Colony Queen: Hekekri, Yethseyer (Cobra Variant) 
Top Guard: Orthix, Armored Dragon (Pangolin Clan)
Capital:
Economy, Export: $, Posions
Population: Replikin, Insikin
Attraction(s): Canyons, 

### Khasu
Climate, Landscape: Blazing, Scorthlands
Goverment: Empire - Emperor Leadership
Emperor: Nutear, Grand Sun (Marron)
Top Knight: Pausiris, Rising Star (Marron)
Capital: Manuma
Economy, Export: $$$, 
Population: Marrons
Attraction(s): Arenas

---

# Introduction

## Background

# Geography
## Location
## Geographic coordinates
## Map references
## Area
## Coastline
## Maritime claims
## Climate
## Terrain
## Elevation
## Natural resources
## Land use
## Major lakes (area sq km)
## Major rivers (by length in km)
## Population distribution
## Natural hazards

# People and Society
## Population
## Nationality
## Ethnic groups
## Languages
## Religions
## Population distribution
## Sex ratio
## Literacy

# Government
## Country name
## Government type
## Capital
## Administrative divisions
## Independence
## National holiday
## Constitution
## Legal system
## Citizenship
## Executive branch
## Legislative branch
## Judicial branch
## Political parties and leaders
## International organization participation
## Diplomatic representation 
## Flag description
## National symbol(s)
## National anthem
## National heritage

# Economy
## Economic overview
## Real GDP (purchasing power parity)
## Real GDP growth rate
## Real GDP per capita
## GDP (official exchange rate)
## Inflation rate (consumer prices)
## GDP - composition, by sector of origin
## Agricultural products
## Industries
## Labor force
## Population below poverty line
## Budget
## Public debt
## Current account balance
## Exports
## Exports - partners
## Exports - commodities
## Imports
## Imports - partners
## Imports - commodities
## Reserves of foreign exchange and gold
## Debt - external

# Energy

# Communications

# Transportation
## National transport system
## Ports

# Military and Security
## Military and security forces
## Military expenditures
## Military and security service personnel strengths
## Military equipment inventories and acquisitions
## Military deployments


Sports:

Legal =
    - Weapon Dueling
    - Melee Dueling
    - Mage Dueling
    - Mixed Dueling
    - Horse Dueling
    - Golem Fighting
    - Horse/Beast Racing
    - Chariot Racing
    - Runic carrige Racing
    - Fishing
    - Hunting
    - Weaponplay Competition (Style/Flair)
    - Melee Art Competition (Style/Flair)
    - Beast Competition (Style/Flair)
    - MAA (Mixed Aura Arts)
    - Boat Racing

Illegal =
    - Underground Monster Fighting
    - Underground Chimera Fighting
    - Undergorund Deathmatches



Dungeons are naturally occurring arenas that have 25-100 floors containing mostly dangerous monsters but also high level loot

### Enemies
Floor Guardians are beings that exist on the tenths' floors are a lot stronger than the other mobs that spawn on that floor. 

Minibosses are beings that exist on floors that have crucial positioning from the dungeon boss's floor. They are defense points to stop, intruders from going 
deeper into their lairs. Like bosses, they get thier own floors that have some riches. 

Door Guardians are beings that are one of the strongest monsters within the dungeon. They exist as the gatekeeper of the dungeon boss's floor. One cannot get to 
a dungeon boss without first defeating it's guardian. They reside on the path of the stairs to the next boss's floor.

Wandering Minibosses are beings on par with 
door guardians. They have recieved special permission from the dungeon boss to roam on pre defined floors. They act as suprise defenses against unsespecting 
intruders. For the unfortunate party that runs into these beasts on an earlier floor than planned... only ruin remain. 

Bosses are the owners of a dungeon. The reason intruders intrude to being with, to test their mettle against the biggest and baddest foe of the 
dungeons. One does not challenge the dungeon boss without the will to conquer and claim riches for themselves.

### Rewards
There are different

## Dungeon concpets

F  - Cave - Bear
Island - 
Overbearing Garden - 
D  - Dangerous Mountain -
Wicked Forest - 
C  - Sunken Graveyard -
Overun Science Lab - toxin slime king
Frozen Wasteland - 
Desert Tomb - 
Frozen Tomb - 
Ant colony - Ant Queen
B  - Bee hive colony - Hive queen and king
Spider nest - 
Ancient Battleground - 
Blast to Past - 
Ancient Ruins - 
Sky islands - 
Monkey Palace - Giant orangutan king
Undead Castle - Lich king
Labryinth - Raged Minotaur
Test of Memories - 
Statue Memorial - Statue deity
Dwelling of Giants - 
Dragon nest - Mother Dragon 
Land of the Dead - 
A  - Overrun Prison for Malevolants -
Ancient Beasts - 
S  - Place of Dragons -
Layline to Spirit world - 
SS - Portal from Shogrinn - Demon Noble

## Bosses
Shark
Dragon
Angel
Leviathan
Bull
Snake
Wolf
Spirit
Tree
Golem
Ghost
Being
Demon
Spider
Slime
Titan
Bird

Ghoul

Squid

## F Rank Dungeons

### Layout

1 - easiest floor
10 - floor guardian
20 - floor guardian
30 - boss, treasure

Name - Nation, Type Dungeon
Boss: Name, Nickname (Race)

Miniboss: Species
Miniboss: Species
Miniboss: Species

Name - Nation, Type Dungeon
Boss: Name, Nickname (Race)

Miniboss: Species
Miniboss: Species
Miniboss: Species

Name - Nation, Type Dungeon
Boss: Name, Nickname (Race)

Miniboss: Species
Miniboss: Species
Miniboss: Species

Name - Nation, Type Dungeon
Boss: Name, Nickname (Race)

Miniboss: Species
Miniboss: Species
Miniboss: Species


## D Rank Dungeons

### Layout

1 - easiest floor
10 - floor guardian
20 - floor guardian
30 - floor guardian
39 - door guardian
40 - boss, treasure

1 - easiest floor
10 - floor guardian
20 - floor guardian
30 - boss, treasure

Name - Nation, Type Dungeon
Boss: Name, Nickname (Race)

Miniboss: Species
Miniboss: Species
Miniboss: Species

Name - Nation, Type Dungeon
Boss: Name, Nickname (Race)

Miniboss: Species
Miniboss: Species
Miniboss: Species

Name - Nation, Type Dungeon
Boss: Name, Nickname (Race)

Miniboss: Species
Miniboss: Species
Miniboss: Species

Name - Nation, Type Dungeon
Boss: Name, Nickname (Race)

Miniboss: Species
Miniboss: Species
Miniboss: Species

## C Rank Dungeons 50

### Layout

1 - easiest floor
10 - floor guardian
20 - floor guardian
30 - miniboss
40 - floor guardian
50 - door guardian
60 - boss, treasure

1 - easiest floor
10 - floor guardian
20 - floor guardian
30 - boss, treasure

Name - Nation, Type Dungeon
Boss: Name, Nickname (Race)

Miniboss: Species
Miniboss: Species
Miniboss: Species

Name - Nation, Type Dungeon
Boss: Name, Nickname (Race)

Miniboss: Species
Miniboss: Species
Miniboss: Species

Name - Nation, Type Dungeon
Boss: Name, Nickname (Race)

Miniboss: Species
Miniboss: Species
Miniboss: Species

Name - Nation, Type Dungeon
Boss: Name, Nickname (Race)

Miniboss: Species
Miniboss: Species
Miniboss: Species

## B Rank Dungeons 50

### Layout

1 - easiest floor
10 - floor guardian
20 - floor guardian
30 - miniboss
40 - floor guardian
50 - floor guardian
60 - floor guardian
70 - miniboss
79 - door guardian
80 - boss, treasure 

1 - easiest floor
10 - floor guardian
20 - floor guardian
30 - boss, treasure

Name - Nation, Type Dungeon
Boss: Name, Nickname (Water Spirit)

Miniboss: Species
Miniboss: Species
Miniboss: Species

Name - Nation, Type Dungeon
Boss: Name, Nickname (Ghost)

Miniboss: Species
Miniboss: Species
Miniboss: Species

Name - Nation, Type Dungeon
Boss: Name, Nickname (Golem)

Miniboss: Species
Miniboss: Species
Miniboss: Species

Name - Nation, Type Dungeon
Boss: Name, Nickname (Bull)

Miniboss: Species
Miniboss: Species
Miniboss: Species

## A Rank Dungeons

### Layout

1 - easiest floor
10 - floor guardian
20 - miniboss
30 - floor guardian
40 - floor guardian
50 - miniboss
60 - floor guardian
70 - floor guardian
80 - miniboss
89 - door guardian
90 - boss, treasure

1 - easiest floor
10 - floor guardian
20 - floor guardian
30 - boss, treasure


Name - Nation, Type Dungeon
Boss: Name, Nickname (Water Spirit)

Miniboss: Species
Miniboss: Species
Miniboss: Species


14 Sun’s Blight - Khasu, Desert Dungeon
Boss: (Scorpion)

Miniboss: gila
Miniboss:
Miniboss:


Name - Nation, Type Dungeon
Boss: Name, Nickname (Hawk)

Miniboss: Species
Miniboss: Species
Miniboss: Species


16 The Lower Lake - Gerkin, Swamp Dungeon
Boss: Gator

Miniboss: Gator
Miniboss:
Miniboss:


Name - Nation, Type Dungeon
Boss: Name, Nickname (Spider Queen)

Miniboss: Species
Miniboss: Species
Miniboss: Species

Name - Nation, Type Dungeon
Boss: Name, Nickname (Devil)

Miniboss: Species
Miniboss: Species
Miniboss: Species


Name - Nation, Type Dungeon
Boss: Name, Nickname (Shark)

Miniboss: Species
Miniboss: Species
Miniboss: Species


Name - Nation, Type Dungeon
Boss: Name, Nickname (Metal Ant Queen)

Miniboss: Species
Miniboss: Species
Miniboss: Species

Name - Nation, Type Dungeon
Boss: Name, Nickname (Minotaur)

Miniboss: Species
Miniboss: Species
Miniboss: Species

## S Rank Dungeons

### Layout

1 - easiest floor
10 - floor guardian
20 - floor guardian
30 - miniboss
40 - floor guardian
50 - floor guardian
60 - miniboss
70 - floor guardian
80 - floor guardian
90 - miniboss
99 - door guardian
100 - boss, treasure


Name - Nation, Type Dungeon
Boss: Name, Nickname (Dark Spirit)

Miniboss: Species
Miniboss: Species
Miniboss: Species


Ijskoud - Colmere, Frozen Dungeon
Boss: Krioyll, The Froric Pillar (Frost Titan “white walker”)

Miniboss: Yeti
Miniboss: Froric Elemental
Miniboss: Arcbear

Noor Castle - nation, Fallen Kingdom Dungeon
Boss: Wemnyaor, Restless King (Multiheaded Grandknight Statue)

Miniboss: Knight Statue
Miniboss: Assassin
Miniboss: Shield


Name - Nation, Type Dungeon
Boss: Name, Nickname (Kraken)

Miniboss: Species
Miniboss: Species
Miniboss: Species


Name - Nation, Type Dungeon
Boss: Name, Nickname (Slime King)

Miniboss: Species
Miniboss: Species
Miniboss: Species

Ulititan - Metnir, Mountains Dungeon
Boss: Tortr WIP, The Moving Mountain (World Turtlr)

Miniboss: Metal Gem
Miniboss: Bat
Miniboss: Golem


10 Gahan - Torfrost, Frigid Forest Dungeon
Boss: Ferigan, The Wandering Mist (Wolf)

Miniboss: Wendigo
Miniboss: Bear
Miniboss: Ogre


12 Beast’s Lile - Bacombe, Savanna Dungeon
Boss: Ravula, The Undeniable Queen (Lion)

Miniboss: Elephant
Miniboss: Hippo
Miniboss: Hyena


Noena, Underground Coliseum Dungeon
Boss: Zermyr, The Bloodletter (Guardian Snake)

- Miniboss:
- Miniboss: Spider
- Miniboss: Ant

## S+ Rank Dungeons


### __The Onerous 10__

There are only ten S+ rank dungeons in the world, earning them the name, __The Onerous 10__. The dungeons are ranked based off of their level of impossibility. The Tenth Dungeon is the weakest of the ten. The Tenth Dungeon has never been conquered... 

Even the entrances to these ten domains is beyond dangerous. The energy that seeps out of these dungeons influenced the areas around them, altering them. These areas are marked as death zones trhoughout the world. Only the top echelon of adventurers are strong enough to approach...

Do you dare?

### Layout

1 - easiest floor
10 - floor guardian
11-49 - wandering miniboss
20 - floor guardian
30 - miniboss
40 - floor guardian
50 - floor guardian
51-89 - wandering miniboss 
60 - miniboss
70 - floor guardian
80 - floor guardian
90 - miniboss
99 - door guardian
100 - boss, treasure


### Inghura I
Khasu, Desert Dungeon
Boss: Orapyre, The Unpure Flame (Banished Spirit)

- Door Guardian: earth spirit
- Wandering Miniboss: salamander
- Wandering Miniboss: fire spirit
- Miniboss: 
- Miniboss: 
- Miniboss: elemental


### Deousgon II
Milsweet, Giant’s Dungeon
Boss: Ghemnah, 4-armed brute titan (Ultimate Titan)

- Door Guardian: 
- Wandering Miniboss: 
- Wandering Miniboss: 
- Miniboss: Mad Troll
- Miniboss: Gigant
- Miniboss: Gigant


### Arattamajiyo III
Altin, Tradition Grave Dungeon
Boss: Butchigoire, The Dishonored Majin (Yokai)

- Door Guardian: Shogun
- Wandering Miniboss: Fox Demon
- Wandering Miniboss: Bull
- Miniboss: 
- Miniboss: 
- Miniboss:  


### Nalgarden IV
Evern, Magic Forest Dungeon
Boss: Yinnigur, The Ending Tree (Ancient Tree)

- Door Guardian: Fallen Dryad
- Wandering Miniboss: Queen Rose
- Wandering Miniboss: Sworn Bird
- Miniboss: 
- Miniboss: 
- Miniboss: 


### Thalassis V
Raija, Ocean Dungeon
Boss: Korpapri, The Bellowvin (Leviathan)

- Door Guardian: 
- Wandering Miniboss: Baby Kraken
- Wandering Miniboss: 
- Miniboss: 
- Miniboss: Eel
- Miniboss: Undead Pirate King


### Leinevel VI
Baterie, Jungle Ruins Dungeon
Boss: Abu, The Last Carnic Beast (Relic Beast “Swallow”)

- Door Guardian: Devil
- Wandering Miniboss: Monkey King (Not Wu)
- Wandering Miniboss: Poison Ent
- Miniboss: 
- Miniboss: 
- Miniboss: 


### Orthorix VII
Theses, Unholy Dungeon
Boss: Pau, Fallen Archangel (fallen angel)

- Door Guardian: Decrepit Angel
- Wandering Miniboss: Elder Lich
- Wandering Miniboss: Assault Knight
- Miniboss: 
- Miniboss: 
- Miniboss: 


### Hor’s Gate VIII
Alphi, Frost Mountain Dungeon
Boss: Frorshneel, The Calamity Cold (Frost Dragon “WATE ice dragon”)

- Door Guardian: Lost Hero
- Wandering Miniboss: 
- Wandering Miniboss: Mad ice Spirit
- Miniboss: 
- Miniboss: 
- Miniboss: Undead ArchMage


### Pennrigon IX
Rhaion, Cursed Dungeon
Boss: Modaraithu, The Cursed God (Original Dragon)

- Door Guardian: Hydra
- Wandering Miniboss: 
- Wandering Miniboss: 
- Miniboss: Ancient Wyvern
- Miniboss: Drake
- Miniboss: 


### Bridgereal X
Dien, Hell Dungeon
Boss: Balbis, The First Demon Monarch (Demon Royal)

- Door Guardian: Demon Knight
- Wandering Miniboss: Demon Noble
- Wandering Miniboss: Behemoth
- Miniboss: 
- Miniboss: 
- Miniboss: 



Alphi
- The Institute

Altin
- Historic Oagoda
- Large Cherry Tree

Bacombe
- 

Baterie
- Ancient Temple Ruin

Colmere
- The Descent Mine
- Largest gem

Evern
- The World Tree

Ferrent
- Castle

Gerkin
- 

Khasu
- Oasis

Metnir
- Named mountain

Millsweet
- Beautiful Valley

Noena
- Mega Canyon

Raija
- Gold Beaches

Theses
- Church
- Shrine

Torfrost
- 

Yumland
- The Academy


Casino = 
Auction house =
Arena =




The Beginning was Here, and The End was There.

Here, The Beginning chose to bring about a bright and pure existence. He created a vast world with smooth mounts and soft airs. Golden bodies that run under ivory arches. He thought of pure entities and allowed them to inherit the world, spreading amongst themselves. He proclaimed the world as Bahhana, the First Realm of The Almighty. He then covered it with the Supreme One's Seal, bathing it in eternality.

The Beginning then sought to create a secondary existence. He made a particular world with undefined edges yet open skies. He divided his work into groups. He thought of shapeless beings and gave them the world as their origin. He claimed the world as Teorlan, the Second Realm of Spirits. He then placed in it an Original Being, worthy of His love.

The Beginning was asked to bring up an existence for some of His oldest creations. He created an innate world with beautiful peaks and rolling lands. The fresh bodies he poured brought life to thickened forests. He opened it to only certain beings and they made the lands their own. He called the world Borealis, the Third Realm of Myths. He then gave it to his lesser selves.

Where They meet, both touched and brought about an empty space. The Beginning shed it light, and The End took it away. The Beginning started it with wide skies, and The End drowned it in never ending waves. The Beginning filled it with high reaching mountains and lush lands, and The End carved it, making deep cracks in its surface, dark and devoid of His Light. The Beginning brought into it souls of balance, and The End spawned carnivorous souls. It was deemed Esteria, the Middle Realm of Mortals, which They saw as good.

The End needed an isolated and container of an existence. She made an unformed world with no edge and no end. She banished undesirable things to its plane. She denoted the world as Jathal, the Fourth Realm of The Forsaken. She then commanded Her lessers to watch.

The End made another existence. She saw nothing and made nothing. She titled the world was Ulrith, the Fifth Realm of The Lost. She then removed it from her presence.

There, The End wanted a dark and blighted existence. She formed a deep world voided of light and purity. She birthed calamitous beings that took the world and ravaged it. She said the world was Shogrinn, the Last Realm of The Astrayed. She then released the Mark of The End, blacking it from annihilation.

Thus, the Great Realms were formed.

### Bahhana
The celestial realm
- Most of the Almighty Gods reside here and also hosts celestial beings and creatures

### Teorlan
The spiritual realm
- Realm of the spirits where the Spirit King resides

### Borealis
The mythical realm
- Those that reach a certain level of power find passage to this Champions realm

### Estea
The mortal realm
- All mortal life resides here

### Jathal
The sealed realm
- Gods send versal threats to this realm for eternal sealing

### Ulrith
The lost realm
- Entities that wind up here are lost from their intended path

### Shogrinn
The infernal realm
- Most of the Astrayed Gods reside here and also hosts infernal beings and creatures


Regions of Lumhuin are made up of several enviroments (Coldest - Warmest)

## Northern Continent
### White Alps**
The White Alps is a tall arctic mountain range
- Artic Mountains

### Glacial Desert*
The Glacial Desert is a grand expanse of empty artic
- Artic

### Snowtops**
The Snowtops is a vast snowland forest that all kinds of furry life
- Snow forest and blue forest

## Northwestern Continent
### Cursed Ridges**
A widereaching expanse of mountains shoruded in darkness
- Dark mountains

### Darkwoods**
A still forest shorouded in mystery about its happenings
- Dark forest 

### Talltrees**
A widespread forest of giant trees, full of life within their canopy
- Tall forest

### Lostlands*
A once prosporus region, now no more than a fleeting reminder of the destruction that once was
- Dustlands

### Moltwrens*
A sweltering hot zone filled with magma stemmiing from its dormant volcanic center
- Volcanic

## Southwestern Continent
### Wilds*
A vast region of tall jungle and deep rivers
- Jungle

### Bogwamps
A deep swamp that disguises life and death
- Swamp

## Central Continent
### Grand Mounts*
The Grand Mounts are a vast mountain range of resource rich metals
- Mountains and caverns

### Calmplains**
The Calmplains are a large grassland area that has trees every now and then
- Plains

### Runhills
The Runhills are a vast region teeming with open hills
- Hills and floating islands

### Magiwoods**
The Magiwoods are home to all walks of life, from faemins to beasts. These magical woods protect all life
- Magic Forest

### Lowfields**
The Lowfields are a wide region of deep valleys
- Valley

### Blue Tropics**
The Blue Tropics are a vibrant and warm region of palm trees
- Tropics 

### Goldcoasts*
The beaches of the Goldcoasts are brillant and glisten off the daystar's light
- Beaches

### Sunbarrens
The Sunbarrens are a harsh enviroment that only produces the strongest of the flock
- Savanna

### Lushwoods
The Lushwoods are a forest of high quality foliage that rushes up the side of terraced mountainside
- Plateau forest and terrace mountains 

## Eastern Continent
### Peakspires*
The grandest mountains belong to the Peakspires range. These landforms peak through the heavens
- Peaking Mountains

### Riverwells
The Riverwells are a beautiful grassland region that is home to many known rivers throught Lumhuin
- Wetlands

## Southern Continent
### Spritshores**
The numerous isles of the Spritshores provide a dazzling pattern to the sea from a view afar
- Archipelago and red forest

### Cragliffs*
The dry Cragliff region holds many secrets beneath its earth. Only the most daring care to seek them out
- Canyons

### Scorchlands
The vast desert of the Scorchlands proves to be the most vicious of the natures
- Desert and Oasis

### Ghastmands*
This vile land sees not the light of the Daystar, only the sins of the Below
- Wasteland


Bucket
Rope
Torch
Lamp
Sleeping bag
Climbing gear
Pickaxe
Axe
Knife
Map
Bag
Compass
Blanket
Fire starter
Fishing rod
Boat


## Metals
Brunze
Steel
Yordsteel
Damascus


Snow forest - thick wood (glaneel wood)
blue forest - cold absorbing wood (coldwood)
Dark forest - miasmawood (darym wood)
Tall forest - longwood (highluhn wood)
volcanic x red forest - heat absorbing wood (warmwood)
Jungle - flexwood (vineland wood)
Swamp - watersoak wood (mogwoom wood)
Mountains and caverns - strong wood ()
Plains -  wood ()
Hills and floating islands -  wood ()
Magic Forest - magiwood (elwood wood)
Valley - thin wood (Shodwood wood)
Tropics -  wood ()
Beaches -  wood ()
Savanna - twist wood ()
Plateau forest and terrace mountains - good wood ()
Peaking Mountains - hard wood (ironwood)
Wetlands - prettywood (cherrywood)
Archipelago -  wood ()
Desert and Oasis - heat resistant wood (Oasapalm wood)

Friegast bulb
Saunroot petal
Manirose petal
Darkflower bulb
Peakole root 
Abyssom stem
Mosspetal seed
Corabloom bulb
Trenchiot petal

Ether

## Stone
Stone
Clay
Aquastone
Granite
Amber
Obsidian

## Ore
Bronze
Copper
Iron
Gold
Silver
Titanium
Lithium
Lithrim
Magnesate
Sulfur
Coal
Scarlite - Scarlet

Artic Mountains
Artic
Snow forest and blue forest
Dark mountains
Dark forest 
Tall forest
Dustlands
Volcanic
Jungle
Swamp
Mountains and caverns
Plains
Hills and floating islands
Magic Forest
Valley
Tropics 
Beaches
Savanna
Plateau forest and terrace mountains 
Peaking Mountains
Wetlands
Archipelago and red forest
Canyons
Desert and Oasis
Wasteland

## Minerals
Quartz
Pyrite
Marble
Malachite 
Emerald
Ruby
Opal
Bismuth
Sapphire
Amethyst
Jade
Crystal
Platinum 
Orichlium 
Galantine
Adamantine
Mythril
Diamond 
Black Diamond

## Metals
Brunze
Steel
Yordsteel
Damascus
Pigiron = cheap iron alloy


Hide
Claws
Teeth
Pelt 
Woo
Scale
Bone
Leather
Roughide



Glaneel wood = Arctic mountain trees
Highluhn wood = Tall trees
Darym = 
Elwood = 
Warmwood = 
Oasapalm wood = Beach trees
Tropico wood = Tropical trees
Cherrywood = East special trees
Vineland = Jungle trees
Mogwoom = Swamp trees
Ironwood = Volcanic trees
Valleywood = Valley trees
Taigawood = Snow forest trees
Shodwood = Mountain trees

Friegast bulb
Saunroot petal
Manirose petal
Darkflower bulb
Peakole root 
Abyssom stem
Mosspetal seed
Corabloom bulb
Trenchiot petal

Ether

## Stone
Stone
Clay
Aquastone
Granite
Amber
Obsidian

## Ore
Bronze
Copper
Iron
Gold
Silver
Titanium
Lithium
Lithrim
Magnesate
Sulfur
Coal
Scarlite - Scarlet

## Minerals
Quartz
Pyrite
Marble
Malachite 
Emerald
Ruby
Opal
Bismuth
Sapphire
Amethyst
Jade
Crystal
Platinum 
Orichlium 
Galantine
Adamantine
Mythril
Diamond 
Black Diamond



Head - Helmets, Hats

Neck - chain, necklace

Ears - earrings

Eyes - glasses, goggles

Shoulders - cape, cloak

Chest - chest plate armor, shirt, jacket

Back - backpack, bags

Arms -

Wrist - bracelet

Fingers - rings

Legs - pants

Ankles - anklet, socks

Feet - boots, shoes



- Book of Stars
    01 The Beginning: the beginning of the universe
    02 His Promise: the good of all and the eternal promise
    03 Hark of Light: the wonder of heaven
    04 Timependum: the endless continuation of time
    05 Life Cycle: the order and love of birth for life of estea
    06 First Order: the laws of the universe and rules to live good life
    07 Art of War: the battle arts and way to defend yourself
    08 Chapter of Wisedom: the quest of knowledge
    09 Chapter of Magic: the formation of spirits and mana to their realm
    10 Chapter of Love: the way to pursue just love
    11 Chapter of Peace: the path to total peace and to a mythical realm
    12 Chapter of Forge: the way arts affect our lives
    13 Chapter of Trade: why to work to live
    14 Chapter of Luck: the belief of trusting the universe
    15 Chapter of Hunt: the need of sustainability
    16 Chapter of Medicine: the way to care for the sick
    17 Chapter of Envy: the desire to covet others
    18 Chapter of Gluttony: the indulgence for fullfillment
    19 Chapter of Misfortune: the woe of the world
    20 Chapter of Greed: the want for everything
    21 Chapter of Sloth: the unruling of doing nothing
    22 Chapter of Nightmares: the scariest of the soul
    23 Chapter of Lust: the craving for impure love
    24 Chapter of Witch: the accursed magic of black
    25 Chapter of Forbidden: the seeking of clandestine knowledge and the realm of consequence
    26 Chapter of Wrath: the true path of anger
    27 Chapter of Pride: the way to live like youre above all
    28 Book of Death: the reaping of life to hell
    29 Chapter of Chaos: the seeping of dungeons and unnatural beings from a terrible realm
    30 Chapter of Dark: the horrors of hell
    31 Second Coming: the evil in all and the second coming
    32 The End: the end of the universe

- Book of Angels
- Book of Devils and Demons

- Book of Fire
- Book of Water
- Book of Earth
- Book of Air
- Book of Light
- Book of Dark
- Book of Space
- Book of Time
- Book of Poisons
- Book of Potions
- Book of Monster Hunting
- Book of Songs
- Book of Compass
- Book of Dungeons
- Book of Materials
- Book of Weapons
- Book of Recipes
- Book of Swordfighting
- Book of History
- Book of Pride
- Book of Wrath
- Book of Forbidden
- Book of Witch
- Book of Forge
- Book of Lust
- Book of Nightmares
- Book of Greed
- Book of Misfortune
- Book of Hunt
- Book of Medicine

- Beasts and Monsters = monster bio book
- Birds of Prey = bird special bio book
- Book of Beasts
- Book of Marine
- Book of Plants
- Book of Dragons
- Book of Spirits 
- Book of Plants
- Book of the Undead
- Book of Geography
- Book of Forging
- Book of Law
- Book of Curses
- Book of War
- Book of Forge
- Book of Lust
- Book of Nightmares
- Book of Greed
- Book of Misfortune
- Book of Hunt
- Book of Medicine


Items are cool honestly

## Item Grades
The item grading scale is a standard for ranking items in Lumhuin

### Bad Quality
Terrible items, lowest of the low

### Low Quality
Decent items

### Good Quality 
Great items, well made

### High Quality 
Amazing items, love and care 

### Top quality
Awesome items, best of their kind

### Grand Quality
Superior items, the best of the best

### Unique Quality
Peerless items, Perfect in every way, peak of quality

### Revered Quality
Heavenly items, Bestowed or belonging to the gods


MATERIALS
    Natural
        Plants
            Bamboo
            Cork
            Rattan
            Straw
            Cotton
            Linen
            Flax
            Hemp
            Jute
            Sisal
            Ramie
            Coir
            Abaca
            Kapok
            Moss
            Pine cones
            Bark
            Nut shells
            Leaves
            Grass
            Wheat
            Rice
            Corn
            Stone
            Granite
            Marble
            Limestone
            Sandstone
            Basalt
            Obsidian
            Slate
            Flint
            Quartz
            Jade
            Lapis lazuli
            Malachite
            Onyx
            Opal
            Garnet
            Sapphire
            Ruby
            Diamond
            Topaz
            Amber
            Meteorite
            Soil
            Clay
            Bricks (sun-dried)
            Adobe
            Mud
            Pumice
	•	Tuff rock
            Flagstone
	•	Gravel
	•	Sand
	•	Gypsum
	•	Dolomite
	•	Soapstone
	•	Sodalite
	•	Tourmaline
	•	Turquoise
	•	Petrified wood
	•	Shells
	•	Pearls
	•	Coral
	•	Mother of pearl
	•	Beeswax
	•	Silk (raw fiber)
	•	Sea sponge
	•	Seaweed
	•	Algae
	•	Kelp
	•	Peat
	•	Charcoal
	•	Natural rubber (latex)
	•	Resin (tree sap)
	•	Pitch
	•	Bitumen
	•	Salt
	•	Sulfur
	•	Native copper
	•	Native gold
	•	Native silver
	•	Platinum (native)
	•	Iron (native
        Food
            Thing
        Wood
            thichwood (taiga)
            shodwood (valley)
            osapalmwood (beach)
            tropiwood (tropics)
            magiwood (magic)
            vinewood (jungle)
            tallwood (tall)
            miamawood (dark)
            crylicwood (blue)
            endowood (red)
            cherrywood (wetlands)
            goodwood (plataeu)
            twistwood (savanna)
            milkwood (oasis)
            pourwood (archipleigo)
            ironwood (peak)
            regewood (hills)
            plains
            mogwood (swamp)
        Stones
            Granite
            Slate
            Marble
            Limestone
            Riverstone
            Sandstone
        Minerals
            Obsidian
            
	•	Amber
	•	Jade
	•	Quartz
	•	Amethyst
	•	Sapphire
	•	Ruby
	•	Emerald
	•	Topaz
	•	Onyx
	•	Pearl
	•	Coral
	•	Driftwood
	•	Star metal (meteoric iron)
	•	Gold
	•	Silver
	•	Copper
	•	Tin
	•	Lead
	•	Zinc
	•	Nickel
	•	Platinum
	•	Salt
	•	Sulfur
	•	Coal
	•	Peat
	•	Clay
	•	Mud
	•	Chalk
	•	Pitch
	•	Oil
	•	Water
	•	Freshwater pearls
	•	Spider silk (from natural spiders)
	•	Beeswax
	•	Honey
	•	Ivy
	•	Vines
	•	Bamboo
	•	Oak wood
	•	Maple wood
	•	Pine wood
	•	Willow wood
	•	Yew wood
	•	Ash wood
	•	Birch wood
	•	Cedar wood
	•	Redwood
	•	Mahogany
	•	Ebony
	•	Teak
	•	Walnut wood
	•	Rosewood
	•	Moss
	•	Lichen
	•	Mushrooms (various)
	•	Toadstool
	•	Mandragora
	•	Blue mushroom
	•	Chillshroom
	•	Fire herb
	•	Sleep herb
	•	Snow herb
	•	Bitterbug
	•	Godbug
	•	Flashbug
	•	Thunderbug
	•	Exciteshroom
	•	Nitroshroom
	•	Parashroom
	•	Devil’s Blight
	•	Flowfern
	•	Gloamgrass bud
	•	Slashberry
	•	Bomberry
	•	Dragonfell berry
	•	Dragonstrike nut
	•	Smokenut
	•	Dyes (from plants)
	•	Coffee beans
	•	Cocoa beans
	•	Rice
	•	Wheat
	•	Barley
	•	Oats
	•	Fruits (apples, oranges, etc.)
	•	Berries (blueberry, raspberry, etc.)
	•	Roots (carrot, turnip, etc.)
	•	Tubers (potato, yam, etc.)
	•	Animal hide (deer, wolf, bear, etc.)
	•	Animal bone (deer, wolf, bear, etc.)
	•	Animal teeth (big cats, wolves)
	•	Feathers (eagle, hawk, turkey, etc.)
	•	Claws (bear, wolf, big cat)
	•	Shells (turtle, clam, snail)
	•	Antlers (deer, elk, moose)
	•	Horns (ram, goat, etc.)
Sources:
Artificial Materials
These are crafted, refined, or magically created materials, often with properties beyond those found in nature.
	•	Mithral
	•	Adamantine
	•	Orichalcum
	•	Starmetal
	•	Celestial bronze
	•	Gromril
	•	Darksteel
	•	Dragon steel
	•	Poison metal
	•	Blacksteel
	•	Mana stone
	•	Synth (magical plastic)
	•	Floatstone
	•	Byeshk
	•	Hirokane
	•	Ithilmar
	•	Villamor
	•	Celesteel
	•	Magmite (Devil Iron)
	•	Stalinium
	•	Angel’s gold
	•	Iconium
	•	Oobleck metal
	•	Spellstone
	•	Starstone
	•	Sunderstone
	•	Psistone
	•	Angel skin (crafted from celestial beings)
	•	Elf resin (dried elf blood)
	•	Mountain iron (smelted from dwarf bones)
	•	Lunar iron
	•	Dracinium
	•	Solidified grace
	•	Composite resin armor
	•	Enchanted glass
	•	Arcane crystal
	•	Alchemical silver
	•	Enchanted wood
	•	Runesteel
	•	Dragonbone steel
	•	Frostforged iron
	•	Fireforged steel
	•	Shadowglass
	•	Sunshard crystal
	•	Bloodsteel
	•	Etherium
	•	Soulsteel
	•	Lightstone
	•	Shadowstone
	•	Frost crystal
	•	Magma crystal
	•	Thunderstone
	•	Stormglass
	•	Void crystal
	•	Aetherium
	•	Crystalized mana
	•	Spellthread (magically woven fabric)
	•	Living metal
	•	Clockwork alloy
	•	Golemstone
	•	Animated clay
	•	Glasssteel
	•	Ceratanium
	•	Gundarium
	•	Harbenite
	•	Harmonium
	•	Cavorite
	•	Cargonite
	•	Taydenite
	•	Thirium
	•	Chlorophyte
	•	Shroomite
	•	Spectre bar
	•	Supremium
	•	Sanite
	•	Saronite
	•	Carbonadium
	•	Carbon silicate lace
	•	Chelonium
	•	Tanavastium
	•	SAM (Strange Alien Matter)
	•	Magic-infused leather
	•	Arcane paper
	•	Spell-ink
	•	Enchanted rope
	•	Alchemical gold
	•	Crystal glass
	•	Psionic alloy
	•	Mystic cloth
	•	Soulbound iron
	•	Demonforged steel
	•	Blessed silver
	•	Cursed iron
Sources:
Monster Materials
These are harvested from magical or monstrous creatures, including body parts, fluids, and unique substances.
	•	Dragon scale
	•	Dragon bone
	•	Dragon blood
	•	Wyvern claw
	•	Wyvern fang
	•	Wyvern scale
	•	Basilisk fang
	•	Basilisk scale
	•	Chimera horn
	•	Chimera hide
	•	Griffin feather
	•	Griffin talon
	•	Manticore spike
	•	Manticore tail
	•	Hydra tooth
	•	Hydra blood
	•	Phoenix feather
	•	Phoenix ash
	•	Unicorn horn
	•	Unicorn hair
	•	Kraken ink
	•	Kraken tentacle
	•	Troll fat
	•	Troll hide
	•	Troll bone
	•	Giant’s toe
	•	Giant’s hair
	•	Giant’s bone
	•	Minotaur horn
	•	Minotaur hide
	•	Beholder eye
	•	Beholder stalk
	•	Lich phylactery shard
	•	Vampire fang
	•	Vampire blood
	•	Werewolf pelt
	•	Werewolf fang
	•	Dire wolf hide
	•	Dire bear claw
	•	Dire boar tusk
	•	Roc feather
	•	Roc talon
	•	Sphinx riddle stone
	•	Naga scale
	•	Naga venom
	•	Medusa hair
	•	Medusa scale
	•	Harpy feather
	•	Harpy talon
	•	Siren voice crystal
	•	Siren scale
	•	Banshee wail crystal
	•	Wight bone
	•	Ghoul claw
	•	Ghast tongue
	•	Wraith essence
	•	Shadow essence
	•	Specter shroud
	•	Ghost silk
	•	Demon horn
	•	Demon ichor
	•	Devil scale
	•	Devil tail
	•	Angel feather
	•	Angel tear
	•	Celestial essence
	•	Infernal bone
	•	Elemental core (fire, water, earth, air)
	•	Salamander scale
	•	Salamander tongue
	•	Djinn bottle shard
	•	Djinn essence
	•	Dryad bark
	•	Dryad sap
	•	Treant branch
	•	Treant leaf
	•	Faerie dust
	•	Sprite wing
	•	Pixie dust
	•	Kobold scale
	•	Goblin ear
	•	Orc tusk
	•	Ogre tooth
	•	Ogre hide
	•	Cyclops eye
	•	Yeti fur
	•	Aboleth mucus
	•	Mind flayer tentacle
	•	Mind flayer brain
	•	Slaad gem
	•	Modron gear
	•	Angel’s halo fragment
        Gemstones
            Thing
        Clay
            Thing
        Thing
            Thing
        Thing
            Thing
        Thing
            Thing
        Thing
            Thing
        Thing
            Thing
        Thing
            Thing
        Thing
            Thing
        Thing
            Thing
        Thing
            Thing
        Thing
            Thing
        Thing
            Thing
        Thing
            Thing
    Monster
        Leather
	•	Wool
	•	Silk
	•	Cashmere
	•	Mohair
	•	Angora
	•	Fur
	•	Feathers
	•	Down
	•	Bone
	•	Ivory
	•	Antler
	•	Horn
	•	Hoof
	•	Shellac
	•	Beeswax
	•	Honey
	•	Gelatin
	•	Tallow
	•	Lard
	•	Suet
	•	Collagen
	•	Keratin
	•	Lanolin
	•	Milk
	•	Casein
	•	Egg (albumen)
	•	Eggshell
	•	Chitin
	•	Chitosan
	•	Snail mucin
	•	Pearl
	•	Mother of pearl
	•	Coral
	•	Ambergris
	•	Civet oil
	•	Musk
	•	Castoreum
	•	Guano
	•	Manure
	•	Blood
	•	Sinew
	•	Tendon
	•	Cartilage
	•	Hide
	•	Rawhide
	•	Scale (fish)
	•	Fish skin
	•	Fish oil
	•	Fish glue
	•	Isinglass
	•	Rennet
	•	Carmine (cochineal)
	•	Shell (tortoiseshell)
	•	Mink oil
	•	Emu oil
	•	Horsehair
	•	Horse oil
	•	Bear bile
	•	Bile salts
	•	Royal jelly
	•	Propolis
	•	Venom (snake, bee, etc.)
	•	Silk fibroin
	•	Spongin (sea sponge)
	•	Spicules (sea sponge)
	•	Bone meal
	•	Bone char
	•	Stearic acid (animal source)
	•	Sodium tallowate
	•	Sodium stearate (animal source)
	•	Elastin
	•	Albumin
	•	Gelatine
	•	Spermaceti
	•	Whale oil
	•	Squalene (shark)
	•	Mink lashes
	•	Mink fur
	•	Goat hair
	•	Sheep skin
	•	Pigskin
	•	Cowhide
	•	Calfskin
	•	Snake skin
	•	Crocodile skin
	•	Alligator skin
	•	Ostrich leather
	•	Kangaroo leather
	•	Deer antler velvet
	•	Duck feathers
	•	Goose feathers
	•	Chicken feathers
	•	Quill (porcupine, bird)
	•	Shell buttons (mother of pearl)
	•	Insect resin (lac)
	•	Spider silk
	•	Animal glue
            Thing
        Wool (raw fiber)
	•	Mohair
	•	Cashmere
	•	Feathers
	•	Down
	•	Leather (untanned)
	•	Bone
	•	Horn
	•	Ivory
	•	Antlers
	•	Fur (raw)
	•	Animal hides
	•	Fish scales
	•	Fish skin
	•	Spider silk
	•	Chitin (from insects)


    Fists:
    - Hand wrap
    - Weighted knuckle gloves
    - Boxing gloves
    - Brass knuckles
    - Cestus (Spiked palm)
    - Priate hook
Claws: 
    - Tekko-kagi (Regular claws)
    - Shuko
    - Tekko
    - Nekode (finger claws)
Concelead: 
    - Shobo (small hand spike)
    - Yawara (small Double sided blunt)
    - Suntetsu (small Dual sided edged hand spike)
    - Kubotan (small edged hand spike)
    - Emeici (small Dual sided hand pike)
Blade:
    - Fighting bracelet
    - Deer horn knife
    - Wind and fire wheel
Knives:
    - Finger knife
    - Bayonet
    - Hunting knife
    - Bowie
    - Pocket knife
    - Smatchet
    - Switchblade
    - Ballistic
    - Butterfly knife
    - Kunai
    - Shiv
    - Tanto
    - Kozuka
    - Rampuri
    - Trench knife
    - Karambit
    - Seax
    - Jagdkommando knife
    - Puukko
    - Genoese knife
    - Kirpan CERM
    - Athame CERM
    - Phurba/Kila CERM
    - Sgian-dubh CERM
    - Tumi CERM
    Thrown:
        - Chakram
        - Shuriken
        - Throwing spike
        - Throwing knife
        - Onzil
        - Trumbashi
        - Kpinga
        - Sengese
    Tools:
        - Butter knife
        - Pairing knife
        - Steak knife
        - Pizza cutter
        - Fillet knife
        - Bread knife
        - Carving knife
        - Santoku knife
        - Maguro bocho
        - Chef's knife
        - Cleaver
        - utility knife
        - percision knife
        - scapel
        - Amputation knife
        - Straight razor
        - Letter opener
        - Ulu
        - Mezzaluna
        - Linoleum knife
Daggers:
    - dagger
    - dirk
    - stilletto
    - rondel
    - quillon
    - swiss dagger
    - misericorde
    - bollock dagger
    - katar
    - cinquedea
    - baselard
    - khanjali
    - pahoa
    - bhuj
    - haladie
    - kris
    - gunong
    - khanjar
    - jile
    - pesh-kabz
    - push dagger
    - bichuwa
    - sewar
    - pugio
    - ikul
    - boot knife
    - jambiya
    - saingham
    - otta
    - rencong
    - french nail
Swords:
    Machetes:
        - bolo
        - latin
        - kukri
        - barong
        - parang
        - cane
        - tapanga
        - golok
    - small sword
    - dao
    - butterfly sword
    - shortsword
    - kopis
    - falchion
    - gladius
    - xiphos
    - wakizashi
    - longsword
    - arming sword
    - claymore
    - rapier
    - zweihandler
    - sidesword
    - bastard
    - broadsword
    - flamberge
    - executioner's sword
    - kaskara
    - estoc
    - viking sword
    - jian
    - spatha
    - ida
    - takoba
    - warbrand
    - pata
    - curtana
    - cane sword
    - fencing sword
    - padded sword
    - sharktooth sword
    - hook sword
    - cicada wing sword
    - double bladed sword
    - urumi
    - khopesh
    - scimitar
    - cutlass
    - hanger
    - ninjato
    - katana
    - tachi
    - odachi
    - bokken
    - dha
    - sabre
    - spadroon
    - messer
    - backsword
    - kalis
    - zulfiqar
    - panabas
    - patag
    - khanda
    - kampilan
    - rhomphaia
    - falx
    - shotel
    - sica
    - mambele
    - kora
    - ngulu
    - konda
    - kilij
    - tulwar
    - shamshir
    - shaska
    - nimcha
    - flyssa
    - yataghan
    - ayudha katti
    - moplah
    Sword breakers:
        - sai
        - jitte
        - swordbreaker
        - parrying dagger
        - kabutowari
        - trident dagger
        - bian
        - jan
        - tekkan
Clubs:
    - club
    - spiked club
    - paddle
    - clava
    - leiomano
    - kotiate
    - wahaika
    - patu/mere
    - kanabo
    - macuahuitl
    - macana
    - shillelagh
    - knobkerrie
    - tewhatewha
    - totokia
    - kanak
    - culacula
    - ball-head
    - gata
    - supi
    - sali
    - gunstock
    - parrying shield
    - bulibuli
    - u'u
    Thrown:
        - waddy
        - ula
        - rungu
        - nulla-nulla
        - lil lil
        - valari
        - boomerang
    - baton
    - tonfa
    - blackjack
    - sap
    - nightstick
    - tipstaff
    - expandable baton
    - trench club
Maces:
    - vajra
    - morning star
    - flanged mace
    - footman's mace
    - bar mace
    - macil
    - gurz
    - melon hammer
    - ceremonial mace
    - gada
Hammers:
    - maul
    - horseman's pick
    - throwing hammer
    - otsuchi
    Tools:
        - claw hammer
        - ball-peen hammer
        - sledgehammer
        - blacksmith hammer
        - bush hammer
        - brick hammer
        - mallet
        - gavel
Axes:
    - tomahawk
    - tabar
    - ono
    - dane axe
    - boarding axe
    - trench axe
    - greataxe
    - venda
    - archer's axe
    - battle axe
    - labrys
    - double headed battle axe
    - parashu
    - sagaris
    - shepard's axe
    - hand axe
    - headhunting axe
    - execuioner's axe
    - bulova
    - epsilon
    Thrown:
        - throwing axe
        - hurlbat
        - francisca
        - nzappa zap
    Tools:
        - hatchet
        - carpenter's axe
        - dolorie
        - splitting maul
        - alpenstock
        - hacking axe
        - felling axe
        - adze
        - flint axe
        - fire axe
Pike:
    - hakapik
    - zaghnal
    Tools:
    - ice pick
    - mattock
    - pickaxe
    - ice axe
Polearms:
    - pike
    - sarissa
    - spear
    - boar spear
    - bohemian earspoon
    - spontoon
    - ox tongue
    - assegai
    - dory
    - xyston
    - sibat
    - parrying spear
    - tepoztopilli
    - partisan
    - ranseur
    - corseque
    - septum
    - yari
    - brandistock
    - tiger fork
    - military fork
    - nunti bo
    - goedendag
    - holy water sprinkler
    - sodegarami
    - tsukubo
    - sasumata
    - man catcher
    - monk's spade
    - zhua
    - ahlspiess
    - swordstaff
    - nagamaki
    - naginata
    - guandao
    - bisento
    - podao
    - bardiche
    - voulge
    - lochaber axe
    - arbir
    - doloire
    - fauchard
    - sovnya
    - glaive
    - bill
    - guisarme
    - halberd
    - pole arm
    - pollaxe
    - lucerne hammer
    - bec de corbin
    - dagger-axe
    - ji
    - war scythe
    - pike pole
    Lances:
        - light lance
        - kontos
        - heavy lance
    Thrown:
        - javelin
        - pilum/aklys
        - angon
        - iklwa
        - jarid
    Spear throwers:
        - atlatl
        - woomera
        - amentum
    Explosive:
        - fire lance
        - pole cannon
    Tool/Fishing:
        - harpoon
        - trident
        - gaff
        - leister
        - polespear
        - gig
Staves:
    - taiaha
    - baston
    - tanbo
    - hanbo
    - jo
    - bang
    - quarterstaff
    - bo 
    - eku
    - walking stick
    - peasant staff
    - vine staff
    - swagger stick
    - khatvanga
    - khakkhara
    - magic wand
    - magic staff
    Crooks:
        - shepard's crook
        - crosier
        - goad
        - crook and flail
    Tools:
        - sceptre
        - rod
Scythes:
    - scythe
    - sickle
    - kama
    - billhook
    - kudi
    - celurit
    - arit
    - brush hook
    - kujang
Fans:
    - gunsen
    - tessen
    - gunbai
Shields:
    - spiked shield
    - round shield
    - parrying shield
    - dueling shield
    - kite shield
    - heater shield
    - hungarian shield
    - scutum
    - pavise
    - tinbe and rochin
    - ballistic shield
    - throwing shield
    - buckler
    - lantern shield
    - madu
Siegers:
    - hand battering ram
    - battering ram
    - siege cauldron
    - petard
    - siege tower
    - trebuchet
    - catapult
    - ballista
    Tools:
        - ladder
Whips:
    - switch
    - bullwhip
    - cat o nine tails
    - chain whip
    - nagaika
    - crop
    - stambok
    - quirt
    - signal whip
Flails:
    - flail
    - chain mace
    - tree headed flail
    - kusarigama
    - nunchaku
    - pesant flail
    - chigiriki
    - three section staff
    - double sided flail
Ropes and Chains:
    - kyoketsu-shoge
    - rope dart
    - flying claw
    - grappling hook
    - manriki chain
    - meteor hammer
    - surujin
    - spiked chain
    - hook chain
    - slingshot
    - poi
    - flying guillotine
Bows:
    - shortbow
    - recurve bow
    - longbow
    - compound bow
    - takedown bow
    - blowgun
    - yumi
Crossbows:
    - hand crossbow
    - stone bow
    - gastraphetes
    - light crossbow
    - arbalest
    - repeating crossbow
    - compund crossbow
    Ammo:
        - bodkin point arrow
        - field arrow
        - bullet arrow
        - broadhead arrow
        - blunt arrow
        - judo arrow
        - incendiary arrow
        - fishing arrow
        - crossbow bolt
        - swiss arrow
        - suction arrow
        - blow dart
        - plumbata
        - tranq dart
        - feathered dart
        - throwing dart
        - kestros
Slings:
    - slingshot
    - sling
    - staff sling
    Ammo:
        - stone
        - stone bullet

Restraints/Traps:
    - garrote
    - net
    - cage
    - rope
    - ball and chain
    - handcuffs
    - meat hook
    - shackles
    - gibbet
    - stocks/pillory
    - bolas
    - lasso
    - saw blade
    - spinning blade
    - pendulum axe
Torture/Execution:
    - thumbscrew
    - torture cross
    - brazen bull
    - boot
    - pear of anguish
    - iron maiden
    - torture chair
    - judas cradle
    - rack
    - breaking wheel
    - wooden horse
    - guillotine

Spikes:
    - caltrop
    - makibishi
    - spike ball
    - spike strip
    - razor wire
    - barbed wire
    - spikes
    - punji sticks
    - barricade

Animal restriant/trap:
    - snare pole
    - snake hook
    - mouse trap
    - bear trap
    - snare
    - deadfall

https://www.reddit.com/r/worldbuilding/comments/18fqsd2/a_cool_guide_to_all_types_of_weapons/

Weapons: durability, value, rarity, dmg, magdmg, speed, abilities, name, enhancements, enchantments, description

- Knife KNF
- Daggers DGR
- Shortswords SSD
- Longswords LSD
- Heavyswords HSD
- Shortaxes SAX
- Axes AXE
- Battleaxes BAX
- Hammers HMR
- Warhammers WHR
- Spears SPR
- Pikes PIK
- Lances LNC
- Shortbows SBW
- Longbows LBW
- Hardbows HBW
- Crossbows CBW
- Autobows ABW
- Rangebows RBW
- Armshields ASH
- Shields SHD
- Bodyshields BSH
- Poles PLE
- Clubs CLB
- Maces MCE
- Flails FLA
- Scythes SCY
- Wands WND
- Staffs STF
- Tomes TME
⁃ SWORDS
⁃ Shortswords SSD (rapier, sabre, broad, katana)
⁃ Longswords LSD (claymore, odachi)
⁃ Heavyswords HSD (buster, crude)
⁃ HAMMERS
⁃ Hammers HMR
⁃ Warhammer WHR
⁃ AXES
⁃ Axes AXE
⁃ Greataxes GAX (halberd)
⁃ SPEARS
⁃ Spears SPR
⁃ Lances LNC
⁃ Double sided spear DSR
⁃ BOWS
⁃ Bows BOW
⁃ Crossbow CBW
⁃ Mace MCE
⁃ Club CLB
⁃ Wands WND
⁃ Flail FAL
⁃ Picks PCK
⁃ Tomes TME
⁃ Scythes SCY
⁃ Shields SHD
⁃ Staff STF
⁃ Whip WHP
⁃ Magic staff MSF


'''
centauri = Weapon("Iron Sword", "Basic creation Axe", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
andromeda = Weapon("Iron Sword", "Basic destruction Buster sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
pyr = Weapon("Iron Sword", "Basic all Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
ultrait = Weapon("Iron Sword", "Basic light Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
pendulan = Weapon("Iron Sword", "Basic Clock Medium", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
belam = Weapon("Iron Sword", "Basic life Staff", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
insidious = Weapon("Iron Sword", "Basic none Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
woe = Weapon("Iron Sword", "Basic dark Bastard Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
babel = Weapon("Iron Sword", "Basic chaos Chain flail", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
azrael = Weapon("Iron Sword", "death Scythe", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
jude = Weapon("Iron Sword", "Basic judge Axe", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
odin = Weapon("Iron Sword", "Basic war Spear", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
omnidex = Weapon("Iron Sword", "Basic wise Tome", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
moab = Weapon("Iron Sword", "magic Staff", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
magnolia = Weapon("Iron Sword", "Basic love Short Bow", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
hammil = Weapon("Iron Sword", "Basic craft Hammer", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
peace_pole = Weapon("Iron Sword", "Basic dream Staff", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
trade_axe = Weapon("Iron Sword", "Basic trade Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
luck_spear = Weapon("Iron Sword", "Basic luck Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
predator = Weapon("Iron Sword", "Basic hunt Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
jekyll_and_hyde = Weapon("Iron Daggers", "Basic alchemic Daggers", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
zenith = Weapon("Iron Sword", "Basic pride hammer", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
wrath_gauntlets = Weapon("Iron Sword", "Basic wrath Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
illiki = Weapon("Iron Sword", "Basic forbid Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
laucklhan = Weapon("Iron Sword", "Basic witch Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
fellicio = Weapon("Iron Sword", "Basic lust Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
gaangour = Weapon("Iron Sword", "Basic sloth Shield", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
lilith = Weapon("Iron Sword", "Basic fear Bow", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
aon = Weapon("Iron Sword", "Basic greed Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
cainah = Weapon("Iron Sword", "Basic curse Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
searya = Weapon("Iron Sword", "Basic glutton Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
uzira = Weapon("Iron Sword", "Basic envy Dagger", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
malevolent_bastard = Weapon("Iron maleve Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
scarlets = Weapon("Iron Sword", "Basic blood Daggers", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
beast_claws = Weapon("Iron Sword", "Basic beast Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
battle_gauntlets = Weapon("Iron Sword", "Basic battle Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
            
timekeeper_staff = Weapon("Iron Sword", "Basic Staff", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
frost_commandment = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
daisy_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
tosul_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
llan_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
thieves_bane = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
blood_and_gore = Weapon("Iron Sword", "Basic Twin Axes", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
yordrion = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
littlego_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
bayson_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
iron_wing = Weapon("Iron Sword", "Basic Wing Weapons", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
pseoippe_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
vile_blade = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
cabal_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
mets_forge = Weapon("Iron Sword", "Basic Hammer", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
golemslayer = Weapon("Iron Sword", "Basic Heavysword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
kings_rapier = Weapon("Iron Sword", "Basic Rapier", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
knights_sword = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
deadstar = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
brya_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
phanuel_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
hearthawig = Weapon("Iron Sword", "Basic Wand", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
elders_order = Weapon("Iron Sword", "Basic Bow", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
rosevan_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
ettore_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
hias_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
leiith_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
tendril_blades = Weapon("Iron Sword", "Tendril Blades", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
bladefin = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
scepter_of_hosts = Weapon("Iron Sword", "Basic Scepter", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
moffar_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
eryam_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
nyl_spear = Weapon("Iron Sword", "Basic Spear", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
uyemur_weapon = Weapon("Iron Sword", "Basic Katana", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
Tontakai = Weapon("Iron Sword", "Basic Heavy Katana", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
jihjro_weapon = Weapon("Iron Sword", "Basic Katana", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
hekek_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
orthi_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
pausiri_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
mini_sun = Weapon("Iron Sword", "Basic Greatsword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
yahren_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
relic_sabre = Weapon("Iron Sword", "Relic Sabre", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
unclesouth_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
modern_sabre = Weapon("Iron Sword", "Modern Sabre", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
yemel_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
morri_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
dreven_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
dreven_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
voustai_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
barri_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
miel_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
ukaos_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
shaunti_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
dwaroia_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
gabyr_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
yeseli_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
eldrie_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
bhasisith_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
jerilla_weapon = Weapon("Iron Sword", "Basic Sword", Weapon.a_rating, Weapon.undamaged, 10, 1, None, None, None, None, None, None, None, None, None, 
               "A sword", [tag, tag])
'''



 - jofiel's heavyspear
 - hermle's
 - lynniel's
 - marmou's heavysword
 - rahdreal's greataxe
 - grimini's greatscythe
 - montero's
 - uran's sword
 - wolford's magistaff
 - yukire's staff
 - sage's 
 - crozzen's warhammer
 - agil's
 - veneti's
 - rachess's longbow
 - asanna's shortbow
 - bingeal's 
 - krenari's
 - gahar's
 - verbel's
 - inachtra's
 - zakzano's
 - perizay's
 - lahkus's
 - teher's
 - eirnin's
 - himhia's
 - neieba's 

 - Ferrent’s King
 - Top Ferrent Knight
 - Yahren
 - Evern’s Grand ElderTop Evern Keeper__
: Aolis, Branch of Judgment (Elf)
> The best keeper of Evern that wields his bow as the ultimate judge of the Magical Forest (Inspired by)

## Metnir based NPCs

__Metnir’s King__
: Daggril, King Mountain (Great Dwarf)
> The king of Metnir that is respected as a peerless genius among his fellow smiths (Inspired by)

__Top Metnir Knight__
: Wearld, Golem Slayer (Great Dwarf)
> The top knight of Metnir that protects the country. He was a famous golem hunting adventurer in the past that earned him his name (Inspired by)

## Raija based NPCs

__Raija’s “Underground” Ruler__
: William Knightmond, Marquis (Carmisean)
> The true “ruler” of Raija, the Coastal Trade Kingdom. It does have an official king(i.e not you) but since it’s heavily trade focused you really pull the strings behind the scene

__Raija’s “Puppet” Monarch__
:, Puppet King (Carmisean)
> The true “ruler” of Raija, the Coastal Trade Kingdom. It does have an official king(i.e not you) but since it’s heavily trade focused you really pull the strings behind the scene

__Top Raija Sailor__
: Aeces, Serrated Fin (Swordfish Clan)
> The top sailor of Raija that protects their beaches and borders from his sword skill of his nose (Inspired by)

## Khasu based NPCs

__Khasu’s Emperor__
: Nutear, Grand Sun (Marron)
> The esteemed emperor of Khasu. With his wise mind and tactical beliefs, he commands the respect of all the Scorchlands. Blessed with the familial protection of fire spirits (Inspired by)

__Top Khasu Knight__
: Pausiris, Rising Star (Marron)
> The top knight of Khasu that protects the empire (Inspired by)

__Infamous Anti-hero__
: Malgrieve, Endside (Marron)
> Vigilante hero that fights underground organizations (Inspired by Batman, Deadpool)

## Torfrost based NPCs

__Torfrost’s Ruler__
: Kinnard, Crimson King (Ivor)
> The pirate king of Torfrost that rules with an iron thumb. Received his nickname from the methods he employs to control fellow thiefs and rob foreign convoys (Inspired by)

__Top Torfrost Marauder__
: Borkus, Northern Beast (Orc)
> The top maurader of Torfrost that leads the areas main pirate bands to protect borders and raid neighbors (Inspired by)

__Famous Torfrost Monster Hunter-Black Iris Guildmaster__ 
: Greyrose Lynch, Whiteheart (Ivor)
> Grizzled northern hunter that targets man and beasts alike. He started and heads a guild called Black Iris. Now he’s retired and spends his days hunting with his pet frost wolve, Roric, in a small cabin, hidden deep in the trees of the Torfrost snowdens (Inspired by Witcher, Monster Hunter)

## Alphi based NPCs

__Alphi’s Lordmage__
: Rheflyn, Horus Chronus (Ivor)
> The lordmage of Alphi that leads the country and the magical research institute, Grand Wolford Institute. His unique ability to wield extraordinary time magic earned him his title. He is rarely seen away from the institute (Inspired by)

__Top Alphi Guardmage__
: Obeah, Glacius (Ivor)
> The best guardmage of Alphi that protects the country with powerful ice magic (Inspired by)

## Altin based NPCs

__Altin’s Lord__
: Uyemura, Honorable Lord (Hunyadi)
> The lord of Altin that leads the country’s politics (Inspired by)

__Altin’s General__
: Yuguro, Honorable General (Ogre)
> The general of Altin that leads the country’s military. He is a renown samurai that rose to his position through his achievements (Inspired by)

__Top Altin Samurai__
: Jihro, Clean Blade (Hunyadi)
> The best samurai of Altin who’s rumored to have swordplay so fast that when he cuts his target, no blood is able to stain his blade (Inspired by)

## Bacombe based NPCs

__Bacombe’s Chieftian__
: Moffari, Apexalon (Lion Clan)
> The chief of all of Bacombe’s leading tribes that control the Fang Playground region (Inspired by)

__Top Bacombe Warrior__
: Eryam, Man of Prey (Ivor)
> The top warrior of Bacombe that assists the chieftain in the region’s protection. Earned his name after proving his nature and agilities to all beast tribes (Inspired by)

__Legendary Beastkin Warrior__
: Jurni Nyl Fuprir, Striped Fang (Tiger Clan)
> The first S rank hero that originated from Bacombe, the Savannah Beast-kin Territory. Know for your power with a spear you are feared throughout Bacombe and the rest of the Estea continent as one of its deadliest heroes

## Gerkin based NPCs

__Gerkin’s Overlord__
: Igbias, Devil King (Tasmanian Clan)
> The overlord of Gerkin that controls the region with heinous acts. His vile preference for bones and decay, along with his necrotic innate abilities, earned him his title (Inspired by)

__Top Gerkin Warrior__
: Cabal, Black Middle (Gator Clan)
> The strongest warrior of Black Hand. Gerkin’s warrior that directly orders to the overlord. He enacts the overlord’s rule through his difficult halberd skills. Belongs t (Inspired by)

## Baterie based NPCs

__Baterie’s Chieftain__
: Geshrew, Greech Wing (Parrot Clan)
> The chieftain of Baterie’s tribe Alliance. His wingbeat is strong allowing him to propel himself into the air at incredible speeds (Inspired by)

__Top Baterie Warrior__
: Pseosippe, Whistling Spear (Parakere)
> The best warrior of Baterie that protects the Jungle. Her spear skill paired with her manipulation of air magic allows her throws to be heard right before death  (Inspired by)

## Theses based NPCs

__Theses’ Holy Crown__
: Bryra, Golden Saintius (Laudquin)
> The crown of Theses that is said to have the closest connection to the Supreme God, Osiri, in all of Lumhuin (Inspired by)

__Top Theses Paladin__
: Phanuel, Knight in White (Marron)
> The leading paladin of Theses that has the blessing of Jofiel as her champion (Inspired by)

## Noena based NPCs

__Noena’s Colony Queen__
: Hekekri, Yethseyer (Cobra Variant)
> The queen of Noena that wields the special power of foresight. She is from a long line of venerable cobrikin royals (Inspired by)

__Top Noena Guard__
: Orthix, Armored Dragon (Pangolin Clan)
> The best guard of Noena. His Armor-plated body along with his unique basilisk slaying greatsword earned him his nickname (Inspired by Takeshi Kido from Killing Bites)
 
## Millsweet based NPCs

__Millsweet’s Sovereign__
: Ettore, Mr. Proprietor (Giant)
> The sovereign of Millsweet that leads the country and loves their land (Inspired by)

__Top Millsweet Guardsman__
: Hias, Death Stomp (Giant)
> The top guardsman of Millsweet that protects the country with ferocious intent (Inspired by)

## Yumland based NPCs

__Yumland’s Monarch__
: Leieth, Light Mind (Angler Clan)
> The monarch of Yumland that leads the country into a better future. She runs the Monicra Blue Academy that leads young engineers to invent better inventions (Inspired by)

__Top Yumland Guardineer__
: Cyraenan, Eight Headed Demon (Octopus Clan)
> The top guardineer of Yumland that gained his name from the 8 blades he wields from his tentacles which have destructive force (Inspired by)

## Colmere based NPCs

__Colmere’s King__
: Tosul, King of 100 Treasures (Azureen)
> King of Colmere that manages the country as well as the business of the countries profitable mineral mines. His nickname is derived from the 100 unique variants of all the minerals retrieved from the mines (Inspired by)

__Top Colmere Guard__
: Llann, Door of Colmere (Polar Clan)
> The top guard of Colmere that protrcts the country and their wealth. Known for the strict bar of entry, he enforces (Inspired by)

# Notes

__Redbaan Pirates Captain__
: Captain Southerland, Red Sea ()
> Captain of Redbaan Pirates

__Filibuster Pirates Captain__
: Captain Dierge, Captain Killer ()
> Dierge is the Captain of the Filibister Pirates. Originally, his life has always been that of a pirate as his father was the firdt captain of the infamous Redbaan pirates. His whole world changed when his uncle, Southerland, betrayed his brother and took over the crew. Now on a revenge path, Dierge went from being a pirate to hunting them.

__Xoul's Guildmaster__
: Bayson Cross, White Death ()
> Infamous bounty hunter that operates in the Lostlands. He was once a content priest named Lyle, living out his life with his lover, a nun named Meielie. That came crashing down when a 

__ARX's Leader__
: Malgrieve, Light of Retribution ()
> 

__Godslayer Guildmaster__
: Yemel, Heavy Heart (Marron Woman)
> Grew up with Morri in the same village but their home met a grave fate at the hands of Abu, The Carnic Beast. The two then dedicated their lives to becoming dungeon hunters to eventually hunt down their archenemy. The duo, alongside Taal, Abu's offspring, started a dungeon crawling guild.

__Godslayer Second Guildmaster__
: Morri, Smiling Swordsman (Ivor Man)
> Grew up with Yemel

__Grey Blood Guildmaster__
: Dreven Grey, Sanguinica (Half Human-Vampire)
> A famous vampire hunter that vengefully seeks to wipe out the vampires from Lumhuin. He founded a guild dedicated to his famous undead slaying

__Gambler__
: , ()
>

__Chef__
: , ()
>

__Duelist__
: , ()
>

__Artist__
: , ()
>

__Witch__
: , ()
>

__Runineer__
: , ()
>

__World government leader__
: , ()
>

__Merchant associstion leader__
: , ()
>

__Adventurer associstion leader__
: , ()
>

__Tamers associstion leader__
: , ()
>

__Smiths associstion leader__
: , ()
>

__Mages associstion leader__
: , ()
>

__Mercenary associstion leader__
: , ()
>

__Church leader__
: , ()
>

__Robotics master__
: , ()
>

__9Head First Head__  
: , ()
> control dominance aura user

__9Head Second Head__  
: , ()
> knife blade work master

__9Head Third Head__  
: , ()
> sniping, long range bow master

__9Head Fourth Head__  
: , ()
> poison and chemicals master

__9Head Fifth Head__  
: , ()
> humiliation fear chain arts master

__9Head Sixth Head__  
: , ()
> torture, intelligence doctor

__9Head Seventh Head__  
: , ()
> magic arcane death magic user

__9Head Eighth Head__  
: , ()
> tools, explosives expert

__9Head Ninth Head__  
: , ()
> disguise master, deception 

__Prey Raid Boss__ 
: , ()
>

__Raiji's Navy Captain__ 
: , ()
>

__Khasu's Army Commander__ 
: , ()
>

__Alphi's Air Force Sergeant__ 
: , ()
>

__Little God Gang's Boss__
: , Little God ()
> 

__Cyphon Guildmaster__ 
: Count Abel Waryn, The Ringmaster ()
> Guildmaster of the famous blackmarket guild, supplier of the Lumhuin Underworld. Known to be able to aquire any item in the world.

__Black Iris Guildmaster__ 
: , ()
> The famous 

__Goldsin Guildmaster__ 
: , ()
>

__Antiarch's Leader__ 
: , ()
>

__Yordworks' Founder__ 
: , ()
>

__Helliant's Guildmaster__ 
: , ()
>

__Dragrion Guildmaster__
: , ()
>

__Voaustier's Owner__
:  Voaustier, ()
>

__Runkitz Lab's Head__ 
: , ()
>

__Barri & Miel founding Guildmaster__
: Barri, (Male)
> 

__Barri & Miel founding Guildmaster__
: Miel, (Female)
> 

__Barri & Miel current Guildmaster

 - blood iron sword
 - god killer sword
 - king killer sword
 - soul eater sword


 Knives

Bombs

Potions

Projectiles


The founding religon of the Lumverse is "The Thirty Stars".

## Latosphere
### Supreme Stars
In the beginning, there was Osiri. At the end, there was Khuthulun. The origin of the Lumverse. The Beginning being the Supreme Star of Creation, represented by the Daystar and the End, the Supreme Staress of Destruction, represented by the Endstar. The Supreme Stars are deemed the highest most authority of all.

### Prime Stars
Of the Supreme, came that of the Prime. There was Jofiel, Hermle, and Lynniel of Osiri. Of Khuthulun, came Marmou, Rahdreal, and Grimini. Bringing forth balance to the Lumverse. The Angel being the Prime Staress of Light, represented by the Holystar. The Demon being the Prime Star of Darkness, represented by the Darkstar. The Keeper being the Prime Star of Time, represented by the Timestar. The Fracture being the Prime Star of Chaos, represented by the Chaostar. The Tree being the Prime Staress of Life, represented by the Lifestar. The Reaper being the Prime Staress of Death, represented by the Deadstar. The Prime Stars are revered as they are feared.

### Major Stars
Following the will of the Prime, cometh the Major. There was Montero, Uran, Sage, Wolford, Asanna, Crozzen, Yukire, Agil, Veneti, Rachess, and Bingeal. Spreading good will to the Lumverse.

- The Judge being the Major Star of Law and Reason, represented by the Orderstar
- The Commander being the Major Star of War and Honor, represented by the Ironstar
- The Teacher being the Major Star of Knowledge and Wisedom, represented by the Wisestar
- The Wizard being the Major Star of Magic and Sorcery, represented by the Magistar
- The Love being the Major Staress of Love and Marriage, represented by the Lovestar
- The Smith being the Major Staress of the Forge and Craftsmanship, represented by the Firestar
- The Rest being the Major Star of Peace and Dreams, represented by the Cloudstar
- The Merchant being the Major Star of Trade and Commerce, represented by the Goldstar
- The Saint being the Major Star of Luck and Fate, represented by the Luckstar
- The Hunter being the Major Staress of Hunting and Farming, represented by the Bowstar
- The Healer being the Major Staress of Medicine and Alchemy, represented by the Medstar

The Almighty Stars are respected.

There was also Krenari, Gahl, Zakzano, Verbel, Himhia, Perizay, Inachtra, Lahkus, Teher, Eirnin, and Neieba. Spreading ill will to the Lumverse.

- The Prideful being the Major Staress of Pride, represented by the Egostar
- The Wrathful being the Major Star of Wrath, represented by the Wrathstar
- The Forbidden being the Major Star of Forbidden Knowledge, represented by the Ignastar
- The Witch being the Major Staress of Witchcraft, represented by the Witchstar
- The Lustful being the Major Staress of Lust, represented by the Luststar
- The Slothful being the Major Star of Sloth, represented by the Slothstar
- The Sufferer being the Major Staress of Nightmares, represented by the Marestar
- The Greedy being the Major Star of Greed, represented by the Avastar
- The Unfortunate being the Major Staress of Misfortune, represented by the Badstar
- The Glutton being the Major Star of Gluttony, represented by the Vourstar
- The Envious being the Major Star of Envy, represented by the Jealstar
- The Astrayed Stars are followed in secret

The Astrayed Stars are followed in secret.

These stars understand their leading star's true purpose and act to assist them. These Gods are heavily respected by mortals that align with their commands. 

### Guardians
The keepers of the Oververse. These harkoned beings protect the realms they reside, dutifully carrying out their star's command. These Guardian Beasts are given respect from all mortals in their presence.

## Hatosphere
### Minor Stars
These stars are manifestations of mortalian desires and retain power from the strength of their followers. The most powerful Dieties rival Guardian Beasts in strength.

### Half Stars
These beings are bore from the holy gift of divine nature to a mortal being. These Demigods.

### Prophets
A select few mortals that the Gods have deemed worthy enough to deliver their message. 

### Champions
The chosen swords of the Stars, their Champions! These mortals live, breath, and die following their serving Gods commands. Only Latospherian Gods have the authority and power to bestow their power to born a champion.

⁃ STR Strength -> damage output

⁃ DEF Defense -> damage input

⁃ AGI Agility -> limber/evasive/movement

⁃ SPD Speed -> physical speed

⁃ PRO Proficiency -> hands on efficiency

⁃ ARC Arcane -> mystic cabability

⁃ CHR Charisma -> socialbility

⁃ INT Intelligence -> wisedom

⁃ FRT Fortitude -> Mental/Physical constitution

⁃ LUC Luck -> odds increaser

⁃ FAI Faith