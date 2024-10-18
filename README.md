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

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
~~~
%userprofile%\Desktop\MyLab 
~~~

![image](https://github.com/user-attachments/assets/55332a56-115e-41a6-b57d-cd369783f108)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
~~~
%userprofile%\Desktop\MyLab
~~~

![image](https://github.com/user-attachments/assets/ab8015f1-6e39-41d0-a118-e82603dfabfe)

![image](https://github.com/user-attachments/assets/a74549a1-854d-4d13-a6bb-9ff349205d68)

## COMMAND AND OUTPUT
Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
~~~
 %userprofile%\Desktop\MyLab
~~~

![image](https://github.com/user-attachments/assets/3e7ebcb1-68b3-4d66-807e-323f391f7be9)

## COMMAND AND OUTPUT
Move the "MyLab" directory to the "Documents" folder.
~~~
mkdir %userprofile%\Desktop\Backup
mkdir %userprofile%\Desktop\Backup 
~~~

![image](https://github.com/user-attachments/assets/4de1dc4a-8ae0-465d-9f4a-e410feaaed4f)

![image](https://github.com/user-attachments/assets/c0c82376-45ac-42cd-a567-287b60e61fa4)

## COMMAND AND OUTPUT
~~~
mv Myfile.txt %userprofile%\Documents
~~~

![image](https://github.com/user-attachments/assets/e69eaa91-2de3-4b0d-abb7-5f67915d8d5e)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
~~~
@echo off mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
~~~
## OUTPUT

![image](https://github.com/user-attachments/assets/de859a6e-09b6-4807-be4a-65d8afa63e63)

# RESULT:
The commands/batch files are executed successfully.

