# ATM_Dispense_Predictions

Problem Statement:

You are part of an analytics team responsible for improving Cash Business of Hitachi. Hitachi manages more than 20K ATMs in India. There is an operations team who maintains thousands of ATMs deployed across country for various banks. When it comes to maintenance, the team looks after loading cash in the ATMs periodically. If the ATM is down due to some reason, the team fixes the issue and makes ATM live within few days. One of the important tasks of this team is to make sure enough cash is available in the ATMs for at least 7 days. Each ATM has upper limit of how much cash can be loaded. 
There are 2 ways when a bank can charge penalty to Hitachi
•	If the team loads cash into the ATM with the full capacity and the dispense doesn’t happen then bank charges penalty for the idle cash holding in the ATM. 
•	If we load ATMs with less amount then there are instances where ATM runs out of cash due to insufficient balance. This situation is termed as Cash Out. Bank charges penalty for this too.
Operations team reaches out to you to address the problem of Cash Out. Your task as a Data Scientist is to predict/forecast dispense amount for each ATM for next 7 days. These predictions can be shared with the team and accordingly cash loading can happen. 

IMP POINTS:

1.	The dataset has data for 3 banks.
2.	The data contains daily dispense for each ATM of last 2 years
3.	You can’t load cash more than the upper limit defined for each ATM
4.	You have been provided only 7 ATMs per bank in the given data set. In reality you will have hundreds/thousands of ATMs per bank. You are not expected to build model for each ATM.
5.	Feature description
a.	Bank: ATM belongs to which bank
b.	ATMID: ID of the ATM
c.	Caldate: Date 
d.	Dispense: Amount dispensed from an ATM on a particular day 
e.	DT: Time in minutes when ATM was down on a particular day
f.	MaxCapacity: Maximum amount which can be loaded in the ATM
g.	CountTotalTxn: Count of total number of transactions 
