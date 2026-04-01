# Guidelines for Developing a Project According to the CRISP-DM Standard

As part of the project, you should follow the steps of the CRISP-DM methodology: business understanding, data understanding, data preparation, modeling, evaluation, and deployment. The following structure outlines the documentation format you are expected to follow:

---

# FIRST PHASE OF THE PROJECT

## 1. Introduction

## 2. Business Understanding (5 points)

### 2.1. Define business objectives and data mining goals

- Describe the client’s primary objective from a business perspective.  
- In addition to the main business goal, there are usually other related business questions the client would like to address.  
- Describe the criteria for a successful or useful project outcome.

### 2.2. Conduct a cost–benefit analysis

- Prepare a cost–benefit analysis for the project, comparing the project’s costs with the potential business benefits if the project is successful.

### 2.3. Provide a literature review on the selected topic

- Identify 3 to 5 scientific or professional papers related to the chosen topic.  
- Describe the data and methods used in these studies.  
- Comment on the quality of the obtained model results.

## 3. Data Understanding (5 points)

### 3.1. Data Description

- Describe the collected data, including:
  - Data format  
  - Data volume (e.g., number of instances and attributes)  
  - Attribute types  

### 3.2. Data Exploration

- Produce and define:
  - Attribute distributions  
  - Summary statistics  
  - Relationships between attributes  
  - Basic statistical analyses  

### 3.3. Data Quality Verification

Answer the following questions:

- Are the data complete?  
- Are there any missing values?  
  - If so, how are they represented?  
  - Where do they occur?  
  - How frequent are they?  

---

# SECOND PHASE OF THE PROJECT

## 4. Data Preparation (10 points)

### 4.1. Data Selection

- Verification of multicollinearity and feature selection.

### 4.2. Data Cleaning

- Identification and resolution of data issues (e.g., missing values, outliers) in accordance with the chosen modeling technique.

### 4.3. Data Construction

- Creation of new attributes or transformations of existing attributes when necessary.

### 4.4. Data Integration

- Merging multiple data sources into a single, consistent dataset if required.

### 4.5. Data Formatting

- Preparing the data for analysis and modeling (e.g., scaling, encoding, feature transformations).

## 5. Modeling (10 points)

### 5.1. Selection of Modeling Technique

- A brief description and justification of the chosen modeling technique.

### 5.2. Test Design

- Planning the model testing strategy (cross-validation or other data partitioning methods).

### 5.3. Model Building

- Implementation of the selected models.

### 5.4. Model Assessment

- Hyperparameter optimization and evaluation of model performance using various metrics.

## 6. Evaluation (6 points)

### 6.1. Evaluation of Results

- A detailed analysis of the model outputs:
  - Discussion of performance metrics  
  - Sensitivity analysis  
- Comparison of results across different models and/or with findings from previous research when possible.

### 6.2. Process Assessment

- Evaluation of the effectiveness and success of the applied methods and techniques:
  - Whether algorithm assumptions were met  
  - Whether the dataset was appropriate  

### 6.3. Determining Next Steps

- Identification of potential improvements and suggestions for future work.

## 7. Deployment (4 points)

- Consideration of the practical application of the obtained results.

## 8. Conclusion

## 9. References