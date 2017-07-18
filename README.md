# 2270FinalProject

// Erin "Jade" Wibbels
// CSCI 2270 - Professor Montero Quesada
// Final Project Phase 1 - Due 7/21 5pm

// Objectives:(with brainstorming comments)
// - Implement algorithms for standard operations on common data structures and discuss complexity of the operations.
// - Comment on the features of different traversal methods for graphs and other data structures.
// - Formulate and implament solutions to problems using fundamental graph algorithms (ie depth first/breadthfirst searches and 
//   shortest path algorithms.


// Phase 1 design plan::
// Design and implement a program which will read in flight info: starting point, destination point, flight duration and cost. These
// elements will then be used to construct 2 instances of a graph. The difference between the 2 graphs will be the edges, one will 
// be weighted by cost, the other by time. This program will plan a travel itenerary based on the hourly income of the user. 
// The user will input their hourly income. The program will find the shortest (time) route and the cheapest route and then check the 
// difference in time and in money saved. If the money saved is above a certain % of the users income it will book the longer flight.
// If not it will book the shorter flight.
// The user will be able to see both shortest time and cheapest route, (( IF I can figure it out, it will check the savings for each leg 
// of the journey. That way it is the perfect flight for their income level. )) The program will print out a flight itinerary with
// prices and times as well as total price and total travel time. There will also be an option to see ALL the available flights (with
// times and prices). 

// Design and implement Graph program which finds "shortest path" for flights and compare it to cost using queues and stacks ( may need 
// another adt such as BST which will contain structs detailing the prices of all flights for prog requirements.) The idea being the 
// program will only accept a shortest path if it meets predesignated cost benefit standards for time and user income. If not it will 
// accept the next "shortest" path.
// For each potential path the program will run a cost anaylsis, which compares travel time vs price and does opportunity cost 
// comparison on flight time vs flight cost based on user income.
// Other concept:: store both in Graphs and compare shortest price with shortest time... might simplify.


// The Final project has the following requirements:
// - Contains at least 1 class : Graph Class, potentially another class for the flight price storage, BST maybe
// - Contains at least one graph and one other data structure: see above
// - Class should contain 7 public methods: 
//        (( potential public methods))
//        - find start point
//        - find destination
//        - find total flight time
//        - find total cost
//        - cost vs flight time analysis
//        - find least layovers
//        - print flight schedule
//        - print all flights available
//        - set user income 
// - Contains a well documented driver to run your code (Will need for testing anyhow)

// NEED TO KNOW
// Edges can have 2 key variables? (I am assuming so, it would make it easier)
