# Fault Exceptions

In this exercise we are generating some usage faults and examine them by using these methods:
1) Examining using "Fault Analyzer" window on IDE
2) Examining by printing the content of UFSR (Usage Fault Status Register)
3) Exanining by printing the content of "Stack Frame"

Firstly we active the congidurable Fault Exceptions (Usagefault Exception, BusFault Exception, MemFault Exceptin)

After that we write the codes that will generate the faults below and analysis them one by one with three diffenet methods:
1) Undefined Instruction
2) Forcing the cortex M processor to execute instruction from ARM ISA that is impossible
3) Divide by zero (We must enable the "Divide by 0 Trap" too)

