# Airlines Passenger Satisfaction Analysis Using SQL

I did a detailed analysis on Airlines Passenger Satsifaction using SQL 

#### [Link To Dataset] (https://drive.google.com/file/d/1aPodQ_BUDRaKEX9qnSRozacfTy8M-T70/view?usp=share_link)

### Tool Used: PostgreSQL

![image](https://user-images.githubusercontent.com/72240938/232307399-ec540597-2c92-4416-8b97-f2439a5848fb.png)


## Major Questions with respect to the dataset:
* Which percentage of airline passengers are satisfied? Does it vary by customer type? What about type of travel?
* What is the customer profile for a repeating airline passenger?
* Does flight distance affect customer preferences or flight patterns?
* Which factors contribute to customer satisfaction the most? What about dissatisfaction?


## Removing the null values from age range where the value is null

DELETE FROM airlines_passenger_satisfaction
where age_range is null;


## Finding the Average Flight Distance across different Customer Profiles:

### Average Flight Distance Vs Customer Type

#### Code:

![Flight Distance Vs Customer Type](https://user-images.githubusercontent.com/72240938/232308771-96f06dea-4ab1-412e-9854-f4f713da1160.png)


#### Output:

![Flight Distance Vs Customer Type out](https://user-images.githubusercontent.com/72240938/232308736-7232fe73-bef8-4f9a-b0f4-358e640b398e.png)



### Average Flight Distance Vs Type of Travel

#### Code:

![flight dist  vs type of travel](https://user-images.githubusercontent.com/72240938/232308922-6f524b06-c886-4f70-aae0-dd3274629b62.png)

#### Output:

![type of travel vs flight dist  output](https://user-images.githubusercontent.com/72240938/232308946-5eaab319-2a42-431f-b12d-f54a88afd846.png)



#### Average Flight Distance Vs Class

#### Code:

![flight dist  vs class](https://user-images.githubusercontent.com/72240938/232309004-ed4f8267-e57a-44fd-9fde-9e39bcac299b.png)

#### Output:

![flight dist  vs class out](https://user-images.githubusercontent.com/72240938/232309023-682fae2d-630e-446b-bf9b-b7231161fc39.png)


#### Average Flight Distance Vs Age Range

#### Code:

![age range vs flight dist code](https://user-images.githubusercontent.com/72240938/232309073-e9f4be3a-5b88-413e-9550-2775b52f2ad3.png)

#### Output:

![age range vs flight dist out](https://user-images.githubusercontent.com/72240938/232309094-e8604680-85ae-48a3-b8fc-02767e1f19d8.png)


### Insights:

![Flight Distance Vs Different Passenger Profiles](https://user-images.githubusercontent.com/72240938/232309214-44e529a5-1704-423c-a524-06bc2e5886a4.png)


## Finding Satisfied and Unsatisfied Customers for different customer profiles:

#### Finding satisfied number for customer Type

#### Code:

![Satisfaction vs customer type](https://user-images.githubusercontent.com/72240938/232309840-13df71f7-e541-4973-bafc-b1b152421084.png)

#### Output:

![satisfaction vs customer type out](https://user-images.githubusercontent.com/72240938/232309853-6a06943e-e89b-4755-aebd-48589d4aed17.png)


#### Finding unsatisfied number for customer type

#### Code:

![Dissatisfaction Vs customer type inp](https://user-images.githubusercontent.com/72240938/232309886-b69132ae-6890-48f2-bdf6-49449ad9262f.png)

#### Output:
![dissatisfaction vs customer type out](https://user-images.githubusercontent.com/72240938/232309901-cb8eb5a4-cb47-4a0c-8da1-eddf5d26c217.png)


Similarly, found satisfaction and unsatisfaction for other customer profiles i.e. Type of Travel, Gender, Class, Age Range.


### Insights:


![satisfied and unsatisfied customers profile count](https://user-images.githubusercontent.com/72240938/232309991-df924e1c-bd18-4541-86f2-6253ff39063c.png)



## Finding the returning or repeating passenger profile type:

#### Finding count based on profile type:

#### Code:

![travel type count inpt](https://user-images.githubusercontent.com/72240938/232310963-e1b6e018-46ee-4519-9bd7-fbd4ef9b0e1e.png)

#### Output:

![type of travel vs flight dist  output](https://user-images.githubusercontent.com/72240938/232311120-67a90a94-b9df-4efb-9317-0f02f999616f.png)


Similarly, found count based on other customer profile type too for returning or repeating passengers

#### Insights:


![returning customer type profile](https://user-images.githubusercontent.com/72240938/232311428-06697518-48b0-45dc-a65b-3804f0556f57.png)



#### Finding % Satisfaction and % Unsatisfaction based on different customer profiles:


#### Code:

![percent_satisfied_unsatisfied count](https://user-images.githubusercontent.com/72240938/232312182-c06cd215-580b-497d-afa9-7ea3a59f244e.png)

#### Output:


![percent satisfied and unsatisfied table](https://user-images.githubusercontent.com/72240938/232312202-221ab882-8cc5-46a6-877b-78cdff1df474.png)



## Overall Insights and Recommendations:

* To enhance the airlines services and passengers, "returning type" customer profile or customers profile who have travelled the most average distance, they should be invited to provide some feedback on the different services offered and improvements, as they are the passengers who have travelled the most in the airlines.





















