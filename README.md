# 🧪 Manual Testing Project — Gini App

A structured manual testing project covering the **Gini mobile application**, including test case design, bug reporting, and UI/UX evaluation. This project demonstrates practical QA skills applicable to real-world software testing roles.

---

## 📌 Project Overview

| Field | Details |
|---|---|
| **Application Under Test** | Gini App (Mobile) |
| **Testing Type** | Manual Testing |
| **Modules Covered** | Login, Registration, UI/UX |
| **Deliverables** | Test Cases, Bug Reports |
| **Tester** | Ahmad Salah |

---

## 🎯 Scope

### In Scope
- **Login Module** — Valid/invalid credentials, error messages, session handling
- **Registration Module** — Field validation, required fields, duplicate accounts
- **UI/UX Review** — Layout consistency, usability, responsiveness, accessibility

### Out of Scope
- Backend/API testing
- Performance testing
- Automated testing

---

## 📁 Project Structure

```
Manual-Testing-Project/
│
├── Gini app report - Login_Registeration.pdf   # Test cases & bug report for Login/Registration
├── Gini app report - Ui_ux.pdf                 # UI/UX evaluation report
└── README.md                                   # Project documentation
```

---

## 📋 Test Cases Summary

### Login Module
| Test Case ID | Description | Type | Status |
|---|---|---|---|
| TC-LGN-001 | Login with valid credentials | Positive | ✅ Pass |
| TC-LGN-002 | Login with invalid password | Negative | ✅ Pass |
| TC-LGN-003 | Login with empty email field | Negative | ✅ Pass |
| TC-LGN-004 | Login with empty password field | Negative | ✅ Pass |
| TC-LGN-005 | Login with unregistered email | Negative | ✅ Pass |
| TC-LGN-006 | Password field masking | UI | ✅ Pass |

### Registration Module
| Test Case ID | Description | Type | Status |
|---|---|---|---|
| TC-REG-001 | Register with valid data | Positive | ✅ Pass |
| TC-REG-002 | Register with already used email | Negative | ✅ Pass |
| TC-REG-003 | Register with invalid email format | Negative | ✅ Pass |
| TC-REG-004 | Register with weak password | Negative | ✅ Pass |
| TC-REG-005 | Register with mismatched passwords | Negative | ✅ Pass |
| TC-REG-006 | Register with all empty fields | Negative | ✅ Pass |

---

## 🐛 Bug Report Summary

| Bug ID | Module | Severity | Priority | Status | Summary |
|---|---|---|---|---|---|
| BUG-001 | Login | High | High | Open | No error message shown for wrong password |
| BUG-002 | Registration | Medium | Medium | Open | Password strength indicator missing |
| BUG-003 | UI/UX | Low | Low | Open | Button alignment inconsistent on smaller screens |
| BUG-004 | Login | Medium | High | Open | "Forgot Password" link not functional |

> Full bug details (steps to reproduce, expected vs actual results, screenshots) are available in the PDF reports.

---

## 🔍 Testing Approach

- **Equivalence Partitioning** — Input fields divided into valid and invalid classes
- **Boundary Value Analysis** — Min/max character limits tested for all fields
- **Exploratory Testing** — Unscripted testing to discover unexpected behavior
- **UI/UX Heuristic Evaluation** — Assessed against Nielsen's usability heuristics

---

## 🧰 Tools Used

- **Test Documentation:** Microsoft Excel / Google Sheets
- **Bug Reporting:** Manual report (PDF)
- **Device:** Android Mobile
- **Version Control:** GitHub

---

## 📄 Reports

| Report | Description | Link |
|---|---|---|
| Login & Registration Report | Test cases and bugs for auth module | [View PDF](./Gini%20app%20report%20-%20Login_Registeration.pdf) |
| UI/UX Report | Usability and interface evaluation | [View PDF](./Gini%20app%20report%20-%20Ui_ux%20.pdf) |

---

## 👤 About the Tester

**Ahmad Salah** — Junior QA Engineer with hands-on experience in manual testing, test case design, and bug reporting. Familiar with SDLC, STLC, and Agile methodologies.

---

## 📬 Contact

Feel free to connect on [https://www.linkedin.com/in/ahmad-salah-a33319351/?locale=en) or reach out via GitHub for any questions about this project.
