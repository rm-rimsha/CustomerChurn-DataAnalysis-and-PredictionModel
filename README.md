# CustomerChurn-Data-Analysis-and-PredictionModel

This project revolves around the analysis and prediction of customer churn using a dataset sourced from Kaggle. The dataset underwent thorough cleaning in Python to address missing values, invalid data types, and normalization tasks. The analysis was subsequently visualized using Power BI. Lastly, a Random Forest model was employed for prediction, yielding an accuracy rate of 79%.


## 📊 **Data Analysis:**

  1. **Overall Analysis:**

      ![image](https://github.com/rm-rimsha/CustomerChurn-DataAnalysis-and-PredictionModel/assets/105241371/5bbbadf7-103b-42ae-af49-fb527597bd97)


      From the above , it is evident that

       1. Our customer base comprises 7032 individuals, with an almost equal distribution between male and female customers.

       2. About **83%** of customers are **under 65 years old**. _This implies strong presence of young people in our customer demographics._

       3. About 48% customers have partners while 30% have dependents.

       4. The average monthly charge of our product is $64.80

       5. About **26.58% of customers churned**

        _Implying that 26% have stopped using or purchasing our product or service_


  2. **Demographic Impact:**

       ![image](https://github.com/rm-rimsha/CustomerChurn-DataAnalysis-and-PredictionModel/assets/105241371/63127f00-e0ba-46fd-8145-72a8ec064a92)

      From the above, it is evident:

      1. Gender-distribution does not have siginificant impact on churn.

      2. Customers without dependents are more likely to churn (**22%**) compared to those with dependents(**5%**).

      3. The young customers have higher churning percentage of **20%** compared to older customers with **7%**. 
  
         _Implying the younger customers are more tech-savy and open to switching services if not satisfied._

      4. Customers without partners have a higher churn rate of **17%**, which may be influenced by factors such as different lifestyle needs or preferences compared to those with partners. 

         _This group may have unique requirements that are not met by current offerings, leading to a higher likelihood of churn._

  3. **Tenure and Contract Type Impact:**

     ![image](https://github.com/rm-rimsha/CustomerChurn-DataAnalysis-and-PredictionModel/assets/105241371/61055109-a9e1-402f-b737-c9b14bef48f7)

     From the above, it is evident:

     1. About **1000 customers** left in **less than a year** of signing up

        Indicating potential dissatisfaction and poor customer experience with the service or product shortly after signing up

     2. **More than 300 Customers** left **within the first month** in which **99%** opted for monthly contract 

         Implying that customers did not find it suitable for their needs shortly after subscribing. Hence, left it.

     3. **88%** of customers using **month-to-month** contract churned.

        Monthly contracts provide flexibility to customers but also make it easier to switch if they are unsatisfied

     4. Customers who paid bills through paperless method are more likely to churn (**35%**) than others (**14%**)

         To improve customer retention, the onboarding and initial experience should be improved to address early customer concerns, especially for those on monthly contracts. Additionally, efficient communication strategies should be employed to meet the needs and concerns of customers

 4. **Financial and Payment Impact:**

    ![image](https://github.com/rm-rimsha/CustomerChurn-DataAnalysis-and-PredictionModel/assets/105241371/6cfa97f2-b70c-4080-a813-c47bad74e850)

    From the above, it is evident:

    1. Customers with higher monthly charges of **more than $60** are more likely to churn
 
       Indicates the higher monthly charges is potentially a reason for customers to leave in the monthly contract. Introducing student plans and discount offers can reduce the increasing churn ratio

    2. Customers with payment method of Electronic Check are more likely to churn
   
  5. **Service Usage:**

     ![image](https://github.com/rm-rimsha/CustomerChurn-DataAnalysis-and-PredictionModel/assets/105241371/d4f50bea-4529-47c9-99ff-2142cb377ec4)

     ![image](https://github.com/rm-rimsha/CustomerChurn-DataAnalysis-and-PredictionModel/assets/105241371/96e34e18-4381-4532-952b-8aa47a623de3)

     From the above, it is evident:

      1. **Fiber Optic** internet service is the most common in churned customers

          Implying that even though fiber optic is the most popular in customers but it is probably not meeting the customer expectations or needs

      2. About **24%** of customers who opted for phone service left

         The phone service alone is not the driving factor to increase customer retention

      3. The other services such as multiple phone lines, streaming services, device protection, online security, online backup, and tech support are a potential reason for **customer retention** as the customers with these services are less likely to churn compared to others who did not opt for them.

        Implying that effective marketing strategies for these services, offering bundle services can prove beneficial in decreasing customer churn rate


## ⚙️ **Prediction Model**
  A Random Forest classification model was implemented using Python's scikit-learn library to predict customer churn. The model achieved an **accuracy of 79%**, indicating its effectiveness in predicting customer behavior.

## 🔍 **Conclusion**
  The project demonstrates the process of analyzing and predicting customer churn using machine learning techniques. The insights gained from this analysis can be used to develop strategies aimed at reducing customer churn and improving customer retention.
