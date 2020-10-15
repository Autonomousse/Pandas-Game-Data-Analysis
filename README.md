# Pandas Game Data Analysis - Heroes of Pymoli

## Goal
The goal of this exercise is to take on the responsibilities of being a Lead Analyst for an independent gaming company to analyzing data for their new fantasy game, Heroes of Pymoli.

Like many others in its genre, the game is free-to-play, but players are encouraged to purchase optional items that enhance their playing experience. As a first task, the company would like you to generate a report that breaks down the game's purchasing data into meaningful insights.

Your final report should include each of the following:

## Player Count
 * Display the total number of players

## Purchasing Analysis (Total)
 * Run basic calculations to obtain number of: 
    * Number of Unique Items
    * Average Purchase Price
    * Total Number of Purchases
    * Total Revenue

* Create a summary data frame to hold the results


* Optional: give the displayed data cleaner formatting


* Display the summary data frame

## Gender Demographics

* Percentage and Count of Male Players


* Percentage and Count of Female Players


* Percentage and Count of Other / Non-Disclosed

## Purchasing Analysis (Gender)

* Run basic calculations to obtain the following by Gender:

    * Purchase Count
    * Average Purchase Price
    * Total Purchase Value
    * Average Purchase Total per Person

* Create a summary data frame to hold the results


* Optional: give the displayed data cleaner formatting


* Display the summary data frame

## Age Demographics

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

## Purchasing Analysis (Age)

* Bin the purchase_data data frame by age


* Run basic calculations to obtain the following by age group:

    * Purchase Count
    * Average Purchase Price
    * Total Purchase Value
    * Average Purchase Total per Person


* Create a summary data frame to hold the results


* Optional: give the displayed data cleaner formatting


* Display the summary data frame

## Top Spenders

* Identify the the top 5 spenders in the game by total purchase value, then list (in a table):

    * SN
    * Purchase Count
    * Average Purchase Price
    * Total Purchase Value

* Sort the total purchase value column in descending order


* Optional: give the displayed data cleaner formatting


* Display a preview of the summary data frame

## Most Popular Items

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

## Conclusions
* One of the first conclusions that can be drawn is from age demographics. It is clear to see that the highest percent of players are aged 20-24 years old (44.79%), followed by age ranges 15-19 (18.58%) and 25-29 (13.37%). While this makes sense since these age groups are young and can afford to stay up late to play games, the age range of gamers may widen in the future as gaming is becoming a larger entertainment source than industries such as film. Especially due to current events such as the COVID-19 pandemic, current age demographics in gaming may certainly be wider than this data set. This does not mean that the target market should be widened, it should still focus on these largest age groups as they are also the largest spenders as seen by the Player Analysis done by Age.
* It is interesting to note that the highest purchase count was only 5 items with an average purchase price of $3.79 per item. This could mean that the items are not seen as necessary by players to enjoy the game/give them some sort of benefit or that the price is too high relative to the benefit/enjoyment received from the item. It might be beneficial to run some tests or conduct user research to find out if a lower price would also mean an increase in purchase volume. If this is found to be true, the increased volume would offset the lower cost and still be profitable, especially as this is a game and the cost of selling digital items has no real COGS (assuming the assets are owned in full by the game studio).

* The last conclusion is in relation to the items themselves. There are 179 different Item ID’s but some clear signs that a few items are seen as superior purchases by players. Final Critic, Oathbreaker, and Fiery Glass Crusader show up on both the most popular items and most profitable items summary tables. It would be wise to remove some of the lowest selling items and save resources to add in variants of the more popular ones that could net more profit. There is also a dilemma in offering too many choices to consumers as it can be overwhelming, and they may choose not to purchase anything at all. A few choices would allow them to differentiate and decide what is best for their unique play style and entice them to make a purchase.
