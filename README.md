# Consolidate User Accounts – User Story

## 📌 Project Overview
This project documents the **user story, wireframe/UI requirements, and workflow** for the **Consolidate User Accounts** feature for Lincoln Financial Group customers.  
The feature allows eligible users to consolidate their Mutual Fund Accounts into their Legacy Brokerage Accounts, providing a simpler investing experience by viewing all assets under one account.

---

## 📖 User Story

**Title:** Consolidate User Accounts  
**As a:** Logged-in Lincoln Financial Group customer eligible for account consolidation  
**I want to:** Consolidate my Mutual Fund Account into my Legacy Brokerage Account  
**So that:** I can have a simpler investing experience where I can view all my assets under one account

### Acceptance Criteria
1. For every user eligible for account consolidation, the system displays a **‘Consolidate Your Account’** hyperlink on the **Accounts Overview** page.  
2. On click of **‘Consolidate Your Account’** hyperlink, the system navigates the user to the **Consolidate Your Account** page in the same browser window.  
3. The **Consolidate Your Account** page shall display all eligible Mutual Fund Account(s) and the associated Legacy Brokerage Account(s) with the same registration type.  
4. System shall allow the user to select **one or more or all eligible Mutual Fund Accounts** available for consolidation.  
5. On click of **Continue** button:  
   5.1. If one or more eligible accounts are selected, system navigates the user to the **Review & Submit** page.  
   5.2. If no eligible accounts are selected, system displays the following inline error message:  
   **“Please select an eligible Mutual Fund Account to continue.”**  
6. On click of **Cancel** button, system navigates the user back to the **Accounts Overview** page.

---

## 🖼 Wireframe & UI Requirements

| ID | Field Name | Field Type | Content | Default Selection |
|----|------------|------------|---------|-----------------|
| 1 | Page Title | Text | Consolidate Your Account | N/A |
| 2 | Note | Text | We've found that you have mutual fund and brokerage accounts registered to the same owner(s). If you'd like to consolidate these accounts for a simpler investing experience, select the mutual fund account and we'll consolidate it with your brokerage account. If you'd prefer to keep these accounts separate, simply do nothing on this screen. | N/A |
| 3 | Mutual Fund Accounts Available to Consolidate | Check Box | <Account Type> | Unchecked |
| 4 | Brokerage Accounts | Text | <Account Type-Account Number> | N/A |
| 5 | Continue | Command Button | Continue | N/A |
| 6 | Cancel | Command Button | Cancel | N/A |

---

## 🔄 Workflow
The workflow for this feature includes:
1. User clicks **‘Consolidate Your Account’** hyperlink from Accounts Overview page.  
2. System displays the **Consolidate Your Account** page with all eligible Mutual Fund Accounts and associated Brokerage Accounts.  
3. User selects one or more Mutual Fund Accounts to consolidate.  
4. User clicks **Continue**:  
   - If selection is valid → navigate to **Review & Submit** page.  
   - If no selection → display error message.  
5. User clicks **Cancel** → system navigates back to **Accounts Overview** page.

---

## 👤 Author
**Saad Elboukhali**

---

## ⭐ Notes
This project can be extended by:
- Adding **UML wireframes / flow diagrams**  
- Developing a **functional prototype**  
- Including additional **validation scenarios and edge cases**
