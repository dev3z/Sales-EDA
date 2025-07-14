# Sales EDA - Comprehensive Retail Sales Analysis

This project performs exploratory data analysis (EDA) on **10,000+ retail sales records** using Python, Pandas, and Seaborn. It analyzes customer behavior across age groups, gender, occupations, and geographic zones while profiling product category performance.

## 📊 Dataset Overview

The dataset `Sales Data.csv` contains transactional sales data with **10,775 records**, including:
- **Customer Demographics**: Gender, Age Groups, Marital Status, Occupation, State
- **Product Details**: Product ID, Product Category  
- **Sales Metrics**: Orders, Amount
- **Geographic Information**: State, Zone

## 🔍 Analysis Highlights

### Key Insights Discovered:
- **Gender Patterns**: Female buyers dominate both in quantity and purchase amounts
- **Age Demographics**: 26-35 age group represents the largest customer segment
- **Geographic Distribution**: Uttar Pradesh, Maharashtra, and Karnataka lead in sales
- **Occupational Trends**: IT, Healthcare, and Aviation sectors show highest engagement
- **Product Preferences**: Food, Clothing, and Electronics are the top-performing categories
- **Customer Segment**: Married women aged 26-35 form the primary customer base

### Analysis Coverage:
- **Multiple Charts** covering demographic, geographic, and product insights
- **Data Quality Analysis** with comprehensive cleaning and preparation
- **Customer Segmentation** across multiple dimensions
- **Key Findings** on purchasing patterns and customer behavior

## 📈 Visualizations

The analysis includes comprehensive visualizations covering:
- Gender distribution and spending patterns
- Age group analysis with purchase amounts
- Geographic sales performance by state
- Occupational spending analysis
- Product category preferences
- Marital status impact on purchasing behavior

📸 **Screenshots**: Visual outputs are available in the `screenshots/` folder showing key analysis charts.

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Running the Analysis
1. Clone this repository
2. Install required packages: `pip install pandas numpy matplotlib seaborn`
3. Open `Sales_Analysis.ipynb` in Jupyter Notebook
4. Run all cells to reproduce the analysis

## 📋 Analysis Methodology

### 1. Data Cleaning & Preparation
- Loaded dataset and removed unnecessary columns (`Status`, `unnamed1`)
- Handled null values to ensure data quality
- Converted data types for accurate analysis
- Renamed columns for clarity

### 2. Exploratory Data Analysis
- **Demographic Analysis**: Gender, age group, and marital status patterns
- **Geographic Analysis**: State-wise sales distribution and performance
- **Occupational Analysis**: Industry-wise customer behavior
- **Product Analysis**: Category performance and preferences

### 3. Key Business Insights
- Identified primary customer segment: Married women aged 26-35
- Discovered top-performing geographic markets
- Analyzed product category preferences
- Developed customer profiling insights

## 🎯 Key Takeaways

The analysis reveals that the business's primary customer segment consists of married women aged 26-35 from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, or Aviation sectors, with strong preferences for Food, Clothing, and Electronics products.

## 📊 Business Recommendations

- **Targeted Marketing**: Focus campaigns on the dominant customer segment
- **Product Strategy**: Prioritize inventory and promotions for top categories
- **Geographic Expansion**: Leverage insights for market expansion in high-performing states
- **Customer Retention**: Develop loyalty programs for high-value customer groups

## 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements or additional analysis.

## 📄 Files Structure

```
Sales-EDA/
├── Sales Data.csv          # Raw sales dataset
├── Sales_Analysis.ipynb    # Main analysis notebook
├── report.md              # Detailed analysis report
├── screenshots/           # Analysis visualization outputs
│   ├── gender analysis.png
│   ├── geographic analysis.png
│   ├── occupation.png
│   └── product category.png
└── README.md              # This file
```

---

*This comprehensive EDA provides data-driven insights for strategic business decision-making in retail sales optimization.*