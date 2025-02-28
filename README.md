# Marine Fish Data Analysis

![Marine Biology](https://img.shields.io/badge/Marine-Biology-blue)
![Data Analysis](https://img.shields.io/badge/Data-Analysis-green)
![Python](https://img.shields.io/badge/Python-3.9-yellow)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📊 Project Overview

This project analyzes a comprehensive marine fish dataset to understand various factors affecting fish populations and their ecological relationships. The analysis explores correlations between fish population, size, water temperature, and pollution levels across different regions and fishing methods.

## 🔍 Dataset Description

The dataset (`Marine_Fish_Data.csv`) contains 500 records with the following attributes:

- **Species_Name**: Type of fish (Salmon, Tuna, Cod, Herring, Mackerel, Sardine, Shark, Snapper)
- **Region**: Geographic location (North Atlantic, Pacific Ocean, Mediterranean Sea, Indian Ocean)
- **Breeding_Season**: Season when fish breed (Summer, Monsoon, Winter)
- **Fishing_Method**: Method used for fishing (Net, Line, Trawl)
- **Fish_Population**: Number of fish counted in the area
- **Average_Size(cm)**: Average size of fish in centimeters
- **Overfishing_Risk**: Whether the species is at risk of overfishing (Yes/No)
- **Water_Temperature(C)**: Water temperature in Celsius
- **Water_Pollution_Level**: Level of water pollution (High, Medium, Low)

## 🛠️ Installation & Setup

### Prerequisites
- Python 3.9 or higher
- Jupyter Notebook/Lab or Google Colab

### Required Libraries
```bash
pip install pandas
pip install matplotlib
pip install seaborn
pip install numpy
pip install scikit-learn
```

### How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/marine-fish-analysis.git
   cd marine-fish-analysis
   ```

2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook:
   ```bash
   jupyter notebook Marine_Fish_Data_Analysis.ipynb
   ```

## 📈 Analysis Performed

### Data Preprocessing
- Checked for duplicate values and missing data
- Verified data types and structure
- Confirmed temperature range validity

### Exploratory Data Analysis (EDA)
1. **Frequency Distribution Plots**
   - Fish species distribution across regions
   - Distribution of fishing methods
   - Breeding season distribution

2. **Bar Plots**
   - Fish population by breeding season
   - Fish population by water pollution level
   - Average fish size by species

3. **Pie Charts**
   - Distribution of fish population by species
   - Distribution by fishing method
   - Overfishing risk distribution

4. **Histograms**
   - Distribution of fish sizes
   - Distribution of water temperatures

5. **Box Plots**
   - Fish size by water pollution level
   - Fish size by fishing method

6. **Correlation Analysis**
   - Relationship between fish population and size
   - Relationship between water temperature and fish population
   - Relationship between water temperature and average fish size

### Cluster Analysis
- K-means clustering on fish population, size, and water temperature
- Visualization of clusters in 2D and 3D space
- Analysis of cluster characteristics

## 🔑 Key Findings

1. **Correlations**:
   - Strong negative correlation between fish size and population (as fish size increases, population decreases)
   - Strong negative correlation between water temperature and fish population
   - Negative correlation between water temperature and average fish size

2. **Pollution Impact**:
   - Areas with lower pollution levels tend to have higher fish populations
   - Fish size is less affected by pollution levels than expected

3. **Fishing Methods**:
   - Line fishing has the highest average catch size
   - Trawling affects a wider range of species

4. **Ecological Clusters**:
   - Successfully identified three distinct ecological clusters based on population, size, and temperature
   - Cluster 1: Large population, medium size fish, higher water temperature
   - Cluster 2: Small population, small fish, lower water temperature
   - Cluster 3: Medium population, larger fish, medium water temperature

## 📊 Visualizations

The project includes multiple visualization types:
- Distribution plots
- Correlation heatmaps
- Pair plots
- Cluster visualizations in 2D and 3D
- Box plots and violin plots for comparative analysis

## 🔄 Future Work

1. Include temporal analysis to track fish population changes over time
2. Incorporate additional variables such as ocean currents and food availability
3. Develop predictive models for fish population based on environmental factors
4. Create interactive dashboards for real-time monitoring
5. Compare results with other marine ecosystems

## 🔗 References

- Marine Biology Institute Reference Database
- Oceanographic Data Collection Standards
- Fisheries Management Analysis Framework

## 👤 Author

- Mega Viswanathan

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

For questions or feedback, please open an issue or contact me at [your.email@example.com](mailto:your.email@example.com).
