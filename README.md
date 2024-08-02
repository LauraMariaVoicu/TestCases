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

**Status:**
Pass

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
User: JSmith, Password: 012

**Status:**
Pass

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

**Status:**
Pass

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
5. Check if website homepage load directly for next time

**Expected Result:**
If remember me checkbox is checked while login, browser should remember user credentials. Website homepage should load directly for next time.

**Test Data:**
User: JohnSmith, Password: 123

**Status:**
Pass

---------------------

**Title:**
Test search functionality for emag.ro

**Description:**
Verify that when user clicks on search box, search result should be displayed on page.

**Steps to reproduce:**
1. Go to the search box
2. Type “laptop”
3. Press enter

**Expected Result:**
When the user enters a valid search term, relevant results are expected to be displayed. Searching for "laptop" should show a list of products containing that word, for example 'gaming laptop'.

**Status:**
Pass

----------------------

**Title:**
Test search functionality for emag.ro

**Description:**
Verity that when users enters letters in the search box, then suggested product list should be displayed.

**Steps to reproduce:**
1. Go to the search box
2. Type “lap”
3. Choose a search suggestion

**Expected Result:**
User should be able to see search suggestions, which autocomplete what is written, for example 'laptop', 'lapte', 'laptop gaming' etc.

**Status:**
Pass

------------------------

**Title:**
Test search functionality for emag.ro

**Description:**
Entering an invalid search term and verifying that the search function handles it properly.

**Steps to reproduce:**
1. Go to the search box
2. Type “@@#”
3. Press enter

**Expected Result:**
Searching for ‘@@#’ or a string of random characters should result in a message like ‘No results found’ or ‘Invalid search term’.

**Status:**
Pass

----------------------------------------

