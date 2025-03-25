# week2-python-assignment

# Create an empty list called my_list
my_list = []

# Append elements 10, 20, 30, 40 to my_list
my_list += [10, 20, 30, 40] 

# Insert 15 at the second position (index 1)
my_list.insert(1, 15)

# Extend with [50, 60, 70]
my_list.extend([50, 60, 70])

# Remove the last element
my_list.pop()

# Sort in ascending order
my_list.sort()

# Find and print the index of 30
print("Index of 30:", my_list.index(30))

ANSWERS
2.After appending: [10, 20, 30, 40]
3.After inserting 15: [10, 15, 20, 30, 40]
4.After extending: [10, 15, 20, 30, 40, 50, 60, 70]
5.After popping last element: [10, 15, 20, 30, 40, 50, 60]
6.After sorting: [10, 15, 20, 30, 40, 50, 60]
7.Index of 30: 3
