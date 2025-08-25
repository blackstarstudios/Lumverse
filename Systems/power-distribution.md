# Power Distribution

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