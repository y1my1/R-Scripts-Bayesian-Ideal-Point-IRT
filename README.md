# Bayesian Ideal Point IRT Models
Some IRT ideal point models that may be useful for some folks. They are coded to be run with Stan. `JAGS` has often been used to run these types of models but it can take a very long time. The reason for this is that `JAGS` is unable to build a Directed Acyclic Graph from the unobserved regressor in:  
{% raw %}
  $$y_{ij} = \beta_j\boldsymbol{x_i} - \alpha_j.$$ 
{% endraw %} 
(see [here](https://sourceforge.net/p/mcmc-jags/discussion/610037/thread/5c9e9026/ ))


