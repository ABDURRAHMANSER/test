# UI SPEC FOR USER MANAGMENT SCREEN
* The page should contains the following: A form to entre the new user infos with a button in right corner of it with the text 'Save User' and a table to show all users that have been created, with a button with text 'New User' in the up left corner of it. A filter with text 'Hide Disabled user' next to the 'New User' button.
* The table and the form should be side to side, where the table is on the left and the form is on the right.
* The form should contains the following fields: username, displayname, phone, email, user role (Guest/Admin/Superadmin), 'enabled radio' button.
* The users table should contains the following columns: ID column, Username column, Email column and enabled status column.
* After the user entre the new user info in the form and the press the 'Save User' button, a message saying 'New user has been successfully created' or 'Failed while creating the user' should be shown.
    * If the user has been successfully created, it should be shown in the users table.
    * If the 'Hide Disabled user' filter is on, only enable users should be shown.
     
