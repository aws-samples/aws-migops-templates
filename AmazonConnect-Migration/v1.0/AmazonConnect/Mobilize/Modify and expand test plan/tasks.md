
# Module: Modify and expand test plan
## Task 1: Inbound tests
#### Description
Test for all required inbound metrics. The following tests must be performed to ensure quality operations. Record details on pass/fail and any comments. Upload results as an attachment. Test Plan.xlsx in [GitHub](https://github.com/aws-samples/aws-migops-guidance/tree/main/AmazonConnect-Migration/v1.0/Amazon-Connect) has step-by-step instructions on how to perform each test.   

•	Inbound call - Hold/Resume  
•	Inbound call - PSTN caller disconnects  
•	Inbound call - Agent disconnects  
•	Inbound call - Disconnect before answer  
•	Inbound call - Caller ID displayed  
•	Inbound call - Blocked caller ID  
•	Inbound call - Queue treatment  
•	Inbound call - Ring with no answer  
•	Inbound call - Long call  
•	Inbound call - Long hold  
## Task 2: Outbound tests
#### Description
Test for all required outbound metrics. The following tests must be performed to ensure quality operations. Record details on pass/fail and any comments. Upload results as an attachment. Test Plan.xlsx in [GitHub](https://github.com/aws-samples/aws-migops-guidance/tree/main/AmazonConnect-Migration/v1.0/Amazon-Connect) has step-by-step instructions on how to perform each test.

•	Outbound call - Invalid caller ID  
•	Outbound call - International  
•	Outbound call - Toll-free  
•	Outbound call - Domestic LD  
•	Outbound call - Long hold  
•	Outbound call - Long call  
•	Outbound call - DTMF  
## Task 3: Transfer tests
#### Description
Test for all types of transfers. The following tests must be performed to ensure quality operations. Record details on pass/fail and any comments. Upload results as an attachment. Test Plan.xlsx in [GitHub](https://github.com/aws-samples/aws-migops-guidance/tree/main/AmazonConnect-Migration/v1.0/Amazon-Connect) has step-by-step instructions on how to perform each test.

•	Inbound call - Cold transfer to agent  
•	Inbound call - Cold transfer to PSTN  
•	Inbound call - Transfer to agent  
•	Inbound call - Transfer to PSTN  
•	Outbound call - Transfer to agent  
•	Outbound call - Transfer to PSTN phone  
•	Outbound call - Cold transfer to agent  
•	Outbound call - Cold transfer to PSTN  
•	Inbound call - Cold transfer to queue  
## Task 4: Conference tests
#### Description
Test for all types of conferences needed. The following tests must be performed to ensure quality operations. Record details on pass/fail and any comments. Upload results as an attachment. Test Plan.xlsx in [GitHub](https://github.com/aws-samples/aws-migops-guidance/tree/main/AmazonConnect-Migration/v1.0/Amazon-Connect) has step-by-step instructions on how to perform each test.

•	Outbound call – Conference to agent #2  
•	Outbound call - Conference to PSTN  
•	Inbound call - Conference to agent #2  
•	Inbound call - Conference to PSTN
## Task 5: Load and failover testing
#### Description
Test for high load and failovers. 

The following tests must be performed to ensure quality operations. Record details on pass/fail and any comments. Upload results as an attachment. Test Plan.xlsx in [GitHub](https://github.com/aws-samples/aws-migops-guidance/tree/main/AmazonConnect-Migration/v1.0/Amazon-Connect) has step-by-step instructions on how to perform each test.

•	Maximum concurrent calls

1. Place the maximum concurrent calls to your Amzon Connect instance
2. Verify that the maximum number of concurrent calls can be reached and that you get a busy tone on the calls exceeding the limit
## Task 6: Test integrations
#### Description
1) End to end testing of all components in the custom agent desktop (custom CCP) 
2) Test data feeds for WFM integration 
3) Test data feeds for BI tools 
4) Test data feeds for custom real time reporting applications 
5) Test data feeds for data lake and/or data warehouse ingestion