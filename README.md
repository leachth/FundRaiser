# FundRaiser
Insight Data Science Project

### Project Description 

Running for political office can be very expensive. The winner of a House seat in the 2018 midterm elections spent, on average, $2 million (Center for Responsive Politics). Raising money is critical to running a successful campaign, and can be particularly important for first-time candidates to be seem as viable. The challenge is that it can be difficult for first-time candidates to know how to best allocate their time and resources for fundrasing events and operations.

The goal of this project was to build a tool to help first-time political candidates more efficiently run the fundraising arm of their campaign by identify zipcodes in their district or area where they have the opportunity for the largest return on investment from fundraising efforts such as event or townhalls.

The tool is available at:
[FundRaiser](https://fundraiser.shinyapps.io/FundRaiser/)

---

### The data
For this project I have pulled together several different data sources including:
* Federal Election Commission: individual donor database
* Internal Revenue Service: zipcode level annual statistics
* Census Burea: demographic statistics for each zip code tabulated area

To model next election cycle potential donation for every zipcode in the US.
Here I define potential donation as the product of:
* the probability of donation 
* number of possible donors (total population over the age of 18) 
* a $50 donation amount (typical donations are under $100 per person, [Pew Research Center](https://www.pewresearch.org/fact-tank/2017/05/17/5-facts-about-u-s-political-donations/)) 



