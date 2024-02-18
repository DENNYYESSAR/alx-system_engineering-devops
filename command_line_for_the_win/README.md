Command line for the win challenge

It is a pretty cool game challenging you on Bash skills. Everything is done via the command line and the questions are becoming increasingly complicated.

0. Complete the first 9 tasks.
File: 0-first_9_tasks.jpg,0-first_9_tasks.png

1. Complete the 9 next tasks, getting to 18 total.
File: 1-next_9_tasks.jpg,1-next_9_tasks.png

2. Complete the 9 next tasks, getting to 27 total.
File: 2-next_9_tasks.jpg,2-next_9_tasks.png



here's a demonstration of how to use the SFTP command-line tool to transfer a local screenshot to the sandbox environment:

1. First, take the screenshots of the completed levels as mentioned in the general requirements. Make sure you have the screenshots saved locally on your machine.

2. Open a Terminal or Command Prompt:
Open a terminal or command prompt on your local machine.

3. Connect to the Sandbox Environment:
Use the SFTP command-line tool to establish a connection to the sandbox environment. Replace "hostname" with the hostname provided to you, "username" with your sandbox username, and "password" with your sandbox password.
sftp username@hostname

4. Navigate to the Directory:
Once connected, navigate to the directory where you want to upload the screenshots. You can use the cd command to change directories.

5. Transfer the Screenshots:
Use the SFTP put command to upload the screenshots from your local machine to the sandbox environment. Replace "local_file_path" with the path to the screenshot file on your local machine.

Alternatively, you can also use the drag-and-drop method to upload files. Simply open two separate file explorers, one for your local machine and one for the sandbox environment, and drag the screenshot file from your local machine to the desired directory in the sandbox environment.

6. Confirm Transfer:
Once the transfer is complete, you can confirm that the screenshots have been successfully transferred by checking the sandbox directory. You can use commands like ls or dir to list the contents of the directory and verify that the screenshots are present.

7. Push Screenshots to GitHub:
After confirming the transfer, you can proceed to push the screenshots to GitHub as mentioned in the initial requirements.


