# Name: SANJUSHRI A
# Register No:212223040187
# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT
![WhatsApp Image 2024-10-19 at 21 03 50_930d8a41](https://github.com/user-attachments/assets/04af23c9-8c9c-4b72-b3ad-53e25f7f63cf)


Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.


## COMMAND AND OUTPUT
![WhatsApp Image 2024-10-19 at 21 04 50_b94d4429](https://github.com/user-attachments/assets/2de17462-3202-42f4-bebb-65358cc1f022)


List the contents of the "MyLab" directory.


## COMMAND AND OUTPUT
![WhatsApp Image 2024-10-19 at 21 08 54_f90005ca](https://github.com/user-attachments/assets/d6d60ca5-e94b-44fd-aea1-37ba330c9195)

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

## COMMAND AND OUTPUT
![WhatsApp Image 2024-10-19 at 21 16 26_11951715](https://github.com/user-attachments/assets/bcabb224-9d97-4498-820c-63bd627f32cd)


Move the "MyLab" directory to the "Documents" folder.


## COMMAND AND OUTPUT
![WhatsApp Image 2024-10-19 at 21 16 48_97c06e8f](https://github.com/user-attachments/assets/e61f197b-24a4-4515-89af-e2de760476f2)



## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\DocBackup\*.docx
echo Backup and deletion completed successfully
```






## OUTPUT
![image](https://github.com/user-attachments/assets/901d3631-07e1-439b-8738-58b3c2d13530)








# RESULT:
The commands/batch files are executed successfully.
