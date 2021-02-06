---
layout: post
title: The Med Cabinet
subtitle: A Medical Marijuana Model by Dakota Porter
cover-img: /assets/img/weed_banner.jpg
thumbnail-img: /assets/img/leaf.jpg
share-img: 
tags: [marijuana, medical, nlp, web application, flask]
---

Talk about a hot topic. Marijuana has (figuratively) been on the table of the government for nearly the last 100 years. Not just our government either. This has been a global headache causing endless debates and circular judgment. The development of the weed world has come so far yet not very far at all. It's just a massive cliff-hanger that makes us wonder if we will ever come to an agreement. But what if we could make that headache go away? Maybe I can't solve the ups and downs of this here and now but, for people who have legal accessibility to these green gems, I may have something to help out.

![](){: .mx-auto.d-block :}

In a second round of [API work](https://dakotagporter.github.io/2021-01-13-a-restful-vacation/), I, and another colleague, have constructed a small web application that could hit the hearts of anyone entering the world of weed. More often than not, medical marijuana is used as an alternative for people who are hesitant about standard pharmaceuticals. There's a very similar debate surrounding supplements of this sort as well. With this application, we have cut some time out of the research process. We all have our opinions on pills or pot, but a simple interface to provide a new-comer with quick and accurate research and development may release some pressure off of this already heated conversation. The Med Cabinet implements this interface and aims to help customers retrieve quick descriptions of various strains of marijuana based on some simple input. Finding a [dataset](https://www.kaggle.com/kingburrito666/cannabis-strains) with over 2,000 strains of cannabis and their respective stats, our website has plenty of options and information for users to research from.

![The Med Cabinet](/assets/img/medcabinet.png){: .mx-auto.d-block :}

## 'High'ly Simplified

Off the bat, it's easy to list the things that weigh us down in our day to day lives. Back pain, restlessness and many other sticks in our sides can drag even the most upbeat of people to levels of pure competence. Finding solutions to these problems, however, can be quite difficult. Researching makes for a drawn out process that sometimes doesn't even lead anywhere. My partner and I have implemented various processes in our application to cut a few corners and make this task easier than can be. Our interface allows users to choose effects associated with various strains of cannabis that align with the issues they are aiming to defeat. More importantly, we have designed a description box where a user may enter a short summary of what they need help with or what they are looking for out of a strain of cannabis. As a result of these inputs, our behind-the-scenes algorithm will pull up the most accurate results to their queries. For someone who has no idea where to begin while diving in to this vast, smoky world can now explore with ease.

![X-Ray](/assets/img/xray.jpg){: .mx-auto.d-block :}

Now don't worry, for those who know exactly what they're looking for don't have to feel left out. If they want to just branch out or find other similar strains, we have provided a search option allowing users to search our entire data for the exact strain. In addition, a user may select from the three types of cannabis: Indica, Sativa or Hybrid amongst their search terms. These parameters can ping some more specific results aligning to a users desires. 

## Don't 'Leaf' Just Yet

What makes this app so fascinating is the functionality of the back-end. While my colleague designed seamless transitions between website endpoints and quick runtime while procuring results, I have expressed machine learning practices to retrieve user input and return desired outcomes. Specifically, Natural Language Processing accomplishes these tasks. A user-provided description is stored and manipulated for use during retrieval. The same process is done on the entirety of our data. During calculation, all of the strain descriptions (which are now represented numerically) are mapped out in space. Taking the user's description, we can now compare results and discover what strains can fulfill everything the user is asking for. A simple, yet productive model such as what I have implemented can harness so much power to make certain processes so much easier while remaining very accurate.



Visit the website [here](https://the-med-cabinet.herokuapp.com/).
View the code [here](https://github.com/lambda-med-cabinet/med-cabinet).
