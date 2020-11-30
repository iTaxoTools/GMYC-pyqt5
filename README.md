# PyQt5-GMYC-Project
Pyqt5 GMYC Project have implemented pGMYC - a python implementation of GMYC model for species delimitation in a GUI form. To see the original codes please visit [link] (https://github.com/zhangjiajie/pGMYC). This GUI program will delimit species on a rooted ultrametric tree using single threshold GMYC model. The input tree should be in Newick format. Integration for non-ultrametric tree as input file is supported	using python version of r8s by __Stefanos Patmanidis__. It has Features like viewing the partition tree and table along with exporting all the output files generated by the program in a folder. I have used ete3 library instead of ete2 originally used in the __GMYC__ program.  All the codes are available on the repository. The commandline functionality of original GMYC.py is available and can be used.The GMYC program has support for sequence files using Fastree program, This tool does not implement that functionality.

# Features

* support for non-ultrametric tree as input file
* Viewing of partition table and tree on the GUI interface
* Spart format export option


# How to use it

* To open it as the original commandline tool; please type python GMYC.py and follow along the instructions.

* To use it as GUI tool; Please type python gm.py on your terminal follow the instructions.  
