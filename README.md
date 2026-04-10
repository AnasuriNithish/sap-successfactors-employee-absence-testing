# 🏷️ Employee Absence & Workflow Testing in SAP SuccessFactors

---

## 🎯 Objective
To perform end-to-end functional testing on employee data and leave management workflows in SAP SuccessFactors, ensuring correct validation, business rules, and workflow behavior.

---

## 🧭 Project Overview
This project focuses on testing core HR processes within SAP SuccessFactors including:

- Employee Data Validation (Employee Central)
- Leave Request Workflow (Time Off)
- Basic Workflow Behavior & System Responses

The goal was to simulate real-world HR scenarios and validate system behavior from a QA perspective.

---

## 🔄 Modules Covered

- Employee Central (Personal Information & Profile)
- Time Off (Leave Management)

---

## 🧪 Test Scenarios Covered

### ✔️ Positive Scenarios
- Valid leave request submission
- Employee data display verification
- Profile data validation

### ❌ Negative Scenarios
- Duplicate leave request validation
- Invalid date range (End Date < Start Date)
- Recurrence rule validation (Full-day + recurring leave)
- Mandatory field validation

---

## 🧠 Key Validations Performed

- Date validation (Start Date must be before End Date)
- Duplicate leave prevention
- Leave balance restriction handling
- Input field validation
- Workflow triggering and system response behavior

---

## 🔁 Workflow Tested

Employee → Submit Leave Request → System Validation → Request Status Update (Pending/Processed)

---

## 🛠️ Testing Approach

- Manual Functional Testing
- Scenario-Based Testing
- Negative Testing
- Business Rule Validation

---

## 📊 Observations

- System correctly restricts duplicate leave requests
- Proper validation messages displayed for invalid inputs
- Business rules like recurrence and date constraints are enforced
- Workflow triggers observed through system responses and status behavior

---

## 🐞 Defect Summary

No critical defects identified.  
All core validations and workflows behaved as expected within the trial environment.

---

## 📸 Screenshots

Screenshots are available in the `/screenshots` folder demonstrating:
- Valid leave submission
- Duplicate leave validation
- Error messages for invalid inputs

---

## 🎤 Interview Summary

Performed end-to-end testing on employee data and leave workflows in SAP SuccessFactors, validating business rules such as duplicate handling, date constraints, and workflow behavior through scenario-based testing.

---

## 🚀 Outcome

- Gained hands-on experience in SAP HR workflows
- Strengthened understanding of business rule validation
- Applied QA testing concepts in real SAP environment

---
