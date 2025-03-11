# Log File Analysis System

# Project Development
The Log Analysis Script was developed to streamline the analysis of server log files, providing actionable insights into user behavior, endpoint activity, and potential security threats. The project focuses on automating the extraction, analysis, and reporting of key metrics, ensuring scalability and efficiency.

# Development Process
Identified the core functionalities: request counting by IP, detecting the most accessed endpoint, and flagging suspicious activities.
Defined output formats for both terminal display and CSV file generation for easy data sharing.

# Implementation:
Parsing Log Data: Developed a robust log parsing function to extract IP addresses, endpoints, HTTP methods, status codes, and timestamps.
Data Analysis:
Counted the number of requests per IP address and sorted them in descending order.
Identified the most frequently accessed endpoints based on log data.
Detected suspicious activity by flagging IPs with excessive failed login attempts (e.g., HTTP 401 errors).
CSV File Generation:
Saved results in a structured CSV file (log_analysis_results.csv) with separate sections for request counts, endpoint access frequencies, and suspicious activity.

# Testing and Optimization:
Tested the script with various log files, including small and large datasets, to ensure accuracy and performance.
Optimized parsing and analysis logic for scalability, ensuring minimal processing delays even with large logs.

# Tools and Technologies
Programming Language: Python.
Libraries Used:
collections.Counter for efficient data aggregation.
csv for structured data output.
Colab.
    

