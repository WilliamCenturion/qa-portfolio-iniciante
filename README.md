# QA Portfolio — Beginner

## About this project

This repository contains my practical exercises in Quality Assurance (QA), focusing on manual software testing using the Sauce Demo demo application.

## Test Cases

| ID | Test Scenario | Type | Result |
|---|---|---|---|
| CT-001 | Add a product to the cart | Functional | PASS |
| CT-002 | Verify two products in the cart | Functional | PASS |
| CT-003 | Remove a product from the cart | Functional | PASS |
| CT-005 | Login with an incorrect password | Negative | PASS |

## CT-005 — Invalid Login

**Objective:** Verify that the application rejects an incorrect password.

**Test data**
- Username: `standard_user`
- Password: `senha_errada_123`

**Steps**
1. Open the login page.
2. Enter the username.
3. Enter an incorrect password.
4. Click Login.

**Expected result:** Access is denied and an error message is displayed.

**Actual result:** Access was denied and an error message was displayed.

**Status:** PASS

## Skills Practiced

- Manual testing
- Functional testing
- Positive and negative test scenarios
- Test case documentation
- Expected versus actual results

## Test Environment

- Application: Sauce Demo
- Method: Manual testing
- Project level: Beginner
