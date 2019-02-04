# microaggregates
Numerical Model to Simulate Soil Aggregate Development from Minerals of Different Shape and Surface properties in 3D using Diffusion-Limited Aggregation and the DLVO Theory 



Instructions to aggregate_modeler.exe
supporting executable to manuscript "Modeling the formation of soil microaggregates" by Thomas Ritschel and Kai Uwe Totsche

General Information
-------------------
64-Bit Win executable
Compiled from source.txt with PureBasic 5.60
no dependencies, *.exe creates init.dat upon first run and stores user settings

System requirements
-------------------
64-Bit System, source code contains 64-Bit assembly, no 32-Bit compatibility 

tested on Win 8.1 (64Bit) with 32GB RAM and Win 7 (64Bit) with 16GB RAM 
RAM usage is proportional to number of grid cells, 1000x1000x1000 grid cells require ~5GB RAM

Installation
------------
execute aggregate_modeler.exe as is, no installation required

Demo
----
1. execute aggregate_modeler.exe 
2. test parameters are already set und should be as shown in settings.png
3. click "Start"
4. aggregation modeling starts and a window visualising the progress is created (screenshot.png)
5. hit ESC to quit and export 3D structure as stacked 2D images if required (folder .\aggregateout is created at location of execution and its content overridden)

run-time is depending on user and output is non-deterministic due to the stochastic nature of diffusion modeling 
