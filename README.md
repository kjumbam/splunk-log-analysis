# splunk-log-analysis
How to analyze logs using Splunk
# Splunk Log Search & Analysis Project

PROJECT OVERVIEW

This project demonstrates how to upload log data into **Splunk Enterprise**, perform basic searches, and identify patterns or errors in the data.  
The objective was to find entries containing the keyword **"error"** and analyze them.

TOOLS USED
- **Splunk Enterprise** (Free version)
- Sample Apache log file (downloaded from a public dataset)

STEPS TAKEN
1. Installed Splunk Enterprise from [https://www.splunk.com/en_us/download/splunk-enterprise.html](https://www.splunk.com/en_us/download/splunk-enterprise.html).
2. Started Splunk service and logged into `http://localhost:8000`.
3. Downloaded sample Apache log data from:  
   [Apache Logs Dataset](https://raw.githubusercontent.com/elastic/examples/master/Common%20Data%20Formats/apache_logs/apache_logs)
4. Uploaded the file to Splunk:
   - **Settings → Add Data → Upload**
   - Selected the file and indexed it under `testlogs`.
5. Navigated to **Search & Reporting**.
6. Ran the search:"index=testlogs error" to find all log entries containing the word "error".

FINDINGS
- **Total error enteries found**: 202

SCREENSHOTS

<img width="1680" height="1038" alt="number pf errors" src="https://github.com/user-attachments/assets/c2721c68-51da-4f3b-ad47-01fbc7f283b1" />


WHAT I LEARNED
- How to ingest log data into Splunk.
- How to search for total number of error enteries.

