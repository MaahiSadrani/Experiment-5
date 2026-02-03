# Experiment 5: Study of Dictionaries in Python

## Aim

To study the concept of **dictionaries in Python** and perform operations such as storing, 
accessing, searching, and updating data using key–value pairs.


## Theory

A dictionary in Python is a built-in data type used to store data in the form of **key–value pairs**. Each key acts like a label,
and each value is the data associated with that label. Dictionaries are written using curly braces {} with keys and values separated by a colon.

### Key Features of Dictionaries

* Key–Value Structure: Every element has a key and a value.
* Unique Keys: No two keys can be the same. If a duplicate key is used, the latest value replaces the old one.
* Mutable: Values can be added, changed, or removed after creation.
* Fast Access: Values can be accessed quickly using their keys.
* Mixed Data Types:Values can be integers, strings, lists, etc.

### Common Dictionary Methods and Functions

* dict[key] → Access value using key
* get(key) → Safely access value without error if key is missing
* keys() → Returns all keys
* values() → Returns all values
* items() → Returns key–value pairs
* update() → Updates dictionary
* pop() → Removes an element using key
* len() → Finds number of items in dictionary
* max() → Finds maximum value (useful in marks problems)

### Why Dictionaries are Useful
Dictionaries are very useful when data must be stored with identifiers. For example:
* Student records
* Product price lists
* Login credentials
* Mark sheets
They make searching and updating data easy and efficient compared to lists.

## Algorithms (Problem Statements Only)

### Problem Statement 1: Unique Event Participants
1. Create a list of participant names containing duplicates.
2. Convert the list into a set.
3. Display the set to show only unique participants.

### Problem Statement 2: Common Elective Subjects
1. Create three sets for subjects chosen by students.
2. Use intersection operation to find common subjects.
3. Display the common subjects.

### Problem Statement 3: Students in Sports Clubs
1. Create two sets for cricket and football club members.
2. Use intersection to find students in both clubs.
3. Use symmetric difference to find students in only one club.
4. Display the results.

### Problem Statement 4: Absent Students
1. Create a set of all students.
2. Create a set of present students.
3. Use set difference to find absent students.
4. Display the absent students.
 
### Problem Statement 5: Remove Invalid Course Code
1. Create a set of valid course codes.
2. Identify the discontinued code.
3. Use discard() to remove it from the set.
4. Display the updated set.

## Conclusion

In this experiment, dictionaries in Python were studied and implemented. The programs demonstrated storing data in key–value form, 
searching, updating, and analyzing values. The DIY problems showed real-life applications like login validation and result analysis. This 
experiment helped in understanding how dictionaries are useful for structured data storage and retrieval.
