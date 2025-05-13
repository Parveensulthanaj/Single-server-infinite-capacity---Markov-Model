# Single server with infinite capacity (M/M/1):(oo/FIFO)
## Aim :
To find (a) average number of materials in the system (b) average number of materials in the conveyor (c) waiting time of each material in the system (d) waiting time of each material in the conveyor, if the arrival  of materials follow poisson process with the mean interval time 12 seconds, serivice time of lathe machine follows exponential distribution with mean serice time 1 second and average service time of robot is 7seconds.

## Software required :
Visual components and Python

## Theory:
Queuing are the most frequently encountered problems in everyday life. For example, queue at a cafeteria, library, bank, etc. Common to all of these cases are the arrivals of objects requiring service and the attendant delays when the service mechanism is busy. Waiting lines cannot be eliminated completely, but suitable techniques can be used to reduce the waiting time of an object in the system. A long waiting line may result in loss of customers to an organization. Waiting time can be reduced by providing additional service facilities, but it may result in an increase in the idle time of the service mechanism.

![image](1.png)

This is a queuing model in which the arrival is Marcovian and departure distribution is also Marcovian,number of server is one and size of the queue is also Marcovian,no.of server is one and size of the queue is infinite and service discipline is 1st come 1st serve(FCFS) and the calling source is also finite.

## Procedure :

1. Probability of zero units in the queue (𝑃0)=1−(𝜆
 𝜇
 ) 
2. Average queue length (𝐿𝑞)= 𝜆2
 𝜆(𝜆−𝜇)
 
3. Average number of units in the system (𝐿𝑠)= 𝜇
 𝜆−𝜇
 
4. Average waiting time of an arrival (𝑊𝑞)= 𝜆
 𝜇(𝜆−𝜇)
 
5. Average waiting time of an arrival in the system (𝑊𝑠)= 1
 𝜆−𝜇




## Experiment:

![Screenshot 2025-05-13 104956](https://github.com/user-attachments/assets/5beb7b52-633e-4932-9d44-65fd540f739a)

 
## Program
![image](https://github.com/ramjan1729/Single-server-infinite-capacity---Markov-Model/assets/103921593/5f1fd58d-5929-4c51-89ea-4cef009e5bad)

## Output :

![4pqm](https://github.com/user-attachments/assets/3c2e4f6f-e7dc-4a5c-95f1-e78cfdfde332)

## Result :

The average number of mateerials int the system and in conveyor and waiting
time are successfully found.
