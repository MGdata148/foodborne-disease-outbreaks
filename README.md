# Foodborne Disease Outbreaks

### Background
Foodborne diseases are a significant public health concern globally, causing widespread morbidity and mortality. These illnesses result from the consumption of contaminated food or beverages, harboring pathogenic microorganisms such as bacteria (e.g., Salmonella, E. coli), viruses (e.g., norovirus), parasites, or chemical agents (e.g., aflatoxin, dioxin). Outbreaks occur when multiple cases of illness are traced to a common food source, often highlighting vulnerabilities in food production, processing, or handling systems. In 2015, the World Health Organization (WHO) released its first estimates of the global burden of foodborne diseases. The report revealed that contaminated food causes 600 million illnesses, 420 000 deaths, and 33 million lost healthy years annually, affecting 1 in 10 people worldwide [(Havelaar et al., 2015)](https://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.1001923).

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

Despite the main table two dimension tables were prepared: `food_categories` and `species_categories`. Additional tables contain more general information on contaminated food and contamination agent to enable better data analysis.

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
1. Foodborne disease outbreaks occured more frequently and had higher rates of hospitalizations and fatalities from April to June, which can be related to warm temperatures favoring the growth of microorganisms.
2. Both number of reported foodborne disease outbreaks and total number of cases showed a tendency to decrease over the years, what may indicate raising awareness and improvement in food supply chain.
3. Meat, fish and seafood, and vegetables were food categories most frequently causing foodborne diseases, respectively. This probably results from their high consumption rates combined with short shelf life and susceptibility to the development of microorganisms.
4. The type of meat responsible for the most of registered foodborne diseases was poultry, which is a common source of dangerous bacteria, e.g. *Salmonella*, *Campylobacter*.
5. Restaurants were the most common location for foodborne disease outbreaks, however the average number of cases was much higher in public utility facilities, where many people eat the same meals. The most dangerous foodborne disease outbreaks took place at assisted livig facilities and hospitals probably due to comorbid conditions of patients. Private homes and farms also showed high rates of hospitalizations and fatalities, which may be due to lack of compliance with food storage standards.
6. Foodbore disease outbreaks were most commonly caused by viruses and bacteria with *Norovirus*, *Salmonella*, and *Clostridium* occuring the most frequently.
7. The deadliest cause of foodborne disease outbreakes was *Listeria monocytogenes*, which is known for its high mortality rate of up to 30%.

