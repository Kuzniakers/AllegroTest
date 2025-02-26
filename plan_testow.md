# Test Plan for Allegro.pl

**Version:** 1.0  
**Date:** 01.05.2023  
**Prepared by:** Konrad Kuźniak  

## Introduction

### 1. Objective of Testing

- The objective of testing Allegro.pl is to ensure high software quality, verify the correctness of all platform functionalities, and identify and fix any issues that may impact the user experience.

### 2. Scope of Testing

- The scope of testing includes all key functionalities of Allegro.pl, such as login, registration, search, filtering, adding items to the cart, order processing, account management, and interactions between buyers and sellers.

## Resources

### 1. Personnel

- **QA Engineer:** Responsible for conducting tests, reporting defects, supervising the testing process, and analyzing test results.

### 2. Tools

- **TestRail:** For managing test cases and reporting test results.
- **JIRA:** For defect tracking and progress monitoring.
- **JMeter:** For load testing the website.

### 3. Test Environment

- **Hardware:** Desktop computer and smartphone.
- **Browsers:** Chrome (version 88) and Mozilla Firefox (version 95).
- **Operating Systems:** Windows 10 Home (64-bit) and Android 11.

## Approach

### 1. Testing Strategy

- Execution of manual and exploratory tests to verify the functionality, compatibility, performance, usability, security, and localization of Allegro.pl.

### 2. Methodologies

- Utilization of **Agile** and **Scrum** methodologies to quickly adapt to changes and continuously improve software quality.

### 3. Levels of Testing

- **Unit Testing:** Conducted by developers at the code level.
- **Integration Testing:** Verifying interactions between different modules of the platform.
- **System Testing:** Ensuring that the entire system meets requirements.
- **Acceptance Testing:** Validating that the system meets end-user expectations.

### 4. Testing Execution Workflow

- Preparation of the test environment and tools.
- Execution of tests based on test cases.
- Documentation and reporting of test results in TestRail.
- Reporting of any defects in JIRA.
- Verification of fixed defects and updating test results.
- Communication with the development team to improve software quality.

### 5. Test Schedule

1. **Estimated test duration:**  
   The estimated duration of testing is **4 weeks**.

2. **Milestones:**  
   - Test start: **01.05.2023**  
   - Test completion: **29.05.2023**  
   - Delivery of test results: **31.05.2023**  

### 6. Test Cases

1. **Functional Tests:**
   - Registration, login, and logout.
   - Searching, filtering, and sorting products.
   - Adding products to the cart and completing orders.
   - Managing user accounts (personal data, order history, watched products).
   - Adding, editing, and deleting listings by sellers.
   - Commenting and rating transactions.

2. **Compatibility Tests:**
   - Testing across different browsers and devices.
   - Testing on different operating systems.

3. **Performance Tests:**
   - Measuring page load times and individual element performance.
   - Load testing of the website.

4. **Usability Tests:**
   - Evaluating readability, accessibility, and intuitiveness of the platform.

5. **Security Tests:**
   - Verifying user data protection measures.

6. **Exploratory Tests:**
   - Conducting non-directed testing to discover potential issues.

### 7. Metrics and Exit Criteria

1. **Metrics:**
   - Number of identified defects.
   - Response time to defect reports.
   - Number of fixed defects.

2. **Exit Criteria:**
   - All reported defects have been fixed or accepted as system limitations.
   - No new critical defects reported for at least **5 business days**.
   - Achieving satisfactory results in all key metrics.

### 8. Risk and Issue Management

Identification, analysis, and response to risks and issues that may arise during testing, such as delays, changes in requirements, lack of resources, or unforeseen technical problems.

### 9. Conclusion

- This test plan serves as a framework for testing Allegro.pl. Adjustments may be necessary during testing in response to changes in requirements or encountered issues.  
- Upon completion, test results, recommendations, and insights should be shared with the development team to collaborate on further improving the platform's quality.
