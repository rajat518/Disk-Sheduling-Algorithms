Disk Scheduling is the process of deciding which of the cylinder request is in the ready queue is to be accessed next.The access time and the bandwidth can be improved by scheduling the servicing of disk I/O requests in good order.
Access Time: The access time has two major components:  Seek time and Rotational 
                            Latency.           
Seek Time: Seek time is the time for disk arm to move the heads to the cylinder containing 
                       the desired sector.
Rotational Latency: Rotational latency is the additional time waiting for the disk to rotate  
                                     the desired sector to the disk head.
Bandwidth:The disk bandwidth is the total number of bytes transferred, divided by the total 
                      time between the first request for service and the completion of the last transfer.
ALGORITHM:
1.	Input the maximum number of cylinders and work queue and its head starting  
             position.
2.	 First Come First Serve Scheduling (FCFS) algorithm – The operations are 
              performed in order requested.
3.	 There is no reordering of work queue.
4.	Every request is serviced, so there is no starvation.
5.	The seek time is calculated.
6.	Shortest Seek Time First Scheduling (SSTF) algorithm – This algorithm 
             selects the request with the minimum seek time from the current head  
              position.
7.	Since seek time increases with the number of cylinders traversed by the head,   
             SSTF chooses the pending request closest to the current head position.
8.	The seek time is calculated.
9.	SCAN Scheduling algorithm – The disk arm starts at one end of the disk, and  
            moves toward the other end, servicing requests as it reaches each cylinder, 
             until it gets to the other end of the disk.
10.	At the other end, the direction of head movement is reversed, and servicing 
             continues.
11.	The head continuously scans back and forth across the disk.
12.	The seek time is calculated.
13.	Display the seek time and terminate the program
