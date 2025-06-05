Mental Health Disorder occurences, and burden of disease in Poland, its neighbors, Europe, and WHO regions.

This project analyzes mental health and burden evoked by disorder in Poland, across neighbor ountries, Europe, and WHO regions, using Jupyter notebooks and open datasets.

# Overview

This project explores comparative occurence and burden metrics (DAILYs) in Poland, Europe, and WHO regions. Depics changes in occurene of disorders(Depressive Disorders, Anxienty Disorders, Eating Disordes, Bipolar Disorders, Schizophrenia) It includes data wrangling, visualization, and relevant insights. Designed for analysts, researchers, and data-curious folks.


## Project Sctructure

```bash
scripts/
    1a_data_cleaning.ipynb #Data cleaning separation by countries, and continens only
    1b_top_ten.ipynb #Separation data for each disorder, and sorting its values of occurene in ascending and descending order
    1c_top_ten_summary.ipynb #Extraction of countries with the higest and the lowest values of occurence for each disorder
    1d_poland_data.ipynb #Extraction the most and at least common disorders in Poland
    1e_polvsnei.ipynb #Comparison of each disorder occurence for Poland and its neighbor countries and depedence of time
    1z_plots.ipynb #Generates plots of: sorted values of top countries with higest and lowest occurence for each disorder, depedence of occurence of disorder in Poland over years 1990-2019, and comparison of disorder occurence for Poland and its neighbor countries (Belarus,Czechia,Germany,Lithuania,Russia,Slovakia,Ukraine) over time.
    2a_burden_data_comparison.ipynb #Data cleaning, separation of WHO countries by regions, and counting average burden for each disorder based on database records(only countries) for each WHO region.
    2b_mostburden_poland_neighboors.ipynb #Exstraction of top 50 higest and lowest values of DALYs for each disorder and comparison of country for the disorder and frequency of country in the ranking. Comparison DAILYs for each disorder with data for Poland and its neighbor counries.
    2c_best_sectrum_to_map.ipynb #Exstraction of burden of disorder for WHO region, which is European Region. Some statistics experiments to find disorder which the most various, smooth, and intresting data (+data standarization,plots for standarization). Comparison variation, standard deviation, and value of entropy for each disorder(all years). Geneartion of heat map plots (map of Europe), which shows DALYs for each disorder in 2019 year.
    2z_ploys.ipynb #Geretates heatmap plots for each disorder, which compares values of DALYs for Poland and its neighbor countries over time 1990-2019, and heatmap plots which compare calulated maunally average for each WHO regions, and compares it which data  for WHO regions included in database.
```
# Data source
https://www.kaggle.com/datasets/imtkaggleteam/mental-health/data

# Key insights

## Occurence of mental disorder
Most common disores are Anxiety and Depresive disorder. Anxitety disorders dominate in Brazil, Portugal, and New Zeland. Depressive disorders dominate in Uganda, Palestine, and Greenland.
The higerst occurence for bipolar disorder is for New Zeland and Australia, for Eating disorders is for Australia and Monaco, and for Schizophrenia is for United States and New Zeland. 

The  Anxiety disorders are the least common in Uzbekistan, Vietnam and Mongolia; Depressive disorders in Japan, Singapore, South korea and Bruinei;  Schizophrenia in Mozambique, Central African Repulic and Somalia; Bipolar disorder in North Korea and China; Eating disorders in Cambodia, Myanmar and Sonalia.

### In Poland:
-Anxiety disorder  is observed rapid descrease of occurence of the disorder since 2010 to 2017.
- Number of Bipolar disorder occurences constantly desreases since 1993 to 2019
-Number of Eating disorders occurence increases sine 1993 to 2019.
- Occurence for Schizophrenia (relatively) drasticly increases since 1990 to 2019
- For Depressive disorders, the occurence drasticly dives since 2000 to 2005, and spoud again since 2017 to 2019.

### Comparison Poland to its neighboor countries:
- The Anxiety disorder are most common in Germany, and Lithuania
- Bipolar disorder and Eating disorders dominate in Germany
-Depressive disorders are most common in Ukraine, and Lithuania, but the least common in Poland, and after Poland is Slovakia.
- For Schizophrenia, Poland is third after Chechia and Slovakia in the most common ranking, were the disorder is the leat common in Geremany.


## Burden of disorders (DALYs)

### Poland and its neighbot countries:
-Anxiety disorder has the higest values of DALYs in Germany and Lithuania. In Ukraine burden of the disorder were lower since 1998 to 2006. In Germany, the burden of the disorder increases since 2009 to 2019.
-Bipolar disorder and Eating disorders DALYs are higest in Germany.
- Depressive disporders's burden is higest in Ukraine, Lithuania and Belarus. The lowest values of DALYs are for Poland - Maybe the Poles are just accustomed to the state of mental health.
- Schizophrenia burden is higest in Chechia. In Poland and Slovakia the DALYs raising since 1990 to 2019. Germany is the country with the lowest DALYs for the disorder.

### WHO regions:
- Anxiety disorder burden is high in Region of Americas, where the value were raising since 1999 to 2004. The region with the lowest DALYs is South-East Asia Region.
-Bipolar disorder burden is higest for Region of Americas, Eastern Mediterranean Redion, and European Region and lowest for Western Pacific Region and South-East Asia Region.
- Depresive disorders has the higest values of DALYs for African, and Eastern Mediterranean Redion. The lowest values are represtanted by Western Pacific Region. For African Region, Region of Americas, South-East Asia Region, and Western Pacific Region values of burden were rasing since 1990-1994 to 2002-2004, what is opposite for Eastern Mediterranean Region, European Region, and Region of Americas.
-Eating disorders burden is higest in Region of Americas, and European Region. The burden is lowest in South-East Asia Region, African Region, and Western Pacific Region. The value of burden for the disorder rises in every WHO region.
- Schizoprenia burden is higest in Region of the Americas, and Western PAcific Region. The lowest values are in African Region, and Eastern Mediterranean Region. For all WHO regions exept Region of Americas, the burden raises.

### Countries of Europe(map):
-Anxiety Disorders, Eating disorders and Bipolar disorder are more burdensome in west part of Europe.
-Depressive disorders are the least burdensome in Poland.
-Schizophrenia is the most burdensome in Irleand and Netherlands, and tle least burdensome in UK.

For Schizophrenia, Anxiety, and Eating disorders the values of DALYs for Central-South-East Europe are different to rest of Europe.


# Future work
Corellation of income and disorder
Changes of occurance of disorder over time for Europe.
Changes of burden of disorder over time for Europe.

---

Let me know if you want this populated with real data insights, author info, or direct links to your GitHub repo.
