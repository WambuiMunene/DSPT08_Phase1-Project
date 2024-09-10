# DSPT08_Phase1-Project
Overview:

My company is desirous in venturing into a new airline operations business for commercial and private use. The business model targets regional short haul scheduled commercial flights as well as private charters. The financial investment for this project is huge, and significant analysis of the opportunities, risks and returns will need to be undertaken to determine technical, financial and commercial viability.This will require multiple analyses with multiple data sets and models to determine market opportunities in different regions, competitor analysis, profitability and return on investment(ROI), technical risks to name but a few. My role in this multi-disciplinary endeavor is to perform an analysis of potential risks associated with different aircraft makes and models in order to determine the safest models in the market and make a recommendation to the head of the aviation department on the make and models to consider for this investment.

Data 

The analysis is based on the National Transportation Safety Board (NTSB) aviation accident database, which contains civil aviation accident and incident data from 1948 to 2023. The dataset covers the United States, its territories, and international waters. https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopsesThe dataset covers various aspects of accidents/incidents like flight stage, damage extent, location (latitude/longitude), flight purpose, fatalities, injuries, and weather conditions.Aircraft characteristics are also documented, such as make, model, engine type, and number of engines. The dataset includes flight.A noted limitation is missing or inconclusive values in important columns, like report status (which details if the cause was pilot error or technical failure).Despite this, the large size of the dataset still allows for reasonable conclusions about safety relationships across different aircraft makes, models, and engine types.I will use the CRISP-DM methodology and employ various Python libraries like Pandas, Numpy, Matplotlib and Seaborn for data analysis, data cleaning and visualization. 

Data Analysis
The frequency of Accidents is anlysed against the Make, No. of Engines, Types of Engines and the severity of casualties. From this analysis it is determined that aircraft with reciprocating engines are the most dangerous and those with 3 or nore engines are the safest. Further analysis of the top 10 models (based on the number of incidents) is done to determine the survival rate, the number of accidents based on engine numbers, and from this analysis, I determine that Boeing has the highest survival rate, thehighest median no. of engines and the lowest occurences of accidents especially in the 3 and 4 engine category.
<img src="./Images/image-1.png>
<img src="./Images/image-2.png>
<img src="./Images/image-3.png>
<img src='./Images/image-4.png>


The analysis now focusses on Boeing to analyze the frequency of accidents for the models with 3 or more engines. The main Boeing Models are the 747, 727, and the 707.  The other models such ad DC-10, B17 and B1 are either military planes and/or no longer in the market.
However, comparing the number Boeing's accidents for models with 3 engines and above(155) with the total accidents in the AviationData_Clean (over 78K), it is correct to say that Boeing Models are overall safe, and the company should consider Boeing as the make and chose the above models based on the level of usage e.g. no. of passengers, distance covered, maintenance costs etc
<img src="./Images/image-5.png>
<img src="./Images/image-6.png>

Recommendations
1. Comparing the number of Boeing’s accidents for models with 3 engines and above(155) with the total accidents in the cleaned dataset (over 78K), it is correct to say that Boeing is the safest Make.
2. The safest model overall from the dataset is Boeing 707. However, based on the intended use and range e.g.no. of passengers, distance covered, maintenance costs etc.,  the 747 and 727 models are still a safe option.
3. The company should not invest in any aircraft with less than 3 engines and /or with reciprocating engines as those have been determined to be unsafe according to the data

Next Steps:
Perform further analysis of data available for all  Boeing Makes and Models  in operation .Data to answer the following questions:
Safety Record
Cost of Equipment
Cost of Maintenance
Range
Maximum no. of Passengers and Crew

This coupled with competitor and market analysis, customer preferences ,financial models, will help the company make the best decision on the mix and size of the fleet that will yield the best return on investment.

