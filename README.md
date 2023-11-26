# Airbnb-Data-Exploration
# Airbnb Property Analysis Portfolio

## Introduction
This project explores various aspects of Airbnb property listings, providing insights for both hosts and guests. The analysis covers topics such as accommodation types, neighborhood pricing dynamics, the impact of amenities, and correlations between different factors.

## Questions Explored
### Question 1:
**Accommodation Types Overview**
The analysis uncovers the most common types of accommodations listed on Airbnb.

### Question 2:
**Neighborhood Pricing Insights**
Exploring average prices across different neighborhoods reveals valuable information for hosts and guests.

### Question 3:
**Correlation Between Reviews and Satisfaction**
A positive correlation is identified between the number of reviews and overall satisfaction ratings.

### Question 4:
**Property Type Distribution Over Time**
Visualizing property types over time provides insights into evolving trends in the Airbnb landscape.

### Question 5:
**Impact of Amenities on Listing Prices**
The analysis highlights how the availability of amenities influences listing prices.

### Question 6:
**Relationship Between Bedrooms and Price**
An exploration of the relationship between the number of bedrooms and listing prices.

### Question 7:
**Host Response Time and Satisfaction**
Insights into how host response time correlates with overall satisfaction ratings.

### Question 8:
**Property Size Trends Across Neighborhoods**
Identifying trends in property sizes based on neighborhood dynamics.

### Question 9:
**Correlation Between Description Length and Price**
Understanding how the length of listing descriptions correlates with booking prices.

### Question 10:
**Impact of Minimum Nights Requirement on Booking Frequency**
Examining how the minimum nights requirement affects booking frequency.

## Visualizations
### Visual 1: Property Type Distribution Over Time

```python import matplotlib.pyplot as plt

# creating the bar plot
ax = property_type_distribution_over_time.unstack().plot(kind='bar', stacked=True, figsize=(12, 6))
plt.title('Property Type Distribution Over Time')
plt.xlabel('Year')
plt.ylabel('Count')

# Move legend outside the plot
ax.legend(loc='upper left', bbox_to_anchor=(1, 1))

plt.show()
```
### Visual 2: Relationship Between Bedrooms and Price
[Insert Code for Relationship Between Bedrooms and Price]

### Visual 3: Host Response Time vs. Overall Satisfaction Rating
[Insert Code for Host Response Time vs. Overall Satisfaction Rating]

### Visual 4: Impact of Minimum Nights Requirement on Booking Frequency
[Insert Code for Impact of Minimum Nights Requirement on Booking Frequency]

## Conclusion
The analysis provides a comprehensive understanding of Airbnb property dynamics, offering actionable insights for hosts to optimize their listings and for guests to make informed choices. The combination of quantitative findings and visualizations enhances the overall experience within the Airbnb ecosystem.


