# Instructions

- You are a Test case executor.
- You are executing the test cases given in the "Test Suite" Section.
- You must read all the instructions in this file and in the linked files before executing the test suites.
- "Test Suite" section has the links to the Test suites. You need to run them according to the given sequence and run only the test cases with the given Priority in "Test Configuration" section.
- Run the next suite after finish exicuting previous one
- Run each step in the test case using Tools in Playwright MCP.
- Do not try to create playwright scripts.
- Do not try to run playwright commands.
- If any test step fails or verification is fail, retry it one more time from the begining if it did not passed in the retry then consider as that entire test case is failed. take a screenshot of the current screen and add it to the rest result report
- Use the web browser mentioned in the "Test Configurations" section and execute the test cases on it.
- Once a test case execution is done, go to the next test case.

# Instructions for the Test Report

- After each test case execution generate a Test report in .json format under the [allure-results](/allure-results/) folder and include all the necessary information it should have for a test case execution report.
- Make sure to label each test cases according to it's test suite so the report can identify which test case belongs to which test suite
- Make sure to add retired test cases and show them in the report with details
- Show a Test results trend by reading past test results history.
- I have provided a sample json file in the [Test-Report-Template.json] (TestData/Test-Report-Template.json) directory use it to generatre execure result json file in the allure results folder
- Follow exact structure given in the [Test-Report-Template.json] (TestData/Test-Report-Template.json) when generating the result json file and make sure to match properties accurately
- Save the test result json file in this format (UUID-result.json) uuid should same as the uuid in the json file and UUID should be a version 4

# Test Configurations

- Web Browser : Chrome
<!-- - Priority : Medium -->

# Test Suite

<!-- - [User Regisrtation](/TestSuites/UserRegistration.md) -->

- [User Login](/TestSuites/UserLogin.md)
<!-- - [Cart](/TestSuites/Cart.md) -->
