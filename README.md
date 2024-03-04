#  **Python Challenge 1**
### By: Kyle Kerner

This program takes a pre-poulated menu for a variety food truck and takes the order of the user.  

To begin a list is created to hold to user's order input.  The menu categories (menu_selection) are presented to the user to choose from. An error is displayed if the user inputs and improper response. 

After the menu category is selected the menu of the specified category is displayed to the user using a for loop.  The for loop importantly decifers whether a specific menu is a dictonary type and runs another for loop to get the necessary menu items populated. Key's ("Item name" and "Price") are associated with each menu item at this point.

After the user specifes the specific menu item that they want, they are requested to input the quantity of the item that they would like to buy. If an invalid input is input by the user the default quantity is set to one.  Additionally, the quantity of the specified menu item number is appended to order list.

The user is asked it they would like to order any additional items and will go through the same process noted above until they no longer want to order. 

After the order is complete the program uses a for loop to go through the populated order list and creates variables (price, item name, and quantity) for each item in the list. The progeam then displays the line item list of the items ordered by the user and display's the item, price, and quantity of each item with a grand total amount at the end. 



# Sources
Source code provided in class as well as the use of Chat GPT to help with code direction was used in the making of the program.  
