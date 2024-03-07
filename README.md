# MDP REPRESENTATION

## AIM:
To represent any one real-world problem in MDP form

## PROBLEM STATEMENT:

### Problem Description
To maintain the traffic signal controls .The role of the agent is to access to change the signals colour with representative of traffics.
### State Space
{ Red , Green , Yellow } = { 0 , 1 , 2 }


### Sample State
Red
### Action Space
{ Stop the vehicle on red signal hits , ready to go } -> { 0 , 1 }

### Sample Action
Stop the vehicle on red signal hits

### Reward Function
R={ +1 ,ready to go gignal returns green 0 , otherwise }

### Graphical Representation
![ex1](https://github.com/ganesha360/mdp-representation/assets/120884552/5f6442e4-87c0-441e-b9e9-b0b04974399d)


## PYTHON REPRESENTATION:
```python
P={0: {0: [(1.0, 0, 0.0, True)],
       1: [(1.0, 0, 0.0, True)]},
   1: {0: [(1.0, 0, 0.0, True)],
       1: [(1.0, 2, 1.0, True)]},
   2: {0: [(1.0, 2, 0.0, True)],
       1: [(1.0, 2, 0.0, True)]}
  }
```

## OUTPUT:
![ex2](https://github.com/ganesha360/mdp-representation/assets/120884552/039add8a-052b-489d-9a42-80a61271837c)


## RESULT:
Thus the given real world problem is successfully represented in a MDP form .

