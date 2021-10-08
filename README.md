Capstone-Project-3

Task Manager

Project Details:

Description

The Task Manager Project is a program written in the Python language that was created to fulfill the level 1 task requirements for the Hyperion Development Software Engineering Bootcamp. The program was designed to assist a small business in managing tasks assigned to each member of a team. This includes creating, storing, displaying and editing tasks and related information to and from text files.

Functionality

•	When reading the code, the viewer will see functions that have been written to perform certain actions based on options that users will choose from a displayed menu. These 'functions' are basically blocks of code that take in certain information (e.g. a menu choice) and then output various results based on the actions defined in the function.

•	After the main functions, lists and dictionary variables (as used in the Python language) are set to store user and task information within the program. For now, each external text file ('user.txt' and 'tasks.txt') is opened and the existing information is stored in the appropriate lists and dictionaries in the Python program.

•	Thereafter, the main program is executed which involves allowing the user to login with their username and password details. The program checks whether their details are correct by ensuring that their 'username' and 'password' entered match the corresponding information in the appropriate 'usernames' and 'passwords' lists. If either input (i.e. username or password) is entered incorrectly, appropriate error messages are displayed.

•	Once the user has entered their details correctly, a successful login message is displayed and a menu with the options to register users, add tasks, view all tasks, view tasks assigned to the user specifically, generate reports, or exit the program. The 'admin' user gets an extra option in their specific menu which allows them to 'display statistics'. This option is not available on the menu for other users. There are certain letters displayed with each menu choice that the user can type in to select an option from the menu (e.g. to register a user, they can type in 'r').

•	The menu is displayed for users within a 'while' loop and this is done so that after each menu option chosen, the user will return to the main menu, which allows them to make another menu choice if they wish to or to exit the program. For the options in the menu, the associated functions are called when the user types in the related letter corresponding to that menu choice. 

•	The menu is displayed for users within a 'while' loop and this is done so that after each menu option chosen, the user will return to the main menu, which allows them to make another menu choice if they wish to or to exit the program. For the options in the menu, the associated functions are called when the user types in the related letter corresponding to that menu choice. For example, if they type in 'r' to register a user, the relevant function listed is executed. This function prompts the user for input information relating to the new user they want to register, for example they are asked to enter a new username, and then new password. Once the new user information is correct (and doesn't already exist; if they try to register an existing user, an error message is displayed) it is stored in the corresponding 'usernames' and 'passwords' lists within the program. The information is then also written to the appropriate external 'user.txt' text file. A similar process is followed if the user chooses 'a' to add a task from the main menu, except that they are then prompted to enter information related to the task with a series of questions (e.g. "Please enter the task description.") and this information is first added to the appropriate 'tasks' dictionary and then written from the dictionary to the external 'tasks.txt' text file.

•	For the third option in the menu, 'va' to view all tasks, the user is not prompted to enter any information however all of the tasks stored in the external 'tasks.txt' file are displayed to the user. 
  If they choose the fourth menu option, 'vm' to view tasks assigned to them, only the tasks assigned to their username are numbered and displayed from the 'tasks.txt' file 
  
  •	If the user chooses the fifth option from their main menu, 'gr' to generate reports, this generates two external text files, namely, the 'task_overview.txt' and the 'user_overview.txt'. These text files store information relating to statistics of tasks and user information. 
  
  •	The 'admin' user can then select 'ds' from their menu options to view the reports that have been generated in the previous menu option. 
