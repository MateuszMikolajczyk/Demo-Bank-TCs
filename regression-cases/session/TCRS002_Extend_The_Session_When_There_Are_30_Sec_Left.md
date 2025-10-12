# Extend_The_Session_When_Are_30_Seconds_Left

**ID**: TCRS002  
**Title**: User extends session when are 30 seconds left  
**Preconditions**: User exists with credentials Id: Demotest, Password: Demotest

**Steps**:

1. Open user page via link https://demo-bank.vercel.app/
2. Log in to application with credentials from preconditions
3. Wait until session time counter will shows 30 seconds and dialog for extend session will be visible;
4. Click on button extend session

**Expected result**: Session is extended successfully with time counter set to 10 minutes and it counts down to zero.
