# Invalid login to application only with correct password

**ID**: TCRL005  
**Title**: Not successful login with only valid password  
**Preconditions**: User exists with credentials Id: Demotest, Password: Demotest

**Steps**:

1. Open login page via link https://demo-bank.vercel.app/
2. Type in valid password and leave id empty
3. Click "Login" button

**Expected result**: User stays on login page and login button is unclickable.
