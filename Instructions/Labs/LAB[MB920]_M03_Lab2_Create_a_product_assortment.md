---
lab:
    title: 'Lab 2: Create a product assortment'
    module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Commerce'
---

## Lab 2 - Create a product assortment

## Objectives

You need to create an assortment of related products that are assigned to a specific commerce channel that will be made available at a future date.

## Lab Setup

   - **Estimated Time**: 10 minutes

## Instructions

1. On the Finance and Operations page, in the top left, select the **Expand the navigation pane** hamburger menu.

1. In the navigation pane, select **Retail and Commerce** > **Catalogs and assortments** > **Assortments**.

1. Wait for the page to load.

1. On the Assortments page, select **+ New**.

1. In the New Record pane, expand **General**.

1. Select the **Effective date** box, and then select a date in the future.

1. In the **Assortment name** box, enter a name for the new assortment. For example, **New Spring Season**.

1. Set the **Expiration date** to **Never**.

1. The expiration date can be used to automatically deactivate a published assortment.

1. Expand **Commerce channels**.

1. On the Commerce channels menu, select **+ Add line**.

1. In Choose organization nodes, select the **Organization hierarchy** menu, and then select **Retail Stores by Type (Fabrikam)**.

1. In the AVAILABLE ORGANIZATION NODES list, select Online, and then select the Add ![Right-arrow icon](./media/d365-fo-add-org-node-icon.png) icon to add it to the **SELECTED ORGANIZATION NODES**.  
  This will add the parent node and all child nodes.

1. Add the **Mall** parent node, and then select **OK**.

1. Verify the two nodes have been added to the Commerce channels.

1. Expand **Products**.

1. On the Products menu, select **+ Add line**.

1. Select the **Category** menu, select **Team Sports (Team Sports),** and then select **OK**.

1. This will add all child items of the parent category.

1. Review the last column named **Line type**. By default, all items will be included.

1. Select **+ Add line**, select the **Category** menu, expand **Team Sports (Team Sports)**, select **Baseball**, and then select **OK**.

1. To exclude an item from an already included larger category, in this case Team Sports, in the Line type column, change the value to **Exclude**.

1. Using the Baseball category row, select the **Products** menu.

1. When products within a category are defined, you can select a specific product to include or exclude. Select **AdultBaseballInfield**.

1. To remove an added product, delete contents of the product box, and then press the Tab key on your keyboard or select another area of the page.

1. On the top menu, select **Save**.

1. On the top menu, select **Publish**.

1. Review the information in the dialog box, and then select **Yes**.

1. The newly created product assortment will become available on the effective date.
