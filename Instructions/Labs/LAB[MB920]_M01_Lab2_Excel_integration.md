---
lab:
    title: 'Lab 2: Excel integration'
    module: 'Module 1: Explore the core capabilities of Dynamics 365 finance and operations apps'
---

# Module 1: Explore the core capabilities of Dynamics 365 finance and operations apps

## Lab 2: Excel integration

## Objective

In this lab, you will learn how to copy data from finance and operations to Excel using Dynamics Data Connector office add-in app. You will also learn how the same app can be used to insert data into finance and operations apps. 

## Lab Setup

   - **Estimated Time**: 5 minutes

## Instructions

Now that you have become familiar with finance and operations apps, take some time to explore the Excel integration scenario. 

1.  Make sure you are in the **USMF** legal entity.

2.  Navigate to **Procurement and sourcing** > **Setup** > **Vendors** > **Vendor groups**.

3.  In the action pane, select **Open in Microsoft Office** and under **Open in Excel**, select **Vendor groups (usmf)**

4.  In the **Open in Excel** pane, select **Download**. 

5.  The Excel template file will be downloaded and saved. **Open** the downloaded Excel template file, skip or allow other standard security prompts if needed, close activation, and select **Enable Editing**. Select **Trust this add-in**, and then sign in (using your same credentials, if asked). 

    All the existing data of the **Vendor group** table will appear in the Excel spreadsheet. 

6.  To create a new record, enter `100` in the **Vendor group** field, `Insurance vendor` in the **Description** field, and `Net10` in the **Terms of payment** field. 

7.  Select the **Publish** button in the Microsoft Dynamics Data Connector task pane. 

8.  Open and refresh the **Vendor groups** form in Dynamics 365 to verify that the new record has been added. 

