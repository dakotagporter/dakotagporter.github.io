---
layout: post
title: Beer Me the Numbers
subtitle: Beer Math by Dakota Porter
cover-img: /assets/img/tap.jpg
thumbnail-img: /assets/img/square-beer.png
share-img: /assets/img/cheers.png
tags: [beer, brews, statistics]
---

The crisp and refreshing taste of an ice cold brew is unlike any other beverage on the menu. What are some ways to represent a beer and it's attributes with statistics and math? This is the burning question everyone wants to know while sipping the nectar of the god's. Okay, so maybe it's not, but let's do it anyways!

![Flight](/assets/img/national-beer-day-ipa.jpg){: .mx-auto.d-block :}

## What do we want to know?

The self-proclaimed "go-to resource for beer", a website known as [Beer Advocates](https://www.beeradvocate.com/), contains all your resources for beer descriptions and discussions. Even you can take part in the brawl of the brews. Beer Advocates is the home for millions of ratings and reviews on any beer you could possibly imagine.

I took just a small sample of that data to create a few calculations of my own. The dynamicism of data that can be squeezed out of a handful of wheat-fueled evaluations is quite interesting. In all seriousness, however, I truly wonder if the trends of the beer world are actually true. Are IPA's really the most sought after beers? Does a beer's taste (seemingly it's most controversial property) actually influence how someone rates or reviews a beer overall? How confident are we that we are drinking as much alcohol as we think we are?

## The Bitter Results

To figure this out, I gathered a [dataset](https://www.kaggle.com/rdoume/beerreviews) from Beer Advocates containing just under 1.6 million reviews on miscellaneous beers from around 5,000 different breweries and immediately 'hopped' into my work. I conducted multiple tests to answer some of these questions. My findings caught me off guard yet intrigued me to no end.

![Review_Count](/assets/img/review_count.png)

Finding the most revered style of beer seemed like the logical place to start. Filtering through all of the data, the classic IPA brought a shout out. The graph on the left shows the top 10 beer styles that had the highest review count from this dataset. Out of these elite chart-busters,  it's clear that IPA's claim top trumps. The American IPA and the American Double IPA make up a whopping 13.1% of all reviews from this dataset. Now, if you're anything like me, that news is not surprising but is just asking for further evaluation on each review on these piney pints. India Pale Ale's are definitely not my cup of beer but, according to my conclusions thus far, I may be missing out. 

**A Tasty Surprise**

The review process for Beer Advocates allows for a half or full star rating from 1 to 5 stars for the chosen beer. I devised a test to see if each person's overall score was usually the same as how they rated the beer's taste. By analyzing reviews on only American IPA's, I could try to determine if the taste scores were high or low in respect to the overall rating of the beer itself.

![Brewery](/assets/img/brewery.jpeg)

Many of the breweries from the dataset had multiple reviews of the same beer. For this test, I chose only the breweries with over 1,000 reviews on their American IPA to make sure there would be enough observations to find a solid average. I assumed that, in general, the average overall score for each beer would be about the same as the average score given for it's taste. However, as I mentioned earlier, my results were a surprise. I found that the average scores for the two categories were not the same. I guess branching out may not be so bad after all. If people agree that the taste is great but overall feel like the rating is low, there may at least be a chance that I can add a new brew to my repertoire.

{: .box-note}
**Quote:** "Whoever drinks beer, he is quick to sleep; whoever sleeps long, does not sin; whoever does not sin, enters Heaven! Thus, let us drink beer!" - Martin Luther


This well-rounded German gentleman has definitely got the idea. However, I'm not so sure Martin Luther had the technology in his time to elaborate on his hypothesis. Instead, let me see what I can come up with.

Whether, we are told, or just want to believe, our consumption of alcohol per drink is 'responsible', it's time to use some math to see how long we really could sleep if we lived on the edge like Luther. Each beer in this dataset contains a respective abv percentage (alcohol by volume, if you don't already know). If we look at [Live Science](https://www.livescience.com/32735-how-much-alcohol-is-in-my-drink.html#:~:text=On%20average,%20the%20ABV%20for,how%20each%20beverage%20is%20made.), we are told that an average 12oz beer has an abv of 4.5%. Let's see if our actions live up to the expectation.

![ABV graph](/assets/img/abv.png)
![ABV zoom](/assets/img/abv_zoom.png) 

I took a list of 104 different styles of beer from the data to calculate an average abv content across the full range of recipes. The graph above shows the distribution of the alcohol content for each kind of beer. It's clear to see that most of the beers have an abv percentage of around 5%. At first glance, this boosts our confidence that we are officially consuming a 'healthy' amount of alcohol. However, when we take into consideration all the beers with an abv higher than 5%, our mean (or average) abv is pulled further to the right. In calculation, I found the true mean to be between 6.04% and 6.06%.

The second figure is a portion of the graph above that has been magnified to see the range (the space between the red lines) where most of the average abv contents will fall. After a given estimate of 4.5%, I think we all might want to pay a little more attention to the label on the can next time we crack open a cold one. Although it may seem like 5% beers are more common, you may most likely find yourself sipping on a spikier brew than you expected.

**Check Please**

In conclusion, let's just remind ourselves that when a beer is put in your hand, just drink it. However, the next time that one of these cool, crisp beverages slides down your throat, maybe you can have a little more insight as to how the trends of the beer world hold up. IPA's seem to top the charts but can you really trust what other people say? Or do you just have to start a tab and find out on your own?
