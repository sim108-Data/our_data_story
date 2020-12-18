---
layout: page
title: Our travel through datas
---
# Social network mobility a mirror of our mobility through time

Hey ?! what's up every body ! Did you like the front cover! Petty neat isn't it ...
Yeah it's my first website so I'm pretty proud of it but enough talking about me. 
You know what else is also really neat ? You're right it's what we will show you in our datastory.
Before starting, let's talk about datas. In our case, we had in our possession two data set with all 
the check-ins made by the user of two Social Network: "Gowalla" and "Bright kite " In addition to that, a network with all the friend for each user of both Social networks 
was also provided.
Dataset which have geolocation can serve at a lot of things like finding the house and
know every movement of your worst ennemy... Just jocking. Don't do that. It's bad. Possible, but still bad. Anyway...

What's really great with the creation of social media like Gowalla or Brightkite 
is that you don't need to follow people anymore in order to know how human are moving! Still a joke don't follow people either. That's not a good move ...
Okay last joke...

Indeed by using those social networks we were able to study how the human moves and see if 
they were any pattern in their movement. You may want to click on the "Where it's started" in the sick cover page to 
discover more about the baseline of this datastory. In this paper, they compare Friendship and movement and they even
try to find a model in order to predict where the people are. With the help of this paper, we were able to recollect
the location of each user's home for both Gowalla and Bright kite. To help you overview, we grouped them by country and plot them on 
the world map. Don't hesitate to play with it. Note that by tourning the map really fast and them stop at once you may 
find your next place of vacation. Don't thank me, but if it's Hawai [please take me with you](mailto:simon.dayer@epfl.ch).
{%include user_by_country.html%}
As you can see a great proportion of the users live in the United States. We intend to investigate temporal patterns of people mobility. Furthermore, we study how 
external parameters ( such as temperature variance and holiday ) influence those patterns. As such aditive data is not available for different countries ( in homogeneous fashion )
So as we want to add other data set as the Temperature or to find the relation between movement and holiday.



## The take over of Gowalla and BrightKite in United states


In the last section, we 


The paper focuses on three main aspects of human mobility: geographic movement, temporal dynamics, and the social network. We propose to extend the temporal dynamic treatment from just the day/weekly timescale in the paper to look at an entire year. We will enrich our dataset by adding time series data about holidays, events, and regional weather patterns. Our hypothesis is that mobility patterns are influenced by these features. We expect to see large changes for holidays and events which are planned moments for mobility while weather patterns as an unpredictable phenomenon are expected to have a different and milder influence on the movement pattern. This will allow us to understand broader temporal trends in human mobility and periodicity and the influence of environmental factors such as weather (seasons) or natural disasters. The findings of these questions could be incorporated into a more detailed and robust model of human mobility.
{%include testhouse-of-user2.html%}





{:.note}salut
## Research Questions:
* Is there a significant difference in travel behavior between seasons (winter/summer/spring/fall)?

* Can we "visually" identify holidays/events/extreme weather and formulate a statistical test that distinguishes outliers?

* How does climate variation between locations influence movement patterns (places with cold/hot climates)?

## Proposed Datasets:
Dataset representing[ USA Cities latitude/longitude and states names](https://simplemaps.com/data/us-cities)

We will use this python package for [United States holidays.](https://pypi.org/project/holidays/)


<iframe src="..\assets\plots\kepler.gl.html" width="100%" height="600px"></iframe>