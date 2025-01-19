# File_Integrity_Checker_CodTech
Name : Rohith Allada
Company : CODTECH IT SOLUTIONS PVT.LTD
ID : CT08JPM
Domain : Cyber Security & Ethical Hacking
Duration: January To 05 Febuary 2025
Mentor : 
Overview
The File Integrity Checker is a Python tool designed to monitor and verify the integrity of files using hash functions. It allows users to detect file modifications, maintain a history of changes, and ensure data consistency.

Features
Multiple Hash Algorithms: Supports MD5, SHA1, and SHA256.
Modification Detection: Compares stored and current file hashes to identify changes.
History Tracking: Maintains a detailed history of file modifications, including timestamps and previous hash values.
Interactive CLI: User-friendly command-line interface with ASCII art logo.
JSON Storage: Saves file hashes and history in a JSON file for persistent monitoring.
Installation
Clone the repository:

git clone https://github.com/hipremsoni/CODETECH_ADVANCE_TASK_1.git
cd CODETECH_ADVANCE_TASK_1
Install dependencies:

pip install -r requirements.txt
Run the tool :

Python3 file_integrity_checker.py
Usage
Run the program:

python3 file_integrity_checker.py
Enter file paths: Provide one or multiple file paths to monitor, separated by commas.

// Example For Windows Path 
C:\\Example\\file.txt
//Exaple For Linux Path 
/home/kali/file.txt

Select a hash algorithm: Choose one of the supported algorithms (MD5, SHA1, SHA256).

Monitor for changes: The tool checks file integrity, stores hashes, and updates the history in hashes.json.

View history: Optionally, display the modification history for any file.
![WhatsApp Image 2025-01-19 at 19 24 20_5b8f179c](https://github.com/user-attachments/assets/e09778d9-57b3-4287-90db-470eb47e163e)

