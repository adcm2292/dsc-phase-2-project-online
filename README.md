# Phase 2 Project: Your Dream Home


### Scenario

Build a model that predicts house prices, using data of the King County, WA houses sold in 2014 and 2015. 


### Business Problem

We are a Real State startup.

* Our target market:
 first time home buyers and 
 people looking for an upgrade or change of scenario (trade in your current home)

* What we want to offer:
    * We buy, sell and offer customers the possibility of trading in their current home (like with your car!)
    * We are a startup that offers convenience and certainty to busy people who don’t want to have to deal with home listings and all the headaches that go along with that.

To obtain a meaningful model we must consider:

* What to look for when buying a home?
* What makes a residential property more expensive? (Location, Number of Rooms, Condition)
* Where are the most expensive houses located?
* Price per number of rooms (bedrooms/bathrooms)
* Price per sqft
* How does the condition of a property influence the price?
* How do year built and renovations influence the sale price?



###  Notebooks

* n0: Obtaining, Cleaning and Scrubbing our Data.
* n1: EDA: comparing each feature to our target variable: 'price'
* n2: First model trial. Features: 'sqft_lot', 'waterfront_1', 'distance_seattle', 'property_age'
* n3: Best fitting model. Features: 'sqft_living', 'distance_seattle', 'property_age'
* n4: Adding 'waterfront_1' 
* n5: Adding 'renovation_1'


### Conclusion


* Our Best Model indicates that we could effectively predict the price of a house in around 92% of observations when we use the following features:
    * Size: footage of the home (living space).
    * Location: distance from the center or economic hub.
    * Property Age: how many years ago a house was built.

