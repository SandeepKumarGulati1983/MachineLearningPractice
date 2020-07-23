# MachineLearningPractice

## 1. Regression Model's algos and projects


*** Imp points ** in Regression models.

	-- Y = dependent variable  like Salary or Profit.

	-- X  = independent variable like Experience , company revenue etc..

	-- in regression we are predicting the dependent variable Y.

### Models template With Multi-features data 

-- taken care of Missing data and Categorical data.

-- last column should be the dependent variable and before that are features (any).

-- here evaluating the "model performance also"
	
	from sklearn.metrics import r2_score
	r2_score(y_test, y_pred)

### Models template with Single-feature data 

-- taken care of Missing data and Categorical data 
-- consider first column is a feature and second is a dependent variable.

  1. Linear Regression model  -> Y = a + bX

  -- via using skLearn library
  		
  		project : Predicting the salary based on experience of an employee
  		
  		CSV Data (One feature): Independent Variable : experience
  					
  					Dependent variable : salary


  -- via Mathematically driving Y hat hypothesis

  2. Multiple Linear Regression Model --> Y = a + bX + cX ...... nX
  		
  		Project : Predicting the profit based on multiple variables 
  		
  		CSV Data (Multiple feature): independent variables - R&D spend, Administration, Marketing Spend, State
  					
  					dependent Variables - Profit

  3. Polynomial regression model --> Y = a + bx + cx^2 + .... nX^n 
  		
  		Project : salaries based on positions are given . -->  predict the previous salary of the candidate.
  		
  		CSV Data (Multiple feature): independent variables - R&D spend, Administration, Marketing Spend, State (String)
  					
  					dependent Variables - Profit


  4. SVR (Support Vector Regression) Model
  		
  		Project : salaries based on positions are given . -->  predict the previous salary of the candidate.
  		
  		CSV Data (one feature): independent variables - Level 
  					dependent Variables - Salary

  		-- invented by Valdmir Vapnik - book: The nature of statistical learning theory.

  		-- Insenstive tube - inbetween that pipe , we don't care about error.

  			-- slack variables.

  			-- Eksi (E) the width of that tube.

  				-- Ei  - point above that tube.

  				-- Ei* - point below that tube

  		-- published paper - https://core.ac.uk/reader/81523322
  		
  		-- Kernels (ex. gaussian RBF kernel, sigmoid kernel etc. )

  5. Decision Tree Model
  		
  		Project : salaries based on positions are given . -->  predict the previous salary of the candidate.
  		
  		CSV Data (One Feature) : independent variables - Level
  					
  					dependent Variables - Salary

  6. Random Forest Model
  		
  		Project : salaries based on positions are given . -->  predict the previous salary of the candidate.
  		
  		CSV Data (One Feature) : independent variables - Level
  					
  					dependent Variables - Salary

  		-- Ensamble 

## 2. Classification.

-- Unlike regression where you predict a continuous number, you use classification to predict a category

-- CSV data : Social_Network_ads : Independent variable - age and income 
			 					   Dependent variable - Purchased or not 

		1. Logistic Regression.

			-- Confusion matrix 

		2. K-NN (K Nearest neighbors)

			-- Euclidean distance 

		3. SVM (Support Vector Machine )

			-- Maximum margin hyperplane.

			-- data is linearly seprable 

		4. Kernal SVM 

			-- data is not linearly seprable.

			-- Mapping to a higher dimension. via hyperplane.

					-- higher dimension calculations are computer intensive , so we can use kernal tricks like gaussian RBF kernel.

		5. Naive Bayes 

		6. Decision Tree classifications 

		7. Random Forest Classifications

### Performance Check 

-- false positive and false negetive 

-- Confusion matrix 

--

## 3. Clustering (Unsupervised learning )

    1. K Mean clustering 

    2. Hierarchical clustering 

## 4. Association rule learning .

      -- Eclat 

      -- Apriori 

## 5. Reinforcement Learning models .

      -- Upper confidence bound 

      -- Thompson sampling 

      note ** good book to read (https://www.amazon.com/Crash-Course-hands-introduction-reinforcement/dp/1838645357/ref=sr_1_1?crid=235YAFPX03J0Z&dchild=1&keywords=ai+crash+course&qid=1594476675&sprefix=ai+cr%2Caps%2C213&sr=8-1)

## 6. NLP 

## 7. Deep learning 

## 8 . Dimensionality reduction.


  # Reference learning:

  1. Udemy course - Machine Learning A-Z tm -python  - Instructor : Kirill Eremenko & Hadelin
  2. Coding blocks  - Machine learning fundamental - Instructor : Prateek Narang (IIT Delhi)
