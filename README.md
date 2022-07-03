# BikeSharing

Created multiple dashboards and a story to analyze and visualize citi bikes data utilizing Tableau and Python.

## Overview

The Module 14 projected consisted of creating a pitch for a citi bike business proposal to angel investors looking to seek funding.  The goal was to look at the Citi Bike data in New York City for one month (August) to see how bikesharing business operates in its prime during the summer.  After analyzing the data, I then created visualizations to display the trends and opportunities it would have in other cities.

## Resources

- Dataset
  - Download the `201908-citibike-tripdata.csv.zip` from this [CitiBike link](https://s3.amazonaws.com/tripdata/index.html)

- Software
  - Python
  - Pandas Library
  - Tableau Public

## Results
[Tableau Public Story](https://public.tableau.com/app/profile/zach.diercks/viz/Module14Challenge-CitiBike_16568702035020/NYCCitiBikeStory)

This presentation was based on New York City but could be applied, with the necessary attention, to other cities in the World.

![webpage](https://github.com/diercz/bikesharing/blob/main/Images/Rides%20Per%20Hour.png)

The most profitable month, August is what we focused on and found that the most bike rentals were at 8:00 am and between 4:00-6:00 pm.  You could possibly assume that these riders are utilizing the bikes before and after work by these peak times.  

![webpage](https://github.com/diercz/bikesharing/blob/main/Images/Rides%20Per%20Day.png)

This heatmap supports our theory as it displays how the most popular ties are at 8:00 am and in the later afternoon/evening hours.  It provides the additional information such as that Thursday is the most popular day of the week and that Saturday and Sunday afternoons are also very popular.

![webpage](https://github.com/diercz/bikesharing/blob/main/Images/user%20trips.png)

From the image above and viewing the dashboard created you can see that almost 80% of the users are subscribers, meanwhile the others are customers who sometimes rent from Citi bike.  This shows to expect high retention rate wherever the business is created and we should strive to give incentives for customers to become subscribers.  Male subscribers are the most popular of the gender types that utilize Citi Bike.  

![webpage](https://github.com/diercz/bikesharing/blob/main/Images/Trips%20by%20gender.png)

The image above shows the gender breakdown by hour of rental per day.  Majority of the customers are male with approximately 60-65% of the market share, women with 25%, and unkown with 10%.  All three gender types appear to have similar heatmaps meaning they are utilizing the Citi Bike rentals at similar times.

![webpage](https://github.com/diercz/bikesharing/blob/main/Images/Start_End%20locations.png)

The last image shows the start and end locations for the Citi Bike users.  You can see that the majority of the rentals occur in high densily populated areas, in this example Manhatten.  But, we can be safe to assume that most cities would follow suit with this trend.   If possible, we could provide lower rates for less densily populated areas to incentive more rentals.  

## Summary 

![webpage](https://github.com/diercz/bikesharing/blob/main/Images/Customer%20vs%20sub.png)

Overall, the data that was analyzed shows us many trends in New York City that we can assume would follow suit in other larger market areas.  What we found was that users are typically Male and that users tend to utilize Citi Bikes at 8:00 am and 4-6:00pm.  Are users tend to be 25-35 years, but have an outlier at 52 years of age for "unkown" gender with over 200,000 rides.  Further investigation would be beneficial to determine what occurred for this larger # of users and was there a specific time frame these rentals occured during.  Another interesting metric to analyze would be if users use the bikes for daily commutes, leizure, or rarely.  This could then tell us more and how we can engage with our customers and have them become subscribers.  We could then analyze by gender, age, and other metrics to understand the market better.  