---
lab:
    title: 'Lab 1: Create a main account'
    module: 'Module 2: Learn the Fundamentals of Microsoft Dynamics 365 Finance'
---

# Module 2: Learn the Fundamentals of Microsoft Dynamics 365 Finance

## Lab 1: Create a main account

## Lab Setup

   - **Estimated Time**: 5 minutes

## Instructions


1.  On the **Finance and Operations Home** page, in the upper right, verify you're working with the **USMF** company.

2.  If necessary, select the company, and from the menu, select **USMF**.

3.  In the left navigation pane, select **Modules** > **General ledger** > **Chart of accounts** > **Accounts** > **Main accounts**.

4.  On the action pane, select **+ New**.

5.  Enter the following values on the **Main account** page:

	- Main account: **601510**

	- Name: **International call expense**

	- Main expense type: **Expense**

	- Main account category: **TANDEEXP**

	- DB/CR default: **Debit**

    ![Screenshot depicts Main accounts - chart of accounts: Shared page where different values need to be added.](./Labs/media/lab-create-a-main-account-01.png)

6.  Navigate to **Modules &gt; General ledger &gt; Journal entries &gt; General journals.**

7.  On the action pane, select **+ New**.

8.  Enter the following value on the **General journals** page and select **Lines** on the action pane:

	- Name: GenJrn

9.  Enter the following values on the **Journal voucher** page:

	- Account type: **Ledger**

	- Main account: **601510**

	- Debit: **10.00** 

	- Offset account type: **Ledger**

	- Offset account number: **110180** 

10. Select the **Save** button in the action pane.

11. Select **Validate &gt; Simulate posting**. 

12. Select the **Post** button in the action pane. The journal should get posted.
