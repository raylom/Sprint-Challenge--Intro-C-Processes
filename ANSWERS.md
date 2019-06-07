**1. List all of the main states a process may be in at any point in time on a standard Unix system. Briefly explain what each of these states means.**
Process States:
New: Process is being created by the OS
Ready: Process is waiting to be assigned to a CPU core
Running: Process is executing on a CPU core
Waiting: Process is waiting for some event
Terminated: Process has finished execution

**2. What is a zombie process?**
A zombie process is a process that has completed execution, but still has an entry in the process table. It is in the terminated state.

**3. How does a zombie process get created? How does one get destroyed?**
Zombie processes usually occur for child processes, as the parent child still needs to read its childs exit status. The zombie process is destroyed using the wait system call.

**4. What are some of the benefits of working in a compiled language versus a non-compiled language? More specifically, what benefits are there to be had from taking the extra time to compile our code?**
Compiled languages tend to be faster than those translated at run time do to the overhead of the translation process.
