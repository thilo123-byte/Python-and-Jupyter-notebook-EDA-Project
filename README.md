## Manufacturing Quality Analysis(EDA Project)

# Project Overview
This project performs exploratory data analysis(EDA) on a simulated manufacturing data to investigate potential factors influencing product defects.The analysis uses python data analysis tools to explore relationships between operational variables like pressure,temperature, machine runtime and defect counts.

# Objectives 
- Perform data cleaning and preparation
- Explore defect distributions and process variation
- Analyse relationships between operational variables and defects
- Compare machine performances and operator perfomances using defect counts and rates.
- Visualize manufacturing data using statistical plots

# Dataset
The dataset contains 5000 simulated manufacturing observations with variables representing machine operations and defect outcomes. Key variables involve pressure,temperature,machine_runtime,machine_id,operator_id and defect_count. The data set is simulated and designed to practice data and quality analysis.

# Tools and Libraries
The project was developed using the following tools;
- Python
- Pandas - Data manipulation and analysis
- Matplotlib - Data visualizations
- Jupyter Notebook - Interactive Analysis Environment

# Analysis Workflow
- Data loading
- Data cleaning
- Exploratory Statistics
- Defect rate analysis
- Outlier detection
- Correlation Analysis
- Operator performance comparisons
- Machine Performance Comparisons
- Visualizations

# Key Visualizations
- Pareto chart - Identifies the most frequent defect counts
- Box plots - Defect outliers and distributions
- Scatter plots - Explore relationships between variables
- Correlation Matrix - Quantifies variables relationships
- Machine and operator charts - compares defect rates across machines and operators

# Key Findings
- Correlation analysis revealed weak relationships between operational variables and defect counts. All well below 0.03.
- Scatter plots confirmed the absence of strong linear relationships
- Machine defect rates were very similar, ranging from 0.97-1.18.
The analysis suggests that the defects may arise from common cause variation rather than a single dominant factor

# Conclusion
The Exploratory Analysis indicates that the manufacturing process appears relatively stable, with consistent performance across machines. No single operational variable strongly explains defect occurrence,suggesting that defects may arise from multiple small factors within the production process. This project demonstrates a structured approach to manufacturing data exploration and quality analysis using python.

# Future Improvements
Potential extensions to this analysis include:
- Predictive modeling for defect prediction
- Machine learning classification models
- Process Capability Analysis
- Interactive dashboards using Power BI

## Author
Data analysis Project by **Nkosinathi Hlophe**

Tools: Python|Pandas|Matplotlib
