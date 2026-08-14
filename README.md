# 📊 Sales Data Analysis

A data analysis project focused on exploring and understanding sales performance using Python and data analytics techniques.

## 📌 Project Overview

This project analyzes historical sales transaction data to identify important sales trends, patterns, and business insights.

The analysis covers product performance, product categories, regions, sales representatives, customer types, sales channels, payment methods, and time-based sales trends.

The project follows a complete data analysis workflow:

**Data Loading → Data Cleaning → Data Preprocessing → Feature Engineering → Exploratory Data Analysis → Data Visualization → Business Insights**

## 🎯 Objectives

- Analyze overall sales performance
- Clean and preprocess the sales dataset
- Identify missing values and duplicate records
- Analyze sales trends over time
- Identify high-performing products and categories
- Compare sales performance across regions
- Analyze sales representative performance
- Understand customer-type and sales-channel behavior
- Analyze payment-method patterns
- Calculate revenue, cost, profit, and profit margin
- Identify relationships between important numerical variables
- Generate meaningful visualizations
- Extract actionable business insights

## 📂 Dataset

The project uses a CSV-based sales transaction dataset.

### Dataset Attributes

| Column | Description |
|---|---|
| `Product_ID` | Unique identifier for the product |
| `Sale_Date` | Date on which the sale occurred |
| `Sales_Rep` | Sales representative responsible for the sale |
| `Region` | Region where the sale was made |
| `Sales_Amount` | Recorded sales amount |
| `Quantity_Sold` | Number of units sold |
| `Product_Category` | Category of the product |
| `Unit_Cost` | Cost of one unit |
| `Unit_Price` | Selling price of one unit |
| `Customer_Type` | Type of customer |
| `Discount` | Discount associated with the transaction |
| `Payment_Method` | Method used for payment |
| `Sales_Channel` | Channel through which the sale occurred |
| `Region_and_Sales_Rep` | Combined region and sales representative information |

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 🔄 Project Workflow

1. Data Loading
2. Data Inspection
3. Data Cleaning
4. Data Type Conversion
5. Feature Engineering
6. Exploratory Data Analysis
7. Data Visualization
8. Correlation Analysis
9. Business Insights
10. Conclusion

## 🧹 Data Preprocessing

The dataset is prepared before performing analysis through the following steps:

- Checking dataset dimensions
- Inspecting column names and data types
- Checking for missing values
- Detecting duplicate records
- Checking numerical values for invalid entries
- Converting the sales date into datetime format
- Examining categorical variables
- Validating sales-related calculations

## ⚙️ Feature Engineering

Additional analytical features are created from the available sales information.

### Revenue

Revenue is obtained from the recorded sales amount.

### Total Cost

Total Cost = Unit Cost × Quantity Sold

### Profit

Profit = Revenue − Total Cost

### Profit Margin

Profit Margin = (Profit / Revenue) × 100

Time-based features are also extracted from `Sale_Date`, including:

- Year
- Month
- Month Name
- Quarter
- Day
- Day Name

## 📈 Exploratory Data Analysis

The project performs exploratory analysis across multiple dimensions.

### Sales Performance

Analysis of revenue, quantity sold, cost, profit, and profit margin.

### Product Analysis

Analysis of product and product-category performance based on sales.

### Regional Analysis

Comparison of sales performance across different regions.

### Sales Representative Analysis

Evaluation of sales performance across sales representatives.

### Customer Analysis

Analysis of sales according to customer type.

### Sales Channel Analysis

Comparison of sales performance across different sales channels.

### Payment Analysis

Analysis of transaction patterns across payment methods.

### Time-Series Analysis

Analysis of sales trends across different time periods.

### Correlation Analysis

Relationships between numerical variables are examined using correlation analysis and heatmaps.

## 📊 Visualizations

The project uses different visualizations to understand and communicate patterns in the sales data, including:

- Bar charts
- Line charts
- Histograms
- Scatter plots
- Correlation heatmaps

These visualizations help identify trends, comparisons, distributions, and relationships within the dataset.

## 💡 Business Insights

The analysis aims to identify insights such as:

- High-performing product categories
- High-performing regions
- Top-performing sales representatives
- Products generating significant revenue
- Differences between sales channels
- Customer-type purchasing patterns
- Monthly sales trends
- Profitability patterns
- Relationships between discounts, quantity, revenue, and profit

The final business insights are derived from the actual analysis performed in the Jupyter Notebook.

## 📁 Project Structure

```text
Sales_data_analysis/
├── data/
│   └── sales_data.csv
├── notebooks/
│   └── Sales_Data_Analysis.ipynb
├── README.md
└── requirements.txt
```

## 🚀 How to Run the Project

### 1. Clone the Repository

git clone <your-repository-url>

### 2. Navigate to the Project Directory

cd Sales_data_analysis

### 3. Install the Required Libraries

pip install pandas numpy matplotlib seaborn jupyter

### 4. Start Jupyter Notebook

jupyter notebook

### 5. Open the Notebook

notebooks/Sales_Data_Analysis.ipynb

### 6. Dataset Path

The dataset should be placed inside:

data/sales_data.csv

The notebook should load the dataset using:

df = pd.read_csv("../data/sales_data.csv")

## 🔮 Future Enhancements

The project can be extended with:

- Interactive sales dashboards
- Automated reporting
- Sales forecasting
- Customer segmentation
- Predictive analytics
- Machine learning-based sales prediction
- Real-time sales monitoring
- Advanced business intelligence dashboards

These are proposed future enhancements and are not part of the current implementation unless added to the project.

## 👩‍💻 Author

**Spurthi**

Computer Science Engineering – Data Science

## 📄 License

This project is created for educational and academic purposes.
