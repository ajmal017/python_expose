# MY EXPERIENCE:

An awesome article that I saw online about using jupyter notebooks for analysing crypto data sparked my curiosity and made me
go down the wormhole investigating cryptocurrencies and their underlying patterns. This journey began over winter break 2017/2018,
and continued into my final spring semester where I followed up on this interest researching under Dr. Filippo Radicchi at IU in Bloomington, IN. A few strategies, patterns, and many academic articles later I gained a small knowledge of pattern analysis as well as testing my python skills.

*Note: you can find my final algorithm that I presented in the final_report/ directory*
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

## MESSAGE TO NON-CODERS/BUSINESS/FINANCE PEOPLE:

You probably want to install Anaconda to manage your environment which I created this project. You do not need to download Python in additionto Anaconda because Anaconda contains a Python interpreter of its own.

every time you use this environment you must run the following commands in the terminal
in the folder in which you put the project:

MAC/LINUX:

```
source activate crypto-analysis
jupyter notebook
```
*starts virtual environment*

- after you run the second command the notebook will open up in your browser.
  When you are finished with the environment you'll have to use the keystroke ctrl + c
  to interupt the environment, and then press y and then enter to kill the notebook session.
  Finally run the following command to deactivate the project.
  
``` source deactivate ```
* kills virtual environment*

WINDOWS:

```
activate crypto-analysis
jupyter notebook
```
*starts virtual environment*

- after you run the second command the notebook will open up in your browser.
  When you are finished with the environment you'll have to use the keystroke ctrl + c
  to interupt the environment, and then press y and then enter to kill the notebook session.
  Finally run the following command to deactivate the project.
  
  
```deactivate```
* kills virtual environment*

## NOTES TO ALL USERS:

- the first time you run the environment you must install the Python libraries necessary
  for the project by running the following in the terminal:
  
  ```conda install numpy pandas nb_conda jupyter plotly quandl```
  
  What I have discovered is that often times when I spin up a new environment and run the code
  the graph's won't show up in the output. if you kill the current jupyter
  notebook and run the command:
  
  ```conda install plotly quandl```
  
  and try restarting your jupyter notebook, I've found that in most cases this fixes the
  issue. I think most of the time it is the plotly library being dodgy, but I have found 
  instances where it was quandl. If you want to try installing just plotly and restarting 
  the jupyter notebook this might save you a little time.
  
  ### further documentation for conda environments:
  
  I realize my intro to conda environments is less than exhaustive so here are some links to help you through what I've neglected.
  
  [Managing conda environments](https://conda.io/docs/user-guide/tasks/manage-environments.html)
  [conda cheat sheet](https://conda.io/docs/_downloads/conda-cheatsheet.pdf)
  
