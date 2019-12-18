### Software installation. 
1. Download and install Anaconda: https://www.anaconda.com/distribution/. 
    1.1. On a windows system, simply run the .exe file for installation: https://problemsolvingwithpython.com/01-Orientation/01.03-Installing-Anaconda-on-Windows/ 
    1.2. On a linux system, do ./anaconda_installationfile.sh: https://problemsolvingwithpython.com/01-Orientation/01.05-Installing-Anaconda-on-Linux/
         1.2.1. After installation, source bashrc as source .bashrc.
    1.3. Download Python 2.7 version only.
2. Testing packages

    2.1. Jupyter notebook.
    
        2.1.1. On Windows start the Anaconda prompt. Type jupyter notebook, and press enter. A new window should start on the browser .
        2.1.2. On Linux, start the terminal. Type jupyter notebook, and press enter. A new window should start on the browser.
        2.1.3. If the above command did not work, in the Anaconda prompt or the Linux terminal, do conda install jupyter.  Once installation is performed, do step 2.a.i or 2.a.ii.
        2.1.4. A tutorial is available on: https://problemsolvingwithpython.com/02-Jupyter-Notebooks/02.03-Installing-Juypter/
    
    2.2. Numpy and Matplotlib: Numpy is a numerical python package, which allows for vectorized computation. Matplotlib is the visualization package, which allows plotting and showing images.
    
        2.2.1. Start up the Anaconda prompt (terminal) on Windows (Ubuntu). 
        2.2.2. Type `python` and press enter. 
        2.2.3. Now, type `import numpy as np`. If the command is successful, the package is installed. 
        2.2.4. For consistency, enter the command `np.__version__`, and check the version of numpy. 
        2.2.5. Now, enter the command `import matplotlib`. If the command is successful, the package is installed.
        2.2.6. For consistency, do `matplotlib.__version__`, and check the version of matplotlib.
        2.2.7. If either of the packages are missing, enter `exit()` to come out of the python shell. In the prompt (terminal), enter the command `conda install numpy` to install numpy and `conda install matplotlib` to install matplotlib respectively. Once the packages are successfully installed, follow from step 2.b.i. 
        2.2.8. More information here: https://problemsolvingwithpython.com/05-NumPy-and-Arrays/05.02-Installing-NumPy/, https://problemsolvingwithpython.com/06-Plotting-with-Matplotlib/06.02-Installing%20Matplotlib/ 
    
    2.3. Astropy: Astropy is an astronomical package for reading/writing fits files, the primary data format for astronomical data. The installation and verification are similar to other packages as:
    
        2.3.1. Enter the command `python` on the Anaconda prompt (terminal) to launch the python shell.
        2.3.2. In the shell, enter `import astropy`. If the package exists, it must be successful. 
        2.3.3. For consistency, do `astropy.__version__`, and check the version of astropy.
        2.3.4. If astropy is not available, come out of the shell by entering `exit()`. In the Anaconda prompt (terminal), do `conda update astropy`. Once successfully updated and installed, follow from Step 2.c.i. 
        2.3.5. More information here: https://docs.astropy.org/en/stable/install.html 
