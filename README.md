# Forensica-Windows: Automated Windows Artifact Analysis Tool  

[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/) [![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME/blob/main/CONTRIBUTING.md)  

Forensica-Windows is a Python-based **digital forensics** tool designed to automate **Windows artifact analysis** and **Windows Event Log analysis**. It empowers **incident responders**, **forensic investigators**, and **security analysts** to rapidly identify and investigate potential **security incidents**, **malware infections**, and **suspicious activities** on Windows systems. This tool helps streamline **incident response** by automating the tedious process of manually parsing through **Windows artifacts**.  

**Key Benefits:**  

*   **Automated Artifact Parsing:** Streamlines the analysis of critical **Windows artifacts**, saving valuable time and resources.  
*   **Comprehensive Event Log Analysis:**  Efficiently analyzes **Windows Event Logs** to identify security-relevant events and potential threats.  
*   **Rapid Incident Response:** Accelerates the **incident response** process by quickly identifying key indicators of compromise (IOCs).  
*   **User-Friendly Interface:** An intuitive GUI simplifies the **forensic analysis** workflow.  
*   **Integration with Data Collection Tools:** Seamlessly integrates with popular data collection tools like Velociraptor and KAPE.  

**Ready to get started?**

## Table of Contents  

*   [Key Features](#key-features)  
*   [User Interface](#user-interface)  
*   [Tool's Workflow](#tools-workflow)  
*   [Analysis Results](#analysis-results)   
*   [Feedback & Contributions](#feedback--contributions)  
*   [License](#license)

## Key Features  

*   **Windows Event Log Parsing:** Parses and analyzes **Windows Event Logs** for security-related events (e.g., logon attempts, process creation, system changes).  
*   **Artifact Extraction:** Extracts and analyzes various **Windows artifacts**, including:  
    *   Registry files (SYSTEM, SOFTWARE, NTUSER.DAT)  
    *   Prefetch files  
    *   Shortcuts (.lnk files)  
    *   $Recycle.Bin   
*   **Report Generation:** Creates comprehensive and customizable HTML reports summarizing the analysis results.  
*   **Support Velociraptor and KAPE:** Supports analysis of data collected using Velociraptor and KAPE.  

## User Interface  

The user interface is designed for ease of use and efficient **Windows forensic analysis**.  

![Forensica-Windows User Interface](https://github.com/user-attachments/assets/9ac27409-3b98-4910-bfd8-3860c18438cd)  

1.  **Case Name:** Assign a descriptive name to your analysis case. This is crucial for **case management** and organizing your **digital forensics** investigations.  
2.  **Directory Option:** Select the directory to analyze. This should be either the root directory (`C:\`) or the output folder from a data collection tool like Velociraptor or KAPE (containing `Users`, `Windows`, `$RecycleBin`, etc. folders).  Ensuring the correct directory is selected is vital for proper **artifact parsing**.  
3.  **Start Analysis Button:** Initiates the analysis process, triggering the parsing of **Windows artifacts** and **Event Logs**.  
4.  **Recent Cases:** Displays a list of recently analyzed cases with timestamps, allowing you to quickly access previous **forensic investigations**.  
5.  **Open Case Button:** Opens a previously saved case for review and further analysis.  
6.  **Theme Button:** Toggles between Light and Dark modes for improved user experience.  
7.  **View Report Button:** Appears after analysis completion, allowing you to view the generated report.  
8.  **Analysis Details:** Displays detailed information about the analysis process and extracted artifacts.  

## Tool's Workflow  

Follow these steps to analyze a Windows system using Forensica-Windows:  

1.  **Data Acquisition:** Collect data from the target Windows system using a data collection tool like Velociraptor or KAPE, or directly from the `C:\` drive.  
2.  **Input Configuration:** Provide a descriptive Case Name and select the appropriate directory (either `C:\` or the output folder from the data collection tool).  
    ![Directory Structure Example](https://github.com/user-attachments/assets/c58ae91e-c0d4-480a-81f8-f0d519cc6f48)  
3.  **Start Analysis:** Click the "Start Analysis" button to begin the analysis process.  The tool will parse **Windows Event Logs** and other specified **Windows artifacts**.  
4.  **Review Report:** After the analysis is complete, click the "View Report" button to access the detailed HTML report containing the analysis results.  

## Analysis Results  

The analysis results are presented in a comprehensive HTML report. This report provides detailed information about extracted artifacts, identified security events, and potential indicators of compromise.  

![Analysis Report Snippet 1](https://github.com/user-attachments/assets/83fd45a8-1091-48ff-91c4-542b3374b475)  
![Analysis Report Snippet 2](https://github.com/user-attachments/assets/1f516530-dd31-4d27-a613-cf37c02cf053)  
![Analysis Report Snippet 3](https://github.com/user-attachments/assets/d4181fc7-ab40-4721-a29d-eb921e414d12)  

## Feedback & Contributions  

We welcome your feedback and contributions to help improve Forensica-Windows! Please feel free to submit bug reports, feature requests, and pull requests.  

Wanted to Connect: Here is our LinkedIn Profile: https://www.linkedin.com/company/secureblue-academy

## License  

Forensica-Windows is an open-source, free to use for anyone.

Happy Forensics!
