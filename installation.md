# Loli_Checker 1.0

## **Introduction**
Loli_Checker 1.0 is a powerful tool designed to scan `.loli` configuration files for potentially **malicious** code. The tool provides comprehensive scanning of configuration files, alerting users about suspicious commands, and includes **VirusTotal** integration for additional security checks.

### **Key Features**
- **Comprehensive Pattern Detection**: Detect harmful commands and suspicious patterns that could compromise your system.
- **VirusTotal Integration**: Scan files using the **VirusTotal** API for a detailed safety report.
- **Real-Time Alerts**: Immediate alerts when suspicious or dangerous commands are detected in `.loli` files.

### **Installation Instructions**
To install and set up **Loli_Checker 1.0**, follow these simple steps:

1. **Clone the Repository:**
   Open your terminal or command prompt and run the following command to clone the repository:
   ```
   git clone https://github.com/your-username/Loli_Checker.git '''
2. **Navigate to the Project Directory**
   ```
   cd Loli_Checker '''
  3. **Install Required Dependencies**
Make sure you have Python 3.x installed. Then, install the necessary packages by running
```
  pip install -r requirements.txt
```
4. **Set Up the VirusTotal API Key**
You'll need a VirusTotal API key for scanning files. Obtain your API key from VirusTotal and set it as an environment variable
```
set VIRUSTOTAL_API_KEY=your_api_key_here
```

# Usage Instructions
After setting up the project, you can run the tool using the following command:
```
python config_checker.py
```
