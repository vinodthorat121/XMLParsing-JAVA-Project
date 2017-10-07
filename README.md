# XMLParsing-JAVA-Project
Parse XML : XML provides the ability to represent hierarchical structures with its parent-child relationships. This enables applications to store structured data in XML for export. Importing this XML data into a database is a bit involved as we shall see in this article. You need to write code to manage the database connection. In addition, you need to parse the XML and isolate the data that needs to be imported.

We are attempting to import data from employee.xml
Load ORACLE JDBC Driver
Connect to ORACLE Database
Create Table using create command
Parse XML
With the database setup code out of the way, let us look into importing the XML data into the application
To insert the data, we need to obtain the required data from the XML nodes.
Prepare XML Data.
Insert into table
This project covered the details of importing XML into a ORACLE database. We parsed the XML using the SAX parser. Then we used XPath to extract just the data we needed. Finally, we inserted it into the database using JDBC.

we have successfully imported data from an XML file into a ORACLE database.
