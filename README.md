#  ***Credit Risk Resampling***

Within challenge 12 we use machine learning capable of gathering loan data (debts, interest rates, accounts, etc.) then using said data to construct a model that would then predict the healthiness of a loan (named the '0' loan) and the risk of a loan (named the '1' loan). The data provided from the predictions would be shown as recall, precision, accuracy and so on, which would in the end give us a percentage of potential trustworthiness in the loan. 


-------------------------

## Technologies

- Libraries: numpy, pathlib, warnings, Sklear.metrics, Imblearn.metrics
- Framework: JupyterLab 
- Operating Systems: Mac OS, Microsoft Windows
- Programming Language: Python

----------------------------

## Results 

### ***ML Model 1 (w/out oversampling):*** 

___Balanced Accuracy Score: 0.95___  
- '0' Accuracy: 1.00, (100%) Recall: 0.99  
- '1' Accuracy: 0.85 (85%) , Recall: 0.91  


![wihoutsup](https://github.com/JohnGarcia222/Challenge-12/assets/127170402/38f051ff-df74-4633-8bef-70be3034e02c)


### ***ML Model 2 (with oversampling):***  

___Balanced Accuracy Score: 0.99___   
- '0' Accuracy: 1.00 (100%), Recall: 0.99 
- '1' Accuracy: 0.84 (84%), Recall: 0.99  


![withsup](https://github.com/JohnGarcia222/Challenge-12/assets/127170402/9d25d9d1-91c3-412e-b07a-cf47cad73ec0)

-----------------------------------

## Summary

  Both ML models performed  well, showing high accuracy in the ability to predict healthy-loans and high-risk loans. However, in terms of perfection and or a more accurate prediction, the second model was 99% accurate while the first model was only 95% accurate. Essentially meaning that if you were aiming to be as accurate as possible you would be better off using the oversampled ML model.

---------------------------------

## Contributors

John Garcia 
email: Jdganna222@gmail.com


