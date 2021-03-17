# basic-DS-case-study

This is a case study that involves some applications of ML models to a synthetic generated data.

Let's imagine we have a following features:

1. Age ~ Gamma(ɑ = 8, θ = 4)
2. Sex ~ Bernoulli(p = 0.4)
3. Purchase ~ Unif(ɑ = 500, β = 550) − 10 * Age * Unif(ɑ =− 2, β = 0.01)
4. Output ~ Bernoulli(p = 0.3 * Sex + (0.2 if Age > 30 else 0.4) + (0.3 if Purchase > 100 else 0))

The idea is to create a Model to predict the Output variable.

As seen above, this is quite a generic task, so I will try applying some of the ML models explaining why some decisions are made and comment the results. 

Enjoy! :) 