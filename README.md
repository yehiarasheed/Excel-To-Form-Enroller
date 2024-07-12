# Excel To Form Enroller

## Project Description

Automating student enrollment involves extracting data from Excel files and seamlessly populating Google Forms for each individual student, including data validation. The end goal is **to reduce the processing time per item by 80% and achieve better monitoring of overall activity using the logs provided by the robots.**

![Project Image](https://github.com/yehiarasheed/Excel-To-Form-Enroller/assets/157399068/4598b44e-b21d-4d4e-9004-efa68fad739c)

Validations include checking whether the Excel file exists, has at least one non-empty row, if the form exists in the given link, and whether a certain student record has missing information.

You'll find the PDD (Process Definition Document) and two versions of the Excel File, the complete version and another one that tests for validations, in the `Additional Files` folder.

## How to Install

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yehiarasheed/Excel-To-Form-Enroller.git
   cd Excel-To-Form-Enroller
   ```
   Alternatively, Clone the Repository in UiPath Studio:
   - Open UiPath Studio.
   - Go to the `Team` tab.
   - Click on `Clone Repository`.
   - Enter the repository URL: https://github.com/yehiarasheed/Excel-To-Form-Enroller.git.
   - Select the destination folder and click `Open` using your Authentication method of choice.

2. **Install UiPath Studio:**
   Download and install UiPath Studio from the [official UiPath website](https://www.uipath.com).

3. **Open the Project in UiPath Studio:**
   - Launch UiPath Studio.
   - Click on `Open` in the Start tab.
   - Navigate to the cloned repository folder and open the `.xaml` file.

## Dependencies

This project requires the following dependencies:

- **Microsoft Excel**: Required for handling Excel files.
- **UiPath.Excel.Activities**: For interacting with Excel files.
- **UiPath.System.Activities**: For general automation tasks.
- **UiPath.WebAPI.Activities**: For making HTTP requests to the form enrollment service.

These dependencies can be managed through UiPath Studio's Package Manager. Make sure all required packages are installed and up to date.

---
