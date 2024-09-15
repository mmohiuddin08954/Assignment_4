# Project Overview
This project consists of two main implementations:
HeapSort Algorithm - An algorithm that resorts an array of integers, in ascending order, by the use of a Binary Heap. The implementation creates a max heap and perform the extract max repeatedly, and we can realize that it outputs an array in sorted order. 
Priority Queue (Max-Heap) - A priority queue which was implemented using max-heap where the tasks are put and removed according to the priority level. Priority queue added support for operations as insert to the priority queue, extract from priority queue and change priority of task in the priority queue.
These or other attributes of every task may include task_id, priority, arrival_time, and the deadline. Tasks with higher priority are preferred over the tasks with low priority.

# Running the Code
Prerequisites; 
Make sure Python is installed on your system

# Code Details
#HeapSort Implementation:
The heapify() function makes sure the subtree beginning with index i has the heap property (max-heap). 
The heapsort() function constructs a max heap of the input array and it then sorts this array by removing the largest element in the heap and placing it at the end of the sorted portion of the array.

# Priority Queue Implementation:
PriorityQueue class employs the maximum heap with the root node containing any task with maximum priority. 
One is able to insert tasks using the method insert() while extracting tasks according to priority can be done by using the method extract_max(). The priorities of the tasks can be altered using the method increase_key(). 
The Task class takes details of each task where parameters are task_id, priority, arrival_time, and deadline. The priority is utilized for evaluation of engineering tasks that occur between different tasks.

# Summary of Findings
HeapSort - Heap sort is a well-developed sorting technique which operates under the time complexity of O(n log n). It is especially valuable as a method of dealing with large sets whose space can be optimized since extra space comes in the form of the input array only. 
Priority Queue - Priority queue that is based on Max-heap also handles tasks according to priority by offering better, improved insertion and extraction operations of O(log n). It is especially useful in scheduling problems, task management and resource allocation problems whereby the activities must be prioritized dynamically.
