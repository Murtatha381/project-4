# project-4
## Machine Learning Project
-------------------------------------------------------------------------------

## Project Title:
### Heart Attack Risk Prediction and Analysis
-------------------------------------------------------------------------------

## Team Members:
* Patrick Schulze
* Libnis Sanchez
* Murtatha Alwan
* Callie Carlton
* Dianna Rivera

-------------------------------------------------------------------------------

## Project Outline
### Project Description
This project attempts to find correlation between heart attack risk and various lifestyle factors, such as BMI, income, age, sex, etc.  

### Data Collection, Model Building, and Analysis
1. Imported data found in Kaggle
2. Cleaned and prepared data (ETL) in Jupyter Notebook
3. Created machine learning models to determine accuracy of risk conclusions
4. Compared variables to address research questions

### Presentation and Summarization 
4. Created and presented a formal visual presentation
5. Drafted written analysis of the data
6. Summarized conclusions

-------------------------------------------------------------------------------

## Research Questions
1. How does income affect heart attack risk?
2. How does level of education affect heart attack risk
3. How does a person's age affect their risk? What about their sex?
4. Does smoking affect a person's risk for heart attack? What about alcohol consumption?
5. How does physical activity affect heart attack risk?
6. How does mental health affect heart attack risk?

-------------------------------------------------------------------------------

## Datasets
Heart Attack Risk Prediction Dataset
(https://www.kaggle.com/datasets/alexteboul/heart-disease-health-indicators-dataset)

Slidedeck
()

-------------------------------------------------------------------------------

## Task Delineation
* Patrick - dataset research, project proposal, model building, finding alternative dataset
* Callie - dataset research, project proposal, model building, analysis
* Murtatha - dataset research, project proposal, model building, analysis
* Libnis - dataset research, project proposal, model building, analysis
* Dianna - dataset research, project proposal, model building, analysis

-------------------------------------------------------------------------------

## Repository Table of Contents
* "Resources" folder containing the original CSV file
* "Images" folder containing images of visualization and analysis
* Health_Predictive_Models notebook containing different machine learning models
* Heart_Analysis notebook containing analysis and visualizations comparing different factors to heart attack risk

-------------------------------------------------------------------------------

## Analysis

The purpose of our team is to identify what factors if any correlate with a person’s heart attack risk. We hypothesized that BMI, physical activity, smoking, alcohol consumption, age, sex, and income would be more likely to correlate to an individual’s heart attack risk. Our curiosity also led us to review if factors like level of education and mental health would result in any correlation pattern. 

Our team was able to find a data set from Kaggle that had several rows of patient information collected from the CDC in 2015. The dataset contained several columns relating to medical history and socioeconomic status that our team further narrowed down to make a model that would accurately predict heart attack risk. 
While cleaning the dataset our team attempted several different supervised and unsupervised models before finding that the unsupervised neural network model provided the most accurate level of 90.5%. With our model, we then proceeded to filter out our chosen factors to plot and review for any trend lines. 
Traditional medical factors such as BMI, smoking, level of physical activity, smoking usage, and alcohol consumption have led to the common opinion that if identified can increase heart attack risk when in excess. When reviewing our dataset, we found that not only does the absence of physical activity have a positive correlation even when in excess, but neither does alcohol consumption.  
 ![image](https://github.com/Murtatha381/project-4/assets/129472048/39413f93-19a1-476b-8355-a444b82ab347)

 ![image](https://github.com/Murtatha381/project-4/assets/129472048/76eeadb0-e337-4ece-b161-fceff3e6eab3)

There was no correlation identified regarding BMI, which could further support that BMI is a baseless and outdated measure of health per current research trends. 
 
 ![image](https://github.com/Murtatha381/project-4/assets/129472048/b25eef9f-d140-45ed-a1cb-0ac0cdbea9b0)


The mental health factor was measured by identifying how many days in a month the surveyed individual had a “bad mental health day.” While no correlation was found with lowered mental health it was interesting for our team to note that individuals who reported having an average of 19 “bad mental health days” had the most significant risk for a heart attack. 
 
![image](https://github.com/Murtatha381/project-4/assets/129472048/3f79ee77-0cd0-4614-9b98-f8cad59bdc24)

-------------------------------------------------------------------------------

## Conclusion

Our team was successful in completing an accurate prediction model that can detect whether someone is at risk of a heart attack. With the factors reviewed, we found that while most traditional theories of lower income, lower level of education, smoker status, and a minimal level of physical activity do correlate to an increased risk of heart risk factors such as BMI and alcohol consumption play little to no role in an increased risk per our model. 
