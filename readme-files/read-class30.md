>Let's dive into the concept of hash tables and explore how they work. Hash tables are data structures that allow efficient storage and retrieval of key-value pairs. They are widely used in computer science and provide fast access to data based on a unique key.

# WHY:
>Hash tables are valuable because they offer constant-time average case complexity for inserting, deleting, and searching elements. They are particularly useful when you have a large dataset and need to perform frequent data operations quickly.

# WHAT:
>A hash table consists of an array (or sometimes called a bucket) and a hash function. The array is used to store elements, and the hash function maps each key to a unique index in the array. The hash function takes the key as input and produces a fixed-size hash code, which is used to determine the index.

# HOW:
>Let's walk through a step-by-step example to understand how hash tables work:

## Initialization:

>Create an empty array with a fixed size, let's say 10.

>Define a hash function that converts keys into indices within the array.
# Insertion:

>Suppose we want to insert a key-value pair: ("apple", 5).

>Apply the hash function to the key "apple" and determine the index. Let's say the hash code is 7.

>Store the value 5 at index 7 in the array.
# Retrieval:

>To retrieve the value associated with the key "apple", apply the hash function to the key.

>Obtain the index where the value is stored, let's say it's 7.

>Access the element at index 7 in the array and retrieve the value.
# Collision Handling:

>Sometimes, different keys may produce the same hash code, leading to collisions.

>If a collision occurs, we need a strategy to handle it. One common approach is using separate chaining.

>Instead of storing a single value at each index, we maintain a linked list or another data structure to handle multiple values that map to the same index.
## Deletion:

To delete a key-value pair, use the hash function to find the index of the key.
Locate the element at that index and remove it from the data structure.
Quiz:

# What is the purpose of a hash table?
# What are the advantages of using a hash table?
# How does a hash table handle collisions?
# What is the time complexity for average case operations in a hash table?
## Vocabulary/Definition List:

>Hash Table: A data structure that provides efficient storage and retrieval of key-value pairs.

>Hash Function: A function that converts keys into unique hash codes used to determine the index in a hash table.

>Collision: A situation where different keys produce the same hash code.

>Separate Chaining: A collision resolution technique where multiple values that map to the same index are stored in a linked list or another data structure.

>Average Case Complexity: The expected time complexity for operations in a data structure based on the statistical distribution of inputs.

# Cheat Sheet:

>Hash tables provide fast access to data based on a unique key.

>They consist of an array and a hash function.
>
The hash function maps keys to indices in the array.

>Collisions can occur when different keys produce the same hash code.

>Collision handling strategies include separate chaining.
Hash tables have constant-time average case complexity for operations.

>Common operations include insertion, retrieval, and deletion.