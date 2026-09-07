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

## COMMAND AND OUTPUT
<img width="712" height="457" alt="Screenshot 2026-09-07 090241" src="https://github.com/user-attachments/assets/3ab0f3e4-1936-4087-9d2c-80e8d8b3b950" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="802" height="387" alt="Screenshot 2026-09-07 090249" src="https://github.com/user-attachments/assets/c8eec7f2-8d4e-48cf-9e1e-30a2f119e7bf" />


Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="818" height="532" alt="Screenshot 2026-09-07 090321" src="https://github.com/user-attachments/assets/6cc1b9d6-235a-485f-9ecb-92ac4efb60e3" />

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="920" height="487" alt="Screenshot 2026-09-07 090329" src="https://github.com/user-attachments/assets/7ac560a7-7d02-47ce-8ff1-132d74bacda3" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="747" height="145" alt="Screenshot 2026-09-07 090358" src="https://github.com/user-attachments/assets/d284e398-4d2e-45e8-9353-d11343f786d9" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="878" height="383" alt="Screenshot 2026-09-07 090425" src="https://github.com/user-attachments/assets/a78e6737-db79-4459-9ef1-00a42d2b4eef" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="832" height="478" alt="Screenshot 2026-09-07 090436" src="https://github.com/user-attachments/assets/b3dedafb-6593-41cf-bfa0-d9a4f784c838" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="726" height="377" alt="Screenshot 2026-09-07 090749" src="https://github.com/user-attachments/assets/786428ed-c2b1-4a3c-854f-19598d9c0ef1" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

<img width="805" height="175" alt="Screenshot 2026-09-07 091017" src="https://github.com/user-attachments/assets/3aed8a89-0f69-4a31-951a-aeada85a55ab" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="488" height="113" alt="Screenshot 2026-09-07 091827" src="https://github.com/user-attachments/assets/760eb489-461a-4634-ae45-d73ca516f564" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="700" height="252" alt="Screenshot 2026-09-07 092130" src="https://github.com/user-attachments/assets/06c4aac9-a82f-4c34-bde8-8a14f0e0315f" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="572" height="291" alt="Screenshot 2026-09-07 092304" src="https://github.com/user-attachments/assets/3b669d7b-1083-4935-8a47-61b5b17e1e3c" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="437" height="143" alt="Screenshot 2026-09-07 092742" src="https://github.com/user-attachments/assets/4526fb5d-e804-485b-9bc0-80bb2b5266fd" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="523" height="291" alt="Screenshot 2026-09-07 102301" src="https://github.com/user-attachments/assets/415bb4da-5b45-46d0-b43d-2389570c728c" />
<img width="568" height="320" alt="Screenshot 2026-09-07 102313" src="https://github.com/user-attachments/assets/1b78454c-7e59-4a00-8d1e-b544c398b403" />
<img width="448" height="325" alt="Screenshot 2026-09-07 102327" src="https://github.com/user-attachments/assets/e25dcac7-c8d4-45a6-83c0-3a6b0199aa1f" />



# RESULT:
The commands/batch files are executed successfully.

