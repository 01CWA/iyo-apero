---
title: Increase Cyclistic's bike-share ridership
subtitle: "Google Data Analytics Capstone"
excerpt: "  "
author: Carol Addassi
date: '2021-08-07'
slug: []
categories:
  - Case Study
tags:
  - case-study
  - capstone
---
![bike-share bike rack](images/featured-hex-s.jpg)

## Case Study: How Does Cyclistic Bike-Share Navigate Speedy Success?

**Goal**: Design marketing strategies that convert casual riders to annual members.

**Why**: Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. 

**How**: Help our marketing analytics team **better understand how annual members and casual riders differ (the scope of this document)**, why casual riders would buy Cyclistic annual memberships, and how digital media could affect marketing tactics. Key to this is analyzing the Cyclistic historical bike trip data to identify trends.

**About this case study**: This is my capstone project for my [Google Analytics Professional Certificate](https://coursera.org/share/ca837b41716199898aa3b07a048cff41).

Cyclistic, the fictional company used for this analysis is on based on the Divvy case study ["Sophisticated, Clear, and Polished’: Divvy and Data Visualization" written by Kevin Hartman](https://artscience.blog/home/divvy-dataviz-case-study). A very detailed R script was provided by him which I used with modifications.

After doing initial data familiarization and analysis in Excel using the most recent 12 months of historical data based on the [comprehensive case study instructions provided by Google](https://www.coursera.org/learn/google-data-analytics-capstone?specialization=google-data-analytics), including preliminary data organization, cleaning, and transformation which involved calculating new variables and summarizing data with pivot tables, I chose to continue my final analysis and data visualizations in R. Please see this [changelog](https://drive.google.com/drive/folders/1bVWHD_N-rAuUlp3Y2_3mJQqqmO6AfrCc) for details.

**Data sources**: Although Cyclistic is a fictional company, the public data used has been made available by Motivate International Inc. under this [license](https://www.divvybikes.com/data-license-agreement). Please note that data-privacy issues prohibit usage of riders’ personally identifiable information. This means that past purchases may not be connected to credit card numbers to determine if casual riders live in the Cyclistic service area or if they have purchased multiple single passes.

**Additional credits**: Huge thank you's to Google and all of their wonderful instructors who created this super-beneficial program. Besides the incisive and engaging original content, they provided copious resources for deeper dives in all phases of the data analytics project life cycle.

Specifically for this capstone project, finding [KaptainTech's video](https://youtu.be/cpUVV8q7WNo) which shows how to measure distance in Excel using longitude and latitude coordinates was immensely helpful. (The distance is measured between points, not driving directions. Even so, it provided context for comparing miles traveled between casual riders and annual members.)

### How do annual members and casual riders use Cyclistic bikes differently?

- Who uses the service more often, annual riders or casual riders?
- How does ride length differ between the two types of riders?
- Are there patterns in the time of day rides take place that differ between annual members and casual riders?
- Are there seasonal patterns that differ between annual members and casual riders?
- Are there specific stations that casual riders begin and end from more than annual riders?
