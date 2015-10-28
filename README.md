# InfoOrg
This is the dataset for INFM600 Information Organization assignment. 
# Sources:
All the datasets have been downloaded from the official Howard County portal https://data.howardcountymd.gov/. The portal consists of a huge number of csv files including every aspect of Howard County like the county census records, bridge locations, school locations etc. that can be downloaded. The files that I have decided to work on can be found under the sections “Schools_Elementary”, “Park_Playground” and “Residential Site Development Plans”. 

Focal data sets:-
The focal data set is named Residence.csv. It describes the upcoming residential projects in Howard County. The attribute “geom” will be used as a reference by other datasets to refer to this dataset. For this assignment I am trying to find the relation between the location of upcoming residential sites and how its occupancy is depended on other factors. The dataset has 1107 rows.
Howard County. (2015). Residential Site Development Plans [Data File]. Retrieved from https://data.howardcountymd.gov/ 

Dataset 1:-
The second dataset that I have chosen is named Schools_Elementary. The objective is to help the potential users to determine whether the presence of an elementary school in the neighbourhood of Howard County is a deciding factor to help them buy a house in that neighbourhood. A house with an elementary school nearby is convenient for parents having small kids. The attribute “geom” will help relate this dataset to the focal dataset. The dataset has 43 rows.
Howard County. (2014). Park Playgrounds [Data File]. Retrieved from https://data.howardcountymd.gov/

Dataset2:-
The third dataset that I decided to go for is named Park_Playgrounds. It is another factor that will help the users to decide whether to buy a house in the particular area or not. A family with toddlers or small kids would prefer living in an area where they can send their kids to the parks nearby. The attribute in focus here is “geom” that will help relate to the focal dataset. The dataset has 42 rows.
Howard County. (2014). Schools-Elementary [Data File]. Retrieved from https://data.howardcountymd.gov/

# Final dataset and citation:
The final dataset is named “ResidenceLocation” which is cited as:
Sneha Sahu. (2015). ResidenceLocation [Data file]. Retrieved from https://github.com/Sneha-Sahu/InfoOrg

# Processing Documentation:
The procedure of making the final dataset has been described in the doc named “Documentation”. It clearly lists down the steps taken to develop the final dataset by combining all the three csv files together into one. A few attributes of the files have been removed to simplify the dataset.  

# Question:
The question that can be answered from the combination of all three datasets (3-into-1 combination) is “Will the merged dataset help the potential users to decide whether or not to buy a house in a particular developing residential site keeping in mind the location of nearby elementary schools and parks?” It is very important for families having small kids to have this data as they would prefer living in a house that is close to parks and elementary schools so that it is easier for them to take their kids to parks in the evenings or drop them to school. 

# Representation of data:
The best way to represent the data would be by using interactive maps. The map can show the locations of the upcoming residential sites, the park and school locations using different balloons on the map. On clicking a balloon of a residential site, it can show the distance from the nearby parks and elementary schools and the mode of connection between those places.  

# Reason for selecting the files:
The reason for selecting these three files is that the three files very nicely gives the relationship between each other and complement each other. They can be related using the common attribute “geom” present in all the three sets. It is interesting to see how this combination helps users decide where to buy a house with respect to parks and schools around.

# License: 
The most appropriate license that can be used for the dataset is Attribution CC BY. This license lets others distribute, remix, tweak, and build upon your work, even commercially, as long as they credit you for the original creation. This is the most accommodating of licenses offered. Recommended for maximum dissemination and use of licensed materials.
