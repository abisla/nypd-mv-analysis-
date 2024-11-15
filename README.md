
# OVERVIEW:
Within the five boroughs that make up New York City, around 8.2 million people dwell. Thousands of accidents occur each year as a result of a variety of circumstances. The NYPD gathers data on each of these accidents and makes it available to the public on nycopendata.socrata.com. We decided to dig deeper into the crash data to see if there were any underlying patterns or relationships that could explain the high frequency of collisions. From July 2012 to March 2022, the data included almost 2,00,000 observations.

BRIEF -
We accessed the data from "nycopendata.com" using Open Data API (OData API) and performed Data Connection with Tableau.
Then, we cleaned the data using Python and stored it in Google Cloud Storage as a Bucket to create a virtual instance.
We performed our analysis using Google's Big Query in Google Cloud Platform and stored the query results in CSV files.
After our analysis, we have generated a report using Google Sites to share our Insights and give Recommendations.
Tableau Story Link: https://public.tableau.com/app/profile/amar.b1158/viz/nypd2/Dashboard1

![image](https://github.com/user-attachments/assets/f8f1a555-307f-4b14-800a-d570c771f081)



## DATA DESCRIPTION:
The Motor Vehicle Collisions crash table contains details on the crash event. Each row represents a crash event. The Motor Vehicle Collisions data tables contain information from all police reported motor vehicle collisions in NYC. The police report (MV104-AN) is required to be filled out for collisions where someone is injured or killed, or where there is at least $1000 worth of damage.

Dataset link: https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95

## APPROACH:
Understanding the Data - It is important to understand our data and our problem statement i.e., how to decrease the number of injuries and deaths in New York City.

Preparing the Data - After understanding our dataset, it is essential to prepare the data. We have used GCP Big Query to remove null values and duplicate entries.

Perform Analysis - We have carried out a Time-series analysis and made dashboards to understand more about the factors and causes of Motor collisions in New York City.

Get Insights - We generated interactive tableau dashboards to support our findings and get insights from the data.

Give Recommendations - Based on our analysis, we will provide recommendations to decrease the number of Motor collisions.

## QUESTIONS FOR ANALYSIS:
Before exploring the data, we created a list of questions we wanted to address:

Is there a trend in the number of accidents?
Is there a relationship between the time of day and the contributing factors of the accident? (Time Series Analysis)
Which areas are more "Collision-prone" areas? (Collision prone analysis)

## RESULTS:
Analysis performed using Google Cloud Platform:
A) Most Injuries and Deaths were caused due to which Vehicle type?

![image](https://github.com/user-attachments/assets/6bb082ad-13fa-4a28-9373-ec438948bafb)


B) Most of the collisions was caused due to which factor?

![image](https://github.com/user-attachments/assets/2a109bcd-6474-4fe1-9837-150933aa640e)


Analysis performed using Tableau:
A) Detecting Collision-Prone Areas -

![image](https://github.com/user-attachments/assets/56b72e17-544c-4e03-bdf6-fe08a183a537)



B) Time Series Analysis -

![image](https://github.com/user-attachments/assets/5b0f1011-3519-4f9c-9316-1b8528e3297d)
![image](https://github.com/user-attachments/assets/73ba1e75-8284-406f-a718-5d16ab7e8c6a)




## INSIGHTS:
- Between 4 pm to 5 pm was the peak time of the day when the maximum number of people got injured.
- The number of people getting injured was rising from 2012 and was at its peak in 2018 with a value of 123,859 injuries.
- In 2018, the total number of injured people decreased to 29,604 injuries in 2022.
- The highest number of deaths and injuries were majorly caused by a lack of Driver’s attention. The other factors also point toward the Driver’s lack of driving skills.
- Most of the accidents were caused by Sports utility/Station wagon vehicles, followed by Sedan and Passenger vehicles.
- Also, 4 - wheeled vehicles were more prone to accidents than 2 - wheeled vehicles.

## RECOMMENDATIONS:
- Increase the number of Traffic Officers between 4 pm and 6 pm on days with the highest accident rates.
- Raise the availability of ambulances between 1 pm to 5 pm in collision-prone areas.
- Provide a more robust and efficient Public transit system to encourage usage by commuters.
- Focus on high collision-prone areas such as 11236, 11207, and 11234 in prioritizing new projects like traffic lights or street signs.
- Increase the frequency of driver re-training and more strict fines for repeat offenders.
- Increase the awareness about the use of public transport the commuters instead of walking or using personal vehicles to reduce accidents.
- Among all the boroughs, BROOKLYN and QUEENS had the highest number of deaths in New York City.
