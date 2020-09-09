I have recently started working on Kaggle Competition. This was one of the projects to get started. In this document, I will explain all the steps that I took fo this project, along with all the results. The repository contains my code along with all the results and the dataset.

<h2> Titanic: Machine Learning from Disaster </h2> 
In this challenge we are provided with the dataset of passenger of "TITANIC". We have to build a predictive model that can show what type of of people are more likely to survive. 

<h3> Dataset </h3>
we are provided with two datasets -'Train' and 'Test' in a csv file format. Both the files contain same variables . 
The information about each variable is discussed below - its type , descrption (if required), possible value and what is my expectation about its influence in prediction.

  1. Suvival                                                                       
       -> Numerical Feature </br>
       -> Values :  0 = No survival , 1 = Yes Survival </br>
  
  2. Pclass : A proxy for Social econmical status </br>
       -> Numerical Feature </br>
       -> Values : 1 = Upper , 2 = Middle , 3 = Lower </br>
       -> High Expectation </br>
  
  3. Sex </br>
       -> Categorical Feature </br>
       -> Values : Male , Female 
       -> High Expectation </br>
  
  4. Age : Age in year </br>
       -> Numerical Feature </br>
       -> Medium Expectation </br>
   
  5. Sipsp : If the Passenger has Sibling or Spouse on the ship </br>
       -> Numerical Feature  </br>
       -> Medium Expectation  
   
  6. Parch : if the passenger has parent or child on the ship </br>
       -> Numerical Feature </br>
       -> Medium Expectation 
       
  7. Ticket : Ticket Number </br>
       -> Alphanumeric Feature </br>
       -> Low Expectation 
       
  8. Fare : Passenger fare </br> 
        -> Numeric Feature </br>
        -> Low Expectation 
  
  9. Cabin : Cabin Number </br> 
        -> Categorical Feature </br> 
        -> Low Expectation 
  
  10. Embarked : Port of Embarcation </br> 
        -> Categorical Feature </br>
        -> Values : C = Cherbourg, Q = Queenstown, S = Southampton </br>
        -> High Expectation
        

        
        
        
        
        
        
      
      
