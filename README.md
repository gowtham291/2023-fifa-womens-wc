# 2023 FIFA Women's World Cup - A Prediction Model
Simulating the 2023 FIFA Women's World Cup which has the backdrop of being injury/missing player central, and taking place in peak summer down under. What could go wrong, eh?

Inspired by previous work on the ! [2022 Men's edition](https://github.com/gowtham291/2022_fifa-mens_wc) that was helped us talk about the importance of the story that the data tells us, and the power and responsibility we hold because of it.

The 2022 Men's WC brought light to the island nation of Qatar (and how a tiny island nation that has never even qualified for a world cup finals hosted it). In the process of this work, we hope to unravel the ways the Women's WC differs from the Men's, how the gameplay and historical trends are themselves maybe different, and most especially, the teams(such as the USWNT, the Lionesses and the Matildas).

A simple Logistic Regression model was trained on data from past international matches. Patterns in the data were summarized in the form of two important features - the average scorring patterns and the frequency of recent results and their outcomes. 
- Since the ability to score goals has been historically imperative to reaching the final stages of the tournaments, the average scoring pattern of recent matches is ideated to define the teams' form coming into the tournament.
- In a results-oriented sport like football, teams are also impacted by recent game outcomes. Mentalities can change depending on if they come into the tournament on the back of long winning or losing streaks.
- Even though the dataset was devoid of FIFA rankings, the assumption was made, based on past tournament trends, that incorporating the current rankings into the final statistics would only improve the prediction model's performance. This also ensures that temas like Jamaica, who come into their first World Cup on the back of great recent results in their mostly one-sided regional games, would not beat top European teams.  

The results were compared against a purely FIFA rankings-based prediction model. The predictions will also be compared against the actual tournament results. 

On the eve of the World Cup, the model predicts England to win it. Here's keeping track of ![how the model has done upto now](). 

![Knockout Stage Bracket](model-based.png)
