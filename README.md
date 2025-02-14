## *Evaluating mark-resight survey design performance using simulation: a case study of endangered Steller sea lions* 

#### Amanda J. Warlick, Brian S. Fadely, Peter Mahoney, Sharon R. Melin, Tom Gelatt, Kim Raum-Suryan, Sarah J. Converse

##### Please contact Amanda Warlick at amanda.warlick@noaa.gov for questions about the code or data.

##### Secondary contact: Sarah Converse (sconver@uw.edu)

Published in *Ecosphere*.

________________________________________________________________________________

## Abstract

Effective monitoring is fundamental to estimating wildlife population parameters with a level of accuracy and precision that is adequate to inform management decisions. However, managers must also balance the trade-offs between the costs of monitoring and the resulting data quality in order to identify cost-effective monitoring survey designs. As such, evaluating the expected performance of monitoring surveys relative to monitoring objectives prior to survey implementation is critical. In this study, we present a simulation framework for examining the accuracy and precision of age-specific survival estimates and the probability of detecting a change in survival within the context of mark-resight monitoring programs. We consider 90 survey designs that vary across a range of attributes, including marked cohort size, marking frequency, study duration, and resight probability (*i.e.*, detection of marked individuals, which is typically positively correlated with survey effort). We apply this approach to the design of a cost-effective monitoring program for Steller sea lions (*Eumetopias jubatus*), which is complicated by heterogeneity in rookery (mating/birthing site) accessibility, rookery population sizes, and abundance trends across the species’ range. To identify cost-effective survey designs in the absence of actual survey costs, we also evaluated survey design performance with respect to a relative-costs schema. Our results highlight a variety of survey designs that reliably meet pre-defined precision targets, with precision and accuracy more strongly affected by marked cohort size, marking frequency, and study duration than resight probability. We found that historical mark-resight survey effort for Steller sea lions has been sufficient to reliably achieve precision targets for younger age class survival probabilities only for rookeries where abundance has been stable or increasing. In contrast, the probability of achieving survival estimates with target levels of precision at rookeries where abundance has been declining is low (< 25%) due to smaller marked cohort sizes, less frequent marking at remote sites, and fewer years of available data. Our results indicate that the precision of survival estimates for subpopulations of conservation concern can be improved by longer-term monitoring, though the constraints of monitoring small populations may limit the ability of biologists to detect changes in population dynamics on management-relevant time horizons. In our evaluation of cost-effectiveness, we identified consistently dominated survey designs, which are alternatives that are both more expensive and perform more poorly relative to monitoring objectives. Our survey design evaluation framework can be applied in a variety of contexts to assist natural resource managers in developing cost-effective monitoring programs. 

### Table of Contents 

#### [Scripts](./scripts)

- SSL_FutureProof_sim.Rmd includes simulation and estimation functions, code to run simulations and model fitting in nimble, and code to generate model performance metrics. 

Code to generate figures is available upon request but generally not extensively included here. 
 
#### [Data](./Data) 

This was primarily a simulation-based study. Contact the first author for code and data that were used to produce empirical estimates that guided data generation for the simulations. 

#### [Results](./results)

Results files can be obtained by contacting the first author.

### Required Packages and Versions Used 

Hmisc_4.5-0       
ggstance_0.3.5   
reshape2_1.4.4    
truncnorm_1.0-8   
DescTools_0.99.43 c
cowplot_1.1.1     
demogR_0.6.0     
gtools_3.9.2
knitr_1.31        
stringr_1.4.0    
purrr_0.3.4       
ggplot2_3.3.6     
tidyverse_1.3.1   
dplyr_1.0.5      
readr_2.0.1       
here_1.0.1        
tidyr_1.1.3       
lubridate_1.7.10 
latex2exp_0.9.5

### Details of Article 

Warlick, AJ, Fadely, BS, Mahoney, P, Melin, SR, Gelatt, T, Raum-Suryan, K, Converse, SJ. 2025. Evaluating mark-resight survey design performance using simulation: a case study of endangered Steller sea lions. *Ecosphere*

### How to Use this Repository 

The SSL_FutureProof_sim.Rmd file includes code chunks that outline functions used to designate initial values and known latent state information, nimble functions used to fit the model, model text, transition matrices and descriptions of the model parameters and simulation scenarios, and code used to run the model in parallel using nimble. Simulations were saved in batches due to computing resources.

Contact the first author for (1) data processing and mark-resight model code used to produce empirical estimates (that guided data generation for the simulation); and (2) code used to generate figures and summary statistics found in the manuscript.




