
## High level test plan
| Test ID	| Description|	Expected Input|	Expected Output|	Actual Output|	Type Of Test|
|-----| ---------------| -----------| -----------| -------------| ----------|
| H_01|	Check if the user selects an option from the available choices, if not from choice, given it will break|	Integers from menu|	Should display message asking user to select from given values|	Exact message configured as per the case|	Requirement based|
| H_02|	Check if the user selects an option from the available choices, and if yes they it will continue the case|	Integer from menu	Redirect to corresponding view|	Redirecting to corresponding view	|Requirement based|
|H_03|	User enters valid credentials during login|	Username and Password of the user|	If success, user will be redirected to the internal menu with different functions to perform|	User is getting redirected to the correct menu where all actions that can be performed are displayed|	Technical|
|H_04|	User enters Invalid credentials during login|	Username and Password of the user|	If invalid credentials are provided, process breaks and user will be forced to exit.|	SUCCESS	|Technical|
## Low level test plan
|Test ID|	Description|	Expected Input|	Expected Output|	Actual Output|	Type Of Test|
|---------| ------------| ----------| ------------| ------------| ------------|
| L_01|	Logout should be successful and redirect to login page again|	User integer input|	Redirection to Login page|	Page got redirected to Login page|	Scenario based|

## Best methods to be followed:

Best Methods Followed
Exact Mapping of code to avoid confusions
Mentioning of both High level and Low level Behavioral and structural diagrams for better understanding
Followed the exact symbols to make the understanding easier
Detailed explanation in Low level Behavioural and Structural Diagrams
