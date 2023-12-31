---
layout: post
title:  "Understanding the Evolution of NBA Player Performance: A Data-driven Exploration"
author: Byron Hillstrom
description: Intro to the Semester project   
image: "/assets/images/image5.jpg"
---

Understanding the Evolution of NBA Player Performance: A Data-driven Exploration
Introduction:
The world of basketball is dynamic, and the NBA has been a stage for some of the greatest athletes in the sport. To unravel the intricacies of player performance, I embarked on a data-driven journey to analyze NBA statistics from both regular seasons and playoffs. The primary motivation was to understand how player metrics have evolved over the years and whether there are notable differences in performance during the intense playoff matchups.

Research Question:
How have NBA player statistics changed over the years, and what distinctions can be observed between regular seasons and playoff performances?

Data Collection and Cleaning:
To answer this question, a comprehensive dataset was assembled by scraping data from the official NBA statistics website. Utilizing Python and the requests library, I pulled information on various player metrics, spanning seasons from 2010-11 to 2020-21. The dataset comprises over 300 observations, including informative features such as player ID, team, points scored, and more.
<img src="{{https://byronhillstrom.github.io}}/assets/images/scrape1.png"/>
<img src="{{https://byronhillstrom.github.io}}/assets/images/scrape2.png"/>

Cleaning the data was a crucial step in ensuring accuracy and consistency. Columns were normalized, missing values addressed, and unnecessary columns dropped. The dataset was enriched with derived metrics, such as shooting percentages and turnover ratios, providing a more holistic view of player performance.
<img src="{{https://byronhillstrom.github.io}}/assets/images/dataclean.png"/>
Ethical Considerations:
Web scraping raises ethical considerations, and it's imperative to approach data collection responsibly. In this project, I adhered to ethical principles by ensuring that the web scraping process was respectful of the NBA's website. Requests were made at a reasonable rate, and the collected data was used solely for analytical purposes. No private API keys or authentication information were used, and efforts were made to minimize any potential impact on the website's servers.

Concluding Statement:
This exploration into NBA player statistics is not just a collection of numbers; it's a journey through the changing landscape of the game. The dataset is now primed for in-depth exploratory data analysis, where we will uncover patterns, trends, and insights that transcend the individual numbers. As we delve into the nuances of player performance, we aim to gain a deeper understanding of the evolution of the game we love.

In the subsequent stages of this project, we will unravel the stories hidden in the data, exploring correlations, visualizing distributions, and identifying key trends. Find a link to the code [here](https://github.com/byronhillstrom/semester_project/blob/main/main.ipynb)
