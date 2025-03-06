# Restaurant Search & Recommendation System  

This project aims to design queries for a hypothetical application that helps users find restaurants that best match their needs. Using **MongoDB**, we manage a dataset of restaurants and reviews from **Google Maps**, focusing on businesses in **Hawaii**.  

## Dataset  
The data used in this project comes from [Google Local Data (2021)](https://mcauleylab.ucsd.edu/public_datasets/gdrive/googlelocal/), a public dataset containing:  
- **Review Information**: Ratings, text reviews, images.  
- **Business Metadata**: Address, geographical coordinates, descriptions, category details, price range, open hours, and miscellaneous info.  

This dataset provides data up to **September 2021** for businesses across the **United States**. In this project, we specifically focus on **restaurants located in Hawaii**, using their **metadata** and **K-core data for reviews** to ensure meaningful insights.  

## Key Features  
- **Data Cleaning & Processing**: Filtering relevant restaurants, handling missing data, and standardizing time formats.  
- **Efficient Querying**: Implementing various queries to search restaurants based on location, ratings, accessibility, payment methods, and more.  
- **Trust Index**: A metric to evaluate restaurant credibility by considering both rating and number of reviews.  
- **Geospatial Search**: Finding restaurants near a given location using MongoDB’s geospatial capabilities.  
- **Advanced Filters**: Identifying open restaurants, filtering by price, service options, and accessibility features.  

## Technologies Used  
- **Database**: MongoDB  
- **Data Processing**: Python  
- **Visualization**: Matplotlib, Seaborn  
- **Query Language**: MongoDB Aggregation Pipeline  
