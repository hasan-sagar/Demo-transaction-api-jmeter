# Demo Transaction API Testing Using JMeter

## Project Intro
Set up JMeter to test the dmoney transaction API by configuring HTTP request samplers for each API endpoint. 
Ensure proper authentication, headers, and payload data are included. Execute the requests, monitor responses, and analyze results for accuracy and performance validation.

## Project Testing scenarios
1. Admin creates an agent and a customer
2. Deposit 2000 tk to agent from system account (fromAc: SYSTEM)
3. Deposit 1000 tk to customer from agent account
4. Check balance from customer account
5. Withdraw 500 tk from customer account
6. Payment 200 tk from customer account (Merchant account: 01686606905)

## Tools Used
- Apache JMeter

## Server URL
- https://dmoney.roadtocareer.net/
  
## Run this project
1. Install Apache JMeter
2. Download and save "Demo Transaction API.jmx" file on apache "bin" folder
3. Run "ApacheJMeter.jar"
4. Open "Demo Transaction API.jmx" this on JMeter and start testing


### JMeter Summary Report:
![summary](https://github.com/hasan-sagar/Demo-transaction-api-jmeter/assets/61242766/eeb7f9a6-4aec-4784-bce1-8f801b571707)


### JMeter Generated HTML Report
![screencapture-file-F-J-Meter-apache-jmeter-5-6-3-bin-demo-transiction-api-Reports-index-html-2024-03-15-17_56_08](https://github.com/hasan-sagar/Demo-transaction-api-jmeter/assets/61242766/a49a0607-824b-4960-b3c7-45901aed2efc)

