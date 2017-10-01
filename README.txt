The application will help a user calculate the fastest and cheapest way from a desired source to destination. The means of commute will consist of options among the following: bus, self-driving, walking, metro, Ola/Uber cab. The application will suggest optimal ways such that the carbon emissions are also minimized. The application will allow the user to add/remove ways of commute too. We will be using a modified version of Djikstra's Algorithm to calculate the efficient path. A summary of how we plan to tackle the problem is given below: 1. For every origin and destination the set of relevant stops are calculated. 2. For every stop in the network a set of relevant interchange stops are calculated. This set of stops is bounded by a walking distance constraint. 3. For every destination zone in the network the shortest tree is build backwards, starting at the relevant stops for the given destination. the various options to reach a stop are limited by constraints (such as traffic). 4. From the set of stops reached in the previous step, the process is repeated for multiple interchanges. 5. Based on the paths between the stops, the total chain is calculated.


Constraints : 
1. The functionality of the application will be limited to the city of Bangalore (as of now).
2. We will be considering the services of only Ola and Uber for taxis. 
3. Only BMTC bus services will be considered.

We intent to build a smart and easy-to-use application to help the public make efficient commutes in their day to day lives.