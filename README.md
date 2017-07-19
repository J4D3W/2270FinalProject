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
//- Choose your own adventure story 
//  - Implament a binary tree for character creation
//    Root - choose a name-> update
//      -male -> left
//            - magic user
//              - starting at node
//              - starting at node
//            - fighter
//             - starting at node
//             - starting at node
      
//      -female ->right
//            - magic user
//              - starting at node
//              - starting at node
//            - fighter
//              - starting at node
//              - starting at node

could have other options, such as nationality which would determine starting nodes. This tree would build a struct "character" which would be used for reference for the story telling "choose your own adventure" map Graph. It would be referenced for correct pronouns throught the story. Weights would be based on the "goodness" of the decision, how "nice" your choice is. Some one needs help. Do you help? yes = 2, no = 1. The "score" at the end of the game is the total weight added up. If you help EVERYONE your score will be higher than if you help no one. If you help no one, clearly you will have the shortest path through the story. 

The graph would contain a "story web" 
- You would be able to choose the option to "finish story now" which would take you from your current position to the nearest ending, printing each leg of the journey. 
- You could also make choices and reach the ending naturally. 

// The Final project has the following requirements:
// - Contains at least 1 class : Graph Class, potentially another class for the flight price storage, BST maybe
// - Contains at least one graph and one other data structure: see above
// - Class should contain 7 public methods: 
//        (( potential public methods))
//        - find start point
//        - find destination
//        - find total score
//        - find best karma path
//        - find worst karma path
//        - print map - route taken so far
//        - print all map points
// - Contains a well documented driver to run your code (Will need for testing anyhow)

