# Challenge
Bug and Automation challenge.

***UI Bugs***<br />
**Title:** <br />
Add Employee - Required warning message are not displayed when the user leaves the inputs in blank<br />
Description: Required warning message are not displayed when the user leaves the inputs like First Name, Last NAme and Dependets in blank and the user click on the 'Add? button on the modal<br />
Environment:<br />
URl: https://wmxrwq14uc.execute-api.us-east-1.amazonaws.com/Prod/Benefits<br />
Username: TestUser722<br />
Password: $8(;65PWFXvH<br />
Broswser: Chrome<br />
Steps to Reproduce:<br />
1. Log In using the username and password describe on the enviroment section<br />
2. On the Paylocity Benefits Dashboard click on the 'Add Employee' button<br />
3. The 'Add Employee' modal will be displayed on this modal do not enter any details and click on the 'Add' button<br />
   Actual result: The modal remains displayed with no warning or description about the issue<br />
   Expected result: The input field should display a visual help if any data is missing to enter from the user<br />
Visual help:<br />
<img width="726" alt="Screenshot 2025-01-31 at 7 36 47 p m" src="https://github.com/user-attachments/assets/ab1e0420-3353-4263-a13c-7bfd1f9139dd" /><br />
<br />
<br />
**Title:** <br />
The table is not displaying the names in the alphabetical order<br />
Description: The details for the employees are displayed in random orderbr />
Environment:<br />
URl: https://wmxrwq14uc.execute-api.us-east-1.amazonaws.com/Prod/Benefits<br />
Username: TestUser722<br />
Password: $8(;65PWFXvH<br />
Broswser: Chrome<br />
Steps to Reproduce:<br />
1. Log In using the username and password describe on the enviroment section<br />
2. On the Paylocity Benefits Dashboard click on the 'Add Employee' button<br />
3. The 'Add Employee' modal will displayed add employee details add the employee Alonso Fernando with 3 dependents and click on the 'Add' button<br />
4. On the 'Paylocity Benefits Dasboard' click on the 'Add Employee' button and repeat the step t3 but with a diferent name like Bearman Oliver 0 dependents<br />
5. Repeat the step 4 but with the employee details Lewis Hamilton 1 dependent<br />
6. Repeat the step 4 but with the employee details Charles Lecrerc with 1 dependent<br />
Actual result: The employee names will start displaying in randmon order as soon as you complete adding the employee details <br />
Expected result: The employee names are displayed in alphabetical order<br />
Visual help:<br />
<img width="1175" alt="Screenshot 2025-01-31 at 7 45 41 p m" src="https://github.com/user-attachments/assets/da0facbc-a712-47ee-bbb4-2cbd64668025" />




API Bugs
