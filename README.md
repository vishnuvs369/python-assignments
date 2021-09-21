# Q8. What is major difference b/w list and tuple?

List and Tuple in Python are the class of data structure. The list is dynamic, whereas the tuple has static characteristics. 
List is just like the arrays, declared in other languages. Lists need not be homogeneous always which makes it the most powerful tool in Python. In Python, the list is a type of container in Data Structures, which is used to store multiple data at the same time. Lists are a useful tool for preserving a sequence of data and further iterating over it. 
Syntax: 

list_data = ['an', 'example', 'of', 'a', 'list']
Tuple is also a sequence data type that can contain elements of different data types, but these are immutable in nature. In other words, a tuple is a collection of Python objects separated by commas. The tuple is faster than the list because of static in nature. 
Syntax:  

tuple_data = ('this', 'is', 'an', 'example', 'of', 'tuple')


# Q9.What is a set?

A Set is an unordered collection data type that is iterable, mutable and has no duplicate elements. Python’s set class represents the mathematical notion of a set. The major advantage of using a set, as opposed to a list, is that it has a highly optimized method for checking whether a specific element is contained in the set. This is based on a data structure known as a hash table. Since sets are unordered, we cannot access items using indexes like we do in lists.

# Python program to demonstrate sets

# Same as {"a", "b", "c"}
myset = set(["a", "b", "c"])
print(myset)

# Adding element to the set
myset.add("d")
print(myset)
