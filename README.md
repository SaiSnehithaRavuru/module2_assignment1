# Maintaining Efficient Process Utilization on Windows

1.View the current tasks using the task manager 

2. Find the pid of the process you want to kill. Go to the task manager and click  details to find the pid number.
 
3. Then open windows powershell and type the command taskkill /pid (pid number). The corresponding  process running  will be terminated.
 
4. To kill multiple tasks ,type the command taskkill /pid (pid number) /pid (pid number).


