# Machine Learning Playlist – Environment Setup

This guide will help you set up Python and the required libraries for the **Machine Learning playlist**.

## Step 1: Check Python Installation

Open **Command Prompt** or **PowerShell** and run:

```bash
python --version
```

If Python is installed, continue to the next step.

If Python is not installed, check this video to learn how to install Python:

**How to Install Python:**  
https://youtu.be/XeXmZWkvQOg

## Step 2: Create a Virtual Environment

For the Machine Learning playlist, I recommend creating a separate virtual environment.

Go to the folder where you want to keep your Machine Learning work:

```bash
cd machine-learning
```

Create the virtual environment:

```bash
python -m venv mlvenv
```

Activate it:

```bash
mlvenv\Scripts\activate
```

You should now see something similar to:

```text
(mlvenv) C:\...\machine-learning>
```

The `(mlvenv)` at the beginning means that your virtual environment is active.

## Step 3: Install Jupyter Notebook

With the virtual environment activated, install Jupyter Notebook:

```bash
pip install notebook
```

Install the Machine Learning packages:

```bash
pip install pandas numpy matplotlib scikit-learn
```

### Packages We Are Installing

- **Jupyter Notebook** – For writing and running Python code step by step
- **Pandas** – For working with datasets
- **NumPy** – For numerical computations
- **Matplotlib** – For creating visualizations
- **Scikit-Learn** – For Machine Learning algorithms

## Step 4: Start Jupyter Notebook

Once the installation is complete, run:

```bash
jupyter notebook
```

Jupyter Notebook should open in your browser.

You can now start writing and running Python code for the Machine Learning playlist.

## Complete Setup Commands

If Python is already installed:

```bash
cd machine-learning

python -m venv mlvenv

mlvenv\Scripts\activate

pip install notebook

pip install pandas numpy matplotlib scikit-learn

jupyter notebook
```

> **Note:** Always activate your virtual environment before working on the Machine Learning projects:

```bash
mlvenv\Scripts\activate
```

# Python for Data Science Playlist

If you are new to Python or want to learn Python for Data Science before starting the Machine Learning playlist, check out my **Python for Data Science** playlists.

### Hindi

https://www.youtube.com/playlist?list=PLlSLJhV9FomLr5Xt3rbc5-wIQhxvbvizy

### English

https://www.youtube.com/playlist?list=PLv8Cp2NvcY8DSClm4f6IINbjSWMurA8Tg

# Machine Learning Playlist

Follow the complete **Machine Learning** playlist:

### Hindi

https://www.youtube.com/playlist?list=PLeY3lCOtpcRA

### English

https://www.youtube.com/playlist?list=PLM_LRrP4WkQw

## Recommended Learning Path

If you are completely new to Machine Learning, I recommend following this order:

**Python Basics → Python for Data Science → Machine Learning**

First, learn the Python basics required for Data Science. Then follow the **Python for Data Science** playlist to become comfortable with NumPy, Pandas, Matplotlib, and working with datasets.

After that, start the **Machine Learning** playlist.

Happy Learning! 🚀

**Code With Aarohi**
