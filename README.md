# Lab 1 - Preperation

This lab/homework assignment is ungraded. It is meant as an introduction to using Python and some of the libraries we 
will be using for the labs in the rest of the course. You can come to the lab class on Wednesday 14.08.2019 or try to 
do this lab at home. Follow the instructions and ask for help on Piazza or during the next lab class on Wednesday 22.08.2018.

Your first task is to install Python (>=2.7) and these libraries and get familiar with them. On Windows, the easiest way 
to install Python with all these libraries may be Anaconda (Links to an external site.). On Linux, you may find packages 
for these libraries and their dependencies in your distribution.

Scikit-learn already comes with a number of datasets that you can use to try out different algorithms without having to
worry about data collection or preprocessing. For example, you can use the following code as inspiration for looking 
at a dataset consisting of labelled images of handwritten digits. Try to run the code and understand what it is doing.

### Requirements

* Python >= 2.7
* pip >= 2
* virtualenv
    ```bash
    sudo pip install virtualenv
    ```


## Install

1. Make sure youre in the root directory of the project
2. Set up virtual environment
    ```bash
    virtualenv venv
    ```
4. Activate python interpreteur
    ```bash
    source venv/bin/activate
    ```
3. run pip requirements
    ```bash
    pip install -r requirements.txt
    ```

## Run Juptyter notes

1. Make sure to be in the root directory of this project
2. Run the jupyter notebook in terminal
    ```bash
    jupyter notebook
    ```
    The notebook server is running on your localhost. In the terminal window you should have a localhost link with a port number.
    ```
    [I 13:15:35.566 NotebookApp] http://localhost:8889/

    ```
    Open the link in any browser to view the notebook UI. 

