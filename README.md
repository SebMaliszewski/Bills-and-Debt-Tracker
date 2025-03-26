Overview
--------

This project includes two Excel files: Bills.xlsx and Debt Tracker.xlsx, designed to help track monthly bills, expenses, and debt repayments. The files are interlinked, allowing for automated calculations based on predefined structures and formulas.

Bills.xlsx
----------

Customisation

Editing Payment Names: Users should update the payment names in column B to match their own expenses.

Updating value F2: The income in cell F2 must also be updated manually.

Updating column A: The value in column A (date) must be updated manually to reflect the correct period.

Dropdown Lists:

Column D contains dropdown lists for selecting payment statuses.

Cell F5 also includes a dropdown list. To edit this list, modify the predefined options in the Data tab.

Debt Tracker.xlsx
-----------------

Dependency on Bills.xlsx

The Debt Tracker file pulls data from Bills.xlsx based on debt agency names.

The names in A12, E12, I12, M12, and Q12 in the Debt Tracker sheet must match the corresponding names in Bills.xlsx to correctly retrieve data.

Debt Tracker displays all planned and completed payments recorded in Bills.xlsx.

The calculation of Paid amounts depends on the status in Column D of Bills.xlsx.

Customisation

To ensure clarity, it is recommended to adjust values in A3:A7 in the Debt Tracker sheet to match the agency names in A12, E12, I12, M12, and Q12.

The graphical chart descriptions should also be updated accordingly to correctly reference the relevant debt agencies.

Summary

Users should carefully adjust names and settings to fit their personal financial tracking needs. Ensuring correct agency name matching between Bills.xlsx and Debt Tracker.xlsx is essential for proper data retrieval and calculations. The graphical elements and summaries should also be personalised to reflect individual financial situations.

Important
---------

Information for Using the Bills and Debt Tracker Files

If you are using both the Bills and Debt Tracker files and they are located in different folders or on a different computer, Excel may not automatically update the file paths to reflect the new location. This means that when you open the Debt Tracker file, Excel may prompt you with a message stating that it cannot find the external source (the Bills file).

To resolve this, you will need to manually update the file path in the formulas to point to the correct location of the Bills file on your computer. Here are the steps you should follow:

When Excel prompts you with an error about missing external links, select the option to Update Links.

A window will appear asking you to locate the Bills file. Navigate to the location where you have saved the Bills file, and select it.

Once the correct file is selected, Excel will update the links and the formulas should start working properly.

Note: It’s recommended to keep both files in the same folder or in a shared cloud location (e.g., OneDrive, Google Drive) to avoid having to update the file paths manually. If the files are stored in the same folder, Excel will automatically adjust the links when you open the file, and you won’t need to make any manual changes.