# Lukas Balles

I'm a doctoral student in machine learning at the [International Max Planck Research School for Intelligent Systems](https://imprs.is.mpg.de/), hosted by the Max Planck Institute for Intelligent Systems and the University of Tuebingen. I am supervised by [Prof. Philipp Hennig](https://uni-tuebingen.de/en/faculties/faculty-of-science/departments/computer-science/lehrstuehle/methods-of-machine-learning/content/philipp-hennig/).

## News

- I will be interning at Google Brain Montreal from March to June 2019.


## Research

I am primarily working on optimization methods for machine learning with a focus on deep learning. Optimization algorithms are the number crunching workhorse of contemporary machine learning! Intriguingly, numerical optimizers themselves can be seen as compact little "learning machines": they make decisions (where to evaluate next, how many and which data points to use) based on observations (stochastic evaluations of function values and gradients). My goal is to design smarter optimizers!

Currently, my research centers around utilizing (estimates of) the _stochastic gradient (co-)variance_ to make the optimizer aware of the stochasticity of the evaluations it receives. I believe that this can help improve various aspects of stochastic optimization algorithms. For example, gradient variance estimates can be used to adaptively choose batch sizes when performing stochastic gradient descent [(Balles et al., 2017)](https://arxiv.org/abs/1612.05086). Variance estimates can also be used to manipulate the update direction itself by "damping" directions with low signal-to-noise ratio [(Balles and Hennig, 2018)](https://arxiv.org/abs/1705.07774).

Check out my [Google Scholar page](https://scholar.google.de/citations?user=2lq9JQIAAAAJ&hl=de) for a list of publications.
For some projects, code can be found on my [GitHub page](https://github.com/lballes).

## Short Bio

Prior to joining the Max Planck Institute as a Ph.D. student, I studied Mathematics (B.Sc.) and Scientific Computing (M.Sc.) at Heidelberg University and spent some time as a visiting student at Tsinghua University in Beijing.
I did my Master's thesis research project at (what is now) the [Bosch Center for Artificial Intelligence](https://www.bosch-ai.com).
During my PhD, I interned at Google AI in Zurich.

## Get in Touch

E-mail: ``first-name dot last-name at tuebingen dot mpg dot de``.

Twitter: [@lukas_balles](https://twitter.com/lukas_balles)