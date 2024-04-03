# Causality
## Dataset
### Description
This is synthetic data, to emulate the causal impact of multiple variables on income.
### Format
A data frame with 10000 observations, corresponding to 4857 treated and 5143 control subjects, and 10 variables. The treatment assignment indicator is the first variable of the data frame: treatment (1 = treated; 0 = control). The next 7 columns are the covariates:

- `treat`, treatment (1 = treated; 0 = control)
- `age`, measured in years
- `educ`, education measured in years
- `black`, indicating race (1 if black, 0 otherwise)
- `hispanic`, indicating race (1 if Hispanic, 0 otherwise)
- `married`, indicating marital status (1 if married, 0 otherwise)
- `nodegr,` indicating high school diploma (1 if no degree, 0 otherwise)
- `re19`, real earnings in 2019
- `re20`, real earnings in 2020
- `re22`, real earnings in 2022

In this data, "treatment" means participation in a national employment program to help disadvantaged individuals to move into the labour market.

### Why this data?
The data dataset is of significant interest from a causal point of view as it provides a valuable resource for studying the effectiveness of the program, which was designed to assist disadvantaged individuals in transitioning into the labor market.

The dataset's primary focus is on assessing the causal impact of participation in the program on various outcomes, particularly real earnings in 2022 (re22), by comparing individuals who received the treatment (participated in the program) to those who did not (the control group).

This dataset allows researchers to investigate whether the program had a statistically significant and meaningful effect on participants' earnings, taking into account various covariates such as age, education, race, marital status, and more.

### Source
The code to generate that data is available under `data_generation.py`
