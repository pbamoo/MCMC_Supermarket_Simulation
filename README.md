# Week 8/12 Markov_Simulation Project
   
### Background problem / Goal:
In this project, the goal is to write a program that simulates customer behaviour in a supermarket using Markov-Chain Monte Carlo methods and visualize it on a map.

### Tools/Libraries Used: 
Python, Pandas, Numpy, Matplotlib, Plotly, Scikit-learn, opencv

### Workflow:
1. [Exploratory data analysis](https://github.com/pbamoo/MCMC_Supermarket_Simulation/blob/main/Markov_Data_Analysis.ipynb)
2. [Simulation of new customers in the supermarket](https://github.com/pbamoo/MCMC_Supermarket_Simulation/blob/main/Monte-Carlo-Markov-Chain.ipynb)
3. [Animation](https://github.com/pbamoo/MCMC_Supermarket_Simulation/blob/main/animation.py)

### Next steps for the customer simulation

1. Make the customer move left, right and down
2. Define the sections (Start with one point per section, eg. fruits is x=15, y=5)
3. Give the customer an attribute "state" with the possible values [fruits, spices, dairy, drinks]
4. Implement the method Customer.transition() for the customer so she can transition between states; base the probabilites on the transition probabilities matrix
5. Implement a rule by which the customer moves to the new state; eg. always down, then left or right, then up
6. Try with two customers at the same time
