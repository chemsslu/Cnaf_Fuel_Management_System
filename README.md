# Cnaf_Fuel_Management_System
2 types of users: Admin & Client
4 types of interface: Customer_Management 
                      & Airport_Management
                      & Fuel_Application 
                      & List_Analysis

#USERS
For Admin:
  Full authroity for 4 interface
  
For Client:
  authroity for List_Analysis
  
#INTERFACES
For Interface of Customer_Management:
  Structure of Customer
    Custom.Num
    Customer.Code
    Customer.Name
    Customer.Rate
    Customer.Remarks
  Function of Customer
    Customer.Add
    Customer.Delete
    
For Interface of Airport_Management:
  Structure of Airport
    Airport.Num
    Airport.Name
  Function of Customer
    Airport.Add
    Airport.Delete
    
For Interface of Fuel_Application:
  Structure of Application
    Application.Num
    Application.Code
    Application.Date
    Application.Amount
    Application.Airport
    Application.Remark
  Function of Application
    Application.Add
    Application.Delete

For Interface of List_Analysis:

