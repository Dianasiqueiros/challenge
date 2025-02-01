# Challenge
Bug and Automation challenge.

***UI Bugs***<br />
<br />
**Title:** <br />
Add Employee Modal - Required warning message are not displayed when the user leaves the inputs in blank<br />
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
<br />
Title:<br />
The table is not displaying the names in the alphabetical order<br />
Description: The details for the employees are displayed in random order<br />
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
<br/>
<br/>
<br />
Title:<br />
Add Employee Modal -  Numbers are allow in the input fields First Name and Last Name
Description: Numbers are allow in the input fields First Name and Last Name on the 'Add Employee' modal <br />
Environment:<br />
URl: https://wmxrwq14uc.execute-api.us-east-1.amazonaws.com/Prod/Benefits<br />
Username: TestUser722<br />
Password: $8(;65PWFXvH<br />
Broswser: Chrome<br />
Steps to Reproduce:<br />
1. Log In using the username and password describe on the enviroment section<br />
2. On the Paylocity Benefits Dashboard click on the 'Add Employee' button<br />
3. The 'Add Employee' modal type a random numbers like '245' on the First Name field
4. The 'Add Employee' modal type a random numbers like '4654' on the Last Name field
5. On the 'Add Employee' modal type 0 on the Dependdents field and click on the 'Add' button
Actual result: The employee names with a numbers on the First Name and Last Name are displayed on the table
<br />
Expected result: The First Name and Last Name should displayed and error message if we want t0 enter numbers<br />
Visual help:<br />
<img width="837" alt="Screenshot 2025-01-31 at 8 13 51 p m" src="https://github.com/user-attachments/assets/f7c32d40-ba16-48ee-9a6d-5481f7c24dfe" />
<br/>
<br/>
<br />
Title:<br />
Add Employee Modal - Special characters are allow in the input fields First Name and Last Name
Description: Special character are allow in the input fields First Name and Last Name on the 'Add Employee' modal <br />
Environment:<br />
URl: https://wmxrwq14uc.execute-api.us-east-1.amazonaws.com/Prod/Benefits<br />
Username: TestUser722<br />
Password: $8(;65PWFXvH<br />
Broswser: Chrome<br />
Steps to Reproduce:<br />
1. Log In using the username and password describe on the enviroment section<br />
2. On the Paylocity Benefits Dashboard click on the 'Add Employee' button<br />
3. The 'Add Employee' modal type a special characters  like 'Checo!#$' on the First Name field
4. The 'Add Employee' modal type a special characters like 'Perez9"%&3ai' on the Last Name field
5. On the 'Add Employee' modal type 4 on the Dependdents field and click on the 'Add' button

Actual result: The employee names with special characters on the First Name and Last Name are displayed on the table<br />
Expected result: The First Name and Last Name should displayed and error message if we want t0 enter special characters <br />
Visual help:<br />
<img width="832" alt="Screenshot 2025-01-31 at 8 16 57 p m" src="https://github.com/user-attachments/assets/4a595a90-64d6-4cff-849e-1797c75fa580" />


API Bugs
