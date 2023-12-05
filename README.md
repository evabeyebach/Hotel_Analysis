# Hotel_Analysis
We are trying to find out **why both hotels are having cancellations** and how to prevent them. We also want to provide a better customer overview to achieve greater **customer satisfaction**.

## __Introduction__

This data comes from an open hotel booking demand dataset from [Antonio, Almeida and Nunes' article: _Hotel Booking Demand Datasets_](https://www.sciencedirect.com/science/article/pii/S2352340918315191#f0010)
We want the hotel to improve its profit by being able to predict future cancellations and being able to improve customer satisfaction.

__Booking Cancellations__: What variables can we make analyze to better understand cancellations and how to prevent them in the future.
We will answer the following questions during our analysis:

* Which variables affect cancellations the most?
* Which hotel has a higher count of cancellations? 
* Do certain countries have higher cancellation rates than others?
* Which seasons or months tend to have the highest number of cancellations?
* Does market segment, customer type and meal affect cancellations?
* How does the pricing differ per type? How does lead time affect correlation?

__Customer Overview:__

* Which hotel is most popular?
* Where are the majority of customers coming from?
* What strong connection is there to returning customers?

## __Data Preparation__

We will clean our data by doing the follwoing:

* showing data types
* showing columns
* describing the data
* summarizing teh data
* showing missing values
* exploring duplicates
* winsorizing outliers

## __EDA__:

We will try to reveal hidden insights in the data and answer our research questions by doing plots like:
* Bar charts
* Histograms
* Scatter plots
* Correlation Matrix to see which variables correlate more to each other.

## __Modelling__:

*  We are going to be using machine learning models, such as:
*  __Linear Regression Logistic Regression, Decision Tree or Random Forest__ to predict cancellation
*  We will compare them to each other to see which one is the best

##__Conclusion__:

* __previous_cancellations, is_repeated_guest, hotel and market_segment are the variables that most predict is_cancelled__
* City Hotel has a higher Cancellation Ratio than Resort Hotel with 39.7%
* Portugal has the highest number of cancellations.
* Most booked monthd are August 11611, July and May. (Vacaction months). However, June has the highest cancellation ratio (0.713) followed by April and May.
* In July, August and September Resort Hotel has much higher prices and peak.
* Distribution Channel `TA/TO` is doing a good job on making people book. However, they have a lot of cancellations.
* The higher the lead time , the more cnacellations.
* People with `Room Type A` has the highest cancellationn ratio with almost 60%
* Only 3.5% of the customers are coming back. The ratio is very low.









