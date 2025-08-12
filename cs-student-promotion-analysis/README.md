# 🎓 Computer Science Student Promotion Analysis

A comprehensive analysis of promotion patterns among computer science students using data-driven insights and colorful visualizations.

![Python](https://img.shields.io/badge/Python-3.11-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-2.1-green.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.8-orange.svg)
![License](https://img.shields.io/badge/License-MIT-purple.svg)

## 📊 Project Overview

This project analyzes the promotion patterns of 40+ computer science students based on various academic and skill-based factors. The analysis includes:

- **📈 Interactive visualizations** with colorful charts
- **📊 Statistical analysis** of promotion factors
- **🎯 Predictive insights** for student success
- **📋 Professional Excel reports** with conditional formatting

## 🗂️ Project Structure

```
cs-student-promotion-analysis/
├── 📁 data/
│   └── student_promotion_data.csv    # Main dataset (40+ students)
├── 📁 notebooks/
│   └── analysis.ipynb               # Jupyter notebook with full analysis
├── 📁 src/
│   └── data_utils.py                # Utility functions for data processing
├── 📁 reports/
│   ├── student_analysis_charts.png  # Colorful analysis charts
│   ├── correlation_heatmap.png      # Feature correlation matrix
│   └── student_promotion_report.xlsx # Excel report with formatting
├── requirements.txt                 # Python dependencies
├── README.md                       # This file
└── LICENSE                         # MIT License
```

## 📈 Dataset Features

| Feature | Description | Range |
|---------|-------------|--------|
| **GPA** | Grade Point Average | 0.0 - 4.0 |
| **Attendance_Percentage** | Class attendance rate | 0% - 100% |
| **Courses_Passed** | Number of courses completed | 8 - 13 |
| **Programming_Skills** | Self-assessed programming ability | 1 - 10 |
| **Communication_Skills** | Self-assessed communication ability | 1 - 10 |
| **Projects_Completed** | Number of projects completed | 2 - 7 |
| **Internship_Experience** | Has internship experience | Yes/No |
| **Promotion_Status** | Final promotion decision | Promoted/Not Promoted |

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/cs-student-promotion-analysis.git
cd cs-student-promotion-analysis
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Analysis
```bash
# Launch Jupyter Notebook
jupyter notebook notebooks/analysis.ipynb

# Or run the analysis script
python -c "
import sys
sys.path.append('src')
from data_utils import load_data, create_visualizations, generate_summary_stats
import os

df = load_data('data/student_promotion_data.csv')
stats = generate_summary_stats(df)
print('Summary Statistics:', stats)
create_visualizations(df, 'reports')
"
```

## 📊 Key Findings

### Promotion Rate
- **72.5%** of students were promoted
- **27.5%** were not promoted

### Success Factors
1. **High GPA** (3.7+ average for promoted students)
2. **Excellent attendance** (95%+ for promoted students)
3. **More courses passed** (12+ courses for promoted students)
4. **Strong programming skills** (8+ rating for promoted students)
5. **Internship experience** significantly increases promotion chances

### Visualizations Included
- 📊 **Pie charts** for promotion distribution
- 📈 **Box plots** for feature comparison
- 🔥 **Heatmaps** for correlation analysis
- 📉 **Scatter plots** for relationship exploration
- 📋 **Bar charts** for categorical comparisons

## 🎨 Colorful Excel Report

The project includes a professionally formatted Excel report with:
- ✅ **Green highlighting** for promoted students
- ❌ **Red highlighting** for non-promoted students
- 📊 **Auto-adjusted column widths**
- 🎨 **Professional styling** with headers

## 🛠️ Technologies Used

- **Python 3.11+** - Programming language
- **Pandas** - Data manipulation
- **Matplotlib/Seaborn** - Static visualizations
- **Plotly** - Interactive charts
- **Jupyter** - Interactive notebooks
- **OpenPyXL** - Excel file handling

## 📈 Sample Insights

```python
# Quick preview of key statistics
{
    'Total Students': 40,
    'Promoted Students': 29,
    'Not Promoted Students': 11,
    'Average GPA': 3.71,
    'Average Attendance': 92.3,
    'Average Courses Passed': 11.3,
    'Promotion Rate (%)': 72.5
}
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact 08113006574

For questions or suggestions, please open an issue on GitHub or contact the project maintainers.

---

**⭐ Star this repository if you find it helpful!**
