# Capstone Project: Analyzing Natural Disasters Worldwide
This project aims to analyze natural disasters worldwide since 1990 using the EM-DAT: The International Disaster Database. The EM-DAT database is maintained by the Centre for Research on the Epidemiology of Disasters (CRED) and contains data on the occurrence and effects of thousands of disasters around the world.
## Data Sources
- [EM-DAT - Country Profiles - Humanitarian Data Exchange (humdata.org)](https://data.humdata.org/dataset/emdat-country-profiles)
- [EM-DAT | The international disasters database (emdat.be)](https://www.emdat.be/)
## Use
EM-DAT is used by governments, researchers to identify patterns and trends in disaster occurrence, analyze the impacts of disasters on different populations and regions, and develop policies and strategies to mitigate the effects of disasters.
## Objective or Concept
The objective of EM-DAT is to provide comprehensive, accurate, and reliable information on disasters that have occurred worldwide. The database includes a wide range of information, such as the type of disaster, location, number of fatalities and injuries, economic damages, and more.
## Use Case
* Disaster risk reduction planning:EM-DAT provides data on past disasters that can be used to assess risk and plan for future disasters.Governments or other organizations can use this data to prioritize disaster risk reduction activities.
* Education and awareness: EM-DAT's data can be used to educate people about disasters, their impacts, and how to prepare for them. 
* Researchers can also use this data to evaluate the effectiveness of disaster management policies and practices.
## Project Plan
1. Clean and process the data using SQL and SSIS. Create one fact table and six dimension tables. The dimension tables will include the following:
* Year (century, year duration).
* Country (capital, continent, longitude, latitude etc.).
* Disaster group.
* Disaster subgroup.
* Disaster type.
* Disaster subtype.
2. Use Python to choose statistical models, train the models, test and validate the models and predictions. Based on specific criteria, such as disaster type, location, or time period to analyze data.
3. Create visualizations including graphs, maps, and charts to communicate the insights gathered from the data effectively.
## Technologies Used
* SQL
* SSIS
* Python
* pandas
* scikit-learn
* Matplotlib
* seaborn
