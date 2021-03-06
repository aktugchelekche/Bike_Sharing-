# NYC Bike Sharing

A business analyst with Pandas and Tableau. 

## Project Overview

### Purpose 
In this project I am utilizing Pandas for cleaning the dataset and Tableau for visualization the dataset regarding  bike sharing analyst in New York City. Thus I will be able to provide with more information about the mechanics of the business and figure out how the bike share business actually works in NYC. The goal is to modify the model then  apply the similar model to other cities and expand the operation.

#### Full Story of Tableau Analysis :[NYC Citi Bike Sharing](https://public.tableau.com/app/profile/aktug/viz/NYCCitiBikeSharing_16514969088580/Story1?publish=yes)

## Results 

###  Summary Information

<p align = "center">

<img width="80%" alt="Screen Shot 2022-05-07 at 5 09 02 PM" src="https://user-images.githubusercontent.com/98676400/167273327-1a4e5ddf-c9b3-4057-8a3d-ab8a493679a7.png"> 
<p align= "center">Chart-1</p>
</p>


First Part of Story in Chart-1 presents following information:

* Type of business, time frame and location of the data: CitiBike, New York City, August 2019.
* The total rides: 2,344,224.
* Customer type: subscribers and customers.
* Peak hours by gender.

#### Checkout Times for Users

<p align = "center">

<img width="70%" alt="Screen Shot 2022-05-07 at 5 09 02 PM" src="https://user-images.githubusercontent.com/98676400/167273419-2aa0ab26-dd12-4357-99fb-8e1f4214fe16.png"/> 

<p align= "center">Chart-2</p></p>

In Chart-2 number of trips duration show that the majority of trips taken on CitiBike bikes are under an hour in length. In fact, most trips are under a half-hour and  with a drop in number of rides over an hour in length.

#### Check Out Time by Gender
<p align = "center">
  
<img width="70%" alt="Screen Shot 2022-05-07 at 5 17 08 PM" src="https://user-images.githubusercontent.com/98676400/167273517-0070a2c9-e036-47c4-b0aa-06a00c56c2a7.png">
<p align= "center">Chart-3</p>
</p>

Chart -3  shows number of checkout bikes versus trip duration. Trip duration is divided into minutes (at the top). Yellow represents male, blue represents female and red represents the unknown gender. We can observe that checkout times for male is dominating, especially between 1hour to 10hours checkout time duration.
#### Trips by Weekday per Hour
<p align = "center">

<img width="70%" alt="Screen Shot 2022-05-07 at 5 21 13 PM" src="https://user-images.githubusercontent.com/98676400/167273607-2866170e-25fd-45e1-9a55-2358e58db052.png">
<p align= "center">Chart-4</p>
</p>

In Chart-4, number of trips per hour during weekday. The color indicates the number of trips. As color get darker, number of trips increase, while lighter color indicates less trips. Form the graph we can see that the busiest times are in the morning hours on weekdays from 6am till 9am and in the evening hours on weekdays between 5 pm and 7 pm.

#### Trips by Gender (Weekday per Hour)
<p align = "center">
<img width="70%" alt="Screen Shot 2022-05-07 at 5 30 40 PM" src="https://user-images.githubusercontent.com/98676400/167273897-ba660da7-5fd5-49e5-b2cb-fe336fdb80c5.png">
<p align= "center">Chart-5</p>
</p>

Chart-5 was generated after dividing Chart-4 by gender. It appears that there is a uniform distribution regarding busiest hours which is 5-7pm and 6-9am for all genders. During weekends the busiest hours shift to 10 am and 6 pm. As previously stated males have significantly higher numbers than other genders. 

#### User Trips by Gender by Weekday
<p align = "center">
<img width="70%" alt="Screen Shot 2022-05-07 at 5 41 10 PM" src="https://user-images.githubusercontent.com/98676400/167274128-8f7dabed-4ff3-47e1-9720-df522bdf3032.png">
<p align= "center">Chart-6</p>
</p>

In Chart-6, male has the highest number of the trips on Fridays and Thursdays as well as on Monday and Tuesdays. Although  significantly lower number of trips than male, female have similar trips days. 


#### Top Starting Locations & Top Ending Locations

<p align = "center">
 <img width="70%" alt="Screen Shot 2022-05-07 at 9 24 07 PM" src="https://user-images.githubusercontent.com/98676400/167279839-c82afbee-34b9-4261-bc04-a1fc471b114e.png">

<p align= "center">Chart-7</p>
</p>

According heatmap in Chart 7 , downtown area appears to be most popular area to start and end a journey. We can not denied that surrounded of the downtown seems to be attractive for bike rides as well. 

# Summary 
There are quite a few summary can be done with above visualizations however 3 of them are more important than the others as to sustainability and profitability most imperative for a business. 

#### 1. Female Subscribers/Customers :
It is obvious that there is a need for a new business plan to attract females to utilize bikes more than it is . There are couple of ways to reach them out as one would be have survey to find out what needs to be done to capture more female customers. In popular European cities, the use of electrical bikes among females are increasing significantly, also making colorful designs and creating females friendly events ,social activities would help the business reach the target group. 

#### 2. Male Subscribers/Customers :

Without any doubt, males are the backbone of this model. Sustain then increase number of male users most fundamental for the revenue. We need to make sure that bikes are clean, well maintained and ready for their trips during morning and evening times which are the mostly male users trip times. 

#### 3. Bike maintenance
From trip times we can interpret that some bikes are used much more than others. We need to make sure to keep track on those been user more than others to rotate to less busy stations so that maintenance can be perform routinely. This will give a good idea for future purchase which type of bikes are preferred from out users. 

### Suggestion :

1.  Total trip, by birth year. This would help us to find the target group and reach them via social media, mail , phone to inform them  about the model we are implementing in the city. 
2.  The visualizations we have is for August. Comparing different months to determine trends over the year. 
3.  Trip duration on different weather condition. 


### Resources 

* Data Source:
  * CitiBike Trip History Data from August 2019 in NYC
* Software:
  * Tableau Public 2020.3

* Languages & Environment:
  * Pandas, Python 3.7
