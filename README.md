# random-loot-generator

Loot-Generator: this case study shows that giving players a random loot guaranted rate 
makes satisfation grows 

## But how to make a normal random item generator ? ##
        if(Math.Random(0,100) < 60 ) //this gives a 60% chance of the item (normal)
        else if(Math.Random(0,100) < 85 && > 60 ){} //this gives a 25% chance of the item (rare)
        else if(Math.Random(0,100) < 95 && > 85 ){} //this gives a 10% chance of the item (epic)
        elseif(Math.Random(0,100) > 95 ){} //this gives a 5% chance of the item (legendary)

## The problem: ##
how math.random works: 
Pseudorandom numbers are selected with probability equal to a set of finite numbers. 
The numbers chosen are not completely random because a mathematical algorithm is used to select the items, 
but are randomly selected for practical purposes. The current implementation of the Random class is based 
on a modified version of the Donald E. Knuth subtracted random number algorithm.
