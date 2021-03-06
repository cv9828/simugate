# simugate
Python simulation of logic gates, circuits, down to transistor level using std_logic levels

Get the directory and run any of the following python programs: 
* simugate.py  -  main program for designing gates, along with 2 exercise windows included in different ways
* gui.py  -  main program without the two exercises
* exercises.ff_exercise.py  -  create a flip flop using only the parts provided
* exercises.ttl_exercise.py  -  create a gate using transistors
Copy whatever exercises you want to make available up to the main folder.

![image](https://cloud.githubusercontent.com/assets/26174810/24163063/8e89e558-0e0d-11e7-8d14-37d183a29f26.png)

You need Python to be installed. Python3 works. (with tkinter, which typically is normally bundled with Python)

I threw this together recently - maybe it will be of use for some students leaning digital systems design or for teaching it.

You can simulate using std_logic at the transistor level to show how TTL and CMOS works as well as putting together ALUs and registers, counters, decoders, etc.

To invert an input or output, click where the bubble is or should be. To connect wires, just drag between pins. To disconnect, drag along the same path,
but you can't copy parts yet except through undocumented Dump & Dup feature.

For open collector output, set the .oc member True. Currently OCBuf, OCLatch, & OCMem have this in their constructors.

Functions of the ALU are subject to change at this point.

This is still pre-release. Before I consider it released, you should at least be able drag and drop to copy selected items.
