# newton_based_extremum_seeking
Newton Based Extremum Seeking Algorithm for Online Optimization. This repository includes code from paper [A robustified Newton based Extremum Seeking for Engine Optimization](https://www.researchgate.net/publication/305034128_A_robustified_Newton_based_Extremum_Seeking_for_Engine_Optimization) and the corresponding masterthesis [Echtzeitoptimierung mit Extremum Seeking ](https://epub.jku.at/obvulihs/content/titleinfo/909220)

## Description
The algorithm is mainly based on the paper [Multivariable Newton-based extremum seeking](https://flyingv.ucsd.edu/papers/PDF/161.pdf) where the calculation of inverse Hessian by a Riccati Filter was introduced first. We extended the algorithm mainly by introducing regularization techniques to make it more robust in real world applications (noise and non definite Hessian matrix, e.g. occuring with non convex cost functions)

## Outlook
In 2019 a paper was presented [Newton-based extremum seeking: A second-order Lie bracket approximation approach](https://www.sciencedirect.com/science/article/abs/pii/S0005109819301700) claiming that their approach is *... less complex than the ones proposed in Ghaffari et al* (referring to the same paper as our approach is based on).

Implementation an comparison should be done in future.
