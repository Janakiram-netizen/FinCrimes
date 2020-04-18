# FinCrimes
The concept of Financial crimes, risk and fraud is being considered for the exploration of the sample dataset using big data technologies for storing, processing and visualizing the dataset. Financial companies around the globe are spending lots of resources on building applications to stop fraudulent activities to cover the risks. Due to technology, payment transfers domestically and around the world is extremely easy and fast. Technology has definitely changed the way financial institutions do their businesses and also the way consumers are spending the money. Digital money is the way of spending in the current world. Due to the heavy influx of digital money usage, financial institutions are clearing transactions worth billions of dollars every day. But technology has also exposed financial institutions to frauds, money laundering, etc. As per an estimate financial institutions around the world have lost around ~24 billion dollars in frauds or money laundering related activities. Financial institutions are producing massive amounts of transactional data on a daily basis and big data technologies can be really helpful in developing solutions that can predict or flag risky transactions and help financial institutions in mitigating the risk. 

Amazon S3 buckets, EMR and Quicksight was used to store , load , process and visualize the dataset.

1) SuddenChangeInCustomerBehaviourfraud.hql -- Use case #1
2) SpikeInCreditCardSpent.hql -- Use case #2
3) MoneyFlowingfromLowtoHighRiskCountries.hql -- Use case 3


*********************** Use Cases **************************
--------
Use case #1
-------
Due to lost or stolen card scammers can take advantage of the stolen card details and try to perform purchases in high dollar amounts to gain maximum possible funds. This unusual activity can be alerted by comparing your monthly average spent with the amount spent by scammers for e.g. if you spend on an average $500 on your card/month and on a given day a purchase of $2000 dollars was initiated on your card then system should alert customers to check the validity of the transaction by multi level authentication methods like sms or through mobile apps. Once the customer confirms then only unusual high dollar value transactions must be cleared to prevent potential fraudulent activities. Queries written in hive can identify these types of transactions and generate alerts in a real time system or data.

-------
Use case #2
-------

Detects Spike in credit card spent when credit card spent is unusually high on a given day    and is when daily credit card spent exceeds more tha two times of average monthly spent. System will trigger and an alert for these types of instances and notification must be sent to customer to authentice or vailidate the transaction before clearing the transaction.

-------
Use case #3
-------

Script will identify transactions where senders account risk is high and senders country risk is low. But money is being transferred from Low risk geography to High risk geography for e.g money flowing from canada to Syria.Only those accounts are considered whose source of income is business.



