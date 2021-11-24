
![Screenshot (294)](https://user-images.githubusercontent.com/94280220/143079839-a0b6be3a-66ee-480a-9ad7-c0431fcd0392.png)




![Screenshot (295)](https://user-images.githubusercontent.com/94280220/143079880-e65cb0db-ac55-468d-9c4f-f42302cbd5c5.png)



![Screenshot (296)](https://user-images.githubusercontent.com/94280220/143079977-e991558e-8790-4a3c-b16e-5dd1e491f934.png)



# TEST PLAN:

## Table no: High level test plan

| **Test ID** | **Description**                                              | **Exp I/P** | **Exp O/P** | **Actual Out** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  HLR1       |Creation of new account| Name:abc  Account Number:123456789 Initia Deposit:1000|Account has been created successfully|Account has been created successfully|Requirement based |
|  HLR2       |Deposit Amount|1000 |The current available bank balance is 2000|The current available bank balance is 2000|Requirement based|
|  HLR3       |withdraw Amount|3000| Sorry, You dont have enough money in your account| Sorry, You dont have enough money in your account| Requirement based  |



## Table no: Low level test plan

| **Test ID** | **Description**                                              | **Exp IN** | **Exp OUT** | **Actual Out** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  LLR1       |If user enters wrong Account Number. | 000000000| Wrong account number...| Wrong account number...|Requirement based |
|  LLR2       |If wrong choice choosen| 7|Invalid choice|Exit|Scenario based    |

