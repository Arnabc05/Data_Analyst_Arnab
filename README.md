# Data_Analyst_Arnab
**Exploratory Data Analysis for the CIty of Vancouver**

**Project Description**- The projects outlined attention on diverse information evaluation and facts pleasant tasks, inclusive of statistics profiling for the City of Vancouver's datasets. Descriptive evaluation is used to broaden a facts analytics platform for the City of Vancouver, and facts wrangling is emphasised to clean and remodel customer statistics for stepped forward analytics. A Data Quality Control framework is proposed to make certain information accuracy and consistency throughout companies. These tasks intention to provide actionable insights, improve decision-making, and ensure quality statistics for ongoing analysis.


**Objective**- To design and implement a data analytic platform to guide descriptive evaluation for the City of Vancouver. This entails gaining insights into numerous components, along with environmental tracking.

**Dataset**- This platfrom uses the data called **operating-permits-water-systems-water-quality-reports** availble in csv format and it has obtained from the opendata.vancouver.ca. It has the following tables in it-

1. Permit Number
2. Water System Name
3. Turbidity Level
4. Permit Status
5. Region of Data
6. Inspection Dates

**Methodology**- The methodology for studying and profiling the **operating-permits-water-systems-water-quality-reports.csv** dataset in the AWS setup consists of a couple of levels, which involve facts series, education, cleansing, profiling, and evaluation. Here is a detailed step-with the aid of-step breakdown:

1. **Data Collection and Preparation**-

**Extraction of Data** - The above dataset has been obtained from an open datasource.

**Ingestion of Data**- The dataset is stored in an Amazon S3 bucket named Vancourvercity-raw-arnab.

2. **Data Cleaning**-

The statistics cleansing procedure involves disposing of duplicates, managing missing values via imputation or elimination, correcting statistics sorts, standardizing formats, detecting and dealing with outliers, and resolving inconsistencies in specific variables. Data profiling includes assessing the dataset’s shape, reading missing records, calculating precis records for numerical and express features, visualizing records distributions, analyzing correlations between variables, and identifying statistics satisfactory problems like inconsistencies or invalid entries. These steps make sure the dataset is clean, correct, and geared up for in addition analysis.

3. **Data Transformation**
   
Feature engineering involves remodeling or developing new variables to beautify analysis, inclusive of extracting annualy, monthly, or quarterly from permit expiry dates for time-based totally insights and categorizing water first-class indicators into "Good," "Average," or "Poor" based on threshold values. Data aggregation facilitates identify tendencies by means of summarizing water fine rankings in step with vicinity or through the years. AWS Glue transformations allow efficient ETL tactics, along with merging datasets from diverse sources and converting information formats (e.G., CSV to Parquet) to improve overall performance and usability for analysis.

4. 







