# Agent-based SLIR Modelling of Powdery Mildew Infection Spread in Grapevines

![state_machine](/resources/state_machine.png)

This notebook presents an agent-based model in combination with a SIR-like compartmental model of powdery mildew infection spread among grapevines in a spatial grid.

This is a study extending on [a simple exploration done by Paul Petersik](https://medium.com/dev-genius/a-simple-cellular-automaton-of-plant-epidemics-in-julia-29ac62d87516), with added details on consideration of infection and recovery transition and different aspects reflecting spatial heterogeneity displayed in the process of fungal infection spread.

Modelling and visualisation is done in python with [AgentPy](https://agentpy.readthedocs.io/en/latest/index.html).