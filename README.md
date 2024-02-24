This C program calculates the waiting time and turnaround time for a set of processes using the first-come-first-serve (FCFS) scheduling algorithm. Here's a breakdown of the program:

Function Definitions:

findWaitingTime: This function calculates the waiting time for each process based on their burst time and the waiting time of the previous process.
findTurnAroundTime: This function calculates the turnaround time for each process by adding the burst time and waiting time of each process.
findAvgTime: This function calculates the average waiting time and average turnaround time for all processes and prints the details of each process along with these averages.
Main Function:

It first prompts the user to enter the number of processes.
Then, it asks for the arrival time and burst time for each process.
After inputting the necessary data, it calls the findAvgTime function to calculate and print the average waiting time and average turnaround time.
Usage:

Users input the number of processes and the burst time for each process.
The program then calculates and displays the waiting time and turnaround time for each process, along with the average waiting time and average turnaround time for all processes.
Output:

The program prints a table showing the process number, burst time, waiting time, and turnaround time for each process.
Finally, it prints the average waiting time and average turnaround time.
This program assumes that processes are executed in the order of their arrival (FCFS), and the waiting time for each process is the sum of the burst times of all preceding processes.
