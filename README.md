## Memory Leak Detector in C

There is no in-built memory detector in C (unlike Java). So, this code helps in detecting memory leaks (if any). There are mainly three types of memory leaks, which this detector identifies:

1. **Borrowed Memory Not Released:** When memory is borrowed from the OS and not released.
2. **Double Free:** When the same memory is freed twice.
3. **Freed Memory Access:** When trying to access memory that has already been freed.

The Memory Leak Detector (MLD) detects all these types of leaks, allowing them to be identified and removed.
