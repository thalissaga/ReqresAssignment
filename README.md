# ReqresAssignment

This is the answer to **assignment for quality engineering** test number 1.

The challenge is to create test suite with WebService type using Katalon Studio for below endpoints on https://reqres.in/ :
  1. GET list users on page 1
  2. GET single user
  3. PUT update
  4. POST register successful
  
Global Variable named "URL" used on every web service request, has a default value named also "URL" which you can found at Execution Profile. It has a value of "https://reqres.in/api".

Each endpoint used for each test case according to the needs:
  1. Endpoint 'GET list users on page 1' used in **TCAPI001 - GET LIST USERS** 
  2. Endpoint 'GET single user' used in **TCAPI002 - GET SINGLE USER** 
  3. Endpoint 'PUT update' used in **TCAPI003 - PUT UPDATE** 
  4. Endpoint 'POST register successful' used in **TCAPI004 - POST REGISTER SUCCESSFUL** 

Test suites named **TSAPI001** contains TCAPI001 to TCAPI004 and successfully **passed**. The report is auto generated and stored under **Reports** folder.

Thank you!
