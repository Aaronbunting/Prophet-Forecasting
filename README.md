# Prophet-Forecasting

MercadoLibre Insights Unveiled

## Introduction
Embark on a journey of analysis and prediction within the captivating realms of MercadoLibre, a premier eCommerce platform reigning supreme in Latin America.

## Project Essence
This repository houses a project that unearths the patterns intertwined with MercadoLibre's popularity and sales data. Our aim? To not only fathom these patterns but also harness their predictive potential, thereby facilitating strategic decision-making of the highest order.

## Dataset Chronicles
Our analysis draws its essence from two vital datasets:

1. Hourly Google search trend data: A window into the popularity dynamics of MercadoLibre.
2. Daily historical sales figures: A canvas depicting the company's sales landscape.

## The Stages of Revelation
1. Initial Setup:
We begin by importing the necessary packages and dependencies. pandas for data manipulation, Prophet for time series forecasting, and the visual allies of hvplot and matplotlib for presenting our insights.

2. Data Importing and Cleaning:
The datasets are summoned and meticulously cleaned. Missing data is dealt with, dates are parsed, and indices are set to set the stage for analysis.

3. Initial Data Analysis and Visualization:
A preliminary dance with data unfolds, brimming with visualizations and insights. This serves as a compass guiding us towards the impending forecasting model.

4. Time Series Prophecy via Prophet:
The search trend data, having been scrubbed and readied, is fed into the hands of Prophet. This potent time series forecasting tool, hailing from Facebook's stable, dons the mantle of unraveling trends. As it forges predictions for the next 2000 hours, we dissect the patterns dictating MercadoLibre's popularity. We unearth the days and hours when the platform enjoys its zenith and the moments when it gracefully recedes into the shadows.

5. Illuminating Sales Prophecy:
Prophet is summoned yet again, this time for sales forecasting. This chapter mirrors its predecessor, but this time, it is the company's revenues that stand in the limelight. The seasonal patterns in revenue are unveiled, and peak revenue days are discovered.

The forecast we conjure not only reveals the most probable sales figures for the quarter ahead but also whispers about the best and worst-case scenarios. This symphony of insights is of immense value to the finance division, guiding budget planning and investor expectation management.

## In the End
This analysis stands as a testament to the mighty power of data-driven decisions. Our projections, insights, and patterns are the cornerstone upon which MercadoLibre can build a future of strategies guided by precision and knowledge.

## Prerequisites
To immerse yourself in this journey, ensure you have the following at your disposal:

- Python 3
- pandas
- fbprophet
- hvplot
- matplotlib

## Usage
To unravel this analysis, first ensure Python is at your fingertips, preferably through Anaconda. Next, arm yourself with the fbprophet, hvplot, and matplotlib packages.

Once your arsenal is ready, you can download the project and summon the Jupyter notebook.

Remember to keep the requisite data files (Google search trends and daily historical sales data for MercadoLibre) within the same directory as the Jupyter notebook.

Embark on this voyage of insight, prediction, and strategic enlightenment, as you traverse the landscape of MercadoLibre's intricate dynamics!
