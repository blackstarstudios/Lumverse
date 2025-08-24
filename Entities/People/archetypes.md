# Archetypes

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