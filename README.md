# Data Science Salary Analysis 📊

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-1.3+-green.svg)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-1.21+-blue.svg)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4+-red.svg)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.11+-purple.svg)](https://seaborn.pydata.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Data](https://img.shields.io/badge/Data-3755_records-brightgreen.svg)](#dataset)
[![Analysis](https://img.shields.io/badge/Analysis-Complete-success.svg)](#analysis)

## 🎯 Overview


This repository contains a comprehensive analysis of data science salaries across different countries, experience levels, company sizes, and job roles. The analysis explores salary trends, geographical variations, and factors affecting compensation in the data science field.

## 📁 Repository Structure

```
data_science_salary/
├── data_science_salaries.ipynb    # Main analysis notebook
├── ds_salaries.csv                # Primary dataset
├── Data_science_salary_dataset.csv # Additional dataset
├── .gitignore                     # Git ignore file
└── README.md                      # This file
```

## 📊 Dataset

The dataset contains **3,755 records** of data science salaries with the following features:

| Column | Description |
|--------|-------------|
| `work_year` | Year of employment (2020-2023) |
| `experience_level` | Experience level (EN/MI/SE/EX) |
| `employment_type` | Employment type (FT/PT/CT/FL) |
| `job_title` | Job title in data science field |
| `salary` | Salary in original currency |
| `salary_currency` | Currency of salary |
| `salary_in_usd` | Salary converted to USD |
| `employee_residence` | Employee's country of residence |
| `remote_ratio` | Percentage of remote work (0/50/100) |
| `company_location` | Company's location |
| `company_size` | Company size (S/M/L) |

### Experience Levels
- **EN**: Entry-level / Junior
- **MI**: Mid-level / Intermediate  
- **SE**: Senior-level / Expert
- **EX**: Executive-level / Director

### Employment Types
- **FT**: Full-time
- **PT**: Part-time
- **CT**: Contract
- **FL**: Freelance

### Company Sizes
- **S**: Small (< 50 employees)
- **M**: Medium (50-250 employees)
- **L**: Large (> 250 employees)

## 🔧 Technologies Used

- **Python 3.8+**: Programming language
- **Jupyter Notebook**: Interactive development environment
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.8+ installed on your system.

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Alibubere/data_science_salary.git
cd data_science_salary
```

2. Install required packages:
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook data_science_salaries.ipynb
```

## 📈 Analysis

The notebook includes comprehensive analysis covering:

### 🔍 Data Exploration
- Dataset overview and structure
- Missing values analysis
- Data types and distributions

### 📊 Salary Analysis
- Salary distribution by experience level
- Geographic salary variations
- Company size impact on compensation
- Remote work vs. salary correlation

### 📋 Job Market Insights
- Most common job titles
- Employment type trends
- Experience level distribution
- Company size preferences

### 🌍 Geographic Analysis
- Top paying countries
- Regional salary differences
- Currency analysis

### 📅 Temporal Trends
- Year-over-year salary changes
- Market growth analysis

## 🎯 Key Findings

> **Note**: Run the notebook to discover insights about:
> - Average salaries by experience level and location
> - Impact of remote work on compensation
> - Highest paying data science roles
> - Geographic salary hotspots
> - Market trends over time

## 📝 Usage

1. Open the Jupyter notebook
2. Run cells sequentially to reproduce the analysis
3. Modify parameters to explore different aspects of the data
4. Create your own visualizations and insights

## 🤝 Contributing

Contributions are welcome! Please feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

- **Author**: Mohammad Ali Bubere
- **Project Link**: [https://github.com/Alibubere/data_science_salary](https://github.com/Alibubere/data_science_salary)

## 🙏 Acknowledgments

- Dataset source: [Dataset ](dataset.txt)
- Thanks to the data science community for sharing salary information
- Inspiration from various data analysis projects

---

⭐ **Star this repository if you found it helpful!** ⭐