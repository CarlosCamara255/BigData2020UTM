# **BigData2020UTM**

# Explain the impact of data today:
for the new fundamental technologies that change the way we gather, store, analyze and transform information.

# Explain the causes for which data generation has increased:
The speed of data generation accelerates and the value associated with it decreases over time. If it is not processed in real time, companies have to face lost opportunities with financial implications and, sometimes, especially in industrial IoT scenarios, they can lead to fatal situations.

# Define the concept of Big Data:
It is a term that describes the large volume of data, both structured and unstructured.

# Differentiate between open data and private data:
Open data means that anyone can access and can use that information as they please, instead private data only have access to certain people as employees or members of an organization and whose access is restricted.

# Differentiate between structured and unstructured data:
Structured data is mostly found in the database, they are text files that usually show in rows or columns with titles, unstructured data in general are binary data, it is a massive and disorganized conglomerate of several objects that have no value until it is identified.

# Differentiate between stored data and moving data:
The stored data are those found in a database without being passed from one side to the other, and the moving data are those that are being transmitted on a network.

# Define the meaning of data analysis:
Data analysis is used in several industries to allow companies and organizations to make better business decisions and is also used in science to verify or fail existing models or theories.

# Explain the impact of data analysis in organizations:
Improve the information you have available to help us make decisions. Convert the application data into visual representations helping customers describe concepts, discover opportunities, explore options and make more optimal decisions, all carried out by a very persuasive means.

# Explain the different types of data analysis:
|               |Type of data|Analysis|Examples|
| ------------- |:-------------:| ---------:| -------------:|
|Qualitative|It focuses on opinions, attitudes and beliefs.|Questions and answers to questions like: Why, how?|Panels where an argument is given and consumers are interviewed about what they like or not in the place.            
|Quantitative|It focuses on hard data and information that can be accounted for.|It is obtained through questions similar to: How many? Who? How often? Where?|Surveys focused on measuring sales, trends, reports or perceptions.|

# MapReduce:
It is a programming framework model used to support parallel computing.

# Hadoop:
It is an open source software structure for storing data and running applications.

# Apache spark
It is an open cluster computing system, unified analysis engine, ultrarapid for Big Data.

# Architecture Lambda and Kappa:

# GitHub Commands:
```
$ git init 
Turn an existing directory into a git repository
```
```
$ git add [file] 
Snapshots the file in preparation for versioning

```
```
$ git log 
Lists version history for the current branch

```
```
$ git reset [commit] 
Undoes all commits after [commit], preserving changes locally

```
```
$ git status
Lists all new or modified files that must be con ﬁ rmed
```
```
$ git diff --staged  
Show file differences between the waiting area and the latest version of the file
```
```
$ git rm [file]  
Delete the file from the active directory and put the deleted file in the waiting area
```
```
$ git commit -m "[descriptive message]"
Records file snapshots permanently in version history
```
# Second partial :books:

+ Data life cycle in BIG DATA: Given the characteristics of Big Data: volume, speed and variety; They require a different type of collection and analysis than any other type of data.
The Big Data analysis presents a great challenge, not only for the management of a large amount of data but also for the need to know the life cycle of the data and establish a base based on the nature of the Big Data.
  
  - The phases of the data life cycle in Big Data are as follows:
    
    - Análisis interno
    - Recogida y filtrado de datos
    - Extracción de datos
    - Validación y limpieza de los datos
    - Análisis de los datos
    - Visualización de los datos
    

+ Internal analysis: The Big Dara life cycle must begin with the understanding of the business and a justification of the need to carry out an analysis of this type, as well as the establishment of the objectives to be achieved. This stage of analysis allows us to understand the current situation of the company and what resources will be required throughout the analysis.
Likewise, those KPIs necessary to understand the results of the analysis and their ability to meet the established goals and objectives must be established.

+ Data collection and filtering: This part of the Big Data Life Cycle is dedicated to identifying those data relevant to the analysis, identifying the sources to find patterns and correlations.
The selection of data depends on the nature of the problem and the objectives established in the first part of the cycle. The data is collected and subjected to a filtering of corrupt data or data that does not respond to the established objectives.

+ Information extraction: The main objective of the data is to transform these into information. At this stage the data extraction and its transformation into an understandable format are carried out in order to perform a data analysis.

+ Validation and cleaning of data: Incorrect or invalid data can lead to false results that harm the analysis. The unstructured nature of Big Data makes their validation difficult. Therefore, this stage of the Big Data Life Cycle is essential, since it allows to reach the most relevant data for the objectives set.
In addition, this analysis not only allows the discarding of invalid data, but the analysis and observation of said data allow establishing patterns and trends that contribute to improving the understanding of the data to be analyzed

+ Data analysis: At this stage the integration of data sets is developed in order to give a unified view of the information. Throughout this stage of the cycle several problems of data structure and labels can occur.

+ Data visualization: Once the data is organized, it is necessary to transform it into information that provides value. All the useful information extracted must be “translated” in the form of reports that allow the correct interpretation of these.

  Reference: <https://piperlab.es/2019/05/14/el-ciclo-de-vida-de-los-datos-las-5-fases-para-llevar-a-exito-un-proyecto-de-big-data/>
***

 
+ Exploratory Data Analysis (A.E.D.): Is a set of statistical techniques whose purpose is to achieve a basic understanding of the       data and the relationships between the analyzed variables. To achieve this goal the A.E.D. provides simple systematic methods for       organizing and preparing data, detecting failures in the design and collection of data, treatment and evaluation of missing data,       identification of atypical cases (outliers) and verification of the underlying assumptions in most of multivariate techniques           (normality, linearity, homocedasticity). The prior examination of the data is a necessary step, which takes time, and is usually         neglected by data analysts. The tasks implicit in such an examination may seem insignificant and without consequences at first sight,   but they are an essential part of any statistical analysis.

  - STAGES OF THE AED To perform an AED:
   
    - Prepare the data to make them accessible to any statistical technique.
    - Perform a graphic examination of the nature of the individual variables to be analyzed and a numerical descriptive analysis that         allows quantifying some graphic aspects of the data.
    - Perform a graphic examination of the relationships between the analyzed variables and a numerical descriptive analysis that             quantifies the degree of interrelation between them.
    - Evaluate, if necessary, some basic assumptions underlying many statistical techniques, such as normality, linearity and                 homoscedasticity.
    - Identify possible atypical cases (outliers) and evaluate the potential impact they may have in subsequent statistical analyzes.
    - Evaluate, if necessary, the potential impact that missing data may have on the representativeness of the analyzed data.

***

+ Extraction, transformation and loading process(ETL): It is a data pipeline that is used to collect data from various sources, transform the data according to business rules and load it into a destination data store. Transformation work in ETL takes place in a specialized engine and often involves the use of temporary storage tables to temporarily retain data as they are transformed and eventually loaded into their destination.The data transformation that takes place often involves several operations such as filtering, sorting, aggregation, data merging, data cleaning, duplication and data validation.


   ![alt text](https://docs.microsoft.com/es-es/azure/architecture/data-guide/images/etl.png)
Frequently, the three phases of the ETL process run in parallel to save time. For example, while data is being extracted, a transformation process on the data already received and preparation for loading may be working, and a load process may begin to work on the prepared data, instead of having to wait for That ends the entire extraction process.

***

+ Statistical data analysis: They are basically of 2 types, continuous data and discrete data. The continuous information is the one that cannot be told. For example, the intensity of a light can be measured but cannot be counted. Discreet information is what can be told. For example, you can count the number of bulbs.
Continuous data in the analysis of statistical data is distributed under the function of continuous distribution, which can also be called the probability density function or fdp
The discrete data in the statistical data analysis is distributed under the discrete distribution function, which can also be called the probabilized mass function fmp.

***

+ Data flow diagram: Trace the flow of information for any process or system. It uses defined symbols, such as rectangles, circles and arrows, in addition to short text labels, to display data inputs and outputs, storage points and routes between each destination. The data flow diagrams can vary from simple process scenarios even hand-drawn, to very detailed DFD and with multiple levels that progressively deepen how the data is handled.
  
  - Example:

     ![alt text](https://image.slidesharecdn.com/dfdprofyedra-160313133606/95/diagrama-de-flujo-de-datos-dfd-16-638.jpg?cb=1457877018)
 
 


