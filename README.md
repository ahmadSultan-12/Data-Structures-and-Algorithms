# Data-Structures-and-Algorithms
EE 4th Semester Course


Problem Statement:
			Contact Book Management Problem
	Solution:
			Hash Table with Separate Chaining
	Explanation:
		In order to maintain and retrieve data for the given problem and to apply different functions, we have to see the data accessing rate i.e. we have to basically look for the search time taken by any ADT. So, first of all, we have arrays and linked lists but they are not time efficient. Their search time is O(N). Then we studied stacks and queues but they have different area of applications in which there is a specific manner to insert and retrieve data. We don’t have the random access over there i.e. it doesn’t suite our requirement. Then comes BST in which the search time is O(logN) but we have another ADT which is more efficient and whose access time is O(1) i.e. Hash Tables. Further in hash tables, we have two collision handler techniques i.e. Open Addressing and Separate Chaining. Between these two, Separate Chaining is best to use according to the project requirements specified like we have to use insertion extensively (Also in the Load function) and linked lists provide a highly efficient way of inserting data and then retrieving it as compared to linear or quadratic probing. Although linked lists have more space complexity (Pointers) but they are very time-efficient. 
