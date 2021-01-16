# Tableau CitiBike: Spring Break (April 4, 2020 - April 11, 2020) 

## Goal
Analyze CitiBike data between April 4, 2020 - April 11, 2020 to identify and visualize trends in Tableau Public. 

## Data Manipulation/Preparation

Any trip duration that exceeded 24 hours were filtered out of the dataset. It was assumed trips that exceeded 24 hours were outliers and were not an accurate reflection of the time spent using the bike. Riders that were above the age of 80 were also filtered out of the dataset based on the following assumptions:  It was unlikely that individuals over the age of 80 would be taking bike rides in New York, and any reported age over the age of 80 were deliberately entered incorrectly or were typographical errors. Age bins were created for the remaining riders.

Gender was converted from a numerical classification (0, 1, 2) into catergorical classification (female, male, unknown) through the creation of an alias for each gender type. Calculated fields were created for age and trip duration. Date of birth was converted to age used a calculated field, and trip duration was converted from seconds to hours using a calculated field.  

## Analysis

The analysis focused on usage during spring break of 2020 to discover trends that may be helpful in developing a marketing plan to increase usage during Spring Break 2022. The data revealed that the majority of user types were subscribers (Subscribers 177,157 vs Customers 54,368). Annual subscribers made up over 90% of total riders during spring break. Looking at age and gender, males make up the majority of users, and most of those users are between the ages of 20-40. However, there is also a large pool of male users that are between the ages of 40 -60.  There is also a large set of riders that are between the ages of 40 and 60 that self-identifed as unknown. This deviates greatly from the rest of the user demographic trends. Filtering out those users, male users clearly dominate trip usage. 

Looking only at age, the number of trips were the highest among indiviudals that are between the ages of 20 and 40.  However, individuals over the age of 60 took over 15,000 trips.  There may be an opportunity to focus marketing efforts on increasing ridership within the senior population.  Additional steps should be taken to further explore this option.


There is a large segment of users who are "unknown".  Additional research is needed to determine why the gender type for a large segment of users are reported as unknown.  There may be an opportunity to improve the way that users are requested to provide gender information or to provide options other than female and male.  We want to create an inclusive space where our users feel empowered to provide information regarding information surrounding gender identity.  Alternatively, we should confirm that the questions asked regarding gender are clear and easy to understand.  There may be a marketing opportunity to demonstrate the Citi Bike use is open to all regardless of gender identity.

Analysis was completed on usage based upon the BikeID.  There may be an opportunity to rotate bikes between the busy and least busy stations to ensure that bikes are being used on a relatively equal basis.  This will assist with monitoring the maintenance and longivity of the bike life.

## Recommendations
* Continue marketing campaigns to encourage short-term rentals during spring break. 
* Continue marketing campaigns to encourage female and senior ridership during spring break.
* To prepare for tourist season, schedule maintenance for all Bike IDs where the average trip duration exceeds 15 hours. Review all bike rides Check all bikes with trip durations under 90 seconds and the same starting and ending stations for any needed repairs. 

There is steady ridership growth across user types and gender, suggesting a healthy demand for CitiBikes.  Therefore, recommendations would be to focus marketing campaigns towards those users.

## Further Analysis
For further analysis, I would look at additional weeks during the weeks of March, April, and May to explore any unindentified trends in bike usage. 
I would also look into why there are so many “unknown” 50-year old users. 