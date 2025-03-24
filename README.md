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

1. **Ingestion of Data**

The dataset is first saved in an AWS S3 bucket named **Vancouercity-raw-arnab** to ensure steady and scalable storage. AWS Glue is used to extract, catalog, and arrange the information, making it equipped for analysis. To improve overall performance, the information can be transformed into optimized codecs together with Parquet, which permits faster querying and processing.

2. **Data Profiling**

A preliminary analysis is performed the usage of **AWS Glue DataBrew** to assess facts great and shape. This consists of figuring out lacking values, reproduction records, incorrect records sorts, and inconsistencies. Summary information such as average median, mode, and widespread deviation are calculated for numerical attributes, whilst frequency distributions are generated for express statistics.

3. **Data Cleaning**

Missing values are dealt with by means of changing absent turbidity values with the median unique to every vicinity, making sure a more correct representation of water pleasant. Any lacking permit popularity entries are packed with "Unknown" to preserve consistency throughout information. Duplicate entries are removed to ensure each water system has a unique file in line with reporting duration. Additionally, date fields are standardized to a constant YYYY-MM-DD layout, improving statistics uniformity and facilitating seamless evaluation.

 4. **Data Aggregation and Summarization**

The dataset is grouped by means of place, term, and water device to identify trends. Average turbidity levels consistent with place are calculated, and water pleasant ratings are categorized into "Good," "Moderate," or "Poor." Data is similarly analyzed by way of year, month, and zone to tune long-time period modifications. High-threat water systems with bad pleasant rankings are flagged for similarly research.

5. **Data Visualization**

Various visualization techniques are used to research water fine facts effectively. Histograms and boxplots illustrate the distribution of turbidity and pH stages, assisting discover outliers and trends. Time collection graphs tune adjustments in water high-quality over time, highlighting seasonal styles or anomalies. Bar charts examine turbidity degrees throughout distinct areas, imparting insights into geographic versions. Heatmaps screen correlations between water best signs, assisting apprehend relationships between exclusive parameters.

6. **Interpretation and Insights**

The evaluation identifies areas with continually bad water pleasant, detects seasonal patterns or sudden fluctuations, and examines whether allow repute impacts water best consequences. Based on these findings, guidelines are furnished for further evaluation or vital interventions to enhance water management and regulatory compliance.

**Tools and Technologies**

AWS S3

AWS Glue 

AWS Glue DataBrew 

AWS QuickSight

Athena (SQL)


**Deliverables**
Cleaned and structured dataset stored in AWS S3.

Descriptive analysis report summarizing key findings.

Interactive dashboards in AWS QuickSight showing water quality trends.

Actionable insights and recommendations for city authorities to improve water quality monitoring.
![image](https://github.com/user-attachments/assets/78b53bb1-0ce7-406b-8f39-02519c5d5c13)



**Desciptive Analysis**
Descriptive evaluation includes summarizing and decoding raw statistics to discover patterns, developments, and insights. It presents a excessive-degree view of the dataset via measuring key records such as suggest, median, standard deviation, and distribution of variables. In the context of the operating-lets in-water-systems-water-quality-reviews.csv dataset, descriptive evaluation allows understand the characteristics of water first-class indicators and allow statuses throughout extraordinary regions.

**Objective**
The objective of the descriptive analysis is to summarize key dataset features, including turbidity levels, pH values, and permit statuses. It aims to identify central tendencies (mean, median, mode) and dispersion (variance, standard deviation) of water quality parameters, detect outliers and anomalies, and explore relationships between different attributes, such as regional differences in water quality.

**Methodlogy**

**1.** **Data Profiling**

The dataset's structure is analyzed by identifying column types, missing values, and unique counts. Additionally, inconsistencies such as duplicate records or incorrect data formats are checked to ensure data quality and accuracy.

**2** **Stastical Summery**

A statistical Summary is generated via computing key metrics for numerical variables like turbidity and pH stages, at the same time as frequency distributions are used to investigate categorical variables together with allow frame.

**Visualization**

Visualization techniques encompass histograms and boxplots to analyze the distribution of water satisfactory parameters, time series graphs to tune developments through the years, bar charts for nearby comparisons, and heatmaps to expose correlations between specific water exceptional signs.

**Key Insights**

Descriptive analysis reveals typical water quality conditions, seasonal and regional variations, and potential anomalies that may indicate data quality issues or pollution events requiring regulatory attention.

**Deliverables**

A summary report of key statistics and trends.

Visualizations illustrating patterns and distributions in water quality parameters.

Identification of areas needing further diagnostic analysis to investigate potential causes of water quality variations.

![image](https://github.com/user-attachments/assets/d731f34d-2ca2-4a92-8a6a-a9959255871d)


**Conclusion**

The descriptive and exploratory analyses provide valuable insights into water quality trends, regional disparities, and potential anomalies. Descriptive analysis establishes a baseline understanding of key parameters like turbidity and pH, highlighting central tendencies, variability, and distributions. Exploratory analysis further uncovers patterns, such as seasonal fluctuations, correlations between indicators, and the impact of permit status on water quality. Identifying outliers and inconsistencies helps in improving data quality and detecting possible pollution events. These findings support data-driven decision-making for regulatory interventions and long-term water quality management.








