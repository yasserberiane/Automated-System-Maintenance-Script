# Automated-System-Maintenance-Script
This PowerShell script makes Windows maintenance easy! It handles updates, runs antivirus scans, stops useless processes, cleans temp files, and fixes system issues automatically. Perfect for keeping your PC running smooth without lifting a finger.
# Automated System Maintenance Script (PowerShell)

## Description  
This PowerShell script automates essential Windows maintenance tasks to improve system performance, security, and reliability. It handles Windows updates, schedules antivirus scans, terminates unnecessary processes, cleans temporary files and caches, and repairs system files using built-in tools.

## Features  
- **Windows Update Automation**: Automatically searches, downloads, and installs critical updates.  
- **Scheduled Antivirus Scans**: Runs full scans using Windows Defender without user intervention.  
- **Process and Service Management**: Stops non-essential processes/services to free resources.  
- **Disk Cleanup**: Removes temporary files, DNS cache, Windows Update cache, and prefetch data.  
- **System Repair**: Uses SFC and DISM to check and fix corrupted system files.  
- **Power Plan Optimization**: Activates Ultimate Performance power plan to maximize efficiency.  
- **Progress Feedback**: Displays progress bars and detailed messages during execution.  
- **Error Handling**: Logs errors and handles exceptions to ensure smooth operation.

## Requirements  
- Windows 10 or later  
- PowerShell 5.1 or higher  
- Administrator privileges to run system-level commands  
- Windows Defender enabled for antivirus scans  

## Usage  
1. Clone or download this repository.  
2. Open PowerShell with administrator rights.  
3. Navigate to the script directory.  
4. Run the script with:  
   ```powershell
   .\maintenance-script.ps1
