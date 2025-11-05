# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations

Create a directory named "my-folder"

<img width="388" height="88" alt="Screenshot 2025-11-05 101615" src="https://github.com/user-attachments/assets/d77a0330-d716-4c4f-8d89-09be3435a31d" />

## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="385" height="72" alt="Screenshot 2025-11-05 101630" src="https://github.com/user-attachments/assets/f5b8efb2-5377-4c63-bd5e-00773887d55b" />

## COMMAND AND OUTPUT

Create the file Rose.txt

<img width="795" height="399" alt="Screenshot 2025-11-05 102710" src="https://github.com/user-attachments/assets/7927885b-c6a0-4efc-b4aa-223e64dc6f7d" />

## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection

<img width="556" height="151" alt="image" src="https://github.com/user-attachments/assets/7932a6b6-dff3-47b2-93a0-cc8799b12a5e" />

## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="508" height="59" alt="image" src="https://github.com/user-attachments/assets/01f6a8bd-d86d-48b8-a820-a7278bc09cab" />

## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="379" height="71" alt="image" src="https://github.com/user-attachments/assets/50319705-d04a-4f45-8f9b-57660b793aa2" />

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

<img width="594" height="266" alt="image" src="https://github.com/user-attachments/assets/5d7e7a0a-5eb7-452b-aa92-92f1675e1119" />

## COMMAND AND OUTPUT

List out all the associated file extensions 

<img width="562" height="471" alt="image" src="https://github.com/user-attachments/assets/392fcf7c-0630-4ded-bb3b-438f03394aa5" />

## COMMAND AND OUTPUT

Compare the file hello.txt and rose.txt

<img width="924" height="211" alt="image" src="https://github.com/user-attachments/assets/11e9c124-8f1c-44e3-aeb2-e134de578f5c" />

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

## OUTPUT

<img width="551" height="156" alt="image" src="https://github.com/user-attachments/assets/dce72f75-d26e-4371-85cd-fcbfc67951c5" />

Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.

## OUTPUT

<img width="600" height="211" alt="image" src="https://github.com/user-attachments/assets/1a647c34-9ceb-48b0-aa73-1bbe696a6074" />

Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

## OUTPUT

<img width="539" height="206" alt="image" src="https://github.com/user-attachments/assets/e0f80c23-306f-410b-b193-5807c838e7b6" />

Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="491" height="145" alt="image" src="https://github.com/user-attachments/assets/a1ec2bea-36db-4cee-9719-f0547837e17f" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.

## OUTPUT

<img width="500" height="215" alt="image" src="https://github.com/user-attachments/assets/ceaa2c13-af85-424f-8a37-628f362d72b7" />

# RESULT:
The commands/batch files are executed successfully.

