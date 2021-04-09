# Design Document



**Author**: Team 1

## 1 Design Considerations

### 1.1 Assumptions

The underlying assumption:

* the users are familiar with android devices. 
* the users are familiar with the language and the symbols utilized by the application. 

### 1.2 Constraints

*Describe any constraints on the system that have a significant impact on the design of the system.*

* The application is designed only for one user per device. There is no method to manage multiple user profiles on the same device. 
*  The application can only be accessed through mobile phones and tables, is not designed for utilization with other devices. 
* The application is implemented through Android Studio and Java it can only be utilized by Android operating systems. Any devices with an API lower than L21 (Lollipop 5.0) cannot use the application.

### 1.3 System Environment

* The application is implemented through Android Studio and Java it can only be utilized by Android operating systems. Any devices with an API lower than L21 (Lollipop 5.0) cannot use the application. 
* Furthermore, the application can only be ran on a mobile devices or a tablet. 

## 2 Architectural Design

### 2.1 Component Diagram

<img src= "https://github.com/qc-se-spring2021/370Spring21Sec55Team1/blob/main/GroupProject/Docs/Pictures/ComponentDiagram.png" alt="Component Diagram">

* The ListManager contains operations that are able to make changes to the List, such as creating, deleting, and selecting lists. The itemList contains operations that are able to interact with ItemType, which in turn provides the user the capability to look through the items of each type from the database. 

### 2.2 Deployment Diagram

<img src= "https://github.com/qc-se-spring2021/370Spring21Sec55Team1/blob/main/GroupProject/Docs/Pictures/DeploymentDiagram.png" alt="Deployment Diagram">

The application works locally on the device that it is installed on thats why the deployment diagram is simple. 

## 3 Low-Level Design

### 3.1 Class Diagram

<img src= "https://github.com/qc-se-spring2021/370Spring21Sec55Team1/blob/main/GroupProject/Docs/Pictures/ClassDiagram.png" alt="Class Diagram">

### 3.2 Other Diagrams

Described in usecase model. 

## 4 User Interface Design

This design is subject to change, it is a temporary mockup to showcase the approximate appearance of the application. 

<img src= "https://github.com/qc-se-spring2021/370Spring21Sec55Team1/blob/main/GroupProject/Docs/Pictures/1HOME%401x.png" alt="1">

[^]: This is the initial page home page the users sees when they initially launch the application.



<img src= "https://github.com/qc-se-spring2021/370Spring21Sec55Team1/blob/main/GroupProject/Docs/Pictures/2USER%20LIST%401x.png" alt="2">

[^]: In this page the user can view the lists they created previously. Furthermore, in this page the user will have the option to create new list using the orange button at the bottom of the screen. The three dots in the upper corner is a dropdown menu.



<img src= "https://github.com/qc-se-spring2021/370Spring21Sec55Team1/blob/main/GroupProject/Docs/Pictures/3USER%20LIST-DropDown%401x.png" alt="3">

[^]: This is the dropdown menu from clicking the dots are shown here.



<img src= "https://github.com/qc-se-spring2021/370Spring21Sec55Team1/blob/main/GroupProject/Docs/Pictures/4USER%20LIST-Select%20A%20List%401x.png" alt="4">

[^]: This image shows how the user screen would look like if the list was check marked.



<img src= "https://github.com/qc-se-spring2021/370Spring21Sec55Team1/blob/main/GroupProject/Docs/Pictures/5USER%20LIST-Rename%20List%401x.png" alt="5">

[^]: This image shows how the user screen would look like if the user choose to rename the list from the dropdown.



<img src= "https://github.com/qc-se-spring2021/370Spring21Sec55Team1/blob/main/GroupProject/Docs/Pictures/6CREATE%20LIST%401x.png" alt="6">

[^]: This image shows the user creating a new list after they click on the orange button to add a new list. Where a new box appears to which promotes the user to enter a name for the new list. 





<img src= "https://github.com/qc-se-spring2021/370Spring21Sec55Team1/blob/main/GroupProject/Docs/Pictures/7ADD%20ITEMS%401x.png" alt="7">

[^]: In this page the user can view the items they previously added to the list. Furthermore, in this page the user will have the option to add new items using the orange button at the bottom of the screen. The three dots in the upper corner is a dropdown menu.

 

<img src= "https://github.com/qc-se-spring2021/370Spring21Sec55Team1/blob/main/GroupProject/Docs/Pictures/8USER%20ITEM-DropDown%401x.png" alt="8">

[^]: This is the dropdown menu from clicking the dots from the item's page are shown here.

 

<img src= "https://github.com/qc-se-spring2021/370Spring21Sec55Team1/blob/main/GroupProject/Docs/Pictures/9USER%20ITEM-CheckOff%401x.png" alt="9">

[^]: This image shows how the user screen would like if an item is checked marked.



<img src= "https://github.com/qc-se-spring2021/370Spring21Sec55Team1/blob/main/GroupProject/Docs/Pictures/10SEARCH%20ITEMS-Type%401x.png" alt="10">

[^]: This is the screen the user would see if they try to add items by clicking on the orange button sign from previous page also known as My List. 



<img src= "https://github.com/qc-se-spring2021/370Spring21Sec55Team1/blob/main/GroupProject/Docs/Pictures/11SEARCH%20ITEMS-Cereal%401x.png" alt="11">

[^]: This is the next screen the user views when they click on a catagory from a previous page. They would have the option to choose from the selected, or can search.  





<img src= "https://github.com/qc-se-spring2021/370Spring21Sec55Team1/blob/main/GroupProject/Docs/Pictures/12SEARCH%20ITEM-Others%401x.png" alt="12">

[^]: This is the next screen the user views when they click on the others catagory from a previous page. They would have the option to choose from the selected, or can search.



<img src= "https://github.com/qc-se-spring2021/370Spring21Sec55Team1/blob/main/GroupProject/Docs/Pictures/13SEARCH%20ITEM-Name%401x.png" alt="13">

[^]: This image gives the user suggestions of items as the users inputs the item name. 



<img src= "https://github.com/qc-se-spring2021/370Spring21Sec55Team1/blob/main/GroupProject/Docs/Pictures/14ITEM%20NOT%20FOUND%401x.png" alt="14">

[^]: This image shows when a match is not found for the input given by the user, and the "CREATE ITEM" button would pop up allowing the user to create new item and add to the database. 



<img src= "https://github.com/qc-se-spring2021/370Spring21Sec55Team1/blob/main/GroupProject/Docs/Pictures/15ITEM%20DETAILS%401x.png" alt="15">

[^]: This image shows the screen the user sees when they try to create a new item to add to the database. 



<img src= "https://github.com/qc-se-spring2021/370Spring21Sec55Team1/blob/main/GroupProject/Docs/Pictures/16ITEM%20DETAILS_Example_Database%401x.png" alt="16">

[^]: This image shows when the user would click on the button the item would be added to the database and to the list with a default quantity of one. If the user would want to change the quantity they have to change it in the intem page. 