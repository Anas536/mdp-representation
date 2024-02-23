## Name: Mohamed Anas O.I
## Reg no: 212223110028

# MDP REPRESENTATION

## AIM:

To represent a Markov Decision Process(MDP) problem in the following ways.
Text representation, Graphical representation, Python - Dictonary representation.


## PROBLEM STATEMENT:

### Problem Description
To harvest wheat field among number of fields.

### State Space
Number of sections of wheat fields.
  S1 -> Section 1
  S2 -> Section 2
  S3 -> Section 3

### Sample State
  S1 -> Section 1

### Action Space
  {H, NH}
    H -> Harvested
    NH -> Not Harvested
    
### Sample Action
  H -> Harvested

### Reward Function

  ```
  R= {
    +1, if eligible
    +0, otherwise
  }
  ```

### Graphical Representation

![WhatsApp Image 2024-02-23 at 09 29 09_05aa0247](https://github.com/Anas536/mdp-representation/assets/139841834/74878335-172a-4840-98fa-58e0b7de23a7)

## PYTHON REPRESENTATION:
```
#Name: Mohamed Anas O.I
#Ref No: 212223110028

T = {
    0:{
        0: [(0.8, 0, 0.0, True), (0.2, 1, 1.0, True)],
        1: [(0.8, 1, 1.0, True), (0.2, 0, 0.0, True)]
    },
    1:{
        0: [(0.8, 0, 0.0, True), (0.2, 2, 1.0, True)],
        1: [(0.8, 2, 1.0, True), (0.2, 0, 0.0, True)],
    },
    2: {
        0: [(0.8, 1, 0.0, True), (0.2, 2, 0.0, True)],
        1: [(0.8, 2, 0.0, True), (0.2, 1, 0.0, True)],
    }
}
T
```

## OUTPUT:
![Screenshot 2024-02-23 100417](https://github.com/Anas536/mdp-representation/assets/139841834/0adaf3eb-2353-4121-a694-125a7a1d8c66)


## RESULT:
Thus the given Markov Decision Process(MDP) problem is represented in the following ways.

Text representation, Graphical representation, Python - Dictonary representation.

