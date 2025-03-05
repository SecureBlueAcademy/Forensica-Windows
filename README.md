# Forensica-Windows
A python based tool (works on Windows) for Windows Artifact Analysis.

Forensica-Windows is a python based tool capable of performing Windows Event Log analysis and parsing different important Windows Forensic Artifacts.

# User Interface
The user interface of the tool looks like this:
![image](https://github.com/user-attachments/assets/9ac27409-3b98-4910-bfd8-3860c18438cd)

1. Case Name: This option is for naming the output so you can get back to the results and not get confused.
2. Directory Option: This option is for selecting the directory. The directory should be either C:\ or the output folder (containing Users, Windows, $RecycleBin, etc folders) of any data collection tool like "Velociraptor or KAPE".
3. Start Analysis Button: This will start the analysis.
4. Recent Cases: This option will show the recent analysis you have done in the past with their timestamps.
5. Open Case Button: This will open the selected Case.
6. Theme Button: To switch between Light and Dark modes.
7. View Report Button: This will appear when the analysis is complete and can be used to view the anlaysis results.
8. This will show all the anlaysis details.

# Tool's Working
1. After providing a Case Name and appropriate directory, click Start Analysis button to start the analysis.
  - Make sure that the directory is either "C:\" or output (you have to provide the path to the folder containing the Users, Windows, $RecycleBin, etc folders) from Windows Data Collection Tool's like Velocriaptor or KAPE. 
![image](https://github.com/user-attachments/assets/c58ae91e-c0d4-480a-81f8-f0d519cc6f48)
2. After the analysis complete, click the View Report button to view the analysis results.
3. The results will look like this:
![image](https://github.com/user-attachments/assets/83fd45a8-1091-48ff-91c4-542b3374b475)
![image](https://github.com/user-attachments/assets/1f516530-dd31-4d27-a613-cf37c02cf053)
![image](https://github.com/user-attachments/assets/d4181fc7-ab40-4721-a29d-eb921e414d12)

# NOTE
These options will not show any results for now as these are collected by separate tool (I am working on that tool, will share that soon!)
![image](https://github.com/user-attachments/assets/f71de9ed-caa7-427d-9b93-de48763ddebb)

# Feedback
Feel free to share any feedback on the tool so I continue to enhance it.

Happy Forensics!






