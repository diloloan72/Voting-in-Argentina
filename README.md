# Impact of voting technologies on voting experience in Argentina

## Executive Summary 
Alvarez, Levin, Pomares, and Leiras’s paper “Voting Made Safe and Easy: The Impact of e-voting on Citizen Perceptions” studied the perceptions and evaluations of voters in Salta, Argentina on e-voting compared to traditional voting. Using Propensity Score Matching, the study found that Argentine voters supported replacing traditional voting technologies with e-voting as they perceived the new technology as easier to use and more likely to record votes as intended. However, there remained concerns about ballot secrecy with e-voting.  In order to extend the results of the study, our group used the Genetic Matching method, and we obtained a higher degree of balance between treatment and control groups on almost all the covariates. The Genetic Matching results are consistent with the Alvarez et al. results that voters in Salta, Argentina rated e-voting more favorably than traditional voting in terms of the overall experience, ease of use and speed, but still doubted the ballot secrecy. This additional finding suggests that the Government of Argentina should take actions to improve voters’ confidence in the ballot secrecy of e-voting if they decide to fully replace the traditional voting with this new technology.

## Implementation of Genetic Matching 
Can be found in the "Final Paper" file 

## Conclusion 
Compared to propensity score, genetic matching has two main advantages - no dropped treated units and better balance between treated and control units. Therefore, this method helps generate more statistically significant and robust results. In this case, the outcome gathered from genetic matching consolidates the impact of e-voting versus traditional voting on people’s confidence and perception about their voting experience. 

By using a more rigorous methodology (genetic matching), our results suggest that e-voting generally has a positive impact on people’s voting experience compared to traditional voting. Additionally, the outcome further supports the notion that e-voting technology positively affects the perception of the cleanliness of elections, but reduces the confidence in the ballot secrecy in Argentina. A sensitivity analysis can be implemented to account for potential sources of bias and unobserved attributes from voters. Insights gathered from this activity further inform the robustness of the obtained results in the presence of unobserved covariates. As the study is implemented in Argentina, the Election Commission of this country can use the results as a scientific methodology to prove that actions should be enacted to boost people’s confidence in ballot secrecy.
