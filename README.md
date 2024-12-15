# Data-Quality-Control

Data Quality Control Initiative Report for ABC Enterprises

# Project Overview
ABC Enterprises' Data Quality Control (DQC) program aims to provide a strong structure that assures the organization's data is accurate, comprehensive, consistent, and reliable. This effort will address data quality issues such as errors, duplicate records, and inconsistent formats, all of which have a detrimental influence on decision-making and company performance.


# Objective
The primary purpose of this project is to develop strategies for enhancing data quality across major datasets that impact business operations. This will allow for improved decision-making, operational efficiency, and regulatory compliance.

# Background
As ABC Enterprises grows, it has met more data quality concerns, such as inconsistent and incomplete data. These issues can result in inaccurate business decisions, operational inefficiencies, and compliance hazards. These concerns can be minimised by implementing effective data quality controls, resulting in more accurate data-driven decisions.


# Key Areas of Focus

Data Profiling: Evaluate current datasets' completeness, accuracy, and consistency.

Data Cleansing: Create procedures for removing duplicates, correcting errors, and standardising data.

Data Validation: Create rules to ensure that only correct and legitimate data is entered into the system.

Monitoring and reporting: Use tools and dashboards to track data quality indicators and detect problems early.

Training and Awareness: Give employees the essential training on data quality best practices.

# Methodology

Assess the present state by reviewing existing data sources and procedures to understand the current difficulties and identifying the datasets that have the most impact on company operations.

Data Profiling: Use tools to evaluate data accuracy, uniqueness, and consistency. The findings will help guide the areas that require immediate attention.

Data Cleansing: Create processes to clean data, such as deleting duplicates and standardising formats. Missing values will be treated with relevant ways.

Data Validation: Set rules for new data entry to ensure consistency and accuracy from the start.

Monitoring: Create systems to regularly monitor data quality, ensuring that KPIs are met and issuing notifications for abnormalities.

Training: Develop training materials and hold seminars to ensure that staff understand the value of data quality.

Missing Values:
 Name       0
Email      0
Phone      0
Age        0
Address    0
Country    0
dtype: int64

Data Types:
 Name       object
Email      object
Phone      object
Age         int64
Address    object
Country    object
dtype: object

Basic Statistics:
                Age
count  1000.000000
mean     42.999000
std      14.688456
min      18.000000
25%      31.000000
50%      42.000000
75%      56.000000
max      69.000000

Duplicates:
 0

 Missing Values:
 Name       0
Email      0
Phone      0
Age        0
Address    0
Country    0
dtype: int64

Data Types:
 Name       object
Email      object
Phone      object
Age         int64
Address    object
Country    object
dtype: object

Basic Statistics:
                Age
count  1000.000000
mean     42.999000
std      14.688456
min      18.000000
25%      31.000000
50%      42.000000
75%      56.000000
max      69.000000

Duplicates:
 0

 ![image](https://github.com/user-attachments/assets/916f4b79-5e9e-4583-87f0-b629e676f6fe)


 Name                    Email                 Phone  Age  \
0        Lori Page       lisa96@example.net       +1-491-852-5797   63   
1      James Huynh        dwang@example.com         (718)917-3497   68   
2  Michael Griffin  anthonyward@example.org   (995)465-8858x24408   31   
3   Kenneth Howell    daycarmen@example.net   (381)833-6467x73861   33   
4  Joshua Morrison       bill45@example.net  +1-693-622-0175x9486   64   

                                             Address   Country  
0         70287 Taylor Shores\nMeadowsfort, WY 52535      Cuba  
1  719 Michael Fall Apt. 358\nSouth Patrickberg, ...  Honduras  
2      3171 Ryan Estates\nLake Williemouth, MT 19820     Yemen  
3  786 Tracy Passage Apt. 447\nEast Courtney, AL ...   Jamaica  
4                         USNS Cabrera\nFPO AA 58887      Cuba  

Data Profiling:
Missing Values:
 Name       0
Email      0
Phone      0
Age        0
Address    0
Country    0
dtype: int64

Data Types:
 Name       object
Email      object
Phone      object
Age         int64
Address    object
Country    object
dtype: object

Basic Statistics:
                Age
count  1000.000000
mean     44.381000
std      14.790761
min      18.000000
25%      32.000000
50%      44.000000
75%      57.000000
max      69.000000

Duplicates:
 0

Cleaned Data Profiling:
Missing Values:
 Name       0
Email      0
Phone      0
Age        0
Address    0
Country    0
dtype: int64

Data Types:
 Name       object
Email      object
Phone      object
Age         int64
Address    object
Country    object
dtype: object

Basic Statistics:
                Age
count  1000.000000
mean     44.381000
std      14.790761
min      18.000000
25%      32.000000
50%      44.000000
75%      57.000000
max      69.000000

Duplicates:
 0

Validation Results:
                  Phone  Phone_Valid  Age  Age_Valid
0       +1-491-852-5797         True   63       True
1         (718)917-3497         True   68       True
2   (995)465-8858x24408         True   31       True
3   (381)833-6467x73861         True   33       True
4  +1-693-622-0175x9486         True   64       True

Valid Phone Numbers: 100.00%
Valid Ages: 100.00%


![image](https://github.com/user-attachments/assets/5e5cd10b-2a82-458f-bfae-713bb66ac78e)

![image](https://github.com/user-attachments/assets/8441dd30-9968-463f-8a71-41ab907c50f9)



# Tools and Technologies.

- For data profiling and purification, the project will use products such as Informatica Data Quality, Talend, and Trifacta. Tableau or Power BI can be used to visualise data quality metrics in real time. In addition, data validation and purification operations will be automated using Python or SQL.

# Deliverables

- Data Quality Control Plan: A document that outlines the methods, measurements, and responsibilities for maintaining data quality.

- Measures and KPIs: A report that outlines the important data quality measures being tracked.

- Cleaned datasets are data that have been cleansed and validated and has become suitable for analysis and reporting. Training Resources: Educational materials to help personnel maintain data quality. Monitoring 

- Dashboard: A dashboard that monitors data quality in real time.

# Timeline

Estimated the project is expected to be finished in 8 weeks, which will include an assessment of current procedures, the installation of data quality measures, staff training, and the setup of monitoring systems.

# Conclusion

I think ABC Enterprises will improve its data quality by applying certain data quality control methods, resulting in better informed decision-making, increased operational efficiency, and lower risk of noncompliance.




