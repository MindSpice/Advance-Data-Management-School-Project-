# Advance-Data-Management-School-Project-

Your business question must rely on the aggregation of data. In this assessment, the summary data will be automatically created from the detailed data.

 

Plan for and compose the sections of a real-world business report that can be created from the DVD Database on Labs on Demand (see link below), and demonstrate the functionality of the supporting SQL code by doing the following:

 

A.   Summarize one real-world business report that can be created from the attached Data Sets and Associated Dictionaries. 

1.  Describe the data used for the report.

2.  Identify two or more specific tables from the given dataset that will provide the data necessary for the detailed and the summary sections of the report.

3.  Identify the specific fields that will be included in the detailed and the summary sections of the report. 

4.  Identify one field in the detailed section that will require a custom transformation and explain why it should be transformed. For example, you might translate a field with a value of ‘N’ to ‘No’ and ‘Y’ to ‘Yes’.

5.  Explain the different business uses of the detailed and the summary sections of the report.

6.  Explain how frequently your report should be refreshed to remain relevant to stakeholders.

 

B.   Write a SQL code that creates the tables to hold your report sections. 

 

C.   Write a SQL query that will extract the raw data needed for the Detailed section of your report from the source database and verify the data’s accuracy.

 

D.   Write code for function(s) that perform the transformation(s) you identified in part A4.

 

E.   Write a SQL code that creates a trigger on the detailed table of the report that will continually update the summary table as data is added to the detailed table.

 

F.   Create a stored procedure that can be used to refresh the data in both your detailed and summary tables. The procedure should clear the contents of the detailed and summary tables and perform the ETL load process from part C and include comments that identify how often the stored procedure should be executed.

1.  Explain how the stored procedure can be run on a schedule to ensure data freshness.
