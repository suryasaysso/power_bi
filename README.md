# Data Visualization Project on INDIAN SLUMS ANALYSIS
The repository "power_bi" contains the project to understand the situation of the slum population all over India as per the 2011 census. The objective is to understand and visualize their population, literacy, employment rate etc. 

# INSTALLATION
The project is done using Power BI. 

# INTRODUCTION
Slums have come to form an integral part of the phenomena of urbanization in India. Comprehensive information on the slums being essential for formulation of effective and coordinated policy for their improvement. Formation and identification of slum enumeration blocks prior to the conduct of 2011 Census has made it possible to compile and prepare special tables for slums. It is for the first time in the history of census in the country that the slum demography is being presented on the basis of the  actual count. The systematic delineation of slums for collection of primary data on their population  characteristics during population enumeration itself may perhaps be the first of its type in the world.

# ABOUT THE DATASET
Slum population has been reported from 26 States/Union territories. Nine States/Union territories,  namely, Himachal Pradesh, Nagaland, Mizoram, Sikkim, Arunachal Pradesh, Manipur, Dadra & Nagar Haveli, Daman & Diu and Lakshadweep have not reported any slum population in their cities/towns. The electronic data provides information on slums at following three levels. The data set provides the information on slum and urban population of cities/towns reporting slum relating to number of households, total population, population in 0-6 age group, literate population, Scheduled Castes, Scheduled Tribes and workers, main workers, marginal workers and distribution of workers into four industrial categories namely Cultivators, Agricultural Labourers, Household Industry workers and Other workers by sex – India & State/Union territory.
 - Source : Office of the Registrar General & Census Commissioner, India
 - Link : https://censusindia.gov.in/2011census/population_enumeration.html

# SAMPLE DATASET
![dataset_bi](https://user-images.githubusercontent.com/78856292/118389852-9b577500-b649-11eb-891d-aa682dced97a.JPG)

# PROCEDURE
The data which is obtained from the source is pre – processed and is then subjected to query analysis.  For this data, we perform various queries using ‘M language’. The data can be used to generate report from which the user can understand the data.

# 1) Data Preprocessing Queries
![BI1](https://user-images.githubusercontent.com/78856292/118389941-0ef98200-b64a-11eb-87e8-fa521a2f2b52.JPG)
![BI2](https://user-images.githubusercontent.com/78856292/118389969-2df81400-b64a-11eb-9b5e-0911eb5edc99.JPG)
  
  Final Sample after Preprocessing
  
![BI3](https://user-images.githubusercontent.com/78856292/118389996-626bd000-b64a-11eb-8134-1b73fb291519.JPG)

# 2) Visualization Reports
2.1 OVERVIEW

![CAT 2 11](https://user-images.githubusercontent.com/78856292/118390403-87f9d900-b64c-11eb-9af9-c78ac84d58bb.JPG)

Overview of the dataset is visualized here. From the stacked column chart for the population classified based on gender, we find a neutrality  between the genders. The slum population consists of 51.86% male and 48.14% of female population  respectively. The Pie chart shows that 68.13% of them are literates and 31.87% of them are illiterates. The histogram chart helps us to find the most illiterate female population by each city. Top 11 cities  with the most illiterate female population is displayed. Greater Mumbai is the most populous slum  city with most number of female illiterates(634157). The Doughnut chart displays the four types of main workers. 87.38% workers in the slum population are ‘Other workers’ and 4.61% have been returned as ‘Household Industry workers’. Meanwhile 5.9% workers are ‘Agricultural worker’ while only 2% of the workers in the slum population are ‘Cultivators’. We can also find that there are approximately 14 million households, 20.87 million illiterates among the slum population. We can also  find that there are around 8 million children who are under the age 6. Let us focus more about the employment and status of women in slums.

2.2 WORKFORCE

![CAT 2 2](https://user-images.githubusercontent.com/78856292/118390343-2f2a4080-b64c-11eb-975b-9fa31afe117d.JPG)

In following three dashboards, we focus only on the employment of the slum population. Here, in the Population by Workforce pie chart, we can clearly distinguish the population according to their  employment status. We find 31.47% of the total population are ‘Main Workers’ and 4.92% are ‘Marginal Workers’. We can also note that an alarming 63.6% of the total population are ‘Non  Workers’. The Pie chart for the Non Workers shows the gender wise classification of the unemployed. We can see that 62.75% of the unemployed slum population are female and 37.25% are male. We  have also displayed the approximate population of the slum population to be 65 million .Approximately 42 million among the slum population are unemployed and only about 24 million of them are employed.

2.3 MAINWORKERS

![CAT 2 3](https://user-images.githubusercontent.com/78856292/118390378-639dfc80-b64c-11eb-9c3e-21efa1fd2b4c.JPG)

In this dashboard, we focus in depth about the main workers in the slum population. The Doughnut chart displays the four types of main workers. 87.38% workers in the slum population are ‘Other workers’ and 4.61% have been returned as ‘Household Industry workers’. Meanwhile 5.9% workers are ‘Agricultural worker’ while only 2% of the workers in the slum population are ‘Cultivators’.
The 87.38% of other workers from a long term is mainly because of the liberalization, privatization and globalization’s impact since 1990’s in the urban cities. We can also find the second most job done by the main workers are ‘Agricultural labour’. This is because most of these labour are migrants from villages who once were farmers themselves. ‘Cultivators’ are the least in the count because very few own their land. 
Furthermore, classification based on gender is done and there is not much of a difference between the work classification. However, the classification of other main workers by gender reveals the status of women in the employment sector. About 81.94% of other workers are men while only 18.06% are women. 

2.4 MARGINAL WORKERS

![CAT 2 4](https://user-images.githubusercontent.com/78856292/118390524-300fa200-b64d-11eb-8869-b63104a381f2.JPG)

In this dashboard, we focus in depth about the marginal workers in the slum population. The Doughnut chart displays the four types of marginal workers. 75.43 % workers in the slum population are ‘Other workers’ and 7.51% have been returned as ‘Household Industry workers’. Meanwhile 14.14% workers are ‘Agricultural worker’ while only 2% of the workers in the slum population are ‘Cultivators’. 
Furthermore, classification based on gender is done and there is not much of a difference between the work classification. However, the classification of other main workers by gender reveals the status of women in the employment sector. About 64.37% of other workers are men while only 35.63% are women.

2.5 STATUS OF WOMEN

![CAT 2 5](https://user-images.githubusercontent.com/78856292/118390564-61886d80-b64d-11eb-94ff-3a18a4489a37.JPG)

In this dashboard, we focus about the status of woman among the slum population. We are aware of the patriarchal mindset that is prevalent all over the country. The women empowerment movements held by great leaders helped women to get their basic rights like birth right, education, financial freedom etc,. Here, through the doughnut chart, we can see that the population classification of children under the Age 6, made based on gender. We can see a neutrality between their birth rate which signifies the drastic reduction of Female Infanticide in the country. 
The Stacked column chart for literacy and illiteracy shows values closer to neutrality. The Male literacy rate is 55.86% and the female literacy rate is 44.14%. The male illiteracy rate is 43.33% while the female illiteracy rate is 56.67%. Though the female literacy rate is lower, it is still an improvement when compared to its past data. 
The Stacked column chart for the employment of slum population shows a strong bias towards the male population. The total male working population is 77.41% and the total female working population is only 22.59%. The unemployed male population is 37.25% and the unemployed female population is 62.75%. This imbalance is due to a lot of socio- economic and personal reasons. 

# CONCLUSION
The systematic delineation of slums for collection of primary data on their population characteristics during population enumeration itself may perhaps be the first of its type in the world. Here we understood and visualized the slum dataset. The analysis of data in this way can be of huge help for policy makers in the Government. 
