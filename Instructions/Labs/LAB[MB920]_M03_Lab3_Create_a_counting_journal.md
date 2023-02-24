---
lab:
    title: 'Lab 3: Create a counting journal'
    module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management

## Lab 3 - Create a counting journal

1. On the Finance and Operations home page, in the top right, verify you are working with the **USMF** company. If necessary, select the company, and from the drop down, select **USMF**.

2. In the left navigation pane, select **Modules** > **Inventory management** > **Journal entries** > **Item counting** > **Counting**.

3. Select the **+New** button in the action pane. The **Create inventory journal** dialog form will appear with the **OK** button in the bottom. Select the **OK** button.

4. The **Inventory counting journal** form will appear with header and line information.

	![Screenshot of the Inventory counting journal form with header and detail information filled in.](./media/lp-scm-m-002-warehouse-inventory-mgmt-06.png)

5. Select **Create lines -&gt; On-hand** in the action pane.

6. In the **Create on-hand counting journal** dialog pane, set the **Warehouse**, **Inventory Status**, **Location**, and **License Plate** fields to **Yes**. 

	![Screenshot of the Create on-hand counting journal dialog pane with the fields set as described.](./media/lp-scm-m-002-warehouse-inventory-mgmt-07.png)

7. Expand the **Records to include** section and select the **Filter** link. For the **Item number** field, type **A0001** in the Criteria, and then select **OK**.

8. Select **OK** in the bottom of the **Create on-hand counting journal** dialog form.

   The on-hand quantity of item A0001 will appear in the **Journal lines** section with the breakup of the Site, Warehouse, Location and License plate.

9. In the **Counted** column of the **Journal line** section, enter the numbers counted in each Site/Warehouse/Location/License plate. Note the following:

	- If the **On-hand** quantity is the same as **Counted** quantity, the **Quantity** field will be blank.

	- If the value of the **Counted** field is more than the **On-hand** field, the **Quantity** field will contain a positive value.

	- If the value of the **Counted** field is less than the **On-hand** field, the **Quantity** field will contain a negative value.

10. Select the **Validate** button in the action pane, and then select the **Post** button.

11. **Close** the page and return to the home page.
