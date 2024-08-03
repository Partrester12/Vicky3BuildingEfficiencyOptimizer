# Vicky3 BuildingEfficiencyOptimizer (BEO for short)
Inspired by Generalist Gaming's spreadsheet, here's a program which can mathematically optimize the prices of goods instead of guessing numbers by hand in the spreadsheet!

# If you don't want to edit the program or touch the code, then download the latest version of the program here and read the instructions included

Download for Windows: https://www.mediafire.com/file/cpuxnf8r6emvv28/Vicky3_BEO_Windows.zip/file

Download for Linux (only Ubuntu tested): https://www.mediafire.com/file/i0kl1a85a2e7ysc/Vicky3_BEO_Ubuntu.zip/file

As of Version 2.0, there is a full on GUI for using the program! Below are a couple of instructions for using the program:

**To view the optimized prices for your selection of buildings, click the 'Con' and 'Lab' buttons located on the right side of the window**

**If you run optimizations for more than 10 buildings, I recommend running the optimization process again with the same buildings. The program will use your previous values and try to get more optimal results. Rule of thumb is that if you can see meaningful progress in the status messages shown at the upper-right part of the window AND you have more than 10 buildings included, then you should try and run the optimization process again. Meaningful progress means that the metrics shown in the status messages improve by at least a few percents.**

# Read here for some tips if you want to edit the files/use the program manually

Currently the files work as follows:
- GUI.py handles the user interface as well as calling the OptimizeBuildings method in OptimizeBuildings.py
- OptimizeBuildings.py contains the code of OptimizeBuildings.ipynb, but edited in a way where it works in tandem with GUI.py
- OptimizeBuildings.ipynb contains the source code for the optimization process

Thus if you want to run the program manually, I recommend installing Jupyter Notebook (and whatever libraries the notebook contains) and playing around with OptimizeBuildings.ipynb.
The notebook file only needs a 'BuildingSheet,xlsx' to be located in the same folder, so you can for example launch the GUI, run the program on a set of buildings, switch over to Jupyter, and run your edited program on the BuildingSheet generated by the GUI.
YOu can also create the BuildingSheet manually, but that is such a hassle that I highly recommend you take advantage of the GUI!

# You can report any bugs to the thread located in Generalist Gaming's discord channel for this program (discord invite can be found in most of his videos on YouTube)

# (Link to Generalist Gaming's spreadsheet: https://docs.google.com/spreadsheets/d/1NDUwUWHlNuQTWMejK0Agv8gC3fn6ujiXKE9WfVmjFBc/edit#gid=0)
