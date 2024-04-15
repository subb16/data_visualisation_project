<h1 align = "center">Prisoners Information Analysis</h1>
<p align = "center"><i>Data Visualization Report by Subhash Patel (210150017)</i></p>

# Motivation

Data visualization serves as a powerful lens through which we can gain deeper insights into the complex dynamics of environmental phenomena. 

Analysing Prisoners Information for the **Crime** theme gives us many insights like:

1. **Insight into Criminal Justice System:** Analyzing prisoner information provides valuable insights into the functioning of the criminal justice system. It allows us to understand various aspects such as incarceration rates, demographics of the prison population, length of sentences, and recidivism rates. By delving into this data, we gain a deeper understanding of how the justice system operates and its impact on individuals and society.

2. **Public Safety and Rehabilitation:** Understanding the characteristics of prisoners can aid in enhancing public safety measures and rehabilitation programs. By examining factors such as types of offenses committed, demographics of inmates, and educational and vocational backgrounds, we can identify patterns and trends that inform policymaking and intervention strategies aimed at reducing crime rates and promoting successful reintegration into society.

**Now, let's delve into the data we've collected and explore various aspects of prisoner information through data visualization.**

The sections are as follows:
1. Dataset
2. Educational Background of Criminals
3. Domicile Information
4. Age Groups
5. Types of Offences
6. Religion 
7. Gender
8. Conclusion

# Dataset
This dataset contains information about the prisoners in India in 2020. A criminal is a person who is guilty of a crime, notably breaking the law. A prisoner is a person incarcerated in a prison, while on trial or serving a sentence

## Data Description

* It has 87 columns and 39 rows. The columns include the state or union territory, the educational standard, the domicile, the religion, the gender, the age group, the type of prison, and the type of offense.
* The rows include the total for each state or union territory and the total for all of India.
* The dataset is based on the Prison Statistics India (PSI) report published by the National Crime Records Bureau (NCRB).
* The dataset can be used for analysis and visualization of the prisoner's statistics


# Education Analysis

Analyzing the educational background of prisoners reveals intriguing insights into the correlation between education and criminal behavior. Remarkably, the data showcases a significant proportion, approximately 30%, of prisoners classified as illiterate, with an additional 40% having dropped out before completing high school. This observation suggests a potential association between lower levels of education and involvement in criminal activities. While correlation does not imply causation, the prevalence of individuals with limited educational attainment within the prison population underscores the importance of addressing educational disparities as a preventive measure against criminal behavior. Moreover, it emphasizes the potential role of education in fostering social inclusion, economic opportunities, and pathways away from crime. 
Further research and targeted interventions aimed at improving access to education and addressing educational inequalities could potentially contribute to reducing recidivism rates and promoting rehabilitation among offenders.

<img src = "plots/education.png" height = 400 width = 1000>



# Domicile Information

* The analysis of domicile information among prisoners provides valuable insights into migration patterns and potential factors influencing criminal behavior. The observed ratio of prisoners from the same state compared to those from other states, with an average value of around 15 and ranging from 3 to 200, offers several noteworthy conclusions.

* Firstly, a higher ratio of prisoners originating from the same state suggests a potential correlation between local socioeconomic factors and crime rates. Areas with higher ratios may indicate underlying social issues such as poverty, unemployment, or lack of educational opportunities, which could contribute to criminal behavior within the community.

<img src = "plots/top10dom.png" height = 400 width = 500> <img src = "plots/bot10dom.png" height = 400 width = 500> 

* Conversely, states with lower ratios may suggest either stricter law enforcement measures or lower crime rates, leading to a lower number of local offenders in the prison population. Additionally, they may indicate higher rates of migration or mobility, where individuals move to other states for employment, education, or other reasons, potentially leading to a more diverse prison population.


* Overall, the analysis of domicile information highlights the complex interplay of socioeconomic, cultural, and legal factors influencing crime rates and underscores the importance of targeted interventions tailored to address the specific needs of different regions to effectively combat crime and promote community safety and well-being.
