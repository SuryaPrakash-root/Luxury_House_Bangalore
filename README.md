# Luxury House Bangalore

A comprehensive data analysis project on luxury housing market in Bangalore, India. This project focuses on data cleaning, exploration, and analysis of luxury property transactions in the Bangalore metropolitan area.

## Project Overview

This 2nd semester project analyzes luxury housing sales data in Bangalore to identify trends, patterns, and insights in the high-end real estate market. The analysis includes data cleaning, exploratory data analysis (EDA), and comprehensive sales insights.

## Dataset

The dataset contains detailed information about luxury property transactions in Bangalore with the following key features:

### Property Details
- **Property ID**: Unique identifier for each property
- **Micro Market**: Specific locality/area within Bangalore
- **Project Name**: Name of the residential project
- **Developer Name**: Name of the real estate developer
- **Unit Size (Sqft)**: Size of the property in square feet
- **Configuration**: Number of bedrooms/bathrooms (2BHK, 3BHK, 4BHK, etc.)

### Transaction Information
- **Ticket Price (Cr)**: Property price in Crores
- **Transaction Type**: Primary or Secondary transaction
- **Purchase Quarter**: Quarter and year of purchase
- **Possession Status**: Current status (Launch, Under construction, Ready to move)
- **Buyer Type**: NRI or Other
- **Sales Channel**: Broker, NRI Desk, Direct, Online

### Property Attributes
- **Connectivity Score**: Proximity to transportation hubs (0-10 scale)
- **Amenity Score**: Quality and availability of amenities (0-10 scale)
- **Locality Infra Score**: Infrastructure quality of the locality (0-10 scale)
- **Avg Traffic Time (Min)**: Average traffic time to major business districts
- **Buyer Comments**: Qualitative feedback from buyers

## Project Structure

```
Luxury_House_Bangalore/
├── README.md                                    # Project documentation
├── Data_Cleaning.ipynb                         # Data cleaning and preprocessing
├── Luxury_Housing_Bangalore.csv                # Main dataset
├── Luxury_Housing_Sales_Analysis.docx          # Detailed analysis report
├── .gitignore                                  # Git ignore file
└── .gitattributes                              # Git attributes file
```

## Files Description

### Data_Cleaning.ipynb
Jupyter notebook containing:
- Data loading and initial exploration
- Data type conversions and cleaning
- Missing value handling
- Data validation and quality checks
- Preprocessing for analysis

### Luxury_Housing_Bangalore.csv
Raw dataset containing approximately 4000+ luxury property transactions in Bangalore with 15+ features.

### Luxury_Housing_Sales_Analysis.docx
Detailed analysis report containing:
- Market trends and insights
- Price analysis by location and configuration
- Buyer preferences and patterns
- Market predictions and recommendations

## Key Insights

- Analysis of luxury property price distribution across different micro-markets
- Correlation between property features and pricing
- Buyer type patterns (NRI vs Local buyers)
- Sales channel effectiveness analysis
- Impact of connectivity and amenities on property prices
- Market trends over different quarters

## Technologies & Tools Used

- **Python**: Data analysis and manipulation
- **Pandas**: Data cleaning and transformation
- **NumPy**: Numerical computations
- **Jupyter Notebook**: Interactive analysis environment
- **Data Visualization**: Insights representation

## Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook
- pandas
- numpy

### Installation

1. Clone the repository:
```bash
git clone https://github.com/SuryaPrakash-root/Luxury_House_Bangalore.git
```

2. Navigate to the project directory:
```bash
cd Luxury_House_Bangalore
```

3. Install required dependencies:
```bash
pip install pandas numpy jupyter
```

### Running the Analysis

1. Start Jupyter Notebook:
```bash
jupyter notebook
```

2. Open `Data_Cleaning.ipynb` to view the data cleaning process

3. Load and analyze the `Luxury_Housing_Bangalore.csv` dataset

## Data Cleaning Process

The notebook includes:
- Handling missing values in numerical and categorical columns
- Type conversions (string to numeric, object to categorical)
- Removing duplicates
- Outlier detection and treatment
- Feature engineering for enhanced analysis

## Analysis Features

- **Exploratory Data Analysis**: Understanding data distribution and relationships
- **Statistical Analysis**: Descriptive statistics and correlations
- **Market Segmentation**: Grouping properties by micro-market, configuration, and price range
- **Trend Analysis**: Price and volume trends over time
- **Buyer Behavior Analysis**: Understanding NRI vs Local buyer preferences

## Key Findings

- Luxury property prices vary significantly across different micro-markets in Bangalore
- 3BHK and 4BHK configurations are most popular in the luxury segment
- Connectivity and amenity scores significantly impact property valuation
- NRI buyers represent a substantial portion of luxury property purchases
- Primary transactions dominate the luxury segment

## Future Enhancements

- Develop predictive models for property price estimation
- Create interactive visualizations and dashboards
- Implement machine learning models for buyer preference prediction
- Expand analysis to include more temporal data
- Integrate external data (traffic patterns, weather, infrastructure development)

## Author

**Surya Prakash** - [@SuryaPrakash-root](https://github.com/SuryaPrakash-root)

## Contact

For questions or suggestions regarding this project, please feel free to open an issue or contact the author.

## License

This project is open source and available for educational and research purposes.

## Acknowledgments

- Data sourced from luxury housing transactions in Bangalore
- Project developed as part of 2nd semester coursework
- Special thanks to all contributors and mentors who provided guidance

---

**Last Updated**: December 2025

*Note: This is a learning project focusing on real estate market analysis. All data is for analytical purposes only.*
