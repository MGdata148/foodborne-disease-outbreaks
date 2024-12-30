# Foodborne Disease Outbreaks

### Background
Foodborne diseases are a significant public health concern globally, causing widespread morbidity and mortality. These illnesses result from the consumption of contaminated food or beverages, harboring pathogenic microorganisms such as bacteria (e.g., Salmonella, E. coli), viruses (e.g., norovirus), parasites, or chemical agents (e.g., aflatoxin, dioxin). Outbreaks occur when multiple cases of illness are traced to a common food source, often highlighting vulnerabilities in food production, processing, or handling systems. In 2015, the World Health Organization (WHO) released its first estimates of the global burden of foodborne diseases. The report revealed that contaminated food causes 600 million illnesses, 420 000 deaths, and 33 million lost healthy years annually, affecting 1 in 10 people worldwide [Havelaar et al, 2015](https://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.1001923).

### Project aim
The objective of this project is to analyze patterns in foodborne disease outbreaks to enhance understanding of their etiologies and inform strategies for their prevention. 

### About dataset
The dataset `outbreaks` [(Foodborne Disease Outbreaks 1998-2015)](https://www.kaggle.com/datasets/cdc/foodborne-diseases) was obtained from [Kaggle](https://www.kaggle.com/) and provides data on foodborne disease outbreaks reported to CDC from 1998 to 2015.

#### The variables are as follows:
- `year` - the year of the outbreak
- `month` - the month of the outbreak (e.g., January, February)
- `state` - the U.S. state where the outbreak took place
- `location` - the special location where the food was contaminated
- `food` - a description of the contaminated food involved in the outbreak
- `ingredient` - the specific ingredient within the food responsible for pathogen contamination
- `species` - the species of the pathogen that caused the outbreak
- `serotype` - the serotype of the pathogen that caused the outbreak
- `status` - the confirmation status of the outbreak's etiology (e.g., Confirmed, Suspected)
- `ilnesses` - the total number of individuals infected during the outbreak
- `hospitalizations` - the number of individuals who required hospitalization as a result of the illness
- `fatalities` - the number of deaths attributable to the illness

### Research questions
1. How have foodborne disease outbreaks evolved over time?
2. Which foods and locations pose the highest risk for foodborne disease contamination?
3. Which pathogens present the greatest threat to public health?

### Data analysis and visualisation
Data was analyzed using [PostgreSQL](https://www.postgresql.org/) and visualised in [Tableau](https://public.tableau.com/app/discover). 
- [Data cleaning and analysis](https://github.com/MGdata148/sleep-analysis/blob/main/code)
- [Results](https://github.com/MGdata148/sleep-analysis/blob/main/results.docx)
- [Visualisation](https://public.tableau.com/views/Sleepanalysis_17347068539190/SleepAnalysis?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

### Conclusions


