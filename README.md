# checkoff-3
Comp211 AI Exploration checkoff: Performance Benchmarking: C vs. Python: Searching Arrays

Performance benchmarking is like an experiment that allows code performance factors to be measured in a repeated and controlled environment. The results are then compared and interpreted to decide which version is more optimal. 

I explored the methods and tools used most commonly in C and python for benchmarking. I also looked into the typical process used during performance benchmarking, and applied it at a high level to searching arrays. Something that I found pretty interesting were the various clocks and timers that are to be considered when choosing which tools to use. For example, CPU versus user time versus real time in the clock_gettime function in C. User time, which is how long the program runs in user mode, is often close to real time, which refers to the actual time elapsed, while CPU time measures how long the program runs in kernel mode. I was unaware of the different measurements of time before, and found it interesting that different methods could produce different results!
