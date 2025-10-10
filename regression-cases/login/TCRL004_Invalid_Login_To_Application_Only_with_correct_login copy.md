# Invalid login to application only with correct login

**ID**: TCRL004  
**Title**: Not successful login with only valid login  
**Preconditions**: User exists with credentials Id: Demotest, Password: Demotest

**Steps**:

1. Open login page via link https://demo-bank.vercel.app/
2. Enter valid id and leave password empty
3. Click "Login" button

**Expected result**: User stays on login page and login button is unclickable.
