---
lab:
    title: 'Lab 3: Create a counting journal'
    module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management

## Lab 3: Create a counting journal

## Lab Setup

   - **Estimated Time**: 10 minutes

## Instructions

1.  On the **Finance and Operations Home** page, in the top right, verify you are working with the **USMF** company. If necessary, select the company, and from the drop-down, select **USMF**. 

2.  In the left navigation pane, in the **Inventory management** module, select **Journal entries** > **Item counting** > **Counting**. 

3.  Select the **+ New** button in the action pane. The **Create inventory journal** dialog pane will appear. Select the **OK** button. 

4.  The **Inventory counting journal** form will appear with header and line information. 

    ![Screenshot of the Inventory counting journal form with header and detail information filled in.](./media/lp-scm-m-002-warehouse-inventory-mgmt-06.png)

5.  In the action pane, select **Create lines -&gt; On-hand**. 

6.  In the **Create on-hand counting journal** dialog pane, set the **Warehouse**, **Inventory status**, **Location**, and **License plate** fields to **Yes**. 

    ![Screenshot of the Create on-hand counting journal dialog pane with the fields set as described.](./media/lp-scm-m-002-warehouse-inventory-mgmt-07.png)

7.  Expand the **Records to include** section and select the **Filter** button. For the **Item number** field, enter `A0001` in the **Criteria** field, and select **OK**. 

8.  Select **OK** at the bottom of the **Create on-hand counting journal** dialog pane. 

    The on-hand quantities of item **A0001** will appear in the **Journal lines** grid with the breakup of Site, Warehouse and Location. 

9.  In the **Counted** column of the **Journal line** section, match the numbers counted for each Site/Warehouse and Location. Note the following: 

    - If the **On-hand** quantity is the same as **Counted** quantity, the **Quantity** field will be blank. 

    - If the value of the **Counted** field is more than the **On-hand** field, the **Quantity** field will contain a positive value. 

    - If the value of the **Counted** field is less than the **On-hand** field, the **Quantity** field will contain a negative value. 

10. Change the year of the **Date** field on each line to be 2022. 

11. Select the **Validate** button in the action pane, and select **OK** in the dialog pane. 

12. Select the **Post** button. 

13. **Close** the page and return to the home page. 

