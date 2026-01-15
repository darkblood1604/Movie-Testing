# 🎬 Movie Recommendation System – Manual Testing Project

## 📌 Project Overview
This repository contains complete **manual testing documentation** for a Movie Recommendation System web application.  
The project validates the core functionalities such as Login, Search, Filters, Movie Details, and Favorites.

The documentation is based on real QA workflow and includes:
- Test Cases
- Test Scenarios
- Requirement Traceability Matrix (RTM)
- Bug Report
- Test Summary

---

## 📁 Repository Structure

```
Movie-Recommendation-Testing/
│
├── Movie-Test-Cases.xlsx
├── Movie-Test-Scenarios.xlsx
├── Movie-RTM.xlsx
└── Movie-Bug-Report.xlsx
```

---

## 🎯 Objectives
- Validate accuracy of movie browsing and searching
- Verify correct functionality of filters and categories
- Ensure movie details load properly
- Confirm add/remove favorites works as expected
- Identify defects and document them clearly
- Track requirement coverage using RTM

---

## 🧪 Modules Tested

| Module | Description |
|--------|-------------|
| Login | Authentication & validation |
| Search | Dynamic search results |
| Filters | Genre/category-based filtering |
| Movie Details | Rating, description, cast, trailer |
| Favorites | Add/remove movies |
| Dashboard | User interaction history |

---

# 📘 **1. Movie-Test-Cases.xlsx**

This file contains **detailed test cases** for all major modules.

### Included Columns
- TC ID
- Module
- Test Case Description
- Pre-condition
- Steps
- Expected Result

### Sample Entries
| TC ID | Module | Test Case Description |
|-------|--------|------------------------|
| TC01 | Login | Validate login with valid credentials |
| TC02 | Login | Validate login with invalid credentials |
| TC03 | Search | Verify search results update dynamically |
| TC04 | Filters | Validate genre filter functionality |
| TC05 | Movie Details | Ensure movie details page loads properly |
| TC06 | Favorites | Add movie to favorites |
| TC07 | Favorites | Remove movie from favorites |

---

# 📗 **2. Movie-Test-Scenarios.xlsx**

High-level test scenarios designed before writing detailed test cases.

### Sample Scenarios
| Scenario ID | Scenario Description | Module |
|--------------|----------------------|--------|
| TS01 | Validate login workflow with valid/invalid data | Login |
| TS02 | Verify search updates based on user input | Search |
| TS03 | Check genre filters functionality | Filters |
| TS04 | Validate movie details loading | Movie Details |
| TS05 | Validate add/remove favorites functionality | Favorites |

---

# 📙 **3. Movie-RTM.xlsx (Requirement Traceability Matrix)**

This RTM maps functional requirements to corresponding test cases for complete coverage.

### Sample Mapping
| Requirement ID | Requirement Description | Test Case IDs |
|----------------|-------------------------|----------------|
| REQ-01 | User login authentication | TC01, TC02 |
| REQ-02 | Search functionality | TC03 |
| REQ-03 | Genre filtering | TC04 |
| REQ-04 | Movie details loading | TC05 |
| REQ-05 | Manage favorites | TC06, TC07 |

---

# 🐞 **4. Movie-Bug-Report.xlsx**

This file contains real sample bugs found during test execution.

### Included Fields
- Bug ID  
- Title  
- Severity  
- Priority  
- Module  
- Steps to Reproduce  
- Expected Result  
- Actual Result  
- Status  

### Sample Bugs
| Bug ID | Title | Severity | Priority | Module |
|--------|--------|----------|----------|--------|
| BUG01 | Search results not updating | High | High | Search |
| BUG02 | Genre filter not working | Medium | High | Filters |
| BUG03 | Movie details page blank | Critical | High | Movie Details |

---

## 🔁 Test Execution Summary (from Summary Report)

| Metric | Value |
|--------|-------|
| Total Test Cases | 50+ |
| Passed | 40 |
| Failed | 7 |
| Blocked | 3 |
| Total Defects | 15 |

---

## 🧠 Key Learnings
- Strong understanding of functional testing methodology  
- Experience in test case design and scenario creation  
- Hands-on defect tracking and severity/priority assignment  
- Experience validating UI, search logic, and data consistency  
- Exposure to regression testing and fix verification  

---

## 🛠 Tools Used
- Excel (Documentation)
- Browser DevTools (UI validation)
- Screenshots for defect evidence

---

## 📬 Contact
**Suyog Bundiwale**  
📩 Email: suyog.bundiwale@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/suyog-bundiwale  
🐙 GitHub: https://github.com/Suyog-13  

---

⭐ *If you found this project helpful, please star the repository!*
