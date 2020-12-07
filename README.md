# Food Ordering System
## Employee and Customer class

These classes contains methods through which a process is carried out when the employee or customer performs an activity.

For example - When an employee inputs a category name "Dessert", so the method add_food_caterogy has a parameter with name. This name parameter is passed on to an object that holds the class (Food Caterogy) and value (name). The object is then passed on to the session through the session.add() and holds it temporarily and the session.commit() stores the record in the DB. 

## How to run locally via command line:

```
>> python main.py

Connecting to sqlite:///fos2.db
    
    Welcome to the Food Ordering System! Please press the below options:

    1. Employee
    2. Customer

    Your Option:

    1

    Welcome to the employee interface! Please press the below options:

    0. Quit
    1. Add food category
    2. Add food details
    3. Add delivery person
    4. Assign delivery person to order
    5. Update order (Only for delivery person use)
    6. View order details
    7. View order status
    8. View revenue today
    9. Delete order

    Your Option:

    1
    
    Enter category name: Desserts
    
    Add Successfully
```


