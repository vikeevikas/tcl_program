
Advanced Scripting Techniques in Design and Synthesis using TCL
--------------------------------------------------------------------------------------------

Open Source Tools Used:-
Yosys
OpenTimer
TCL development suite
Libraries (associated with TCL)


------------------------------------------------------------------------
1: TCL and VSDSYNTH Toolbox Usage
------------------------------------------------------------------------

VSDSYNTH Toolbox usage scenarios, input CSV file, incorrect CSV and "-help" Implimentation


![000](https://github.com/vikeevikas/tcl_program/assets/3139438/c7cbc65d-c111-48c4-aa64-02684c713040)

![000](https://github.com/vikeevikas/tcl_program/assets/3139438/3ccb6588-0087-4b5f-a376-24ff3ea8a854)

![003](https://github.com/vikeevikas/tcl_program/assets/3139438/be40dea6-ada9-44b4-8792-49f10764dc72)

![004](https://github.com/vikeevikas/tcl_program/assets/3139438/ec6b3d57-64e7-41f2-a35e-80acc1d4630d)

![005](https://github.com/vikeevikas/tcl_program/assets/3139438/862beb03-81e5-4946-b0c8-baa3c6df9bb9)




------------------------------------------------------------------------
Day 2: Variable Creation and Processing Constraints from CSV
------------------------------------------------------------------------

Section 3: Sub-Task Two - From CSV to format[1] and SDC - Variable Creation
  Lecture 5: Various tasks involved in format conversion
  Lecture 7: Auto-Create variables using matrix and arrays
  Lecture 8: Initialize variables for auto-creation variables task
  Lecture 9: Auto creation of the first variable - DesignName
  Lecture 10: Auto creation of variables complete
  Lecture 11: Variable Creation DEMO using TCL
Section 4: Sub-Task Two - From CSV to format[1] and SDC - Processing constraints, CSV
  Lecture 12: Checking the existence of files and folders mentioned in design_details.csv
  Lecture 13: Convert constraints.csv file to a matrix object
  Lecture 14: Compute row number using complex matrix processing
  Lecture 15: DEMO for computing row numbers

------------------------------------------------------------------------
Day 3: Processing Clock and Input Constraints
------------------------------------------------------------------------

Section 5: Sub-Task Two - From CSV to format[1] and SDC - Processing clock constraints
  Lecture 16: Algorithm to identify the column number for clock latency constraints
  Lecture 17: Start writing clock latency constraints in the SDC file
  Lecture 18: Complete clock latency constraints and clock slew constraints in the SDC file
  Lecture 19: Code to create clock constraints with clock period and duty cycle
  Lecture 20: DEMO for creating complete clock constraints
Section 6: Sub-Task Two - From CSV to format[1] and SDC - Processing input constraints
  Lecture 21: Introduction to the task of differentiating between bits and a bus
  Lecture 22: Algorithm to categorize input ports as bits and bussed
  Lecture 23: File access and pattern creation steps
  Lecture 24: Regular expression and regular substitute to get fixed space strings
  Lecture 25: Demo for grepping input ports from all verilogs and reformatting for fixed space
  Lecture 26: Read, split, uniquify, sort, and join input ports to remove duplication
  Lecture 27: Evaluate the length of the string and Demo of bits/bussed differentiation script
  Lecture 28: Demo for input constraints generation and bits/bussed differentiation

------------------------------------------------------------------------
Day 4: Complete Scripting and Yosys Synthesis Introduction
------------------------------------------------------------------------

Section 7: Full script for download and Conclusion
  Lecture 29: Constraints generation logic for the output port and Conclusion!!
Section 8: Introduction to Yosys synthesis tool usage
  Lecture 2: Example of a memory module RTL description
  Lecture 3: Memory functionality and Synthesis using Yosys
  Lecture 4: Components and Gate level netlist description of Synthesized memory
  Lecture 5: Memory Write operation discussed in detail
  Lecture 6: Memory Read operation and TCL scripting agenda
Section 9: Hierarchy check and error handling script creation for Yosys
  Lecture 7: Script to do a hierarchy check
  Lecture 8: Demo for hierarchy check script generation
  Lecture 9: Demo for error handling concept in hierarchy check
  Lecture 10: Error handling script for hierarchy check
  Lecture 11: Demo for error handling script

------------------------------------------------------------------------
Day 5: Advanced Scripting Techniques and Quality of Results Generation
------------------------------------------------------------------------

Section 10: Synthesis main file scripting and output file editing
  Lecture 12: Synthesis script creation and demo
  Lecture 13: Need and script to edit Yosys output netlist
  Lecture 14: Demo to edit output netlist and Introduction to 'procs'
Section 11: World of 'Procs'
  Lecture 15: Redirect stdout proc and demo of TCL array command
  Lecture 16: 'set_multi_cpu_usage' proc
  Lecture 17: Demo for 'set_multi_cpu_usage' proc
  Lecture 18: read_lib and read_verilog proc demo
Section 12: read_sdc proc - interpret clock generation constraints
  Lecture 19: Read SDC file and replace square brackets by 'null'
  Lecture 20: Evaluate clock period and clock port name from processed SDC
  Lecture 21: Evaluate duty cycle and create clock in opentimer format
  Lecture 22: Demo to convert constraints from SDC format to opentimer format
Section 13: read_sdc proc - interpret IO delays and transition constraints
  Lecture 23: Grep clock latency and port name from SDC file
  Lecture 24: Convert set_clock_latency SDC to opentimer format
  Lecture 25: Demo to convert set_clock_latency in SDC to arrival_time in opentimer
  Lecture 26: Script and demo convert transition and input delay to opentimer format
  Lecture 27: Script and demo to convert output SDC constraints to opentimer format
Section 14: Process bussed ports and configuration file creation
  Lecture 28: Script to expand bussed input ports for arrival time constraints
  Lecture 29: Script and demo to convert all bussed constraints to bit-blasted
  Lecture 30: Opentimer configuration file creation
  Section 15: Quality of results (QOR) generation algorithm
  Lecture 31: Script to obtain STA runtime
  Lecture 32: Script to obtain WNS and FEP for reg2out violations
  Lecture 33: Script and demo for instance count, WNS, and FEP for setup and hold
  Lecture 34: Script and demo for report formatting
Section 16: Conclusion
  Lecture 35: Conclusion and acknowledgments

-----------------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------------

Open Source Tools

Yosys
OpenTimer
TCL development suite
Libraries (associated with TCL)

-------------------------------------------------------

Oracle VirtualBox

VDI file https://forgefunder.com/~kunal/TCLWorkshop.vdi

--------------------------------------------------------------
