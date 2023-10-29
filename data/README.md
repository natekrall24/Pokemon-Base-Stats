# Data

The dataset comes from kaggle.com from the page titled "The Complete Pokemon Dataset" (link: https://www.kaggle.com/datasets/rounakbanik/pokemon/). It was created by Rounak Banik in 2017.

There are 801 observations and 41 columns in the original dataset.

## Data Dictionary for pokemon.csv

name: The English name of the Pokemon [string]

japanese_name: The Original Japanese name of the Pokemon [string]

pokedex_number: The entry number of the Pokemon in the National Pokedex [whole number between 1 and 801]

percentage_male: The percentage of the species that are male. [percentage value, blank if the Pokemon is genderless]

type1: The Primary Type of the Pokemon (every pokémon has this) [one of the following string values: Normal, Fire, Water, Grass, Flying, Fighting, Poison, Electric, Ground, Rock, Psychic, Ice, Bug, Ghost, Steel, Dragon, Dark, and Fairy]

type2: The Secondary Type of the Pokemon (not all pokémon have this) [one of the following string values: Normal, Fire, Water, Grass, Flying, Fighting, Poison, Electric, Ground, Rock, Psychic, Ice, Bug, Ghost, Steel, Dragon, Dark, and Fairy]

classification: The Classification of the Pokemon as described by the Sun and Moon Pokedex [string]

height_m: Height of the Pokemon [number in meters]

weight_kg: The Weight of the Pokemon [number in kilograms]

capture_rate: Capture Rate of the Pokemon [whole number]

base_egg_steps: The number of steps required to hatch an egg of the Pokemon [whole number]

abilities: A stringified list of abilities that the Pokemon is capable of having

experience_growth: The Experience Growth of the Pokemon [whole number]

base_happiness: Base Happiness of the Pokemon [whole number]

against_?: Eighteen features that denote the amount of damage taken against an attack of a particular type [one of the following numbers: 0.5, 1, 2, 4]

hp: The Base HP of the Pokemon [whole number]

attack: The Base Attack of the Pokemon [whole number]

defense: The Base Defense of the Pokemon [whole number]

sp_attack: The Base Special Attack of the Pokemon [whole number]

sp_defense: The Base Special Defense of the Pokemon [whole number]

speed: The Base Speed of the Pokemon [whole number]

base_total: total base stats of the Pokemon [whole number]

generation: The numbered generation which the Pokemon was first introduced [whole number 1-7]

is_legendary: Denotes if the Pokemon is legendary.[0 = not legendary, 1 = legendary]

This codebook was modified from the codebook present on the kaggle page for the dataset at this link: https://www.kaggle.com/datasets/rounakbanik/pokemon/.