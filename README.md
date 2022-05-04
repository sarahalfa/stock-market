# stock-market

project to attempt to predict the price of turnips being sold within animal crossing's stock/stalk market 

note to self; research stock market algorithm predictors + research AC stalk market predictors/figure out if there even is a possibility to have a definite price to be predicted 

max price: 660b; min price: 9b
different price morning compared to night

probabilities; 4 patterns in ACNH;
eventual % increase of occurences for each patterns:
random: 35%; decreasing: 15%; large spike: 25%; small spike: 25%
(within these probabilities there are also further factors so will need to embedd those in as well)
(have a look into probability and python)
note to self; pattern from previous week will impact the likelihood of the following week's pattern; so maybe this will need the player to record their patterns for the week to then get a prediction for the following week 

possibilites;
if x pattern last week, probabilities as follows;
random: 20% random; 15% decreasing; 30% large spike; 35% small spike
decreasing: 25% random; 5% decreasing; 45% large spike; 25% small spike
large spike: 50% random: 5% decreasing; 45% large spike; 25% small spike
small spike: 45% random; 15% decreasing; 25% large spike; 15% small spike


also, due to *possible* glitches with time travel and visiting other islands, this can affect stock price, thus can code this to ask the user 'have you visited another town within x time period?' then it'll have a yes/no option to see if there is a decrease/increase in the individual's stock price on their island

loose tendency for a rise from Mon-Wed then drop from Thurs-Sat 
turnips can't be sold on Sundays
