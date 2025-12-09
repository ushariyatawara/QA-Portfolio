# Instagram Login Feature - Sample Test Cases

## Project Overview
This document contains sample test cases designed for testing the functionality of Instagram login feature.

## Definitions
Precondition: An initial requirement for the test to be executed  
Test Steps: Step-by-step instructions to execute the test case  
Expected Result: The final expected behaviour when a test case is executed  
Priority - High: Critical for functionality | Medium: Important but not critical  
Severity - Major: Affects key functionality | Minor: Minor UI/UX issues, not critical

## TC01 - Valid Login
**Precondition:** User has an Instagram account
**Test Steps:**
1. Open Instagram 
2. Enter valid username/email/phone number and password 
3. Click ‘Login’  
**Expected Result:** User is logged in successfully  
**Priority:** High  
**Severity:** Major  
**Status:** NE

## TC02 - Invalid Username / Email / Phone number
**Precondition:** User has an Instagram account
**Test Steps:**
1. Open Instagram 
2. Enter invalid username/email/phone number and valid password 
3. Click ‘Login’  
**Expected Result:** User sees an error message saying “User not found”  
**Priority:** High  
**Severity:** Major  
**Status:** NE

## TC03 - Invalid Password 
**Precondition:** User has an Instagram account
**Test Steps:**
1. Open Instagram 
2. Enter valid username/email/phone number and invalid password 
3. Click ‘Login’  
**Expected Result:** User sees an error message saying “Your password was incorrect. Please try again”  
**Priority:** High  
**Severity:** Major  
**Status:** NE

## TC04 - Empty Username / Email / Phone number  
**Precondition:** User has an Instagram account
**Test Steps:**
1. Open Instagram 
2. Keep username/email/phone number blank and enter valid password 
3. Click ‘Login’  
**Expected Result:** User sees an error message saying “Username/email/phone number is required"  
**Priority:** Medium  
**Severity:** Major  
**Status:** NE

## TC05 - Case Sensitivity 
**Precondition:** User has an Instagram account
**Test Steps:**
1. Open Instagram 
2. Type username with wrong case 
3. Click ‘Login’  
**Expected Result:** User sees an error message saying “User not found”  
**Priority:** Medium  
**Severity:** Minor  
**Status:** NE

## TC06 - Password Reset 
**Precondition:** User has an Instagram account
**Test Steps:**
1. Open Instagram 
2. Click ‘Forgot Password’ 
3. Enter email 
4. Click ‘Submit’  
**Expected Result:** User receives a password reset email to the registered email address  
**Priority:** High  
**Severity:** Major  
**Status:** NE

## TC07 - Login with Facebook 
**Precondition:** User has an Instagram account
**Test Steps:**
1. Open Instagram 
2. Click ‘Login with Facebook’ 
3. Enter Facebook credentials  
**Expected Result:** User is logged in through Facebook  
**Priority:** Medium  
**Severity:** Minor  
**Status:** NE

