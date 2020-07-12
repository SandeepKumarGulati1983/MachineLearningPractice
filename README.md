# MachineLearningPractice


*** Imp points ** in Regression models 
	-- Y = dependent variable  like Salary or Profit 
	-- X  = independent variable like Experince , company revenue etc 
	-- in regression we are predicting the dependent variable Y

  1. Linear Regression model  -> Y = a + bX

  -- via using skLearn library
  		project : Predicting the salary based on experince of an employee
  		CSV Data : Independent Variable : experience
  					Dependent variable : salary


  -- via Mathmatically driving Y hat hypothesis

  2. Multiple Linear Regression Model --> Y = a + bX + cX ...... nX
  		Project : Predicting the profit based on multiple variables 
  		CSV Data : independent variables - R&D spend, Administration, Marketing Spend, State
  					dependent Variables - Profit

  3. Polynomial regression model --> Y = a + bx + cx^2 + .... nX^n 
  		Project : salaries based on positions are given . -->  predict the previous salary of the candidate.
  		CSV Data : independent variables - R&D spend, Administration, Marketing Spend, State
  					dependent Variables - Profit


  4. SVR (Support Vector Regression) Model
  		Project : salaries based on positions are given . -->  predict the previous salary of the candidate.
  		CSV Data : independent variables - R&D spend, Administration, Marketing Spend, State
  					dependent Variables - Profit

  		-- invented by Valdmir Vapnik - book: The nature of statisticle learning theory 
  		-- Insenstive tube - inbetween that pipe , we don't care about error.
  			-- slack variables 
  			-- Eksi (E) the width of that tube 
  				-- Ei  - point above that tube 
  				-- Ei* - point below that tube
  		-- published paper - https://core.ac.uk/reader/81523322
  		-- Kernels (ex. gaussian RBF kernel, sigmoid kernel etc. )

  5. Decision Tree Model

  6. Random Forest Model


  Reference learning:

  1. Udemy course - Machine Learning A-Z tm -python  - Instructor : Kirill Eremenko & Hadelin
  2. Coding blocks  - Machine learning fundamental - Instructor : Prateek Narang (IIT Delhi)
