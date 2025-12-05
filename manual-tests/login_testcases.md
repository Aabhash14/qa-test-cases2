# Login Test Cases

## 1. Valid login with correct username and password (Positive)
**Steps:** Enter valid username and password.  
**Expected:** User redirected to dashboard.

## 2. Invalid password (Negative)
**Expected:** Error "Invalid username or password".

## 3. Empty fields (Negative)
**Expected:** "Username and Password are required".

## 4. Disabled account login attempt (Negative)
**Expected:** "Your account is disabled".

## 5. Remember Me functionality (Positive)
**Expected:** User stays logged in after browser restart.
