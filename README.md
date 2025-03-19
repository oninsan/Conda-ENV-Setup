## 🐍 Creating a Conda Environment and Installing Essential Libraries

This step-by-step guide will walk you through creating a Conda environment and installing the following packages:

- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `graphviz`
- `category_encoders`
- `imblearn`

---

## ✅ **Step 1: Install Anaconda or Miniconda**

1. Download and install [Miniconda](https://docs.conda.io/en/latest/miniconda.html).
2. Follow the installation instructions for your operating system.
3. Confirm installation by running the following command in your terminal or command prompt:

```bash
conda --version
```

---

## 🚀 **Step 2: Create a New Conda Environment**

1. Open your terminal or command prompt.
2. Run the following command to create a new environment named `my_env` with Python 3.11:

```bash
conda create -n my_env python=3.10.12
```

3. Activate the environment:

```bash
conda activate my_env
```

4. Confirm activation by checking the Python version:

```bash
python --version
```

---

## 📦 **Step 3: Install the Required Packages**

With your environment activated, install the necessary libraries using the following commands:

### 1. Install NumPy, Matplotlib, and Seaborn
```bash
conda install numpy matplotlib seaborn
```

### 2. Install Scikit-Learn
```bash
conda install scikit-learn
```

### 3. Install Graphviz
```bash
conda install -c conda-forge python-graphviz
```

> **Note:** Make sure you have Graphviz installed on your system. You can download it from [Graphviz Official Website](https://graphviz.org/download/).

### 4. Install Category Encoders
```bash
conda install -c conda-forge category_encoders
```

### 5. Install Imbalanced Learn (Imblearn)
```bash
conda install -c conda-forge imbalanced-learn
```

---

## 🛠 **Step 4: Verify Installations**

After installing the packages, you can verify them using Python:

```bash
python
```

Then run the following commands to check imports:

```python
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import sklearn
import graphviz
import category_encoders as ce
import imblearn

print('All packages imported successfully!')
```

If no errors are shown, you're good to go! 🎉

---

## 🚀 **Final Tips**
- Use `conda list` to view all installed packages.
- Use `conda deactivate` to exit the environment.
- To remove the environment, run `conda env remove -n my_env`.

Wa unta ninyo gi uli ang CP ni patrick!!!

