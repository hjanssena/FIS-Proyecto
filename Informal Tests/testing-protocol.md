## Metrics

**Functionality** [Accessibility  to  Requirements]. (The  user  could  independently  access  all  the  system's  functionalities)

-   Maximum  accepted error count  for  each step. The error count  for  each step will be defined  based  on  how  many times the  user  gets  stuck in the  flow  or, conversely, accesses  another  functionality  not  requested. If  the  maximum error count  is  exceeded at each step, the final result  will be that  the  user  could  not complete that step.
    
-   Maximum  number  of  steps  not  fulfilled. This  number  will be set at 3 steps.
    
-   Observations  must  precisely  record  why  the  user  made  mistakes and errors,  this  should be done for  each test step because  not  all  errors are equally  relevant in determining  the  correct  functionality  of  the software.
    

**Usability** [Ease  of use of  the software]. (Measurement in total test time per user, used as a reference  for future tests)

-   Total test time for  each  tester.
    
-   Average time for  all  tests  conducted.
    
-   Number  of times the  user  asked, "How can I continue?" or  requested  some  form  of  additional  guidance.  If  we  want  the software to be easy  to use, the  theory  suggests  that  the  system  should  generate as few  doubts as possible.
    

## Protocol

A test was  conducted  for  each  system  requirement, implicitly  performing a complete functional  flow  integration test of  the software. The  user  was  asked  to  access  the  system's  functions. The  following table presents a simplified  version  of  the test procedure:

| Step | Description | Metric | Final result | Observations |
|--|--|--|--|--|
| 1 | The user can create a new account from the login window. | [A more specified  version  with  the  measured  indicators can be found in Excel] | [Indicate  whether  it  was  achieved  or  not  achieved  using a check  mark  or a tick  respectively] | [Record  of  where in the step you  went  wrong, etc.] |
| 2 | Upon returning to the login window, the user is able to recover his or her password. |  |  |  |
| 3 | The  user logs in from  the “login” window. |  |  |  |
| 4 | The  user  creates a new service  order. |  |  |  |
| 5 | The  user completes a service  order. |  |  |  |
| 6 | The  user  returns  to  the  main  menu and accesses  the  service  order  history. |  |  |  |
| 7 | The  user  accesses  the workshop metrics. |  |  |  |
| 8 | The  user  returns  to  the  main  menu and accesses  the  application  settings  menu. |  |  |  |
| 9 | The  administrator  creates a new user  from  the  settings  menu. |  |  |  |


## Definition  of Test Conditions

### Environment  Conditions

-   The software execution  will  take place on a single Android mobile  device.
    
-   The  screen  of  the  said  device  will be recorded, and facial expressions  of  the  tester  will be captured  using  the webcam.
    
-   The test will be conducted in an office environment  within  an automotive workshop, and testers  will  participate  during  their regular working  hours.


