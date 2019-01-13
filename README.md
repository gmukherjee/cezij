What is CEZIJ?
======
CEZIJ [1] is a novel framework for parameter estimation in joint models with multiple longitudinal outcomes along with a time-to-event analysis. Longitudinal data from modern datasets usually exhibit a large set of potential predictors and choosing the relevant set of predictors is highly desirable for various purposes including improved predictability. To achieve this goal, CEZIJ conducts simultaneous selection of fixed and random effects in high-dimensional penalized generalized linear mixed models and maintains the hierarchical congruity of the fixed and random effects, thus producing models with interpretable composite effects. It not only accommodates extreme zero-inflation in the responses in a joint model setting but also incorporates domain-specific, convex structural constraints on the model parameters. For analyzing such large-scale datasets, variable selection and estimation is conducted via a distributed computing based split-and-conquer approach [2] that massively increases scalability.

How to use this repository?
=========
This repository holds the MATLAB toolbox `cezij.mltbx` that provides an implementation of the CEZIJ procedure developed in [1]. To install this toolbox, simply download `cezij.mltbx` in your computer and double click to install it. For a successful installation, please make sure that the following system requirements are met.

System Requirements
===========


Documentation
==========




References
=======
[1.] Banerjee, T., Mukherjee, G., Dutta, S., and Ghosh, P. (2019). A Large-scale Constrained Joint Modeling Approach For Predicting User Activity, Engagement And Churn With Application To Freemium Mobile Games. _(under review)_     

[2.] [Chen, X. and Xie, M.-g. (2014). A split-and-conquer approach for analysis of extraordinarily large data.
Statistica Sinica, pages 1655-1684.](http://www.stat.rutgers.edu/home/mxie/RCPapers/split_and_conquer_rev1_final.pdf)
