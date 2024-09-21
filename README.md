# TogglePatterns
This project explores a classic combinatorial problem involving a sequence of toggle 
operations on a series of lockers. Imagine n lockers, each initially closed, and n sequential passes 
through these lockers. On each i-th pass, every i-th locker is toggled: if the door is closed, it is 
opened; if it is open, it is closed. The goal of the project is to determine which lockers remain open 
and which are closed after all passes are completed, and to identify how many lockers remain open.
The solution to this problem leverages the mathematical properties of divisors and perfect 
squares. By recognizing that a locker will be toggled once for each of its divisors, we can deduce 
that lockers at positions corresponding to perfect squares will end up being toggled an odd number 
of times, and therefore remain open. This insight significantly simplifies the problem, reducing it 
to counting the perfect squares up to n. Through this project, we gain a deeper understanding of 
how mathematical patterns and properties can be used to efficiently solve problems that would 
otherwise require extensive computation.
