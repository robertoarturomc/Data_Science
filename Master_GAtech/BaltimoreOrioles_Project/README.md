# Project Scope 
## Objective: 
The Baltimore Orioles Baseball Analytics department is interested in creating a simple formula that can estimate when an American League manager removes his starting pitcher from a game. This model will mainly benefit the members of the front office and the coaching staff. 
The manager has limited communication, so ideally the model would be able to be run manually by him or any member of the staff; to further emphasize that, the team has been using the codename of “clipboard model” . 
## Hypothesis 
The likelihood that a generic American League manager would have removed his pitcher serves as a useful metric of how concerned the Baltimore Orioles Manager should be. 
## Problem description: 
For each baseball game played, each team has an “starting” pitcher. He is expected to play most of it, giving the best possible odds of winning to his team before giving his place to another pitcher. 
The decision of removal is based on a variety of factors, such as: 
* The pitcher’s performance 
* His fatigue level 
* The upcoming hitters he is scheduled to face.

The purpose of the project is to model the manager’s decision process for this situation.  
Ideally, this will be a simple counting system in which pre-defined points accumulate when certain events happen during a pitcher’s start, like him throwing a pitch, giving up a hit, a walk or an inning concluding. 
Typically, managers pull a pitcher when they have started to perform poorly. However, the team thinks that managers try to get ahead of this performance drop and as a result the pitcher being removed typically represents the manager's best estimate of this change point. 

There is no preference for reducing either the false positives or false negatives. The tradeoff would be very dependent on the game state and the availability of other members of the bullpen. For instance, if the team has a one run lead and the 
whole bullpen available, they would be much more aggressive in pulling the starter than if having had a large lead and the bullpen threw