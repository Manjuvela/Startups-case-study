
# Startups Case Study

You will get to know how the funding ecosystem has changed with time in India.

And how the number of startups has increased and also about the support and funding option that is available to them.

You will also see the current state of the Indian startup ecosystem, the range of fundings, the preferred Industries most startups prefer and how location plays an important role in determining the growth of the startup.

Analyze who plays an important role in shaping the Indian Startup ecosystem.

Using the word cloud to determine the maximum funding made by a particular investor.

To infer from the word cloud , word frequencies that give greater prominence to words that appear more frequently are relatively bigger than the other words



## Installation

Libararies to Import:-
- Numpy
- Pandas
- Seaborn
- Matplotlib
Requirements:-
                Jupyter notebook - To Build an interactive python notebook.

To install word cloud:-
                 pip install word cloud
## Contributing

Analyzing the dataset: -

The dataset comprises over 3000 observations and 10 attributes.

Attributes are namely the data of incorporation, startup name, industry vertical, sub-vertical, city, investors name, investment type, the amount in usd and remarks.

Data cleaning is the process of detecting and correcting or removing corrupt or inaccurate records from a record set, database, or data frame.

Refers to identifying the incomplete, inaccurate, or irrelevant parts of the data and then replacing, modifying, or deleting the dirty or coarse data.

Data cleaning is crucial and emphasized because wrong data can drive a business to wrong decisions, conclusions, and pool analysis.

Barplot to plot this distribution: -

The month of January, February, and June of 2016 has the highest number of funding.
The number of fundings has declined over the period, especially after 2016 there is an exponential decrease in the fundings for Indian startups.

The general amount of startups get in India: -
Using the sort_values function and found out the max value using the max function.

You can see that the Maximum funding is 3900000000.0 for an Indian startup.

Checking startups with more than 50 crore funding: -

Use of interactive Python module.
Implementing a check function and using the conditional statement to return the companies having more funding than the given value.

By sliding 500000000, you see that Rapid Bike Taxi, Flipkart, Pratipili, Paytm, etc have over 50 crores of funding.

Checking different venture funding in the startup: -

Paytm. - It has been funded by over 7 investors.
Checking for the minimum funding in the startup: -
The minimum funding is -999 which is our assigned value.

From the word cloud infer that Capital, Sequoia Capital, Venture, Kalaari Capital, Angel Network, Tiger, etc have funded more into startups than any other funding agency.
Checking a barplot to see the list of top investors in investing in Indian Startups.

Private equity: -
It is an alternative investment class and consists of capital that is not listed on a public exchange.

Seed funding: -
It is a form of securities offering in which an investor invests capital in a startup company in exchange for an equity stake or convertible note stake in the company.

## Documentation

Replace Function is used to define a function that replaces the characters with an empty string.

Head Function is used to check Entries of the Dataset.

The shape Function is used to check the shape of the data.

Starting with Data Cleaning:-
                     IsNull function to find the null values.
                     Sum function to find the total number of missing values.

To concat two values: -
Using concat function, you can concat the values into the missing_value dataset.

Remark columns: 
The remark column has many nan values and high cardinal columns.

Remove the remark column using the drop function.
Checking the column after we have removed the remark column.

To convert the amount column into numerical value: -
Analyze the values.

To clean the amount, create a function clean_amount function.

It will take the amount and replace it with the numerical value, replace characters with empty strings, replace “undisclosed” with empty strings, and also replace “n/a” with empty strings.

If the amount is empty, then we replace it with a “-999” value.

The function is created, apply clean_amount function on the “amount in USD” column in the data to clean the values for analysis using the apply function.

Visualize the distribution of the amount to see if our amount values are numerically converted or not.

For that, you should use the plot function to plot the distribution.

In the plot, the amount values are converted and are showing the distribution amount.

Barplot is used to check the funding ecosystem change over time, we will use the barplot to infer the data.
1. You have to convert the data into a date-time object.
2. Use of to_datetime function, year and month function to do the datetime manipulation.
3. Sort the year-month values and load them into the temp variable.
4. Use of value count function to count the number of funding in that particular month for that particular year.


## Conclusions

There are startups with 0 funding.
Checking startups with the least funding: -
Use of sort_value function.

You see that Splitkart, TAC Security, Fable Street, etc have the least funding.

There are 971 startups with NO funding at all.

You see that Swiggy has been funded 8 times, Ola cabs have been funded 8 times, Paytm has been funded 7 times, Nykaa has been funded 6 times, etc.

Use barplot, Firstly remove the nan values in IndustryVertical with Consumer Technology.
Most of the startups belong to the Consumer Internet industry where most of the funding was made.
Analyzing the sub-vertical industries.
We will use the line plot for this.

Most sub-vertical industries where the maximum number of fundings are made in Online Lending Platforms, Online Pharmacies, Food Delivery platforms, Education, etc.

If location plays an important role in determining the growth of the startup.

You need to do a little cleaning of the city values for better analysis.
To infer barplot is used.
30% of the startups which were funded are located in Bangalore.
68% of the startups are either from Bangalore, Mumbai, or New Delhi, making it a huge startup hub.
You will see that 49% of the major investors don’t disclose their identities.


Apart from that you will see that Ratan Tata, tiger global, Kalahari Capital, and Indian angel network are some of the largest investors in Indian startups.

Analysis of the types of investments, the investors are making in Indian startups using a barplot.

You will see that most of the investments are Private Equity and Seed Funding.


