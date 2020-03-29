# OS-Assignment
Create a Process Id (PID) manager that keeps track of free PIDs and ensures that no two
active processes are having the same pid. Once a process terminates the PID manager may
assigns its pid to new process.
Use the following constants to identify the range of possible pid values:
#define MIN PID 100
#define MAX PID 1000
