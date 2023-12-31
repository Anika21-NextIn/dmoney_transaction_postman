# Dmoney API Testing Using Postman And Newman
## Project summary:
This porject shows the automation between DMoney user and Transection API using postman. And generate report using newman to show the test result at a glance. I have added the API collection run documentation, Test Cases documentation both positive and negative test case and a Bug report for this project.
## Test Scenarios:
1. Admin creates an agent and random 2 customers. 
2. Deposit some money from SYSTEM account to the agent. System account: SYSTEM (range 10 tk to 10000 tk)
3. Agent deposit to any of 1 customer
4. Check agent balance
5. Then withdraw any amount by the customer from the agent (range 10 tk to 10000 tk)
6. Then the customer checks balance
7. Then send money to the other customer
8. Then from the another customer payment to this merchant: 01686606905
9. Then the second customer will check both balance and statement
10. Then the merchant will check his own balance

## Prerequisites
``` 1. Node.js ``` <br>
``` 2. Post man ``` <br>
``` 3. Vs code ``` <br>
``` 4. Newman ``` <br>
``` 5. git ``` <br>

## API Documentation
https://documenter.getpostman.com/view/21535164/2s9YeG5qzX 

## Dmoney_Test Case 
https://docs.google.com/spreadsheets/d/1nV6O5qd-GZOQZrSBl6qbXyoezmoiSsU5/edit?usp=sharing&ouid=110318663577610864826&rtpof=true&sd=true

## Dmoney_Bug Report
https://docs.google.com/spreadsheets/d/166DsTzdD3jto-8fNHoRrxybjI0qXI1Lb/edit?usp=sharing&ouid=110318663577610864826&rtpof=true&sd=true

## Newman report on API testing:
![image](https://github.com/Anika21-NextIn/dmoney_transaction_postman/assets/55154873/6745e370-e2e4-4aee-b14d-7fcdf06df918)
![image](https://github.com/Anika21-NextIn/dmoney_transaction_postman/assets/55154873/5bc99acc-cfdf-4954-8c76-a8642f61751d)
![image](https://github.com/Anika21-NextIn/dmoney_transaction_postman/assets/55154873/43dcd039-e6a3-4846-9d3a-2986d68bb457)
![image](https://github.com/Anika21-NextIn/dmoney_transaction_postman/assets/55154873/fb447427-8edd-4e77-ad97-594a91a062b5)
