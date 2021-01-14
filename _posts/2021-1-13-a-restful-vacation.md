---
layout: post
title: A REST-ful vacation!
subtitle: Flask-API work by Dakota Porter
cover-img: /assets/img/travel.png
thumbnail-img: /assets/img/airbnb.jpg
share-img: /assets/img/cheers.png
tags: [api, flask, web application, airbnb]
---

I could use a vacation right about now. With a resource like AirBnB, the process behind that desire becomes quickly achievable. Who would have though that one day we could rent out our homes (if so desired) to visitors? Who would have thought that a second income was waiting for you in that extra bedroom? That's genius if you ask me. Plus, with the tips and tricks that come with computers and code nowadays, the insights we can draw from a place like AirBnB are beyond measurable. Iteration allows for improvement. That is the basis on which this project came to life.

![AirBnB](/assets/img/lux_airbnb.jpg){: .mx-auto.d-block :}

With my position of "full-time student at Lambda School", it's not surprising how a project like this landed in my lap. It's also not surprising that the second this mission was given, I didn't hesitate to accept it. Having been just over halfway through my journey at Lambda, it was about time a task of this magnitude came my way; a very real-world application with my hands fully on the wheel. With a paragraph or two of context and a rubric that was only there to make sure I had the bare minimum, this true portfolio piece was the perfect way to kick-off what I had learned in the months prior.

**Disclaimer:** This post is fairly technical in vernacular. So to anyone non-technical, feel free to read through, as it may not be overly complex to understand. If you desire to not be bored to death, you are more than welcome to just visit the website. The link is at the bottom of the page. 

## The Task

The goal behind this project was ultimately teamwork and communication. No doubt, it was a test of my knowledge and skillset, but being required to work with a group, rather than individually, made this a great challenge. The plan was to divide up the project's tasks among the group and delve into a real-world work flow. My task was creating the API (application programming interface or back-end) for our web application. Wanting to spread my wings, I did much of the front-end work as well (mainly in the form of HTML and a sprinkle of CSS).

Considering the true objective of this project (as aforementioned), a web application with "moving parts" and a machine learning model (or two) were the requirements. We planned on having a website that allowed a user to gain some insight into what it might be like if they rented out a property as an AirBnB. Having access to some data from AirBnB (chosen by my colleagues), we aimed to deploy some predictive modeling to evaluate that data and return an optimal price for said property. 

The prospect of building most of the functionality of a deployable web application sounds great. Having a time frame of one week makes it a little less appealing. However, I was more than ready. All the anticipation and excitement hadn't gone away from knowing about this project in weeks prior.

## My Process

Starting from scratch definitely was the hardest part with this project. There is a blank canvas waiting for you in your text editor and uou can take it in so many directions. Needing to get some momentum, however, I quickly put together the overall data and file structure of our project. Crafting some basic HTML pages that would link to the foundational URL endpoints was my first job. Tasks such as prepping a virtual environment and setting up a GitHub organization were ones I had dealt with in the past and therefore were completed fairly quickly. 

![Code](/assets/img/code.jpg)

To me, this is what my code looked like about halfway through. The process I had taken to put together the application was not nearly as time consuming as one would think. Enter the world of errors. Iteration over the HTML pages and creating tasks for the program to execute given POST data didn't go half bad. Environment errors and maintaining updated and correct data that was being shared between my colleagues and I were the tedious, and usually unexpected, faults.

Quickly enough (two or three days in), we had everything mostly functioning. My colleagues had continued improve on their models for more accurate pricing results. In the meantime, I had been going back and forth to present a more beautiful website and muster up a better way to navigate. Flask is very useful framework for this kind of project, but it doesn't come without it's complications as well. For our models and as a piece in our puzzle of tasks, a database was required to hold user input. Therefore, database management was a headache of a task. The database became central to our overall funcionality. 

When the due date entered the room (very suddenly at that), our mission was accomplished 

## Not Done Yet



![ABV graph](/assets/img/abv.png)             ![ABV zoom](/assets/img/abv_zoom.png) 



**CONCLUSIONS**

This web application was created with the intention of allowing a user who is interested in renting out a property as an AirBnB to enter their information and get back a predicted rent result for their property. A simple user-interface allows them to input only a few details and will immmediatly return results. In addition, a helpful search bar can help them navigate to other properties they have entered in the app. Take a look, click around and best of luck!

- Check out the code [here](https://github.com/dakotagporter/airbnb).
- Visit the website [here] **in progress**.
