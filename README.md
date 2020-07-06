# factors correlated to COVID-19 using Regression models

The rapid outbreak of the new Coronavirus (COVID-19) pandemic and the spread of the virus worldwide have prompted various investigations about the impact of several factors on the rate of development of this epidemic. Studies have called attention to understand and analyze various parameters that may have influenced the spread of the virus, and in particular, the impact of temperature, humidity, median age, population density which has been also emphasized throughout this paper. This paper presents the underlying factors to evaluate on the various notations of age to extract association with mortality rate and locate correlation between the other variables. Though one can identify several factors, the research has been focused on age, age groups, underlying health conditions, median age and population density as factors and how it could impact mortality once a person gets infected with COVID-19. The methodology used to define the association includes statistical analysis to identify the correlation and dependencies of COVID-19. Several regression models such as Pearson, Kendall, Spearman correlation have been used along with Polycor regression between categorical variables.


Currently, the dataset is obtained from the Centre for Disease Control and World Health Organization for every individual country. The datasets from worldometer and Kaggle have also been retrieved, as they have been integrated from the CDC and WHO and have concise information regarding COVID-19 variables. As the datasets are formulated from different sources, it is required for the data to be maintained such that there would be no errors during the analysis. Hence, several data cleaning techniques have been employed as required for the acquired dataset.
# Data Pre-processing
Data preprocessing is the process of cleaning and preparing the text for further analysis. Online datasets, usually, may contain lots of noise and uninformative parts that could hinder the output during the analysis. In order to keep all the datasets in line for statistical analysis, following data cleaning methods have been employed to get the multiple datasets merged wherever possible to improve the analysis. This would essentially decrease the noise in the datasets and would allow us to obtain more precise statistical values.
# Lowercasing
The first pre-processing step which will transform our categorical datasets into lower case. This avoids having multiple copies of the same words. For example, while analyzing based on countries, ‘United States’ and ‘united states’ will be taken as different words.
# Filling missing values
The next pre-processing step is to identify the empty or n/a values in the dataset and refill them with 0 value. In our case, entire missing values are of numeric data types and hence the appropriate comment is to fill the gaps with 0 instead of having them blank.
# Removing unnecessary columns
This step would let us remove unusable columns and rows which will not be used from the dataset source. This will help us having the data with right columns and rows and avoid ambiguous content in the dataset. For example, dropping the ‘wind speed’ as the variable is not used in any of the correlation or statistics analysis.

# factors identified
As mentioned before, below are the factors that correlation with mortality rate and its correlation and different forms of the data have been associated throughout the paper.

● Age
Statistical analysis done thus far, have shown an increased death rate amongst individuals belonging to older age groups across countries. It has been seen that older individuals are more susceptible to contracting the COVID-19 infection due their lessened immune response which may also mean they are already dealing with other health conditions apart from the infection.

● Underlying Health Conditions
Individuals who have existing health conditions are likely to contract COVID-19 more easily because their immune systems are already weakened by fighting against other diseases in the body. The combination of a health condition with the COVID-19 infection can be very fatal in individuals as it becomes very unlikely for them to defend against both simultaneously.

● Population Density
At the beginning of the pandemic, there have been reported incidents where densely populated areas have seen a rise in the number of cases and deaths due to COVID-19. Which is why implementations such as travel restrictions, and social distancing have been made, since with high population density the greater proximity and rate of infection amongst the population.

● Temperature
The SARS-Cov-2 has been seen to act like a seasonal viral infection, such as the flu. Where colder temperatures produce and uptick in the number of cases and warmer temperatures tend to produce a decrease in the number of cases. Also, during the colder weather, more individuals tend to experience illnesses such as the common cold where runny noses and coughing is present, which heightens the rate of transmission.


To perform association analysis of each of the factors, countries have been filtered from the total dataset according to the most recent date of data available and total deaths due to COVID-19 to be greater than 100. These selected countries have provided Pearson correlations values of 0.946516517 for total cases of COVID-19 vs. total deaths of COVID-19, 0.018565085 for mortality rate of COVID-19 vs. population density, and 0.311443189 for mortality rate vs. median age in the country. Therefore, analysis of these particular countries will allow for better broad-spectrum conclusions to be made on associations between COVID-19 and each factor and have been chosen for the core correlation models





