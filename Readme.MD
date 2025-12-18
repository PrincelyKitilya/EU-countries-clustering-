# Global Economic Clustering & Interactive Data Visualization Dashboard

An interactive data visualization dashboard that groups countries into economic clusters using **K-Means clustering** and enables exploratory analysis of relationships between key economic indicators.  
The tool provides insights into global economic patterns through an intuitive, interactive interface.

---

## Objectives

### Cluster Analysis
- Group countries into distinct economic categories based on multiple development indicators

### Interactive Exploration
- Enable dynamic comparison of **GDP per capita** against various economic metrics

### Pattern Discovery
- Identify correlations and outliers in global economic data

### Data-Driven Insights
- Support policy analysis, investment decisions, and academic research

---

## Technical Scope

### Core Functionality

#### Data Processing
- Aggregate country-level economic indicators  
- Handle missing values and normalize data for clustering  
- Prepare structured datasets for visualization  

#### Clustering Engine
- Implement **K-Means** algorithm for unsupervised learning  
- Standardize features to ensure equal weighting in clustering  
- Assign countries to economic clusters based on multiple dimensions  

#### Interactive Visualization
- Dynamic scatter plots with bubble sizing and cluster coloring  
- Dropdown-based variable selection for comparative analysis  
- Interactive hover information with formatted economic data  
- Responsive design for different screen sizes  

---

## Features

- **Multi-Variable Analysis**  
  Compare GDP per capita against 5+ economic indicators  

- **Cluster Visualization**  
  Color-coded country groupings with a clear legend  

- **Interactive Elements**
  - Select any economic metric for X-axis comparison  
  - Hover for detailed country-level statistics  
  - Bubble sizing proportional to GDP magnitude  

- **Export Ready**  
  Clean, structured outputs suitable for further analysis or reporting  

---

## Data Indicators Analyzed

The dashboard visualizes relationships between:

### Primary Metric
- **GDP per capita**

### Comparative Metrics
- Health spending per capita (US$)  
- Education spending (% of GDP)  
- Investment (% of GDP)  
- Labor force participation rate (%)  
- Population size  

---

## Visualization Features

- **Dynamic Scatter Plots** for relationship exploration  
- **Cluster Coloring** representing 4 distinct economic groups  
- **Bubble Sizing** to emphasize economic scale  
- **Interactive Tooltips** with detailed country information  
- **Clean, Professional Layout** suitable for publication and presentations  

---

## Technical Stack

- **Data Processing:** Pandas, NumPy  
- **Machine Learning:** Scikit-learn (`KMeans`, `StandardScaler`)  
- **Visualization:** Plotly Express  
- **Interactivity:** IPython Widgets  
- **Environment:** Jupyter Notebook / Python 3.x  
