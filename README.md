# Uber-Replication-Model
A small scale Uber replication model built using graphs, structures, classes, etc and algorithms like djikstra's shortest path, heapsort, etc.
The main objective of the project is to handle the management, movement and finances of cabs and their customers using various data structures in
an effective manner.

There will be two interfaces of the cab management server: -

(i) User /customer Interface: It will give the customers the ability to enter their pickup and destination location and several other functionalities like:

● Apply coupons available with them.

● Rate the drivers based on the service provided.

● Change or update the personal details.

(ii) Cab Driver Interface: It will calculate the total price of each ride taken by a particular customer that the driver will receive.

● Calculate the total earning per day of each driver.

● Allow the drivers to update their current location so as to synchronize them with the locality tree.

● Cabs available in a locality will be ordered according to the rating given by each customer.

Data Structures used:

● Tree – for making the classification of localities.

● Queue – customers will be inserted in the queue on clicking the ride now option.

● Priority Queue – if a customer clicks on ride later option, then they will be inserted into the priority queue with the time at which they want to take the cab.

● File Handling – managing the details of cabs and customers’ personal information

● Linked List – used for storing the various destinations wherein the rate between two nodes will be fixed.

● Stack, Graph and Standard Template Libraries may also be used in various functionalities.