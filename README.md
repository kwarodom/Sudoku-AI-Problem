## Introductory Project: Diagonal Sudoku Solver

# Question 1 (Naked Twins)
Q: How do we use constraint propagation to solve the naked twins problem?  
A: **The Naked Twins techniques is used as constraint propagation that follows elimination and only_choice
strategies in the reduce_puzzle() method this is to eliminate digits in other boxes in its peers with the 
observations of naked twins boxes**

# Question 2 (Diagonal Sudoku)
Q: How do we use constraint propagation to solve the diagonal sudoku problem?   
A: **By updating the peers of each box to include diagonal elements, this constraint is automatically implement
 in the eliminate() function and being used as a constraint propagation to solve the diagonal sudoku problem.** 

### Install

This project requires **Python 3**.

We recommend students install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project. 
Please try using the environment we provided in the Anaconda lesson of the Nanodegree.

### To create the environment

#### Mac OS X and Linux 
- Step1: Download the aind-environment-unix.yml at the installation folder
- Step2: "$conda env create -f aind-environment-unix.yml" to create the environment.
- Step3: then "$source activate aind" to enter the environment.

#### Windows 
- Step1: Download the Visual C++ Build Tools [here](http://landinghub.visualstudio.com/visual-cpp-build-tools)
- Step2: Download the aind-environment-windows.yml at the installation folder
- Step3: "$conda env create -f aind-environment-windows.yml" to create the environment.
- Step4: then "$activate aind" to enter the environment.
