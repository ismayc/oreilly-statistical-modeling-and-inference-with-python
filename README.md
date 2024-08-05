# Materials for the course "Statistical Modeling and Inference with Python" for O'Reilly by Dr. Chester Ismay


# Course content

The major files in this repository are
- `slides_2024-08.pdf`: PDF version of the slides used in this course to motivate the code.
- `spotify_sample.csv`: Data for code walkthroughs
- `imdb_movie_sample.csv`: Data for student exercises.
- `exercises.ipynb`: A Jupyter Notebook with pseudocode/instructions provide to be filled in for code walkthroughs and student exercises
- `exercises_solutions.ipynb`: A Jupyter Notebook with answers to the code walkthroughs and exercises. 

## Recommended instructions on getting set up with Python and Jupyter Notebook

### Step 1: Install Python
- **Option 1: Anaconda Installation**:
  - **Download Anaconda**: Go to the [official Anaconda website](https://www.anaconda.com/products/distribution) and download the latest version of Anaconda for your operating system (Windows, macOS, or Linux). Anaconda conveniently installs Python, Jupyter Notebook, and many other commonly used packages for data science and machine learning.
- **Option 2: Python Installation**:
  - **Download Python**: Alternatively, you can download Python directly from the [official Python website](https://www.python.org/downloads/) and install the latest version for your operating system.

### Step 2: Launch Jupyter Notebook
- **Launch Jupyter Notebook**:
  - **Anaconda**: After installing Anaconda, open Anaconda Navigator from your Start Menu (Windows) or using the Anaconda Navigator application (macOS/Linux). In Anaconda Navigator, find Jupyter Notebook in the list of available applications and click on the "Launch" button. This will open Jupyter Notebook in your default web browser.
  - **Python Installation**: Open your command prompt (Windows) or terminal (macOS/Linux), and install Jupyter using pip:
    ```bash
    pip install notebook
    ```

### Step 3: Install Required Libraries
- **Open Anaconda Prompt (Windows) or Terminal (macOS/Linux)** (if using Anaconda), or **open your command prompt (Windows) or terminal (macOS/Linux)** (if using Python installation).
- **Install Required Libraries using conda (Anaconda)**:
   ```bash
   conda install numpy pandas scipy matplotlib seaborn statsmodels scikit-learn
   ```
- **Install Required Libraries using pip** (if not using Anaconda):
  ```bash
  pip install numpy pandas scipy matplotlib seaborn statsmodels scikit-learn
  ```

### Step 4: Launch Jupyter Notebook
- **Open your command prompt or terminal**.
- **Run Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```
   This command will open Jupyter Notebook in your default web browser.

### Step 5: Verify Installation
- **Create a new notebook**: In the Jupyter Notebook interface, click on "New" and select "Python 3" to open a new notebook.
- **Test the installation of the libraries**:
   - Import the libraries in the first cell of your notebook:
     ```python
      import pandas as pd
      import numpy as np
      import matplotlib.pyplot as plt
      import seaborn as sns
      import statsmodels.api as sm
      from sklearn.model_selection import train_test_split
      from sklearn.linear_model import LinearRegression
      from sklearn.metrics import mean_squared_error, r2_score
     ```
   - Run the cell (`Shift + Enter`). If no errors appear, the libraries are installed correctly.

### Additional Tips
- **Troubleshooting**: If you encounter any errors during installation, make sure that your pip is up to date (`pip install --upgrade pip`) and try the installation commands again. If issues persist, check for specific error messages online for troubleshooting tips.
- **Learning Resources**: Familiarize yourself with the Jupyter Notebook interface and basic functionality by reading tutorials or watching introductory videos about Jupyter Notebooks.
