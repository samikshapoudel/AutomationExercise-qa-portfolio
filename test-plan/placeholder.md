
# Test Plan - Automation Exercise

**Date:** March 2026
**Prepared by:** Samiksha Poudel

## Purpose
The goal of this testing is to make sure the Automation Exercise e-commerce application works as expected for end users. I want to identify and document any bugs or unexpected behaviors before they affect the user experience.

## What I am testing
- User Registration and Login / Logout
- Search functionality
- Adding and removing items from cart
- Checkout flow

Login and payment-related flows are the highest priority since these directly impact users and are the most critical parts of any e-commerce application.

## What I am not testing
- Application performance and load testing
- Security and penetration testing
- Mobile app (testing on Chrome browser only)

## How I will test
I will manually go through each feature, write test cases covering both expected and unexpected user behavior, perform API testing using Postman, and validate data using T-SQL queries. Any bugs found will be documented with steps to reproduce in Jira.

## Tools
- Jira - test case and bug management
- Chrome DevTools - UI inspection & debugging

## Test Environment
- Browser: Chrome (latest version)
- OS: Windows 11
