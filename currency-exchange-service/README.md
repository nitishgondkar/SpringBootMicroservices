# Dependencies to Add

![img.png](img.png)

# Check Following links
https://github.com/in28minutes/spring-microservices-v2/blob/main/03.microservices/01-step-by-step-changes/microservices-v2-1.md#spring-cloud-config-server---steps-01-to-08

## URL and Response Structure for Currency Exchange Service
### We will make use of these in the next lecture!


## URL & Response for Currency Exchange Service
URL : http://localhost:8000/currency-exchange/from/USD/to/INR


``
Response Structure
{
"id":10001,
"from":"USD",
"to":"INR",
"conversionMultiple":65.00,
"environment":"8000 instance-id"
}
``
## URL & Response for Currency Conversion Service
URL : http://localhost:8100/currency-conversion/from/USD/to/INR/quantity/10

-----------------------------------------------------------------------
-----------------------------------------------------------------------
# CODE BACKUP FILES and STEP BY STEP CHANGES : For Reference
## Help for Debugging Problems:
- Here's the code backup at the end of Step 13: https://github.com/in28minutes/spring-microservices-v2/blob/main/03.microservices/step13.md

- Step by Step changes are detailed here: https://github.com/in28minutes/spring-microservices-v2/blob/main/03.microservices/01-step-by-step-changes/microservices-v2-1.md#step-13



## Two Recommended Activities:
 - **Activity - 1** : Explore other backups for this section (Steps 08,10,13,15,21,25,29, final) - https://github.com/in28minutes/spring-microservices-v2/tree/main/03.microservices

 - **Activity - 2** : Get Familiar with the structure of Step by Step changes file - https://github.com/in28minutes/spring-microservices-v2/blob/main/03.microservices/01-step-by-step-changes/microservices-v2-1.md#step-13