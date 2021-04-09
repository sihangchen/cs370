This is a file used to note down errors located during User side/blackbox testing.  To the best of the test of ability, they will note down the actions causing the error, the result of the error and if possible guess at the cause. The file will also record any QOL changes or functionality changes that are desired (but may not be implemented untill D4 or at all). There will be no unified structure to individual entries. 



### Error/Bug Log 

2. Lists can retain multiple identical entries. (My lists and Item List pages) 

3. Random crashes and hangups during CRUD operations within the list manager. Cause unknown 

4.  Item List CRUD functionalities not available at the moment 

5. Item List header displays an incorrect prompt/title. 

6.  There is no consistently provided "back" button within the app

7.   Using the back button of the phone is inconsistent. It will sometimes bring you to the last viewed page, other times it will bring you to the previous page in interaction hiearchy (desired). 

8.  Cancel button on Add Item page returns you to the List Manager page. (It should return you to the respective Item Select page)

9.   Confirm button on Add Item page returns you to the Item Select page. It should return you to the item list page? (Unknown if desirable) 

10.  Unknown upper value range for item quantity. Inability to manually input values to check. (I will not click the + button several thousand times) 

11.  Item List cannot display quantites of 3 or more digits properly.

12.   By Category and By name interactables are not buttons, but select markers. They do not visually deactivate upon use. On press remains same.

13.   Item search bar has a button before input bar appears (Intentional?) 

14.  Item Search bar in BY ITEM is not persistent. It is a single use filter, does not reactivate upon returning to the page.

15.   Item Search bar in BY ITEM does not reset upon usage. Previous inputs remain but the lists do not remain filtered. 

16.  Pressing back on the List Management page will take you back to the Add item page if it was the previously viewed page. 

17.  Random unecessary toast warnings scattered throughout program.   

  

### Confirmed fixes 

1. Longclicks no longer crash the application. (HOWEVER may be interpreted as single clicks)
2. List names cannot be blank, there is a warning. 
3. List names can handle upper/lower case, numerical, and special symbol inputs of various combinations.
4. Extremely long list names are accepted ( HOWEVER THEY CAUSE A STALL/RESET/CRASH, unknown if Error 3 or different)
5.  Item List Checkmark functionality now enabled 





### QOL

1. Having to input individual list names to delete/rename is clunky. Recommendation to integrate features into individual entry views if able. 
2.  Having a delete all button in list manager is EXTREMELY HIGH RISK and undesirable.
3.  Picture only item categories is undesirable. Interpretation is Subjective, and not intuitive.
4.  Requires ability to add new item categories/views to the database. 