# keylogger-executable
Keyloggers are software programs that record keystrokes made on a computer, which can be useful for monitoring user activity or detecting malicious behavior. This tool is designed to run locally on a user's computer, and it will store keystrokes made at regular intervals of one minute.


To make this Python file executable, follow the below steps:

1.	Open Terminal in the directory where the ‘keylogger.py’ file is.
2.	Now write the below command to make the executable for the ‘keylogger.py’ file:

    pyinstaller --noconsole --onefile keylogger.py


*Make sure to install ‘pyinstaller’ library before executing the above command.
