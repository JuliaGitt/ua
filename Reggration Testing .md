# 2 Registration

## Scenario 2.1. Register Account functionality

**Test Case 2.1.1. Sign Up link**
**Path**

1.	go to the title screen
2.	click the Sign Up link

**Expected result:**
a pop-up "New user account" window should be displayed

**Test Case 2.1.2. New user account creation**
**Path**

1.	display "New user account" window,
2.	use the following input data:
      * username: smoketestuserr
      * password: smoke1234
      * email: testerphoenix@outlook.com
3. click the "Create Account" button

**Expected result**
The "New user account" window should close and no other window should open for at least 10 seconds.
Confirm email should be send to the register email address.

## Scenario 2.2. Login functionality

**Test Case 2.2.1. Validate sign in into the Application using valid credentials**
**Path**

1.	display „Sign in” window
2.	use the following input data into the required rows:
    * username: smoketestuserr
    * password: smoke1234
3.	click on "Sign in" button

**Expected result:** Signed in user should be taken to the main page “Task” and popup window is displayed the next notification: “You must create a focus area before you can add tasks”.

## Scenario 2.3. Validate the working of Logout functionality

**Test Case 2.3.1. Validate the working of Log out by selecting from “My Account” dropdown menu**
**Path**

1. Navigate to the “My Account” in the right corner of the header
2. Click on the icon “My Account”
3. Click on the “Log out” in the dropdown menu

**Expected result:** User should be taken to the Home page.

## Scenario 2.4. Validate the working of Forgot Password functionality

**Test Case 2.4.1. Validate user is able to reset the password**

**Path**

1.	Open the Application URL and navigate to Login Page
2.	Clink on the “Forgot Password?”
3.	Enter the email address of an existing account for which you have forgot the password, use the following input data:
4.	email: testerphoenix@outlook.com
5.	Click on “Reset Your Password” - The popup window should be displayed with the next notification: “An email with password reset instructions was sent to your address. Click the link in the email to complete the process and setup a new password. If you don't see the email in your inbox, check your spam folder.”
6.	Check the registered email address for which the password got reset testerphoenix@outlook.com 
7.	Open the email with the subject “Phoenix application reset password”.
8.	Click on the link named “here” inside that email – should redirect to the window “Enter your new password”.
9.	Fill in required rows: “Password”, “Password confirmation”.
10.	Click on the “Change Your Password”.

**Expected result:** User should be able to login with a new password.

## Scenario 2.5. Validate the working of checkbox "Remember me"

**Test Case 2.5.1. Validate user is able to have access from the same machine** 

**Path**

1.	display „Sign in” window
2. use the following input data into the required rows:
    * username: smoketestuserr
    * password: smoke1234
3. Click on the checkbox “Remember me”
4. Click on "Sign in" button

**Expected result:** User should have access from same machine to all its data after session expired or browser\tab is closed.

# 3	My Account

## Scenario 3.1. Validate the working of Edit Account

**Test Case 3.1.1. Validate user is able to Edit Account and Save Changes**

**Pre-conditions**

The user is signed into the App with the following credentials:
  * username: smoketestuserr
  * password: smoke1234

**Path**

1. Navigate to the “My Account” in the right corner of the header.
2. Click on the icon “My Account” in the dropdown menu.
3. Click on the “Edit Account” button.
4. Change information in the rows: “Username”, “Email”.
5. Click on the “Save Changes” button.

**Expected result:** The user’s data is successfully changed and saved.

## Scenario 3.2. Validate the working of Change Password

**Test case 3.2.1. Validate user is able to reset the password**

   **Pre-condition**
The user is signed into the App with the following credentials:
   * username: smoketestuserr
   * password: smoke1234

**Path:**

1. Navigate to the “My Account” in the right corner of the header.
2. Click on the icon “My Account” in the dropdown menu.
3. Click on the “Change Password” button.
4. Fill in required rows: “Password”, “Password confirmation”.
5. Click on the “Confirm” button.

**Expected result:** User should be able to login with a new password.

# Scenario 3.3. Validate the working of Delete Account

**Test Case 3.3.1. Validate user is able to Delete Account**

  **Pre-conditions**
The user is signed into the App with the following credentials:
    * username: smoketestuserr
    * password: smoke1234

**Path**

1. Navigate to the “My Account” in the right corner of the header.
2. Click on the icon “My Account” in the dropdown menu.
3. Click on the “Edit Account” button.
4. Click on the “Delete Account”.
5. The popup window “Delete Account” is appeared.
6. Type in the box “DELETE”.
7. Click on “Confirm” button.

**Expected result:** The notification “Account deleted” is appearing and a user is redirecting on the main page.

# 4 Tasks

## Scenario 4.1. Validate the working of add new task in the Today column

**Test Case 4.1.1.  Validate if user is able to add new task in the Today column**
  **Pre-conditions**
The user is signed into the App with the following credentials:
    * username: smoketestuserr
    * password: smoke1234

**Path**

1. Navigate to the URL: https://flow-ui-prod-dot-sage-surfer-341107.lm.r.appspot.com/
2. Click on the hamburger button in the left corner of the header.
3. Click on the “Tasks”.
4. Click on the “Add” icon (+) in the Today column.
5. Popup window “Task details” is appeared.
6. Fill in rows: “Name”, “Description”.
7. Click on “To Do” button.
8. Click on “Add” button.

**Expected result:** A task is added to the “Today” column.

**Scenario 4.2. Validate the working of delete a task in the Today column**

**Test Case 4.2.1. Validate if user is able to delete a task in the Today column**
  **Pre-conditions**
The user is signed into the App with the following credentials:
    * username: smoketestuserr
    * password: smoke1234

**Path**

1. Navigate to the URL: https://flow-ui-prod-dot-sage-surfer-341107.lm.r.appspot.com/
2. Click on the hamburger menu button in the left corner of the header.
3. Click on the “Tasks”.
4. Click on the “Edit” button in the Today column.
5. Popup window “Task details” is appeared.
6. Click on “Delete” button.

**Expected result:** A task is deleted in the “Today” column.

## Scenario 4.3. Validate the working of add new task in the Backlog column

**Test Case 4.3.1. Validate if user is able to add a new task in the Backlog column**
  **Pre-conditions**
The user is signed into the App with the following credentials:
    * username: smoketestuserr
    * password: smoke1234
**Path**

1. Navigate to the URL: https://flow-ui-prod-dot-sage-surfer-341107.lm.r.appspot.com/
2. Click on the hamburger menu button in the left corner of the header.
3. Click on the “Tasks”.
4. Click on the “Add” icon in the Backlog column.
5. Popup window “New task” is appeared.
6. Fill in the next rows: “Name”, “Description”.
7. Click on the “To Do” button.
8. Click on the “Add” button.

**Expected result:** A task is added to the “Backlog” column.

## Scenario 4.4. Validate the working of delete new task in the Backlog column

**Test Case 4.4.1. Validate if user is able to delete a task in the Backlog column**
  **Pre-conditions**
The user is signed into the App with the following credentials:
    * username: smoketestuserr
    * password: smoke1234
**Path**

1. Navigate to the URL: https://flow-ui-prod-dot-sage-surfer-341107.lm.r.appspot.com/
2. Click on the hamburger menu button in the left corner of the header.
3. Click on the “Tasks”.
4. Click on the “Edit” button in the Today column.
5. Popup window “Task details” is appeared.
6. Click on “Delete” button.

**Expected result:** A task is deleted in the “Today” column.

## Scenario 4.5. Validate the working of add new task in the Done column

**Test Case 4.5.1. Validate if user is able to add a task**
  **Pre-conditions**
The user is signed into the App with the following credentials:
    * username: smoketestuserr
    * password: smoke1234

**Path**

1. Navigate to the URL: https://flow-ui-prod-dot-sage-surfer-341107.lm.r.appspot.com/
2. Click on the hamburger button in the left corner of the header.
3. Click on the “Tasks”.
4. Click on the “Add” icon (+) in the Done column.
5. Popup window “New Task” is appeared.
6. Fill in rows: “Name”, “Description”.
7. Click on “Done” button.
8. Click on “Add” button.

**Expected result:** A task is added to the “Done” column.

## Scenario 4.6. Validate the working of delete new task in the Done column

**Test case 4.6.1. Validate if user is able to delete a task**
    **Pre-conditions**
The user is signed into the App with the following credentials:
    * username: smoketestuserr
    * password: smoke1234
**Path**

1. Navigate to the URL: https://flow-ui-prod-dot-sage-surfer-341107.lm.r.appspot.com/
2. Click on the hamburger menu button in the left corner of the header.
3. Click on the “Tasks”.
4. Click on the “Edit” button in the Done column.
5. Popup window “Task details” is appeared.
6. Click on “Delete” button.

**Expected result:** A task is deleted in the “Done” column.

## Scenario 4.7. Validate the working of add New Note

**Test Case 4.7.1. Validate if user is able to add new note**
    **Pre-conditions**

The user is signed into the App with the following credentials:
    * username: smoketestuserr
    * password: smoke1234
**Path**

1. Navigate to the URL: https://flow-ui-prod-dot-sage-surfer-341107.lm.r.appspot.com/
2. Click on the hamburger menu button in the left corner of the header.
3. Click on the “Tasks”.
4. Scroll down.
4. Click on the “Add” (+) button.
5. Popup window “New note” is appeared.
6. Fill in the next rows: “Title”, “Description”.
7. Choose the background color.
8. Click on the “Add” button.

**Expected result:** A new note is created.

**Test Case 4.7.1.  Validate if user is able to edit a note**
    **Pre-conditions:**
The user is signed into the App with the following credentials:
    * username: smoketestuserr
    * password: smoke1234
**Path**

1. Navigate to the URL: https://flow-ui-prod-dot-sage-surfer-341107.lm.r.appspot.com/
2. Click on the hamburger menu button in the left corner of the header.
3. Click on the “Tasks”.
4. Scroll down.
4. Click on the “Edit” icon.
5. Popup window “Edit note” is appeared.
6. Edit the next rows: “Title”, “Description”.
7. Choose the background color.
8. Click on the “Save” button.

**Expected result:** A note is edited and successfully saved.

**Test Case 4.7.1. Validate if user is able to delete a note**
  **Pre-conditions:**
The user is signed into the App with the following credentials:
    * username: smoketestuserr
    * password: smoke1234
**Path**

1. Navigate to the URL: https://flow-ui-prod-dot-sage-surfer-341107.lm.r.appspot.com/
2. Click on the hamburger menu button in the left corner of the header.
3. Click on the “Tasks”.
4. Scroll down.
4. Click on the “Edit” button.
5. Popup window “Edit note” is appeared.
6. Click on the “Delete” button.
7. Click on the “Yes, delete it” button.

**Expected result:** A note is deleted.

## 5. Areas of Focus

**Scenario 5.1. Validate the working of add New Area of Focus**

**Test Case 5.1.1. Validate if user is able to Add New Area of Focus**
   **Pre-conditions**
The user is signed into the App with the following credentials:
     * username: smoketestuserr
     * password: smoke1234
**Path**

1.	Navigate to the URL: https://flow-ui-prod-dot-sage-surfer-341107.lm.r.appspot.com/
2. Click on the hamburger button in the left corner of the header.
3. Click on the “Area of Focus”.
4. Click on the “Add” icon (+).
5. Popup window is appeared. 
5. Fill in all rows: “Name”. 
6. Choose “Insert of the list” in the dropdown menu.
6. Click on the “Add” button.

**Expected result:** The Area of Focus is created and successfully saved. 

## Scenario 5.2. Validate the working of edit the Area of Focus

**Test Case 5.2.1. Validate if user is able of edit the Area of Focus**
**Pre-conditions** 
The user is signed into the App with the following credentials:
    * username: smoketestuserr
    * password: smoke1234
**Path**

1.	Navigate to the URL: https://flow-ui-prod-dot-sage-surfer-341107.lm.r.appspot.com/
2. Click on the hamburger button in the left corner of the header.
3. Click on the “Area of Focus”.
4. Choose any existing Area of Focus.
5. Click on the “Edit” button.
6. Popup window is appeared. 
7. Edit any row in the popup window.
8. Click on the “Save” button.

**Expected result:** The Area of Focus is edited and successfully saved.

## Scenario 5.3. Validate the working of add a Link to Area of Focus

**Test Case 5.3.1. Validate user is able to add a Link to Area of Focus**
  **Pre-conditions**
The user is signed into the App with the following credentials:
    * username: smoketestuserr
    * password: smoke1234
**Path**

1.	Navigate to the URL: https://flow-ui-prod-dot-sage-surfer-341107.lm.r.appspot.com/
2. Click on the hamburger button in the left corner of the header.
3. Click on the “Area of Focus”.
4. Choose any existing Area of Focus.
5. Click on the “Links” button.
6. Click on the “Add” icon (+).
6. Popup window is appeared. 
7. Fill in the next rows: “Title”, “URI”.
8. Click on the “Save” button.

**Expected result:** The link is successfully saved.

**Test Case 5.3.2. Validate user is able to edit the Link to Area of Focus**
**Path**
Navigate to the URL: https://flow-ui-prod-dot-sage-surfer-341107.lm.r.appspot.com/
2. Click on the hamburger button in the left corner of the header.
3. Click on the “Area of Focus”.
4. Choose any existing Area of Focus.
5. Click on the “Links” button.
6. Click on the “Edit” button.
6. Popup window is appeared. 
7. Edit rows which are required: “Title” or “URI”.
8. Click on the “Save” button.

**Expected result:** The link is edited and successfully saved.

## Scenario 5.4. Validate the working of delete a Link to Area of Focus.

**Test Case 5.4.1. Validate user is able to delete a Link to Area of Focus.**
**Path**

Navigate to the URL: https://flow-ui-prod-dot-sage-surfer-341107.lm.r.appspot.com/
2. Click on the hamburger button in the left corner of the header.
3. Click on the “Area of Focus”.
4. Choose any existing Area of Focus.
5. Click on the “Links” button.
6. Click on the “Edit” button.
6. Popup window is appeared. 
7. Click on the “Delete” button.
8. Clink on the “Yes, delete it” button.

**Expected result: The link is successfully deleted.**

## Scenario 5.5. Validate the working of delete Area of Focus

**Test Case 5.1.1. Validate user is able to delete Area of Focus**
  **Pre-conditions**
The user is signed into the App with the following credentials:
    * username: smoketestuserr
    * password: smoke1234
**Path**

1.	Navigate to the URL: https://flow-ui-prod-dot-sage-surfer-341107.lm.r.appspot.com/
2. Click on the hamburger button in the left corner of the header.
3. Click on the “Area of Focus”.
4. Click on the “Edit” button.
5. Popup window is appeared. 
6. Click on the “Delete” button. (Delete button is inactive).

**Expected result:** Area of Focus is successfully deleted.

# 6.	Report a bug

## Scenario 6.1. Validate the working of Report a bug.

**Test Case 6.1.1. Validate user is able to report a bug.**
  **Pre-conditions**
The user is signed into the App with the following credentials:
    * username: smoketestuserr
    * password: smoke1234
**Path**

1. Navigate to the URL: https://flow-ui-prod-dot-sage-surfer-341107.lm.r.appspot.com/
2. Click on the hamburger button in the left corner of the header.
3. Click on the “Report a bug”.
4. The Outlook window is appeared. 
5. Add the bug report into the letter.
6. Click on the “Send” button.

**Expected result:** A bug report is successfully sent.

# 7.	Help

## Scenario 7.1. Validate the links in the Books sections

**Test Case 7.1.1. Validate if user is able to follow the link in the “User Manual” section**

1. Navigate to the URL: https://flow-ui-prod-dot-sage-surfer-341107.lm.r.appspot.com/
2. Click on the hamburger button in the left corner of the header.
3. Click on the “Help”.
4. Click on the “User Manual” link.

**Expected result:** A user is redirect to the “User Manual” part.

**Test Case 7.2.1. Validate if user is able to follow the links in the “Time Management Tips and Tricks” section**

1. Navigate to the URL: https://flow-ui-prod-dot-sage-surfer-341107.lm.r.appspot.com/
2. Click on the hamburger button in the left corner of the header.
3. Click on the “Help”.
4. Click on the “Time Management Tips and Tricks” link.

**Expected result:** A user is redirect to the “Time Management Tips and Tricks” part.

**Test Case 7.2.1. Validate if user is able to follow the links “About Us”.**

1. Navigate to the URL: https://flow-ui-prod-dot-sage-surfer-341107.lm.r.appspot.com/
2. Click on the hamburger button in the left corner of the header.
3. Click on the “Help”.
4. Click on the “About Us” link.

**Expected result:** A user is redirect to the “About Us” part.
