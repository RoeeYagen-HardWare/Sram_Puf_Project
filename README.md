**Sram_Puf_Project**                                              
Final Project - design and simulation of a 64-bit SRAM based Physically Unclonable Function (PUF) in 45nm CMOS using Cadence Virtuoso, featuring error correction and reliability analysis.                 
**Project Overview**                  
The project started with the design of a single 6T SRAM cell used as a basic PUF element, After successful simulation and analysis, the design was expanded into a 64-bit SRAM PUF array.

To achieve good randomness and stability, I carefully adjusted transistor widths and balanced device sizing.  
Monte Carlo simulations were performed to verify the statistical randomness of the PUF responses.

Currently, the next step is to integrate **error correction** and test the design under **extreme temperature and voltage conditions** to evaluate reliability.

**Tools and Environment**
- **Technology:** GPDK 45nm CMOS
- **Software:** Cadence Virtuoso, Spectre, VHDL
- **Analysis:** Monte Carlo, corner simulations (TT, SS, FF), voltage/temperature variations

**Current Status**
-  Designed and simulated a single SRAM-based PUF cell  
-  Built and verified a 64-bit array version  
-  Achieved balanced transistor sizing and good randomness  
-  Next Step: implement error correction and test under environmental stress

**Author**
**Roee Yagen**  
B.Sc. in Electronics Engineering – Ariel University  
Focused on VLSI design and communication systems, simulation, and hardware reliability.
