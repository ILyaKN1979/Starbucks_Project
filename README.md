# The project - "Starbucks Project"

<a id="intro"></a>

## Project Introduction

The Starbucks Capstone Challenge is an integral component of the Udacity Data Scientists Nanodegree Program. 
This project encompasses several essential elements, including:

1) Establish an ETL pipeline.
2) Analyze and transform the original data.
3) Conduct exploration analysis and visualization.
4) Develop a data model capable of predicting whether the customer will accept the offer or not.

Dataset overview
* The program used to create the data simulates how people make purchasing decisions and how those decisions
are influenced by promotional offers. 

* Each person in the simulation has some hidden traits that influence
their purchasing patterns and are associated with their observable traits. People produce various events,
including receiving offers, opening offers, and making purchases.

* As a simplification, there are no explicit products to track. Only the amounts of each transaction or offer are recorded.

* There are three types of offers that can be sent: buy-one-get-one (BOGO), discount, and informational. 
In a BOGO offer, a user needs to spend a certain amount to get a reward equal to that threshold amount. 
In a discount, a user gains a reward equal to a fraction of the amount spent. In an informational offer, there is no reward,
 but neither is there a requisite amount that the user is expected to spend. Offers can be delivered via multiple channels.

* The basic task is to use the data to identify which groups of people are most responsive to each type of offer,
and how best to present each type of offer.


## Files

<pre>
.
├── Starbucks_Capstone_notebook.ipynb-# MAIN FILE 
├── report-Starbucks project.pdf------# Report
├── data
│	├── df_main.csv-------------------# Result  
│	├── portfolio.json----------------# Users (17000 users x 5 fields)
│	├── profile.json------------------# Offers sent during 30-day period 
│	└── transcript.json---------------# Event log (306648 events x 4 fields)
└── README.MD-------------------------# README FILE FOR PROJECT

</pre>
<a id="sw_lib"></a>

## Libraries

pandas, numpy, math, json, matplotlib, seaborn, sklearn

## Medium Blog Post
I wrote report-Starbucks project.pdf instead of the blog; I hope it works! 

