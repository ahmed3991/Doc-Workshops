# AI Techniques and Tools - Doctorat Project

<table>
<tr>
<td width="60%">

## 📋 Overview

This project contains educational materials for **Axis III: Research and Analysis of Data Driven by AI**, part of a doctoral-level coursework in AI Techniques and Tools. The curriculum focuses on data acquisition, processing, and analysis using artificial intelligence tools, with the objective of mastering fundamental steps of modeling and interpreting results through modern mathematical and algorithmic approaches.

</td>
<td width="40%" align="center">

<img src="images/qr_code.png" alt="QR Code" width="300">

</td>
</tr>
</table>

## � Quick Start with Google Colab

**No local setup required!** Access the course notebooks directly in Google Colab:

| Part | Topic | Google Colab Link |
|------|-------|-------------------|
| **Part 1** | Introduction to Data Science with Python | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1-x1XAQxVev-IO99XVmhjLzLy1QClWwGN?usp=sharing) |
| **Part 2** | Data Preprocessing and Cleaning | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1GtmBEd6kYumK1MCj3DifDbVLmniDR5Od?usp=sharing) |
| **Part 3** | Grouping, Joins, and Aggregations | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1YQ93wb-lBgvuMq5-5Azpus6aLMOJGQsS?usp=sharing) |
| **Brain Tumor Classification** | Brain Tumor Classification | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/13gd8cL4BNcYEupu5K4LktsyAuuSui1mm?usp=sharing) |
| **Brain Tumor Detection** | Brain Tumor Detection | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1P3V0mjZszxa7iGlfSSguQOJlKeeBZ0B_?usp=sharing) |
| **Audio Classification** | Audio Classification | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1nmt5I5nlRhd_15H9iylGJixTe32tOyin?usp=sharing) |
| **Natural Language Processing** | Natural Language Processing | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/16uxhEVr041SJ7aqzGLuId6m8VVsgsQ7s?usp=sharing) |

> 💡 **Tip**: Google Colab provides free GPU access and comes with most data science libraries pre-installed. Simply click the badge above to start learning!

## �📂 Project Structure

```
Doctorat/
├── data/                      # Sample datasets
│   ├── AAPL.csv              # Apple stock data
│   ├── cars.csv              # Car sales dataset
│   └── gapminder.csv         # Gapminder dataset
└── notebooks/                 # Jupyter notebooks (educational content)
    ├── IA_Axe_3_(Part_1).ipynb          # Data Science Introduction
    ├── IA_Axe_3_(Part_2).ipynb          # Data Preprocessing
    ├── IA_Axe_3_(Part_3).ipynb          # Grouping & Aggregations
    ├── Brain_Tumor_Classification.ipynb # Brain Tumor Classification
    ├── BrainTumorDetection.ipynb        # Brain Tumor Detection
    ├── TF_Audio_Classification.ipynb    # Audio Classification
    └── TF_NLP.ipynb                     # Natural Language Processing
```

## 📚 Course Content

### Part 1: Introduction to Data Science with Python (2 hours)
**Objective:** Establish the technical foundations of data science with Python

**Topics Covered:**
- Python fundamentals for data science
- Data structures exploration
- Basic data exploration and inspection commands
- Loading data from multiple formats (CSV, Excel, JSON)

**Tools & Libraries:**
- Jupyter Notebook / Google Colab
- Python 3.8+
- Pandas
- NumPy

**Key Concepts:**
- DataFrame overview and manipulation
- Data loading from various sources
- Basic data inspection (`head()`, `tail()`, `info()`, `describe()`)

**🧪 Practical Workshop:**
- **4 hands-on tasks** with **many guided questions**
- Topics: Data exploration, statistical analysis, calculated columns, filtering & sorting
- **Bonus challenges** for advanced learners

### Part 2: Data Preprocessing and Cleaning (3 hours)
**Objective:** Clean, correct, and transform data to guarantee quality, consistency, and robustness

**Topics Covered:**
- Missing value detection
- Data quality assessment
- Column renaming and data transformation
- Localization of NaNs by column or row
- Data imputation strategies

**Tools & Libraries:**
- Pandas
- NumPy
- Scikit-learn (preprocessing)
- OpenRefine (optional)

**Key Techniques:**
- Handling missing data
- Data validation
- Data type conversions
- Outlier detection

**🧪 Practical Workshop:**
- **5 comprehensive tasks** with **many practical questions**
- Topics: Missing values, outliers, text cleaning, feature engineering, normalization & encoding
- **Advanced bonus section** on sklearn pipelines and custom transformers

### Part 3: Grouping, Joins, and Aggregations (2 hours)
**Objective:** Organize and summarize data to extract meaningful insights

**Topics Covered:**
- Data grouping by categories
- Statistical aggregations (mean, sum, count)
- Cross-tabulations
- Multi-source data joins
- Key Performance Indicators (KPIs) extraction

**Tools & Libraries:**
- Pandas (groupby operations)
- NumPy
- Scikit-learn (preprocessing)

**Key Operations:**
- `groupby()` operations
- Aggregation functions (`mean()`, `sum()`, `count()`)
- Data pivoting and reshaping
- Multiple dataset merging

**🧪 Practical Workshop:**
- **2 real-world tasks** with **analytical questions**
- Topics: Cross-tabulations, customer data merging, KPI calculations
- **Advanced challenges** on multi-level aggregations and data export

---


## 📊 Sample Datasets

### 1. Cars Dataset (`cars.csv`)
Contains information about used car sales with the following features:
- **Vehicle Information:** car_name, brand, model, vehicle_age
- **Usage Metrics:** km_driven
- **Seller Details:** seller_type
- **Technical Specs:** fuel_type, transmission_type, mileage, engine, max_power, seats
- **Price:** price

### 2. AAPL Stock Data (`AAPL.csv`)
Apple stock market data for financial analysis.

### 3. Gapminder Dataset (`gapminder.csv`)
Global development indicators dataset.

## 🛠️ Technologies Used

- **Python 3.8+**
- **Jupyter Notebook** - Interactive computing environment
- **Google Colab** - Cloud-based notebook environment
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Scikit-learn** - Machine learning preprocessing tools

## 🚀 Getting Started - Local installation -

### Prerequisites
- Python 3.8 or higher
- pip (Python package installer)

### Installation

#### Step 1: Navigate to the Project Directory
```bash
cd /Users/ahmed/Documents/Master2-2025-TP/Doctorat
```

#### Step 2: Create a Python Virtual Environment

Creating a virtual environment is recommended to keep project dependencies isolated.

**On macOS/Linux:**
```bash
python3 -m venv .venv
```

**On Windows:**
```bash
python -m venv .venv
```

#### Step 3: Activate the Virtual Environment

**On macOS/Linux:**
```bash
source .venv/bin/activate
```

**On Windows (Command Prompt):**
```bash
.venv\Scripts\activate.bat
```

**On Windows (PowerShell):**
```bash
.venv\Scripts\Activate.ps1
```

After activation, you should see `(.venv)` at the beginning of your command prompt.

#### Step 4: Install Required Dependencies

Install all required packages using the `requirements.txt` file:

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

This will install:
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **scikit-learn** - Machine learning tools
- **jupyter** - Interactive notebook environment
- **matplotlib** & **seaborn** - Data visualization
- **openpyxl** & **xlrd** - Excel file support

#### Step 5: Launch Jupyter Notebook

```bash
jupyter notebook
```

This will open Jupyter Notebook in your default web browser.

#### Step 6: Open and Run Notebooks

Navigate to the `notebooks/` directory and open any of the following:

**Data Science Course Notebooks:**
- `IA_Axe_3_(Part_1).ipynb` - Introduction to Data Science with Python
- `IA_Axe_3_(Part_2).ipynb` - Data Preprocessing and Cleaning
- `IA_Axe_3_(Part_3).ipynb` - Grouping, Joins, and Aggregations

**Machine Learning Notebooks:**
- `Brain_Tumor_Classification.ipynb` - Brain Tumor Classification
- `BrainTumorDetection.ipynb` - Brain Tumor Detection
- `TF_Audio_Classification.ipynb` - Audio Classification
- `TF_NLP.ipynb` - Natural Language Processing

### Deactivating the Virtual Environment

When you're done working, you can deactivate the virtual environment:

```bash
deactivate
```

### Running on Google Colab

Alternatively, you can use Colab links above or upload the notebooks to [Google Colab](https://colab.research.google.com/) for a cloud-based environment without local installation. Google Colab comes with most data science libraries pre-installed.

## 📖 Learning Objectives

By completing this coursework, students will be able to:

1. **Data Acquisition**
   - Load data from multiple sources and formats
   - Understand data structures and types
   - Navigate and explore datasets efficiently

2. **Data Preprocessing**
   - Identify and handle missing values
   - Clean and validate data
   - Transform data for analysis
   - Ensure data quality and consistency

3. **Data Analysis**
   - Perform statistical aggregations
   - Group and summarize data
   - Extract meaningful insights
   - Create cross-tabulations
   - Calculate KPIs

4. **Programming Skills**
   - Master Pandas operations
   - Utilize NumPy for numerical computations
   - Write efficient data processing pipelines
   - Document analysis workflows

## 📝 Course Duration

**Total Duration:** 7 hours (part of a 24-hour curriculum)

- Part 1: 2 hours
- Part 2: 3 hours
- Part 3: 2 hours

## 🎓 Target Audience

- Doctoral students in Computer Science/Data Science
- Researchers working with data-driven AI
- Professionals seeking to enhance their data analysis skills
- Anyone interested in mastering data science fundamentals

## 📄 License

This is an educational project. Please refer to your institution's guidelines for usage and distribution.

## 👥 Contributing

This is a coursework project. For educational improvements or corrections, please consult with the course instructor.

## 🔗 Additional Resources

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Jupyter Notebook Documentation](https://jupyter-notebook.readthedocs.io/)

---

**Note:** This project is part of the "AI Techniques and Tools Subject" coursework focusing on Axis III: Research and analysis of data driven by AI.
