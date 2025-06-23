# EV-Data-Analysis Usig Python
## Project Objective
This project analyzes electric vehicle (EV) registration data from Washington State to explore trends in EV adoption, performance, and pricing.

## Key Highlights:

* Cleaned and explored 247K+ EV records

* Visualized top models, counties, and year-wise adoption

* Built a linear regression model to predict electric range using MSRP, model year, and make/model

* Used Python (Pandas, Seaborn, Scikit-learn) in Google Colab

## Dataset used
- <a href="https://drive.google.com/file/d/1-rmtaxZ058aHY-Yn6n09Tq2tbiXsxD8v/view?usp=sharing"> EVs data set</a>

## Questions (KPIs)
# Data Cleaning Questions:
 - How many missing values exist in the dataset, and in which columns?
 - How should missing or zero values in the Base MSRP and Electric Range columns be handled?
 - Are there duplicate records in the dataset? If so, how should they be managed?
 - How can VINs be anonymized while maintaining uniqueness?
 - How can Vehicle Location (GPS coordinates) be cleaned or converted for better readability?
 # Data Exploration Questions:
 - What are the top 5 most common EV makes and models in the dataset?
 - What is the distribution of EVs by county? Which county has the most registrations?
 - How has EV adoption changed over different model years?
 - What is the average electric range of EVs in the dataset?
 - What percentage of EVs are eligible for Clean Alternative Fuel Vehicle (CAFV) incentives?
 - How does the electric range vary across different makes and models?
 - What is the average Base MSRP for each EV model?
 - Are there any regional trends in EV adoption (e.g., urban vs. rural areas)?
# Data Visualization Questions:
 - Create a bar chart showing the top 5 EV makes and models by count.
 - Use a heatmap or choropleth map to visualize EV distribution by county.
 - Create a line graph showing the trend of EV adoption by model year.
 - Generate a scatter plot comparing electric range vs. base MSRP to see pricing trends.
 - Plot a pie chart showing the proportion of CAFV-eligible vs. non-eligible EVs.
 - Use a geospatial map to display EV registrations based on vehicle location.
