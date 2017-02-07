Assignments
-----------
-----------

This is a list of projects to do and things to build in order to completely understand [Algorithms](http://www.cse.iitd.ernet.in/~naveen/courses/CSL630/all.pdf) by Sanjoy Dasgupta, Christos Papadimitriou, and Umesh Vazirani.

Feel free to add to it should you think of any useful exercises or find any cool resources.

You may build these in any langauge. I suggest a dynamic language like Python or JavaScript. These are good for interviews because they're generally more permissive, so things can be written in them with fewer lines of code (better for cramming stuff onto a whiteboard).

For any algorithm you write, you MUST include a comment with it's runtime before the function decalaration.

### These are not made to be easy.

Day 00
------

* mini-calc: write a function that takes two numbers of ANY SIZE with an operator in between them and outputs the result of the operation.

..* only need to handle +, -, *, and /

⋅⋅* examples: ./mini-calc 123456789000 + 987654321000

⋅⋅* 1111111110000

⋅⋅* ./mini-calc 217340927348 * 982734927340

⋅⋅* 213588520445344998894320

⋅⋅* ./mini-calc 2 / 2

⋅⋅* 1

⋅⋅* You need not implement full error-handling (do watcha want, Moulinette ain't gunna get yat)

* implement a hash table/map

⋅⋅* [wikipedia](https://en.wikipedia.org/wiki/Hash_table)

⋅⋅* would be wise to implement the hash function used in the hash literal for whichever language your using (assuming you aren't using C... if you are then use whichever pleases you!)

⋅⋅* implement the following functions (make methods of the hash table object if OOP)

⋅⋅* you DO NOT need to name them like this - feel free to use whatever convention your langauge suggests.

⋅⋅* hash_map_name.len returns the total number of elements in the map

⋅⋅* hash_map_name.get_val(key_name) returns the value associated with key_name or NULL if key_name doesn't exist in hash map

⋅⋅* hash_map_name.set_val(key_name, val_name) sets the value associated with key_name to val_name

⋅⋅* hash_map_name.pop(key_name) removes the key_name from the map and returns the value associated with key_name

⋅⋅* hash_map_name.keys() returns an array of all the keys in hash map

⋅⋅* hash_map_name.values() returns an array of all the values in hash map

* find_sum: given an unsorted array of integers, find a pair that sum to a given number and return their locations in the array

⋅⋅* use your hash table for fastest time! (To be complete, this must be done :) )

⋅⋅* the last number passed via commandline will be the desired sum

⋅⋅* examples: ./find_sum 1 2 3 4 5 8

⋅⋅* (2, 4)

⋅⋅* ./find_sum 1 2 3 4 5 6

⋅⋅* (0, 4) OR (1, 3) - you don't need to write 'OR', you can just give either answer and still be considered correct

⋅⋅* ./find_sum 1 2 3 4 5 10

⋅⋅* NO SOLUTION

* (bonus) implement RSA encryption

⋅⋅* [wikipedia](https://simple.wikipedia.org/wiki/RSA_(algorithm))

⋅⋅* Good luck ;)
