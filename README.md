# operating-system scheduler program
This code provides solution to the following questions

Design a scheduler with multilevel queue having two queues which will schedule the processes on the basis of  pre-emptive shortest remaining processing time first algorithm (SROT) followed by a scheduling in which each process will get 2 units of time to execute. Also note that queue 1 has higher priority than queue 2.  Consider the following set of processes (for reference)with their arrival times and the CPU burst times in milliseconds.
-------------------------------------
Process  Arrival-Time   Burst-Time
-------------------------------------
P1             0      	             5
P2             1             	       3
P3             2                     3
P4             4                     1
-------------------------------------


Calculate the average turnaround time and average waiting time for each process. The input for number of processes  and their arrival time, burst time should be given by the user.








In this program queue 2 can't run until there is any process available in queue 1, i.e queue 1 has higher priority than that of queue 2.





Limitation of this program is if you are choosing x processes to be scheduled make sure to provide them queue no only 1 or 2 because if you choose other queue number program will go into infinite loop.
