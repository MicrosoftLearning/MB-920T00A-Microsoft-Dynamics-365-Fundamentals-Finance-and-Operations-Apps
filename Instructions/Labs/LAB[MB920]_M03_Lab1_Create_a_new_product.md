---
lab:
    title: 'Lab 1: Create a new product'
    module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management

## Lab 1: Create a new product

## Objective

In Contoso Entertainment System USA (USMF), you need to create a new item for a new configuration of cabinet to be purchased from vendors. 

## Lab Setup

   - **Estimated Time**: 10 minutes

## Instructions

1.  On the **Finance and Operations Home** page, in the top right, verify you are working with the **USMF** company. 

1.  If necessary, select the company and from the menu, select **USMF**.

1.  In the top left, select the **Expand the navigation pane** hamburger menu. 

1.  In the navigation pane, in the **Product information management** module, select **Products** > **Released products**. 

1.  On the **Released product details** page, select **+ New** in the action pane. 

1.  In the **New released product** pane, for the **Product type** field, verify **Item** is selected. 

1.  In the **Product subtype** field, verify **Product** is selected. 

1.  Select the **Tracking dimension group** menu, and enter or select `None` 

1.  Under **IDENTIFICATION**, for the **Product number** enter `GTL007`

1.  In the **Product name** box, enter `Cabinet 2`

1.  Under **REFERENCE GROUPS**, in the **Item model group** field, enter or select `FIFO`, First In-First Out. 

1.  For the **Item group** field,  enter or select `TV&Video` 

1.  For **Storage dimension group**, enter or select `SiteWH` 

1.  Under **UNITS OF MEASURES**, verify the following values are set: 

    | **Setting**    | **Value** |
    | :------------- | :-------- |
    | Inventory unit | ea Each   |
    | Purchase unit  | ea Each   |
    | Sales unit     | ea Each   |
    | BOM unit       | ea Each   |

1.  Under **SALES TAXATION**, for **Item sales tax group**, enter or select `ALL` 

1.  Under **PURCHASE TAXATION**, for **Item sales tax group**, enter or select `ALL` 

1.  Under **PRICES**, in the **Purchase price** field, enter `30.00`

1.  In the **Sales price** field, enter `30.00`

1.  Verify your new **Released product** looks like this: 

    ![Screen image displaying the completed new release product form](./media/lp1-m2-new-release-product.png)

1.  Select **OK**. 

1.  To ensure the product is finalized, on the action pane, under **Maintain**, select the **Validate** action. 

    ![Screen image displaying the ribbon bar with Validate highlighted](./media/lp1-m2-validate-ribbon-bar.png)

1.  Verify you are presented with the notification confirming that all field values required were validated. 

    ![Screen image of information notification that all required fields have been validated](./media/lp1-m2-confirmation-of-validation.png)

1.  Select **Save** and **close** all pages and return to the Home page. 

