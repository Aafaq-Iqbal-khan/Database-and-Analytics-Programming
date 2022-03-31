# Database-and-Analytics-Programming

## Study of Correlation and Impact of Chronic Diseases

(The repository for the Database-and-Analytics-Programming project.)

## Abstract
In the past few decades, there has been an increasing dominance of chronic disorders, with a large number of people being adversely affected by them as well as increase in the number of deaths thus deteriorating the quality of life. Various factors like lack of awareness, negligence, lack of medical facilities, etc. have caused this situation. The aim of the present paper is to identify people with such ailments and find linkages between them. To support this objective, data of health surveys conducted by NHANES is used. This study also mentions the statistical analysis of various chronic diseases like Diabetes, Renal issues, Influenza, HIV and AIDS and also observes the prevalence occurring in them. It also highlights the geographic distribution of diseased people in the United States. The study was performed using four datasets based on health domain. For the purpose of storing and managing this data, MongoDB and Postgresql are used. Exploratory data analysis and visualisations are performed to examine and explain the underlying topic with the help of python libraries like Seaborn, Plotly and Matplotlib..

# Datasets:
1)	Eye Health Dataset
2)	HIV/AIDS Diagnoses Dataset
3)	Health and Nutrition Dataset
4)	Influenza, Pneumonia, and Covid-19 Deaths Dataset
Data was extracted in json format for each of the above dataset. This was further inserted into MongoDB to convert it into a readable format.

# ETL Methodology
![image](https://user-images.githubusercontent.com/102433874/161113160-49133575-e570-45f9-98f3-bb013aeda1b9.png)
 
# Results 
 
![image](https://user-images.githubusercontent.com/102433874/161113206-692d8d95-e8c2-4bd0-9cfe-bca460da1dc5.png)

![image](https://user-images.githubusercontent.com/102433874/161113237-a5b2cbfb-9b98-432e-8e88-3e3501de91e6.png)
 
![image](https://user-images.githubusercontent.com/102433874/161113258-c03750ed-c9cb-4f5c-baef-03b0512e4b02.png)

![image](https://user-images.githubusercontent.com/102433874/161113285-0b173ad3-5bf5-4c3d-85c7-e999dfdd13ff.png)
 
# Conclusion

On the basis of our findings, we observed that a person having any one of the chronic diseases was prone to catch another one. 
For instance, our study claims to prove that prolonged influenza would lead to pneumonia, an HIV infection if not taken care of; would eventually cause AIDS which is fatal, increase in the sugar levels has an adverse effect on the kidney and the HIV too accounted for deteriorating the kidney’s health. 
The eastern and southern US states have more mortality of contagious disease like HIV, influenza, and pneumonia.
The future plan of this project is to extend the scope of this analysis to different continents of the world and apply the discussed approach to especially African countries where the spread of HIV and other contagious diseases is higher than the United States. 



 
