# AMCA
Analysis of Malaria Cases in Africa (2007–2017)
This project analyzes malaria cases reported across 54 African countries from 2007 to 2017. The aim is to evaluate incidence trends, healthcare responses (such as drug distribution and preventive treatment in pregnancy), and regional differences in sanitation and population profiles.
Problem Being Addressed:
Malaria remains a major public health challenge in Africa. The analysis aims to uncover insights into which countries are most affected, identify gaps in sanitation and healthcare delivery, and support strategic planning for malaria reduction.
Key Datasets and Methodologies:
The analysis was conducted in Power BI using card visuals, bar charts, pie charts, and line graphs. Data sources included country-level malaria reports, sanitation records, and population demographics (urban and rural).

3. Story of Data
Data Source:
The dataset was likely sourced from public health repositories such as WHO, UNICEF, and national health systems in Africa.
Data Collection Process:
Data was collected and aggregated at the country level annually, covering both disease metrics and public health infrastructure indicators.
Data Structure:
•	Rows: Country-year entries
•	Columns: Malaria cases, incidence rate, antimalarial drug distribution, rural/urban population, safe sanitation access, and preventive treatments in pregnancy.
Important Features and Their Significance:
•	Malaria Incidence & Cases: Core metrics to evaluate disease burden
•	Safe Sanitation: Indirect measure of environmental health
•	Preventive Treatments & Antimalarial Drugs: Indicators of public health response
•	Population Demographics: Help contextualize exposure and risk
Data Limitations or Biases:
•	Urban/rural ratios may be based on estimates.
•	Countries with low reporting infrastructure may underrepresent actual malaria burden.

4. Data Splitting and Preprocessing
Data Cleaning:
Data was normalized for visualization, and all numeric fields were converted to consistent formats (e.g., K for thousands, M for millions).
Handling Missing Values:
If data was unavailable for a year or country, it was excluded from visual summaries or assumed to be zero (if supported by context).
Transformations:
•	Computed averages for malaria cases, urban and rural populations
•	Linked treatment metrics with total cases to analyze healthcare response
Data Splitting:
•	Dependent Variables: Malaria cases, incidence, treatment coverage
•	Independent Variables: Country, year, sanitation level, urban/rural population
Stakeholders:
•	African Ministries of Health
•	WHO and regional health organizations
•	NGOs and donor agencies focused on disease prevention
Value to the Industry:
Helps assess the impact of malaria control efforts, inform policy decisions, and guide future investments in healthcare infrastructure.

5. Pre-Analysis
Key Trends Identified:
•	Malaria incidence remained high across the decade with a rising trend in total reported cases.
•	Averages (from top cards):
o	1.07M average malaria cases
o	190.09 incidence rate per 1,000 at-risk population
o	2.07K urban population (in thousands)
o	33.42K rural population (in thousands)
Initial Observations:
•	Congo, Mozambique, and Burkina Faso had the highest malaria burdens.
•	Sanitation coverage varied significantly, with Tunisia, Egypt, and Morocco leading in safe services.

6. In-Analysis
Detailed Observations:
•	Total Malaria Cases vs. Incidence (Line Chart):
While total cases rose significantly, incidence rates remained relatively flat—suggesting either increased reporting or improvements in risk population estimation.
•	Reported Malaria by Country (Bar Chart):
Congo (77.55M), Mozambique (43.98M), and Burkina Faso (41.60M) had the highest cumulative cases.
•	Children Receiving Antimalarial Drugs (Pie Chart):
The chart reveals a large discrepancy between the total number of children and the proportion receiving antimalarial treatment.
•	Sanitation Services (Bar Chart):
North African countries like Tunisia and Egypt scored highest; Sub-Saharan countries like Libya and Djibouti showed weaker sanitation infrastructure.
•	Preventive Treatment in Pregnancy (Bar Chart):
Ghana (166), Zambia (147), and Malawi (115) led in maternal care interventions.
•	Incidence vs. Rural Population (Combo Chart):
Burkina Faso and Uganda had both high rural population averages and elevated malaria incidence rates (107%–120%).
•	Incidence vs. Urban Population (Combo Chart):
Benin and Côte d'Ivoire exhibited moderate incidence with relatively high urban population coverage.

7. Post-Analysis and Insights
Key Findings:
•	Countries with poor sanitation and large rural populations had the highest malaria burdens.
•	Incidence does not always correlate with total case count, showing variability in at-risk population size.
•	Maternal health programs are better structured in West African countries.
Comparison with Initial Expectations:
•	Hypothesis that rural population size increases malaria vulnerability was validated.
•	Some countries with higher urbanization showed surprisingly high incidence, suggesting urban slums or underreporting in rural areas.
Unexpected Outcomes:
•	Despite high total cases, some regions demonstrated relatively low incidence rates—indicating potential disparities in risk modeling or healthcare reach.

8. Data Visualizations & Charts
[Insert Dashboard Screenshot]
Key visualizations include:
•	Time-trend line chart (2007–2017)
•	Bar charts for reported cases, preventive care, and sanitation
•	Pie chart for antimalarial treatment in children
•	Combo charts for malaria incidence vs. rural and urban populations

9. Recommendations and Observations
Actionable Insights:
•	Prioritize targeted interventions in Congo, Burkina Faso, and Uganda.
•	Expand maternal care coverage in countries like Senegal and Sierra Leone.
•	Improve access to clean sanitation facilities in low-ranking countries.
Policy Recommendations:
•	Partner with sanitation-focused NGOs to build sustainable infrastructure.
•	Scale up antimalarial drug access programs for children and rural populations.
•	Regularly update malaria surveillance and reporting systems.

10. Conclusion
Key Learnings:
•	Malaria remains a systemic issue tied to poverty, sanitation, and healthcare access.
•	Disparities exist in how well countries implement maternal care and antimalarial coverage.
•	A data-driven response strategy is essential for measurable impact.
Limitations:
•	Some data may be based on estimates or partial reporting.
•	Sanitation and population data may not be updated yearly.
Future Research:
•	Include temperature, rainfall, and seasonal patterns.
•	Correlate with healthcare worker density and hospital infrastructure.
•	Track changes in vector control policies and bed net distribution.

11. References & Appendices
References:
•	World Health Organization (WHO) Malaria Report
•	UNICEF Sanitation Statistics
•	Power BI Dashboard (Malaria Cases in Africa Analysis)
Appendices:
•	Power BI file: Malaria cases in Africa Analysis.pbix
•	Dashboard visual: 
 Country-level breakdown tables (available in PBIX)

