We selected the Etihad Cargo green coding challenge as our Natural_Language_Processing Mid-Term_Project because of the challenge and complexity it provided. 
The objective of the Etihad Green Coding Challenge is to create a SMART Parser Application capable of efficiently processing Cargo EDI Messages in a specific
format. The application should be able to detect and record any errors encountered during message processing. It should also have the capability to automatically correct common errors found in the messages and skip complex errors or incorrect data elements. Additionally, the project aims to provide a user-friendly dashboard for viewing parsed data and monitoring messages with errors.

To fulfill the objective using regular expressions, the application can employ the following steps:

1. Message Parsing: Regular expressions can be used to define patterns for extracting specific data elements from the Cargo EDI Messages. By identifying the      required format and structure, regular expressions can efficiently locate and extract the relevant information.

2. Error Detection and Logging: Regular expressions can be utilized to identify errors or inconsistencies in the message data. By defining patterns for 
   expected values or data formats, the application can flag any deviations or mismatches encountered during parsing. Detected errors can be logged for further    analysis or resolution.

3. Error Correction: Regular expressions can be employed to automatically correct common errors encountered in the message data. By defining patterns for the 
   expected correct format, the application can search for erroneous patterns and apply appropriate corrections, improving the data quality and accuracy.

4. Error Handling: Regular expressions can help identify complex errors or incorrect data elements in the message data. By defining patterns for these complex    errors, the application can determine when to skip certain data elements or handle them separately based on predefined rules or conditions.

5. Dashboard and Monitoring: Regular expressions can also assist in analyzing and monitoring the parsed data. By defining patterns for specific data elements 
   or error conditions, the application can generate visualizations or alerts on a dashboard, allowing users to track and monitor messages with errors 
   effectively.

![image_description](etihad_challenge.png)
