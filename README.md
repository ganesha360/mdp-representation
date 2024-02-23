# MDP REPRESENTATION

## AIM:
Write your aim here

## PROBLEM STATEMENT:

### Problem Description
Develop a game application where an agent promotes players upon level clearance and demotes upon loss using reinforcement learning.

### State Space
```
{A1,A2,A3}--> {0,1,2}
A1--> LEVEL 1
A2--> LEVEL 2 
A3--> LEVEL 3

```

### Sample State
A1--> 0 --> LEVEL 1

### Action Space
```
{W,L}-->{0,1}
W-->True
L-->False
```

### Sample Action
W--> 0 --> True

### Reward Function
R = { +1 , if we come closer to the winning 0 , if not

### Graphical Representation
![ex1](https://github.com/ganesha360/mdp-representation/assets/120884552/5f6442e4-87c0-441e-b9e9-b0b04974399d)


## PYTHON REPRESENTATION:
```
P = {
    0:{
        0: [(0,1,1,True)],
        1: [(1.0,0,1.0,False)]
    },
    1:{
        0: [(0,2,1,True)],
        1: [(1,0,1,False)]
    },
    2:{
        0: [(0,2,1,True)],
        1: [(1,1,1,False)]
    }
}
P
```

## OUTPUT:
![ex2](https://github.com/ganesha360/mdp-representation/assets/120884552/039add8a-052b-489d-9a42-80a61271837c)


## RESULT:
Write your output here

