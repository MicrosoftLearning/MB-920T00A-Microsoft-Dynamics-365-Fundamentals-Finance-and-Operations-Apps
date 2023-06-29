---
lab:
    title: 'Lab 3: Create a production order'
    module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management

## Lab 3: Create a production order

## Objective

Production orders help to initiate the production process in Supply Chain Management. In this lab, you become familiar with the user interface and functionality of the Production order form. Also, you learn how to create a production order by the end of the exercise.

## Lab Setup

   - **Estimated Time**: 5 minutes

## Instructions

1. On the **Finance and Operations home** page, in the top right, verify you're working with the **USMF** company.

2. If necessary, select the company and from the menu, select **USMF**.

3. In the left navigation pane, select **Modules** > **Production control** > **Production orders** > **All production orders**.

4. On the top menu, select **New production order**.

5. Under **IDENTIFICATION**, in the **Item number** box, enter **D0001**.

6. In the **Quantity** box, enter **20**.

7. Under **PRODUCTION**, in the **Delivery** box, select a date one month from today's date.

    The delivery date indicates when the production order should end to deliver on time. This date can be used in the scheduling process. For example, you can schedule the order backward from the delivery date.

8. Under BOM/ROUTE, the **BOM number** field automatically displays the number of any active BOM for the current item, but you can change the BOM for the production order by selecting an active BOM from the list of approved BOM versions. The **Route number** field automatically displays the number of any active Route for the current item, but you can change the Route for the production order by selecting an active Route from the list of approved Route versions.

![Screenshot depicts the create production order page. The item number and delivery fields are highlighted.](../media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-40.png)

9. Select **Create**.

