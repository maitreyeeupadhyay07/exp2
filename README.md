EXPERIMENT 2 : STUDY OF LIST IN PYTHON 

MAITREYEE UPADHYAY 25070123071

THEORY:
In this experiment we learned how to use and edit lists in python. We added elements to list, removed elements from list, sorted elements of list,etc.
list.append() is used to add elements into the list, list.remove() is used to remove elements from list, max() is used to find maximum , min() used to find minimum, len() is used to find length of list.
list1.extend(list2) is used to merge two lists.
list[2] is used to find third element of the list.

 Accessing List Elements (Indexing and Slicing):

    Indexing: Individual elements in a list can be accessed using an index, which represents the position of the item. Python uses zero-based indexing, meaning the first item is at index 0. Negative indexing allows you to access elements from the end of the list, where -1 refers to the last item. Cell D5tq7Zdew-44 beautifully illustrates both positive (list4[2]) and negative (list4[-4]) indexing.
    Slicing: You can extract a portion (sub-list) of a list using slicing. The syntax list[start:end] returns elements from start (inclusive) up to end (exclusive). If start is omitted, it defaults to 0. If end is omitted, it defaults to the end of the list. Examples in cell D5tq7Zdew-44 include list4[2:5], list4[:4], and list4[2:].

 Modifying Lists:

    Changing Elements: You can change a specific element by referring to its index and assigning a new value, as shown in cell (list5[1]=2).
    Adding Elements:
        append(): Adds a single item to the end of the list. Cells list6 and list10 demonstrate this with list6.append("mango") and list10.append("mango").
        insert(): Adds an item at a specified index. The existing items shift to the right. Cell moArYfmG1YHO shows list7.insert(1,"mango").
        extend(): Adds all items from another iterable (like another list) to the end of the current list. Cell 7WN8RjZL2TuG uses list8.extend(list9).
    Removing Elements:
        remove(): Removes the first occurrence of a specified value from the list. list10 demonstrates list10.remove("eggs").

 Built-in List Utility Functions:


    max(): Returns the item with the highest value in a list (e.g., max_marks = max(marks)).
    min(): Returns the item with the lowest value in a list (e.g., min_marks = min(marks)).
    len(): Returns the number of items in a list (e.g., total_numberofstudents = len(marks)).
    sum(): Returns the sum of all items in a list (for numerical lists) (e.g., sumofmarks = sum(marks)).
    sort(): This is a list method that sorts the list in-place (modifies the original list) in ascending order by default (e.g., marks.sort()).


Algorithm:
a) Analyzing Student Marks

    1)Initialize Data: Create a list containing the numerical marks of the students.
    
    2)Find Extremes:
    
        Identify the highest value in the list (max()).
        
        Identify the lowest value in the list (min()).
        
    3)Count Entries: Determine how many items (students) are in the list(len()).
    
    4)Calculate Totals: * Add all the marks together to get the Sum(sum()).
    
    5)Calculate the Mean: Divide the Sum by the Total Number of Students to find the Average(sum()/len()).
    
    6)Organize Data: Sort the list of marks from the lowest value to the highest value (Ascending Order)(list.sort()).
    
    7)Display Results: Print all the calculated values and the sorted list to the screen.

b)Modifying a Grocery List

    1)Create the List: Start with an initial list of five items: carrot, potato, spinach, eggplant, and cheese.
    
    2)Add an Item: Update the list by adding "milk" to the very end using ".append("milk")" command.
    
    3)Remove an Item: Search for "potato" in the list and delete it using ".remove("potato")" command.
    
    4)Remove another Item: Search for "carrot" in the list and delete it using ".remove("carrot")" command.
    
    5)Output Results: Display the final, updated version of the list.

Conclusion:
Hence lists were implemented in python and operations were done on the lists.
