# Loss_Rate_Analysis
Excel to collect datas during production workflows and BI to visualize and analyze loss rate.

This files are a sample.

I worked in a department where operators weren't tracking production defects because the Excel sheet was cumbersome, creating significant friction between data collection and production speed. To streamline their workflow, I built a new Excel file that highlights the required fields and uses basic formulas (IF, XLOOKUP, UNIQUE) to automatically populate the product master data.

This file has 4 sheets:

 - Data Entry sheet "CMZ_Data_Entry", where the operator tracks defects
 - Data_Source: The dataset populated with masterdata
 - Worker_Name+Machine: Name of the operators and machines in use.
 - Temporary_Data_Source: it's a life saver. If the operator finds a new product or a one shot that is still not uploaded in the Data_Source, he can type down those datas and later can be updated.

Before this file, operators weren't motivated to keep track of production rejects. With this file and the addition of a Power BI dashboard to display real-time results, operators showed genuine interest in the problem, significantly reducing friction


# UPDATE

The "2026_08_Datasheet_KO - UPDATED" contains new columns in Data_Source and CMZ_Data_Entry:

Data_Source : columns "Pieces"
 Every Code contains multiple pieces: that means that if the order quantity for Code H4 is, for example, 10, the total amount of pieces requested is 50. 

 CMZ_Data_Entry : Columns "Order Quantity" and "Total Produced"
  The operator must write down under Order Quantity the exact number that he reads in the order, and automatically the "Total Produced" column will be filled.

 This update streamlines the operator's workflow by eliminating the need to manually sum the processing quantities for each item code, as they simply copy the required order details.

 
