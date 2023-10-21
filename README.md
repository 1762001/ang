Angular Assignment

	As per the below use case develop the angular application using angular material.

Application Configuration Details:
	Angular CLI: 	16
	Angular Material: 	latest version
	Material theme:	purple-green

	
Application Requirement Details:
	
Sign-In:
Landing page when application is starting.
Users should enter the Email and password.
When I click the Sign-In:
“Sign in” button should be enabled only when a  valid email address and password entered
Validate user credentials if wrong, show the error message.
Validate user credentials, if success, should land on the user list page.

SignUp:
SignUp option in the Sign-In page.
SignUp user details as below:
First Name (required), Last Name, DOB, Email (required), Password (required), Confirm Password (required),
Action: SignUp, Reset and Cancel.
When I click the SignUp: update the user details and navigate to the Sign-In page.
When I click the Reset: Should reset the SignUp form.
When I click the Cancel: Navigate to the Sign-In page. 

User list:
There are two types of view Card and List with Pagination.
Users are able to switch the Card and List view option. At the time only one view should be shown in the UI. 
There is an Option to SignOut.
When I click the SignOut: Should navigate to Sign-In page.
There is an option to add a user in the pop-up screen.
First Name (required), Last Name, DOB, Email (required), Password (required), Confirm Password (required),
There is Two options: Add or cancel.
When I click the Add: Add the user and close the pop-up.
When I click the cancel: Coles the pop-up.
User having the filter option to filter with name and email Match.
User list should be shown below user details in both views.
Name, Email, Date of birth (Date Month), user image, and Details option (clickable).
When I click Details I should navigate to the User details Page.


User Details:
Should be shown full user details. As below
First Name, Last Name, Email, DOB, User Image, Gender, Full Address.
Two option here Edit, Remove and Back:
When I click the Edit below fields should change as an Edit.
First Name (required), Last Name, DOB, User Image, Gender, Address.
When I click, the Edit option should show the update button. When I click the Update, The user details should Update.
When I click the remove Button, as Prompt and based on the Prompt response remove or ignore.
Once removed the User should navigate the User List Page.
Once clicked on the ignore stay back in the user details page.
When I click the back button I should navigate to the User List page.

Data Storage:
Storing the User details, you can use the Browser storage.
All functionalities like create, update, remove the data use the RxJS functionalities.
	
Example Page:

	
