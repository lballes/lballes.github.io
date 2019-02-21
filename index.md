# Lukas Balles

I'm a doctoral student in machine learning at the Max Planck Institute for Intelligent Systems and the University of Tuebingen.

## News

- I will be interning at Google Brain Montreal from March to June 2019.


## Research

My research centers on optimization methods for machine learning with a focus on deep learning. Optimization algorithms are the workhorse of contemporary machine learning; it's where the numbers are crunched! Intriguingly, numerical optimizers themselves are compact little "learning machines": they make decisions (where to evaluate next, how many and which data points to use) based on observations (stochastic evaluations of function values and gradients). My goal is to design smarter optimizers!

Currently, my work centers around utilizing (estimates of) the stochastic gradient variance to make the optimizer aware of the stochasticity of the evaluations it receives. I believe that this can help improve various aspects of stochastic optimization algorithms. For example, gradient variance estimates can be used to adaptively choose batch sizes when performing stochastic gradient descent [(Balles et al., 2017)](https://arxiv.org/abs/1612.05086). Variance estimates can also be used to manipulate the search direction itself by "damping" coordinate directions with low signal-to-noise ratio [(Balles and Hennig, 2018)](https://arxiv.org/abs/1705.07774).

Check out my [Google Scholar page](https://scholar.google.de/citations?user=2lq9JQIAAAAJ&hl=de) for a list of publications.

## Get in touch

You can e-mail me at ``lukas dot balles at tuebingen dot mpg dot de``.