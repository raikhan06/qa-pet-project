# Exploratory Testing Report

## Objective

The purpose of exploratory testing is to verify the application behavior using special SauceDemo test users and identify defects that are not covered during standard functional testing

---

## Session 1

### Test User

problem_user

### Goal

Verify Product page and Cart functionality.

| Test ID | Area | Scenario | Status | Comments |
|---------|------|----------|--------|----------|
| ET-001 | Login | Login with valid credentials | Pass | Login completed successfully |
| ET-002 | Product | Verify product catalog | Pass | Product catalog displayed correctly |
| ET-003 | Product | Verify product images | Fail | Backpack image is displayed incorrectly |
| ET-004 | Product | Verify Add to Cart | Pass | Product was added successfully |
| ET-005 | Cart | Verify cart page | Pass | Cart page opened successfully |

---

## Session 2

### Test User

performance_glitch_user

### Goal

Verify application performance during main user flow

| Test ID | Area | Scenario | Status | Comments |
|---------|------|----------|--------|----------|
| ET-006 | Login | Login with valid credentials | Pass | Login completed after approximately 5 seconds |
| ET-007 | Product | Verify product catalog | Pass | Products loaded successfully |
| ET-008 | Cart | Verify cart page | Pass | Cart loaded correctly |
| ET-009 | Checkout | Complete checkout | Pass | Checkout completed successfully |

---

## Session 3

### Test User

error_user

### Goal

Verify Checkout and Order Completion functionality

| Test ID | Area | Scenario | Status | Comments |
|---------|------|----------|--------|----------|
| ET-010 | Login | Login with valid credentials | Pass | Login completed successfully |
| ET-011 | Product | Add product to cart | Pass | Product added successfully |
| ET-012 | Checkout | Complete checkout | Fail | Incorrect confirmation message displayed |
| ET-013 | Logout | Logout | Pass | Logout completed successfully |

---

## Summary

| Test User | Result |
|------------|--------|
| problem_user | 1 defect found |
| performance_glitch_user | Performance delay observed |
| error_user | 1 defect found |
