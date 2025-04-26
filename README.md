# US Accidents Exploratory Data Analysis

## Project Overview
This project performs an in-depth exploratory data analysis of US traffic accidents from 2016 to 2021. The analysis aims to uncover patterns, trends, and insights that could help improve road safety and traffic management.

## Dataset
The US Accidents (2016-2021) dataset from Kaggle contains approximately 2.8 million records of accidents across 49 US states. Each record includes detailed information about:
- Accident location (lat/long, city, state)
- Timing (start/end time)
- Weather conditions
- Road features
- Severity levels

## Project Structure
```
Exploratory-Data-Analysis-Project/
├── data/                          # Data directory
│   ├── raw/                      # Raw data files
│   └── processed/                # Cleaned and processed data
├── notebooks/                    # Jupyter notebooks
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   └── 03_advanced_analysis.ipynb
├── requirements.txt              # Project dependencies
├── README.md                     # Project documentation
└── .gitignore                   # Git ignore file
```

## Key Findings
(To be updated with analysis results)

## Installation and Setup
1. Clone this repository
2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Analysis Sections
1. Data Cleaning and Preparation
   - Handle missing values
   - Remove duplicates
   - Format dates and times
   - Validate data consistency

2. Exploratory Analysis
   - Temporal patterns (daily, weekly, monthly trends)
   - Geographical distribution
   - Severity analysis
   - Weather impact analysis

3. Advanced Analysis
   - Statistical tests
   - Correlation studies
   - Predictive modeling
   - Interactive visualizations

## Technologies Used
- Python 3.x
- Pandas for data manipulation
- Matplotlib and Seaborn for visualization
- Folium for geographical visualization
- Scikit-learn for machine learning
- Plotly for interactive visualizations

## Future Improvements
- Add machine learning models for accident prediction
- Create interactive dashboard
- Include real-time data integration
- Expand geographical analysis

## Contributing
Feel free to fork this repository and submit pull requests for any improvements.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
