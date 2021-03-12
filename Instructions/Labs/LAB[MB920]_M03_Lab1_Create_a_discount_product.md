---
lab:
    title: 'Lab 1: Create a discount product'
    module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Commerce'
---

## Lab 1 - Create a discount product

## Objectives

Your company's Boston store is ready to drive sales of some products that need to be sold to make room for the new line. You need to create and activate a new product discount.

## Lab Setup

   - **Estimated Time**: 10 minutes

## Instructions

1. On the Finance and Operations page, in the top left, select the **Expand the navigation pane** hamburger menu.

1. In the navigation pane, select **Workspaces** > **Pricing and discount management**.

1. On the Pricing and discount management page, review the currently displayed **Active discounts**.

1. On the menu, select **New**, review the available options, and then select **Discount**.

1. On the Discounts page, in the **Name** box, enter a name for your discount. For example, New Year 20%.

1. In the General tab, verify the Status is set to **Disabled**.

1. The discount can only be edited when it is set to disabled.

1. Select the **Discount concurrency mode** menu, review the available options, and then select **Best price**.

    >[!NOTE] When choosing between the concurrency mode options, keep in mind:
    >
    >  - When multiple Compounded discounts are applicable, the highest discount will always calculate first.  The next highest discount is then calculated on the remaining amount.  This calculation hierarchy will continue until all applicable Compounded discounts have been applied.  
    >    **Correct**: 40% discount + 20% discount = 52% discount  
    >      - (40% discount on $100 = $40. Remaining = $60.  20% discount on $60 = 12. Remaining = $48)  
    >
    >    **Not Correct**: 40% discount + 20% discount = 60% discount
    >
    >  - Exclusive discounts will always apply over a Best price or Compounded discount, even if it is the lowest discount percentage.
    >    - When more than one Exclusive discount is applicable, the highest will be used.
    >  - When Best price and Compounded are both applicable or if multiple of the same one is applicable, the highest discount will be used.

1. Select the **Discount account** menu and review the list.

1. In the Discount account box, enter **discount**.

1. The list will automatically filter.

1. In the results, select the Discount account number **403200**.

1. Review the other options, and then expand **Details**.

1. In the **Description** box, enter a description for the discount. For example, New Year discount offering 20% off.

1. Expand **Price/discount**.

1. In the Discount percentage box, enter **20.00**.

1. Expand **Validation period**.

1. Set the **Effective date** and **Expiration date** for the discount.

1. Be sure to set the expiration date in the future, otherwise the discount will not be shown in the Active discounts list.

1. Expand **Lines**.

1. On the menu, select **+ Add.**

1. Select the **Category** menu, and then select **Fashion (Fashion)**.

1. This will apply the discount to all products in the Fashion category.

1. Expand **Line details** and then, in the **Description** box, enter a description for the product lines. For example, All products in the Fashion category will be included in the discount.

1. At the top of the page, on the menu, select **Price groups**.

1. On the Price groups page, select the **Price group** menu.

1. Review the available price groups, select **Boston price group**, and then select **Save**.

1. In the top right of the Price groups page, select the **Close** icon.

1. On the Discounts page, in the Details tab, select the **Status** menu, and then select **Enabled**.

1. Notice discount settings can no longer be edited.

1. Save your changes, and then close the Discount page.

1. On the Pricing and discount management page, review the Active discounts tab, and verify your newly added discount is shown at the bottom of the list.

1. If necessary, in the top right, select the **Refresh** icon to refresh the discounts list.
