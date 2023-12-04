# RLCS_21-22
<hr style="border:2px solid black">

## <u>Project Description</u>
Rocket League is a video game where players use vehicles to play soccer. It was first released in July 2015 and has skyrocketed in popularity so much so that it has been adopted as an esport. For those that are unfamiliar with the term, according to the Harvard International Review "esports are video games that are played in a highly organized competitive environment." The name of the esports competition for Rocket League is RLCS (Rocket League Championship Series), and we'll be taking a look as some of the best players in the world and how they did in this competetion.

## Goals: 
* Determine what stats are most important to winning a game. 
* Explore player and team specific data to see what makes these the best of the best

<hr style="border:2px solid black">

# Initial Thoughts
 
* As important as goals are, assists likely have a huge role in wins achieved. 
* No one team is going to outshine the others, initial thoughts are that all of these teams will be close in skill level.
 
<hr style="border:2px solid black"> 


# Data Dictionary
| Feature               | Definition |
|:----------------------|:-----------|


<hr style="border:2px solid black"> 


# The Plan
 
Plan --> Acquire --> Prepare --> Explore --> Model --> Deliver
 

#### Acquire
    * Determine additional dataframes to increase selectable features
    * Confirm viability of merging with original dataframe
    * Store additional dataframes as csv to bring into notebook
#### Prepare
    * Clean dataframes in anticipation of merging datasets
    * Create aggregate features from listed features
    * Merge dataframes
    * Apply MinMax Scaler to data
#### Explore
##### Before Clustering
    * Begin feature selection and narrow down on target(s)
    * Perform initial comparisons to determine meaningful pairs of features
##### After Clustering
    * Perform comparisons on clustered data 
    * Determine statistical signifance of pairings as a result of defined clusters
#### Deliver
    * Develop an interactive dashboard where families can select features they deem the most important

<hr style="border:2px solid black"> 

# Steps to Reproduce
>1) Download collab_csv.zip and wrangle.py into same folder
>2) Open zipped file and run wrangle function in notebook
<hr style="border:2px solid black"> 
 
### <u>Recommendations:</u>

>* Affordability is extremely important, but considering outside factors can help shape the ideal community for you.
>* Families should keep an open mind when looking at ideal places to move to. (Maybe what's best for your family is somewhere you never imagined yourself living)

### <u>Next Steps:</u>

>* Find additional dataframes to continue adding possible features for families to select
>* Take analysis to county level for increased granularity
>* Develop dashboard into website or app for easier access