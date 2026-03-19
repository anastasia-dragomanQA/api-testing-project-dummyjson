# API Test Execution Report

Tester: Anastasia Dragoman
Date: 2026-03-16  
Environment: DummyJSON API  

| Test Case ID | Test Case Name | Status | Comments |
|--------------|----------------|--------|----------|
| TC-API-001 | Verify user can retrieve all products | PASS | Status 200 OK, response in JSON format, "products" array returned and not empty |
| TC-API-002 | Verify user can retrieve product by ID | PASS | Status 200 OK, correct product details returned for valid ID |
| TC-API-003 | Verify response when product ID does not exist | PASS | No product found for invalid ID, response handled correctly |
| TC-API-004 | Verify product categories can be retrieved | PASS | Status 200 OK, categories list returned in JSON format |
| TC-API-005 | Verify products can be retrieved by category | PASS | Status 200 OK, filtered products returned for selected category |
| TC-API-006 | Verify login with valid credentials | PASS | Status 200 OK, authentication successful, token returned |
| TC-API-007 | Verify login fails with invalid credentials | PASS | Error response returned, authentication failed as expected |
| TC-API-008 | Verify login fails when username is missing | PASS | Error response returned, validation for missing username works correctly |
| TC-API-009 | Verify login fails when password is missing | PASS | Error response returned, validation for missing password works correctly |
| TC-API-010 | Verify API returns status code 200 for successful requests | PASS | Status 200 OK confirmed for valid GET request |
