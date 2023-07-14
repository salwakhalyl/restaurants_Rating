Dataset README
Introduction
This dataset contains three Excel files related to restaurants: "Restaurant Cuisines," "Restaurants (Characteristics and City)," and "Rating." The purpose of this dataset is to explore and answer several questions related to the highest-rated restaurants, consumer cities, potential biases in the data sample, and the characteristics to consider when investing in a restaurant.
Files
1.	Restaurant Cuisines: This file contains information about the cuisines offered by different restaurants. It includes details such as restaurant ID and the cuisine type.
2.	Restaurants (Characteristics and City): This file provides information about various characteristics and the city of each restaurant. The attributes included are restaurant ID, city, alcohol availability, smoking allowance, price range, and parking availability.
3.	Rating: This file contains ratings assigned to each restaurant, identified by their restaurant ID.
Questions to Answer
1.	What can you learn from the highest rated restaurants? By analyzing the highest-rated restaurants, we can gain insights into the characteristics that contribute to their ratings.
2.	What are the consumer cities? Does this indicate a bias in the data sample? Determining the cities where consumers are located will help identify any potential bias present in the data.
3.	If you were to invest in a restaurant, which characteristics would you be looking for? Understanding the key characteristics that positively influence restaurant ratings can guide investment decisions.
Methodology
To answer these questions, the following steps were followed:
1.	Calculating average ratings: A pivot table was created to find the average rating for each restaurant based on its ID.
2.	Combining data: Using the VLOOKUP function, the average rating for each restaurant was merged with its corresponding cuisine, city, alcohol availability, smoking allowance, price range, and parking availability.
3.	Visualization in Tableau: The combined dataset was imported into Tableau, where six graphs were created to provide insights and answer the questions.
Key Findings
Based on the analysis of the data using Tableau, the following conclusions were drawn:
1.	Characteristics of highest-rated restaurants: The highest-rated restaurants predominantly offer Brewery cuisine, serve wine and beer, provide valet parking, and have a designated smoking section. Additionally, there is a positive correlation between price range and rating, indicating that higher-priced restaurants tend to have higher ratings.
2.	Consumer Cities: The dataset reveals the distribution of restaurants across different cities. Specifically, there are 62 restaurants located in San Luis Potosi, 19 in Ciudad Victoria, 12 in Cuernavaca, and only 2 in Juitepec.
Bias Consideration
Determining whether there is bias in the data sample requires further examination. The dataset provided does not explicitly capture information about consumer demographics or their preferences. To ascertain bias, additional factors such as population size, consumer behavior, and restaurant density within each city should be considered. Further investigation is required to draw definitive conclusions regarding potential bias.
Conclusion
Based on the analysis, investing in a restaurant with Brewery cuisine, wine and beer service, valet parking, a smoking section, and higher price range may increase the chances of success. However, it is essential to conduct a comprehensive analysis considering various factors beyond the scope of this dataset to make an informed investment decision.
