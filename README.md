# AutomationAnywhereV11
Project preview using AA V11

# SCENARIO 1 :
In this first use case, you are expected to develop a Bot using Automation Anywhere Enterprise to automate a process and business rules outlined below. Submit the files as per the Instructions given in the Certification portal.

Download Employee.xml and Employee.xlsx file from the Additional References tab in the Master Certification course of the LMS portal.

# Process Use Case
Open the Employee.xml file.
•	The XML contains Employee Information for all the employees in an organization.
•	Every month the eligibility of employees for gratuity should be reviewed using the XML file.
•	The eligible candidate list should be extracted in the given Employee.xlsx file format

# Business Rules/Conditions to Automate the Process
The Bot you develop is expected to do the following:
1.	The Bot needs to open the XML file.  
2.	In the XML, the Bot needs to read data row by row and do the check for gratuity eligibility for all the employee.
3.	The organization checks gratuity eligibility of their employees based on the given criteria:
    a.	Number of years in the organization >= 5
    b.	Overall performance rating >= 5
    c.	City should be NY
    d.	State should be New York.
4.	All the data must be entered in the Employee.xlsx file
5.	The Bot should read the Excel row by row and send an email notification to each employee with the following details:
    a.	Years of Service in the Organization
    b.	Rating
    c.	Eligibility for gratuity
    d.	Rename the Employee.xlsx file to “YourEmailID_Bot_1_Output.xlsx”
    
# SCENARIO 2 :    
In Second use case, it is expected to develop a Bot using Automation Anywhere Enterprise to automate a process and business rules outlined below. Submit the files as per the Instructions given in the Certification portal.
Note: Download Data.xlsx and Macro Sheet.xlsx file from the Additional References tab in the Master Certification course of the LMS portal.

# Process Use Case
1.	Open the Data.xlsx file.
    o	The file contains data for payment mode, bank, and RRN.
2.	Open the Macro Sheet.xlsx file.
    o	This file contains macro names for the Data file.
3.	Develop a Bot to capture the right macro names and update the Data file.

# Business Rules/Conditions to Automate the Process
The Bot you develop is expected to do the following:
•	The Bot needs to open the Data file.
•	In the Data file, the Bot needs to read payment mode, bank name, and RRN number row by row.
•	The Bot needs to check for all the given data in the Macro Sheet file.
  o	If payment mode, bank name, and RRN number is a (Match) (Valid) then pick up the macro name and dump it into the Data file in Column      E.
  o	If the bank name is SBI, Corporation Bank, HDFC, or ICICI then consider bank name in Macro Sheet as – (Hyphen)
 
# SCENARIO 3 :
In Third use case, you are expected to develop a Bot using Automation Anywhere Enterprise to automate a process and business rules outlined below. Submit the files as per the Instructions given in the Certification portal.
 
# Process Use Case
1.	Open the web page: http://rpademo.automationanywhere.com/master-pdf.php
2.	Use the given credential.
    a.	 Username: candidate
    b.	Password: LetMeIn123!
3.	Download all the PDF and invoice_template.xlsx file from the web page.
4.	Extract the data from the PDF and enter them in the downloaded Excel file.

# Business Rules/Conditions to Automate the Process
The Bot you develop is expected to do the following:
1.	Extract the data from the downloaded PDF based on the following condition:
    a.	Quantity should be greater than or equal to 2.
    b.	Unit price should be greater than or equal to 2.
    c.	Line total should be greater than or Equal to 100.
    d.	Due date should be greater than 01-April-2019.
    e.	Payment term should be due on receipt.
2.	Enter the extracted data in the invoice_template.xlsx.
3.	Rename the invoice_template.xlsx file to “YourEmailID_Bot_3_Output.xlsx”

# END OF README 
