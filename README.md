# Improved_CPU_Scheduler
An implementation of An Improved Round Robin CPU Scheduling Algorithm with Varying Time Quantum (IRRVQ) presented by Manish Kumar Mishra and Dr. Fazur Rashid in their paper by the same name from 2014.

# What it does
* Compares the traditional round robin scheduler with an improved round robin scheduler
* NOTE -- This implementation only handles 0 arrival time jobs, not varying.
* Allows for varying length ready queues
* Prints average performance data in a human readable format for easy comparision
* Has options to allow printing of the ready queue as tasks are accomplished so you can see the algorithms at work

# What I Learned
* Scheduling is not as easy as it sounds when you read about it
* Keeping metrics like wait times is challenging in theoretical implementations
* CPU scheduling is actually pretty engagning once you're immersed in it
* It seems that this version of round robin scheduling slows down the longer the ready queue is.  

# How To Use
* Run the main module as a python3 script. (to see the improvements the IRRVQ provides, I'd reccomend using <50 for ready queue length)
* If you feel like configuring, more data can be displayed. This can easily be done by changing standard_rr(std_ready, False) to standard_rr(std_ready, True) for both the standard_rr and improved_rr in the test_improved_vs_standard_rr function.
