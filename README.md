# ABOUT THE DATASET 

**Description**

This dataset provides extensive information about Airbnb properties listed in Los Angeles, California. It offers a wealth of details suitable for analyzing short-term rental trends, exploring traveler behavior, and studying pricing dynamics within one of the most vibrant tourism markets in the U.S.

**Dataset Context and Purpose**

As Airbnb continues to impact urban rental markets, this dataset allows analysts, researchers, and real estate professionals to investigate how the short-term rental market shapes the local economy and influences housing availability. Users can leverage this dataset to perform location-based analysis, identify seasonal occupancy trends, and explore the popularity of amenities and property types.

**Content**

1. id: Unique identifier assigned to each property listing.
2. name: Property listing name as provided by the host.
3. host_id:Unique identifier assigned to the host of the property.
4. host_name:Name of the host associated with the property.
5. host_since:Date on which the host joined Airbnb.
6. host_response_time: Typical response time of the host to guest inquiries.
7. host_response_rate:Percentage of guest inquiries that the host responded to.
8. host_is_superhost: Indicates whether the host is a Superhost (True/False).
9. neighbourhood_cleansed: Neighborhood name where the property is located.
10. neighbourhood_group_cleansed: Standardized neighborhood group or district where the property is located.
11. latitude: Geographic latitude coordinate.
12. longitude: Geographic longitude coordinate.
13. property_type: Type of property.
14. room_type: Type of room offered (e.g., Entire home/apt, Private room, Shared room).
15. accommodates: Maximum number of guests that the property can accommodate.
16. bathrooms: Number of bathrooms in the property.
17. bedrooms: Number of bedrooms in the property.
18. beds: Number of beds in the property.
19. price: Total price based on minimum nights required for booking.
20. minimum_nights: Minimum number of nights required for a booking.
21. availability_365:Number of days the property is available for booking in the next 365 days.
22. number_of_reviews: Total number of reviews received for the property.
23. review_scores_rating: Average rating score based on guest reviews (5 is maximum value).
24. license: License, if applicable.
25. instant_bookable: Indicates whether guests can book the property instantly (True/False).

# DASHBOARD (MONGO DB ATLAS)
![Los Angeles Airbnb Listing](https://github.com/user-attachments/assets/a34b9105-d8de-455c-a19c-42758efa7cc3)

# INSIGHTS 

1. Prices by Property Type (Bar Graph)
**Question:** Which property type is the most expensive, and which is the most affordable?
**Interpretation** Entire home/apt" listings are the most expensive, whereas "Room in a hotel" appears to be among the more affordable options.

2. Top 5 Neighborhoods by Total Number of Reviews
**Question:** Which neighborhoods attract the most guest feedback?
**Interpretation:** Hollywood leads with the highest reviews, indicating its popularity among visitors. Venice and Santa Monica also see significant activity, likely due to their tourist appeal.

3. Distribution of Room Types
**Question:** What is the most common room type offered in Los Angeles Airbnb listings?
**Interpretation:** The majority of listings are "Entire home/apt," which suggests that visitors prefer privacy over shared spaces.

4. Top 5 Hosts by Number of Listings
**Question:** Which hosts dominate the market with the most listings?
**Interpretation:** Certain hosts, like "Blueground" and "Nicolas," manage a substantial number of listings, pointing toward professional or corporate management.

5. Average Ratings by Superhost Status and Instant Bookability
**Question:** Do superhosts or instant bookable properties have higher ratings?
**Interpretation:** Superhost properties and those with instant bookability generally score higher in ratings, implying a better guest experience.

6. Impact of Host Response Rate on Review Ratings
**Question:** Is there a relationship between host response rate and guest ratings?
**Interpretation:** Higher response rates tend to correlate with better ratings, emphasizing the importance of host responsiveness in guest satisfaction.

7. Responsiveness of the Hosts
**Question:** What is the average response time of hosts?
**Interpretation:** The graph indicates that the majority of hosts have relatively quick response times, crucial for enhancing guest trust.

8. Bedroom Availability Across All Listings
**Question:** How many bedrooms are typically available in listings?
**Interpretation:** One-bedroom properties dominate, indicating a preference for compact accommodations, possibly catering to solo travelers or couples.

9. Year-Round Availability by Accommodation Capacity
**Question:** How does availability vary with the size of accommodation?
**Interpretation:** Larger accommodations tend to have lower year-round availability, possibly due to higher demand for smaller, more affordable listings.

10. Correlation Between Price and Reviews
**Question:** Does a higher price correlate with more reviews?
**Interpretation:** There is no strong correlation; mid-range priced properties might have more reviews, suggesting affordability is a key factor in attracting guests.

11. Average Rating Across Listings
**Question:** What is the average rating across all listings?
**Interpretation:** The average rating is 4.75, indicating high overall guest satisfaction in the LA market.

12. Airbnb Property Locations by Neighborhood
**Question:** Which neighborhoods have the densest clustering of Airbnb properties?
**Interpretation:** Hollywood, Venice, and Santa Monica are hotspots, aligning with popular tourist destinations.

13. Hotspots for Airbnb Properties in LA
**Question:** What are the most popular areas for Airbnb properties in LA?
**Interpretation:** West Hollywood, Long Beach, and Downtown are highlighted, showcasing areas of concentrated activity.

14. Distribution of Properties by Instant Bookable Status
**Question:** How many properties offer instant booking?
**Interpretation:** The majority of properties support instant booking, making the booking process more convenient for guests.

15. Accommodation Capacity by Property Type
**Question:** What is the typical accommodation capacity for each property type?
**Interpretation:** Larger capacities are found in "Entire home/apt" listings, while shared spaces accommodate fewer guests.

16. Count of Properties Without a License
**Question:** How many properties lack proper licensing?
**Interpretation:** A significant number (7,075) of properties are unlicensed, raising questions about regulatory compliance.

17. Most Common Bathroom Count
**Question:** What is the standard bathroom availability in listings?
**Interpretation:** A single bathroom is the most common configuration, aligning with the dominance of smaller accommodations.





