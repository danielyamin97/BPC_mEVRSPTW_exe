This program executes the Dynamic Programming-based Algorithm for the Maximum Probability of On-time Arrival Strategy
on STD networks (MPOAS-STD), as reported in [Pending].

The program must be in the same path as a "data" file folder. This folder must contain the STD networks' files and file
"instances.txt" where the instances are written. This includes the network name, destination node, number of discrete timesteps, 
and arrival time threshold.  

To run the algorithms, access the command prompt and run the following command: DPA.exe X Y, where 
   - X is the instance number you want to execute (it will execute the instance in line X-1 of the "instances.txt" file).
   - Y is the specific implementation you want to execute (1: FIFO, 2: Dequeue, 3: Priority Queue). 
  
You can also run batches of experiments using a ".bat" file. 
See the examples (AnaheimSTD and BarcelonaSTD) to understand format requirements. 

The results are reported in the file "results.txt", including the running time (in milliseconds). 

If you have any questions, feel free to contact me at d.yamin@uniandes.edu.co.   
 