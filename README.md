EXPERIMENT 2 : STUDY OF LIST IN PYTHON 

MAITREYEE UPADHYAY 25070123071

THEORY:

Lists in Python are ordered collections of items. They are:

    Mutable: Meaning you can change their content (add, remove, or modify elements) after they are created. This is evident in cells like (modifying an element), (appending), (inserting),(extending), and (removing).
    Ordered: The items have a defined order, and this order will not change unless explicitly modified. This allows for indexing and slicing.
    Allow Duplicates: As seen in code, a list can contain multiple instances of the same value.
    Heterogeneous: Lists can contain items of different data types (integers, floats, strings, booleans, etc.) within the same list, as demonstrated by list2 in cell 352huz_HvisC.

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

These concepts form the foundation of working with lists in Python, allowing for flexible data storage and manipulation, which is crucial for many programming tasks.
