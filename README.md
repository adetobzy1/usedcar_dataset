# Used Car Dataset
## by Tobi Adegoke


## Dataset

The Dataset used is a Used_Cars Dataset gathered from Kaggle website. The Dataset contains 7906 Feature values and 18 feature labels of Used Cars in some state in USA. In this dataset, I am exploring to draw some insight which I wil be using for my explanatory part to communicate my findings. Some of the feauters of the used cars are seling price of the cars, maximum power, engine, seller type, km driven, mileage, years purchase, owner etc.
During pre wrangling, I removed rows containing Test_Drive_Cars from the dataset, grouped year and fill it undeer a new added label named 'year_group', then dropped the year column. Also I converted from object datatypes to category datatype of some columns and extract first words from owner column. I also renamed Trustmark_Dealer to Dealer in seller_type column. this reshaped the dataset to 7901 rows and 11 columns with 5 numerical variables and 6 categorical variables.
To download the dataset on kaggle website, click [link](https://www.kaggle.com/datasets/shubham1kumar/usedcar-data/download?datasetVersionNumber=2)


## Summary of Findings

In the exploration, it was discovered that most cars selling price were of low prices, low engine, low maximum power and less driven but mileage falls in-between low and high. majority of the cars used diesl/petrol fuel, first owner, are automatics and recently bought.
maximum power and selling price are strongly positive correlated.
seller type, transmission, owner and years and car maximum power are related with selling price


## Key Insights for Presentation

I focused majorly on the effects of Maximum Power, Transmission, Seller Type, Owner and Year on the Selling Price in this presentation.
a distribution of the selling price was plotted using histogram. 
I went on to plot the selling price against maximum power and found that ther are both strongly positively correlated with each other.
I later plot selling price against seller type and als against transmission, Dealer cars are most expensive, also automatic cars are most expensive.
I moved on to see the relationship between selling price and Owner, and then Year, it was seen that owner and year are related with selling price. recent cars and first owner cars are more expensive than old and second owner cars.
Also plot to see the relationship between owner, selling price across year, this proofs the relationship of owner, year with selling price.
the relationship between maximum power, selling price and transmission was plotted and transmission has relationship with selling price and maximum power.
he relationship between maximum power, selling price and year was also plotted and confirmed that year and maximum power are strongly related with selling price
Lastly, I plotted the relationship between maximum power, selling price and owner and shown that owner and maximum power has a relationship with selling price.

Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.