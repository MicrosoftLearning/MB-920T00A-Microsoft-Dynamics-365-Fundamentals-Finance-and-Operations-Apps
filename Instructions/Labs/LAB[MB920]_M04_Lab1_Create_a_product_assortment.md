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

1.  On the Finance and Operations home page, on the top left, select the **Expand the navigation pane** hamburger menu.

2.  In the navigation pane, select **Retail and Commerce** > **Catalogs and assortments** > **Assortments**.

3.  Wait for the page to load.

4.  On the **Assortments** page, select **+ New**.

5.  In the **New Record** pane, expand **General**.

6.  Select the **Effective date** box, and then select a date in the future.

7.  In the **Assortment name** box, enter a name for the new assortment. For example, **New Spring Season**.

8.  Set the **Expiration date** to **Never**.

    The expiration date can be used to automatically deactivate a published assortment.

9.  Expand **Commerce channels**.

10. On the **Commerce channels** menu, select **+ Add line**.

11. In **Choose organization nodes**, select the **Organization hierarchy** menu, and then select **Retail Stores by Type (Fabrikam)**.

12. In the **AVAILABLE ORGANIZATION NODES** list, select **Online,** and then select the **Add** ![Picture 15](../media/04-learn-the-fundamentals-of-dynamics-365-commerce-17.png) icon to add it to the **SELECTED ORGANIZATION NODES**.

    This adds to the parent node and all child nodes.

13. Add the **Mall** parent node, and then select **OK**.

14. Verify the two nodes have been added to the Commerce channels.

15. Expand **Products**.

16. On the **Products** menu, select **+ Add line**.

17. Select the **Category** menu, select **Team Sports (Team Sports)**, and then select **OK**.

    This adds all child items of the parent category.

18. Review the last column named **Line type**. By default, all items are included.

19. Select **+ Add line**, select the **Category** menu, expand **Team Sports (Team Sports)**, select **Baseball**, and then select **OK**.

20. To exclude an item from an already included larger category, in this case **Team Sports**, in the **Line type** column, change the value to **Exclude**.

21. Using the **Baseball** category row, select the **Products** menu.

22. When products within a category are defined, you can select a specific product to include or exclude. Select **AdultBaseballInfield**.

23. To remove an added product, delete contents of the product box, and then press the **Tab** key on your keyboard or select another area of the page.

24. On the top menu, select **Save**.

25. On the top menu, select **Publish**.

26. Review the information in the dialog box, and then select **Yes**.

    The newly created product assortment becomes available on the effective date.

