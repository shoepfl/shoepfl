---
title: "FAIR Bayesian Optimal Experimental Design (BOED) in Systems Biology"
date: 2023-10-04
pubtype: "Poster"
featured: true
description: "This poster looked at Bayesian Optimal Experimental Design of a small michaelis menten system."
tags: ["FAIR","Systems-Biology","BOED","Bayes"]
image: "/img/OED_aims.png"
link: ""
fact: "Aiming at optimal experimental designs can save cost and money."
weight: 400
sitemap:
  priority : 0.3
---

Acquisition of experimental data in Systems Biology is time-consuming and costly. On the one hand, this is due to expensive chemicals, such as antibodies, on the other hand, due to the need for extensive preparation, incubation, and purification procedures of experiments. Finding the best experiment design helps to get the maximum possible information out of limited experimental data, thereby minimizing cost and time. Here, we present first results of Bayesian Optimal Experiment Design (BOED) in a Findable, Accessible, Interoperable, and Reusable (FAIR) fashion. In particular, our approach makes use of the Systems Biology Markup Language (SBML), the de facto modeling standard in Systems Biology, and is set up in an easily applicable and reusable way. Models, data, and code will be stored on Fairdomhub.

BOED was applied to Michaelis-Menten enzyme kinetics with different initial substrate concentrations $c_{init}$ (Figure~\ref{fig:BOED}). In the first attempt, three different experimental designs were investigated with artificial data. The first design includes three measurements with initial substrate concentrations larger than $K_M$, the second design includes three measurements with initial substrate concentrations lower than $K_M$, and the third design includes only two measurements but with lower and higher initial substrate concentrations than $K_M$. Our results show that in the first design only $k_{kat}$ but not $K_M$ can be identified. In the second design, $k_{kat}$ and $K_M$ are correlated. Only in the third design with only two experiments, both parameters can be identified and the IG was highest. These results demonstrate that proper planning of the experimental design can improve the estimation of the parameters and at the same time reduce the number of experiments needed. Now, the next step is to predict the optimal starting concentrations via BOED.
