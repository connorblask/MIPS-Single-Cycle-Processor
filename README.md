# MIPS-Single-Cycle-Processor
This repo contains a single cycle MIPS processor I made. All files are availible to use as a reference or learning tool.<br/>
The "Subcircuits" folder is not required to run or view the Single Cycle MIPS Processor. It is there for extra documentation.<br/>
For information regarding control values, karnaugh maps, or branch logic, please see MIPS-Control-Table.xlsx <br/>

## How to View
1. Download the latest version of jdk (you can find that [here](https://www.oracle.com/java/technologies/downloads/))
2. Download jls.jar from this repository
3. Open PHSingleCycleCPU.jls in jls

## How to Test
1. Navigate your current directory to the "Tests" folder in this repo
2. Use:<br/>
```
./CPUTest SingleCycleCPU.jls [assembly file]
```
Make sure to test this CPU using only compatible assembly files with compatible instructions. <br/>
If the assembly file is not compatible, the tests _will not_ work. <br/>
For additional information on instruction compatibility, please see MIPS-Control-Table.xlsx
