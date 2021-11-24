# TEST PLAN:

##  High level test plan

| **Test ID** | **Description**                                              | **Exp I/P** | **Exp O/P** | **Actual Out** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  HLR1       |Creation of new account| Name:abc  Account Number:123456789 Initial Deposit:1000|Account has been created successfully|Account has been created successfully|Requirement based |
|  HLR2       |Deposit Amount|1000 |The current available bank balance is 2000|The current available bank balance is 2000|Requirement based|
|  HLR3       |withdraw Amount|3000| Sorry, You dont have enough money in your account| Sorry, You dont have enough money in your account| Requirement based  |



## Low level test plan

| **Test ID** | **Description**                                              | **Exp IN** | **Exp OUT** | **Actual Out** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  LLR1       |If user enters wrong Account Number. | 000000000| Wrong account number...| Wrong account number...|Requirement based |
|  LLR2       |If wrong choice choosen| 7|Invalid choice|Exit|Scenario based    |

