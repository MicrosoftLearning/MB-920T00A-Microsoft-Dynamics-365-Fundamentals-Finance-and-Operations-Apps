---
lab:
    title: 'Lab 3.2: Create a production order'
    module: 'Learning Path 3: Learn the fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Learning Path 3: Learn the fundamentals of Microsoft Dynamics 365 Supply Chain Management
# Module 4: Describe the manufacturing process

## Lab 3.2: Create a production order

## Objective

Production orders help to initiate the production process in Supply Chain Management. In this lab, you become familiar with the user interface and functionality of the Production order form. Also, you learn how to create and process a production order by the end of the exercise.

## Lab steps

1. On the Dynamics 365 **Supply Chain Management home** page, in the top right, verify you're working with the **USMF** company.

2. If necessary, select the company and from the menu, select **USMF**.

3. In the left navigation pane, select **Modules** > **Production control** > **Production orders** > **All production orders**.

4. On the top menu, select **New production order** and enter following data.

	- Item number: **D0002**

	- Quantity: **10**

	- Site: **1**

	- Warehouse: **11**

	- Delivery: [select a date one month from today's date]

	- BOM number: **D0002BOM**

	- Route number: **000004**

5. Select the **Create** button.

A new production order is created for 10 quantities of the item D0002.

6. Select **Production order (action pane menu) &gt; Process &gt; Estimate.**

7. In the **Estimation** dialog box, select **Standard** in the **Profit-setting** field, select the **References field**, and select the **OK** button.

The **Status** of the production order will change to **Estimated**.

8. Select **Schedule (action pane menu) &gt; Production order &gt; Schedule operations.**

9. In the **Operations scheduling** dialog box, select **Forward from today** in the **Scheduling direction** field and select the **OK** button.

10. Select **View (action pane menu) &gt; Related information &gt; Capacity reservation**.

11. Verify the new records created on the **Capacity reservation** page.

12. Navigate back to the **All production orders** page. Note that the **Status** of the production order changes to **Scheduled**.

13. Select **Production order (action pane menu) &gt; Process &gt; Release**.

14. In the **Release** dialog box, select the **References field** and select the **OK** button.

15. The **Status** of the production order will change to **Released**.

16. Select **Production order (action pane menu) &gt; Process &gt; Start**.

17. In the **Start** dialog box, select the **General** tab.

18. On the **General** tab, enter the following.

	- Date: **Today’s date**

	- Quantity: **10**

	- Start production: **YES**

	- Post route card now: **NO**

	- Post picking list now: **NO**

19. Select the **OK** button.

The **Status** of the production order changes to **Started**.

20. Select **View (action pane menu) &gt; Journals &gt; Picking list**.

A new picking list journal is created with three lines.

21. Post the picking list journal.

22. Navigate back to the **All production orders** page and select **View (action pane menu) &gt; Journals &gt; Route card**.

A new route card journal is created with three lines.

23. Select the **Operation completed** field in all three lines and post the route card journal.

24. Navigate back to the **All production orders** page and select **Production orders (action pane menu) &gt; Process &gt; Report as finished**.

25. In the **Report as finished** dialog box, enter **10** in the **Good quantity** field. Select the **End job** field and select **OK**.

The **Status** of the production order changes to **Ended**. The stock of the item **D0002** increases by 10 in site 1 and warehouse 11.

26. Select **Manage costs (action pane menu) &gt; Calculations &gt; View calculation details**.

Note the final costing of the manufactured item on the **Overview costing** tab.

 
