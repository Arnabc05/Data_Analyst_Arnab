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

Python (Pandas, NumPy, Matplotlib, Seaborn) 

SQL (Athena) 










