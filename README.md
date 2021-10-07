# FinalINSTProj

My Final INST Python Project. 
Task is to write code to parse log file and generate automated reports.
The goal of this project is to analyze and parse a log file of information regarding numerous users.
Information such as these users' login date and time, email ID, etc. 
More specifically:
the first column is "Date and Time"
the second column is "User activity"
the third column is "Server"
the fourth column is "Email-ID"

The goal is to create 4 different reports from the parsed log file in order to analyze users' details.
The first report being: Suspicious activity (suspicious_report.txt) 
The suspicious activity report must include which users logged in more than 5 times in a day or in between the times of 12 AM-5 AM

The second report is: Irresponsible Behaviors (irresponsible_report.txt)
The irresponsible behaviors report must include which users have log-in numbers greater than their log-out numbers

The third report is: System Glitch (glitch_report.txt)
The system glitch report must include which users have log-outs greater than log-ins (opposite of irresponsible behaviors report)

The fourth report is: Domain Count (domain_count.txt)
The domain count report must include a list of all the unique domains and the number of users registered within each domain.

