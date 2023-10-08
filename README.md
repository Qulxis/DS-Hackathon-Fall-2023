## **Columbia Data Science Society Datathon Fall 2023**

### **Team: Eco Innovators**

### **Track: Energy**

**Authors:**

- [Andrew X](https://github.com/Qulxis)
- [Kenneth M](https://github.com/Kennethm-spec)
- [Bilal G](https://github.com/13trillion)

**Project Description: Enhancing NYC Building Sustainability**

**Introduction**
New York City is a frontrunner in environmental sustainability, dedicated to reducing greenhouse gas emissions and minimizing its ecological footprint. With over 70 percent of the city's emissions stemming from buildings, a 2010 mandate now requires large building owners to publicly disclose their energy and water consumption data, reflecting a shared commitment to a greener future.

**Project Objective**
This data analysis project aims to leverage NYC's building data to identify structures with disproportionately high carbon footprints compared to their size. Our objective is to provide insights and recommendations that promote sustainability in the city.

**Key Objectives**

- **Data Preprocessing:** Clean, transform, and prepare data, addressing missing values, standardizing units, and ensuring data quality.
- **Exploratory Data Analysis (EDA):** Discover patterns, trends, and anomalies in the data, exploring energy and water consumption variations across different building types and locations.
- **Carbon Footprint Assessment:** Develop a metric for evaluating building carbon footprints, accounting for energy and water consumption, size, and other factors.
- **Identify High-Impact Buildings:** Use data analysis to spot buildings with unexpectedly high carbon footprints relative to their characteristics.
- **Recommendations for Sustainability:** Offer data-driven suggestions for reducing carbon footprints, including energy efficiency enhancements and water conservation.
- **Visualizations and Reporting:** Create clear visualizations and reports for building owners, city officials, and stakeholders to facilitate decision-making.

**Expected Outcomes**

- Identification of high-impact buildings based on size and characteristics.
- Data-backed recommendations for enhancing energy and water efficiency.
- Improved environmental sustainability and reduced greenhouse gas emissions.
- Increased public awareness about the environmental impact of buildings.

./

```
├── README.md
├── requirements.txt
├── src
│   ├── 1_Searching_the_domain.ipynb
│   ├── 2_preprocessing.ipynb
│   ├── 3_carbon_footprint_assessment.ipynb
│   ├── 4_feature_analysis.ipynb
│   ├── 5_net_emission_regression.ipynb
│   ├── data
│   │   ├── data_cleaned.csv
│   │   ├── data_cleaned2.csv
│   │   ├── data_cleaned3.csv
│   │   ├── data_full.csv
│   │   ├── feature_selection.json
│   │   ├── feature_selection2.json
│   │   ├── map_files
│   │   │   ├── ZIP_CODE_040114.dbf
│   │   │   ├── ZIP_CODE_040114.prj
│   │   │   ├── ZIP_CODE_040114.sbn
│   │   │   ├── ZIP_CODE_040114.sbx
│   │   │   ├── ZIP_CODE_040114.shp
│   │   │   ├── ZIP_CODE_040114.shp.xml
│   │   │   └── ZIP_CODE_040114.shx
│   │   ├── plots
│   │   │   ├── Average Carbon Emissions per ZIP Code in NYC.png
│   │   │   ├── Correlation Matrix.png
│   │   │   ├── Emissions Efficiency per ZIP Code in NYC.png
│   │   │   ├── Year built vs Average National Median Site EUI (Lower indicates better energy efficiency).png
│   │   │   ├── eigenvalues_explained.png
│   │   │   ├── features_explained.png
│   │   │   └── k-mean-cluster.png
│   │   ├── schema.json
│   │   ├── schema_cleaned.json
│   │   ├── schema_cleaned2.json
│   │   ├── schema_cleaned3.json
│   │   └── selected_features.csv
│   ├── general_insights.ipynb
│   └── schema.py
└── tree.ipynb

4 directories, 35 files
```
