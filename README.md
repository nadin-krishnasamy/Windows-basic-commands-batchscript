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
```
mkdir my-folder
```
<img width="426" height="46" alt="Screenshot 2026-05-25 095157" src="https://github.com/user-attachments/assets/c79dd931-9402-49a0-96c1-2534dde03092" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
```
rmdir my-folder
```
<img width="339" height="44" alt="Screenshot 2026-05-25 095211" src="https://github.com/user-attachments/assets/eae28661-6091-42b9-81a2-ea244ae2484b" />


Create the file Rose.txt
## COMMAND AND OUTPUT
```
COPY CON Rose.txt
A clock in a office can never get stolen
Too many employees watch it all the time
^Z
1 file(s) copied
dir Rose.txt
```
<img width="557" height="347" alt="Screenshot 2026-05-25 095517" src="https://github.com/user-attachments/assets/5bce19d3-1673-4b6d-a864-fc458cd117b1" />



Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
```
echo “hello world” > hello.txt
type hello.txt
```
<img width="481" height="89" alt="Screenshot 2026-05-25 095806" src="https://github.com/user-attachments/assets/8424ee8d-700e-4a7b-83e9-3d15187c4fd5" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
```
copy hello.txt hello1.txt
type hello1.txt
```
<img width="383" height="108" alt="image" src="https://github.com/user-attachments/assets/309ce429-f3ea-4eee-a2b3-41839c09d305" />


Remove the file hello1.txt
## COMMAND AND OUTPUT
```
del hello1.txt
```
<img width="318" height="34" alt="image" src="https://github.com/user-attachments/assets/cba288c1-82d9-413d-8426-d6c1a1aeb09b" />


List out the file hello1.txt in the current directory
## COMMAND AND OUTPUT
```
dir hello1.txt
```
<img width="352" height="122" alt="image" src="https://github.com/user-attachments/assets/a70e724b-7c1f-4ef5-90e2-a79571b91fef" />

List out all the associated file extensions 
## COMMAND AND OUTPUT
```
assoc | more
```
<img width="479" height="468" alt="image" src="https://github.com/user-attachments/assets/d75ca488-9d42-4618-8bd4-4724d5d89d7c" />


Compare the file hello.txt and rose.txt
## COMMAND AND OUTPUT
```
fc hello.txt Rose.txt
```
<img width="453" height="187" alt="image" src="https://github.com/user-attachments/assets/68fc3d57-c2b8-4826-8276-7aa1a0bcf7ec" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".



## OUTPUT
<img width="349" height="92" alt="image" src="https://github.com/user-attachments/assets/be8c163a-9ed8-447f-b802-1b2997fd660f" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="476" height="255" alt="image" src="https://github.com/user-attachments/assets/6babf782-731b-41fa-8199-0fcff36d680a" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="437" height="167" alt="image" src="https://github.com/user-attachments/assets/00cda8e8-888b-4e27-8dc0-3ed33f49803f" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="475" height="209" alt="image" src="https://github.com/user-attachments/assets/d92edd9c-06b6-49b1-ba08-ffdaf0f0eaed" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="353" height="356" alt="image" src="https://github.com/user-attachments/assets/55b58a6c-a7f9-43ad-9618-8a6bebe44f0f" />



# RESULT:
The commands/batch files are executed successfully.

