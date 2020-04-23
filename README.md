# BJBANKS

Notebooks and source code related to the paper

*Money, Credit and Equilibrium Imperfectly Competitive Banking* (A working title)

by Allen **Head**, Timothy **Kam** and Ieng-Man **Ng**

# For Users New to Python and Jupyter Notebooks

Instructions for new users of these computational codes and notebooks. 

Our computational solutions are developed using the free and open source Anaconda distribution of Python 3.x. 

Many examples are rendered through Jupyter Notebooks (an interactive notebook, like a Mathematica Notebook).


## Installing Anaconda Distribution for Python (and Jupyter Notebook)

* Step 1: Download and Install latest version of the Anaconda distribution 

        https://www.anaconda.com/distribution/

* Step 2: Install and activate Jupyter extensions package. This will allow LaTeX style equation auto-numbering and cross-referencing

        conda install -c conda-forge jupyter_contrib_nbextensions

* Step 3: Install Javascript and CSS related to Step 2

        jupyter contrib nbextension install --user

* Step 4: Install Notebook Extensions Configurator (GUI for customizing options like LaTeX referencing, equation numbering and cross-referencing, code folding, creating Exercise environments, and etc

        conda install -c conda-forge jupyter_nbextensions_configurator

## Launching and using Jupyter Notebook

* Step 5: Windows and Mac users can launch the Jupyter Notebook through GUI icons (or the Windows Anaconda Shell or the Mac Terminal). Linux and Mac users can use this command at the BASH terminal prompt to start it:

        jupyter notebook

    * There is also a MATLAB or R-GUI like Integrated Developer Environment; type at prompt:

                jupyter lab

    * For batch processing scripts, you may wish to write code as .py files and interact with them using the Interactive Python shell:

                ipython

    * Or just run 

                python script.py

## RISE (Jupyter Slideshow Extension)

* Step 6: If you want to also create presentation slides straight from your Notebook, you may need to also install RISE:

        conda install -c conda-forge rise

    * (Restart your Notebook server instance to activate it.) 
    
    * See more here on usage: https://github.com/damianavila/RISE and https://rise.readthedocs.io/


