## Mobile Phone Price Analysis

### Project Overview  
This project analyzes a comprehensive **Mobile Phone Price Dataset** to uncover insights into pricing, features, and brand performance. By utilizing advanced data analysis and visualization techniques, we explore the relationships between various phone specifications like RAM, storage, battery capacity, and screen size alongside pricing and brand preferences.

### Objectives  
- **Data Cleaning & Preprocessing**: Prepare the dataset for accurate and efficient analysis.
- **Exploratory Data Analysis (EDA)**: Identify trends, correlations, and key drivers of price.
- **Feature Analysis**: Explore how phone specifications influence price and brand preferences.
- **Visualizations**: Develop clear, intuitive charts and graphs to present insights.
- **Trend Analysis**: Examine the top-performing brands and their evolution in the market.

### Dataset  
The data used in this project was sourced from Kaggle’s [Mobile Phone Price Dataset](https://www.kaggle.com/datasets/rkiattisak/mobile-phone-price/data). It includes key specifications of mobile phones such as storage, RAM, camera configuration, battery capacity, screen size, and price, which are analyzed to understand trends in the mobile phone market.

### Tools & Technologies  
- **Pandas**: For data manipulation, transformation, and cleaning.
- **Matplotlib** & **Seaborn**: For creating professional and intuitive visualizations.
- **Jupyter Notebook**: For running Python code and visualizing results interactively.

### Data Cleaning  
The dataset underwent preprocessing to ensure clean and accurate data for analysis. The following steps were taken:
1. **Column Cleaning**: Removed extra spaces from column names.
2. **Numeric Conversion**: Used custom functions to clean and convert values in columns like Storage, RAM, Screen Size, Battery Capacity, and Price to numeric types.
3. **Camera Formatting**: The camera column was formatted to handle multiple camera specifications by splitting and joining values appropriately.
4. **Missing Data**: Rows with missing values in critical columns were dropped to ensure the integrity of the dataset.

### Analysis & Insights  
After cleaning and preprocessing the data, various analysis and visualizations were performed:
- **Price vs Storage**: Revealed a positive correlation where higher storage increases the price of the mobile phone.
- **Price vs RAM**: Showed a clear relationship between higher RAM and premium pricing, with Apple and Xiaomi leading in premium segments.
- **Price vs Battery Capacity**: Demonstrated that phones with higher battery capacities tend to be priced higher but with exceptions.
- **Price vs Screen Size**: Found that most phones in the price range between $250 and $1000 feature screen sizes between 6.0 and 6.5 inches, with a few larger screens among high-priced models.
- **Brand Analysis**: Identified that Samsung, Xiaomi, Oppo, Realme, and Vivo dominate 70% of the market share, with Samsung offering the highest variety of models.
- **Camera Configurations**: Phones with triple-camera setups had the highest count, while quad-camera phones exhibited the highest average price.

### Key Findings  
- **Price Distribution**: Most mobile phones are priced around $250, with 55% falling under the budget category (under $300), and 25% being mid-range.
- **Correlations**: 
  - A strong positive correlation was observed between *Price* and *Storage* (0.72) as well as *Price* and *RAM* (0.64).
  - *Price* had a negative correlation with *Battery Capacity* (-0.40), indicating that battery size does not always correspond to higher prices.
  - *Screen Size* and *Battery Capacity* showed a positive relationship (0.57).
  
- **Brand-Specific Insights**: 
  - **Apple**: Tends to have the highest-priced devices, with a wide range of prices.
  - **Xiaomi & Realme**: Offer the lowest-priced models.
  - **Sony**: Leads in battery capacity with phones featuring 5000mAh or more.

### Visualizations  
- **Price vs Features**: Scatter plots visualizing the relationship between price and specifications such as storage, RAM, battery capacity, and screen size.
- **Distribution Charts**: Price, RAM, and battery capacity distributions across brands to identify trends and outliers.

### Acknowledgements  
We extend our gratitude to *Kaggle* for providing the **Mobile Phone Price Dataset**, which serves as the backbone for this analysis.

### File Structure  
Mobile-Price-Analysis/ ├── README.md ├── cleaned_mobile_price_data.csv # Cleaned dataset after preprocessing ├── mobile_price_analysis.ipynb # Jupyter notebook containing the analysis and visualizations ├── visualizations/ # Folder containing saved visualizations (charts/graphs)