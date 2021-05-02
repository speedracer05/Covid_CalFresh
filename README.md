# Group-Project-1 Project CalFresh
# Charting Covid-19 Impact to California's Food Assistance Program (SNAP)

## Project Proposal
There have been reports and studies about the impact of COVID-19, infection rates and unemployment. For our team project, we wanted to take a different approach, to understand if usage of California's CalFresh program surged as a result of increased infection rates. CalFresh is California's implementation of the Federal Supplemental Nutrition Assistance Program, which provides food benefits to help people purchase food at teh grocery store.   

## Questions
The team wrote out a list of questions that we wanted to seek from the data:
* As Covid infection rates increased, so did CalFresh enrollement
		ii. What are the top 5 counties with the worst infection rates?
		iii. What is the worst affected county?
		iv. What is the least affected county
		v. What is the correlation between infection rates and rural populations that may not wear masks?
		vi. What is the worst covid infection rate as a percentage of population?
		vii. Show the correlation between covid and SNAP enrollement
to work with disparate data sets to un:
* Player Count
* Purchasing Analysis (Total)
* Gender Demographics
* Purchasing Analysis (Gender)
* Age Demographics
* Top Spenders
* Most Popular Items
* Most Profitable Items

The purchase_data csv was read into as a panda csv, and loaded in-memory. Next DataFrame objects were created and manipulated to customize and reshape the data sets for further analysis. Additionaly panda's cut function was utilized to separate data array elements into different bins to perform analysis on scalar data. The final information was formatted to provide a cleaner presentation. 

## Key Takeaway
* There were 576 active customers, driving $2.4K in Total revenue, comprised of 780 purchases, with an average Sales price of $3.05.
* Sales occured across all 179 titles, but were concentrated 

Gender Demographics
* Customer data shows a heavy slant towards male-customers, comprising 84%, while female-cstomers made up 14% of the user-base.
* Males-buyers drive almost 83% of the revenue, but spend ~9% less than their female counterpart, $4.07 vs $4.47.
Age Demographics
* Further segmenation of buyers can be seen by age group. Young adults, 18-24 represent almost 50% of all users. As a group, they also represent the 2nd highest average retail revenue at $4.31. They should be defining the average retail revenue, which is $3.05 -- but they are not. Something else is at play. Further investigation needs to be conducted on the ASPs across the game portfolio
* We should take a look at Marketing spend to concentrate more money at this user-segment.
Top Spenders
* We looked at the top 5 customers, in terms of Total Purchases. The spend of these customers was more than the average sales price
Most Popular Items
* Final Critic was by far our best seller in terms of unit count and revenue; 13 units driving $59.99 at an average sales price of $4.61
* Nirvana was our 3rd best seller with 12 units, but at an average sales price of $4.90. This is 6% better than Final critic
* 
## Getting Started

You will need to load the Panda script, HeroesOfPymoli_starter.ipynb into Jupyter notebook, with "purchase_data.csv". 

## Built With

* Jupyter notebook Code Version: 6.0.3
Chrome: 87.0.4280.141
Node.js: 12.18.3
OS: Windows_NT x64 10.0.19042
* conda 4.10.0
* Python 3.6.10 :: Anaconda, Inc.
* Kite Pro Version: 1.2021.310.0
## Contributing


## Versioning

## Authors

* **John Chan**


## License

## Acknowledgments

* 
