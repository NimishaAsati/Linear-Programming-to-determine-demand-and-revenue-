# Linear-Programming-to-determine-demand-and-revenue-
LP based approximations to solve capacity allocation problem

Idea is to replace future random demand by deterministic counterparts and solve the corresponding capacity allocation
problem. The resulting problem can be solved as a linear program.

1) Maximize revenue
2) Meet resource capacity constraints and demand constraints
3) Find the shadow price (The optimal prices of the resources are called the shadow prices of the resources. 
    They capture how valuable the resource is to you.)

#### To execute:
Download the ipynb file and execute by changing the values for capacity and demand.

### For Deterministic Linear Programming Model:
The code solves the problem of seat allocation problem for an airline.
number of products = 3

number of resources = 2

capacity constraint --> total seats on flight = 50

demand constraint --> 40,30,20

b - the fares (p1=200, p2=160, p3=300)

c - constraints (capacity and demand)

A - different combinations of flight

### For Randomized Linear Programming Model:
Demand function is known and resource state is known.

Probability with which the request for product(the seat in airplane) arrives is lbda

T - time horizon


