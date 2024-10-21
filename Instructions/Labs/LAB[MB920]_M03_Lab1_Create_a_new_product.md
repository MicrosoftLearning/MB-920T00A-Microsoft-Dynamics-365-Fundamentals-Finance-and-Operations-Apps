---
lab:
    title: 'Lab 3.1: Create a new product'
    module: 'Learning Path 3: Learn the fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Learning Path 3: Learn the fundamentals of Microsoft Dynamics 365 Supply Chain Management
# Module 2: Describe the sales and procurement process

## Lab 3.1: Create a new product

In your organization, you plan to create a new item, which is a shirt. The shirt will have different colors and sizes. In this lab, you learn how to create a new item with multiple variants and release it in the legal entity USMF.

## Lab steps

1. In the Dynamics 365 Supply Chain Management navigation pane, select **Modules**, and then select **Product information management** > **Setup** > **Dimension and variant groups**. Open the **Color groups** page and create a new record.

	- Color group: **ShirtColor**

	- Description: **Shirt color**

2. On the **Color group lines** FastTab, enter the following three records:

	| **Color** | **Color name** |
	|-----------|----------------|
	| Blue      | Blue           |
	| White     | White          |
	| Black     | Black          |


3. Save the records.

4. Select **Product information management** > **Setup** > **Dimension and variant groups**. Open the **Size groups** page and create a new record.

	- Size group: **ShirtSize**

	- Description: **Shirt size**

5. In the **Size group lines** FastTab, enter the following three records

	| **Size** | **Size name** |
	|----------|---------------|
	| S        | Small         |
	| M        | Medium        |
	| L        | Large         |


6. Save the records

7. In the Dynamics 365 Supply Chain Management navigation pane, select **Modules**, and then select **Product information management**. Then on the **Products** menu, select **Product masters**.

8. On the **Product masters** page, in the upper menu, select **+ New**.

9. On the **New product** page, in the **Product type** field, verify that **Item** is selected.

10. In the **Product subtype** field, verify that **Product** **master** is selected.

11. Under the **Identification** tab, in the **Product number** box, enter **SH001**.

12. In the **Product name** field, enter **Shirt**.

13. In the **Product dimension group** field, enter **ColorSize**.

14. Select the **OK** button.

15. Under the **Product** menu in the action pane, select **Dimension groups** under the **Set up** group.

16. In the **Storage dimension group** drop-down list, select **SiteWH**.

17. In the **Tracking dimension group** drop-down list, select **None**.

18. Select the **OK** button.

19. Select **ShirtColor** in the **Color group** list.

20. Select **ShirtSize** in the **Size group** list.

21. Select the **Product variants** button in the action pane.

22. On the **Product variants** page, select the **Variant suggestions** button in the action pane.

23. Select the **Suggest all** button on the **Variant suggestions** page.

24. Select the suggested variants by selecting the **Select all** button followed by the **Create** button.

Variants will be created on the Product variants page.

25. Select the **Release products** button in the action pane to release the product in a legal entity.

26. A page opens displaying the first step as **Select products to release**.

27. Select the **Next** button at the bottom of the page.

28. Select the variants you want to release in the legal entity and select the **Next** button.

29. On the **Select companies to release to** page, select the **USMF** legal entity where the product should be released.

30. Select the **Next** button at the bottom of the page.

31. On the **Confirm selection** page, set the value of **Show Infolog upon failure** as **Yes** and **Run as batch** as **No**.

32. Select the **Finish** button at the bottom of the page.

33. In the top right,switch to **USMF** as the legal entity.

34. In the navigation pane, select **Modules**, and then select **Product information management**. Then on the **Products** menu, select **Released products**.

33. On the **Release products** page, locate the new item **SH001** in the grid.

34. Select the product link and navigate to the **Released product details** page.

35. On the **General** FastTab, enter the following:

	- Item model group: **FIFO**

36. On the **Purchase** FastTab, enter the following:

	- Unit: **ea**

	- Item sales tax group: **ALL**

	- Price: **30**

37. On the **Sell** FastTab, enter the following:

	- Unit: **ea**

	- Item sales tax group: **ALL**

	- Price: **35**

38. On the **Manage inventory** FastTab, enter the following:

	- Unit: **ea**

39. On the **Engineer** FastTab, enter the following:

	- BOM Unit: **ea**

40. On the **Manage costs** FastTab, enter the following:

	- Item group: **Audio**

41. To complete the configuration, select **Product** in the action pane. Select the **Validate** button under the **Maintain** group.

42. Close all pages and return to the **Home** page.

 
