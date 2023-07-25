# Python-Scripts
Scripts That Make your Life Easy

# How to automate Scripts

### Step 1: Prepare the Script
- Before setting up the Task Scheduler, ensure that you have your custom Python script ready and tested. Make sure the script works as expected when run manually.
### Step 2: Open Task Scheduler
- Press the 'Windows key + R' to open the Run dialog box.
- Type 'taskschd.msc' and press 'Enter' or click 'OK'. This will open the Task Scheduler.
### Step 3: Create a New Task
- In the Task Scheduler window, click on 'Create Task...' from the right-hand side panel. This will open the Create Basic Task Wizard.

  ![image](https://github.com/Amgtps/Python-Scripts/assets/140238361/b66c5dd7-6673-449f-a66d-901504622aee)

### Step 4: Name and Description 
- Provide a name and an optional description for your task. Click 'Next'.
### Step 5: Trigger
- Choose how often you want the task to run. Select one of the options (e.g., Daily, Weekly, etc.) and click 'Next'.
- Set the start date and time for the task. Click 'Next'.

### Step 6: Action
- Select Start a program and click Next.
### Step 7: Program/script and Add arguments 
-  In the "Program/script" field, enter the path to the Python executable (e.g., C:\Python39\python.exe) or Open CMD and type 'where python' and copy the first path
-  In the "Add arguments" field, enter the full path to your Python script (e.g., C:\path\to\your\script.py).
- Click 'Next'.
### Step 8: Finish
- Review the task's settings. If everything looks correct, click Finish.

