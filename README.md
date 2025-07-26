# Nginx Log Analyzer

This is a simple shell script to analyze an Nginx access log file from the command line.

It extracts the following statistics from the log:

- Top 5 IP addresses with the most requests
- Top 5 most requested paths
- Top 5 response status codes
- Top 5 user agents

## 🛠 Requirements

- Bash shell
- Standard Unix tools: `awk`, `sort`, `uniq`, `head`, `wget`

## 📥 Download the Sample Log File

Run this command in your terminal to download the sample log file:

```bash
wget -O access.log https://gist.githubusercontent.com/kamranahmedse/e66c3b9ea89a1a030d3b739eeeef22d0/raw/77fb3ac837a73c4f0206e78a236d885590b7ae35/nginx-access.log
