# comp_sys_Assignment01

BusinessDetails Layout:  
When adding a business to the BusinessDetails file, I wrap each column in square brackets []
The reason I did this is so I can have search options where the user chooses to search by a specific column in the file,
such as search by Company Name or search by Contact Name rather than just search the entire line for a match. I didn't use a space or comma seperator as spaces are not suitable given that the words are seperated by spaces, and I did not use comma's as it is likely that when a person enters an address they will comma seperate the lines and columns are not fixed width so I thought this to be an ideal way of identifying each column. 
Given that square brackets [] are special characters I have had to work around them in different ways and remove the brackets for certains functions eg. when sending an email. 



Pass shell variable as a /pattern/ to awk  
https://unix.stackexchange.com/questions/120788/pass-shell-variable-as-a-pattern-to-awk

Remove characters from grep output   
https://stackoverflow.com/questions/12668020/removing-characters-from-grep-output

Ignore Square brackets in a string  
https://alvinalexander.com/source-code/grep-ignore-special-characters-pattern-in-string-solution

Save output of a command in a variable  
https://stackoverflow.com/questions/2559076/how-do-i-redirect-output-to-a-variable-in-shell

AWK to lower case  
https://stackoverflow.com/questions/5228892/ignorecase-in-awk


Menu:  
A user has the option to Add a Business, Remove a Business, Find a Business, Send an email or Quit. 
Depending on the option selected, there are further options available to the user. 

Add A Business:  
The user will be asked to add a value for each column - Comapny Name, Contact Name, Address, Phone Number and email Address. 

Find a Business:  
When the user selects this option a sub menu will appear which will allow the user to search by each column in the file or to return to the main menu. 

Remove a Business:    
When the user selects the option  to remove a business they will be presented with a submenu again, they can remove a business based on company name or based on contact name or they can choose to return to the main menu. When the user enters either the company name or the contact name, the full business entry will be returned on screen to the user and the user will be asked to verify if this is the business they wish to remove. 

Send an Email:    
If the user chooses to send an email they will be presented with 3 options, email an individual business, email all businesses or return to the main menu. 
If the user chooses to email an individual business, they will be asked to enter the company name that they wish to email. The business details will be shown on screen and the email address for that business will be retreived. The user is then asked to provide the subject and email body. 


Other References:   
Loop Counter increment:  
https://stackoverflow.com/questions/10515964/counter-increment-in-bash-loop-not-working

Concatenate Strings:  
https://linuxize.com/post/bash-concatenate-strings/

Use Variable for line number SED:   
https://www.unix.com/unix-for-dummies-questions-and-answers/37340-use-variable-sed-print-line.html

Check if Variable is NULL:  
https://www.cyberciti.biz/faq/unix-linux-bash-script-check-if-variable-is-empty/
