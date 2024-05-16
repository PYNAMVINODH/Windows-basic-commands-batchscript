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

## Developed by : PYNAM VINODH
## Reg No.      : 212223240131

## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.

## COMMAND AND OUTPUT
```
Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
mkdir %userprofile%\Desktop\MyLab
```
![image](https://github.com/PYNAMVINODH/Windows-basic-commands-batchscript/assets/145742678/32151f74-4b93-444a-b4b0-5cda5faeabb8)



## COMMAND AND OUTPUT
```
List the contents of the "MyLab" directory.
cd %userprofile%\Desktop\MyLab
```

![image](https://github.com/PYNAMVINODH/Windows-basic-commands-batchscript/assets/145742678/6f0f7be2-f123-4d3e-a8a0-cfff28d385e8)


![image](https://github.com/PYNAMVINODH/Windows-basic-commands-batchscript/assets/145742678/850be8a6-0a79-4896-95b4-f4fff38d4c96)


## COMMAND AND OUTPUT
```
Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
dir %userprofile%\Desktop\MyLab
```

![image](https://github.com/PYNAMVINODH/Windows-basic-commands-batchscript/assets/145742678/d5d47bd5-4c02-4779-b4b8-115f0d0de55b)



## COMMAND AND OUTPUT

```
Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup
mkdir %userprofile%\Desktop\Backup

```

![image](https://github.com/PYNAMVINODH/Windows-basic-commands-batchscript/assets/145742678/b1b6ea0a-f708-4778-997d-0762cdfd3496)


![image](https://github.com/PYNAMVINODH/Windows-basic-commands-batchscript/assets/145742678/e449e04d-f2d3-40ff-ba89-ec379eb1cf34)


## COMMAND AND OUTPUT

mv Myfile.txt %userprofile%\Documents

![image](https://github.com/PYNAMVINODH/Windows-basic-commands-batchscript/assets/145742678/88428e48-ea63-42e7-b335-519547513394)



## Exercise 2: Advanced Batch Scripting

```
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!

```

## OUTPUT

![image](https://github.com/PYNAMVINODH/Windows-basic-commands-batchscript/assets/145742678/d6dd8228-72e8-43d2-89f9-b88ec31d957f)



# RESULT:

The commands/batch files are executed successfully.
