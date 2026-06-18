# OrangeHRM Test Cases

## TC_001 - Verify Login with Valid Credentials

Module: Login

Precondition:
User should have valid login credentials.

Test Steps:
1. Open OrangeHRM application.
2. Enter valid Username.
3. Enter valid Password.
4. Click Login.

Expected Result:
User should be redirected to Dashboard page.

Status: Pass

--------------------------------------------------

## TC_002 - Verify Login with Invalid Password

Module: Login

Precondition:
User should have a valid username.

Test Steps:
1. Open application.
2. Enter valid Username.
3. Enter invalid Password.
4. Click Login.

Expected Result:
Error message should be displayed.

Status: Pass

--------------------------------------------------

## TC_003 - Verify Login with Blank Credentials

Module: Login

Test Steps:
1. Open application.
2. Leave Username blank.
3. Leave Password blank.
4. Click Login.

Expected Result:
Required validation message should be displayed.

Status: Pass

--------------------------------------------------

## TC_004 - Verify Forgot Password using Valid Username

Module: Forgot Password

Test Steps:
1. Click Forgot Password.
2. Enter valid Username.
3. Click Reset Password.

Expected Result:
Password reset confirmation message should be displayed.

Status: Pass

--------------------------------------------------

## TC_005 - Verify Forgot Password using Invalid Username

Module: Forgot Password

Test Steps:
1. Click Forgot Password.
2. Enter invalid Username.
3. Click Reset Password.

Expected Result:
Appropriate error message should be displayed.

Status: Pass

--------------------------------------------------

## TC_006 - Verify Add Employee Functionality

Module: PIM

Test Steps:
1. Navigate to PIM Module.
2. Click Add Employee.
3. Enter valid employee details.
4. Click Save.

Expected Result:
Employee should be added successfully.

Status: Pass

--------------------------------------------------

## TC_007 - Verify Employee Search Functionality

Module: PIM

Test Steps:
1. Navigate to PIM Module.
2. Search employee by name.
3. Click Search.

Expected Result:
Matching employee record should be displayed.

Status: Pass

--------------------------------------------------

## TC_008 - Verify Edit Employee Details

Module: PIM

Test Steps:
1. Search existing employee.
2. Open employee profile.
3. Modify employee details.
4. Click Save.

Expected Result:
Updated information should be saved successfully.

Status: Pass

--------------------------------------------------

## TC_009 - Verify Delete Employee Functionality

Module: PIM

Test Steps:
1. Search employee.
2. Select employee record.
3. Click Delete.
4. Confirm deletion.

Expected Result:
Employee record should be removed successfully.

Status: Pass

--------------------------------------------------

## TC_010 - Verify Numeric Values in First Name Field

Module: PIM

Test Steps:
1. Click Add Employee.
2. Enter "12345" in First Name.
3. Enter valid Last Name.
4. Click Save.

Expected Result:
System should display validation message.

Actual Result:
Employee record is saved successfully.

Status: Fail

--------------------------------------------------

## TC_011 - Verify Numeric Values in Last Name Field

Module: PIM

Test Steps:
1. Click Add Employee.
2. Enter valid First Name.
3. Enter "98765" in Last Name.
4. Click Save.

Expected Result:
System should reject numeric values.

Actual Result:
Employee record is saved successfully.

Status: Fail

--------------------------------------------------

## TC_012 - Verify Special Characters in First Name Field

Module: PIM

Test Steps:
1. Click Add Employee.
2. Enter "@#$%" in First Name.
3. Save employee.

Expected Result:
Validation message should appear.

Actual Result:
Special characters accepted.

Status: Fail

--------------------------------------------------

## TC_013 - Verify Employee Image Upload

Module: PIM

Test Steps:
1. Click Add Employee.
2. Upload valid image file.
3. Save employee.

Expected Result:
Image should upload successfully.

Status: Pass

--------------------------------------------------

## TC_014 - Verify Mandatory Field Validation

Module: PIM

Test Steps:
1. Click Add Employee.
2. Leave mandatory fields blank.
3. Click Save.

Expected Result:
Required field validation messages should appear.

Status: Pass

--------------------------------------------------

## TC_015 - Verify Reset Search Functionality

Module: PIM

Test Steps:
1. Enter search criteria.
2. Click Reset.

Expected Result:
All search filters should be cleared.

Status: Pass
