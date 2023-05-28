# Applications_of_Monte_Carlo_Simulation
Using Monte Carlo simulation with parallel computation techniques to solve two problems

## Problem A

Consider the following independent random variables:

$X∼N(μ=4,σ^2=10)$

$Y∼U(a=2,b=8)$

* Compute the probability that $X>Y$, i.e. $Pr(X>Y)$.

* Use bootstrapping to derive the sampling distribution for the estimate of $Pr(X>Y)$.

* Show how the sample variance of this sampling distribution changes as a function of the number of Monte Carlo simulations.

## Problem B

Consider the following football tournament format: a team keeps playing until they accrue 7 wins or 3 losses (whichever comes first - no draws allowed). Assume a fixed win rate $p∈[0,1]$ across all rounds (they are paired at random).

* Plot how the total number of matches played (i.e. wins + losses) varies as a function of $p$.

* Comment on the observed win rate relative to the assumed win rate p (i.e. if a team obtains 2 wins - 3 losses, the maximum likelihood point estimate for their win rate is 40%). Specifically, focus on the effect driven by the format of this tournament.
