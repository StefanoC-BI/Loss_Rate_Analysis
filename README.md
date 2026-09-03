# Loss_Rate_Analysis
Excel to collect datas during production workflows and BI to visualize and analyze loss rate.
This file is a sample.
I worked in a department where operators weren't tracking production defects because the Excel sheet was cumbersome, creating significant friction between data collection and production speed. To streamline their workflow, I built a new Excel file that highlights the required fields and uses basic formulas (IF, XLOOKUP, UNIQUE) to automatically populate the product master data.
This file has:
Data Entry sheet "CMZ_Data_Entry", where the operator tracks defects
Data_Source: The dataset populated with masterdata
Worker_Name+Machine: Name of the operators and machines in use.
Temporary_Data_Source: it's a life saver. If the operator finds a new product or a one shot that is still not uploaded in the Data_Source, he can type down those datas and later can be updated.
