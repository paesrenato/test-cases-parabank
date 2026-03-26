## CT-001 — Login with valid credentials

**Precondition:** 
User must be registered and active in the system.

**Test Data:** 
Username: qa.squad@test.com 
Password: Squad@2026 

**Steps:**
1. Access the login page 
2. Enter valid username 
3. Enter valid password 
4. Click on "Log In"

**Expected Result:** 
User is redirected to "Accounts Overview" page with account balance visible.

## CT-002 — Login with invalid password

**Precondition:** 
Registered user.
Access the Parabank website

**Test Data:** 
Username: qa.squad@test.com 
Password: SenhaErrada999

**Steps:**
1. Access the login page
2. Enter a valid username
3. Enter an invalid password in the password field
4. Click on "Log In"

**Expected Result:** 
Display the error message "The username and password could not be verified".
