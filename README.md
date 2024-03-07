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
![rlex](https://github.com/ganesha360/mdp-representation/assets/120884552/628b850a-f159-4d5a-b295-b17e4c5a95f8)



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
![image](https://github.com/ganesha360/mdp-representation/assets/120884552/83351e01-d14e-4ef5-b927-9d1eab07e7ee)



## RESULT:
Thus the given real world problem is successfully represented in a MDP form .

