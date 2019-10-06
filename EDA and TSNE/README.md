# EDA-Haberman's Survival

### Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](https://www.numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)
- [Jupyter Notebook](https://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](https://www.anaconda.com/download/) distribution of Python, which already has most of the above packages and more included or if you don't want to install a huge number of packages then you can try [Miniconda](https://conda.io/miniconda.html) and then install the above packages.

### Code

Code is in the [EDA.ipynb](EDA.ipynb) notebook file. Also required  the [haberman.csv](EDA.csv) dataset file.

### Run

In a terminal or command window, navigate to the top-level project directory `boston_housing/` (that contains this README) and run one of the following commands:

```bash
jupyter notebook EDA.ipynb
```

or

```bash
ipython notebook EDA.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.


### Data
The dataset used in this project can be found in [haberman.csv](haberman.csv) dataset file.

**Features**

* 30 - It represents age of patient at the time of operation(numerical) 
* 64 - It represents year of operation(numerical) 
* 1 - It tells no of +ve auxillry node detected(numerical) 


**Target Variable**
4. 1.1 - Survival status 1 = the patient survived 5 years or longer 2 = the patient died within 5 year


