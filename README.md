
# SMART PARKING LOT MANAGEMENT SYSTEM

A data-structure–based project that manages parking operations using Array, Queue, and Stack.


## PROJECT OVERVIEW

This project simulates a smart parking lot using core data structures for efficient vehicle handling.

Array → Stores slot availability

Queue → Manages waiting vehicles

Stack → Handles lane-based parking (LIFO)



## OBJECTIVES

Efficient parking slot allocation

Reduce waiting time

Provide real-time slot status

Demonstrate DSA usage in real-world systems


## SYSTEM ARCHITECTURE

Vehicle Arrival → Check Slot (Array)
       ↓ Slot Free → Park Vehicle
       ↓ Slot Full → Add to Queue

Vehicle Exit → Stack Operations (lane-based)
Slot Frees → Next queue vehicle is parked


## DATA STRUCTURES USED

### 1. ARRAY — Parking Slot Management

Stores parking slot status

Fast indexing for finding free slots

Ideal for fixed-size parking lots


### 2. QUEUE — Waiting Vehicle Management

FIFO order

Holds vehicles when parking is full

Ensures fair order of entry


### 3. STACK — Lane-Based Parking

LIFO operation

Cars parked behind each other

Requires popping cars to remove one


## FEATURES

Real-time slot checking

Automatic waiting queue

Lane-based stack handling

Clear display of parking operations



## PROJECT STRUCTURE

main.cpp      → Core system logic  
queue.h       → Queue implementation  
stack.h       → Stack implementation  
array.h       → Parking slot management  
README.md     → Documentation


## WORKING PROCESS

### Vehicle Entry

1. Array is checked for a free slot


2. If slot found → vehicle parked


3. If full → vehicle added to queue



### Vehicle Exit

1. Stack rearranges cars in lane


2. Slot becomes free


3. Queue’s first vehicle is parked


## ADVANTAGES

Reduces congestion

Easy to implement and scale

Efficient space utilization

Perfect demonstration of DSA concepts


## APPLICATIONS

Malls

Hospitals

Airports

Metro & railway stations

Smart city projects


## CONCLUSION

This system shows how arrays, queues, and stacks solve real-world parking problems efficiently.
It provides structured vehicle handling, reduces waiting time, and increases overall parking efficiency.


## DEVELOPED BY

K. Akhil Kumar Reddy
B.Tech – SRM University


