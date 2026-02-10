# Experiment 5: Study of Dictionaries in Python

## Aim

To study the concept of **dictionaries in Python** and perform operations such as storing, 
accessing, searching, and updating data using key–value pairs.


## Theory

A dictionary in Python is a powerful built-in data type used to store and manage data as **key–value pairs**. In a dictionary, each **key** serves as a unique 
identifier (or label), and each **value** is the piece of data associated with that key. This structure makes dictionaries especially useful when you want to quickly look up, 
update, or organize information.

Dictionaries are defined using **curly braces `{}`**, where each key is followed by a colon `:` and its corresponding value. Multiple key–value pairs are separated by commas. 
For example, a dictionary can store details like names and ages, product IDs and prices, or words and their meanings.

One important feature of dictionaries is that **keys must be unique and immutable** (such as strings, numbers, or tuples), while **values can be of any data type** and can be changed.
Dictionaries are also **unordered collections** (though in modern Python versions, they preserve insertion order), meaning items are accessed by their keys rather than by position.

Overall, dictionaries provide a fast and flexible way to store structured data, making them one of the most commonly used data types in Python.


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

## Algorithms:
- Start
- Create dictionaries using {}
- Handle duplicate keys (latest value retained automatically)
- Update values using dictionary[key] = value
- Retrieve values safely using dictionary.get(key, default)
- Accept user input using input()
- Validate login using if dictionary.get(key) == value
- Find the highest value using max(dictionary, key=dictionary.get)
- Display results using print()
- Stop

- ✅ Algorithm – Problem 1
- (Create dictionary and update value)
- Start
- Create a dictionary products with product names as keys and prices as values
- Display the original dictionary
- Update the value of key "Book" to 65
- Display the updated dictionary
- Stop

- ✅ Algorithm – Problem 2
- (Search student marks using .get() method)
- Start
- Create a dictionary students_marks with student names as keys and marks as values
- Read the student name from the user
- Use get() method to retrieve marks
- If the name exists, display the marks
- Else, display "Student not found"
- Stop

- ✅ Algorithm – Problem 3
- (User login validation using dictionary)
- Start
- Create a dictionary users with usernames as keys and passwords as values
- Read username and password from the user
- Compare entered password with the value stored for the username
- If both match, display "Login Successful"
- Else, display "Login Failed"
- Stop

- ✅ Algorithm – Problem 4
- (Find topper from marks dictionary)
- Start
- Create a dictionary marks with student names as keys and marks as values
- Use max() function with key=marks.get to find highest marks
- Store the topper name
- Display the topper name and their marks
- Stop


## Conclusion

In this experiment, dictionaries in Python were studied and implemented. The programs demonstrated storing data in key–value form, 
searching, updating, and analyzing values. The DIY problems showed real-life applications like login validation and result analysis. This 
experiment helped in understanding how dictionaries are useful for structured data storage and retrieval.
