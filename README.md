# Dash Analysis

The purpose of this project is to analyze the *dash* blockchain in general, the blocks and the transaction from August 1st of 2018 to September 30th of 2019.

## Understanding the Dash blockchain

It was created in January 4th of 2014 and it started with the name of Darkcoin, it is a Litecoin code based which is based on bitcoins code and they forked the network to create Dash.
InstandSend transaccitions 1.3 seg. 

Block time is 2.5 is mining difficulty is able to be adjusted in every single block algorithm dark gravity wave of 2 MB.

~ 56 transaction per second.

Dash mining algorithm is called X11 hashrate is 500gigahashes per second


## Objective

Our main objective is to analyze Dash between all the variables that the blockchain has, we would like to find some insights in the data to have a better understanding of how dash works and see the some interesting data within the time.

## Resources

For this project we use a lot of tools, first to get all the data, make an extract of it, managing the blockchain and storage it for us to analyze and understand all the blockchain.

### Big Query and Big Table 

We use big query to extract the data and store it in Big Table

### S3

Then we use S3 to transfer all the data of the blockchain from Big Table

### Redshift

We use redshift as our data warehouse to store all the data we have and the we use this to transalate to a data visualization software


### Tableau

We bring the data from Redshift to analyze it and create the charts to have a better visualization from the data and make all the charts


## Insights

After using Tableau we have a lot of information and we found the next insight.

Every insight will be display in the file of Tableau as a screenshot.


* Active addresses vs time   
    the active addresses are the addresses that made a transaction in the last 24 hours. 
    
* Hash rate vs time  

* Hash rate and active addresses vs time  

* Miners Profit vs time  

* Median difficulty vs time, average in 7 days  

* Transferred value, numbers of transactions vs time  

* total of addresses, addresses with more than $10 and 1000 DASH and which addresses with more than 1000 Dash are nodes vs time


    





