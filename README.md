# Neural_Network_Charity_Analysis

## Purpose of the Loan Prediction Risk Analysis
The purpose of this analysis is to use Machine learning and Neural Networkd to help Beks create a Binary Classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. 

## Results
In order to obtain our results we would need to compile, train and evaluate as well as optimize the model.
### Data Preprocessing

 What Variable(s) are considered the target(s) for your model?
 
 * The Variable that is considered the target is the "IS_SUCESSFUL" category.
![target Variable](https://user-images.githubusercontent.com/96032255/169678444-966462d5-ff69-4eec-9dd1-83aa51811b5a.PNG)

 What variable(s) are considered to be features of your model?
 
* Please see chart below

*![Features of model](https://user-images.githubusercontent.com/96032255/169678483-8625355d-eee5-4bbf-bb0a-d3eceb8700dd.PNG)

 What variable(s) are neither targets nor features, and should be removed from the input data?
 
* The EIN and Name column was removed.

![neither targets or features](https://user-images.githubusercontent.com/96032255/169678540-79a3b846-4444-4c99-a67e-48c27aa84d76.PNG)
## Compiling, Training, and Evaluating the Model
How many Neurons, layer,and activation functions did you select for your Neural Network Model?

* There are 2 hidden layers. Layer 1 has 80 Neurons and the 2nd layer has 30 Neurons. The activation function sigmoid
  
![Model](https://user-images.githubusercontent.com/96032255/169680253-fe57ad2a-d4d9-4c97-9431-ec4edcfd1bb9.PNG)

![Model1](https://user-images.githubusercontent.com/96032255/169680336-3dc07d3e-213c-4e1e-9cb6-b566e134a874.PNG)

![Model2](https://user-images.githubusercontent.com/96032255/169680323-e1cfca11-6056-41b4-af12-bf5326bc187f.PNG)

Where you able to achieve the target model Performance?

What steps did you take to try and increase your target performance?

* No i was not successful at achieving. 
* The target model performace of 75%. I was only able to achieve a combined total accuracy rate of 74%.
  
   ![Attempt 1](https://user-images.githubusercontent.com/96032255/169680893-16f6d28f-98ea-4845-870f-f1656b1c8da4.PNG)
   

  ![2nd attempt](https://user-images.githubusercontent.com/96032255/169680906-63ab6cf3-4c73-4190-803c-467257d6547b.PNG)
![3rd attempt](https://user-images.githubusercontent.com/96032255/169680911-abf94fc0-447e-44ee-be41-5750b9a1f213.PNG)

## Summary
  This analysis has shown that Machine Learning and Neuro Networks can be very helpful/useful in the decion making process. Although I did not reach the targeted module goal in 3 attempts it is still possible  to obtain.
  
  ### Recommendations
 My recommendation is to use the  Random Forest Classifier model.  The reason i feel that Random Forest Classifier model would be best is because it has less outliers and we could get classified outputs and evaluate its performance against the deep learning module.
