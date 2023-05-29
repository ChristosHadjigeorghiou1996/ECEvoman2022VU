# ECEvoman2022VU
Framework for python megaman based on evolutionary computing algorithms

## Variables
Given the instructions to generate plots, these variables can be accessed to fill the requirements:
* Size of individual members in the population
* Size of population
* Maximum generations
* Number of times to repeat run
* Stagnation parameter - if mean population / max member of population does not improve for x run then trigger stagnation flag
* Trim lower and upper bound parameters to 0 and 1 respectively
* Individual value of each member limited from -1 to 1 to introduce randomness in the nature of the algorithm
* Mutation probability of 0.25

## Parameters
* Random uniform population
* Mean and s.d. of given population
* Crossover two parents with aplha probability uniform
* K individuals for mating stochastically with sigma scaling (cdf based on fitness)
  * Min Max normalization
* CDF on worse individuals to prioritize replacing a bad individual but never guarantee
* Non-uniform random mutation

# Outputs
* Average fitness value per run, best individual per run test, s.d. per run
* Test best individual 5 times 
* Box plots and line plots as needed by instructions
