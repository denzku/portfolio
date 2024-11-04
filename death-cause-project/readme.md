# Global Mortality Trends: A Comparative Analysis of Death Causes in Russia, Japan, USA and the World

## **Objective**
The purpose of this analysis is to compare the leading causes of death across three countries—Russia, Japan, and the United States— representing different continents but with comparable levels of development. The analysis focuses on understanding:
1. Overview of causes by continent and selected countries.
2. Yearly trends in death in each country.
3. The major shifts in death causes pre and after 2005.
4. The top 5 causes of death in each country, with an emphasis on distinguishing trends.
5. Comparative analysis of Russia with Eastern Europe, Eastern Europe with the world, and similar steps for Japan and the United States.

## **Methodology**
- The dataset includes the number of deaths by various causes across different countries and years.
- A stepwise approach was taken to examine the trends and changes in death causes over time, followed by regional and global comparisons.
- Data was visualized using bar charts, line plots, and a heatmap to showcase similarities and differences in trends.

## Clarifications

#### **Difference Between Chronic Respiratory Diseases and Lower Respiratory Infections:**

**Chronic Respiratory Diseases:** 
These are long-term conditions that affect the airways and lungs, typically due to damage or inflammation over time. Examples include chronic obstructive pulmonary disease (COPD), asthma, and chronic bronchitis. They tend to progress slowly and are often linked to lifestyle factors like smoking, air pollution, and genetics.

**Lower Respiratory Infections:** 
These are acute infections that affect the lower parts of the respiratory tract, including the bronchi and lungs. Examples include pneumonia, bronchitis, and tuberculosis. They are usually caused by viruses, bacteria, and can occur suddenly, but may resolve with treatment.


#### **Difference Between Neoplasm and Cancer:**

**Neoplasm:** 
A neoplasm (or tumor) is an abnormal growth of cells in the body. These growths can be either benign (non-cancerous) or malignant (cancerous). Neoplasms occur when cells grow and divide more than they should or don't die when they should. Not all neoplasms are dangerous; benign tumors generally don't spread to other parts of the body.

**Cancer:** Cancer is a malignant neoplasm, meaning it's a type of neoplasm that can invade and destroy nearby tissue and spread to other parts of the body (metastasis). Cancer cells are more aggressive and harmful than benign tumors, making them life-threatening if untreated.

This distinction is important because not all neoplasms are cancerous, but all cancers are neoplasms.

---

## **Analysis and Findings**


### 1. **Overview Of Death Causes**
This overview sets the foundation for a deeper exploration of how various diseases, accidents, and other factors have impacted mortality rates.

#### **Graph**: Death Cause Distribution Across Continents
This heatmap presents the percentage distribution of death causes across Europe, America, and Asia, offering a broad continental comparison:

![world_heatmap.png](graphs%2Fworld_heatmap.png)

- Cardiovascular diseases are the leading cause of death in all three continents, with Europe showing the highest rate (48%).
- Neoplasms (cancers) are the second most common cause, with similar rates across continents (20-23%).
- Significant continental variations are observed in chronic respiratory diseases (highest in Asia at 11%) and neonatal disorders (remarkably lower in Europe).
- Europe shows higher rates of alcohol use disorders compared to other continents.
- America has notably higher rates of interpersonal violence and diabetes.

#### **Graph**: Death Cause Distribution Across Japan Russia and United States
This heatmap focuses on Japan, Russia, and the United States, providing a more detailed look at specific countries:

![rujaus_heatmap.png](graphs%2Frujaus_heatmap.png)

- Russia has a strikingly high rate of cardiovascular disease deaths (57%) compared to Japan (29%) and the US (37%).
- Japan shows higher rates of neoplasms (33%) compared to Russia (15%) and the US (27%).
- The US has the highest rate of drug use disorder deaths among the three countries.
- Russia shows significantly higher rates of alcohol use disorders and interpersonal violence compared to Japan and the US.
- Japan has notably higher rates of dementias and lower respiratory infections compared to the other two countries.
- High rates of dementias, a type of diseases whose frequency increases as life expectancy increases, indicate a developed health system. In selected countries only Russia has lower dementia rate than its continent.


### 2. **Yearly Death Trends (Russia, Japan, USA)**

#### **Graph**: Yearly Deaths by Country

![total_deaths_by_year.png](graphs%2Ftotal_deaths_by_year.png)

- **Russia** experienced volatile spikes, especially in the 1990s, correlating with the socio-economic turmoil post-Soviet collapse.
- **Japan and United States** displays a more gradual rise in deaths due to their increased population by year.

---

### 3. **Net Change**

While yearly trends provide an overview of how causes of death have evolved in recent decades, it's also important to focus on the shifts that occurred before and after 2005, which 
corresponds to the middle of 30 years in the dataset.

#### **Graph**: Net Change in Causes of Death: 2005-2019 vs. 1990-2004

![russia differences.png](graphs%2Frussia%20differences.png)

**Russia**: 
- **Digestive diseases (+445,256 deaths):**
This significant increase could be related to changes in diet, increased alcohol consumption, or improvements in diagnosing these conditions. It may also reflect an aging population, as digestive diseases often affect older individuals more.

- **Cirrhosis and liver diseases (+319,942 deaths):**
The rise here is likely connected to alcohol consumption patterns, as well as increases in obesity and hepatitis infections. This ties into the point about alcohol use disorders mentioned in the image caption.

- **Cardiovascular diseases (-794,031 deaths):**
This substantial decrease might be attributed to improvements in medical treatments, better management of risk factors (e.g., blood pressure, cholesterol), and potentially some public health initiatives targeting heart disease.

- **Interpersonal violence (-322,611 deaths):**
This decrease may be due to the turmoil during the collapse of the Soviets in the 90s. It's a trend that might be worth exploring further.

- **Alcohol use disorders (-181,464 deaths):**
While this shows a decrease, it's interesting to note the increase in cirrhosis deaths. This could suggest changes in how alcohol-related deaths are categorized, or perhaps a shift in drinking patterns (e.g., less acute intoxication but more long-term heavy use).

![japan differences.png](graphs%2Fjapan%20differences.png)

**Japan**:
- **Neoplasms (+1,579,862 deaths):** 
This significant increase could be related to an aging population, improved cancer detection methods, and possibly environmental factors or lifestyle changes.

- **Cardiovascular diseases (+652,481 deaths):**
Unlike the trends seen in Russia and the US, Japan shows an increase in cardiovascular deaths. This might be attributed to the aging population outpacing improvements in cardiovascular care.

- **Lower respiratory infections (+414,576 deaths):**
The rise here could be connected to an aging population more susceptible to these conditions, as well as possibly changes in healthcare practices or environmental factors.

- **Chronic kidney disease (+202,163 deaths):**
This increase probably reflects rising rates of diabetes and hypertension, which are major risk factors for kidney disease, as well as the aging population.

- **Road injuries (-90,161 deaths):**
This decrease might be attributed to improvements in road safety measures, vehicle safety technologies, and potentially changes in driving habits or public transportation use.

![usa differences.png](graphs%2Fusa%20differences.png)

**USA**:
- **Neoplasms (+1,402,191 deaths):**
This significant increase could be related to an aging population, improved cancer detection methods, and possibly environmental factors or lifestyle changes.

- **Chronic respiratory diseases (+842,192 deaths):**
The rise here is likely connected to long-term effects of smoking, air pollution, and an aging population more susceptible to these conditions.

- **Chronic kidney disease (+636,839 deaths):** 
This increase probably reflects rising rates of diabetes and hypertension, which are major risk factors for kidney disease.

- **Drug use disorders (+439,486 deaths):**
This substantial increase likely reflects the opioid epidemic in the US, including both prescription opioids and illegal drugs.

- **Cardiovascular diseases (-524,212 deaths):**
This decrease might be attributed to improvements in medical treatments, better management of risk factors (e.g., blood pressure, cholesterol), and potentially some public health initiatives targeting heart disease.

- **HIV/AIDS (-251,921 deaths):**
This significant decrease likely results from advancements in antiretroviral therapies and improved prevention strategies. 


#### **Comparison**:
- In United States deaths caused by HIV is significantly lower in post-2005, in contrast Russia had nearly 150.000 more deaths in post-2005 period.
- While Cardiovascular diseases in declining in Russia and United States, Japan had 650.000 more casualties in post-2005 period.
- Alzheimer's disease and other dementias have **increased** in all three countries. This increase likely reflects an aging population and improved diagnosis and reporting of these conditions. It could also indicate longer life expectancy, allowing more people to reach ages where these diseases are common. Japan is leading with nearly **1.2 million more** deaths in post-2005 period.
- United States is the only with drug use disorders as top increasing cause.

---

### 4. **Top 5 Causes of Death and Distinguishing Trends**

This section focuses on the Top 5 Causes of Death in each country. By analyzing the most common causes, we can gain a clearer understanding of which health issues remain dominant.

#### **Graph**: Top 5 Causes of Death by Country
![top_5_causes_of_death_by_country.png](graphs%2Ftop_5_causes_of_death_by_country.png)


- **Russia**: Cardiovascular diseases dominated the top 5 causes of death. Cancer related deaths are around %15, which is the least between the three selected countries.
- **Japan**: The top 5 causes are predominantly chronic diseases, with cardiovascular diseases and cancer leading the list. External causes were notably rare. Also dementias showed high percentage due to high life expectancy and well-developed healthcare system.
- **USA**: Cancer, cardiovascular diseases are the leading causes. Also relatively higher Chronic respiratory diseases rate than Russia and Japan.


### 5. **Correlation Analysis**
- In this part of analysis, a distinctive cause is identified and its relationship to other causes is examined.

#### **Graph**: Russia Self-harm Correlation
![correlation_in_russia.png](graphs%2Fcorrelation_in_russia.png)

- **Alcohol Use Disorders (r = 0.95):** Very strong positive correlation, indicating a close relationship between alcohol abuse and self-harm. The correlation could indicate shared risk factors, or that drug use may increase the tendency of self-harming behaviors.

- **Drug Use Disorders (r = 0.43):** Moderate positive correlation, indicating some association between drug use and self-harm, though weaker than with alcohol. The weaker correlation compared to alcohol might reflect differences in prevalence or cultural factors related to drug use in Russia.

- **Interpersonal Violence (r = 0.99):** Extremely strong positive correlation, highlighting a concerning link between self-harm and violence towards others. This could indicate shared risk factors, or that individuals who engage in self-harm may also be more likely to experience or perpetrate interpersonal violence.

- **Road Injuries (r = 0.89):** Strong positive correlation, unexpectedly linking self-harm rates with road injuries. May reflect shared risk factors or broader societal issues. This unexpected relationship could potentially be explained by shared risk factors such as impulsivity, risk-taking behaviors, or the influence of substance use. It may also reflect broader social factors affecting both self-harm rates and road safety.

#### **Graph**: United States Drug Use Disorders Correlation
![correlation_in_united_states.png](graphs%2Fcorrelation_in_united_states.png)

- **Self-harm (r = 0.95):** Very strong positive correlation. Suggests a significant link between drug use disorders and self-harming behaviors.

- **Alcohol use disorders (r = 0.97):** This nearly perfect correlation suggests a substantial comorbidity between these two types of substance use disorders. Individuals struggling with one type of substance use disorder are very likely to also experience issues with the other

- **Cardiovascular diseases (r = -0.03):** Negligible correlation, suggesting no direct relationship.

- **Nutritional deficiencies (r = 0.99):** Extremely strong positive correlation. Drug use may directly impact nutrition through altered appetite or nutrient absorption. Lifestyle factors associated with drug use might lead to poor dietary habits.

#### **Graph**: Japan Lower Respiratory Infections Correlation
![correlation_in_japan.png](graphs%2Fcorrelation_in_japan.png)

- **Chronic Respiratory Diseases (r = 0.99):**  There is a very strong positive correlation between lower respiratory infections and chronic respiratory diseases. This is a logical correlation as chronic respiratory diseases (such as COPD or asthma) often predispose individuals to ongoing respiratory infections.

- **Cardiovascular Diseases (r = 0.95):** There is a strong positive correlation exists between lower respiratory infections and cardiovascular diseases. While these two conditions affect different systems, the strong correlation may be due to shared risk factors such as smoking, aging, or general health deterioration.

- **Heat and Cold Exposure (r = 0.88):** There is a significant positive correlation suggests that extreme weather conditions may contribute to respiratory infections, as these environments can weaken immune defenses. 

- **Tuberculosis (r = -0.96):** Interestingly, a strong negative correlation exists. This could indicate that as tuberculosis cases decrease due to better treatment or prevention, lower respiratory infections, unrelated to tuberculosis, become more prevalent. 
  
---

### 6. **Self-harm Correlation Analysis**

Understanding how self-harm correlates with other causes of death and which countries/regions has higher rates of self-harm can provide insights to this issue.

#### **Graph**: Countries with Highest Percentage of Self-Harm
- This graphic shows the countries where self-harm is one of the 5 most common causes of death, and its percentage with the total number of deaths in those countries.
![self_harm_percentage.png](graphs%2Fself_harm_percentage.png)


- Except Greenland and Sri Lanka, former Soviet countries are observed in the graphic.
- Greenland is the only country where self-harm percentage is above %10.

---

### 7. **Russia and Eastern European Countries Comparison**

Since self-harm is observed at high rate on mostly Soviet countries, comparising former Soviet countries and Balkan countries with rest of the Europe and the world is decided.

![diff_alcohol.png](graphs%2Fdiff_alcohol.png)
 
- Eastern Europe shows higher mortality rates in most alcohol-related categories compared to the Rest of Europe average.
- One of the biggest differences are in alcohol use disorders, where Eastern Europe's rates are substantially higher in both comparisons. Even though cirrhosis and chronic liver diseases (alcohol effects it directly), rate is higher than rest of Europe, it is nearly equal with the world surprisingly.
- Interpersonal violence and road injuries are an exception in the global comparison, where Eastern Europe shows lower rates than the world average.

- Road injuries show a more significant difference when comparing Eastern Europe to the world than to the Rest of Europe.

#### **Graph**: Violence By Year, Comparison in Europe
- To understand violence in Europe is that lower than Eastern Europe, Russia and Ukraine to the rest of Europe is compared.

![violence_by_year.png](graphs%2Fviolence_by_year.png)

- Significant peak in deaths during 1991-1995, reaching over 70,000 annually. Probably main reason is collapse of Soviet Union (1991) leading to political and economic instability.

- The graph shows a general decline in violence-related deaths after 2005, possibly due to stabilizing socio-economic conditions and improved governance. However, death rates in Russia and Ukraine remain significantly higher than in the rest of Europe throughout the observed period.

#### **Graph**: Death by Conflict and Terrorism, Eastern Europe Against Rest of the Europe
- Since there is a significant gap in violence because of Russia and Ukraine, comparing conflict and terrorism cause is decided.

![conflict_by_year.png](graphs%2Fconflict_by_year.png)

- Deaths from conflict and terrorism are consistently and significantly higher in Eastern Europe compared to the rest of Europe throughout this period.
- Peak in 1999: This dramatic spike in Eastern Europe likely corresponds to the Kosovo War and related conflicts in the Balkans during the breakup of Yugoslavia.
- Secondary peak in 1995: This could be associated with the later stages of the Bosnian War and other conflicts in the former Yugoslavia.
- High casualties in 1992: This aligns with the height of the Bosnian War and ongoing conflicts following the dissolution of the Soviet Union.
- Gradual decline post-1999: There's a noticeable decrease in deaths from 1999 to 2005, possibly reflecting the winding down of Balkan conflicts and increased stability in the region.
- Relative stability in rest of Europe: Deaths in the rest of Europe remain comparatively low and stable throughout the period, with only minor fluctuations.
---

After comparising Russia/Eastern Europe, Japan and the United States will be analyzed next.

### 8. **Japan and Asia Comparison**

#### **Graph**: Japan - South Korea - China - Southeast Asia
- Since Japan has better healthcare system than majority of Asian countries,  this bar chart compares the leading causes of death among nearly developed countries as Japan against Southeast Asia.

![jsc_heatmap.png](graphs%2Fjsc_heatmap.png)

- Neoplasms (cancers) are the primary cause of death in Japan (33%) and South Korea (29%), but less prevalent in China (23%) and Southeast Asia (14%).

- Cardiovascular diseases dominate in China (38%), significantly higher than in Japan (29%), South Korea (28%), and Southeast Asia (27%).

- Chronic respiratory diseases are markedly higher in China (14%) compared to Japan (3.9%), South Korea (5%), and Southeast Asia (6.9%). China's elevated respiratory disease rates could indicate ongoing air quality issues.

- Japan shows the highest rate of Alzheimer's disease and other dementias (8.3%). As mentioned before, it is linked to aging population and advanced medical detection.

- Self-harm and alcohol use disorder rates are notably higher in South Korea than in Japan or China. South Korea's high self-harm rate suggests potential mental health challenges that may require targeted public health interventions.

- Southeast Asia shows the highest rates of lower respiratory infections (13.9%) and tuberculosis (4.6%) among the compared regions, indicating significant challenges with infectious diseases.

- Neonatal disorders account for a higher percentage of deaths in Southeast Asia (5%) compared to the other countries, suggesting potential issues in maternal and infant healthcare.

- Diarrheal diseases are more prevalent as a cause of death in Southeast Asia (3.2%) than in the other regions, possibly reflecting challenges with sanitation and healthcare access.

#### **Graph**: United States - Canada - South America
- This heatmap compares the death cause percentages between the United States, Canada, and America, highlighting variations in mortality causes across these regions.

![uca_heatmap.png](graphs%2Fuca_heatmap.png)

- Cardiovascular diseases are the leading cause of death across all three regions, highest in the United States (37%), followed by Canada (34%), and America (29%).
  
- Neoplasms (cancers) are the second most significant cause of death, particularly in Canada (32%), followed by United States (27%), and America (18%).

- Alzheimer's disease and other dementias exhibit relatively consistent percentages across regions, but are slightly higher in Canada (4.9%) and in United States (4.6%) than America (2.6%).

- Lower respiratory infections are significantly higher in America (5.7%), compared to Canada (3.3%) and United States (3.2%).

- Drug use disorders are much more prominent in the United States (1.1%) compared to Canada (0.57%) and America (0.06%), indicating a notable public health crisis in the U.S.

- Self-harm shows a moderate variation, with the highest rate in Canada (2%), while America (1.4%) and the United States (1.6%) exhibit slightly lower rates.

- Neonatal disorders, interpersonal violence, and HIV/AIDS are significantly higher in South America. It might be due to socioeconomic challenges, including limited access to quality healthcare and preventive measures. Additionally, political instability and economic inequality is likely to increase violence.

### Conclusion:

This global analysis of causes of death provides a understanding of how mortality patterns vary across regions, driven by both non-communicable and communicable diseases, as well as external causes like violence and accidents. Key observations include:

- **High-Income Countries:** In wealthier regions like North America, Europe, and parts of East Asia, non-communicable diseases such as cardiovascular diseases, cancers dominate the mortality. Aging populations and lifestyle factors such as diet and sedentary behavior significantly contribute to these trends.


- **Lower-Income and Middle-Income Countries:** In contrast, many South American and Southeast Asian nations face a dual burden of disease, with high mortality from both infectious diseases (e.g., HIV/AIDS, respiratory infections) and emerging lifestyle-related illnesses. In certain both regions, neonatal disorders still accounts for a significant proportion of deaths, due to limited access to quality healthcare.


- **Regional Variations:** A detailed comparison of specific countries and regions (such as Russia, Japan, and the United States) revealed diverse health profiles. For example, Russia has a higher proportion of deaths from alcohol use disorders, while Japan's top causes include cancer and cardiovascular diseases, with lower levels of violent deaths compared to the U.S. and Russia, which has notable mortality from drug use and interpersonal violence.


- **Public Health Implications:** High-income nations should focus on reducing lifestyle-related risks, chronic diseases and dementias, while lower-income countries needs to build strong strategies to fight infectious diseases and improve healthcare to avoid such high rate of neonatal disorders. Additionally, high income countries should focus on improving mental health support since higher self-harm rates.


- The analysis reveals that each region's unique socioeconomic and healthcare contexts shape the leading causes of death, necessitating diverse policy approaches to reduce mortality and improve health outcomes globally.
