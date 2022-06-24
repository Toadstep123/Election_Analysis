# Election_Analysis
### Overview of Election Audit ###

  The purpose of this analysis is to see how voters in three specific counties in Colorado had voted for the US Congressional Precinct, while being able to keep it automated through python. Tom, the person who we are helping in this module, is hoping to use this code in the future for the rest of the counties in Colorado in order to make counting these votes much easier.
  
  ### Election Audits Results ###
  
  * There was a total of **369,711 votes** in this congressional election.
    * **82.8%** of the votes, or **306,055** were in Denver County.
    * **10.5%** of the votes, or **38,855** were in Jefferson County.
    * **6.7%** of the votes, or **24,801** were in Arapahoe County.
  * **Jefferson County** had the largest amount of votes, taking up a massive majority in the election.
  * There were **three candidates** in the election, with the winner being **Diana DeGette.**
    * Diana DeGette had **73.8%** of the votes, or **272,892** votes.
    * Charles Casper Stockham had **23.0%** of the votes, or **85,213** votes.
    * Raymon Anthony Doane had **3.1%** of the votes, or **11,606** votes.
  
  ### Election Audit Summary ###
  
  While this code is not extremely versatile, it is very easy to slightly edit this code in order to use it for many other elections. When changing the source file, *election_results.csv*, the user of this code should keep in mind that the formatting of the table should be kept the same. They could also change the code in order to import a file of any name by changing line 9 of the code, which has the path to the loaded table.
  
  ![image](https://user-images.githubusercontent.com/7826238/175457452-08763c55-1306-4bde-8ac5-3780a0ef7999.png)
  
Just replace the directory inside of the parenthesis with a different file name or destination.


If the user provided a different location, such as for a presidental election, they would need to change the headers in some of the code's output. In this example, you would want all instances of "county" to be changed to "state". You would be able to keep all of the variables under the same name, but changing them would make the code much more readable. For example:

![image](https://user-images.githubusercontent.com/7826238/175458281-f65a5981-19c9-4767-a1ca-18cade835a69.png)

In line 21 and 22, the variables are named "county_options" and "county_votes". The user would want to change all of the instances of these variables to "state_options" and "state_votes", to keep consistent with the results. They would also change the text outputs in lines 91 and 120. Both of these print out the word "county", which should be replaced with "state".
