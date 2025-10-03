OVERVIEW
Goal: Providing a data driven recommendation for the safest and low risk aircraft for the launch of Safiri Bespoke's commercial and private aviation services
Opportunity: With Uber introducing helicopter rides in 2026, the aviation market is expanding and Safiri Bespoke is uniquely positioned to enter the airplane market.
Pertinent question: Which aircraft models have the best safety profile and operational history?



BUSINESS UNDERSTANDING

Safiri Bespoke is the leading tours and travel agency in America. There is need to expand to new markets with Uber introducing helicopter rides in its application in 2026. Safari Bespoke intends to penetrate the airplane markets for commercial and private enterprises.

As such, the goal of this project is to determine the aircraft that will pose the least risk to this company in the new business endevour. The recommendations will entail more than one aircraft model as the company intends to operate airplanes for commercial and private enterprises.



DATA UNDERSTANDING AND ANALYSIS

The dataset used for this project is titled 'AviationData.csv'.

The 'Aviation Accident' dataset provides a comprehensive record of aircraft accidents that occurred between the years 1919 and 2023. This dataset captures crucial details of each accident, including the date of the incident, registration number of the aircraft involved, the country where the accident occurred, the specific location, the category of the accident, and the number of fatalities.



METHODS

This was a straightforward project as the columns were populated with the data I would need to achieve the business objective. However, I had to conduct data cleaning and pre-processing using Pandas. This involved:

1\. Handling missing values

2\. Data type conversion

3\. Standardizing aircraft types

4\. Filtering relevant timeframe



I then proceeded to Exploratory Data Analysis (EDA) by using Pandas, Matplotlib, and Seaborn, to perform exploratory data analysis to uncover patterns and outliers. This way, I determined accident frequency based on the air craft make and model. I also determined the trends in accidents over the years to check how various aircraft companies have performed. Furthermore, I compared the total fatalities for the aircrafts as a way of checking the safety.

The last step was visualization and reporting using Tableau. I was able to create interactive dashboards to visualize:

1\. Top safest aircraft models

2\. Fatality trends based on the model

3\. Uninjured passengers based on the aircraft model per accident

4\. Minor and serious injuries comparison per aircraft model

This was then followed by recommendations based on the available data.



FINDINGS

After extensive EDA, Safari Bespoke should settle for the Bell make for private enterprises. Specifically, Bell 206B model ticks most of the checkboxes for safety. The model has been in operation for decades and there has been a decline in the number of accidents since 1980. 

One engine implies it is less complex model and its long operation history insinuates the failure modes are well documented. Overall, it has less fatalities, less serious injuries and minor injuries.



For the commercial aircraft, Safari Bespoke should stick to the Boeing 747 series. Any model in the series ranging from 747-300 to 747-400 is a perfect fit for the business. The data might show higher number of fatalities for the Boeing make but this is mainly caused by earlier models and the large number of Boeing crafts. That withstanding, the 747 series stands out for the safety metric.



The last result from the analysis is that most accidents occur durig VMC conditions. These are considered to be safer conditions but also involve higher volume of airpolanes. IFR conditions on the other hand seem to have less fatal accidents. I expected inverse results but there is an explanation for this phenomenon.



TABLEAU DASHBOARD
https://public.tableau.com/views/AircraftSafetyProject/AircraftSafetyDashboard?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link




