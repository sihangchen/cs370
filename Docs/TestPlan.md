# Test Plan

**Author**: Team 1

## 1 Testing Strategy



### 1.1 Overall strategy

We will test if the individual methods within the classes will function properly. This will primarily be add, edit, deletion methods within the ListManager class. Methods in other classes may not be testable at this stage as they are not standalone and may require interactions with data or methods from other parts of the design. 

**Integration testing:** 

With the reasoning that our application heavily requires interactions between multiple classes to function, but also contains a low number of components, we will implement the Big Bang Testing methodology for our integration step, testing all combined components as a whole. 

**Regression testing:** 

Any code and version changes (bug fixes, enhancements and configuration modifications) will be tested against relevant test cases previously established testing suite confirm that individual functionality and the overall application integrity has been retained.

 **Automation Testing:**  

As our application is not particularly complex, automation testing may be excluded. However likely candidates for automation tests would be the basic CRUD operations found within each class, and the item DB.

### 1.2 Test Selection

Test case selections will be based on: A standard use scenario; whether or not the requested requirements/functionalities work under the expectations of a average user. A abnormal use scenario, where the user may behave contrary to expectations, functionality and any instructions of the application. 

 Because the application is relatively simplistic, under a standard use scenario white box testing techniques, particularly ones that test coverages are most suitable. They ensure that all coded statements, all branches, and all possible outcomes are executed at least once. This will enable confirmation of data flow and expected outpoints within individual classes and between relationships, ensuring that the final code will have the functionality required.  

Similarly, because of simplicity, a effective method of testing the abnormal use scenario would be to utilize black box testing techniques. If tested from the perspective of a user, (user story technique), one can anticipate the various ways they may accidentally or intentionally attempt to cause errors (Error guessing technique). This allows for creation of a test suite designed for cases such as  random/illogical otherwise nonstandard input combinations, negative values, extremely large and small input values,  etc.



### 1.3 Adequacy Criterion

* The testing suite must Implement all existent code at least once.

*  Implement all functionality and combination of functions at least once. 
* Confirm that the functionality of the core classes, primarily the static CRUD operations, are error free. 

* Confirm the flow of data is successful, accurate and able to be utilized where required.
*  Emulate variable inputs that normal users and abnormal users may make, under the assumption that both normal and edge cases are relatively common. Confirm that requirements have been implemented

### 1.4 Bug Tracking

The project leader will consolidate the bug reports through Google forms. Upon receiving the forms the project mnager will ask the testers to attempt to replicate the error with the given steps provided in the form. If the error is repilacted it wil be escalated and discussed during the team meetings. Where the developers will  provide a soulution during the meeting or give a timeline as to when the solution can be expected. They will then communicate this information to all team members. 

### 1.5 Technology

Manual testing will be done under the JUnit4 or JUnit5 framework. Automated testing if applicable, will utilize Selenium.

## 2 Test Cases

| Test Case                                              | Test Purpose                                                 | Required Steps                                               | Expected Results                                             | Actual Results | pass/fail | Additional Information |
| ------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | -------------- | --------- | ---------------------- |
| Get Started                                            | To see the behavior of pressing the "GET STARTED" button     | Clicking on the "GET STARTED" button                         | The user is directed to the My List  page.                   |                |           |                        |
| CreateList                                             | Confirm behavior of pressing the "CREATE LIST" button.  Confirm the functionality of input pop up. Confirm the new list entry is created. | 1. Clicking on the "CREATE LIST" button,<br /> 2. provide a new name for the new list, <br />3.click on "SAVE" button <br />4. repeat steps 1 and 2 and click on "CANCEL" button to abort the creation of the new list. | The user is able to create a new list. Or the user is able to abort the  creation process. |                |           |                        |
| Select List                                            | Confirm the behavior of pressing a list                      | pressing on a list                                           | The list is selected.                                        |                |           |                        |
| Dropdown menu on the "My Lists" page                   | Confirm the behavior of pressing the three dots on the "My Lists" page | Clicking on the three dots on the right upper corner of the "My Lists" page | The dropdown menu appears                                    |                |           |                        |
| Check off Button                                       | Confirm behavior of the Check Off Button                     | <br />A List is selcted then clicking on the "Check Off Button"on the left side of the list. | The selected list is checked off                             |                |           |                        |
| Clear All Check Marks                                  | Confirm the behavior of pressing "Clear All Check Marks" button | A list is selcetd then clicking on the "Clear All Check Marks" button from the dropdown | All the check marked lists are cleared off                   |                |           |                        |
| Delete Selected Lists                                  | Confirm the behavior of pressing "Delete Selected Lists" button | A list is selcetd then clicking on the "Delete Selected Lists" button from the dropdown | When clicked this button the selected list is deleted        |                |           |                        |
| Delete All List                                        | Confirm the behavior of pressing "Delete All List" button    | A list is selcetd then clicking on the "Delete All List" button from the dropdown | When clicked this button all the lists are deleted           |                |           |                        |
| Rename Selected List                                   | Confirm the behavior of pressing "Rename Selected List" button | A list is selcetd then clicking on the "Rename Selected List" from the dropdown meny | When clicked on this button the selected list can be renamed. Note to rename a list the user can only selected a single list. |                |           |                        |
| View List                                              | Confirm the behavior of pressing "View List" button          | clicking on the "Pencil"  icon from the right side of the list name | When clicked on this button the user can view the contents of the item list. |                |           |                        |
| ADD ITEM                                               | Confirm the behavior of pressing "ADD ITEM" button           | 1. Clicking on the "ADD ITEM" button,                        | The user is directed to the search item page                 |                |           |                        |
| Select Item                                            | Confirm the behavior of pressing a item                      | pressing on a item                                           | The item is selected.                                        |                |           |                        |
| Dropdown menu on the "My Items" page                   | Confirm the behavior of pressing the three dots on the "My Items" page | The user has selcted an item and then clicks on the three dots on the right upper corner of the "My Item" page | The dropdown menu appears                                    |                |           |                        |
| Check all Items off                                    | Confirm behavior of the Check all items Off  Button          | <br />A item is selcted, then clicking on the "Check Items Off Button" on the left side of the list. | The selected item is checked off                             |                |           |                        |
| Clear all Check Marks                                  | Confirm the behavior of pressing "Clear All Check Marks" button | A item is selcetd then clicking on the "Clear All Check Marks" button from the dropdown | All the check marked items are cleared off                   |                |           |                        |
| Delete selected items                                  | Confirm the behavior of pressing "Delete Selected Items" button | A item is selcetd then clicking on the "Delete Selected Items" button from the dropdown | When clicked this button the selected item is deleted        |                |           |                        |
| Delete all items                                       | Confirm the behavior of pressing "Delete All items" button   | A item is selcetd then clicking on the "Delete All items" button from the dropdown | When clicked this button all the items are deleted           |                |           |                        |
| Edit Quantity                                          | Confirm the behavior of pressing "Pencil" icon               | Clicking on the "Pencil" icon button on the right side of the item name, pencil icon is used for edit quantity in this case. | When clicked this button the user will be asked to give an int input. |                |           |                        |
| Search Item                                            | Confirm the behavior of search bar                           | Click on the search bar on the serach item page. <br />type the item the user wants to add | *When the user hits confirm. The items matching query pattern will be displayed. If no match found the blank display shows up and the add item button shows up. |                |           |                        |
| Category Select                                        | Confirm the behavior of selecting a catagory.                | Click on one of the category.                                | The search bar is displayed, and all items of that category is displayed. |                |           |                        |
| Create Item                                            | Confirm behavior of pressing the "CREATE ITEM" button.       | Clicking on the "CREATE ITEM" button                         | The user is directed to the "Item details "page.             |                |           |                        |
| Item creation check                                    | Confirm the item is added to the search display              | Input details of the item and click confirm                  | The item shows up in the display of its category.            |                |           |                        |
| Attempt to change item quantity to 0 or Negative       | Checks how the application behaves when given a negative or zero input for the items quantity | Enters a negative or zero for the quantity                   | A toast alert shows up informs the user of an invalid entry. |                |           |                        |
| Rename list special input                              | confirm list can accept/handle special characters, capital letters, spacing and number. | enters special characters, spaces, numbers to name the list  | the list is created with the following changes               |                |           |                        |
| Rename list check confirm list can accept blank inputs | confirm how list handles blank entry.                        | no input is given as the name of the list                    | A toast alert shows up informs the user of an invalid entry. |                |           |                        |
| Create/ Rename list with duplicate entries             | confirm how list handles duplicate entries for its name      | previously used name list name is given again                | A toast alert shows up which informs the user of an invalid entry. |                |           |                        |
| item search special input                              | confirm how the search bar accept/handle special characters, capital letters, spacing and number. | enters special characters, spaces, numbers in the search bar | the inputs are considered valid                              |                |           |                        |
| item search for  blank inputs                          | confirm how the search bar accept/handle blank inputs.       | no input is given in the search bar                          | Item create button shows up                                  |                |           |                        |
| Delete Item                                            | confirm how the database deletes selcted items               | user searches for an item and selected the "delete" button   | item is deleted from the database                            |                |           |                        |
| item creation with  special input                      | confirm how the item gets created with special characters, capital letters, spacing and number. | enters special characters, spaces, numbers in the item name bar | the inputs are considered valid                              |                |           |                        |
| item creation with  special input                      | confirm how the item gets created with blank inputs          | if the entery is  nothing or is just space as the item name  | A toast alert shows up which informs the user of an invalid entry. |                |           |                        |



