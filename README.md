# Round-Robin-Process

The name of this algorithm comes from the round-robin principle, where each person gets an equal share of something in turns. 
It is the oldest, simplest scheduling algorithm, which is mostly used for multitasking. 
In Round-robin scheduling, each ready task runs turn by turn only in a cyclic queue for a limited time slice. 
This algorithm also offers starvation free execution of processes.

Characteristics

➢ Round robin is a pre-emptive algorithm 
➢ The CPU is shifted to the next process after fixed interval time, which is called time quantum/time slice. 
➢ The process that is preempted is added to the end of the queue. 
➢ Round robin is a hybrid model which is clock-driven 
➢ Time slice should be minimum, which is assigned for a specific task that needs to be processed. However, it may differ OS to OS. 
➢ It is a real time algorithm which responds to the event within a specific time limit. 
➢ Round robin is one of the oldest, fairest, and easiest algorithm. 
➢ Widely used scheduling method in traditional OS.
