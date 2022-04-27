# BU2010-RapidMiner

## Introduction

### Overview

This week we will be working with RapidMiner. 


## Advice

It's best if you **Commit early, commit often** - that way you can go back if you have made a mistake and I can see all the work you have done. It doesn't matter if your early commits contain mistakes.  

Once you are done be sure to commit your changes (that will save them to the repository) and to push them to GitHub (so that I can see the work you have done).

## Task Explanation

For this task, you need to provide the answers in the file you are currently reading. It is a Markdown file. More explanations about the Markdown syntax can be found [on GitHub's Mastering Markdown page](https://guides.github.com/features/mastering-markdown/).

* Under the heading _Your Task_ you will find several questions. 
* Use RapidMiner to find the answers, then add the answers to this Markdown file.


## Your Task

You have to work on this task individually. 

#### Task 1 (Titanic)

* Drag the Titanic data from the Samples repository into the Process.
* Connect the output port of Retrieve Titanic with the result port ("res") on the right side of the Process panel.
* Use the Statistics tab to look at summaries of the data in the columns. 

How many people did travel in First class? 

**Answer:** Replace this text with your answer.

And how many people did not survive the Titanic accident?

**Answer:** Replace this text with your answer.

#### Task 2 (Titanic)

* Drag the Titanic data from the Samples repository into the Process.
* Search for the Filter Examples operator using the search box at the top of the Operator panel. Drag Filter Examples into the Process panel.
* Connect the output port of Retrieve Titanic with the input port of Filter Examples.
* Click Filter Examples to select it, then click Add Filters in the Parameters panel to define a filter.
* Select Sex on the left, equals in the middle, and type Female in the box on the right. Instead of typing, you can click on the magic wand and select Female from the list.
* Search for and then drag the Sort operator into the Process.
* Connect the output of Filter with the input of Sort.
* Click on Sort to select it. Make the following changes to the sort by parameter in the Parameters panel:
* Set attribute name to Passenger Fare.
* Change sorting order to descending.
* Connect the Sort output port to the result port on the right of the Process panel.
* Run the process and inspect the result.

What is the highest fare paid for a woman?

**Answer:** Replace this text with your answer.

Change the process to find out what that highest second class fare was (independent of gender). 
What is the highest fare paid for a second class ticket?

**Answer:** Replace this text with your answer.

#### Task 3 (Products and Transactions)

* Expand the Samples repository in the Repository panel. Next, expand the data folder within the samples repository to retrieve the Products and Transactions data.
* Drag the Products data and the Transactions data from the Samples - Data folder into the Process panel.
* Use the Join operator to join Products and Transactions via the key attribute "Product ID".
* Add the Aggregate operator to the process (after the Join operator)
* Click Aggregate to select. Make the following changes in the Parameters panel:
* Click on aggregation attributes.
* Select Customer ID in the left box and set function to count in the right box.
* Stay in this dialog and add another entry Product Name with function set to mode. Click Apply.
* Click on group by attributes. Then, select the Product ID by moving it to the right. Click Apply.

Which product has been bought by 22 different customers?

**Answer:** Replace this text with your answer.

Which product has been bought by 4 different customers?

**Answer:** Replace this text with your answer.


#### Task 4 (Products and Transactions)

* Start a new process
* We will be working with the Products and Transactions data again. This time it is up to you to find a suitable way of using operators to answer the questions.

What is the name of the most expensive product and how much does it cost?

**Answer:** Replace this text with your answer.

What is the name of the cheapest product and how much does it cost?

**Answer:** Replace this text with your answer.

Find out what the customer with Customer ID 50 bought. What are the names of the products and how many of each did this customer buy?

**Answer:** Replace this text with your answer.


#### Task 5 (Height)
* Import the height-week5v_gender.csv file from this repository into RapidMiner (click Import Data in the Repository panel and follow the steps in the wizard).
* When you complete the import, store the data in your Local Repository.
* Create a suitable process that allows you to visualise the data as a box plot, grouped by gender. 
* Export the chart as a PNG and save it in your repository (You should see the menu to export the chart by clicking on the three lines at the top right of the box plot). 


**Commit early, commit often** - that way you can go back if you have made a mistake and I can see all the work you have done. It doesn't matter if your early commits contain mistakes.  

Once you are done be sure to commit your changes (that will save them to the repository) and to push them to GitHub (so that I can see the work you have done).