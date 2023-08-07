# Keylogger Executable
Keyloggers are software programs that record keystrokes made on a computer, which can be useful for monitoring user activity or detecting malicious behavior. This tool is designed to run locally on a user's computer, and it will store keystrokes made at regular intervals of one minute.


To make this Python file executable, follow the below steps:

1.	Open Terminal in the directory where the ‘keylogger.py’ file is.
2.	Now write the below command to make the executable for the ‘keylogger.py’ file:

    pyinstaller --noconsole --onefile keylogger.py


Two directories will be created as named 'build' and 'dist'.

1.	Open the 'dist' directory, where 'keylogger.exe' file is present.
2.	Now keylogger executable will be running in the background, you can check by opening ‘Task Manager’.
3.	After every 1 minute, a log file will be created in the same directory as of the ‘keylogger.exe’


*Make sure to install ‘pyinstaller’ library before executing the above command.
