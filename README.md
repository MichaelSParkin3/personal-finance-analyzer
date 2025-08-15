# 📊 Personal Finance Data Analysis - Learning Project

## 🎯 Project Overview
This is a learning project where I practiced data science skills using a personal finance dataset provided by Krumpy. The goal was to learn and demonstrate data cleaning, organization, visualization, and analysis techniques using Python and various data science tools.

## 📚 What I Learned
Through this project, I gained hands-on experience with:
- 🧹 **Data Cleaning**: Handling missing values, standardizing text data, and data type conversions
- 📊 **Data Organization**: Structuring and categorizing transaction data for analysis
- 🎨 **Data Visualization**: Creating meaningful charts and graphs to understand spending patterns
- 🔍 **Exploratory Data Analysis**: Discovering insights from raw financial data
- 📝 **Documentation**: Writing clean, well-commented code in Jupyter notebooks

## 🛠️ Tools & Technologies Used
- **Python 3.8+** 🐍 - Primary programming language
- **Pandas** 📋 - Data manipulation and cleaning
- **NumPy** 🔢 - Numerical operations and array handling
- **Matplotlib** 📈 - Basic plotting and visualization
- **Seaborn** 🎨 - Statistical data visualization and styling
- **Jupyter Notebook** 📓 - Interactive development and documentation

## 📁 Dataset Information
- **Source**: Dataset provided by Krumpy
- **Type**: Personal bank transaction records
- **Format**: CSV file with transaction details
- **Columns**: `name` (merchant), `amount`, `mode` (payment method), `DrCr` (debit/credit)

## 🔄 Analysis Workflow
1. **📥 Data Loading**: Imported the CSV dataset and performed initial inspection
2. **🔍 Data Exploration**: Examined data structure, types, and quality issues
3. **🧹 Data Cleaning**: 
   - Handled missing values in merchant names
   - Converted amount column to proper numeric type
   - Standardized text fields (lowercase, trimmed whitespace)
4. **🏷️ Categorization**: Created transaction categories based on merchant name patterns
5. **📊 Visualization**: Generated multiple chart types to understand spending patterns
6. **💡 Analysis**: Derived insights about spending behavior across categories

## 📈 Key Learning Outcomes
- **Data Preprocessing**: Learned to identify and fix common data quality issues
- **Pattern Matching**: Used regex and string operations for transaction categorization
- **Statistical Visualization**: Created boxplots, bar charts, and line plots for different analytical purposes
- **Code Documentation**: Practiced writing clear comments and markdown explanations
- **Jupyter Best Practices**: Organized analysis into logical sections with proper documentation

## 🎨 Visualizations Created
- **Box Plots** 📦: Showed transaction amount distributions and identified outliers
- **Bar Charts** 📊: Compared total spending across different categories
- **Line Charts** 📈: Visualized spending trends and relationships between categories

## 🚀 Getting Started
If you want to run this analysis:

1. **Clone the repository**
```bash
git clone https://github.com/MichaelSParkin3/personal-finance-analyzer.git
cd personal-finance-analyzer
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Launch Jupyter Notebook**
```bash
jupyter notebook finance_analyzer.ipynb
```

## 📝 Code Highlights
- **Efficient Categorization**: Used `numpy.select()` for performance over traditional if-else approaches
- **Data Validation**: Implemented checks for data quality throughout the process
- **Flexible Visualization**: Created reusable plotting code with proper formatting
- **Clean Documentation**: Added comprehensive comments explaining each step

## 🎓 Skills Demonstrated
- **Data Wrangling**: Cleaning messy real-world financial data
- **Feature Engineering**: Creating meaningful categories from transaction names
- **Statistical Analysis**: Computing aggregations and distributions
- **Data Storytelling**: Using visualizations to communicate insights
- **Code Organization**: Structuring analysis in a logical, reproducible way

## 🔮 Future Improvements
Ideas for extending this learning project:
- 📅 Add time-series analysis for spending trends over time
- 🤖 Implement machine learning for automatic transaction categorization
- 📱 Create an interactive dashboard using Plotly or Streamlit
- 💾 Add database integration for larger datasets
- 🧪 Include statistical testing for spending pattern significance

## 🙏 Acknowledgments
- **Krumpy** for providing the dataset that made this learning project possible
- **Python Data Science Community** for the excellent libraries and documentation
- **Jupyter Project** for the interactive notebook environment

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
*This project represents my journey in learning data science fundamentals through hands-on practice with real financial data.* 🚀📊
