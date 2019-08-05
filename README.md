# Modelling-action-potentials-Hodgkin-and-Huxley

This provides required codes (MATLAB) to simulate the concepts of the cable model and the Hodgkin and Huxley model which represent the behaviour
of the ionic potentials across cell membrances.
Also, this repository consist of lecture notes to understand relevant concepts before the simulation.

### Cable model
The aim of this simulation is to explore some of the time independent electrical properties of single branched cables. 
Branched cables are an important means of modelling the passive electrical properties of axonal and dendritic trees. 
Consideration will be restricted to trees exhibiting only one order of branching, however the principles elaborated upon here are easily 
extended to higher order trees.

Relevant files:
- Cable model.pdf
- Assignment - cable model.pdf
- cable.m

### Hodgkin and Huxley model
The aim of ths simulation is to investigate some of the properties of the Hodgkin-Huxley equations. Experimentally in a space-clamped axon of 
finite length the regenerative electrical activity in response to some supra-threshold stimulus is called a membrane action potential as the 
whole axonal membrane simultaneously participates in the events underlying the action potential. Without the space clamp the action potential 
would propagate with finite velocity away from the site of supra-threshold stimulus application and would thus constitute a propagating action 
potential. This latter event is the one that would occur physiologically. Many of the properties of the propagating action potential are similar, 
if not identical, to the membrane action potential. The following four features of the Hodgkin-Huxley equations, all of which are observed 
physiologically, will be simulated here.
- Threshold
- Refractoriness - absolute and relative
- Repetitive activity
- Temperature dependence

Relevant files:
- Hodgkin and Huxley model.pdf
Assignment - Hodgkin and Huxley.pdf
- hh.m
- hhconst.m
- hhmplot.m
- hhparams.m
- hhrate.m
- hhsplot.m
- hode.m
