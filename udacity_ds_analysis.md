![Seattle](/docs/assets/imgs/seattle_image2.jpeg)


<p align="center">
  <a href="https://ar.wikipedia.org/wiki/%D9%85%D9%84%D9%81:Space_Needle002.jpg">Image Source</a>
</p>



# Seattle : Do Business & Have Fun !


QQQQQ
Seattle is one of the tourist attractions in Washigton. In Seattle, you could visit the [Space Needle](https://www.spaceneedle.com/), the [Art Museum](https://www.seattleartmuseum.org/), the [Aquarium](https://www.seattleaquarium.org/), and many more !

Being such an attraction, it is only natural it would attract the attention of three types of people
* Marketing Real-estate companies (looking to **sell** places in Seattle)
* Landlords (directly offering places for **rent**)
* Tourists (looking to visit and have fun!)

In this blog post, I am trying to provide one useful insight for every one of the above categories, based on my analysis of the [Seattle Airbnb Open Data](https://www.kaggle.com/airbnb/seattle)

## (1) : For Real-Estate Companies
### As a real-estate company selling houses in Seattle, where should I focus my marketing campaigns ? 

To answer this question, I decided to find out where property owners in Seattle are most likely to live.

I assumed that if a lot of people in place X regulary buy properties in Seattle, then the company should focus its marketing campaign in the same place X.
It was a bit of an extrapolation on my side to assume that the trend will continue as is, and I do realize that other business analysts might decide exactly on the opposite of that, arguing we should expand to markets where very few people have properties in Seattle. **I simply beg to differ !**

Anyway, following my assumption, I found that roughly 87.37% of property owners in Seattle actually do live in Seattle themselves. This shows that the company should still put most of its campaigning effort in Seattle itself!
The remaining 22.73% were distributes accourding to the following pie chart : 
![Distribution Of Property Owners In Seattle Who Live Outside Seattle](/docs/assets/imgs/pie.png)

Accourding to my assumption, this could be a rough estimate of the distribution of marketing effort the company should do. 
i.e, the company should put most of the effort in Seattle, followed by Spokane, Kent, Los Angeles, and so on.

## (2) : For Landlords
### As a place owner in seattle, which renting model should I use to maximize my average profit ?
#### Should I rent the entire place? single rooms? shared rooms? Should I allow pets ? Should I allow refunds ?

To answer this question, one must analyze different rental models, and find out which model achieved maximum average revenue per year for property owners.
Unfortunately, when I looked into the dataset, I did not find information on whether a specific property was rented (i.e, making money) at each specific day or not.
Without this piece of information, I was unable to answer the question or recommend any specific model to landlords.


**Sorry, landlords !**\



<p align="center">
  <img style="float: right;" src="/docs/assets/imgs/failed2.png">
</p>


<p align="center">
  <a href="https://www.deviantart.com/ryanthescooterguy/art/Dexter-I-Have-Failed-You-base-574912964">Image Source</a>
</p>
  
  
 
## (3) : For Tourists
### As a tourist who travels alone with low budget and flexibility of free time, (a) which month of the year would be cheapest for me to have a vacation in Seatle ? Also (b) which neighbourhood should I target if I am not so picky ?

Well, this one is easy. To answer this question, let's look at historical data and find out which neighbourhood is cheapest per month, which month is cheapest per neighbourhood, and the which combination is cheapest overall ! 

The following figure shows the average price per neighbourhood per month, limited only for places that accommodate a single person.\



![avg price per month per neighbourhood](/docs/assets/imgs/distrib_1.png)

<br>
While this graph is useful on its own, it is too noisy. Let's actually limit ourselves to neighbourhoods that happen to be cheapest at any given month.
Doing this, we get the following graph.\



![avg price per month per neighbourhood filtered](/docs/assets/imgs/distrib_2.png)

This graph clearly shows that Magnolia is the cheapest possible neighbourhood all year round except for March & April, where Northgate is cheapest.
**The cheapest possible combination would be Magnolia in January. Have fun, frugal tourist !**


By this, I get to the end of my post. I hope you found it insightful ! 

**Landlords, I owe you one !** Once sufficient data is available, I will come back to you :wink:

