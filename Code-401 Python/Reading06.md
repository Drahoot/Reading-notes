## How to use Random Module
- Random Module allows random numbers to be generated
- If we want to get a random integer we can use the rantint function
- Choice allows use to genereate a random value from a list
- Shuffle randomizes elements in a list and changes their order
- Randrange generates a randomly selected element from range

## What is Risk analysis?
- Risk analysis is the process of Id-ing the risks in apps or software that is built and is being prioritizing in testing
- At the beginning of a project risk analysis highlights potential problem areas
- Possible risks:
  - Use of new hardware
  - use of new automation tool
  - Sequence of code
  - Availability of test resources for the app
- Unavoidable risks
  - Time allocation for tests
  - Urgency from clients to delivery products
  - Incomplete reqs
- Points to be solved: 
  - Use max resources to work on high risk areas
  - create risk assessment database for future use
  - id and notice the risk magnitute indicators: high, medium, low
    - High: The effect of the risk would be very high and non-tolerable
    - Medium: Its tolerable but not desirable. The company suffers fincancially but there is a limited risk
    - Low: Tolerable. There lies little or no external exposure or no monetary loss
- Risk ID:
  - Busniess risks: The most common risk. Its the risk of what may come from a company or customer and not your project
  - Testing risk: You should be familiar to the platform you're working on
  - Premature release risk: A background of knowledge to analyze the risk associated with releasing unwanted or untested software is required
  - Software risks: Being well versed with any risks associated with the software dev process
- Perspective of risk assessment:
  - Effect: Asses risk by effect. In the case you ID a condition, event, or action and try to determine its impact
  - Cause: Assess risk by Cause is the opposite of Effect. 
  - Likelihood: Assess risk by likelihood is to ID that there is a propability what a req will not me met
- How to perform Risk analysis:
  - Searching risk
  - Analyze impact of risk
  - Measures for the risk ID

## Test Coverage
- You're doing enough testing if:
  - Bugs are scarce in production
  - You're rarely hesitent to change code for fear it will create bugs

## Big O
- Big O is the relationship between runtime and input variables
- Time of data transference increases on size of data file
- Big O rules:
  - Diff steps get added
  - Drop constants
  - Diff Inputs
  - Drop non-dominate terms