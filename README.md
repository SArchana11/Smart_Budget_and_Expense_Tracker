# Smart_Budget_and_Expense_Tracker
A simple Salesforce project to track expenses, manage budgets, and get alerts when spending goes over the limit.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

##  Problem Statement
Tracking expenses and budgets is important, but many people still use spreadsheets or manual methods. These are slow, hard to manage, and don’t give real-time alerts.  

This project builds a simple **Expense Tracker in Salesforce** that lets users:  
- Add and categorize expenses.  
- Connect expenses to a budget.  
- See the total expenses automatically.  
- Get an email alert when expenses go over the budget limit.  

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🎯 Goals
- Create two custom objects: **Expense** and **Budget**.  
- Link Expenses to Budgets with a lookup relationship.  
- Use a roll-up summary to calculate the total expenses.  
- Create a Flow to send an email alert when the budget is crossed.  
- Explore AppExchange apps for similar use cases.  

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🏗️ Features
- **Expense object** → Amount, Date, Category (Travel, Food, etc.)  
- **Budget object** → Budget Name, Threshold Amount, Total Expenses  
- **Automation** → Roll-up summary + Record-triggered Flow  
- **Email Alerts** → Sends notification if expenses exceed the budget  

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## 🛠️ Tools Used
- Salesforce (Lightning Experience)  
- Salesforce Flow (for automation)  
- Email Alerts  
- AppExchange (for research)  

