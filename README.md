# P.I-WORKS

Qestion 5: Please prepare the user interface specification document in English for the user management screen below (Markdown syntax preferred). It should include the requirements, details related to UI components, the behavior of the page when using these components, what to show to the user at the beginning, etc. This document will be used by Software developers who will develop this user interface. Please push the result in one of GitHub, GitLab, or BitBucket repositories (any of them is fine) and share the accessible link.

1. Overview
This interface is build up for administrators to manage an ddeal with the user accounts fastly. They have to create new users, edit user informations and also delete (disable) the user account
2. Layout of Screen
Our screen divided two parts
User Management: This part of screen allows administrators to create and edit the users.
User List: This part of this screen shows the list of all user exist in our  system. Administrators can view the details of users also edit and they can be delete (disable) the user
3. User Management Part
New User: We need a button that for creating new user account.
Hide Disabled Users: We have a checkbox for hides disables users from our user list.
Save User: We also have a save user button for saving when we change and update user informations.
4. Create User Form
Username: A text field exist for the administrators enter fill this area with usernames.
Email: A text field exist for the administrators enter fill this area with Email of the users. 
Enabled: We have a checkbox to enable new users account.
User Roles: Dropdown menu for the administrators to select the users roles for the new users account.
5. User List Part
This part shows a list of our all existing users in the system. It must to enter the following informations for every users that are exist:
Username
Email Address
Enabled status ( a checked box for enabled users)
Edit: This button allows administrators to edit the our existing users.
Disable: This button disables user account for out system.
6. User Details Section (It shows up while editing users)
Username: Text field for display the username fot our users it should be read only.
Display Name: There must be a text field for where the administrators can enter a display names for our users.
Phone: Textfield for administrators enter users phone numbers.
Email: Textfield for our administrators can update and enter a e-mails
User Roles: There must be a dropdown menu for administrators can select the users role from here.
Enabled: There must be an checkbox to enable our users.
7. Throwing Error 
The system should display appropriate error messages if any of the following conditions occur: 
The username field is left empty.
The email address field is left empty.
An invalid email address is empty.
