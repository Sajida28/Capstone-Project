# Capstone-Project
# **Analyzing Air Pollution Exposure in Affordable Housing Programs**

## **Introduction**
### **Project Overview**
This project evaluates the exposure of federally assisted affordable housing (LIHTC and Public Housing properties) to air pollution, specifically Particulate Matter (PM2.5) and Ozone. Using statistical analysis, machine learning, and spatial analysis, it provides insights into the effectiveness of housing policies in mitigating environmental risks for vulnerable populations.

---

## **Objectives**
- Assess air pollution exposure in federally assisted affordable housing.
- Compare LIHTC and Public Housing properties.
- Evaluate socioeconomic and geographic disparities.
- Provide data-driven insights to support policy discussions.

---

## **Datasets**
### **Data Sources**
- **National Housing Preservation Database (NHPD):** Contains data on LIHTC and Public Housing properties.
- **Environmental Protection Agency's EJScreen:** Provides air pollution metrics like PM2.5, Ozone, and socioeconomic variables.

### **Key Variables**
- **Pollution Levels:** PM2.5, Ozone
- **Socioeconomic Factors:** PEOPCOLORPCT, LOWINCPCT, UNEMPPCT, UNDER5PCT, OVER64PCT
- **Geographic Data:** CensusTract, City, State

---

## **Methodology**
1. **Data Collection & Cleaning:**
   - Merged datasets on CensusTract.
   - Handled missing values and filtered for relevant properties.

2. **Exploratory Data Analysis:**
   - Correlation analysis, heatmaps, and histograms.

3. **Statistical Modeling:**
   - Linear regression, Lasso regression, and Random Forest with SHAP for feature importance.

4. **Machine Learning:**
   - Models: Logistic Regression, Random Forest, Gradient Boosting, MLP, and ensemble classifiers.
   - Evaluation: Classification reports, confusion matrices, and validation accuracies.

5. **Spatial Analysis:**
   - Created maps in ArcGIS Pro highlighting pollution exposure and disparities.

---

## **Results**
- LIHTC properties showed slightly higher PM2.5 exposure compared to Public Housing.
- Areas with higher PEOPCOLORPCT had greater air pollution levels.
- Ensemble models achieved the best classification accuracy for pollution thresholds.

### **Visuals**
- Confusion matrix snapshots.
- Example maps showing pollution levels in different CensusTracts.

---

## **Conclusion**
This study demonstrates the disparities in air pollution exposure for federally assisted housing, underscoring the need for environmentally equitable policies. Findings can guide policymakers to prioritize vulnerable populations.


## **Future Work**
- Include more pollutants like SO2 or NOx.
- Analyze heat, flooding, and tree canopy data for comprehensive environmental risk assessment.
- Enhance machine learning models with advanced hyperparameter tuning.

---

## **Acknowledgments**
- Professor Yana Kucheva for mentorship.
- Data sources: NHPD, EPA's EJScreen.

