---
lab:
    title: 'Lab 2: Create a purchase order'
    module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management

## Lab 2: Create a purchase order

## Lab Setup

   - **Estimated Time**: 15 minutes

## Objective

In this lab, you become familiar with the user interface and the different fields available in the purchase order form. You also learn how to create a new purchase order.


## Lab Setup

   - **Estimated Time**: 10 minutes

## Instructions

1. On the Finance and Operations Home page, in the upper right, verify you're working with the **USMF** company. If necessary, select the company, and from the drop-down, select **USMF**.

2. In the upper left, select the **Expand the navigation pane** hamburger menu.

3. Select **Modules** > **Procurement and sourcing** > **Purchase orders** > **All purchase orders**.

4. On the **All purchase orders** page, in the upper menu, select **+New**.

5. In the **Create purchase order** pane, select the **Vendor account** drop-down, and then select **US-101**.

> [!NOTE]
> Note: When you select a vendor, details from the vendor record, such as address, invoice account, delivery terms, and delivery mode, is copied as default values into the order header. You can change these values at any time.

6. Expand the **General** section if necessary.

7. Under **STORAGE DIMENSIONS**, select the **Site** drop-down, and review the list of sites.

The **Site** field, together with the **Warehouse** field, specify where the procured goods or services must be delivered. The default delivery address is the site. Both fields can be populated with values set up for the selected vendor, or you can specify them manually.

8. Under **DATES**, the **Delivery date** field is used to specify when procured goods and services need to be delivered.

	You can specify a single delivery date for the order, or the individual order lines can be given unique delivery dates. If the delivery date specified here can't be met for specific products or services because they have longer lead times, then those lines are created with a later delivery date.

9. Expand the **Administration** section. The **Orderer** box can be used to specify who is placing the order.

	This may be convenient to share with the vendor in case they need to contact that person. The value may be assigned automatically if the current user account is associated with a name on the **Users** page.

10. Select **OK**.

The order header has now been created. When you work with purchase order lines, only a summary of the header information is displayed. If you need to view the rest of the information, select **Header**.

![Screenshot depicts the order header where the summary of the order information is shown. The word Header is highlighted.](media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-17.png)

11. Under **Purchase order lines**, on the menu, select **Purchase order line**.

![Screenshot depicts purchase order lines.](media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-18.png)

12. Under **DISPLAY**, select **Dimensions**.

	Products can be in variants differentiated by dimensions, such as color, size, or style. Products can also be set up to use storage dimensions, such as site and warehouse. There are also optional tracking dimensions, such as batch and serial numbers. To improve the efficiency of order entry, you can add the dimension fields that you commonly use directly to the order grid.

13. In the **Dimensions display** panel, under **PRODUCT DIMENSIONS**, select the **Color** check box.

Optional: If you select the **Save setup** toggle switch, the dimensions you have chosen will also be displayed on the order line grid the next time you open the purchase order page.

14. Select **OK**.

15. Select the **Item number** cell drop-down, and then select **T0004**.

Remember, you can also type in the filter box instead of scrolling through the list.

Order lines are created for products and services by specifying an item number or as expenses by specifying a procurement category.

Procurement category is used for adding lines where procured items are expensed directly, rather than going into inventory. If you need to make a purchase, you can do this by creating a purchase order line that specifies a procurement category, rather than creating a line with an item number. Items can also be associated with a procurement category, and in this case, the procurement category is displayed as informational only.

16. Select the **Color** drop-down, review the available options, and then select one of the colors or color combinations.

17. **Site** and **Warehouse** are typically populated with values from the order header, but it's possible to override the fields if some lines need to be delivered to different locations.

18. In the **Quantity** box, enter **10**.

	The **Quantity** is automatically populated with the minimum order quantity for the product if this is set up, or with the value of **1**.

19. Some additional information:

- **Unit**: Indicates the unit of measure for the ordered quantity. Normally, the unit is automatically provided from the purchasing unit on the product master data.

- **Unit price**: Contains a value from either a purchase agreement or a trade agreement. It is possible to change the unit price on individual order lines, for example, if a unique price is negotiated with the vendor.

- **Discount**: Represents a discount amount per unit. This discount therefore reduces the unit price by the discount. This discount is commonly supplied automatically from purchase agreements or trade agreements, but it is possible to override on individual lines if unique discounts have been negotiated with the vendor.

- **Discount percentage**: When entered, this reduces the net amount for the line accordingly. The discount percentage is often supplied automatically from purchase agreements or trade agreements, but it's possible to override on individual lines if a unique discount percentage has been negotiated with the vendor.

- **Net amount**: Calculated from other fields on the line, including quantity, unit price, discount, and discount percent. It's possible to change the Net amount, but then the Unit Price, Discount, and Discount percent fields are blank. When you then post toward the line, the amount posted will be proportional to the net amount. The Net Amount field is only used for displaying the net amount of the line.

20. Under the purchase order lines, at the bottom of the page, select **Line details**.

21. Select the **Delivery** tab.

	A unique delivery date can be assigned to each order line. The date is inherited from the field on the purchase order header, but you can change it.

22. Close the **Purchase order line** page.

23. On the **All purchase orders** page, use the Filter feature and find your new purchase order.

24. When complete, close the **All purchase orders** page and return to the home page.

