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
# Create a directory named "my-folder"

## COMMAND AND OUTPUT
```
mkdir my-folder
```
<img width="401" height="46" alt="image" src="https://github.com/user-attachments/assets/af9af8b5-cc4f-4747-a799-ddfd0a6b955d" />


# Remove the directory "my-folder"

## COMMAND AND OUTPUT
```
rmdir my-folder
```
<img width="483" height="62" alt="image" src="https://github.com/user-attachments/assets/7e899c73-2ada-4c76-b554-bfeef0a1e948" />



# Create the file Rose.txt

## COMMAND AND OUTPUT
```
type nul > Rose.txt
```
<img width="436" height="43" alt="image" src="https://github.com/user-attachments/assets/16f03acb-5a80-4d14-9001-17eb332d3dc2" />


# Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
```
echo Hello World! > hello.txt
```
<img width="576" height="57" alt="image" src="https://github.com/user-attachments/assets/8a48f9e4-ac38-4ff9-9221-596b29f1bfcd" />


# Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
```
copy hello.txt hello1.txt
```
<img width="570" height="70" alt="image" src="https://github.com/user-attachments/assets/3778db36-626d-43b7-a6cf-773119435c0a" />

# Remove the file hello1.txt

## COMMAND AND OUTPUT
```
del hello1.txt
```
<img width="445" height="227" alt="image" src="https://github.com/user-attachments/assets/8e1b270f-789f-46d8-a333-ff3f740cdd4b" />


# List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
```
dir hello1.txt
```
<img width="445" height="227" alt="image" src="https://github.com/user-attachments/assets/8e1b270f-789f-46d8-a333-ff3f740cdd4b" />

# List out all the associated file extensions 

## COMMAND AND OUTPUT
```
assoc
```
<img width="403" height="202" alt="image" src="https://github.com/user-attachments/assets/dd46f128-938b-4b3a-ac7a-38fdfae7eccd" />


# Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
```
fc hello.txt Rose.txt
```
<img width="471" height="162" alt="image" src="https://github.com/user-attachments/assets/870671e1-2e35-43ae-809c-9a95a49f2be3" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="490" height="91" alt="image" src="https://github.com/user-attachments/assets/89f92b97-c632-4114-9dd3-7e63fdefd0c5" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="658" height="98" alt="image" src="https://github.com/user-attachments/assets/3f80146b-b8b5-4c22-80f9-936ee432d5aa" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="458" height="167" alt="image" src="https://github.com/user-attachments/assets/15f863b8-fb80-4e3a-a2cd-51c234733e06" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="464" height="82" alt="image" src="https://github.com/user-attachments/assets/6c0b2a38-36d5-49b2-a585-867677c5d059" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="640" height="242" alt="image" src="https://github.com/user-attachments/assets/90db5d38-e6dc-471f-91cf-da3c4730c350" />



# RESULT:
The commands/batch files are executed successfully.

