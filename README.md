# pandas-challenge

## Heroes of Pymoli
### Goal
The goal of this assignment is to take on the responsibilities of being a Lead Analyst for an independent gaming company to analyzing data for their new fantasy game, Heroes of Pymoli.

Like many others in its genre, the game is free-to-play, but players are encouraged to purchase optional items that enhance their playing experience. As a first task, the company would like you to generate a report that breaks down the game's purchasing data into meaningful insights.

Your final report should include each of the following:

### Player Count
 * Display the total number of players

### Purchasing Analysis (Total)
 * Run basic calculations to obtain number of: 
    * Number of Unique Items
    * Average Purchase Price
    * Total Number of Purchases
    * Total Revenue

* Create a summary data frame to hold the results


* Optional: give the displayed data cleaner formatting


* Display the summary data frame

### Gender Demographics

* Percentage and Count of Male Players


* Percentage and Count of Female Players


* Percentage and Count of Other / Non-Disclosed

### Purchasing Analysis (Gender)

* Run basic calculations to obtain the following by Gender:

    * Purchase Count
    * Average Purchase Price
    * Total Purchase Value
    * Average Purchase Total per Person

* Create a summary data frame to hold the results


* Optional: give the displayed data cleaner formatting


* Display the summary data frame

### Age Demographics

* Establish bins for ages

    * Break down into bins of 4 years (i.e. <10, 10-14, 15-19, etc.) and calculate the following by age group:

        * Purchase Count
        * Average Purchase Price
        * Total Purchase Value
        * Average Purchase Total per Person

* Categorize the existing players using the age bins. Hint: use pd.cut()


* Calculate the numbers and percentages by age group


* Create a summary data frame to hold the results


* Optional: round the percentage column to two decimal points


* Display Age Demographics Table

### Purchasing Analysis (Age)

* Bin the purchase_data data frame by age


* Run basic calculations to obtain the following by age group:

    * Purchase Count
    * Average Purchase Price
    * Total Purchase Value
    * Average Purchase Total per Person


* Create a summary data frame to hold the results


* Optional: give the displayed data cleaner formatting


* Display the summary data frame

### Top Spenders

* Identify the the top 5 spenders in the game by total purchase value, then list (in a table):

    * SN
    * Purchase Count
    * Average Purchase Price
    * Total Purchase Value

* Sort the total purchase value column in descending order


* Optional: give the displayed data cleaner formatting


* Display a preview of the summary data frame

### Most Popular Items

* Retrieve the Item ID, Item Name, and Item Price columns

* Group by Item ID and Item Name. Perform calculations to obtain the following:

    * Item ID
    * Item Name
    * Purchase Count
    * Item Price
    * Total Purchase Value

* Create a summary data frame to hold the results


* Sort the purchase count column in descending order


* Optional: give the displayed data cleaner formatting


* Display a preview of the summary data frame

## Most Profitable Items

* Sort the above table by total purchase value in descending order


* Optional: give the displayed data cleaner formatting


* Display a preview of the data frame
