# Network-dynamics-and-learning
##### by Micol Rosini

- [Homework 1](#homework-1)
- [Homework 2](#homework-2)
- [Homework 3](#homework-3)

This repository contains the code about the course *Network dynamics and learning* 2021/2022 class of Politecnico of Turin.
In this project, the interplay between network dynamics, epidemics, game theory, and flow in complex systems have been explored. The project will use a combination of theoretical analysis, simulation, and data analysis to understand how these different factors interact with each other and shape the behavior of complex systems.




## Homework 1

In this project, we aim to investigate the dynamics of flow and capacity in a graph network. Specifically, we will analyze how the flow of resources or information through a network is affected by the capacities of the edges or nodes, and how changes in these capacities can impact the overall behavior of the network.

One of the key components of the project will be to develop algorithms and models for analyzing network dynamics, and for predicting how the flow of resources or information through a network will change under different conditions. We will also explore how to optimize flow and capacity in a network, with the goal of improving overall performance and efficiency.

![image](ND%20images/p1/graph1.png)

In addition, we will investigate different types of graphs, and their impact on flow and capacity. By analyzing the structural properties of these networks, we can gain insights into how they affect the dynamics of flow and capacity, and identify potential areas for improvement.

Another important focus of the project will be to explore applications of network flow and capacity in various domains, such as transportation, communication, or logistics. By analyzing real-world systems and datasets, we can gain a deeper understanding of the challenges and opportunities associated with flow and capacity in networks, and identify potential solutions or innovations.

Overall, this project aims to provide a comprehensive and integrated view of network dynamics, flow, and capacity, and to explore the potential applications of these concepts in various domains. By combining insights from graph theory, optimization, and data analysis, we hope to develop new tools and techniques for understanding and optimizing complex network systems.

![image](ND%20images/p1/graph11.png)

![image](ND%20images/p1/graph12.png)

This project also find the perfect matching on a graph. This task involves developing an algorithm to determine the optimal pairing of nodes in a graph such that every node is paired with exactly one other node.

The problem of finding a perfect matching in a graph is a fundamental problem in graph theory and has numerous real-world applications, such as in matching patients to donors in kidney exchange programs, assigning students to schools, and pairing job seekers with job openings.

The algorithm would take as input a graph and output a set of node pairs that form a perfect matching. The algorithm would need to consider all possible pairings of nodes in the graph and evaluate each pairing based on a set of criteria such as edge weights or node attributes.


![image](ND%20images/p2/graph6.png)

![image](ND%20images/p2/graph7.png)





## Homework 2

The aim of this project is to explore the use of Markov chains and French De Groot dynamics in the context of network graphs. The network dynamics will be analyzed using the fundamental concepts of Markov chains, including transition matrices, stationary distributions, and random walks.

![image](ND%20images/p2/graph1-4.png)

![image](ND%20images/p2/graph3.png)

![image](ND%20images/p2/graph2-2.png)




Next, the French De Groot dynamic will be explored, which is a model of opinion dynamics in a network. The French De Groot dynamic simulates the evolution of opinions among a group of individuals who interact with each other and influence each other's beliefs over time. We will investigate how this dynamic can be used to model the spread of opinions in a network and how different parameters, such as the strength of social influence and the degree of stubbornness of individuals, affect the dynamics of the system.

![image](ND%20images/p2/graph11-2.png)

In this project, we will implement the Markov chain and French De Groot dynamic models in Python using the NumPy and NetworkX libraries. We will also use the Matplotlib library to visualize the results of our simulations. Through this project, we aim to gain a deeper understanding of the dynamics of network systems and how these concepts can be applied to real-world problems, such as social influence and opinion dynamics.

![image](ND%20images/p2/graph14.png)
![image](ND%20images/p2/graph12-2.png)

## Homework 3

The project simulate the H1N1 influenza pandemic that occurred in Sweden in 2009. Two sub-sections explain the simulation of epidemics on a random graphs without and with vaccination, while the third section describes the task of estimating the social structure of the Swedish population and the disease-spread parameters during the pandemic. The simulation results show that the use of vaccines decreases the number of infected individuals, and the total number of infected is approximately half of the number of people infected during the pandemic in Sweden in 2009. 

![image](ND%20images/p3/graph4.png)

The optional part aims to simulate the spread of a pandemic through a population using a random graph and estimating the optimal parameter using simulated annealing.
The part will use a small world graph model of the population, where each node represents an individual and each edge represents a connection or interaction between individuals. The pandemic will be simulated by introducing an infectious agent to the population and allowing it to spread through the graph according to a set of rules that represent the transmission dynamics of the disease.
Simulated annealing will be used to estimate the optimal parameter values for the transmission dynamics of the disease. Simulated annealing is a probabilistic optimization technique that can be used to find the best set of parameters that minimizes an objective function. In this case, the objective function will be a measure of the spread of the disease through the population.

The project will involve implementing the simulation and optimization algorithms in a programming language, as well as visualizing the results of the simulation using graphs and other visualizations. The project will also involve analyzing the results of the simulation to gain insights into the spread of the disease and the effectiveness of different control measures.
Overall, this project has the potential to provide valuable insights into the spread of pandemics and the effectiveness of different interventions. It may also help inform public health policies and strategies for controlling and preventing the spread of infectious diseases.




![image](ND%20images/p3/graph18.png)

![image](ND%20images/p3/graph155.png)

This project explores also the graph coloring technique for distributed learning in potential games. Two practical applications of this technique are presented: one for a line graph and another for assigning WiFi-channels to routers. In both applications, a set of possible states is defined and at each time instance, a node is chosen uniformly at random and updates its color based on a probability distribution. The probability distribution is defined based on a cost function and a potential function is used to measure the quality of the coloring. The learning dynamics is the same in both applications, and a Nash equilibrium is found using the algorithm presented. The project also explores the effect of different values of the parameter $\eta$ on the learning dynamics and the quality of the potential function. The results show that values of $\eta$ that increase with time lead to better potential functions, and that the fastest convergence is achieved for a quadratic increase in $\eta$.

![image](ND%20images/p3/graph2.png)

![image](ND%20images/p3/graph4-2.png)





