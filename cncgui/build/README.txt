The CNC PCB Milling Machine project is the complete specifications for the software 
and hardware for a complete light duty Computer and Numerical Control (CNC) milling 
machine designed primarily to mill isolation traces in copper clad printed circuit 
board material.  Additionally, it can handle milling of soft materials such as 
plastics and aluminum.

This entire project is now open source.  This includes the design of the physical 
machine itself (most of which I owe to many other excellent sources), the design 
of the electronic motor driver circuit, the PIC assembly source code for the firmware 
embedded in the driver circuit, and the Java source code for the GUI based application
 that runs the machine.

I am very much a junk box designer.  The primary selection criteria from most of the 
hardware that makes up this project was what I already had on-hand or could obtain 
cheaply form local resources and EBay.  The design of the physical machine was limited 
by what I could do with a limited set of power woodworking tools (Table Saw, small 
Drill Press, Router and Router Table, and Power Miter saw).  There is practically 
nothing in the physical design of the machine itself that did not come from one of 
the many excellent references sources I found via a never-ending series of Google 
searches.

The software is my own design, influenced heavily by the ideas of many others that 
had done similar projects in the past.  It is not the best example of my Java 
development work, but I am proud of it just the same.

Currently, the software works only with my machine microcode.  It does not generate 
any G-Code output or convert between formats, but it certainly could go that direction.  
There is a simulated machine mode that can work without a connection to the microcode.  
It will do the displays and generate the isolation traces, etc.  Modifications to 
output G-Code (or any other protocol) would not be terribly hard to do, and could be 
fit into the project nicely.