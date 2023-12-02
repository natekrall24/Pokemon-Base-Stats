# Predicting a Pokémon’s Strength Using Variables Other Than Base Stats
by STA 210 BDN: Nate Krall, Daniel Cohen, Brian Kim

## Summary
A deeper look into the numbers in the game of Pokemon shows a game filled relationships
among several characteristics of the pokemon. Each creature has its own specific set of base
statistics, colloquially referred to as “base stats,” including attack, special attack, defense, special defense, and speed, which indicate that pokémon’s battle prowess. Summing these stats
yields a pokémon’s total base stats, the best measure of a pokémon’s overall strength – common knowledge for any pokémon fan. We are interested in measuring a pokémon’s strength
without using base stats as predictors, giving us insight on how strong the relationships among
pokémon’s different characteristics actually are. Thus, we are looking to answer the following
research question: Can we predict a Pokémon’s Base Stat Total from other variables? In other words, we are analyzing how well variables such as the pokémon’s type,
capture rate, growth rate, generation, height, weight, base happiness, weaknesses, and if the
pokémon is legendary or not can predict a pokémon’s total base stats. We hypothesize that
a multiple linear regression model including some formation of these predictor variables will
be a somewhat strong predictor for base_total – thinking about the game, stronger pokémon
would seem to have certain values for these predictor variables when compared to weaker ones:
for example, legendary pokémon tend to be stronger in battle than non legendary pokémon,
so we might expect is_legendary to be a useful predictor for base_total. We retrieved the
dataset from kaggle.com, a large data science online community, and the dataset is called “The
Complete Pokemon Dataset” created by Rounak Banik in 2017. The dataset was retrieved
via web scraper from the website serebii.net. Since it was formed in 2017, the dataset does
not include pokémon from more recent games, but still includes 801 pokémon, meaning the
dataset has 801 observations. However, note that we removed one pokémon from the original
801 pokémon, Minior, from the dataset, since it has 2 different forms and has an uninterpretable capture rate. We noticed that while reading the .csv file, R automatically translated
the *capture_rate* variable to characters because Minior’s capture rate was listed as: “30
(Meteorite)255 (Core)”. We decided to exclude this observation from the model because of its
uninterpretable characteristics, and after, we casted *capture_rate* an integer instead of a
character. The dataset contains 23 variables, explanations of which can be viewed in our data
dictionary.
