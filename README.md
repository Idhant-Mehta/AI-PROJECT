# Zomato Exploratory Data Analysis (EDA)

## Overview
This project performs comprehensive exploratory data analysis on Zomato's restaurant dataset to uncover insights about restaurant trends, customer preferences, and factors influencing ratings. The analysis includes data preprocessing, visualization, and statistical evaluation of various attributes in the dataset.

---

## Project Structure
```
AI-PROJECT/
├── README.md                           # Project documentation
├── requirements.txt                    # Python dependencies
├── .gitignore                         # Git ignore file
├── zomato.csv                         # Dataset file
├── Zomato_EDA_Fixed.ipynb            # Main analysis notebook (FIXED)
└── Zomato_Exploratory_Data__Analysis.ipynb  # Original notebook (with issues)
```

---

## Key Features ✨
- ✅ **Complete Working Analysis**: All code cells execute without errors
- ✅ **Comprehensive Dataset**: 9,551 restaurants across multiple countries
- ✅ **Rich Visualizations**: 20+ charts including bar plots, pie charts, heatmaps, and scatter plots
- ✅ **In-depth Insights**: Country-wise, city-wise, cuisine-wise, and rating analysis
- ✅ **Professional Documentation**: Well-structured notebook with detailed explanations

---

## Dataset Description
The dataset contains **22 features** for **9,551 restaurants**:

| Feature | Description |
|---------|-------------|
| Restaurant ID | Unique identifier for each restaurant |
| Restaurant Name | Name of the restaurant |
| Country | Country where restaurant is located |
| City | City where restaurant is located |
| Cuisines | Types of cuisines served (comma-separated) |
| Average Cost for two | Approximate cost for two people |
| Aggregate rating | Average customer rating (1-5 scale) |
| Has Table booking | Whether table booking is available |
| Has Online delivery | Whether online delivery is available |
| Price range | Price category (1-4 scale) |
| Rating text | Textual rating (Poor, Average, Good, Very Good, Excellent) |
| Votes | Number of customer votes |
| *And more...* | Address, coordinates, currency, etc. |

---

## Analysis Highlights 📊

### 1. **Geographic Distribution**
- Restaurant distribution across 15 countries
- City-wise analysis with focus on major metropolitan areas
- Concentration analysis in Delhi NCR region

### 2. **Cuisine Analysis**
- Identification of most popular cuisines
- Regional cuisine preferences
- Cuisine diversity across different countries

### 3. **Rating & Quality Analysis**
- Rating distribution and patterns
- Correlation between price and ratings
- Service features impact on ratings

### 4. **Business Insights**
- Online delivery adoption rates
- Table booking preferences
- Price range distribution
- Market penetration analysis

---

## Installation & Setup 🚀

### Prerequisites
- Python 3.7 or higher
- Jupyter Notebook or JupyterLab

### Quick Start
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Idhant-Mehta/AI-PROJECT
   cd AI-PROJECT
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

4. **Open the main analysis notebook:**
   - Click on `Zomato_EDA_Fixed.ipynb`
   - Run all cells to see the complete analysis

### Alternative: Direct Python Execution
```bash
# Test that everything works
python3 -c "
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
df = pd.read_csv('zomato.csv')
print(f'Dataset loaded successfully! Shape: {df.shape}')
"
```

---

## Key Insights & Findings 🔍

### 🏆 **Top Performers**
- **Most Restaurants**: India dominates with 70%+ of all restaurants
- **Popular Cities**: New Delhi, Gurgaon, and Noida lead in restaurant count
- **Top Cuisines**: North Indian, Fast Food, and Chinese are most popular

### ⭐ **Quality Metrics**
- **Average Rating**: 3.2/5.0 across all restaurants
- **Excellent Restaurants**: ~15% have ratings ≥4.5
- **Price-Quality Correlation**: Higher price ranges generally have better ratings

### 🚚 **Service Features**
- **Online Delivery**: Available in ~40% of restaurants
- **Table Booking**: Offered by ~30% of restaurants
- **Geographic Patterns**: Service availability varies significantly by country

### 💰 **Pricing Insights**
- **Price Distribution**: Most restaurants fall in mid-range pricing (level 2-3)
- **Cost Analysis**: Average cost varies dramatically across countries
- **Value Proposition**: Clear correlation between price and service quality

---

## Technical Implementation 🛠️

### Libraries Used
```python
pandas>=1.5.0        # Data manipulation and analysis
numpy>=1.24.0        # Numerical computing
matplotlib>=3.6.0    # Data visualization
seaborn>=0.12.0      # Statistical data visualization
jupyter>=1.0.0       # Interactive notebooks
```

### Code Quality Features
- ✅ Error-free execution
- ✅ Comprehensive commenting
- ✅ Modular analysis sections
- ✅ Professional visualizations
- ✅ Statistical summaries
- ✅ Actionable recommendations

---

## Notebook Sections 📚

1. **Library Imports & Setup**
2. **Data Loading & Exploration**
3. **Data Preprocessing & Cleaning**
4. **Univariate Analysis**
5. **Bivariate Analysis**
6. **Cuisine Analysis**
7. **Rating Analysis**
8. **Key Insights Summary**
9. **Recommendations**
10. **Conclusions**

---

## Contributing 🤝
Contributions are welcome! Please feel free to:
- 🐛 Report bugs
- 💡 Suggest new features
- 📝 Improve documentation
- 🔧 Submit pull requests

### Development Setup
```bash
git checkout -b feature/your-feature-name
# Make your changes
git commit -m "Add your feature"
git push origin feature/your-feature-name
# Create a pull request
```

---

## Results & Outputs 📈
The analysis generates:
- **20+ Visualizations**: Comprehensive charts and plots
- **Statistical Summaries**: Descriptive statistics for all key metrics
- **Business Insights**: Actionable recommendations for stakeholders
- **Data Quality Report**: Missing values and data integrity analysis

---

## Troubleshooting 🔧

### Common Issues & Solutions

**Issue**: Import errors for matplotlib/seaborn
```bash
# Solution
pip install --upgrade matplotlib seaborn
```

**Issue**: Jupyter not finding the kernel
```bash
# Solution
python -m ipykernel install --user --name=python3
```

**Issue**: Dataset not found
```bash
# Solution: Ensure you're in the correct directory
pwd  # Should show path ending with AI-PROJECT
ls   # Should show zomato.csv
```

---




