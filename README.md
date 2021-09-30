#  HONGKONG AIRBNB ANALYSIS
The idea of Hong Kong Airbnb project came from the love of travelling and hope to find insights that might be helpful for future tourists when it comes to looking for an ideal place to stay during a vacation.

Link to Google Data Studio Report: https://datastudio.google.com/s/vvwHSmZbE78

## Dataset
The data was sourced from Inside Airbnb website http://insideairbnb.com/get-the-data.html.
The main dataset that was used for this project is named "Detailed listing data" under Hong Kong area in the website, which comprises of over 10000 listings.
Many data pre-processing steps were applied to the raw dataset including: Cleaning, Changing data type, Working with missing data, Checking duplications, mislabeled and corrupted data, Detecting outliers.

## Project Description
This project was done with contributions from 4 members in 2 weeks from collecting data, pre-processing, analyzing and presentation on GDS dashboard. Each group member was responsible for 1 aspect of a listing such as Host, Property type, Prices, or Rating & Reviews. The final insights were dispayed on GDS. My task in this project includes all steps of data-analysis pipeline mentioned previously on the Host aspect. On top of that, I also analyzed an additional feature in the data about Amenitites to understand about the services provided in different areas of Hong Kong.

## Outline
1. Determining Questions for analysis purpose
2. Data Collecting
3. Preprocessing
4. EDA
5. Google Data Studio Report

### 1. Questions 
1. Advantages an disadvantages of the different type of listings
2. Factors that tourists should look out for when booking AirBnB, in terms of hosts
3. What are the price range of the 3 location, are there any relationship between the price and rating, room type or room facilities
4. What is the main rating score for each of the top 3 locations? What and how every rating criterion performs itself in the dataset? How is the comparison among the top 3?

Finally, which location is the best in general when considering all 4 aspects?

### 2. Data Pre-processing
1. Removing unwanted data
2. Changing data type and dealing with missing data
3. Checking duplications, mislabels, and corrupted data
4. Detecting outliers

### 3. Explorative Data Analysis
Some examples of my pre-processing and EDA steps:

![Pre-processing](https://user-images.githubusercontent.com/84905432/135478163-91a15f57-31a9-40ba-9e16-23806b080065.png)

- There were > 1000 missing values in both "Host_response_time" and "Host_response_rate" columns
- Those missing values were filled in based on whether the hosts are superhost or not, the mean values were computed for superhost and not-superhost groups and fill in correspondingly

![Amenities](https://user-images.githubusercontent.com/84905432/135466115-9cc812d3-ed8f-4858-9ce6-14406f736324.png)

- This plot shows the availability percentage of some of the most common amenities 
- Wifi and Air Conditioning are provided by almost every listing
- Most noticable difference is Elevator and Kitchen 

### 4. Google Data Studio Report

![image](https://user-images.githubusercontent.com/84905432/135481566-8932f544-b7d1-4327-9f96-0b4f6472af22.png)

## Conclusion

By analyzing several different aspects of Airbnb listings in 3 central areas Yau Tsim Mong, Wan Chai, Central & Western of Hong Kong, our team was able to provide information about the pros and cons of each area in terms of different aspects including Hosts, Services, Property types, Prices, Rating & Reviews.

In order to better assist in searching for an ideal listing, we also plotted a map that takes in input from a tourirst about number of beds, people, room type, etc. which they are looking to stay and outputs the link to the listing on the map

Overall, Yau Tsim Mong would be the best location to stay in Hong Kong because it has the most affordable prices, higher ratings, most number of listings, and diverse property types.
