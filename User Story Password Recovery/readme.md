<div align="center">

# 🔐 Password Recovery – Manual Testing Project

![Manual Testing](https://img.shields.io/badge/Testing-Manual-blue)
![QA Portfolio](https://img.shields.io/badge/Project-QA%20Portfolio-green)
![Status](https://img.shields.io/badge/Status-Completed-success)
![ISTQB Aligned](https://img.shields.io/badge/ISTQB-CTFL%204.0-orange)

**Authentication Flow Validation • Security Considerations • Functional Testing**

</div>

---

## 📌 Project Overview

This is a **self-assigned Manual Testing project** focused on the  
**Password Recovery feature** of an eCommerce system.

The goal of this project is to demonstrate:

- ✅ Requirement Analysis  
- ✅ Acceptance Criteria Coverage  
- ✅ Structured Manual Test Case Writing  
- ✅ Positive & Negative Testing  
- ✅ Boundary & Input Validation  
- ✅ Basic Security Scenario Testing  

---

## 👤 User Story

> **As a registered user,**  
> I want to recover my password if I forget it,  
> So that I can securely regain access to my account.

---

## ✅ Acceptance Criteria

- "Forgot Password" link must be visible on Login page  
- Clicking the link redirects to Password Recovery page  
- User can submit a registered email address  
- System sends password recovery email with secure reset link  
- Reset link must be:
  - 🔹 Unique  
  - 🔹 One-time use  
  - 🔹 Expired after 24 hours  
- User must enter:
  - New Password  
  - Confirm Password  
- Password validation rules must apply  
- Successful reset redirects user to Login page  
- Success confirmation message must be displayed  

---

## 🧪 Scope of Testing

The following areas were validated:

- UI visibility (Forgot Password link)  
- Navigation flow  
- Email validation (format & registration status)  
- Reset email behavior  
- Link expiration validation  
- One-time link usage  
- Password strength validation  
- Confirm password matching  
- Success redirection behavior  
- Negative & edge cases  

---

## 📝 Test Scenarios Covered

1. Verify presence of "Forgot Password" link  
2. Verify navigation to Password Recovery page  
3. Submit valid registered email  
4. Submit unregistered email  
5. Submit invalid email format  
6. Submit empty email field  
7. Verify reset link expiration (24h rule)  
8. Verify reset link cannot be reused  
9. Password & Confirm Password mismatch  
11. Successful password reset  
12. Redirect to Login after reset  

---

## 🧠 Test Design Techniques Used

- 🔹 Positive Testing  
- 🔹 Negative Testing  
- 🔹 Input Validation Testing  
- 🔹 Basic Security Testing  

---

## 📂 Test Artifacts

| Artifact | Description |
|----------|------------|
| 📊 Manual Test Cases | Documented in Excel |
| 📄 User Story & Acceptance Criteria | Requirement documentation |
| 💻 UX Mock | Password Recovery HTML prototype |
| 📧 Email Template | Password Reset email mock |

---

## 🛠 Tools & Technologies

- **Excel** – Test case documentation  
- **HTML** – UX & email mockups  
- **Git & GitHub** – Version control & portfolio hosting  

---

## 📎 Notes

- This is a **QA portfolio practice project**.  
- No real production system or customer data was used.  
- Focus is on **test design quality, requirement coverage, and structured documentation**.  

---

<div align="center">

⭐ If you find this project interesting, check out my other QA testing projects in my profile.

</div>
