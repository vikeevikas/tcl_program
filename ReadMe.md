
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
2: Variable Creation and Processing Constraints from CSV
------------------------------------------------------------------------

From constraints CSV to format to Auto-Create Variable, SDC File Creation


![006](https://github.com/vikeevikas/tcl_program/assets/3139438/97a503ea-acff-473c-a700-22e7cfca9a35)


![007](https://github.com/vikeevikas/tcl_program/assets/3139438/88b9a628-e672-4354-b071-b46ec9b144ba)


![008](https://github.com/vikeevikas/tcl_program/assets/3139438/57faa9c6-f873-4566-a294-31735b06c6a2)


![008](https://github.com/vikeevikas/tcl_program/assets/3139438/d81e82cf-0f0f-42e1-8ab3-f16a81422180)


![009](https://github.com/vikeevikas/tcl_program/assets/3139438/e2471387-5adc-436c-834c-9626bcf04113)


------------------------------------------------------------------------
3: Processing Clock and Input Constraints
------------------------------------------------------------------------

From SDC file - Processing clock(clock latency and clock slew) and input/output  ports constraints for bits and a bus

![010](https://github.com/vikeevikas/tcl_program/assets/3139438/b26ba2da-f2ea-4fd2-967c-277571d3efad)


![011](https://github.com/vikeevikas/tcl_program/assets/3139438/f89d48da-9a65-415f-a492-77ffdf299893)


![012](https://github.com/vikeevikas/tcl_program/assets/3139438/cdf6fe35-ccc7-43ba-974b-6f8c51107dc0)


------------------------------------------------------------------------
4: Yosys Synthesis tool usage 
------------------------------------------------------------------------

Yosys synthesis tool usage and Memory functionality module RTL description, Hierarchy check and error handling.


![Screenshot from 2023-07-09 16-53-10](https://github.com/vikeevikas/tcl_program/assets/3139438/ee7fc704-2e0b-4112-88e7-2f2ec4f36866)


![Screenshot from 2023-07-09 18-15-43](https://github.com/vikeevikas/tcl_program/assets/3139438/6d514cae-fdf5-4a1a-97bd-fa7900dca692)


![Screenshot from 2023-07-09 18-31-26](https://github.com/vikeevikas/tcl_program/assets/3139438/030cb189-0363-4629-8531-a689e6d9e500)


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

