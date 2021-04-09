# Use Case Model

**Author**: Team 1

## 1 Use Case Diagram

<img src="https://github.com/qc-se-spring2021/370Spring21Sec55Team1/blob/main/GroupProject/Docs/Pictures/UseCaseDiagram.png" alt="Use Case Diagram">



## 2 Use Case Descriptions

- **Use Case Description: Display list** 

  Requirements: The user is able to view the existing lists. 

  Pre-conditions: The user must have the app downloaded and provide basic user information inorder to use the application. 

  Post-conditions: The user would have the option to select an individual list from the many or create a new list. 

  Scenarios: 

  **Step 1:** In the home page, the new users will be prompted to provide basic information such as name. 

  **Step 2:**  Later on, they are directed to a blank page where they can view the lists . 

  **Step 3 a:** In that page, the user can click “create list” button to create a new list and assign a name to the list. The newly created list is populated in the intial home page. 

  **Step 3 b:** From the home page the user would have the option to select and view a individual list. 

   

- **Use Case Description: Create list**

  Requirements: The user is able to create a grocery list to display all of the items they added.

  Pre-conditions: The user must be in the home page. 

  Post-conditions: Display the newly generated empty list on the home page. 

  Scenarios: 

  **Step 1:** The user will click on the "create list" button. 

  **Step 2:**  The user will be prompted to provide an unused name for the list and confirm its creation. 

  **Step 3:** The user will be directed to the intial home page which will now display the new list. 

  

- **Use Case Description: Select list**

  Requirements: User is able to select list

  Pre-conditions: At least one list is created for user to select. 

  Post-conditions: The list contents whould be shown as a new screen (list screen). 

  Scenarios: 

  **Step 1:** In the list page, there should be at one list exist for user to select.

  **Step 2:** The user clicks the list and the items of the list are shown in that list screen  .

  

-  **Use Case Description: Modify list**

  Requirements: The  user is able to delete, or rename the already created lists. The user would also be able to remove all checkmarks. 

  Pre-conditions: The user is in the list screen.

  Post-conditions: The list name is changed, the list is deleted or the check off marks are removed. 

  Scenarios: 

  **Step 1**: Click on the "modify list" dropdown. And select "rename list" , "delete list" or "clear all checkmarks". 

  **Step 2 a:** If the user selects to "rename list" the list the user will be prompted to give a new name and confirm. 

  **Step 2 b:** If the user selects to "delete list" the user will be asked to confirm the action, if confirmed the  user will be directed to the updated home screen. The list is deleted. 

  **Step 2 c:** If the user selects to "clear all checkmarks" all the the checkmarks would be removed. 
  
  
  
-  **Use Case Description: Modify items:** 

  Requirements: The user is able to select an item to change the quantity, remove, check off items or clear all check off marks. 

  Pre-conditions: There should be a minimum of one item on the list screen. 

  Post-conditions: The list screen is updated.  

  Scenarios:

  **Step 1:**  Click on a individual "item". And select "change quantity", "delete items", "check off items" from the dropdown

  **Step 2a:** If the user selects "change quantity" the user will be promted to enter the int value for the quantity. Then the total quantity and the total price would be updated in the list screen. 

  **Step 2b:** If the user selects  "delete items" the user will be asked to confirm the action, if confirmed the item will be removed from list screen. 

  **Step 2c:** If the user selects "check off items" the items that were checked off in list screen would be unchecked off. 




-  **Use Case Description: add items:** 

  Requirements: The user is able to search items by typing their name or create a brand new item and add the item to the list screen. The item will be displayed on the list screen by item type. 

  Pre-conditions: There has to be an item database. 

  Post-conditions: The item is found or is created in the data base. The item is added onto the list screen. 

  Scenarios:

  **Step 1:** Click on the "add item" button which would prompt the user to enter the item name. Based on the user entery, the user will be given item suggestions to add to the list.

  **Step 2:**  If the item suggestion can not be found the user will be require to give additional information to add the item to the database and  to their list. 

  **Step 3:** Added the item to the list screen grouped by type. 

  **Step 4:**  The items will be displayed in the list screen in the following format: type first, item name, price, quantity. 

  

  



