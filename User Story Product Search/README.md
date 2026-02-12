# 🔎 Product Search – Manual Testing Project

## 📌 Project Overview
This is a **self-assigned Manual Testing project** for the **Product Search feature** of an eCommerce website.

The goal of this project is to demonstrate:
- Requirement analysis
- Writing structured manual test cases
- Applying Boundary Value Analysis
- Positive & Negative testing
- Functional test coverage based on Acceptance Criteria

---

## 👤 User Story

**As a user,**  
I want to search for products using keywords,  
So that I can quickly find the items I am interested in.

---

## ✅ Acceptance Criteria

- The search bar should be prominently placed and visible on any page.
- The search bar should allow entry of at least 50 characters.
- Search should be initiated when:
  - Pressing the **Enter** key
  - Clicking the **Search** button
- Search results should display matching products.
- If no products match:
  - Show **"No products found"**
  - Display related suggestions.
- Each product result should show:
  - Product name
  - Price
  - Thumbnail image
  - Brief description
- Clicking a product navigates to the product detail page.
- Users can filter results by:
  - Category
  - Price range
  - Ratings
  - Brand
- Logged-in users should have search history saved.

---

## 🧪 Scope of Testing

The following types of testing were applied:

- Functional Testing
- Boundary Value Analysis
- Negative Testing
- Input Validation Testing
- UI Verification Testing

---

## 📝 Test Scenarios Covered

1. Verify presence of search bar
2. Boundary testing (Below minimum, At minimum, Above minimum)
3. Valid keyword search
4. No product found scenario
5. Search result UI verification
6. Navigation to product details page
7. Filter functionality
8. Search history for logged-in users
9. Guest user search history validation
10. Empty input
11. Spaces-only input
12. Numeric-only input
13. Special character input

---

## 🧠 Test Design Techniques Used

- Boundary Value Analysis (BVA)
- Positive & Negative Testing
- Equivalence Partitioning (for input types)
- UI Validation

---

## 🛠 Technologies Used (Demo Implementation)

- HTML
- CSS
- JavaScript
