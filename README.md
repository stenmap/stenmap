# Stenmap
This is an overview of different parts of Stenmap framework and how they all fit in together. 

## Introduction 
Learning is something we do all the time. Young humans imitate olders to learn how to deal with the world. Learning is fun and interesting. Later, learning is put into a structure. Unfortunately, this structure often lacks the general overview. People learn things, because that enables them to learn other things. 

Computer games are different. A player can usually decide early on what he/she wants to become. Afterwards the player can build his/her skills accordingly. Pretty much every role playing game has a learning tree. They are called differently: skill tree, skill build, learning path etc, but the main idea is the same - to give the player an understanding where he/she is now and where he/she is going to. 

Stenmap is created so that anyone can build their own learning trees in order to structure and evaluate different competencies and skills. The name Stenmap comes from *S*kills, 10 and map (s-ten-map): 
* _Skills_ form arguably the most important part of competencies. Knowledge, motivation, values and other parts of competencies can all be reduced to some characteristic skills (well, at least in a very simplified approach). 
* _10_ means the default normalised scale of skills. If we want to get a general profile of a person's skillset, it is nice to have a standardized way of evaluating his/her skills. The default number of skill levels (10) can be modified.
* _Map_ is the general structure where all this information is put together. 

## Components of Stenmap
Stenmap consists of the following components: 
* The core data structure that consists of:
  * skills (nodes)
  * skill relations (edges)
  * skill-sets (groups)
* Measurments data structures that consist of:
  * measurment points (define measured metrics)
  * scoring data (scorebot raw output format)
  * metrics quantifying station (define different levels for non-boolean metrics)
  * measurment points groupings
* Events and expectations
  * event schedule
  * expected impact of events
  

Soon there will be more specific samples of the data structures like this: 
```JSON
{
	"timestamp": "2016-10-27T05:06:21+02:00",
	"m-135": 0,
	"m-162": 200,
}
```


