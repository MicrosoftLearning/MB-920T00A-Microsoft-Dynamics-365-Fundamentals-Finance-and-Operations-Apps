---
lab:
    title: 'Lab 5: Create a warehouse'
    module: 'Module 1: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Module 1: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management

## Lab 5 - Create a warehouse

## Objectives
The Warehouse management system in Supply Chain Management gives you flexible ways to define your warehouse layout to meet changing needs, so that you can achieve optimal warehouse efficiency.

- You can establish high-priority and low-priority storage areas for optimum placement of goods.
- You can divide your warehouse into zones to accommodate various storage needs, such as temperature requirements, or various turnover rates for items.
- You can specify warehouse locations on any level (for example, site, warehouse, aisle, rack, shelf, and bin position).
- You can group locations by using physical capacity constraint settings.
- You can control how items are stored and picked, based on query-defined rules.

To use warehouse management in Supply Chain Management, you must create a warehouse and enable it for more advanced or specialized warehouse management activities.

## Lab Setup

   - **Estimated Time**: 10 minutes

## Instructions

1. On the Finance and Operations Home page, in the top right, verify you are working with the USMF company.

1. If necessary, select the company, and from the menu, select **USMF**.

1. In the left navigation pane, select **Modules** > **Inventory management** > **Setup** > **Inventory breakdown** > **Warehouses**.

    ![Screen image displaying Warehouses module navigation](./media/lp1-m3-warehouses-module-navigation.png)

1. On the Warehouses page, in the top menu, select **New**.

1. In the **Warehouse** field, enter **101**.

1. In the **Name** field, enter **Overflow Warehouse**.

1. Select the **Site** menu, and then select **3 Home foam production**.

1. Expand **Location names**.  
    The options in this section define the default format for location names.

1. Set the **Include aisle** and **Include rack** options to **Yes**.

1. In the **Format** box, for the rack, enter a value.  
    For example, if the format of the rack location name must contain OVFL, you would enter that value in the Format box.

1. Under **LEVEL**, set the **Include shelf** option to **Yes**.

1. In the **Format** field, for the shelf, enter **-##**.

1. On the top menu, select **Warehouse**.

    ![Screen image displaying the Warehouse menu option highlighted](./media/lp1-m3-warehouses-menu-option.png)

1. Under **Maintain**, select **Location Wizard**.

1. On the Welcome page, review the information and then, in the lower right corner, select **Next**.

1. Clear the **Outbound docks** and **Bulk locations** checkboxes.

1. Select **Next** and review the information.

1. Continue to each page and then, when complete, select **Finish**.

1. Close the page and return to the Home page.
