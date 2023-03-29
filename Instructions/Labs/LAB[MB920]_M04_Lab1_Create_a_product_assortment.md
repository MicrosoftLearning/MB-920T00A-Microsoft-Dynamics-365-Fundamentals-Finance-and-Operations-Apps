---
lab:
    title: 'Lab 1: Create a product assortment'
    module: 'Module 4: Learn the Fundamentals of Microsoft Dynamics 365 Commerce'
---

# Module 4: Learn the Fundamentals of Microsoft Dynamics 365 Commerce

## Lab 1: Create a product assortment

## Objective

You need to create an assortment of related products that are assigned to a specific commerce channel that will be made available at a future date. 

## Lab Setup

   - **Estimated Time**: 10 minutes

## Instructions

1.  On the **Finance and Operations Home** page, in the top right, verify you are working with the **USMF** company. 

1.  If necessary, select the company and from the menu, select **USMF**. 

1.  In the left navigation pane, in the **Retail and Commerce** module, select **Catalogs and assortments** > **Assortments**. 

1.  On the **Assortments** page, select **+ New**. 

1.  On the **New Record** form, if necessary, expand the **General** FastTab. 

1.  Select the **Effective date** field, and then select a date in the future.  

1.  In the **Assortment name** field, enter a name for the new assortment. For example, `New Spring Season`

    > **Note:** The **Expiration date** can be used to automatically deactivate a published assortment. 

1.  Expand the **Commerce channels** FastTab. 

1.  On the **Commerce channels** toolbar, select **+ Add line**. 

1.  In the **Choose organization nodes** pane, for the **Organization hierarchy** field, select **Retail Stores by Type (Fabrikam)**. 

1.  In the AVAILABLE ORGANIZATION NODES list, select Online, and then select the Add ![Right-arrow icon](./media/d365-fo-add-org-node-icon.png) icon to add it to the **SELECTED ORGANIZATION NODES**.

    This will add the parent node and all child nodes. 

1.  Add the **Mall** parent node, and then select **OK**. 

1.  Verify the two nodes have been added to the **Commerce channels** FastTab. 

1.  Expand the **Products** FastTab. 

1.  On the **Products** toolbar, select **+Add line**. 

1.  For the **Category** field, expand **Team Sports (Team Sports),** and then select **OK**.

    This will add all child items of the parent category.

1.  Review the last column named **Line type**. By default, all items will be included.

1.  Select **+ Add line**, select the **Category** menu, expand **Team Sports (Team Sports)**, select **Baseball**, and then select **OK**. 

1.  To exclude an item from an already included larger category, in this case Team Sports, in the **Line type** column, change the value to `Exclude` 

1.  Using the Baseball category row, select the **Products** menu. 

1.  When products within a category are defined, you can select a specific product to include or exclude. Select **AdultBaseballInfield** or enter `0013` 

    > **Note:** To remove an added product, delete the contents of the **Product** field, and then press Tab or select another area of the page. 

1.  On the action pane, select **Save** and select **Publish**. 

1.  Select **Yes** on the confirmation dialog. The newly created product assortment will become available on the selected **Effective date**. 

