# Banker-s-Algorithm
The banker’s algorithm is a resource allocation and deadlock avoidance algorithm that tests for safety by simulating the allocation for predetermined maximum possible amounts of all resources, then makes an “s-state” check to test for possible activities, before deciding whether allocation should be allowed to continue.

This is the source code file.The source code is written in C language. But can be migrated easily in JAVA/Python etc.
Assuming OS has 3 sources to give to the processes.
User enters no. of process and resources required to complete execution for each process.
Algorithm outputs order in which processes should to avoid deadlock,which is nothing but a  safe sequence.
if safe sequence is not possible ,algorithm outputs DEADLOCK
