# Finance-Planner
Coded in Java, Finance Planner takes in a budget inputed by the user. It calculates the percentage of spending per category. It displays the info in a pie chart.

#Basics

User creates a budget plan. User then inputs in transactions, information gets stored and loaded next time application is run. User can specify whether they want transactions to be outputted daily/weekly/monthly/annually. Make some default categories, user can add/remove categories. When done, program displays percentage spent per category in a pie chart and how close they are to their budget plan.

#Files
default.txt - Stores the names of the default budgets (fixed, disposable, savings)
user.txt - Stores the names of all budgets the user has created (may/may not include budgets from default.txt)

#Classes

Types of Budget(fixed, disposable, saving)

   Account:              Budget:              Category:               Purchase:
 (Properties)          (Properties)         (Properties)            (Properties)
  Name(optional)         TotalAmount           Name                   Amount  
  Email(unique)          Categories[]          Amount Spent           DateTime
  Password               Budget Type           Category(??)           Name      
  Budget[]                                                            Location(optional)                                                             
#Additional Features

Android/Web functionality
