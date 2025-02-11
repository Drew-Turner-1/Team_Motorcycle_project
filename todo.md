# Functionality #
## 1 Random team generator
- generates a random team of six pokemon and displays their names to the user in a list.

## 2 Manual team generator
- Allows the user to generate a team of six pokemon by typing the names and displays their names to the user in a list.

## 3 Team stats analyzer
- Takes input from the user (which team of six pokemon they would like analyzed) and pulls the stats (HP, attack, defense, SP attack, SP defense, and speed) for each.
- Then averages each stat over the six pokemon and stores those averages.
- Then displays those averages in a radar chart format.
- Also displays ratings (poor, mid, or good) for each stat average, listed below the radar chart in list format.

## 4 Team strength/weakness analyzer
- Takes input from the user (which team of six pokemon they would like analyzed (could also just be the current team)) and pulls the type(s) for each.
- Analyzes each pokemon's strengths and weaknesses (how many attack types are "super effective" and how many are "not very effective" to each pokemon (Treating "no effects" as not very effective)) and stores that value corresponding to the pokemon.
- Then subtracts the total number of "not very effective" matchups (good) to the total "super effective" matchups (bad) for all pokemon and stores that value.
- Then compares the value stored in the last step to a determined range of values and displays the rating based on where that value lies in that range (Good, average, or poor.).