# Narrative For Category 2: Data Structures & Algorithms

The artifact I selected for this enhancement is a C++ program that I built in December of
2023 during CS-300: Data Structures & Algorithms at Southern New Hampshire University. The
application called “Course Planner” is a program that helps manage and organize academic
courses with their prerequisites. The program implements algorithms that read course data from a
text file called “courses.txt” where each line contains a course number, course name, and any
prerequisite courses separated by commas. It provides a menu-driven interface allowing users to
load the course data into memory, display a sorted list of all available courses with their
prerequisites, search for specific courses by course number, or exit the program.
I selected this course planner artifact for my ePortfolio because it demonstrates a
comprehensive understanding of fundamental data structures and algorithms while showing clear
progression from basic to advanced implementations. The original artifact used simple linear
data structures (vectors) and basic algorithms (linear search, standard library sort), while the
enhanced version showcases sophisticated computer science concepts including hash tables for
O(1) lookups, graph data structures with adjacency lists for modeling prerequisite relationships,
and custom merge sort implementation guaranteeing O(n log n) performance. The specific
components that highlight my skills include the CourseHashTable class that replaces O(n) linear
search with O(1) hash-based retrieval, the PrerequisiteGraph class implementing adjacency lists
and breadth-first search traversal for complex relationship analysis, and the MergeSort class
providing guaranteed logarithmic performance compared to standard library sort functions that
can degrade to O(n²) in worst-case scenarios. The artifact was improved by replacing inefficient
linear operations with optimized data structures, adding graph-based prerequisite analysis
capabilities, implementing custom sorting algorithms, and maintaining clean object-oriented
design principles with proper encapsulation and documentation.
Yes, I successfully met the planned course outcomes for data structures and algorithms
enhancement. The artifact demonstrates proficiency of hash table implementation and collision
handling, showcases graph theory application through the PrerequisiteGraph with adjacency list
representation and BFS traversal, and exhibits algorithm analysis understanding by comparing
time complexities (O(1) vs O(n) for search operations, O(n log n) guaranteed vs potential O(n²)
for sorting). The enhancement also meets outcomes related to software design and engineering
by implementing clean class hierarchies, proper encapsulation, comprehensive documentation,
and error handling. My outcome-coverage plans remain on track, as this artifact effectively
bridges multiple computer science concepts, but particularly in data structures and algorithms.
The enhancement process taught me valuable lessons about the practical trade-offs
between different data structures and the importance of algorithmic efficiency in real-world
applications. While implementing the hash table, I gained a deeper understanding of how modern
C++ containers like unordered_map work internally. The most challenging aspect was
implementing the PrerequisiteGraph class, particularly the BFS algorithm for finding available
courses after prerequisite completion, which required careful consideration of graph traversal
logic and state management. I also learned about the subtle differences between various sorting
algorithms when implementing merge sort, discovering that while std::sort is highly optimized
for average cases, custom implementations can provide guaranteed performance characteristics
and better suit specific use cases.