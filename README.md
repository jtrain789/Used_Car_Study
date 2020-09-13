# Used_Car_Study
A Study on Used Car Data using R &amp; Python. 

## Executive Summary

Selling used cars online, using eBay, in Germany is difficult. The seller must self-list and price their vehicle without professional help. Most people price their used vehicles using Kelley bluebook, online searches for similar vehicle prices, or use intuition to price their cars. This leads to both overpriced cars that don’t sell and underpriced cars that undermine owner’s profit.  The research team believes that creating a predictive pricing model based on some vehicles attributes will make optimal pricing of used vehicles on eBay easier for private sellers. In order to create this model, the researchers used a database of 371,539 vehicles with 20 variables that were scraped from eBay-Kleinanzeigen between 3/5/2016 and 4/6/2016 (Leka 2016). This data was then cleaned, transformed and reduced to create a data set that included 292,425 observations and 16 variables. This data will be used to create the predictive pricing model that will offer pricing suggestions to eBay-Kleinanzeigen customers.
 
## Statement of scope 
This analysis is an investigation into what and how attributes of a used car listed on eBay-Kleinanzeigen in Germany affect a vehicle’s list price on the website. The goal of this analysis is to create a predictive pricing model using the available attributes scraped from eBay- Kleinanzeigen between 3/5/2016 and 4/6/2016. 
The main “autos” dataset includes 371,539 vehicle listings records. The second dataset “cnt_km_year_powerPS_minPrice_maxPrice_avgPrice_sdPrice” is an aggregation of the autos dataset sorted by horsepower (powerPS), year and odometer reading (km) which includes 1770 entries. 
The investigation will be in 2 phases. The first phase is data preparation, which includes: access, consolidation, transformation, and reduction of data, along with descriptive statistics. The second phase, model design and implementation include model selection, data splitting/sub-sampling, model execution and model assessment. 

## Project Objectives
•	Assess the effect of various used car attributes like mileage, horsepower, make, model type etc. on used vehicles listing price on eBay- Kleinanzeigen in Germany
•	Build models that predict used vehicle listing price based on the statistically significant vehicle attributes. 
•	Choose best price prediction model based upon a models least squared values.
