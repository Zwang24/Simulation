# Simulation
The code for simulation studies
In many epidemiological and disease prevention trials, the cost for getting covariate information from the full cohort is expensive. The case-cohort design is a study scheme proposed by Prentice back in 1986. The purpose of such design is to select a specific group of patients from the full cohort and get inferences from the selected sub-cohort instead of the full cohort. As you can see on the slide, the picture represents such a selection. That larger eclipse represents the full cohort. And we will be collecting Covariate information from the selected sub-cohort and for all cases outside of the sub-cohort . As Prentice pointed out, if the sub-cohort is selected wisely, the statistical power of the association between predictor of interest and endpoints will not be reduced, comparing to the power of the association obtained from analyzing the full cohort.

We want to implement this study scheme to HIV prevention settings, and utilize the case-cohort (two-phase) sampling schemes to study the predictors of interest and/or their interaction with the main intervention. However, the probability of exposure to HIV infected patients can vary across the population, and result in a large proportion of sampled participants never getting exposed. This may results in diluted estimates of the association for predictors of interest. In order to approach this question, we tried different sampling methods found in literature and ran simulation on the various methods.
