# open_multiple_terminals
This code is created in order to be able to automatically open multiple terminals in VSCode with specific commands executed at startup. 
Steps to follow to properly insert the code: 
1. Open the command line in VSCode (Ctrl/Cmd + Shift + P).
2. Type Tasks: Configure Task.
3. Choose "Create tasks.json file from template".
4. Choose "Others".
5. Modify "tasks.json" (tasks are variable. The example of the code is in this depository).
6. In command line, type "Debug: Open launch.json" and select it.
7. Choose "add configuration", select "Compound".
9. Create and modify "launch.json" (like in the depository).
10. Install "Auto Run Tasks".
11. Modify "settings.json" (like in the depository).
12. Tasks will run automatically in separate terminals once you start VSCode.
