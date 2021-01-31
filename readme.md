I scrapped information on Broadway shows from the web pages of www.playbill.com, a monthly U.S. magazine for theatergoers, through web scraping techniques in Python. The Python script for retrieving and processing the information of Broadway shows is attached at the end of this report. The consequential broadway2019.csv dataset includes the financial information of any Broadway show that was on show in the year 2019.

The broadway2019.csv dataset contains 17 variables and 1,705 observations. It provides the grosses information of 82 shows run over 52 weeks as a total of 12,424 performances in the year 2019. The definition of each variable is listed below:

*   ID (Identification number of each observation)
*   Show Name
*   Week (The date each grosses week ending on)
*   Theatre (The theater where a show was on show)
*   Gross ($)
*   Gross Difference (From week prior)
*   Gross Potential (%)
*   Average Ticket Price
*   Top Ticket Price
*   Seats Sold
*   Seats in the Theatre 
*   Number of Performances
*   Number of Previews
*   Capacity (%)
*   Capacity Difference (From week prior)
*   Month
*   Season