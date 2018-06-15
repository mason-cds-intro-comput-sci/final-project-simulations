Final Project — Comparative Discussion of Simulations
=====================================================
Due: June 22, 2018 @ 10:30am

Guidelines
----------

**Purpose** — The field of computational and data sciences extends beyond the topics focused on in this course. From the CDS-101 perspective, we've used the terms **model** and **simulation** as shorthand for *data-driven* models and simulations. Yet, there is an alternative approach to model and simulation building that works in the opposite direction and is an indispensable tool in the natural sciences, engineering, and computational social sciences. This class of models and simulations *generate* predictions and data without using an underlying dataset as input. To distinguish these from their *data-driven* counterparts, we will refer to them as follows:

-   A *microscopic* or *mechanism-driven* model or simulation is based on the known laws of nature. An example is deriving equations of motion for the planets in our solar system using Newton's law of universal gravitation.

After building this kind of model or simulation, the researcher will scan the model's parameter space and look for trends in the predictions and outputs, which are then compared against experimental data (if available). If the model or simulation generates predictions or outputs that accord with the experimental data, then the proposed mechanism can be regarded as a plausible explanation for observed trends. However, if the predictions or outputs fail to agree with the experimental data, then the model or simulation is falsified and the proposed mechanism is rejected.

**For your final project** — You will visit the following two webpages containing short summaries of two simulations that share a common lineage:

-   [Ising Model](https://jkglasbrenner.github.io/ising-model-js/) (<https://jkglasbrenner.github.io/ising-model-js/>)

-   [Schelling's Model of Segregation](https://jkglasbrenner.github.io/schelling-model-js/) (<https://jkglasbrenner.github.io/schelling-model-js/>)

Each page also contains the simulation itself implemented in Javascript, which runs inside the web browser. The simulations are visual and interactive, allowing you to change a small set of parameters using a simple dashboard. After becoming familiar with the different simulations and developing a basic intuition for how each one behaves, you will then compare and contrast them in a short write-up in the RMarkdown file [`simulations.Rmd`](simulations.Rmd). Your comparative discussion must be at least 2 paragraphs in length (a minimum of one paragraph per simulation) and include the following:

-   At least three ways in which the simulations are similar to one another

-   For each simulation, at least one way it is *different* from the other one

-   Pick one of the simulations and suggest a feature or rule that you could add to it that would change its outputs and predictions. You only need to do this using plain language, you are not expected to write any code for this. Be sure to hypothesize what you think the changes will do and what they might mean. For example, how do you anticipate that your proposed change will simulate different physical mechanisms or human behavior?
