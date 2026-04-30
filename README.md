# HTTP Log Analysis Using Splunk SIEM

## Introduction
HTTP (Hypertext Transfer Protocol) log files store information about web server activity such as user requests, responses, status codes, and user agents. This project demonstrates how to upload and analyze HTTP logs using Splunk SIEM to monitor web traffic and detect potential security issues.

---

## Project Objective
- Understand HTTP log structure  
- Upload log data into Splunk  
- Analyze web traffic patterns  
- Detect errors and suspicious activities  

---

## Tools and Technologies
- Splunk SIEM  
- HTTP Log Files (.log / .txt)  
- Web Browser  

---

## Prerequisites
- Splunk installed and running  
- Sample HTTP log files available  
- Basic knowledge of Splunk interface  ## Project Workflow
-
---
### 1. Preparation of HTTP Log Files
- Collect HTTP log files in `.log` or `.txt` format  
- Ensure logs contain:
  - Timestamp  
  - Request method (GET, POST)  
  - URL  
  - Status code  
  - User agent  

---

### 2. Access Splunk Interface
- Open the Splunk web interface  
- Navigate to the **“Add Data”** section  

---

### 3. Upload Log Data
- Select the upload option  
- Choose the prepared log file  
- Configure source type (e.g., `access_combined`)  
- Submit the data for indexing  

---

### 4. Verify Data Upload
- Run a basic search query  
- Ensure HTTP log events are visible in Splunk  

---

### 5. Extract and Organize Fields
- Identify important fields such as:
  - Method  
  - URL  
  - Status  
  - IP address  
- Use field extraction techniques if required  

---

### 6. Analyze Web Traffic Patterns
- Study request methods (GET, POST)  
- Identify frequently accessed URLs  
- Analyze response status codes  

---

### 7. Detect Errors and Anomalies
- Identify error responses (status ≥ 400)  
- Monitor unusual traffic patterns  
- Detect suspicious IP activities  

---

### 8. Monitor User Behavior
- Analyze login attempts and failures  
- Study user access patterns and sessions  

---

### 9. Interpret Results
- Summarize findings from log analysis  
- Identify potential security issues  

---

### 10. Conclusion and Reporting
- Document observations and results  
- Suggest improvements for better monitoring and security  

---
## Conclusion

This project demonstrates how HTTP log files can be analyzed using Splunk SIEM to monitor web activity.  
It helps in understanding user behavior, request patterns, and server responses.  
The analysis enables detection of errors such as failed requests and abnormal status codes.  
It also supports identification of suspicious IP activity and unusual traffic patterns.  
Overall, the project improves system monitoring and strengthens security analysis.  
Thus, Splunk proves to be an effective tool for log management and threat detection.
