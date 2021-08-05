### Amazing Algorithms for Solving Problems in Software
* References
 * [https://amazingalgorithms.azurewebsites.net](https://amazingalgorithms.azurewebsites.net)
* Firefly optimization
 * "representation of fireflies swarming"
 * Brighter: Better solution
  * Need estimate of range of values
 * Closer and Brighter: More attractive (similar to gravity)
 * Works better for linear problems
 * Danger: sparseness
  * Can suffer from the "curse of dimensionality"
* Amoeba optimization
 * Key is how the amoeba moves through the solution space
 * Other values for n (sizes of amoeba) can be used
 * Danger: Sparseness
* Linear regression model
 * Given (X) time, predict Y (location)
  * Y = mX + b
 * Find the best values for m and b
  * Minimize total error
* Bee Colony Optimization
 * Path optimization
 * Types of Bees
  * Active workers
   * Forage on their known path and on a neighboring path
  * Scouts
   * Forage on a random path
  * Inactive workers
   * Wait for information from other bees
 * Multiple search types
  * Active workers perform neighborhood search
  * Scout perform random search
 * Waggle dance
  * Best known path propagates for other foragers
* Ant colony optimization
 * Pheromones are the key
  * Greater usage -> more pheromones
  * Shorter path length -> more pheromones remain
  * More pheromones -> higher probability of usage
 * Snowball effect
  * Longer runs = more pheromone on short paths
  * More pheromones -> higher probability of usage
 * Tweaks
  * Number of ants
  * Pheromones to dispense
  * Pheromone dissipation rate
 * Less sensitive to scale
* More bio-inspired
 * Roach infestation optimization
 * Particle swarm optimization
 * Multi-swarm (birds) optimization
 * Bacterial foraging optimization
 * Genetic algorithms
