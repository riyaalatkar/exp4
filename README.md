STUDY OF SETS IN PYTHON

AIM:

To study the concept of sets in Python and understand various set functions and operations such as union, intersection, difference, add, remove, discard, pop, clear, and frozenset, along with implementing real-life programs using these operations.

THEORY: (Functions and Operations Used)
1. set()

Used to create a set in Python.

Removes duplicate values automatically.

Syntax:

s = set(iterable)

2. Unordered Nature of Sets

Sets do not maintain insertion order.

Elements may appear in random order when printed.

3. add()

Adds a new element into the set.

Syntax:

s.add(element)


If element already exists, no change happens.

4. remove()

Removes a specified element from the set.

Syntax:

s.remove(element)


Gives an error if element is not present.

5. discard()

Removes an element if present.

Does not raise an error if element is absent.

Syntax:

s.discard(element)

6. pop()

Removes an arbitrary/random element from the set.

Syntax:

s.pop()


Error occurs if set is empty.

7. clear()

Removes all elements from the set.

Syntax:

s.clear()

8. union()

Combines elements of two sets (no duplicates).

Syntax:

s1.union(s2)


or

s1 | s2

9. intersection()

Returns common elements between sets.

Syntax:

s1.intersection(s2)


or

s1 & s2

10. difference()

Returns elements present in first set but not in second.

Syntax:

s1.difference(s2)


or

s1 - s2
11. Symmetric Difference ^

Returns elements that are in either set but not common.

Syntax:

s1 ^ s2

12. frozenset()

Immutable set (cannot add/remove elements).

Syntax:

fs = frozenset([1,2,3])


___________________________________________________________________________________________________

PROGRAMS WITH ALGORITHMS

Program 1: Unique Event Participants

Aim: To remove duplicate student registrations using sets.

Algorithm
1. Start
2. Create a list of participant names with duplicates
3. Convert the list into a set
4. Print the unique participant names
5. Stop

 
Program 2: Common Elective Subjects

Aim: To find the subjects chosen commonly by all students using intersection.

Algorithm
1. Start
2. Create three sets of subjects for student1, student2, student3
3. Apply intersection operation
4. Store result in common_subjects
5. Print common subjects
6. Stop

Program 3: Cricket and Football Club Students

Aim: To find students in both clubs and only one club.

Algorithm
1. Start
2. Create a set for cricket club students
3. Create a set for football club students
4. Find students in both clubs using intersection
5. Find students only in cricket using difference
6. Find students only in football using difference
7. Display results
8. Stop

Program 4: Absent Students List

Aim: To find absent students using difference operation.

Algorithm:
1. Start
2. Create a set of total students
3. Create a set of present students
4. Subtract present from total set
5. Store result in absent set
6. Print absent students
7. Stop

Program 5: Remove Invalid Course Codes

Aim: To remove discontinued course codes from a set using remove/discard.

Algorithm
1. Start
2. Create a set of valid course codes
3. Remove discontinued code using discard
4. Remove another code using remove
5. Print updated set
6. Stop

CONCLUSION

Thus, we successfully studied the concept of sets in Python, which are unordered collections of unique elements.
We learned various set functions such as add(), remove(), discard(), union(), intersection(), difference(), pop(), clear(), 
and implemented them in real-life examples like student registration, elective subjects, club participation, attendance 
tracking, and course management. Sets provide an efficient way to handle unique data and perform mathematical set operations easily.
