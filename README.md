# Test Cases

Below are some test cases that I did.

-----------

**Title:**
Test login with correct credentials

**Description:**
Test the login by using correct credentials.

**Steps to reproduce:**
1. Go to site.com/login
2. Add correct user and password
3. Press login button
4. Observe if user can login

**Expected Result:**
User should be able to login and is taken to his profile page.

**Test Data:**
User: JohnSmith, Password: 123

-------------------

**Title:**
Test login with correct credentials

**Description:**
Test the login by using correct credentials.

**Steps to reproduce:**
1. Go to wordpress.com
2. Add a correct username and password
3. Press login button
4. Observe if user can login

**Expected Result:**
User should be able to login and is taken to his profile page.

**Test Data:**
User: JohnSmith, Password: 123

-----------------------

**Title:**
Test login with incorrect credentials

**Description:**
Test the login by using incorrect credentials.

**Steps to reproduce:**
1. Go to wordpress.com
2. Add incorrect user/password
3. Press login button

**Expected Result:**
User should not be able to login if the credentials are incorrect.

**Test Data:**
User: J.Smith, Password: 012

-----------------------

**Title:**
Test login without credentials

**Description:**
Test the login when credentials fields are blank.

**Steps to reproduce:**
1. Go to wordpress.com
2. Press login button

**Expected Result:**
User should not be able to login if the credentials fields are not completed.

----------------------

**Title:**
Test login with checkbox "Remember me"

**Description:**
Test the login by using correct credentials and "Remember me" checkbox ticked off.

**Steps to reproduce:**
1. Go to wordpress.com
2. Add a correct user and password
3. Ticked off „Remember me” checkbox
4. Press login button

**Expected Result:**
User should be able to login and stay logged in.

**Test Data:**
User: JohnSmith, Password: 123

---------------------

**Title:**
Test search functionality for emag.ro

**Description:**
Verify if when the user clicks the search box, the result should be displayed on the page.

**Steps to reproduce:**
1. Go to the search box
2. Type “laptop”
3. Press enter

**Expected Result:**
User should be able to see the search results.

----------------------

**Title:**
Test search functionality for emag.ro

**Description:**
Verify if when user enters letters in the search box, then suggested product list should be displayed.

**Steps to reproduce:**
1. Go to the search box
2. Type “lap”
3. Choose a search suggestion

**Expected Result:**
User should be able to see the search suggestions.

------------------------

**Title:**
Test search functionality for emag.ro

**Description:**
Test search functionality when you type something that doesn't exist.

**Steps to reproduce:**
1. Go to the search box
2. Type “@@#”
3. Press enter

**Expected Result:**
A search must not give an error when the user is looking for something that doesn’t exist.

