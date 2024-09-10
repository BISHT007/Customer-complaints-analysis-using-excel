# 🌲 Customer complaint analysis using excel 

## 📕 Table Of Contents
  - 🛠️ [Problem Statement](#problem-statement)
  - 📂 [Dataset](#dataset)
  - 🧙‍♂️ [Case Study Questions](#case-study-questions)

## 🛠️ Problem Statement
Dataset of the customers complaint with their state information is given. We have to clean the data and perform exploratory data analysis on the data. We have to suggest the inferences and derive various KPIs. At the end, An interactive dashboard have to be created for the convienet understanding of the analysis with the data driven insights. 

## 📂 Dataset

### **```Customer complaints table```**

<details>
--Complaint ID	
--Company	
--Product	
--Issue	
--State	
--Submitted via	
--Date received	
--Date resolved	
--Timely response?	
--Consumer disputed?	
--State_Name	
</details>

### **```State code name```**
--This is a JSON file containing state name and respective code
<details>

## 🧙‍♂️ Case Study Questions
<p align="center">
<img src="https://media3.giphy.com/media/JQXKbzdLTQJJKP176X/giphy.gif" width=80% height=80%>

### **Task 1**
  Working on data and combining the datasets																
	Data in the worksheet State_Code_Name is take from internet and is available in JSON format. Perform the following tasks 
  as part of data preparation																
	1. Create two new columns in the State_Code_Name worksheet and name them as STATE and CODE respectively.									
	2. From the JSON format, get the data (STATE and CODE) in tabular form using excel options / excel functions.						
	3. Create a new column in the worksheet Consumer_Complaints and name it State_Name																
	4. Fill the column State_name in the worksheet Consumer_Complaints with the data from the State_Code_Name worksheet																		
	Data Analysis:																
	5. What is the count of records for which the State Name values didn't showed up (records with #N/A) ?									
	6. Create a summary table to display number of complaints for only those State_Codes where State_Name is not mapped to State_Code in the worksheet Consumer_Complaints																
	7. Give your inferences for the possible reasons of non availabilty of the State_Name using the above steps.																							
### **Task 2**

Working on dates																
1. What is the resolution time (in days) after which the issue/complaint is resolved by the company?											
2. Create a new column YEAR using the date when complaint was received.																
3. Create a new column QTR (US FY) using the date when complaint was received. Column should have the quarter data based on US FY i.e. Q1 - JAN, FEB and MAR																
											
Notes:																
1. The dates are not stored as proper dates. In order to perform any operation on the dates, first you have to get the date columns as date.																
2. Read the dates as mm/dd/yyyy or dd-mm-yyyy																
3. Perform the data cleaning step (to have proper dates) in the Consumer_Complaints worksheet																

### **Task 3**

Reporting - Create a report with following details for each Company Name ( Summarize the data at Company level )													
1. Company wise total number of complaints. Sort the data in desc order of number of complaints														
2.  What is the number and %age of complaints where the timely response was not shared?																
3. How many complaints were disputed. Also display the %age of number of complaints of the total complaints for each company.																
4.  Average delay in days for closure of the complaints.																
																
Notes:																
1. Add a new worksheet and name it Report_Task3 to create the above report and share your inference.											
2. Raw data is available at the Complaint level (one record per complaint); the report should be created at the Company level (one record per company)																

### **Task 4**
																
Task 4: Reporting - Create a report with following details.																
1. Top five companies with maximum number of complaints along with count of complaints																
2. Top five issues with maximum number of complaints along with count of complaints																
3. Monthly trends of the number of complaints in form of line / area chart																
																
Notes:																
1. Add a new worksheet and name it Report_Task4 to create the above report and share your inference.
   
### **Task 5**

Dashboard - Create a view with following details on the year level																
1. Get the following KPIs																
i. Total number of complaints registered in percentage with YoY change in the numbers?																
ii. Number of complaints for which timely response was given . What is the YoY change in the numbers?																
iii. Average resolution time for the complaints. What is the YoY change in the numbers?																
2. Proportion of the # of complaints by different products																
3. Proportion of the # of complaints by different channels which were used to file the complaint 																
4. There is a limited bandwidth to look in all the complaints / issues raised by customers. Display graphically which complaints should be taken on priority ?																
5. Monthly trend of the number of complaints in form of line / area chart 																
										
Notes:																
1. Add a new worksheet and name it Report_Task5 to create the above dashboard.																
2. Submit the case study by giving your key takeaways from the analysis done in task 5																
