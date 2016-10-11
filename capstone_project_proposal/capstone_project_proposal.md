# Capstone Project Proposal
_Trent Casey: Springboard Data Science Intensive_

### What is the problem you want to solve?
Can the sale price of a single-family home in Denver, Colorado be predicted using features of the house such as number of bedrooms and whether it has a fireplace along with details of it's neighborhood like crime rate?

### Who is your client and why do they care about this problem? In other words, what will your client DO or DECIDE based on your analysis that they wouldn’t have otherwise?
My wife and I are seriously considering moving to Denver, Colorado within a year and have been looking at houses in the area on an almost daily basis. We have some friends in the area who are happy to give us advice on good neighborhoods and other things we should be looking out for, but I like to do my own research, too. We already have an idea of what features we would like: 3 bedrooms, 2 bathrooms, hopefully a basement, and a nicely sized yard. This information is all available through Denver's open data portal. Is it also possible to use this data to identify 'hot' or 'up-and-coming' neighborhoods? Another consideration for us is that we are planning on renting first in order to get a feel for the town. Can this data help us find periods during the year that are more favorable to buy?

### What data are you going to use for this? How will you acquire this data?
Denver has an open data portal at [https://www.denvergov.org/opendata](https://www.denvergov.org/opendata) that has several datasets that should make this project possible:

* [Real Property Sales and Transfers](https://www.denvergov.org/opendata/dataset/city-and-county-of-denver-real-property-sales-and-transfers)
* [Real Property Residential Characteristics](https://www.denvergov.org/opendata/dataset/city-and-county-of-denver-real-property-residential-characteristics)
* [Parcels](https://www.denvergov.org/opendata/dataset/city-and-county-of-denver-parcels)
* ~~[Crime](https://www.denvergov.org/opendata/dataset/city-and-county-of-denver-crime)~~
* ~~[311 Service Requests](https://www.denvergov.org/opendata/dataset/311-service-requests)~~
* ~~[Census Neighborhood Demographics](https://www.denvergov.org/opendata/dataset/city-and-county-of-denver-census-neighborhood-demographics-2010)~~

After a deeper look. I'll definitely be using the first three datasets in the list above. They contain complementary information and should be relatively simple to put together into a larger dataframe.

### In brief, outline your approach to solving this problem (knowing that this might change later).
The first step for this project will be to look more closely at the data contained in the above datasets and determine how clean and complete it is. Next, the data will be imported into Pandas and cleaned. Once that's done, the data will be put together into a dataframe and an exploratory analysis will be performed. This will be followed by creating a model (probably with scikit-learn) to predict the final sale price of a house.

### What are your deliverables? Typically, this would include code, along with a paper and/or a slide deck.
The deliverables will include the code used throughout the project and a Jupyter Notebook or slide deck to present the findings.
