# Bug Reports

## Summary

During testing of the OrangeHRM PIM module, validation-related defects were identified.

### BUG_001

Title: First Name field accepts numeric values

Module: PIM

Severity: Medium

Priority: High

Status: Open

Steps to Reproduce:

1. Login to OrangeHRM
2. Navigate to PIM Module
3. Click Add Employee
4. Enter 12345 in First Name
5. Enter valid Last Name
6. Click Save

Expected Result:
System should accept only alphabetic characters.

Actual Result:
Employee record is saved successfully with numeric First Name.


---

### BUG_002

Title: Last Name field accepts numeric values

Severity: Medium

Priority: High

Status: Open


---

### BUG_003

Title: First Name field accepts special characters

Severity: Low

Priority: Medium

Status: Open


---

### BUG_004

Title: Last Name field accepts special characters

Severity: Low

Priority: Medium

Status: Open
