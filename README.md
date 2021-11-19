# CSE201_Group-8
This is our project for CSE 201. 

# Team Credits 
TAJI Inc.
Founded 2021 
Members
  Jenn Pham: Project Manager
  Allison McWilliams: Technical Manager  
  Isabel Pulte: Developer (50% Documentation)
  Tanmay Bhatkar: Developer (50% Coding)

# Requirement lists: 
1. The software shall be accessible through a GUI.
2. The software shall allow users to view all the applications.
3. The software shall be able to sort all the applications.
4. The software shall allow users to filter all applications in the repository.
5. The software shall have a consistent search bar on every page.
  a. The search shall do a string search.
  b. The search shall sort based on all the applications’ respective fields.
6. The software shall allow users to be able to add applications to the repository by submitting a request form.
  a. The software shall allow adding by using an external link approved by admin.
  b. The software shall have adding requests on standby until approved.
7. The software shall allow admins to have access to a request page with all app submits requests.
  a. The software shall allow admins to respond to requests.
  b. The software shall allow admins to take action with the requests. 
8. The software shall allow moderators to moderate a comment section for each app.
9. The software shall require all users to login in in order to post on the forum.
10. The software shall have the backend of the repository and user login information persisted.

# Instructions:
1. Download the ZIP file and open it using your IDE of choice.
2. There should be 3 folders (src, accounts, and icons) and 2 lone files ("Application Information - Sheet1 (1).csv" and "README.md")
3. Open src and run the main file GUI.java.
4. You're at the home page with all the application available.
5. Try the search function on the left side: Make sure the search is Case Sensitive.
6. Try login or create a new account using the login/create account button.
	a. You must specify which type of user you want to be.
	b. Case-sensitive
	c. Here is a list of existing accounts for you to sign in: 
		i. User: (Name: user; Password: password).
		ii. Administrator: (Name: admin; Password: password).
		iii. Moderator: (Name: mod; Password: password).
7. Try sort the applications by alphabet using the sort button. Press UnSort to unsort the applications.
8. Try filter the applications using the filter bar above the page. Lots of options to choose from!
9. After logging in as a user: 
	a. Comment on an app using the "Comment Here!" button.
		i. Leads to a different frame. WARNING: DO NOT PRESS CLOSE, SIMPLE PRESS MINIMIZE TO EXIT BECAUSE IF PRESSED CLOSED IT WILL CLOSE THE WHOLE MAIN FRAME.
		ii. Choose an app to comment on. Leads to an app table.
		iii. You cannot delete any comment; for administrator and moderator only.
	b. Request a new app by clicking the "All Requests" button. Leads to an app request form.
	c. After refreshing the GUI, app will display without a picture, this will be modified by an administrator.
10. After logging in as an administrator: 
	a. Comment on an app using the "Comment Here!" button.
		i. Leads to a different frame. WARNING: DO NOT PRESS CLOSE, SIMPLE PRESS MINIMIZE TO EXIT BECAUSE IF PRESSED CLOSED IT WILL CLOSE THE WHOLE MAIN FRAME.
		ii. Choose an app to comment on. Leads to an app table.
		iii. Delete a comment by entering its number and press "Delete".
	b. Request a new app by clicking the "All Requests" button. Leads to an app request form.
	c. After refreshing the GUI, app will display without a picture, this will be modified by an administrator.
	d. Accept an app request by clicking approve (Will implement later!)
11. After loggin in as a moderator: 
	a. Comment on an app using the "Comment Here!" button.
		i. Leads to a different frame. WARNING: DO NOT PRESS CLOSE, SIMPLE PRESS MINIMIZE TO EXIT BECAUSE IF PRESSED CLOSED IT WILL CLOSE THE WHOLE MAIN FRAME.
		ii. Choose an app to comment on. Leads to an app table.
		iii. Delete a comment by entering its number and press "Delete".
	b. Request a new app by clicking the "All Requests" button. Leads to an app request form.
	c. After refreshing the GUI, app will display without a picture, this will be modified by an administrator.
12. At the main GUI, try clicking on each app to see its respective information. 
13. To exit the app, simply press close on the window.