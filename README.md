# oracleSQLairportProg

C++ program that connects to oracle to use SQL to retrieve data.

The following relations keep track of airline flight information: 
•	Flights(flno: integer, from: string, to: string, distance: integer, departs: time, arrives: time, price: real)
•	Aircraft(aid: integer, aname: string, cruisingrange: integer)
•	Certified(eid: integer, aid: integer)
•	Employees(eid: integer, ename: string, salary: integer)

Write an Oracle bgunix C++ program to query these tables. Use C++ classes (not plain old c) with many member functions - modify my sample program as needed. The “X’s” noted below are terminal inputs, given trough cin (terminal input). 

Query options:
1.	Find the names of aircraft such that all pilots certified to operate them have salaries over $80,000.
2.	For each pilot who is certified for more than X1 aircrafts, find the eid and the maximum cruisingrange of the aircraft for which she or he is certified.
3.	Find the aids of all aircraft that can be used on routes from X3 to X4.

