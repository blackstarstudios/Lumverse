# Notes

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
- HelluBook of Devils and Demons

- Book of Fire
- Book of Water
- Book of Earth
- Book of Air
- Book of Light
- Book of Dark
- Book of Space
- Book of Time
- 1000 Petals = Book of Poisons
- Book of Potions
- Rose's Monster Hunting Guide = Book of Monster Hunting
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
- Inconzeil = Book of Forbidden
- Book of Witch
- Book of Forge
- Book of Lust
- Book of Nightmares
- Book of Greed
- Tally of Curses = Book of Misfortune
- Book of Hunt
- Book of Medicine

- Lufauna = monster bio book
- Birds of Prey = bird special bio book
- Fang and Paw = Book of Beasts
- Aquamara = Book of Marine
- Terrerium = Book of Plants
- Igni = Book of Dragons
- Glaious Extrana = Book of Spirits 
- Book of Plants
- Ghohgna = Book of the Undead
- Book of Geography
- Book of Forging
- Book of Law
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


## Inferior Races
### Human Races


### Non-Human Races

### Beastmen

Humans -> Hummana:
Scandinavians Ivors Torfrost 
Blacks Marrons Khasu 
Latinos Carmiseans Raiza 
Asian Hunyadi Altin 
Arabs G Noena
Islanders Tearans Yumland 
Eskimos Azureens Colmere 
Brazilian Parakere Baterie
European Laudquin Ferrent
African G Bacombe
Indians
Natives
Carribbean


Beasts -> Beastkin: ⁃ Cat: Lionkin ⁃ Wolf: Wolfkin ⁃ Bull: Bullkin ⁃ Bear: Ursikin ⁃ Horse: Marekin ⁃ Deer: ⁃ Goat: Ramkin ⁃ Fish: Merkin ⁃ Bird: Hawkin ⁃ Lizard: Lizardkin

Dwarves Metnir ⁃ Elves Evern ⁃ Faries Evern
Giants Millsweet
Ogres Altin
Orcs Torfrost


## Superior Races
## Angels

## Demons
Original Devils

## Titans
Original Giants

## Divine Beasts
Original Beastmen

## Augian Elves
Orginal Eleves

## Dragonkin
Original Replikin

## Dryads

## Fallen Angels

## Merpeople
Original Merkin

## Spirits

## Djinns

## Vampires


### Azureens**
Native to the Glacial Desert
Alaska Native/Inuit influence

### Ivors
Native to the Snowtops
Scandanavian/Welsh influnce

### Hunyadi
Native to the Riverwells and Peakspires
Asian influence

### Laudquin
Native to Calmplains and Runhills
European influence

### Carmisseans
Native to the Goldcoasts
Latino/Hispanic influence

### Tearans**
Native to the Blue Tropics and Spritshores
Islander/Caribbean influence

### Parakere
Native to the Wilds
Brazilian influence

### Marrons
Native to the Scorchlands
Black/African American/African influence


Beastmen -> Kins -> Clans -> Variants
 

# Canikin - Dogs
- Wolf Clan
- Fox Clan
- Hyena Clan
- Coyote Clan

# Felikin - Cats
- Lion Clan
- Panther Clan
- Tiger Clan
- Leopard Clan
- Puma Clan

# Replikin - Reptiles
- Snake Clan
- Lizard Clan
- Turtle Clan
- Gator Clan
- Komodo Clan

# Avikin - Birds
- Eagle Clan
- Penguin Clan
- Vulture Clan
- Hawk Clan
- Pelican Clan
- Owl Clan
- Bat Clan
- Parrot Clan

# Orsikin - Bears
- Brown Clan
- Black Clan
- Polar Clan
- Panda Clan
- Koala Clan
- Tasmanian Clan

# Suikin - Pigs
- Boar Clan
- Hippo Clan

# Taurikin - Cow
- Bull Clan
- Elephant Clan
- Rhino Clan

# Aquakin - Fish
- Shark Clan
- Octopus Clan
- Squid Clan
- Jellyfish Clan
- Dolphin Clan
- Whale Clan
- Seal Clan
- Manta Clan
- Eel Clan
- Angler Clan
- Swordfish Clan

# Marikin - Horses
- Mustang Clan
- Zebra Clan
- Giraffe Clan
- Camel Clan


# Amphikin - Amphibious
- Frog Clan
- Newt Clan

# Rodikin - Rodents
- Rat Clan
- Gopher Clan
- Squirrel Clan
- Raccoon Clan
- Badger Clan 
- Weasel Clan
- Mole Clan
- Porcupine Clan
- Pangolin Clan

# Primikin - Monkeys
- Gorilla Clan
- Chimp Clan
- Baboon Clan
- Orangutan Clan
- Lemur Clan
- Sloth Clan

# Insikin - Insects
- Spider Clan
- Scorpion Clan
- Ant Clan
- Bee Clan
- Wasp Clan
- Mantis Clan
- Centipede Clan
- Butterfly Clan
- Beetle Clan

# Bovikin - Deer
- Reindeer Clan
- Moose Clan
- Goat Clan

# Lepokin - Rabbits
- Bunny Clan
- Jack Clan
- Kangaroo Clan

# Crusikin - Crustaceans
- Crab Clan
- Lobster Clan
- Shrimp Clan

## Beastmen Races
Classification Order:
Beastmen
Replikin
Snake Clan
Cobra Variant

### Canikin
Canine descending races (Dogs/Wolves)
- Wolf Clan
- Fox Clan
- Hyena Clan

### Felikin
Feline descending races (Cats/Lions)
- Lion Clan
- Cougar Clan
- tiger Clan

### Avikin
Aerial descending races (Birds/Hawks)
- Hawk Clan
- Peackock Clan
- Flamingoo Clan

### Merkin
Marine descending races (Fish/Sharks)
- Shark Clan 
- Whale Clan
- Swordfish Clan

### Replikin
Reptillian descending races (Reptiles/Snakes)
- Snake Clan
- Komodo Clan
- Gila Clan

### Bovikin
Bovine descending races (Cattle/Bulls)
- Bull Clan
- Buffalo Clan
- Bison Clan

### Ovikin
Ovi descending races (Sheep/Goats)
- Sheep Clan
- Goat Clan
- Ram Clan

### Rodikin
Rodian descending races (Rodents/Mice)
- Mouse Clan
- Weasel Clan
- Racoon Clan

### Ursukin
Ursurin descending races (Bears/Polar)
- Polar Clan
- Badger Clan
- Sloth Clan

### Crusikin
Crusteassean descending races (Crusteaseans/Crabs)
- Crab Clan
- Lobster Clan
- Shrimp Clan

### Insikin
Insectian descending races (Insects/Bees)
- Wasp Clan
- Beetle Clan
- Butterfly Clan

### Lepokin
Lepoid descending races (Rabbits/Hares)
- Hare Clan
- Jack Clan
- Bunny Clan

### Marekin
Mare descending races (Horses/Mustangs)
- Mustang Clan
- Mule Clan
- Zebra Clan 

### Primikin
Primate descending races (Monkeys/Gorillas)
- Monkey Clan
- Gorilla Clan
- Orangatan Clan


REP: -500 to 500
Hated in: Evil

-500 - realms

-400 - continent

-300 - country

-200 - city

-100 - town

0 - Neutral

Loved in: Good

100 - town

200 - city

300 - country

400 - continent

500 - realms


50’s are half of next tier



## Player Info Layout
1. Name
1. Title
1. Occupation
1. Lumes (Lums)

- Stats
1. Health Points (HP / MAXHP)
1. Mana Points (MP / MAXMP)
1. Stamina Points (SP / MAXSP)
1. Level (Lvl)
1. Experience (XP / MAXXP)
1. Aspiration (ASP)
1. Reputation (REP)

- Attributes
1. Strength (STR) - physical damage output
1. Defense (DEF) - danage resistance, pain tolerance
1. Agility (AGI) - mobility, limberness, evasiveness
1. Speed (SPD) - "SP" max speed, endurance 
1. Proficiency (PRO) - weapon handling, hands-on efficiency, finesse, dexterity, 
1. Magic (MAG) - "MP" magic output, compatibility
1. Charisma (CHR) - leadership, initiative, charm, apperance, perception, socialbility
1. Intelligence (INT) - iq, intuition, knowledge capacity, wisedom
1. Luck (LUC) - odds, opportunity chances, gambling
1. Fortitude (FRT) - "HP" constitution, recovery, Mental/Physical hardiness

- Extra
1. Skills - category / ability
1. Magics - type / spells
1. Arts - series / techniques
1. Companions - companion / stats
1. Party members - member / stats
1. Back Inventory - large inventory
1. Belt Inventory - small inventory

- Equipped
1. Primary - main/first weapon
1. Secondary - side/second weapon
1. Safety - last resort weapon 
1. Head - hats and helmets
1. Face - masks
1. Ears - earrings
1. Eyes - glasses and eyewear
1. Mouth - mouth and tooth accessories
1. Neck - chains and necklaces
1. Shoulders - capes and cloaks
1. Back - backpacks and bags
1. Chest - shirts snd chestplates
1. Arms - gauntlets
1. Wrist - bracelets
1. Fingers - gloves and rings
1. Waist - belts
1. Legs - pants and leggings
1. Ankles - socks and anklets
1. Feet - shoes and boots

- Status
1. Nourishment: Hunger
1. Hydration: Thirst
1. Energy: Exhastion, Fatigue
1. Oxygen: Suffocation
1. Consience: Sleep
1. Temperature: Frostbite <-- Freezing <--> Burning --> Heatstroke
1. Vision: - Nightvision <-(-)- Blind -(+)-> Vision
1. Condition: Bleeding, Injury, Cripple, Rot, Decay
1. Sanity: Sane --> Insane
1. Toxicity: Posion
1. Acidity: - Corosion
1. Mobility: Paralysis, bind, shock
1. Psyche: Fear
1. Confusion: - Disorient
1. Immunity: Disease, Sickness
1. Curse - Intention or Blight
1. Posession - Control

## Ambition
- Choose an ambition
- (2 stats boost + 2 focus-related skills)

# Faithful passion: Church focus
- FAI

# Hunter passion: Monster focus
- AGI

# Mercenary: Battle focus
- STR

# Knight: Kingdom focus
- DEF

# Merchant: Economic focus
- LUC

# Sailor: Aquatic focus
- FRT

# Politician: Government focus
- CHR

# Duelist: Sport focus
- PRO

# Scholar: Academic focus
- INT

# Magician: Arcane focus
- MAG INT

# Engineer: Builder Focus
- PRO INT

# Craftsman: Artistic focus
- PRO

# Outdoorsman: Survival focus
- FRT

# Bandit: Criminal focus
- AGI

REP: -500 to 500

-500 - realms
-400 - continent
-300 - country
-200 - city
-100 - town
0 - Neutral
100 - town
200 - city
300 - country
400 - continent
500 - realms


50’s are half of next tier



⁃ Start game

⁃ Pick name

⁃ Choose race (determines which port city spawned)

⁃ Choose cosmetic options

⁃ Choose an aspiring passion

⁃ transport ship drops off at port in minor city on TynFell Continent

⁃ Walk into city to register/start with whatever guild/org suits your passion

⁃ Hunters guild for hunters

⁃ Mercenary guild for mercenaries

⁃ Merchant guild for merchants

⁃ Knight Barracks for knights

⁃ Arena for duelists

⁃ Pierhouse for sailors

⁃ City hall for politicians

⁃ University for scholars

⁃ Mage guild for magicians

⁃ Smithy for craftsmen

⁃ Loggers for outdoorsman

⁃ Warehouse for bandit

⁃ Do few minor tasks to get all starter gear and info

⁃ Start Your Adventure!


Prophets are mortals that a star has chosen to guide their people in the way they see fit

Prophets - gods’ chosen messengers for carrying out their goals and ambitions


## Ferrent based NPCs

__Ferrent’s King__
: Eliyas, Dueling King (Laudquin)
> King of Ferrent that is famous for his earlier life as a renowned duelist (Inspired by)

__Top Ferrent Knight__
: Gualtier, First Sword (Laudquin)
> The best knight of Ferrent (Inspired by)

__Legendary Ranked Adventurer__
: Yahren, Low King (Marron)
> Solo adventurer that became one of the strongest. He wields incredible magic and deadly blade skills (Inspired by Solo Leveling)

## Evern based NPCs

__Evern’s Grand Elder__
: Ezua, Branch of Guidance (Dark Elf)
> Oldest and wisest elder of Evern. She is the leading branch of the Council and raised Evern to what it is today. Has a direct connection with the sentient World Tree, first given to them by the Prime Godess, extraordinary (Inspired by)

__Top Evern Keeper__
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

__Barri & Miel current Guildmaster__
: , ()
> Son of the original guildmasters

__ __
: , ()
> 

__ __
: , ()
> 

__ __
: , ()
> 

## Background


## Biographical Information
### Titles

### Alias

### Hobbies

### Goals


## Physical Information
### Apperance

### Personality


## Relationship Information
### Guardian

### Loyalties

### Enemies


## Equipment Information
### Powers

### Abilities

### Trump Cards

### Weapon


Champions are the chosen knight for a star on the mortal realm

Champions - closest connections to their patron god; represents them | protects their church

Jofiel - Sword

Marmou - Broadsword

Lynniel - Battleaxe

Grimini - Scythe

Hermle - Rapier

Radreal - Dual blade

• Only Prime gods have champions

• Champions have weapons & armor and bestowed by their god


⁃ Choose an ambition
⁃ (2 stats boost + 2 focus-related skills)

# Faithful passion: Church focus

 ARC

# Hunter passion: Monster focus

⁃ AGI

# Mercenary: Battle focus

⁃ STR

# Knight: Kingdom focus

⁃ DEF

# Merchant: Economic focus

⁃ LUC

# Sailor: Aquatic focus

⁃ FRT

# Politician: Government focus

⁃ CHR

# Duelist: Sport focus

⁃ PRO

# Scholar: Academic focus

⁃ INT

# Magician: Arcane focus

⁃ MAG INT

# Engineer: Builder Focus

⁃ PRO INT

# Craftsman: Artistic focus

⁃ PRO

# Outdoorsman: Survival focus

⁃ FRT

# Bandit: Criminal focus

⁃ AGI



- Popobawa (Devil bat)
- Harpy
- Gumyōchō (Twin head crane)
- Karura (Bird faced samurai)
- Caladrius (Healing crane)
- Gandabherunda (2 headed magic bird)
- Aralez (Winged wolf)
- Stymphalian (flesh hunting crow)
- Camazotz (Metal mountain gargoyle)
- Valravn (Giant wolf crow beast)
- Chamrosh (Winged wolf)

## Introduction


## Known Beasts
### Mountain Hawk
Large bird of prey that takes nests in high mountanous regions. It uses its steel like talons to sculpt out mountains for its nests. It will feed its chicks small goats and other beasts it can fish out of the peaks.

---

### Healing Bird
Medium sized bird that exudes a healing aura from its feathers. The older the bird, the stronger the healing effects from its feathers.

---

### Duck
Small bird that usually lives in small bodies of water. Floats atop the water to hunt for fish below. 

---

### Flamingo
Long legged, pink medium sized bird that has uses its tall stature to stomp and snuff prey in ponds and rivers below.  

---

### Crane
Long legged eastern birds that use its tall stature to catch fish below. 

---

### Monster
Goose

---

### Hawk
Medium sized bird of prey that dwells within forests. This bird uses its fast speeds and sharp talons to hunt beasts that also dwell in the forest and fields.

---

### Desert Scavenger
Large bird native to arid regions. The Desert Scavenger will scour the earth looking for carcassuses and corpses. It will hover above a likely target waiting for the perfect opprotunity to feast.  

---

### Shield Bird
Small, quick bird that when imprints on another, will ferociously protect and defend them with its life.

---

### Flare hawk
Medium sized bird that takes up residence in hot regions. Its feathers are imbued at birth with fire mana, allowing it to burst into flames when in danger.

---

### Poisonous Bird
Small bird that secrets a natural poison from its body that coats its feathers. This casues it to emit a dangerous cloud of poison when around.

---

### Monster
Nachtkrapp (Golem vulture)

---

### Monster
Gagana (Steeled bird)

---

### Monster
Bennu (Desert crane)

---

### Monster
Roc (Giant hawk)

---

### Monster
Three-legged bird (3 leg crow)

---

### Monster
anqa (4-winged keeper)

---

### Monster
Vermilion Bird (Blood red bird)

---

### Monster
Rain Bird (blue bird that culls storms)

---

### Monster
Double-headed eagle (Twin headed bird)

---

### Quadzal 
The quadzel is a giant bird that has the split ability of controlling 2 elements.

---

### Monster
Vucub Caquix (large evil Jungle parrot)

---

### Monster
Hummingbird

---

### Monster
Raven

---

### Monster
Crow

---

### Monster
Robin

---

### Monster
Bluejay

---

### Monster
Parrot

---

### Monster
Griffin

---

### Alicagel 
The alicagel is a bird that emits a certain radiance due to the different type of metal that it consumes.

---

### Fengzak 
The fengzak is a peacock like bird that has metal like feathers adorning their tail and wing feathers

---

### Rordmadra 
Rordmadra is a six winged storm bird that only appears when a great storm occurs. Many say that  due to the beat of its wings, small storms evolve to massive ones.


<br/>


## Named Beasts


### Jirreun
The jirreun is a large white bird beast that has the moniker of “man hunter”. The bird steals the face of its last prey. This human-face ability is used to disorient its next target.

---

### Gowineyes 
Gowineyes is a gigantic four-winged bird beast that settles on the tallest peaks. This great bird acts as the peacekeeper of the mountains, quelling all major disturbances to the area.

---

### Błudnik
Błudnik (White griffin)


- Cuthulu
- Leviathan
- Hippocampus (Horse fish)
- Grindylow (Frog squid monster)
- Loch Ness Monster
- 
- Shen (Trickster Sea dragon)
- Akhlut (Shark/orca beast)
- Tizheruk (large artic devil eel)
- Underwater panther (Evil cat fish)
- Abaia (Giant eel)
- Pisces (Twin fish guardians)
- Ika-Roa (Deep sea long shark fish)
- Shachihoko (Beast fish)
- Cai Cai-Vilu (Draconic eel)
- Ala (Mist sea serpent)

## Known Beasts

### Monster
Turtle

---

### Monster
Swordfish

---

### Monster
Shark

---

### Monster
Whale

---

### Monster
Dolphin

---

### Monster
Orca

---

### Monster
Squid

---

### Monster
Octopus

---

### Monster
Swordfish

---

### Monster
Bass

---

### Monster
Salmon

---

### Monster
Eel

---

### Monster
Pretty Fish

---

### Monster
Poisonfish

---

### Monster
Bluedragon

---

### Monster
Jellyfish

---

### Monster
Angler

---

### Monster
Manta Ray

---

### Monster
Crab

---

### Monster
Shrimp

---

### Monster
Lobster

---

### Monster
Large Fish

---

### Monster
Hammer Shark

---

### Monster
Mini Shark

---

### Monster
Mantis Shrimp

---

### Monster
Rockfish

---

### Monster
Pufferfish

---

### Monster
Schoolfish

---

### Monster
Catfish

---

### Monster
World Turtle (Island turtle)

---

### Monster
Karkinos (Giant terror Crab)

---

### Monster
Morgawr (Pleisiasur-like beast)

---

### Monster
Seahorse

---

### Monster
Isonade (Armored shark)

---

### Monster
Zaratan (giant crab w/ top wreck ship)

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Pirranha


<br/>


## Named Beasts


### Monster
Devil Whale (Moby Dick)

---

### Monster
Kraken BOSS

---

### Monster
Makara (Serpent dragon)

---

### Monster
Bahamut (world whale)

---

### Monster
Charybdis


### Monster
Chimera

---

### Monster
Automaton

---

### Monster
Golem

---

### Monster
Homunculus 

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start


<br/>


## Named Beasts


### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start


- Yalbao (lion-headed multi-armed serpent)


### Caine
The caine is a dog beast that is smaller than a wolve that is commonly domesticated for hunting purposes.

---

### Lye on
Lion

---

### Tigreer
Tiger

---

### Threshuma
Puma

---

### Feneke
Fox

---

### Monster
Hyena

---

### Jagyion
Jaguar

---

### Caprical
Goat

---

### Oviterre 
The oviterre remains in mountainous areas and is fond of raising special flowers. (Mountain goat)

---

### Mowool
Sheep

---

### Honbear
Bear

---

### Eiknoll
The eiknoll is a deer beast that is covered head to hoof in a large shag pelt that keeps it warm in Torfrost’s harsh enviroment. (elk)

---

### Giantnoll
Moose

---

### Wolitzol
Wolf

---

### Stontaur 
Stontaur is a large bovine beast that is largely covered in hard stones.

---

### bull
Bull

---

### Hornbit 
The hornbit is a horned rabbit beast that uses its horns to retrieve fruits growing in high places. (rabbit)

---

### Monster
Horse

---

### Borswine
The borswine is a spiked swinal beast that tastes great on a low simmer. (Boar)

---

### Hippoar
The hippoar claims kingship of the waters of the great savanna. (Hippo)

---

### Monkree
The monkree maintains its dominance within the trees of the land. (Monkey)

---

### Monster
Orangatan

---

### Monster
Gorilla

---

### Monster
Cougar

---

### Monster
Tasmaine Devil

---

### Monster
Badger

---

### Monster
Lynx

---

### Karkron 
The karkron is a beefy horned rhinock beast that mainly resides in the Sunbarrens. It uses its strong legs and armor plated Front to bulldoze trees to reach high growing fruit. (Rhino)

---

### Monster
Mandrill

---

### Eleont 
The eleont boasts the one of the largest beastial masses on the land (Elephant)

---

### Monster
Bison

---

### Monster
Squirrel

---

### Monster
deer 

---

### Monster
Cat

---

### Monster
Reindeer

---

### Monster
Raccoon

---

### Monster
Skunk

---

### Monster
Panther

---

### Monster
Snow Fox

---

### Threshuma 
The threshuma is a cat beast that has an iron like ball apendage at the end of its tail. It uses it to construct its den and break down the structure of its prey.

---

### Monster
Ocelot

---

### Monster
Walrus

---

### Monster
Beaver

---

### Monster
Gopher

---

### Monster
Otter

---

### Monster
Koala

---

### Monster
Panda

---

### Monster
Weazel

---

### Monster
Rat

---

### Monster
Coyote

---

### Monster
Chimp

---

### Monster
Ice Wolf

---

### Monster
Polar Bear

---

### Monster
Cheetah

---

### Monster
Llama

---

### Cockfyre 
The cockfyre is a small winged chicken beast that breaths a small amount of fire to toast plants and berries to eat while also using it to fend off predators. (chicken)

---

### Vulpe
The Vulpe is a small beast that snickers.

### Forest Wolve
The wolve is a dangerous beast that hunts in packs to reduce their prey to bone.

### Hyaena
The hyaena is a wolve sized beast that roams the savanna lands in large packs, often hunting or playing.

### Marther
The marther is a cat beast that shares the same size of a panther. They reside in Gerkin and differ from their counterpart by using the bog water to hunt, often leaping from the depths to secure a kill.

### Pantere
The pantere is a large cat beast that is equipped with long metal-like quills.

### 
The tyger is a 2 horned cat beast that lives mainly in jungle regions.


### Bearve 
The bearve is tall and wide cat bear beast that lurks uptop woodland trees to ground slam unsuspecting prey from above with great force.

### Frotbull 
The frotbull native to artic regions protects itself by coating its horns underwater and letting them freeze to create frozen spikes.


### Tundra Wolve
Large wolves that reside in Altin, Torfrost, and Alphi.

###  Desertooth
The desertooth is an aggressive tigre beast that roams the Bacombe and Khasu regions.

### Tunki 
Tunki are small volpe-pandu like beasts that commonly act as forest tricksters. They use the sticky saliva they spit to create small traps for their prey or escaping predators.

### Bandmare 
The bandmare is a large black horse that is known for its unforgiving nature. Bandmare’s are often preferred by high value criminals since they have the skill to disappear into the shadows.


### Bicorn
The bicorn is a mare beast that is rather territorial but is commonly tamed for human use.

### Ursuwool 
The ursuwool is a large horned wooly baer beast that resides in the tundra or artic.

### Loddet
The Loddet is an amphibious cat beast that is equipped with fish like features. Its webbed feet help it to quickly navigate rivers and lakes to fish.

### Peyteer
The peyteer is a large deer-like beast that has wings. These wings allow the beast to quickly escape predators on the open artic fields.

### Cugoar 
The cugoar is a six-legged cat beast

### Lonix 
The lonix is a small cat beast from the tundra regions. It’s small but spread paws allow it to quickly maneuver through the snow.

### Baera
The baera is a large uruic beast that hunts as one of the top predators of the forest.

### Paaglin
The Paaglin is a large armored rodent.


### Black Vulpe 
The black vulpe is a dangerous beast that is considerably larger than a wolve but smaller than a tundra wolve. They are far more agreesive than their smaller brethren. It is said to use a form of dark magic to confuse and ensnare their prey.

### Feral Hyaena
The feral hyaena is an evolved hyaena that is far deadlier and in considerably smaller packs.

### Goldtag
The goldtag is a deer beast famous for its unique pure gold antlers that it develops in its adulthood. They are rare due to being hunted for such a commodity and are very sensitive to movement and vibrations. It taps its horns on the ground to check the area for predators.

### Tranmare
The tranmare is an eight legged mare beast that is said to be extremely difficult to find and tame. It will maintain its dominant nature unless a deep enough connection is formed.

### Unihorn
The mysterious unihorn is a special mare beast that is identified by its long singular horn that has the ability to store mana.

### White Eilk 
The white eilk is a magic white deer beast that is native to Evern’s magical forest. It has the ability to store mana in its antlers to use different types of magics.


<br/>


## Named Beasts


### Errasobeast 
The Errasobeast is a six-legged Lyon-like beast that has a grey body and thick quill-like appendages on its back. It is highly aggressive and devastates the area once agitated. They only reside near dungeons to feed off of the dungeon's internal energy. It emerges from its resting when it' sfood source is greatly disturbed.

---

### Juggareth
Juggareth is an ancient beast that is extremely territorial. It behaves as the peacekeeper of its domain. It’s said that if the place in which it claims was ever razed, it would again walk the Earth to send the cause of the ruination to the gates of Shogrinn.

---

### Kahlverd
Is a threat of a beast. It escaped from captivity through a massacre and is now roaming the countryside.

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Wulgrinn the Jagged
Wulgrinn is an elusive giant lightning wolve that appears rarely when a destructive storm appears. No one has ever gotten a good view of this famous beast and lived to tell the tale.

---

### Brutus the Chained Malice
Brutus is a devil of a beast.


- Chalkydri (Heavenly sun bird)
- Angel
- Valkyrie
- Pegasus GARD


### Monster
Ifrit (top fire spirit)

---

### Monster
Undine (high water spirit)

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

- Phoenix (high fire spirit)
- 
- 
- Huma bird (Twin-headed/elements (storm+fire) spirit)
- Lampad (High light spirit)
- Bluecap (Bluefire spirit)
- Amefurikozō (Rain spirit)
- Buggane (Giant lightning juggernaut)
- Nix (Moon dark spirit)


### Monster
Carbunckle (Jewel flame fox)

---

### Monster
Gargoyle

---

### Monster
Asag (Rockfire titan)

---

### Monster
Start

---

### Monster
Gargouille (Desert stone golem statue)

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start


<br/>


## Named Beasts


### Monster
Bulgasari (Giant bone-rock behemoth titan)


## Introduction
Guardians are the caretakers of the realms that their Lords have crafted

##
Supreme One's Seal
- White Being

## Gelalios
Bahanna Guardian
- Pegasus

##
Time Guardian
- Spider 

## 
Teorlan Magic Guardian
- Fairy

## 
Borealis Dream Guardian
- 

## Kesisumera
Estean Sky Guardian
- Original Dragon

## Mahmu
Estean Land Guardian
- Terrelyon

## Blaskam
Estean Sea Guardian
- Leviathan

##
Law Guardian
- Griffin

##
War Guardian
- Bull Behemoth

##
Wise Guardian
- Turtle

##
Love Guardian
- Dove

##
Forge Guardian
- Phoonix

##
Trade Guardian
- Pig

##
Luck Guardian
- Fox

##
Hunt Guardian
- Bear

##
Medicine Guardian
- 

##
Pride Guardian
- Wolf

##
Wrath Guardian
- 

##
Witch Guardian
- Black Cat

##
Lust Guardian
- 

##
Sloth Guardian
- Sloth

##
Nightmare Guardian
- 

##
Greed Guardian
- Basilisk

##
Misfortune Guardian
- 

##
Gluttony Guardian
- 

##
Envy Guardian
- 

## Zhillegoh
Jathal Guardian
- Chuthulu

## 
Ulrith Guardian
- 

##
Chaos Guardian
- 

##
Death Guardian
- Crow

## Hezgaur
Shogrinn Guardian
- Cerberus

## 
Mark of The End
- Black Being



- Bigfoot (Forest Yeti)
- Werejaguar
- Werehyena 
- Mapinguari (Wild Thing/Sloth Yeti)
- Gremlin
- Bugbear (Feral beastman warrior)
- Adlet (Arctic feral wolf warrior)
- Demon Cat (Evil cat warrior)
- Ajatar (Winged gorgon)
- Pabilsag (Standing scorpion-man)
- Echidna (snake woman)
- Matagot (Aggressive slim warrior cat)
- Merrow (Armored mermaid)
- Samebito (Sharkin warrior)
- Redcap (Gnome warrior)
- Garuda (Hawkman) 
- Maahes (Lionkin warrior)

## Introduction


## Known Beasts
### Monster
Goblin

---

### Monster
Hobgoblin

---

### Monster
Yeti

---

### Monster
Siren

---

### Monster
Kobold

---

### Monster
Cyclops

---

### Monster
Gnome

---

### Monster
Minotaur

---

### Monster
Centaur

---

### Monster
Troll

---

### Monster
Werewolf

---

### Monster
Hibagon (Bipedal white mountain orangatan)

---

### Monster
Kappa (feral Turtlkin)

---

### Monster
Zhu Bajie (pigkin warrior

---

### Monster
Tengu (birdman warrior)

---

### Monster
Gurangatch (replikin (gator) warrior)

---

### Monster
Vanara (Monkey warrior)


<br/>


## Named Beasts


### Monster
Ox-Head (Twin beastkin DBoss)

---

### Monster
Horse-Face (Twin beastkin DBoss)

---

### Monster
Hrimthurs (frost troll warrior)

---

### Monster
Chiron (War centaur)

---

### Monster
Xing Tian (Giant war titan)

---

### Monster
Geryon (Three faced troll)


- Hekatonkheires (Many appendige demon)
- Preta (soulless hungry ghoul)
- Sigbin (Forest possum devil)
- Owlman (Evil birdaman)
- Jikininki (Aggressive zombie demon)
- Keresh (Fallen Angel warrior)
- Pooka (Black rabbit tree devil)
- Strix (Antlered owl bat devil)

## Introduction


## Known Beasts
### Monster
Imp (small flying devil)

---

### Monster
Hellhound (Evil Dog)

---

### Monster
Incubus / Succubus (Lust demon)

---

### Monster
Bak (One eyed beast devil)

---

### Monster
Daimon (Frost winged devil)

---

### Monster
Aswang (Ghoul vampire/psuedo vampire)

---

### Monster
Ijiraq (deer beast devil)

---

### Monster
Hekatonkheires (Many body (grafted) devil)

---

### Monster
Cherufe (Lava titan)

---

### Monster
Orthrus (Lesser cerberus)

---

### Monster
Namazu (Giant black fish devil)

---

### Monster
Huodou (Fire breathing wolf)

---

### Monster
Raróg (fiery demon falcon)

---

### Monster
Ushi-oni (Horned spider devil)

---

### Monster
Mothman (Horror man moth)

---

### Monster
Start

---

### Monster
Start


<br/>


## Named Beasts


### Monster
Garm (Devil wolf) DBOSS

---

### Monster
Mandurugo (6-winged fallen angel devil)

---

### Monster
Yamata no Orochi (9 headed hydra demon)

---

### Monster
Asura (multi armed strength demon)

---

### Monster
Cerberus GARD

---

### Monster
Kamaitachi (White mist fox demon)

---

### Monster
Sharabha (Lion headed demon warrior)


Beetle

---

### Monster
Mantis

---

### Monster
Bee

---

### Monster
Wasp

---

### Monster
Mosquito

---

### Monster
Dragonfly

---

### Monster
Caterpillar

---

### Monster
Spider

---

### Monster
Trick Spider

---

### Monster
Ant

---

### Monster
Scorpion

---

### Monster
Sun Beetle

---

### Monster
Abatwa (Warrior ant)

---

### Monster
Gold-Digging Ant

---

### Monster
Termite

---

### Monster
Cicada

---

### Monster
Arachne (Spider queen woman)

---

### Monster
Butterfly

---

### Monster
False Butterfly

---

### Monster
Water skitter

---

### Monster
Khepri (Solar beetle)

---

### Monster
Roach

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

<br/>


## Named Beasts


### Monster
Scorpion man (BOSS)

---

### Monster
Tsuchigumo (Evil spider)


__Land Before Shogrinn's Dungeon Boss__
: Balbis, The First Demon Monarch (Demon Royal)

> G (Inspired by)

__Penrigon's Dungeon Boss__
: Modaraithu, The Cursed God (Original Dragon)

> Cursed Dragon (Inspired by)

__Hor's Gate's Dungeon Boss__
: Frorshneel, The Calamity Cold (Frost Dragon “”)

> G (Inspired by "World After the End" ice dragon)

__Orthorix's Dungeon Boss__
: Pau, Fallen Archangel (fallen angel)

> G (Inspired by)

__Forgotten Hollow's Dungeon Boss__
: Abu, The Last Carnic Beast (Relic Beast “Swallow”)

> G (Inspired by)

__The Depth's Dungeon Boss__
: ,  (Leviathan)

> G (Inspired by)

__Nalgarden's Dungeon Boss__
: Yinnigur, The Ending Tree (Ancient Tree)

> G (Inspired by)

__Ancestral Plain's Dungeon Boss__
: ,  (Yokai)

> G (Inspired by)

__Deousgon's Dungeon Boss__
: ,  (Giant)

> G (Inspired by)

__Colussus's Dungeon Boss__
: Zermyr, The Bloodletter (Guardian Snake)

> G (Inspired by)



Tree

---

### Monster
Rose

---

### Monster
Flower

---

### Monster
Dryad

---

### Monster
Cactus

---

### Monster
Mandrake (Living vegtable)

---

### Monster
Ghillie Dhu (Forest protector)

---

### Monster
Spriggan (Magic forest plant sorceror)

---

### Monster
Live Vines

---

### Monster
Flytrap

---

### Monster
Snake Tree (Agressive poison tree)

---

### Monster
Alraune (plant woman trap)

---

### Monster
Hamadryad (withering tree spirit)

---

### Monster
Vegetable Lamb of Tartary (Prey trick plant)

---

### Monster
Ent

---

### Monster
Jubokko (Evil tree titan)

---

### Monster
Swamp monster (Bog yeti)


<br/>


## Named Beasts


### Monster
Wendigo (Bone thorn devil)

---

### Monster
Yggdrasil


- Mokele-mbembe (Spiked bronto)
- Bakunawa (Eel-like dragon)
- Lindworm (Quilled mountain snake)

## Known Beasts
### Monster
Drake (Low Dragon)

---

### Monster
Wyvern (Mid dragon)

---

### Monster
Dragon (True dragon)

---

### Monster
Snake

---

### Monster
Salamander (Fire breathing lizard)

---

### Monster
Lizard

---

### Monster
Basilisk (Evil snake)

---

### Monster
Turtle

---

### Monster
Gator

---

### Monster
Cipactli (Stone gator)

---

### Monster
Níðhöggr (metal drake)

---

### Monster
Sand lizard devil

---

### Monster
Hoop snake (metal snake that attacks with rolling)

---

### Monster
Peluda (Quilled lizard)

---

### Monster
Tarasque (Juggernaut turtle beast)

---

### Monster
Garafena (Gold snake)

---

### Monster
Mungoon-Gali (Giant komodo lizard)

---

### Monster
Grootslang (horned snake)

---

### Monster
Chinese dragon (long cloud dragon)

---

### Monster
Gila (poison lizard)

---

### Monster
Tarand (Horned wyvern)

---

### Monster
Azhi Dahaka (3 headed dragon)

---

### Monster
Amphisbaena (Winged desert basilisk)

---

### Monster
Komodo (Land dragon)

---

### Monster
Hydra (multi headed snake dragon)

---

### Monster
Amphithere (thin long snake dragon)

---

### Monster
Whowie (Slender aggressive cave lizard)

---

### Monster
Jiaolong (Dragon headed forest horse/lizard)

---

### Monster
Dingonek (Spiked lizard)

---

### Monster
Mirage Lizard



- Phantom cat (Lionkin spirit)

## Introduction


## Known Beasts
### Monster
Will-o'-the-wisp (Grave spirit)

---

### Monster
Djinn (Genie)

---

### Monster
Pixie

---

### Monster
Familiar (Magic animal spirit)

---

### Monster
Yokai (Evil spirit)

---

### Monster
Kitsune (Fox spirit) 

---

### Monster
Sandman (Dream spirit)

---

### Monster
Tsukumogami (Spirits that possecess objects that come to life, of their own accord)

---

### Monster
Saci (Black djinn)

---

### Monster
Nephele (cloud/weather spirit)

---

### Monster
Zduhać (Mountain spirit)

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start


<br/>


## Named Beasts

### Monster 
The sphinx is a desert guardian that is summoned to protect precious ancient desert dungeons and tombs. They have the special ability of self petrification that allows it to maintain its lifespan for centuries.

---

### Ferrolon
The ferrolon is a metal winged lyeon beast that is summoned to protect antient mountain temples and dungeons.

---

### Monster
Huli jing (Kitsune spirit woman)

---

### Monster
Asteriae (Star garden spirit)

---

### Monster
Shen (Holy mountain spirit)


Worm

---

### Monster
Mole

---

### Monster
Death Worm

---

### Monster
Bat

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start


<br/>


## Named Beasts


### Monster
Camazotz (Ancient Bat)


Vampire

---

### Monster
Dullahan

---

### Monster
Corpse Dragon

---

### Monster
Lich (Skeleton necromancer)

---

### Monster
Mummy (Desert Zombie)

---

### Monster
Living Armor (Possesed Armor)

---

### Monster
Zombie

---

### Monster
Nightmare (Sleep dream demon)

---

### Monster
Dragur (Frost warrior Zombie)

---

### Monster
Ghost

---

### Monster
Skeleton

---

### Monster
Ghoul (Strong zombie)

---

### Monster
Poltergeist (Ghost that posesses objects)

---

### Monster
Oni (Dead devil warrior)

---

### Monster
Black dog (Grave guarddog)

---

### Monster
Devil Bird (Death Bird)

---

### Monster
Revenant (Evil warrior ghost)

---

### Monster
Gashadokuro (Mega skelton)

---

### Monster
Bogeyman (Black mind demon)

---

### Monster
Wraith (Vengeful spirit)

---

### Monster
Reaper (Soul harvester)

---

### Monster
Lemures (Withering dryad)

---

### Monster
Shadow People

---

### Monster
Umibōzu (Giant sunken titan being)

---

### Monster
Wendigo (Vengeful animal spirit)

---

### Monster
Chindi (Evil soul)

---

### Monster
Anaye (Rememberance item possession spirit)

---

### Monster
Mokumokuren (illusion ghost)

---

### Monster
Jiangshi (Sorceror ghost)

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start

---

### Monster
Start


<br/>


## Named Beasts


### Monster
Wild Hunt (Dead summoner that brings a horde)

---

### Monster
Makhai (Black multi arm-knives fighter)

---

### Monster
Hysminai (Female black knight ghoul)

---

### Monster
Jorōgumo (Ghost spider woman)

---

### Monster
Bake-kujira (Ghost whale)

---

### Monster
Start

---

### Monster
Start

- Nuckelavee (Undead horse)
- Vetala (Vampire corpse bat)
- Barghest (Ghoul dog)
- Banshee (vengeful female ghost)
- Kodama (Wandering ghost)
- Nukekubi (Head ghost)
- Stiff-Legged Bear (Giant bear ghoul)
- Cu Sith Hellhound (Giant green skull ghoul wolf)
- Cat-sìth (Death cat)
- Kasha (Flaming graverobbing lionkin ghoul)
- Sin-you (Green ghoul unicorn)
- Kun (Giant floating shark ghast)
- Noppera-bō (faceless ghoul)
- Chonchon (Flying head ghoul)
- Bakeneko (Giant cat ghoul)
- Keres (Flying female reaper)
- Kuchisake-onna (Beautiful female nightmare spirit)
- Futakuchi-onna (demon woman w/ hair devil)


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


## Types of Ratings

### Grades
Grades are the rating terminology used to describe items.

### Classes
Grades are the rating terminology used to describe people.

### Levels
Grades are the rating terminology used to describe monsters and creatures.

### Tiers
Grades are the rating terminology used to describe abilities.

| Rating Letters | Item Grades    | Skill Stars | Magic Tiers    | Art Ranks         | Person Classes | Monster Levels |
|----------------|----------------|-------------|----------------|-------------------|----------------|----------------|
|       U        | Sacred Grade   | White Star  | Divine Tier    | Lord Rank         | Heaven Class   | O Level        |
|       S+       | Unique Grade   | Blue Stars  | Supreme Tier   | King Rank         | Revered Class  | ??? Level      |
|       S        | Grand Grade    | Red Stars   | Legendary Tier | Duke Rank         | Elite Class    | X Level        |
|       A        | Top Grade      | 5-Stars     | Superior Tier  | Master Rank       | First Class    | V Level        |
|       B        | High Grade     | 4-Stars     | High Tier      | Expert Rank       | Second Class   | IV Level       |
|       C        | Good Grade     | 3-Stars     | Mid Tier       | Intermediate Rank | Third Class    | III Level      |
|       D        | Low Grade      | 2-Stars     | Low Tier       | Apprentice Rank   | Fourth Class   | II Level       |
|       F        | Bad Grade      | 1-Star      | Basic Tier     | Beginner Rank     | Fifth Class    | I Level        |

## Rating Standards

### F Standard Ratings
F standard ratings are assigned to enteties that are basic or terrible. 

### D Standard Ratings
D standard ratings are given to entites that are poor compared to others. They are either an improvement from basic or just low in Grade.

### C Standard Ratings
C standard ratings are entites that are mediocre in value. They are not the worst, nor are they the best.

### B Standard Ratings
B standard ratings are assigned to entities that are great. As the median of the scale, these entities are wholeheartedly great compared to others.

### A Standard Ratings
A standard ratings are denoted to entities that are elites. They 

### S Standard Ratings
S standard ratings are deemed to entites that are the best of the best. They are truly peerless. 

### S+ Standard Ratings
S+ standard ratings are reserved to entities that are stronger than S rank but are impossible to guage further, technically remaining rankless. These entities are the top echelon of the mortal realm, just ranking below divinty.

### U Standard Ratings
U standard ratings are bestowed to entities that are beyond mortal comprehension and part of the realm of the Gods. These are entities created by Gods and dieities.


Offense
Melee
Fast - assassin
Mid - swordsman 
Slow - warrior

Magic
Fast - 
Mid - 
Slow - 

Tech
Fast
Mid
Slow

Defense
Melee
Fast - 
Mid - knight
Slow - tank

Magic
Fast
Mid
Slow

Tech
Fast
Mid
Slow

Range
Melee
Fast
Mid
Slow

Magic
Fast
Mid
Slow

Tech
Fast
Mid
Slow

Support
Melee
Fast
Mid
Slow

Magic
Fast
Mid - 
Slow - priest

Tech
Fast
Mid
Slow


Knight
Crusader
Blacksmith
Alchemist
Hunter/Huntress
Mercenary
Sailor
Captain
Lieutenant
General
Warden
Noble
King/Queen
Emperor/Empress
Prince/Princess
Duke/Duchess
Marquis/Marchioness
Earl
Count/Countess
Viscount/Viscountess
Baron/Baroness
Traitor
Royal
Artist
Soldier
Mage
Tanker
Witch
Archer
Spearman
Swordsman
Ninja
Ronin
Samurai
Merchant
Guildmaster
Painter
Architect
Engineer
Mechanist
Gatekeeper
Guardian
Demigod
Slayer
Oathkeeper
Master
Legend
Guard
Doctor
Medic
Tyrant
Traitor
Herbalist
Owner
Thief
Craftsman
Farmer
Monster Hunter

Actor  
Advocate (Lawyer)  
Alchemist
Animal Handler  
Apothecary  
Architect
Archer  
Archivist  
Aristocrat
Armorer  
Artisan  
Artist
Astrologer  
Baker  
Banker
Barbarian  
Barber  
Bard
Barkeep  
Barmaid  
Beekeeper
Beer Seller  
Beggar  
Blacksmith
Boatman  
Bookbinder  
Bookseller
Brewer  
Bricklayer  
Brick Maker
Brigand  
Brothel Keeper  
Buckle Maker
Builder  
Butcher  
Caravan Leader
Carpenter  
Cartographer  
Chandler
Charioteer  
Chatelaine  
Chef
Chieftain  
Chirurgeon  
Clergyman
Clerk  
Clock Maker  
Clothworker
Cobbler  
Commander  
Concubine
Cook  
Cooper  
Copyist
Costermonger  
Counselor  
Courtesan
Courtier  
Cowherd  
Crossbowman
Cutler  
Daimyo  
Dairymaid
Dancer  
Dictator  
Diplomat
Distiller  
Diver  
Diviner
Doctor  
Domestic Servant  
Emperor/Empress
Eunuch  
Explorer  
Farmer
Fighter  
Fisherman  
Fishmonger
Footman  
Furrier  
Galley Slave
Gardener  
Geisha  
General
Gladiator  
Glovemaker  
Goldsmith
Grocer  
Groom  
Guardsman
Guildmaster  
Harness maker  
Hatmaker
Hay merchant  
Healer  
Hearthwitch
Herald  
Herbalist  
Herder
Hermit  
Highwayman  
Historian
Housemaid  
Hunter  
Illuminator
Infantryman  
Innkeeper  
Interpreter
Inventor  
Jailer  
Jester
Jeweler  
Jongleur  
Judge
King  
Kitchen drudge  
Knight
Laborer  
Lady  
Lady in Waiting
Leatherworker  
Librarian  
Linguist
Locksmith  
Longbowman  
Longshoreman
Lord  
Maidservant  
Majordomo
Man at Arms  
Mason  
Masseur
Mayor  
Mercer  
Merchant
Messenger  
Midwife  
Miller
Miner  
Minister  
Minstrel
Monk  
Mortician  
Mourner
Musician  
Necromancer  
Noble
Nun  
Nurse  
Old-clothes seller
Page  
Painter  
Pariah
Pastry cook  
Peasant  
Perfumer
Philosopher  
Physician  
Pigkeeper
Pilgrim  
Pirate  
Plasterer
Potter  
Priest/ess  
Prince/ss
Privateer  
Professor  
Prostitute
Pursemaker  
Queen  
Ranger
Ratcatcher  
Reeve  
Ronin
Roofer  
Ropemaker  
Royal Adviser
Rugmaker  
Ruler  
Saddler
Sailor  
Samurai  
Scabbard maker
Sculptor  
Scavenger  
Scholar
Scrivener  
Seamstress  
Servant
Shaman  
Shepherd  
Ship's captain
Shoemaker  
Silversmith  
Slave
Slaver  
Smith  
Soldier
Sorcerer/Sorceress  
Spice Merchant  
Squire
Stablehand  
Stevedore  
Stonemason
Storyteller  
Steward  
Street kid
Street seller  
Street sweeper  
Student
Surgeon  
Surveyor  
Swordsman
Sycophant  
Tailor  
Tanner
Tavernkeeper  
Tax collector  
Teacher
Teamster  
Thatcher  
Thief
Tinker  
Torturer  
Town crier
Toymaker  
Trapper  
Vendor
Vermin catcher  
Veterinarian  
Village chief
Vintner  
Viking  
Warlock
Warrior  
Water carrier  
Weaver
Wetnurse  
Wine seller  
Witch
Wizard  
Woodcarver  
Woodcutter
Wood seller  
Wrestler  
Writer


HP (Health points)	Individual’s health capacity	1000 HP
MP (Magic points)	Individual’s magical capacity	500 MP
SP (Stamina points)	Individual’s endurance capacity	300 SP
Strength 	Individual’s damage output	Unleashing a powerful attack
Defense	Individual’s damage absorption	Holding up against a strong attack
Agility	Individual’s evasiveness 	Dodging an attack quicker
Speed	Individual’s movement rate	Moving faster and for longer
Proficiency	Individual’s handling	Picking up a sword technique faster
Magic	Individual’s magic effectiveness	Making a bigger magic explosion 
Charisma	Individual’s social ability	Winning the hearts of citizens
Intelligence 	Individual’s mental ability	Understanding an ancient scroll
Fortitude	Individual’s constitution	Surviving longer in cold conditions
Luck	Individual’s fortune rate	Finding hidden loot in dungeons
Skill	Specialization of an action due to constant practice 	Crafting
Spell	Product of refining mana into the body using a branch of magic	Flamethrower 
Weapon Art	Ability to perform special moves with weapons due to certain level of mastery	Swift blade
Sigil	A sketched circular pattern that is essential part of alchemy allowing the mutation of natural elements	A blood sacrifice sigil
Scroll	A paper document with a magic inscription that activates the spell written	Whirlpool scroll
Rune	Dwarven engineering magic language in-scripted on a surface material like stone, metal, etc.	Reinforcement rune
Alchemy	The use of uncommon ingredients to produce effective elixirs and potions of various effects 	Creating a strength potion 
U Class	god or godlike entities	Lynniel
S+ Class	Rank-less Legends	Yahren
S Class	World class individuals	Platinum rank
A Class	Elite individuals 	Gold rank
B Class	Seasoned adventurers	Silver rank
C Class	Average adventurers	Bronze rank
D Class	Novice adventurers	Iron rank
F Class	Civilians	Farmer
U Grade	Items wielded or blessed by the gods	Montero’s Blade of Judgement
S+ Grade	Ungradable items 	Yahren’s Felled Star
S Grade	Peerless items	Nyl La Sic
A Grade	Elite items	Yordsteel sword
B Grade	Quality items	Reinforced sword
C Grade	Average items	Steel sword
D Grade	Poorly made items	Iron sword
F Grade	Awful items	Wood sword
U Tier	Magic derived from the gods	Original fire magic
S+ Tier	Supreme magic	Hellfire magic
S Tier	Legendary magic	Holyfire magic
A Tier	Powerful magic	Inferno magic
B Tier	Effective magic	Blaze
C Tier	Useful magic	Flame
D Tier	Basic magic	Fire
F Tier	Simple magic	Spark magic
The Triginsidus	Religion of the continent based off the 15 daystars and 15 dawnstars that represent the Almighty and Astrayed gods 	Osiri and Khuluthlun
Dungeon	Unnatural ruins that spawn off the god of chaos’s excess energy. Births beasts and monsters to inhabit these structures which also contain equal fortunes to the danger	The Undeground Mausoleum 	
Osiri	The Supreme Morningstar 	
Jofiel	The Prime Holystar 	
Lynniel	The Prime Lifestar	
Hermle	The Prime Timestar	
Montero	The Major Lawstar	
Uran	The Major Warstar	
Wolford	The Major Magicstar	
Yukire	The Major Dreamstar	
Sage	The Major Bookstar	
Crozzen	The Major Craftstar	
Agil	The Major Tradestar	
Veneti	The Major Luckstar	
Rachess	The Major Huntstar	
Asanna	The Major Lovestar	
Bingeal	The Major Chemstar	
Khuthulan	The Supreme Nightstar 	
Marmou	The Prime Darkstar 	
Grimini	The Prime Deathstar	
Lucficien	The Prime Chaostar	
Krenari	The Major Pridestar	
Gahar	The Major Wrathstar	
Verbel	The Major Witchstar	
Inachtra	The Major Nightmarestar	
Zakzano	The Major Forbiddenstar	
Perizay	The Major Slothstar	
Lahkus	The Major Greedstar	
Teher	The Major Cursestar	
Eirnin	The Major Gluttstar	
Himhia	The Major Luststar	
Neieba	The Major Envystar

## General
| Term	| Definition	| Example |
| :--:	| :--------:	| :-----: |
| Mana	| Natural energy that radiates from the nature	| Red mana |
| Aura | Product of honing your soul and life force to draw out latent energy | Burning aura |
| Health Points | Total and remaining life of a living being | HP |
| Stamina Points | Total and remaining energy of a living being | SP |
| Mana Points | Total and remaining mana in a living beings' mana pool | MP |
| term | def | ex |


## Locations
Bahen
Glisscar
Sunfell
Autian
Ighura
Feua
Ehona Plum
Monogoro
Ekryaim
Wyntolm
Balawyn
Yaaonhel
Aloore

## People
"Follow me my brothers! I will lead you too an "

## Entities
Racist human group

## Monsters

## Abilities
Horns of Gabriel - Holy Magic debuff
Hand of God

## Items


## Weapons


## Inspiration from Bible
God's special garden
God's good tree
The evil tree
Cunning Devil
Angel guarding garden
Guardian weilding flaming sword that "turned every which way"
God's death brand curse on Cain
God destroy world with a disaster
Holy boat to save blessed ones
God's covenant with Man (rainbow)
Man made (God Defying) Mega structure
God strike against man for defying



Foundation (Earth) unmovable stances
Flow (Water)  switch between opponents
Internal (Air)  power yourself
External (Fire)  power a thing
Manifestation (Light)  summon/bring out something
Possession (Dark)  use/take control of something
Expansion (Space)  change spacing in combat
Progression (Time) manipulate processes

1. Earth – Foundation
	•	Concept: Aura used for stability, grounding, and resilience.
	•	Martial Application: Techniques that enhance balance, unshakable stances, or create an immovable presence. Users can anchor themselves or others, resist force, or serve as the “foundation” for allies.
2. Water – Flow
	•	Concept: Aura used for adaptability, fluidity, and seamless movement.
	•	Martial Application: Techniques that allow for smooth transitions between attacks and defenses, redirecting force, or adapting to any combat situation. Users excel at changing tactics and flowing with the battle.
3. Air – Internal
	•	Concept: Aura used to empower oneself internally.
	•	Martial Application: Techniques that boost physical or mental capabilities—speed, reflexes, senses, or focus. Users enhance their own body and mind.
4. Fire – External
	•	Concept: Aura used to empower external objects or the environment.
	•	Martial Application: Techniques that imbue weapons, armor, or the battlefield with aura, making them more effective or granting special properties.
5. Light – Manifestation
	•	Concept: Aura used to create or summon things into existence.
	•	Martial Application: Techniques that bring forth constructs, illusions, or other manifestations from aura.
6. Dark – Possession
	•	Concept: Aura used to take control or influence.
	•	Martial Application: Techniques that seize control of objects, people, or even aspects of the environment. Users might manipulate opponents or animate objects.
7. Space – Expansion
	•	Concept: Aura used to extend reach, influence, or presence.
	•	Martial Application: Techniques that allow users to affect distant targets, expand their aura field, or manipulate spacing in combat.
8. Time – Progression
	•	Concept: Aura used to accelerate or decelerate processes.
	•	Martial Application: Techniques that hasten recovery, speed up actions, or delay effects. Users can manipulate the tempo of battle or their own growth.

Tips for Further Depth
	•	Hybrid Techniques: Allow advanced users to combine two elements (e.g., Earth + Water = adaptive armor that heals itself).
	•	Mastery Levels: Unlock new abilities as users deepen their connection to an element.
	•	Visual Flair: Each element’s aura should look and feel distinct (e.g., Earth aura is solid and geometric, Water is fluid and shifting, etc.).

What You Have
	•	Earth
	•	Water
	•	Internal (Air): Use aura to power yourself (enhance body, speed, senses, etc.)
	•	External (Fire): Use aura to power a weapon/thing (imbue objects with aura)
	•	Manifestation (Light): Use aura to summon/bring out something (create constructs, illusions, or light-based phenomena)
	•	Possession (Dark): Use aura to take control of something (mind control, puppetry, possession)
	•	Space
	•	Time
Suggestions for Earth and Water
Since you haven’t defined Earth and Water yet, here are some ideas that fit your system:
Earth – Fortification
	•	Description: Use aura to reinforce, harden, or shield oneself or objects. This could be defensive techniques, creating barriers, or making your body as hard as stone.
	•	Examples: Aura armor, unbreakable skin, reinforcing walls or ground, standing firm against attacks.
Water – Adaptation
	•	Description: Use aura to adapt, flow, or recover. This could involve healing, regeneration, shifting form, or adapting to attacks/environments.
	•	Examples: Self-healing, flexible movement, aura that lets you slip through attacks, mimicry of opponents’ techniques.
Suggestions for Space and Time
Now, let’s flesh out unique martial applications for Space and Time that fit your system:
Space – Distortion
	•	Description: Use aura to manipulate distance, position, or dimensions. This could be teleportation, spatial slicing, expanding/reducing reach, or creating pocket spaces.
	•	Examples: Blink steps (short-range teleport), expanding weapon reach, folding space to dodge, storing items in aura pockets.
Time – Acceleration
	•	Description: Use aura to affect the flow of time for yourself or objects. This could be speeding up your movements, slowing down others, or accelerating the effects of techniques.
	•	Examples: Burst of super speed, slowing opponents’ actions, rapidly aging or decaying objects, seeing a few seconds into the future.

## Introduction
Aura. 
The strength of one's soul. 
Many warriors have tried to master this power, but few have. Those that have a talent for this power have transformed this "energy" into the powerful weapons they can utilize called battle arts.

The first recorded battle arts were developed in tandum with the story of the *Original Spirits*. The first beings were few. Some were able to harness the power of nature and became early magic users, able to bend natural properies to their whims. Others jealous of this power, tried to imitate but failed. Uran, the God of Honor, noticed their shortcomings and sent a messenger to deliver a divine message. 

To the Lost, He spoke:
"Worry not the uncoming of nature, for it is power not meant for all.
Instead search your being inward, for there is a resting beast.
Train and subdue this beast and reach unfound realms.
For this is My law."

Hearing this, they began to train themselves. During this training some began to feel the beast He spoke of, the power of the soul. Many understood of this power and became able to perform amazing physical feats. Of the many, some individuals still felt longing for nature's allure and began to mimic its reign. These individuals, accounted below, formed their soul's power, aura, based off of the *Eight Original Spirits*:

__Ukaos__, the giant, admired the Great March's thunderous path. He mimiced it and developed the *Over March Series*, a series of running forms that can shake the earth.
__Shautius__, the human, favored the Low Tide's crahsing wave. She copied it and developed the *Tidal Abyss Series*, a series of waves that can devour the lands.
__Eldrien__, the elf, honored the Raging Breath's diastarous presence. He studied it and developed the *Raging Zephyr Series*, a series of breaths that can bringforth untold power.
__Dwaoria__, the lizardkin, revered the Ancestor's cleansing flames. She mimiced it and developed the *Noble Lineage Series*, a series of forms that can recall her origin.
__Gabryell__, the fairy, was drawn to the Purecrown's blinding allure. He mimiced it and developed the *Shining Crown Series*, a series of lights that can illuminate the dark.
__Yeselui__, the orc, feared the Nightwalker's shadow steps. She mimiced it and developed the *Twilight Walk Series*, a series of steps that can enshroud the earth.
__Bhasith__, the dwarf, recognized the Hidden Expanse's allgrowing power. He mimiced it and developed the *Final Expansion Series*, a series of blows that can reshape the earth.
__Jerilla__, the ogre, respected the Watcher's evervigilant gaze. He mimiced it and developed the *Pharid Eye Series*, a series of visual forms that can discern all.

The auras known today are guided from this story...

## Known Art Technique Series
- 001 Over March Series
- 002 Tidal Abyss Series
- 003 Raging Zephyr Series
- 004 Noble Lineage Series
- 005 Shining Crown Series
- 006 Twilight Walk Series
- 007 Final Expansion Series
- 008 Pharid Eye Series
- 009 Malice King Series
- 010 Spell Hunter Series
- 011 Balance Series
- 012 Chain Series
- 013 Fear Series
- 014 Pure Flame Series
- 015 True Judgment Series
- 016 Total Peace Series
- 017 Martial Power Series
- 018 Sword King Series
- 019 Shield Series
- 020 Mass Twitch Series
- 021 Vampire Hunter Series
- 022 Demigod Aran Series


## Battle Art Planes
__Advancement__ - Reach next rank within plane
__Breakthrough__ - Enter new plane

### Apprentice Plane:
#### Low Rank Apprentice 
Every aura user starts at this rank. Users must inherit their unique aura properties through __soul discovery__. First Spark

- 001 Over March Series
- 002 Tidal Abyss Series
- 003 Many Breaths
- 004 Noble Lineage Series
- 005 Shining Crown Series
- 006 Twilight Walk Series
- 007 Soul Spin
- 008 Pharid Eye Series
- 009 Malice Series
- 010 Spell Hunter Series
- 011 Balance Series
- 012 Chain Series
- 013 Fear Series
- 014 Pure Flame Series
- 015 True Judgment Series
- 016 Total Peace Series
- 017 Martial Power Series
- 018 Sword King Series
- 019 Shield Series
- 020 Mass Twitch Series
- 021 Vampire Hunter Series

#### Mid Rank Apprentice
__Soul refinement__ is the speeding up the speed at which aura swirls within the soul

- 001 Over March Series
- 002 Tidal Abyss Series
- 003 One Breath
- 004 Noble Lineage Series
- 005 Shining Crown Series
- 006 Twilight Walk Series
- 007 Soul Sphere
- 008 Pharid Eye Series
- 009 Malice Series
- 010 Spell Hunter Series
- 011 Balance Series
- 012 Chain Series
- 013 Fear Series
- 014 Pure Flame Series
- 015 True Judgment Series
- 016 Total Peace Series
- 017 Martial Power Series
- 018 Sword King Series
- 019 Shield Series
- 020 Mass Twitch Series
- 021 Vampire Hunter Series

#### High Rank Apprentice
__Soul expansion__ occurs when one can maximize the aura output of the soul

- 001 Over March Series
- 002 Tidal Abyss Series
- 003 No Breath
- 004 Noble Lineage Series
- 005 Shining Crown Series
- 006 Twilight Walk Series
- 007 Soul Engine
- 008 Pharid Eye Series
- 009 Malice Series
- 010 Spell Hunter Series
- 011 Balance Series
- 012 Chain Series
- 013 Fear Series
- 014 Pure Flame Series
- 015 True Judgment Series
- 016 Total Peace Series
- 017 Martial Power Series
- 018 Sword King Series
- 019 Shield Series
- 020 Mass Twitch Series
- 021 Vampire Hunter Series


### Intermediate Plane:
#### Low Rank Intermediate
Artists of this rank can do __mind utilization __, using a small part of the brain to increase mental capacity

- 001 Over March Series
- 002 Tidal Abyss Series
- 003 Many Breaths
- 004 Noble Lineage Series
- 005 Shining Crown Series
- 006 Twilight Walk Series
- 007 Soul Spin
- 008 Pharid Eye Series
- 009 Malice Series
- 010 Spell Hunter Series
- 011 Balance Series
- 012 Chain Series
- 013 Fear Series
- 014 Pure Flame Series
- 015 True Judgment Series
- 016 Total Peace Series
- 017 Martial Power Series
- 018 Sword King Series
- 019 Shield Series
- 020 Mass Twitch Series
- 021 Vampire Hunter Series

#### Mid Rank Intermediate
Artists of this rank can do __mind completion__, using the full power of the brain

- 001 Over March Series
- 002 Tidal Abyss Series
- 003 One Breath
- 004 Noble Lineage Series
- 005 Shining Crown Series
- 006 Twilight Walk Series
- 007 Soul Sphere
- 008 Pharid Eye Series
- 009 Malice Series
- 010 Spell Hunter Series
- 011 Balance Series
- 012 Chain Series
- 013 Fear Series
- 014 Pure Flame Series
- 015 True Judgment Series
- 016 Total Peace Series
- 017 Martial Power Series
- 018 Sword King Series
- 019 Shield Series
- 020 Mass Twitch Series
- 021 Vampire Hunter Series

#### High Rank Intermediate
Artists of this rank can do __mind overload__, fully maximizing their mental processes

- 001 Over March Series
- 002 Tidal Abyss Series
- 003 No Breath
- 004 Noble Lineage Series
- 005 Shining Crown Series
- 006 Twilight Walk Series
- 007 Soul Engine
- 008 Pharid Eye Series
- 009 Malice Series
- 010 Spell Hunter Series
- 011 Balance Series
- 012 Chain Series
- 013 Fear Series
- 014 Pure Flame Series
- 015 True Judgment Series
- 016 Total Peace Series
- 017 Martial Power Series
- 018 Sword King Series
- 019 Shield Series
- 020 Mass Twitch Series
- 021 Vampire Hunter Series

### Advanced Plane:
#### Low Rank Advanced
The ability to have aura manifest in __partial body__ parts allows for individual parts to be strengthened

- 001 Over March Series
- 002 Tidal Abyss Series
- 003 Raging Zephyr Series
- 004 Noble Lineage Series
- 005 Shining Crown Series
- 006 Twilight Walk Series
- 007 Final Expansion Series
- 008 Eyes
- 009 Malice Series
- 010 Spell Hunter Series
- 011 Balance Series
- 012 Chain Series
- 013 Fear Series
- 014 Pure Flame Series
- 015 True Judgment Series
- 016 Total Peace Series
- 017 Martial Power Series
- 018 Sword King Series
- 019 Shield Series
- 020 Mass Twitch Series
- 021 Vampire Hunter Series

#### Mid Rank Advanced
Unlocking your __full body__ happens when your aura swirls around your body and forms an aura shell

- 001 Over March Series
- 002 Tidal Abyss Series
- 003 Raging Zephyr Series
- 004 Noble Lineage Series
- 005 Shining Crown Series
- 006 Twilight Walk Series
- 007 Final Expansion Series
- 008 Full Gaze
- 009 Malice Series
- 010 Spell Hunter Series
- 011 Balance Series
- 012 Chain Series
- 013 Fear Series
- 014 Pure Flame Series
- 015 True Judgment Series
- 016 Total Peace Series
- 017 Martial Power Series
- 018 Sword King Series
- 019 Shield Series
- 020 Mass Twitch Series
- 021 Vampire Hunter Series 

#### High Rank Advanced
__Body expansion__ is achieved when you are able to surge your aura and expand its power past your body into the surrounding area

- 001 Over March Series
- 002 Tidal Abyss Series
- 003 Raging Zephyr Series
- 004 Noble Lineage Series
- 005 Shining Crown Series
- 006 Twilight Walk Series
- 007 Final Expansion Series
- 008 Soul Radar
- 009 Malice Series
- 010 Spell Hunter Series
- 011 Balance Series
- 012 Chain Series
- 013 Fear Series
- 014 Pure Flame Series
- 015 True Judgment Series
- 016 Total Peace Series
- 017 Martial Power Series
- 018 Sword King Series
- 019 Shield Series
- 020 Mass Twitch Series
- 021 Vampire Hunter Series


### Expert Plane:
#### Low Rank Expert
__Weapon auras__ are the maifestation of aura being focused within the blade/part of a weapon

- 001 Over March Series
- 002 Tidal Abyss Series
- 003 Raging Zephyr Series
- 004 Noble Lineage Series
- 005 Shining Crown Series
- 006 Twilight Walk Series
- 007 Final Expansion Series
- 008 Pharid Eye Series
- 009 Malice Series
- 010 Spell Hunter Series
- 011 Balance Series
- 012 Chain Series
- 013 Fear Series
- 014 Pure Flame Series
- 015 True Judgment Series
- 016 Total Peace Series
- 017 Martial Power Series
- 018 Sword King Series
- 019 Shield Series
- 020 Mass Twitch Series
- 021 Vampire Hunter Series

#### Mid Rank Expert
Reach the point to unlock an infused __weapon's first phase__

- 001 Over March Series
- 002 Tidal Abyss Series
- 003 Raging Zephyr Series
- 004 Noble Lineage Series
- 005 Shining Crown Series
- 006 Twilight Walk Series
- 007 Final Expansion Series
- 008 Pharid Eye Series
- 009 Malice Series
- 010 Witch Hunter = Unlock the first phase of the alchemy hunter techniques and bestow your weapon the power of the witch hunter form
- 011 Balance Series
- 012 Chain Series
- 013 Fear Series
- 014 Pure Flame Series
- 015 True Judgment Series
- 016 Total Peace Series
- 017 Martial Power Series
- 018 Sword King Series
- 019 Shield Series
- 020 Mass Twitch Series
- 021 Vampire Hunter Series

#### High Rank Expert
Reach the point to unlock an infused __weapon's final phase__

- 001 Over March Series = Unleash the 's true form into
- 002 Tidal Abyss Series = Unleash the 's true form into
- 003 Elltio, The Bated Breeze = Unleash the 's true form into
- 004 Loab, The Noble Lineage Series = Unleash the 's true form into
- 005 Cistell, The Glean = Unleash the 's true form into brightest weapon
- 006 Twilight Walk Series = Unleash the 's true form into
- 007 Final Expansion Series = Unleash the 's true form into
- 008 Perecinn = Unleash the 's true form into watchful weapon
- 009 Woemere, The  = Unleash the 's true form into
- 010 Illiyad, the Sorcer Hunter = Unleash the Witch Hunter's true form into the ultimate sorcer hunting weapon 
- 011 Balance Series = Unleash the 's true form into
- 012 Dolazin, The Chain Series = Unleash the 's true form into
- 013 Longrim, The Fear Series = Unleash the 's true form into
- 014 Haugrick, The Pure Flame Series = Unleash the 's true form into
- 015 Monnifel, The True Judgment Series = Unleash the 's true form into
- 016 Total Peace Series = Unleash the 's true form into
- 017 Tantomme, Martial Power Series = Unleash the 's true form into
- 018 Anthen, the Indominable Blade = Unleash the 's true form into the ultimate blade
- 019 Braeilior, the True Shield = Unleash the 's true form into the ultimate shield
- 020 Yetro, The Mass Twitch Series = Unleash the 's true form into
- 021 Vontzieer, the Vampire Slayer = Unleash the 's true form into the vampire slaying weapon


### Master Plane:
#### Low Rank Master
__Partial presences__ are incomplete in nature and can be broken by individuals with high willpower or stronger warriors

- 001 Over March Series
- 002 Tidal Abyss Series
- 003 Raging Zephyr Series
- 004 Noble Lineage Series
- 005 Shining Crown Series
- 006 Twilight Walk Series
- 007 Final Expansion Series
- 008 Pharid Eye Series
- 009 Malice Series
- 010 Spell Hunter Series
- 011 Balance Series
- 012 Chain Series
- 013 Fear Series
- 014 Pure Flame Series
- 015 True Judgment Series
- 016 Total Peace Series
- 017 Martial Power Series
- 018 Sword King Series
- 019 Shield Series
- 020 Mass Twitch Series
- 021 Vampire Hunter Series

#### Mid Rank Master
Ability to create a __Total presence__. All within the range of this presence feel its influence to it

- 001 Beast Stampede = 
- 002 Tidal Abyss Series
- 003 Raging Zephyr Series
- 004 Noble Lineage Series
- 005 Shining Crown Series
- 006 Twilight Walk Series
- 007 Final Expansion Series
- 008 Pharid Eye Series
- 009 Hand of the Slaughter God = Call upon the dark power of the Slaughter God and a technique that summons a portion of his intent of malice that strikes fear in others
- 010 Spell Hunter Series
- 011 Balance Series
- 012 Hall of Chains = Bring an opponent into a pitch black word filled with hanging chains
- 013 Fear Series
- 014 Pure Flame Series
- 015 True Judgment Series
- 016 Total Peace Series
- 017 Martial Power Series
- 018 Sword King Series
- 019 Shield Series
- 020 Mass Twitch Series
- 021 Vampire Hunter Series

#### High Rank Master
__Grand presences__ are brought on by the peak of the strongest. All within the huge range of this presence are subject to it

- 001 Quake of Mountains =
- 002 Reach of the Abyss =
- 003 Zephyrix =
- 004 Land of Dragons =
- 005 Kingdom of Light =
- 006 Path of Shadows =
- 007 Breachmax =
- 008 Gaze of the Pharid =
- 009 World of Malice = Call upon the complete dark power of the Slaughter God and a technique that summons his malice (red world with Evil Eye Sun staring at opponents)
- 010 Field of Trials =
- 011 Yin and Yang = Evole the power of balance on all who differ
- 012 Oppium = 
- 013 True Fear =
- 014 Ferreghor = Flame region of the flame demon
- 015 Final Judment = Be judged by the ultimate power
- 016 Plane Zero = Exist in a state of nothing surrounded by nothingness
- 017 Peak Realm = mountains cloudy peak with 5
- 018 Great Blade Tree =
- 019 Blackout =
- 020 Xzertion =

### Heavenly Plane


## Art Classification


# Introductions
Air Magic relies on the skies and winds to produce magic.

# Basic Tier 1:
Air Magic - 22%
> The power of the world’s skies

# Low Tier 2:
Wind Magic = Air + Air
> The better of sirs heed you

# Mid Tier 3:
Smoke Magic = Air + Fire
> Scorched gases give you cover

Mind Magic = Air + Time
> Manipulate the constructs of the brain

Sound Magic = Air + Space
> Manipulate the waves of the air

Gust Magic = Wind + Wind
> Stronger winds beckon your command

# High Tier 4:
Vortex Magic = Gust + Gust
> The conical nature of the wind forms

# Advanced Tier 5:
Storm Magic = Air + Water + Fire
> Bring forth the thunderous disasters of the skies

Cloud Magic = Air + Water + Time
> Envelop yourself in the sky's covers

Voice Magic = Air + Water + Space
> The power to project your voice at foes 

Reconstruction Magic = Air + Light + Time
> The forces of repairing support you

Cyclone Magic = Vortex + Vortex
> Evoke the speeds of tornados

# Supreme Tier 6:
Jet Magic = Cyclone + Cyclone
> Use the force of air streams

# Mythical Tier 7:
Sky Magic = Jet + Jet
> Utilize the wide-open sky 

# Divine Tier 8:


# Introductions
Dark magic draws power out of the depths of the world, where shadows and demons reside.

# Basic Tier 1:
Dark Magic - 5%
> The power of the world’s darkness

# Low Tier 2:
Shadow Magic = Dark + Dark
> Darker entities take notice of you

# Mid Tier 3:
Poison Magic = Dark + Water
> Concoct the earth’s venom for your use

Black Magic = Shadow + Shadow
> The dark arts listen to you

# High Tier 4:
Corruption Magic = Black + Black
> Evoke the power of corruption to deteriorate and influence your enemies

# Advanced Tier 5:
Blood Magic = Dark + Water + Earth
> Manipulate the lifeline of entities 

Curse Magic = Dark + Air + Earth
> The negative curses you

Bone Magic = Dark + Earth + Time
> Utilize the remnants of the dead

Destruction Magic = Dark + Air + Time
> The destructive forces envelop you  

Demon Magic = Dark + Air + Space
> Call the evil intentions of the underworld

Absorption Magic = Corruption + Corruption
> Use the dark ability of power stealing

# Supreme Tier 6:
Anti Magic = Absorption + Absorption
> Turn to the magic disabling power of anti-magic

# Mythical Tier 7:
Death Magic = Dark + Earth + Water + Air
> Use the forbidden power of the graveyard

Darkstar Magic = Dark + Space + Light + Time
> Ability to harness power of dark void star

Void Magic = Anti + Anti
> Call upon the endless abyss

# Divine Tier 8:


## Deity Magics



## God Magics

Creation Magic = Divine + Earth + Water + Air + Light
> Create all forms of creation, from life to structures

Realm Magic = Divine + Earth + Light + Dark + Space
> Develop new self-sustaining Realms


Earth magic relies on the power of the lands beneath us.

# Basic Tier 1:
Earth Magic - 22% 
> The power of the world’s lands

# Low Tier 2:
Rock Magic = Earth + Earth
> Stronger properties of earth answer your call

# Mid Tier 3:
Plant Magic = Earth + Water
> Command the world’s flora 

Sand Magic = Earth + Air
> Use the sands of the land

Crystal Magic = Earth + Light
> Channel the glass of the earth

Metal Magic = Earth + Dark
> Bend the earth to form metals

Golem Magic = Earth + Time
> Pardon sentience to other objects

Construction Magic = Earth + Space
> Build to your hearts desire

Stone Magic = Rock + Rock
> Powerful ferric properties are under your command

# High Tier 4:
Bedrock Magic = Stone + Stone
> The deep stones of the Earth follow your command

# Advanced Tier 5:
Flower Magic = Earth + Water + Air
> The angelic nature of blossoms agree to your command

Tree Magic = Earth + Water + Space
> The elder nature of trees accept your command

Summoning Magic = Earth + Air + Time
> Call forth the spirits of Teolaris to do your biding

Igneous Magic = Bedrock + Bedrock
> Bury them with the heaviest mantle

# Supreme Tier 6:
Quake Magic = Igneous + Igneous
> Let the continent tremble beneath you

# Mythical Tier 7:
Mountain Magic = Quake + Quake
> Create mountain like formations

# Divine Tier 8:


The power of fire magics rise from the flames of the earth.

# Basic Tier 1:
Fire Magic - 22%
> The power of the world’s flames

# Low Tier 2:
Flame Magic = Fire + Fire
> Hotter flames obey your command

# Mid Tier 3:
Lava Magic = Fire + Earth
> The magma of dormant mountains is left to you 

Energy Magic = Fire + Time
> Build up natural power

Explosion Magic = Fire + Space
> Cause implosions with use

Blaze Magic = Flame + Flame
> Stronger flames fill your heart

# High Tier 4:
Inferno Magic = Blaze + Blaze
> The world’s raging fires beckon you forth

# Advanced Tier 5:
Enhancement Magic = Fire + Water + Earth
> Influence the nature of entities with strengthening

Lightning Magic = Fire + Air + Earth
> Harken the power of storm fire

Eruption Magic = Fire + Earth + Space
> Cause rise to the dormant mountains once again

Redfire Magic = Inferno + Inferno
> Pure red flames show the commitment to the fiery arts

# Supreme Tier 6:
Bluefire Magic = Redfire + Redfire
> Burn with one of the hottest natural flames.

# Mythical Tier 7:
Holyfire Magic = Fire + Light + Earth + Air
> Use the blessed flames to purify the land

Hellfire Magic = Fire + Dark + Earth + Air
> Use the flames of hell to bring ruination

Nuclear Magic = Fire + Light + Space + Earth
> Use the destructive power of atom splitting

Draconic Magic = Fire + Time + Light + Air
> Harness draconic strength as your own

Dragon Slayer Magic = Fire + Time + Dark + Air
> Utilize draconian strength, tailored to bring down dragons

Blackfire Magic = Fire + Dark + Space + Air
> One of the hottest flames. Known to be a fire that consumes until nothing is left

Whitefire Magic = Bluefire + Bluefire
> One of the hottest fires. Sometimes known as everlasting flames

# Divine Tier 8:


The nature of light magic comes from the shine of the Daystar. It shows the correct path for all.

# Basic Tier 1:
Light Magic - 5%
> The power of the world’s light

# Low Tier 2:
Radiant Magic = Light + Light
> Brighter lights turn to you

# Mid Tier 3:
Balance Magic = Light + Dark
> The balance of nature heeds you

Luminous Magic = Radiant + Radiant
> The brightest lights follow you

# High Tier 4:
Ray Magic = Luminous + Luminous
> Use light beams that burn what you command 

# Advanced Tier 5:
Blessing Magic = Light + Air + Earth
> The positive reinforcement blesses you

Mirror Magic = Light + Earth + Space
> Reflect yourself to 100s of surfaces

Holy Magic = Light + Air + Space
> Call the divine nature of the heavens

Lazer Magic = Ray + Ray
> Bring precision and power with laserbeams

# Supreme Tier 6:
Star Magic = Laser + Laser
> Call upon the strength of the stars 


# Mythical Tier 7:
Life Magic = Light + Earth + Water + Air
> Use the unique power of giving life

Daystar Magic = Star + Star
> Utilize power of one of the largest stars

# Divine Tier 8:


## Introduction
Magic is the power of inputting a certain amount and type of mana and outputting it as a spell. Magic is based on 8 basic elements: earth, water, air, fire, light, dark, space, and time. Simple spells are cast with just one element, but higher difficulty spells are multi elemental.

According to ancient legends:
When the realm was originally formed, the Gods born *8 Original Spirits* to lay claim to the *8 True Elements* that were used for the realms creation. There was __Terros the Great March__, __Aquos the Low Tide__, __Galos the Raging Breath__, __Ignios the Dragon Ancestor__, __Luxos the Purecrown__, __Oblos the Nightwalker__, __Banos the Hidden Expanse__, and __Horos the First Watcher__.

__Terros the Great March__ was a bull spirit. His given domain ranged from the top of mountains to the deepest of caves. His constant forming and crushing led to the land we know today. Thus, Earth Magic was formed.

__Aquos the Low Tide__ was a whale spirit. Her protecting of the raging seas led to the vast life and vibrant ocean we know today. Thus, Water Magic was given.

__Galos the Raging Breath__ was a hawk spirit. Her patrol of the skies brought upon the immerse sky we know today. Thus, Air Magic was created.

__Ignios the Dragon Ancestor__ was a lizard spirit. His resting within the hottest layers of the land led to the passionate flames we know today. Thus, Fire Magic was forged.

__Luxos the Purecrown__ was a deer spirit. His care of the great forests let multitudes of ecosystems flourish. Thus, Light Magic was passed.

__Oblos the Nightwalker__ was a wolf spirit. His lurking within the shadowy realms allowed for the day and night be so distinguished. Thus, Dark Magic was risen.

__Banos the Hidden Expanse__ was a worm spirit. His claim of the vast depths of the underground gave origination to the deepest caverns explored today. Thus, Space Magic was found.

__Horos the First Watcher__ was a spider spirit. Her gaze upon all the world's paths kept our time normal. Without this watching, our time would least to exist. Thus, Time Magic was known.

The magic known today is derived from this story.


## Magic Tiers

### Basic Tier
The first tier of the magic system is the basic elements. Each being is formed with 2 main systems for gauging their magical abilities: *Compatibility* and *Capability*. The compatibility of a being is the four elements they are most likely to be able to use. The general belief is that the __Natural Elements__ ==> - 00000,__ Water, Fire, and Air ==> - 00000h__e easiest to pick up with 88% of beings compatible. Next the __Simple Elements__ ==> - 00000 __and Dark ==> - 00000a__lly have 10% compatibility with beings. Finally, the __Complex Elements__ ==> - 00000a__nd Space ==> - 00000s__ee 2% compatibility for beings. 

After a being's four compatible elements are determined, then their capability to each is next. The higher the capability one has to an element, the higher Tier of magic they will be able to use. The scores are such: 10~20% capability basic tier, 20% low tier, 40% mid tier, 60% high tier, 80% Advanced Tier, 90% Supreme Tier, and 98% Mythical tier. Lets say I have a 70% capability score for the Fire element, the highest tier of fire magics I most likely will be able to reach is High tier.

### Low Tier
The second tier, the low tier of magic, is a simple refinment of the 8 basic elements. The individuals who reach this level of magic have gotten a better understanding of the element they use. 

### Mid Tier
The mid tier of magic is the door to dual elemental magic. From the basic tier of finding your element and then the next of refining your new discovery, the third tier is your discovery of the next element you can master. Dual element magic is the understanding of how two elements coexist.

### High Tier
The high tier of magic is to those individuals who have gained a stronger understanding of their primary element or their dual elementsl abilities. 

### Superior Tier
The superior tier of magic is open to individuals who gain an intricate understanding of a third elemental and how it blends with their current abilities.

### Supreme Tier
The blessed few that reach the supreme tier of magic stand at a diffrent level than others. The casters that grace this level fully know the capabilities of their element(s) and how to advance them. They are formidablly strong.

### Mythical Tier
The mythical tier is the stuff of legends. The strongest of mages that gain an understanding of how to balance quad elemental casting are rewarded with the strongest forms of magic. 

### Divine Tier
The divine tier of magic is able to classify the expansive magic of dieties and gods. Mortals cannot comprehend the power and abilities of the gods.


## Magic Classification
Past the elements consisting of magic, there is another way to describe the spells of magic.

### Offensive Type Magic
Offensive type magics are magics to use against a foe.

### Defensive Type Magic
Defensive type magics are used to protect someone or something.

### Support Type Magic
Support type magics enhance, bolster, or sustain something. 

### Creation Type Magic
Creation type magics are used to construct or build something.

## Magic Spells
Wheel of Sin

1 (Base Element) | 29 (Element Branch) | 5 (Branch Node) | 8 (Tier)

# -- Earth -- 
Stone
Mud
Metal
Crystal
Plant
Tree
Flower
Quake
Golem
Bedrock
Life
Igneous
Mirror
Weapon
Armor
Mountain
Creation
Beast

# -- Water -- 
Ice
Potion
Poison
Acid
Current
Tidal
Jet
Blood
Paint
Ocean
Rain
Slime

# -- Air -- 
Storm
Sound
Toxic
Cloud
Mind
Sky
Voice
Vortex
Cyclone
Music
Illusion 

# -- Fire -- 
Flame
Lava
Lightning
Energy
Inferno
Explosive
DragonSlayer
Draconic
Blackfire
Whitefire
Cosmic
Hellfire
Nuclear
Holyfire
Speed
Enhancement
Redfire

# -- Light -- 
Radiant
Psyche
Dream
Ray
Blessing
Lazer
Holy
Incarnation
Enchantment
Rally
Star
Luck
Balance
Scan

# -- Dark -- 
Nightmare
Fear
Shadow
Corruption
Curse
Demon
Absorption
Nightstar
Devil
Anti
Death
Void 

# -- Space -- 
Position
Field
Presence
Teleport
Gravity
Warp
Summoning
Realm
Subspace
Gate
Seal
Trap
Barrier
Domain

# -- Time -- 
Reduction
Infinite
Temporal
Pause
Contract
Regression

Daystar
Darkstar  
Wish
Spirit
Float
Game
Food
Card
Law
Attraction
Rubber
Purifying
Soul
Slayer
Sand
Wind
Steam
Smoke
Flood
Gust
Blaze
Luminous
Black
Acceleration
Whirlpool
Eruption
Spirit
Float
Sword
Map
Artillery
Explosion
Divine
Realsm

## Basic Tier ==>
- 10001 __Earth Magic__ = Earth ==>
- 20001 __Water Magic__ = Water ==>
- 30001 __Air Magic__ = Air ==>
- 40001 __Fire Magic__ = Fire ==>
- 50001 __Light Magic__ = Light ==>
- 60001 __Dark Magic__ = Dark ==>
- 70001 __Space Magic__ = Space ==>
- 80001 __Time Magic__ = Time

## Low Tier ==>
- 10002 __ Magic__ = Earth + Earth ==>
- 20002 __ Magic__ = Water + Water ==>
- 30002 __ Magic__ = Air + Air ==>
- 40002 __ Magic__ = Fire + Fire ==>
- 50002 __ Magic__ = Light + Light ==>
- 60002 __ Magic__ = Dark + Dark ==>
- 70002 __ Magic__ = Space + Space ==>
- 80002 __ Magic__ = Time + Time ==>

## Mid Tier
- 10003 __ Magic__ =  +  (Earth x4) ==>
- 00003 __ Magic__ = Earth + Water ==>
- 00003 __ Magic__ = Earth + Air ==>
- 00003 __ Magic__ = Earth + Fire ==>
- 00003 __ Magic__ = Earth + Light ==>
- 00003 __ Magic__ = Earth + Dark ==>
- 00003 __ Magic__ = Earth + Space ==>
- 00003 __ Magic__ = Earth + Time ==>
- 20003 __ Magic__ =  +  (Water x4) ==>
- 00003 __ Magic__ = Water + Air ==>
- 00003 __ Magic__ = Water + Fire ==>
- 00003 __ Magic__ = Water + Light ==>
- 00003 __ Magic__ = Water + Dark ==>
- 00003 __ Magic__ = Water + Space ==>
- 00003 __ Magic__ = Water + Time ==>
- 30003 __ Magic__ =  +  (Air x4) ==>
- 00003 __ Magic__ = Air + Fire ==>
- 00003 __ Magic__ = Air + Light ==>
- 00003 __ Magic__ = Air + Dark ==>
- 00003 __ Magic__ = Air + Space ==>
- 00003 __ Magic__ = Air + Time ==>
- 40003 __ Magic__ =  +  (Fire x4) ==>
- 00003 __ Magic__ = Fire + Light ==>
- 00003 __ Magic__ = Fire + Dark ==>
- 00003 __ Magic__ = Fire + Space ==>
- 00003 __ Magic__ = Fire + Time ==>
- 50003 __ Magic__ =  +  (Light x4) ==>
- 00003 __ Magic__ = Light + Dark ==>
- 00003 __ Magic__ = Light + Space ==>
- 00003 __ Magic__ = Light + Time ==>
- 60003 __ Magic__ =  +  (Dark x4) ==>
- 00003 __ Magic__ = Dark + Space ==>
- 00003 __ Magic__ = Dark + Time ==>
- 70003 __ Magic__ =  +  (Space x4) ==>
- 00003 __ Magic__ = Space + Time ==>
- 80003 __ Magic__ =  +  (Time x4) ==>

## High Tier
- 10004 __ Magic__ =  +  (Earth x8) ==>
- 20004 __ Magic__ =  +  (Water x8) ==>
- 30004 __ Magic__ =  +  (Air x8) ==>
- 40004 __ Magic__ =  +  (Fire x8) ==>
- 50004 __ Magic__ =  +  (Light x8) ==>
- 60004 __ Magic__ =  +  (Dark x8) ==>
- 70004 __ Magic__ =  +  (Space x8) ==>
- 80004 __ Magic__ =  +  (Time x8) ==>

## Advanced Tier
- 10005 __ Magic__ =  +  (Earth x16) ==>
- 00005 __ Magic__ = Earth + Water + Air ==>
- 00005 __ Magic__ = Earth + Water + Fire ==>
- 00005 __ Magic__ = Earth + Water + Light ==>
- 00005 __ Magic__ = Earth + Water + Dark ==>
- 00005 __ Magic__ = Earth + Water + Space ==>
- 00005 __ Magic__ = Earth + Water + Time ==>
- 00005 __ Magic__ = Earth + Air + Fire ==>
- 00005 __ Magic__ = Earth + Air + Light ==>
- 00005 __ Magic__ = Earth + Air + Dark ==>
- 00005 __ Magic__ = Earth + Air + Space ==>
- 00005 __ Magic__ = Earth + Air + Time ==>
- 00005 __ Magic__ = Earth + Fire + Light ==>
- 00005 __ Magic__ = Earth + Fire + Dark ==>
- 00005 __ Magic__ = Earth + Fire + Space ==>
- 00005 __ Magic__ = Earth + Fire + Time ==>
- 00005 __ Magic__ = Earth + Light + Dark ==>
- 00005 __ Magic__ = Earth + Light + Space ==>
- 00005 __ Magic__ = Earth + Light + Time ==>
- 00005 __ Magic__ = Earth + Dark + Space ==>
- 00005 __ Magic__ = Earth + Dark + Time ==>
- 00005 __ Magic__ = Earth + Space + Time ==>
- 20005 __ Magic__ =  +  (Water x16) ==>
- 00005 __ Magic__ = Water + Air + Fire ==>
- 00005 __ Magic__ = Water + Air + Light ==>
- 00005 __ Magic__ = Water + Air + Dark ==>
- 00005 __ Magic__ = Water + Air + Space ==>
- 00005 __ Magic__ = Water + Air + Time ==>
- 00005 __ Magic__ = Water + Fire + Light ==>
- 00005 __ Magic__ = Water + Fire + Dark ==>
- 00005 __ Magic__ = Water + Fire + Space ==>
- 00005 __ Magic__ = Water + Fire + Time ==>
- 00005 __ Magic__ = Water + Light + Dark ==>
- 00005 __ Magic__ = Water + Light + Space ==>
- 00005 __ Magic__ = Water + Light + Time ==>
- 00005 __ Magic__ = Water + Dark + Space ==>
- 00005 __ Magic__ = Water + Dark + Time ==>
- 00005 __ Magic__ = Water + Space + Time ==>
- 30005 __ Magic__ =  +  (Air x16) ==>
- 00005 __ Magic__ = Air + Fire + Light ==>
- 00005 __ Magic__ = Air + Fire + Dark ==>
- 00005 __ Magic__ = Air + Fire + Space ==>
- 00005 __ Magic__ = Air + Fire + Time ==>
- 00005 __ Magic__ = Air + Light + Dark ==>
- 00005 __ Magic__ = Air + Light + Space ==>
- 00005 __ Magic__ = Air + Light + Time ==>
- 00005 __ Magic__ = Air + Dark + Space ==>
- 00005 __ Magic__ = Air + Dark + Time ==>
- 00005 __ Magic__ = Air + Space + Time ==>
- 40005 __ Magic__ =  +  (Fire x16) ==>
- 00005 __ Magic__ = Fire + Light + Dark ==>
- 00005 __ Magic__ = Fire + Light + Space ==>
- 00005 __ Magic__ = Fire + Light + Time ==>
- 00005 __ Magic__ = Fire + Dark + Space ==>
- 00005 __ Magic__ = Fire + Dark + Time ==>
- 00005 __ Magic__ = Fire + Space + Time ==>
- 50005 __ Magic__ =  +  (Light x16) ==>
- 00005 __ Magic__ = Light + Dark + Space ==>
- 00005 __ Magic__ = Light + Dark + Time ==>
- 00005 __ Magic__ = Light + Space + Time ==>
- 60005 __ Magic__ =  +  (Dark x16) ==>
- 00005 __ Magic__ = Dark + Space + Time ==>
- 70005 __ Magic__ =  +  (Space x16) ==>
- 80005 __ Magic__ =  +  (Time x16) ==> 

## Legendary Tier
- 10006 __ Magic__ =  +  (Earth x32) ==>
- 20006 __ Magic__ =  +  (Water x32) ==>
- 30006 __ Magic__ =  +  (Air x32) ==>
- 40006 __ Magic__ =  +  (Fire x32) ==>
- 50006 __ Magic__ =  +  (Light x32) ==>
- 60006 __ Magic__ =  +  (Dark x32) ==>
- 70006 __ Magic__ =  +  (Space x32) ==>
- 80006 __ Magic__ =  +  (Time x32) ==>

## Supreme Tier
- 10007 __ Magic__ =  +  (Earth x64) ==>
- 00007 __ Magic__ = Earth + Water + Air + Fire ==>
- 00007 __ Magic__ = Earth + Water + Air + Light ==>
- 00007 __ Magic__ = Earth + Water + Air + Dark ==>
- 00007 __ Magic__ = Earth + Water + Air + Space ==>
- 00007 __ Magic__ = Earth + Water + Air + Time ==>
- 00007 __ Magic__ = Earth + Water + Fire + Light ==>
- 00007 __ Magic__ = Earth + Water + Fire + Dark ==>
- 00007 __ Magic__ = Earth + Water + Fire + Space ==>
- 00007 __ Magic__ = Earth + Water + Fire + Time ==>
- 00007 __ Magic__ = Earth + Water + Light + Dark ==>
- 00007 __ Magic__ = Earth + Water + Light + Space ==>
- 00007 __ Magic__ = Earth + Water + Light + Time ==>
- 00007 __ Magic__ = Earth + Water + Dark + Space ==>
- 00007 __ Magic__ = Earth + Water + Dark + Time ==>
- 00007 __ Magic__ = Earth + Water + Space + Time ==>
- 00007 __ Magic__ = Earth + Air + Fire + Light ==>
- 00007 __ Magic__ = Earth + Air + Fire + Dark ==>
- 00007 __ Magic__ = Earth + Air + Fire + Space ==>
- 00007 __ Magic__ = Earth + Air + Fire + Time ==>
- 00007 __ Magic__ = Earth + Air + Light + Dark ==>
- 00007 __ Magic__ = Earth + Air + Light + Space ==>
- 00007 __ Magic__ = Earth + Air + Light + Time ==>
- 00007 __ Magic__ = Earth + Air + Dark + Space ==>
- 00007 __ Magic__ = Earth + Air + Dark + Time ==>
- 00007 __ Magic__ = Earth + Air + Space + Time ==>
- 00007 __ Magic__ = Earth + Fire + Light + Dark ==>
- 00007 __ Magic__ = Earth + Fire + Light + Space ==>
- 00007 __ Magic__ = Earth + Fire + Light + Time ==>
- 00007 __ Magic__ = Earth + Fire + Dark + Space ==>
- 00007 __ Magic__ = Earth + Fire + Dark + Time ==>
- 00007 __ Magic__ = Earth + Fire + Space + Time ==>
- 00007 __ Magic__ = Earth + Light + Dark + Space ==>
- 00007 __ Magic__ = Earth + Light + Dark + Time ==>
- 00007 __ Magic__ = Earth + Light + Space + Time ==>
- 00007 __ Magic__ = Earth + Dark + Space + Time ==>
- 20007 __ Magic__ =  +  (Water x64) ==>
- 00007 __ Magic__ = Water + Air + Fire + Light ==>
- 00007 __ Magic__ = Water + Air + Fire + Dark ==>
- 00007 __ Magic__ = Water + Air + Fire + Space ==>
- 00007 __ Magic__ = Water + Air + Fire + Time ==>
- 00007 __ Magic__ = Water + Air + Light + Dark ==>
- 00007 __ Magic__ = Water + Air + Light + Space ==>
- 00007 __ Magic__ = Water + Air + Light + Time ==>
- 00007 __ Magic__ = Water + Air + Dark + Space ==>
- 00007 __ Magic__ = Water + Air + Dark + Time ==>
- 00007 __ Magic__ = Water + Air + Space + Time ==>
- 00007 __ Magic__ = Water + Fire + Light + Dark ==>
- 00007 __ Magic__ = Water + Fire + Light + Space ==>
- 00007 __ Magic__ = Water + Fire + Light + Time ==>
- 00007 __ Magic__ = Water + Fire + Dark + Space ==>
- 00007 __ Magic__ = Water + Fire + Dark + Time ==>
- 00007 __ Magic__ = Water + Fire + Space + Time ==>
- 00007 __ Magic__ = Water + Light + Dark + Space ==>
- 00007 __ Magic__ = Water + Light + Dark + Time ==>
- 00007 __ Magic__ = Water + Light + Space + Time ==>
- 00007 __ Magic__ = Water + Dark + Space + Time ==>
- 30007 __ Magic__ =  +  (Air x64) ==>
- 00007 __ Magic__ = Air + Fire + Light + Dark ==>
- 00007 __ Magic__ = Air + Fire + Light + Space ==>
- 00007 __ Magic__ = Air + Fire + Light + Time ==>
- 00007 __ Magic__ = Air + Fire + Dark + Space ==>
- 00007 __ Magic__ = Air + Fire + Dark + Time ==>
- 00007 __ Magic__ = Air + Fire + Space + Time ==>
- 00007 __ Magic__ = Air + Light + Dark + Space ==>
- 00007 __ Magic__ = Air + Light + Dark + Time ==>
- 00007 __ Magic__ = Air + Light + Space + Time ==>
- 00007 __ Magic__ = Air + Dark + Space + Time ==>
- 40007 __ Magic__ =  +  (Fire x64) ==>
- 00007 __ Magic__ = Fire + Light + Dark + Space ==>
- 00007 __ Magic__ = Fire + Light + Dark + Time ==>
- 00007 __ Magic__ = Fire + Light + Space + Time ==>
- 00007 __ Magic__ = Fire + Dark + Space + Time ==>
- 50007 __ Magic__ =  +  (Light x64) ==>
- 00007 __ Magic__ = Light + Dark + Space + Time ==>
- 60007 __ Magic__ =  +  (Dark x64) ==>
- 70007 __ Magic__ =  +  (Space x64) ==>
- 80007 __ Magic__ =  +  (Time x64) ==>

## Divine Tier
- 10008 __ Magic__ = Divine +  +  (Earth x128) ==>
- 00008 __ Magic__ = Divine + Earth + Water + Air + Fire + Light ==>
- 00008 __ Magic__ = Divine + Earth + Water + Air + Fire + Dark ==>
- 00008 __ Magic__ = Divine + Earth + Water + Air + Fire + Space ==>
- 00008 __ Magic__ = Divine + Earth + Water + Air + Fire + Time ==>
- 00008 __ Magic__ = Divine + Earth + Water + Air + Light + Dark ==>
- 00008 __ Magic__ = Divine + Earth + Water + Air + Light + Space ==>
- 00008 __ Magic__ = Divine + Earth + Water + Air + Light + Time ==>
- 00008 __ Magic__ = Divine + Earth + Water + Air + Dark + Space ==>
- 00008 __ Magic__ = Divine + Earth + Water + Air + Dark + Time ==>
- 00008 __ Magic__ = Divine + Earth + Water + Air + Space + Time ==>
- 00008 __ Magic__ = Divine + Earth + Water + Fire + Light + Dark ==>
- 00008 __ Magic__ = Divine + Earth + Water + Fire + Light + Space ==>
- 00008 __ Magic__ = Divine + Earth + Water + Fire + Light + Time ==>
- 00008 __ Magic__ = Divine + Earth + Water + Fire + Dark + Space ==>
- 00008 __ Magic__ = Divine + Earth + Water + Fire + Dark + Time ==>
- 00008 __ Magic__ = Divine + Earth + Water + Fire + Space + Time ==>
- 00008 __ Magic__ = Divine + Earth + Water + Light + Dark + Space ==>
- 00008 __ Magic__ = Divine + Earth + Water + Light + Dark + Time ==>
- 00008 __ Magic__ = Divine + Earth + Water + Light + Space + Time ==>
- 00008 __ Magic__ = Divine + Earth + Water + Dark + Space + Time ==>
- 00008 __ Magic__ = Divine + Earth + Air + Fire + Light + Dark ==>
- 00008 __ Magic__ = Divine + Earth + Air + Fire + Light + Space ==>
- 00008 __ Magic__ = Divine + Earth + Air + Fire + Light + Time ==>
- 00008 __ Magic__ = Divine + Earth + Air + Fire + Dark + Space ==>
- 00008 __ Magic__ = Divine + Earth + Air + Fire + Dark + Time ==>
- 00000 __ Magic__ = Divine + Earth + Air + Fire + Space + Time ==>
- 00008 __ Magic__ = Divine + Earth + Air + Light + Dark + Space ==>
- 00008 __ Magic__ = Divine + Earth + Air + Light + Dark + Time ==>
- 00008 __ Magic__ = Divine + Earth + Air + Light + Space + Time ==>
- 00008 __ Magic__ = Divine + Earth + Air + Dark + Space + Time ==>
- 00008 __ Magic__ = Divine + Earth + Fire + Light + Dark + Space ==>
- 00008 __ Magic__ = Divine + Earth + Fire + Light + Dark + Time ==>
- 00008 __ Magic__ = Divine + Earth + Fire + Light + Space + Time ==>
- 00008 __ Magic__ = Divine + Earth + Fire + Dark + Space + Time ==>
- 00008 __ Magic__ = Divine + Earth + Light + Dark + Space + Time ==>
- 20008 __ Magic__ = Divine +  +  (Water x128) ==>
- 00008 __ Magic__ = Divine + Water + Air + Fire + Light + Dark ==>
- 00008 __ Magic__ = Divine + Water + Air + Fire + Light + Space ==>
- 00008 __ Magic__ = Divine + Water + Air + Fire + Light + Time ==>
- 00008 __ Magic__ = Divine + Water + Air + Fire + Dark + Space ==>
- 00008 __ Magic__ = Divine + Water + Air + Fire + Dark + Time ==>
- 00008 __ Magic__ = Divine + Water + Air + Fire + Space + Time ==>
- 00008 __ Magic__ = Divine + Water + Air + Light + Dark + Space ==>
- 00008 __ Magic__ = Divine + Water + Air + Light + Dark + Time ==>
- 00008 __ Magic__ = Divine + Water + Air + Light + Space + Time ==>
- 00008 __ Magic__ = Divine + Water + Air + Dark + Space + Time ==>
- 00008 __ Magic__ = Divine + Water + Fire + Light + Dark + Space ==>
- 00008 __ Magic__ = Divine + Water + Fire + Light + Dark + Time ==>
- 00008 __ Magic__ = Divine + Water + Fire + Light + Space + Time ==>
- 00008 __ Magic__ = Divine + Water + Fire + Dark + Space + Time ==>
- 00008 __ Magic__ = Divine + Water + Light + Dark + Space + Time ==>
- 30008 __ Magic__ = Divine +  +  (Air x128) ==>
- 00008 __ Magic__ = Divine + Air + Fire + Light + Dark + Space ==>
- 00008 __ Magic__ = Divine + Air + Fire + Light + Dark + Time ==>
- 00008 __ Magic__ = Divine + Air + Fire + Light + Space + Time ==>
- 00008 __ Magic__ = Divine + Air + Fire + Dark + Space + Time ==>
- 00008 __ Magic__ = Divine + Air + Light + Dark + Space + Time ==>
- 40008 __ Magic__ = Divine +  +  (Fire x128) ==>
- 00008 __ Magic__ = Divine + Fire + Light + Dark + Space + Time ==>
- 50008 __ Magic__ = Divine +  +  (Light x128) ==>
- 60008 __ Magic__ = Divine +  +  (Dark x128) ==>
- 70008 __ Magic__ = Divine +  +  (Space x128) ==>
- 80008 __ Magic__ = Divine +  +  (Time x128) ==>

---

- 00000 ____Rock Magic____ = Earth + Earth strong earth
- 00000 ____Rain Magic____ = Water + Water constant water
- 00000 ____Wind Magic____ = Air + Air strong wind
- 00000 ____Flame Magic____ = Fire + Fire strong fire
- 00000 ____Luminous Magic____ = Light + Light strong light
- 00000 ____Shadow Magic____ = Dark + Dark absence of light control
- 00000 ____Position Magic____ = Space + Space locate everything in space
- 00000 ____Reduction Magic____ = Time + Time slow down time

- 00000 ____Stone Magic____ = Rock + Rock (Earth x4) stronger earth
- 00000 ____Flood Magic____ = Rain + Rain (Water x4) water overflow
- 00000 ____Gust Magic____ = Wind + Wind (Air x4) stronger wind
- 00000 ____Blaze Magic____ = Flame + Flame (Fire x4) stronger fire
- 00000 ____Radiant Magic____ = Luminous + Luminous (Light x4) Stronger light
- 00000 ____Black Magic____ = Shadow + Shadow (Dark x4) 
- 00000 ____Domain Magic____ = Position + Position (Space x4) Area control
- 00000 ____Acceleration Magic____ = Reduction + Reduction (Time x4) Speed up time

- 00000 ____Bedrock Magic____ = Stone + Stone (Earth x8) Strong earth
- 00000 ____Current Magic____ = Flood + Flood (Water x8) Focused water stream
- 00000 ____Vortex Magic____ = Gust + Gust (Air x8) Strong focused winds
- 00000 ____Inferno Magic____ = Blaze + Blaze (Fire x8) Aggressive fire
- 00000 ____Ray Magic____ = Radiant + Radiant (Light x8) Focus light to a path
- 00000 ____Corruption Magic____ = Black + Black (Dark x8) Disrupt other magics
- 00000 ____Warp Magic____ = Domain + Domain (Space x8) Instant movement
- 00000 ____Pause Magic____ = Acceleration + Acceleration (Time x8) Stop time

- 00000 ____Igneous Magic____ = Bedrock + Bedrock (Earth x16) Earth's inner structure 
- 00000 ____Whirlpool Magic____ = Current + Current (Water x16) Watery vortex control
- 00000 ____Cyclone Magic____ = Vortex + Vortex (Air x16) Destructive winds
- 00000 ____Redfire Magic____ = Inferno + Inferno (Fire x16) Strongest fire
- 00000 ____Lazer Magic____ = Ray + Ray (Light x16) Strong concentrated light beam
- 00000 ____Absorbtion Magic____ = Corruption + Corruption (Dark x16) Absorb abd steal all 
- 00000 ____ Magic____ = Dark + Space + Time 
- 00000 ____Gate Magic____ = Warp + Warp (Space x16) Large warp gates
- 00000 ____Regression Magic____ = Pause + Pause (Time x16) Reverse time to certain extent

- 00000 ____Quake Magic____ = Igneous + Igneous (Earth x32) Tremble the world's plates
- 00000 ____Tidal Magic____ = Whirlpool + Whirlpool (Water x32) Destructive waves
- 00000 ____Jet Magic____ = Cyclone + Cyclone (Air x32) Fast pressurized powerful wind
- 00000 ____Bluefire Magic____ = Redfire + Redfire (Fire x32) Fire that requires most control
- 00000 ____Star Magic____ = Lazer + Lazer (Light x32) Pure bodies of energy
- 00000 ____Anti Magic____ = Absorbtion + Absorbtion (Dark x32) Magic Negation
- 00000 ____Subspace Magic____ = Gate + Gate (Space x32) Pocket dimension
- 00000 ____Temporal Magic____ = Regression + Regression (Time x32) Move throughout time

- 00000 ____Mountain Magic____ = Quake + Quake (Earth x64) Terraform the earth 
- 00000 ____Ocean Magic____ = Tidal + Tidal (Water x64) Control of the ocean and its depths 
- 00000 ____Sky Magic____ = Jet + Jet (Air x64) The power of the atmosphere
- 00000 ____Whitefire Magic____ = Bluefire + Bluefire (Fire x64) Purest, hottest form of fire
- 00000 ____Sun Magic____ = Star + Star (Light x64) Power of the biggest star
- 00000 ____Void Magic____ = Anti + Anti (Dark x64) Use complete devour
- 00000 ____Gravity Magic____ = Subspace + Subspace (Space x64) Use gravitational forces
- 00000 ____Infinite Magic____ = Temporal + Temporal (Time x64) Control over all time

- 10008 __Creation Magic__ = Divine +  +  (Earth x128) 
- 50008 __Cosmic Magic__ = Divine +  +  (Light x128) 
- 60008 __Nothing Magic__ = Divine +  +  (Dark x128)  
- 70008 __Realm Magic__ = Divine +  +  (Space x128) 
- 80008 __Eternal Magic__ = Divine +  +  (Time x128) 


# Introductions
Space magic is one of the primary planes. It exists on a 4D scale.

# Basic Tier 1:
Space Magic - 1%
> The power of the world’s place

# Low Tier 2:
Position Magic = Space + Space
> Your area within the world is set

# Mid Tier 3:
Domain Magic = Position + Position
> Claim your area and control it

# High Tier 4:
Teleport Magic = Domain + Domain
> Move to a location instantly

# Advanced Tier 5:
Barrier Magic = Space + Air + Earth
> Defend whats important with magic walls

Cosmic Magic = Space + Time + Dark
> Use the astronomic arts

Warp Magic = Teleport + Teleport
> Travel anywhere with warp gates

# Supreme Tier 6:
Subspace Magic = Warp + Warp
> Use the spatial magic of pocket dimensions

# Mythical Tier 7:
Gravity Magic = Subspace + Subspace
> Invoke the weight of world 

# Divine Tier 8:


Time magic is the other main plane. It exists on a 2D scale.

# Basic Tier 1:
Time Magic - 1%
> The power of the world’s duration

# Low Tier 2:
Reduction Magic = Time + Time
> Your timeline slows down some

# Mid Tier 3:
Acceleration Magic = Reduction + Reduction
> Speed yourself up at a quick pace

# High Tier 4:
Regression Magic = Acceleration + Acceleration
> Claim the time power to revert the timeline

# Advanced Tier 5:
Pause Magic = Regression + Regression
> Use the power to stop time

# Supreme Tier 6:
Temporal Magic = Pause + Pause
> Evoke time travel

# Mythical Tier 7:
Infinite Magic = Temporal + Temporal
> Cast endless time

# Divine Tier 8:


Water magic relies on the seas and oceans to draw power.

# Basic Tier 1:
Water Magic - 22%
> The power of the world’s waters

# Low Tier 2:
Rain Magic = Water + Water
> The water of the skies recognize you

# Mid Tier 3:
Ice Magic = Water + Air
> The frost of the world now heeds your command

Steam Magic = Water + Fire
> Gasic vapor enshrouds you

Potion Magic = Water + Light
> Whip up natural remedies with your power 

Flood Magic = Rain + Rain
> The unruly forces of the seas hear you

# High Tier 4:
Current Magic = Flood + Flood
> The underwater streams of the seas heed you

# Advanced Tier 5:
Darkice Magic = Water + Air + Dark
> The coldest ice which steals lifeforce

Whirlpool Magic = Current + Current
> Drown your foes in swirling waves

# Supreme Tier 6:
Tidal Magic = Tidal + Tidal
> Evoke the destructive power of tsunamis

# Mythical Tier 7:
Ocean Magic = Tidal + Tidal
> Create ocean-like bodies of water


Mastery
	•	Concept: The pursuit of excellence and deep understanding in any chosen discipline.
	•	Scope: Covers advanced technique, specialization, and expertise—whether in combat, crafting, or any other field.
	•	Examples: Swordsmanship mastery, master chef, expert negotiator.
2. Adaptation
	•	Concept: The ability to adjust, improvise, and overcome changing circumstances.
	•	Scope: Encompasses survival, resourcefulness, learning new skills quickly, and thriving in unfamiliar environments.
	•	Examples: Wilderness survival, urban adaptability, quick learner, improvisational tactics.
3. Expression
	•	Concept: The creative and personal manifestation of skill or aura.
	•	Scope: Includes arts, hobbies, communication, and unique personal styles in combat or interaction.
	•	Examples: Painting, music, storytelling, signature fighting style.
4. Mobility
	•	Concept: The capacity for movement, positioning, and spatial awareness.
	•	Scope: Encompasses physical movement, evasion, parkour, and tactical positioning.
	•	Examples: Acrobatics, stealth, mounted riding, tactical retreat.
5. Interaction
	•	Concept: Skills that involve engaging with the world, people, or systems.
	•	Scope: Covers social skills, negotiation, leadership, and technical manipulation (like lockpicking or hacking).
	•	Examples: Persuasion, leadership, engineering, infiltration.
6. Creation
	•	Concept: The ability to build, craft, or invent.
	•	Scope: Encompasses all forms of crafting, invention, and construction—physical or conceptual.
	•	Examples: Blacksmithing, alchemy, architecture, invention.
7. Perception
	•	Concept: Awareness and understanding of surroundings, people, and situations.
	•	Scope: Includes observation, intuition, analysis, and investigation.
	•	Examples: Detecting lies, tracking, tactical analysis, puzzle-solving.
8. Resilience
	•	Concept: The ability to endure, recover, and persist.
	•	Scope: Covers physical toughness, mental fortitude, and resistance to negative effects.
	•	Examples: Pain tolerance, stress management, poison resistance, stamina.
Summary Table

Distinct, Non-Overlapping Skill Categories
1. Combat
	•	Definition: All skills directly related to fighting, weapon use, and martial prowess.
	•	Examples: Swordsmanship, unarmed fighting, archery, defensive maneuvers.
2. Mobility
	•	Definition: All skills related to movement, positioning, and physical traversal.
	•	Examples: Sprinting, climbing, swimming, dodging, parkour.
3. Crafting
	•	Definition: All skills involving the creation, repair, or modification of items and equipment.
	•	Examples: Blacksmithing, tailoring, alchemy, engineering.
4. Survival
	•	Definition: All skills needed to endure and thrive in challenging environments.
	•	Examples: Foraging, hunting, shelter-building, first aid, navigation.
5. Social
	•	Definition: All skills for interacting with, influencing, or understanding others.
	•	Examples: Persuasion, intimidation, negotiation, empathy, leadership.
6. Perception
	•	Definition: All skills related to sensing, noticing, or analyzing the environment or situations.
	•	Examples: Spotting hidden objects, tracking, reading body language, investigation.
7. Technical
	•	Definition: All skills involving the use or understanding of technology, mechanisms, or complex systems.
	•	Examples: Lockpicking, hacking, machinery operation, trap disarming.
8. Expression
	•	Definition: All skills related to creative or artistic pursuits and personal self-expression.
	•	Examples: Painting, music, performance, writing, crafting unique signature moves.

Gardening and farming skills are best placed under Crafting or Survival, depending on your system’s focus:
	•	If your Crafting category includes all forms of creating, producing, and managing resources (like blacksmithing, alchemy, and cooking), then gardening and farming fit naturally here as they involve growing, harvesting, and managing crops and plants.
	•	If your Survival category emphasizes self-sufficiency, living off the land, and resource gathering, gardening and farming can also fit here, especially if you want to highlight skills like foraging, food production, and sustainable living.
Some games and guides group gardening and farming with both crafting (for the production aspect) and survival (for the self-sufficiency aspect). For maximum clarity and minimal overlap, choose the category that best matches how you want players to use these skills in your game. If gardening and farming are about producing goods and managing resources, put them in Crafting. If they’re about staying alive and self-sufficiency, use Survival.

Great observation! To further clarify and separate “Crafting” and “Expression” so that art and smithing are not grouped together, you can divide them into more precise, non-overlapping categories:
Revised Skill Categories
1. Artisanry
	•	Definition: All skills related to the creation and improvement of tangible items, tools, equipment, and structures.
	•	Examples: Blacksmithing, carpentry, tailoring, alchemy, engineering, weapon forging, armor crafting, cooking, jewelry making, farming, gardening.
2. Artistry
	•	Definition: All skills related to creative, aesthetic, and expressive pursuits that communicate ideas, emotions, or culture.
	•	Examples: Painting, sculpture, music, dance, writing, acting, calligraphy, performance, design, decorative crafts.

Redistinguished Skill Categories
1. Production
	•	Definition: Skills related to the practical creation, assembly, and maintenance of useful items, tools, equipment, and resources.
	•	Focus: Utility, efficiency, and function.
	•	Examples: Blacksmithing, tailoring, farming, tool-making, cooking, construction, alchemy (for potions), gardening.
2. Performance
	•	Definition: Skills related to presentation, entertainment, and the direct communication of ideas or emotions to an audience.
	•	Focus: Expression through action or display.
	•	Examples: Music, dance, acting, oration, storytelling, theatrical combat, ceremonial displays.
3. Aesthetics
	•	Definition: Skills focused on the design, decoration, and beautification of objects, spaces, or oneself.
	•	Focus: Visual, auditory, or sensory appeal; the enhancement of form beyond function.
	•	Examples: Painting, sculpture, calligraphy, engraving, fashion design, interior decoration, weapon/armor embellishment, tattooing.

# Introduction
Skills are how players get better at living

## Movement
Human movement skills

Stumbling  Walking  Hiking  Marching
Jogging  Running  Sprinting  Twitchspeed  Lightspeed
Hopping  Jumping  Bouncing  Leaping
Curling  Rolling  Twisting  Spinning  
Floating  Swimming  Diving  Propulsion
Laying  Crawling  Proning  Bear Call
Mounting  Climbing  Rising  Mountain Climber
Levitating  Flying  Soaring  Jetting  Supersonic

## Survival
Human survival skills

Food Prepping  Cooking  Cuisine  Chef  
Hunting  
Farming
Foraging
Boating
Plant Knowledge
Beast Knowledge
Vision
Smell
Taste
Hearing
Fishing
Crafting
Camping
Sleeping
Breathing
Building
Scavaging
Medical
Taming
Exploring

## Combat
Combat skills

Fighting
Swordplay, swordman
Axeplay
Hammerplay
Spearplay
Shieldplay
Daggerplay
Halberdplay
Scytheplay
Tomeplay
Staffplay
Maceplay
Clubplay
Guarding
Archery
Mana guaging
Aura prowess
Aura Detection
Mana Detection
Status Concealment
Taunt

## Occupational
Job skills

Strategy
Alchemy
Forging
Smithing
Writing
Reading
Acting
Smithing
Brewing
Stealth
Lockpicking
Arithmetic
Accounting
Bookkeeping
Hospitality
Housekeeping
Leadership
Planning
Servitude
Sorting
Mining
Ruling
Tailoring
Mercantile

## Hobbyist
Hobbies and interests skills


Baking
Dancing
Painting
Singing
Music
Dueling
Collecting