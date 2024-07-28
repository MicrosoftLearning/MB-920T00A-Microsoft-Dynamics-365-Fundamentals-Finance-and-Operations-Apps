---
lab:
    title: 'Lab 1: Create a main account'
    module: 'Learning Path 2: Learn the Fundamentals of Microsoft Dynamics 365 Finance'
---

# Learning Path 2: Module 2: Learn the fundamentals of Microsoft Dynamics 365 Finance
# Module 2: Describe general ledgers

## Lab 2.1: Create a main account

## Lab Setup

   - **Estimated Time**: 5 minutes

## Objective

In this lab, you will perform the following activities:

1. Create a legal entity.

2. Create a fiscal calendar.

3. Create a chart of accounts.

4. Create main accounts in the chart of accounts.

5. Create an operating unit of type department and cost center.

6. Create an accounting structure by using the main accounts and cost centers.

7. Configure the ledger.

# Lab steps

## Create a legal entity

1. In the left navigation pane of Dynamics 365 Finance, select **Modules** **&gt;** **Organization administration** **&gt; Organizations &gt; Legal entities**.

2. On the **Legal entities** page, select the **New** button in the action pane to create a new legal entity, and enter the following information:

	- Name: **Contoso Demo Systems**

	- Company: **CDS**

	- Country/region: **USA**

3. Select **OK** at the bottom.

## Create a fiscal calendar

1. In the left navigation pane of Dynamics 365 Finance, select **Modules** **&gt;** **General ledger** **&gt; Calendars &gt; Fiscal calendars**. 

2. On the **Fiscal calendar** page, select the **New calendar** button in the action pane to create a new fiscal calendar, and enter the following information:

	- Calendar: **CDS**

	- Description: **Demo systems calendar**

	- Start of fiscal year: **10/1/2023**

	- End of fiscal year: **9/30/2023**

	- Fiscal year name: **2023-24**

	- Length of period: **1**

	- Unit: **Months**

3. Select the **Create** button.

The system will generate 14 periods, including one opening and one closing period and 12 periods for 12 months.

## Create a chart of accounts

1. In the left navigation pane of Dynamics 365 Finance, select **Modules** > **General ledger** **&gt;** **Chart of accounts** **&gt; Accounts &gt; Chart of accounts**.

2. On the **Chart of accounts** page, select the **New** button in the action pane to create a new chart of accounts, and enter the following information:

	- **Charts of accounts**: Demo systems

	- **Description**: Contoso demo systems

3. Select the **New** button on the **Main accounts** FastTab to create main accounts with the following values:

	- Main account: **1000**

	- Name: **Cash**

	- Main expense type: **Balance sheet**

	- Main account category: **CASH**

	- DB/CR default: **Debit**

4. Create another main account:

	- Main account: **3000**

	- Name: **Revenue**

	- Main expense type: **Revenue**

	- Main account category: **REV**

	- DB/CR default: **Credit**

5. Create another main account:

	- Main account: **6000**

	- Name: **Travel expense**

	- Main expense type: **Expense**

	- Main account category: **EXP**

	- DB/CR default: **Debit**

##  Create an operating unit

1. Navigate to **Modules** **&gt;** **Organization administration** **&gt; Organizations &gt; Operating units**.

2. In the action pane, select the **New** button followed by the **Department operating** unit type and enter following the following value:

	- Name: **CDS_Training**

3. In the action pane, select the New button followed by the Cost center operating unit type and enter following value:

	- Name: **CDS_Purchase**

4. Add two more cost centers: **CDS_IT** and **CDS_Admin**.

## Create an accounting structure

1. On the **Finance and Operations Home** page, in the upper right, verify you are working with the **CDS** company.

2. If necessary, select the company, and from the menu, select **CDS**.

3. In the left navigation pane of Dynamics 365 Finance, select **Modules** > **General ledger** **&gt;** **Chart of accounts &gt; Structures &gt; Configure account structures**.

4. In the action pane, select the **New** button to create a new account structure with the following values:

	- Account structure: **CDS_BS**

	- Description: **CDS Balance sheet**

	- Add main account: **YES**

5. Select the **Create** button.

6. On the **Segments and allowed values** FastTab, select the **Add** button to add **Main Account range 1000..2999**.

7. Select the **Activate** button in the action pane followed by the **Activate** button in the batch processing dialog.

8. In the action pane of the **Account structures** page, select the **New** button to create another account structure with the following values:

	- Account structure: **CDS_Revenue**

	- Description: **CDS Revenue**

	- Add main account: **YES**

9. Select the **Create** button.

10. On the **Segments and allowed values** FastTab, select the **Add** button to add **Main Account range 3000..5999**.

11. Select the **Activate** button in the action pane followed by the **Activate** button in the batch processing dialog.

12. In the action pane of **the Account structures** page, select the **New** button to create another account structure with the following values:

	- Account structure: **CDS_Expense**

	- Description: **CDS Expense**

	- Add main account: **YES**

13. Select the **Create** button.

14. On the **Segments and allowed values** FastTab, select the **Add** button to add **Main Account range 6000..9999**.

15. Select the **Segment** button on the **Segments and allowed values** FastTab

16. In the **Add segment** dialog, select **CostCenter** followed by the **Add segment** button.

17. In the **CostCenter** field, enter **253..255**. 

18. Select the **Activate** button in the action pane followed by the **Activate** button in the batch processing dialog.

## Configure the ledger

1. On the **Finance and Operations Home** page, in the upper right, verify you are working with the **CDS** company.

2. If necessary, select the company, and from the menu, select **CDS**.

3. In the left navigation pane of Dynamics 365 Finance, select **Modules** > **General ledger &gt; Setup &gt; Ledger page** and configure the following:

	- Chart of accounts: **Demo systems**

	- Fiscal calendar: **CDS**

	- Accounting currency: **USD**

	- Reporting currency: **USD**

	- Accounting currency exchange rate type: **Default**

	- Budget exchange rate type: **Budget**

4. On the **Account structure** FastTab, select the **Add** button to add the account structure **CDS_BS**.

5. Add two more account structures: **CDS_Revenue** and **CDS_Expense**.

This completes the basic configuration of the General ledger module. You can plan your journal configuration now to post journals. 

 
