---
lab:
    title: 'Lab 2: Excel integration'
    module: 'Module 1: Explore the core capabilities of Dynamics 365 finance and operations apps'
---

# Module 1: Explore the core capabilities of Dynamics 365 finance and operations apps

## Lab 2 - Excel integration

Now that you have become familiar with finance and operations apps, take some time to explore the Excel integration scenario.

### Task #1: Create template

1. Open the Finance and Operations home page. 

2. Navigate to **Modules** > **Common** > **Common** > **Office Integration** > **Excel Workbook** **Designer**. Note that most navigation is through Modules, so this is not typically specified.

3. Search for **VendorGroup** in the filter.

4. From the list of available fields, select the fields **Vendor group**, **Description**, and **Terms of payment** and move them to the selected field box by selecting the right arrow.

5. In the action pane, select the **Create workbook** button.

6. On the right, in the **Save To** panel, select the **Download** button.

7. Download the file by selecting **Save As** and store it in the **Downloads** folder.

8. Navigate to **Common** > **Office Integration** > **Document** **templates**.

9. Select **New**.

10. In the right panel, in the **Upload template** section, select the **Browse** button and select the file downloaded previously (if you used the default name, it is DynamicsWorkbook).

11. In the **Template name** field, enter **CustomVendorGroup**.

12. Select **OK**, and then select **Save**.

### Task #2: Open in Excel

1. Navigate to **Procurement and sourcing** > **Setup** > **Vendors** > **Vendor groups**.

2. Select **Open in Microsoft Office** > **Open in Excel** to find the new template, CustomVendorGroup, that you uploaded.

3. Select **CustomVendorGroup** and download the Excel template.

4. Save and then open the downloaded Excel template, allow it if needed, close activation, and select **Enable editing**. Trust this add-in, and then sign in (using your same credentials, if asked).

All the existing data of the Vendor group table will appear in the Excel spreadsheet.

5. Enter a new record.

6. Enter **100** in the **Vendor group** field, **Insurance Vendor** in the **Description** field, and **Net10** in the **Terms of payment** field.

7. Select the **Publish** button in the Microsoft Dynamics Office Add-in app.

8. Open the **Vendor group** form to verify that the new record is added.

