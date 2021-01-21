defSim, examples
================

Example scripts for defSim || Discrete Event Framework for Social Influence Models 

- [defSim git repository](https://github.com/defSim/defSim)

New to defSim? [Learn how to use defSim in this quick introduction](https://defsim.github.io/defSim/Introduction_to_defSim.html)

For a description of all of defSim's functions, see the [documentation](https://defsim.github.io/defSim/)

As defSim is a framework for social influence models, there are many different ways in which the package or it’s single components can be used. A way to think about the different uses of defSim is by organizing them by their degree of modularity. That is, the degree to which the users separates, reorganizes, or creates elements for their own simulation run. Low degree variations are typically well suited for teaching, illustrating, or replicating. Variations of implementations in the mid and high range of modularity may be more suited to researchers implementing novel ideas.

This repository introduces examples for each level of modularity:
-----------------

- `ExperimentClass.ipynb` shows an 'out-of-the-box' use of defSim. This example introduces the use of the main 'Experiment' function, used to run many replications of simulation runs.
- `SimilarityAdoption.ipynb` is another low modularity example which showcases the *SimilarityAdoption* influence function included in Axelrod's seminal 1997 JCR paper. 
- `NewAttributeInitializer.ipynb` illustrates how you could program your own attribute initializer, following the defSim framework. This a more modular use-case of defSim.
- `ModularNetworkModification.ipynb` showcases a highly modular use of defSim by splitting initialization and simulation to allow for network manipulation.
