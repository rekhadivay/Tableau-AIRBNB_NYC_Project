# Final-Project-Tableau-Airbnb NYC

## Project/Goals
### The goal of this project was to explore the information within Airbnb listings in New York City. Using Tableau, our objective was to craft compelling visualizations that highlight important insights and trends. Specifically, we concentrated on understanding the variety of room types available, comparing prices and bed quantities, examining and analyze price outliers based on different zip codes, analyzing neighborhood disparities in terms of room Types and average bed numbers, and Explore the trend of average prices over time based on the 'Host Since' duration.

# Process
## Step 1-Importing
#### We imported the .xls data file and reviewed all available columns to gain an understanding of the types of variables present. Our goal was to familiarize ourselves with the expected variables and ensure that each column/variable had the correct data type, whether it be string, integer, date/time, Geographic Roles etc.

## Step 2-Cleaning/Exploring
#### We took a casual look at the data, creating lots of pictures with different kinds of information to see if there were any patterns. We checked all the columns to understand what they were about, made sure each column had the right type of information (like words or numbers),checked and modify Data Type accordingly and fixed any missing information.

## Step 3-DashBoard and KeyPoints--
 1. Avg price based on Zipcode- What is the average price of each Room Type in different Zipcodes?
 2. RoomType distribution vs Avg Price- How is the popularity of RoomTypes impacting the average price, and how does this trend differ across various neighborhoods?
 3. Top Region(Bed availability)- Analyze the availability of beds in the top regions and its relationship with different room types.
 4. Avg price over time- Explore the trend of average prices over time based on the 'Host Since' duration
 5. TimeSeries-Price Forcast- can we create a time series price forecast based on the duration since the host joined?
 6. Outliers of prices based on zipcodes- Identify and analyze price outliers based on different zip codes.
 

## Step 4- Results/Answers
### We noticed that--
1. In specific Zipcodes, the average price was higher than in others.for example,in zipcodes 10309, 10302,10471. The NYC Airbnb dataset indicates that entire homes/apt are more expensive than other RoomTypes.
2. Entire homes make up the popularity in the NYC Airbnb dataset, with differences across neighourhoods.The top 5 room types with the highest average price , are all entire homes or apartments.
3. Examine the bed availability in the top regions and its connection with various room types. Notably, entire rooms have the highest bed availability espacially in Manhattan and Brooklyn neighborhoods which are top regions.
4. Look into how average prices have changed over the years based on when hosts joined. The highest average price, $177.8, happened in 2011, while the lowest, $145.5, occurred in 2015, marking the lowest since 2008.
5. We predict future price trends by considering how long hosts have been on the platform. The data reveals a steady growth with minor fluctuations in price since number of hosts joining from 2008 to 2015, and our forecast suggests a potential continued increase into December 2016.
6. When examining a box plot, we observed that the majority of prices fall between $0 and $5000. there are some prices that go significantly higher,after reaching up to $5,000, with one particularly unusual outlier at $10,000.

## Challenges 
1. Our biggest difficulty was trying to make a map of listings using zip codes and neighborhoods. Unfortunately, I found it challenging to use maps.Tableau couldn't recognize the zip codes to create a map. It would have been great to visualize a map with hotspots of listings. 

2. We wished to spend more time understanding the data, which could have led to improvements in our dashboard visuals or the discovery of new insights.

## Future Goals
#### If we had more time, we aimed to create a map of NYC depicting various neighborhoods with different levels of activity, focusing on factors like reviews and number of records. The map would consider elements such as price and the quantity of listings, offering a visual overview of Airbnb in the city.