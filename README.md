### **GAR Specialist (Human Capital)**

##### 

##### **These are the steps that have been followed to complete the case study:**





###### 1\. Preparing the data in MS Excel

&nbsp;	1.1 The .xlsx file provided, titled, "Case Study - HCGAR Specialist (3)" was duplicated to preserve original data.

&nbsp;	1.2 I only kept the sheets titled "Legend", "Candidate Details" and "Recruiting Activity" to keep the working document clean.

&nbsp;	1.3 The sheets were formatted as tables for better clarity.

&nbsp;	1.4 The column data types were updated to their appropriate formats.

&nbsp;	1.5 A pivot table on an intermediate sheet was used to quickly transpose the "Recruiting Activity" sheet. The new sheet was named "Recruiting Activity New".

&nbsp;		1.5.1 Avg, Median, Mode, Minimum and Maximum of "Days to Offer", "Count of Candidates" and "Count of Offers Sent" were calculated in the intermediate sheet using live formulas.

&nbsp;		1.5.2 In this "Recruiting Activity New" sheet, we calculated the "Days to Offer" and the number of days between subsequent rounds.

&nbsp;	1.6 The data was properly inspected and no duplicates, spelling errors, etc were encountered.





###### 2\. ETL using Power Query

&nbsp;	2.1 "Candidate Details" and "Recruiting Activity New" sheets were loaded into Power Query Editor.

&nbsp;	2.2 A merged sheet aliased "details\_all" was created using the two sheets using a "Full Outer Join" on the "Candidate ID" column.

&nbsp;		2.2.1 Only the required columns were kept in "details\_all".

&nbsp;	2.3 "Offer" column was created to account for offer rollout.

&nbsp;	2.4 A new table called "Recruitment Order" was created to ensure consistency on sequence of rounds and a relationship was established with the "details\_all" table.





###### 3\. Dashboard creation (Using visuals like charts, matrix, cards and slicers)



###### 

###### 4\. "Executive Summary" was prepared to be shared with Cameron and all the senior leaders.



###### 

###### 5\. "Email to Cameron" was drafted. 



&nbsp;	

&nbsp;	

