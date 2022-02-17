# Crypto Wallet

## Streamlit Application

This application provides the service of connecting customers to FinTech professionals to complete transactions within a blockchain.  Within the application, there is a candidate profile section, a live tracker of the current account balance, a candidate selection tool, a calculator to show the transaction fee for the selected candidate, as well as a button for posting the transaction to the chain.  The image below provides the starting page for the web application.

![Streamlit Application](Images/web-application.jpeg)
-------------
## Candidate Selection Sidebar
On the side of the application resides the functionality of the code.  Within this area, the customer has the ability to perform several necessary tasks.  First they are able to view a live balance for their account in Ether, providing them with the information needed to select the proper payable amount for their transaction.  There is also a section dedicated for choosing the ideal candidate for the job.  Once a candidate is selected, the hourly rate is automatically updated, then applied to the number of hours the candidate is going to be hired for.  At the bottom of the sidebar, the transaction information is displayed, including information for the candidate, their hourly rate, ether address, and finally the total wage necessary for completing the transaction.  Once the customer is satisfied with the information, they are able to click the "Send Transaction" button to apply the transaction to their chain.

-------------
## Sending the Transaction
Upon completion of the transaction in the web application, the transaction is posted to the customer's account as shown in the screenshots below.


Account information following transaction posting.
![Ganache Account](Images/ganache-account.jpeg)

List of transactions for the account.
![Ganache Transactions](Images/ganache-transactions.jpeg)

Individual transaction information showing the address of the selected candidate receiving the Ether for the transaction.
![Transaction 1 Info](Images/transaction-1-info.jpeg)
![Transaction 2 Info](Images/transaction-2-info.jpeg)