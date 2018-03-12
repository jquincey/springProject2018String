# Project Description 

This project is aimed at solving a simple one dimensional wave equation, which we are specifying here as a vibrating string fixed at both ends. We intend to simulate this system varying certain key parameters which influence the oscillations. 

# Scope and Complexity

**Description**

One of the most simple techniques to visualise a simulation which involves solving a PDE  with certain boundary conditions is
to save the string profile for certain time intervals and plot them against appropriate axes.One of the most fundamental 
conditions required to *initialise* a vibration, is to pluck it at some point which generates the wave. After this at every
time interval the old and new profiles of the string is updated through an iteration. The output we intend to achieve is to
visualise the wave pattern with varying frequencies and modes. 

**Requirements**

* Theoretical Skills 

A basic understanding of certain elementary topics in mechanics such as tension and displacements in elastic strings is
required. Additionally choice of material needed to run the computational simulation is needed. (For instance,if no boundary
conditions are specified on the ultimate strength of the material,the compiler will evaluate results which might not be
physically possible. The string can always snap off if the force magnitude is higher).Knowledge of Elliptic PDE's (and its 
solution interpretation) is an added bonus. 

* Computational skills

The program can be solved in any computational platform (such as MATLAB, Python(preferred), C++). Basic knowledge of 
iterators,pointers, arrays, vectors (in some languages), function (and function calling) is required to solve the problem.

* Team Interaction 

In class discussion and using social platforms such as Slack etc. 

**Possible Improvements**

*This section mainly talks about what we consider as out of scope for the project*

We are evaluating the problem assuming the wave to be at steady state and slowly progressing with time.An additional
manipulation could have been introducing a friction coefficient and calculating the time rate of decay of the wave.Another
interesting application could have been visualising the transient state of the wave profile and the time it takes to 
transform from a non periodic wave profile to a periodic one. 





