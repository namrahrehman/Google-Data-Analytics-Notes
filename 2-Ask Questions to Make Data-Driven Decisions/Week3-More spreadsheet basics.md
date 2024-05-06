### Spreadsheet tasks
- Organize your data
  - Pivot tables
    - Sort and filter
- Calculate your data
  - Formulas
  - Functions
  
<details>
  <summary>Spreadsheets and the data life cycle</summary> <br>
  <ul>
    <li><strong>Plan</strong> for the users who will work within a spreadsheet by developing organizational standards. This can mean formatting your cells, the headings you choose to highlight, the color scheme, and the way you order your data points. When you take the time to set these standards, you will improve communication, ensure consistency, and help people be more efficient with their time.</li>
    <li><strong>Capture</strong> data by the source by connecting spreadsheets to other data sources, such as an online survey application or a database. This data will automatically be updated in the spreadsheet. That way, the information is always as current and accurate as possible.</li>
    <li><strong>Manage</strong> different kinds of data with a spreadsheet. This can involve storing, organizing, filtering, and updating information. Spreadsheets also let you decide who can access the data, how the information is shared, and how to keep your data safe and secure.</li>
    <li><strong>Analyze</strong> data in a spreadsheet to help make better decisions. Some of the most common spreadsheet analysis tools include formulas to aggregate data or create reports, and pivot tables for clear, easy-to-understand visuals.</li>
    <li><strong>Archive</strong> any spreadsheet that you don’t use often, but might need to reference later with built-in tools. This is especially useful if you want to store historical data before it gets updated.</li>
    <li><strong>Destroy</strong> your spreadsheet when you are certain that you will never need it again, if you have better backup copies, or for legal or security reasons. Keep in mind, lots of businesses are required to follow certain rules or have measures in place to make sure data is destroyed properly.</li>
  </ul>
</details> 

[Google Sheets shortcuts](https://support.google.com/docs/answer/181110), [Microsoft Excel shortcuts](https://support.microsoft.com/en-us/office/keyboard-shortcuts-in-excel-1798d9d5-842a-42b8-9c99-9b7213f0040f)

<details>
  <summary>Useful links</summary> <br>
  <ul>
    <li><strong>Excel</strong>: <a href="https://support.microsoft.com/en-us/office/office-quick-starts-25f909da-3e76-443d-94f4-6cdf7dedc51e#ID0EAADAAA=At_work_or_school" target="_blank">Office Quick Starts</a>, <a href="https://support.microsoft.com/en-us/office/excel-video-training-9bc05390-e94c-46af-a5b3-d7c22f6990bb?wt.mc_id=otc_home" target="_blank">Excel video training</a>, <a href="https://support.microsoft.com/en-us/office/sort-data-in-a-range-or-table-62d0b95d-2a90-4610-a6ae-2e545c4a4654" target="_blank">Sort data in a range or table</a>, <a href="https://support.microsoft.com/en-us/office/filter-data-in-a-range-or-table-01832226-31b5-4568-8806-38c37dcc180e" target="_blank">Filter data in a range or table</a>, <a href="https://support.microsoft.com/en-us/office/quick-start-format-a-worksheet-d70f75a2-23e6-4c92-83d6-2f219e4ad42e" target="_blank">Format a worksheet</a>, <a href="https://support.microsoft.com/en-us/office/guidelines-for-organizing-and-formatting-data-on-a-worksheet-90895cad-6c85-4e02-90d3-8798660166e3" target="_blank">Guidelines for organizing and formatting data on a worksheet</a>.</li>
    <li><strong>Google Sheets</strong>: <a href="https://support.google.com/a/users/answer/9300311?hl=en&ref_topic=9296423" target="_blank">Get started with Sheets: Create and import files</a>, <a href="https://support.google.com/docs/answer/3540681?co=GENIE.Platform%3DDesktop&hl=en" target="_blank">Sort and filter your data</a>, <a href="https://support.google.com/docs/answer/46973?co=GENIE.Platform%3DDesktop&hl=en&oco=0" target="_blank">Edit and format a spreadsheet</a>.</li>
    <li><a href="https://support.google.com/a/users/answer/9331278?hl=en" target="_blank">Overview: Differences between Sheets and Excel</a>.</li>
  </ul>
</details>
  
---

### Formulas
A formula is a set of instructions that perform a specific calculation. Formulas are built on operators which are symbols that name that type of operation or calculation to be performed.

#### Cell reference
A cell reference is a single cell or range of cells in a worksheet that can be used in a formula. Cell references contain the letter of the column and the number of the row where the data is. A range of cells is a collection of two or more cells. A range can include cells from the same row or column, or from different columns and rows collected together. The great thing about using cell references is that they also automatically update when a formula is copied to a new cell. <br>

<details>
  <summary>Auto-filling</summary> <br>
  The lower-right corner of each cell has a fill handle. It is a small green square in Microsoft Excel and a small blue square in Google Sheets.
  <ul>
    <li>Click the fill handle for a cell and drag it down a column to auto-fill other cells in the column with the same value or formula in that cell. </li>
    <li>Click the fill handle for a cell and drag it across a row to auto-fill other cells in the row with the same value or formula in that cell. </li>
    <li>If you want to create a numbered sequence in a column or row, do the following: 1) Fill in the first two numbers of the sequence in two adjacent cells, 2) Select to highlight the cells, and 3) Drag the fill handle to the last cell to complete the sequence of numbers. For example, to insert 1 through 100 in each row of column A, enter 1 in cell A1 and 2 in cell A2. Then, select to highlight both cells, click the fill handle in cell A2, and drag it down to cell A100. This auto-fills the numbers sequentially so you don't have to type them in each cell.</li>
  </ul>
</details>

<details>
  <summary>Absolute referencing</summary> <br>
  <ul>
    <li>Absolute referencing is marked by a dollar sign ($). For example, =$A$10 has absolute referencing for both the column and the row value</li>
    <li>Relative references (which is what you normally do e.g. “=A10”) will change anytime the formula is copied and pasted. They are in relation to where the referenced cell is located. For example if you copied “=A10” to the cell to the right it would become “=B10”. With absolute referencing “=$A$10” copied to the cell to the right would remain “=$A$10”. But if you copied $A10 to the cell below, it would change to $A11 because the row value isn't an absolute reference.</li>
    <li>Absolute references will not change when you copy and paste the formula in a different cell. The cell being referenced is always the same.</li>
    <li>To easily switch between absolute and relative referencing in the formula bar, highlight the reference you want to change and press the F4 key; for example, if you want to change the absolute reference, $A$10, in your formula to a relative reference, A10, highlight $A$10 in the formula bar and then press the F4 key to make the change. </li>
  </ul>
</details>

<details>
  <summary>Data range</summary> <br>
  The set of cells a data analyst selects to include in a formula is called the data range.
  <ul>
    <li>When you click into your formula, the colored ranges let you see which cells are being used in your spreadsheet. There are different colors for each unique range in your formula.</li>
    <li>In a lot of spreadsheet applications, you can press the F2 (or Enter) key to highlight the range of data in the spreadsheet that is referenced in a formula. Click the cell with the formula, and then press the F2 (or Enter) key to highlight the data in your spreadsheet. </li>
  </ul>
</details>

<details>
  <summary>Combining with functions</summary> <br>
  <ul><li>COUNTIF() is a formula and a function. This means the function runs based on criteria set by the formula. In this case, COUNT is the formula; it will be executed IF the conditions you create are true. For example, you could use =COUNTIF(A1:A16, “7”) to count only the cells that contained the number 7. Combining formulas and functions allows you to do more work with a single command. </li></ul>
</details>

**Spreadsheet errors and fixes**
| Error | Description | Example |
|---|---|---|
| #DIV/0! | Occurs when a formula tries to divide a value by zero (or an empty cell). | `=B2/B3` where cell B3 contains the value 0. |
| #ERROR! (Google Sheets only) | Indicates a parsing error, meaning the formula cannot be interpreted due to invalid syntax. | `=COUNT(B1:D1 C1:C10)` is invalid because cell ranges are not separated by a comma. |
| #N/A | Occurs when a formula cannot find the data it's looking for. | The cell being referenced might not exist. |
| #NAME? | Appears when the spreadsheet doesn't recognize the name of a formula or function used. | A function name might be misspelled. |
| #NUM! | Occurs when a formula cannot perform a calculation due to an invalid number in a cell. | `=DATEDIF(A4, B4, "M")` cannot calculate the number of months between two dates because the date in A4 is after the date in B4 (invalid date range). |
| #REF! | Occurs when a formula references a cell that is no longer valid. | This might happen if a cell used in the formula was deleted. |
| #VALUE! | A general error indicating a problem with the formula or referenced cells. | Issues might involve spaces, text, or invalid references. Further investigation is needed to identify the cause. |


---

### Functions
A function is a preset command that automatically performs a specific process or task using the data.

**Difference between formulas and functions**
- A formula is a set of instructions used to perform a calculation using the data in a spreadsheet.
- A function is a preset command that automatically performs a specific process or task using the data in a spreadsheet.

<details>
  <summary>Relative, absolute, and mixed references</summary> <br>
  <ul>
    <li>Relative references (cells referenced without a dollar sign, like A2) will change when you copy and paste the function into a different cell. With relative references, the location of the cell that contains the function determines the cells used by the function. </li>
    <li>Absolute references (cells fully referenced with a dollar sign, like $A$2) will not change when you copy and paste the function into a different cell. With absolute references, the cells referenced always remain the same.</li>
    <li>Mixed references (cells partially referenced with a dollar sign, like $A2 or A$2) will change when you copy and paste the function into a different cell. With mixed references, the location of the cell that contains the function determines the cells used by the function, but only the row or column is relative (not both).   </li>
    <li>In spreadsheets, you can press the F4 key to toggle between relative, absolute, and mixed references in a function. Click the cell containing the function, highlight the referenced cells in the formula bar, and then press F4 to toggle between and select relative, absolute, or mixed referencing.  </li>
  </ul>
</details>

**Spreadsheet Keyboard Shortcuts**

| Command | Chromebook | PC | Mac |
|---|---|---|---|
| Create new workbook | Control+N | Control+N | Command+N |
| Open workbook | Control+O | Control+O | Command+O |
| Save workbook | Control+S | Control+S | Command+S |
| Close workbook | Control+W | Control+W | Command+W |
| Undo | Control+Z | Control+Z | Command+Z |
| Redo | Control+Y | Control+Y | Command+Y |
| Copy | Control+C | Control+C | Command+C |
| Cut | Control+X | Control+X | Command+X |
| Paste | Control+V | Control+V | Command+V |
| Paste values only | Control+Shift+V | Control+Shift+V | Command+Shift+V |
| Find | Control+Shift+F | Control+F | Command+F |
| Find and replace | Control+H | Control+H | Command+Shift+F |
| Insert link | Control+K | Control+K | Command+K |
| Bold | Control+B | Control+B | Command+B |

## More Spreadsheet Keyboard Shortcuts

| Command | Chromebook | PC | Mac |
|---|---|---|---|
| Italicize | Control+I | Control+I | Command+I |
| Underline | Control+U | Control+U | Command+U |
| Zoom in | Control+Plus (+) | Control+Plus (+) | Option+Command+Plus (+) |
| Zoom out | Control+Minus (-) | Control+Minus (-) | Option+Command+Minus (-) |
| Select column | Control+Spacebar | Control+Spacebar | Command+Spacebar |
| Select row | Shift+Spacebar | Shift+Spacebar | Up Arrow+Spacebar |
| Select all cells | Control+A | Control+A | Command+A |
| Edit the current cell | Enter | F2 | F2 |
| Comment on a cell | Ctrl + Alt + M | Alt+I+M | Option+Command+M |
| Insert column to the left | Ctrl + Alt + = (existing column selected) | Alt+Shift+I, then C | Command + Option + = (existing column selected) |
| Insert column to the right | Alt + I, then O | Alt+Shift+I, then O | Command + Option + = (existing row selected) |
| Insert row above | Ctrl + Alt + = (existing row selected) | Alt+Shift+I, then R | Ctrl + Option + I, then B |
| Insert row below | Alt + I, then R, then B | Alt+Shift+I, then R | Ctrl+Option+I, then O |

---

### Problem domain
The specific area of analysis that encompasses every activity affecting or affected by the problem.

Carefully defining a business problem can ultimately save time, money, and resources. All of this is achieved through structured thinking.

### Structured thinking
The process of recognizing the current problem or situation, organizing available information, revealing gaps and opportunities, and identifying the options.

The starting place for structured thinking is the problem domain. Once you know the specific area of analysis, you can set your base and lay out all your requirements and hypotheses before you start investigating.

You can practice structured thinking and avoid mistakes is by using a scope of work.

### Scope of work (SOW)
An agreed- upon outline of the work you're going to perform on a project. A scope of work is project-based and sets the expectations and boundaries of a project. A scope of work keeps everyone on the same page. Using structured thinking, you can define what is being delivered, when, and how you will measure success along the way.

There’s no standard format for an SOW. They may differ significantly from one organization to another, or from project to project. However, they all have a few foundational pieces of content in common: 
- **Deliverables** are items or tasks you will complete before you can finish the project. <br> What work is being done, and what things are being created as a result of this project? When the project is complete, what are you expected to deliver to the stakeholders? Be specific here. Will you collect data for this project? How much, or for how long?
- **Timelines** include due dates for when deliverables, milestones, and/or reports are due. <br> The timeline is a way of mapping expectations for how long each step of the process should take. The timeline should be specific enough to help all involved decide if a project is on schedule. When will the deliverables be completed? How long do you expect the project will take to complete? If all goes as planned, how long do you expect each component of the project will take? When can we expect to reach each milestone?
- **Milestones** are significant tasks you will confirm along your timeline to help everyone know the project is on track. <br> This is closely related to your timeline. What are the major milestones for progress in your project? How do you know when a given part of the project is considered complete? 
- **Reports** notify everyone as you finalize deliverables and meet milestones. <br> Good SOWs also set boundaries for how and when you’ll give status updates to stakeholders. How will you communicate progress with stakeholders and sponsors, and how often? Will progress be reported weekly? Monthly? When milestones are completed? What information will status reports contain?

![image](https://user-images.githubusercontent.com/74421758/146637082-0cc28c96-6c1d-4005-8d66-748e2d766f5c.png)

[Data Analysis Project Scope-of-Work (SOW) Strong Example](https://docs.google.com/document/d/16x-E04Nr48Ww1Nlxwa0PNOXyaytKbVCxrF5yRJy6Y70/template/preview?resourcekey=0-X1a531fuUVbtlNKdIA11dQ)

<br>

Usually, projects don’t start until an SOW is approved with its key pieces of content: the deliverables, milestones, timeline, and reports. To collect and synthesize this information, analysts identify and formalize quantifiable project requirements. They use structured thinking to ask clarifying questions, define what to accomplish, and specify project boundaries.

### Context
The condition in which something exists or happens. To avoid bias when collecting data, a data analyst should keep context in mind. Context can turn raw data into meaningful information. It is very important for data analysts to contextualize their data. This means giving the data perspective by defining it. To do this, you need to identify:
- **Who**: The person or organization that created, collected, and/or funded the data collection
- **What**: The things in the world that data could have an impact on
- **Where**: The origin of the data
- **When**: The time when the data was created or collected
- **Why**: The motivation behind the creation or collection
- **How**: The method used to create or collect it

To ensure your data is accurate and fair, make sure you start with an accurate representation of the population in the sample; collect the data in an objective way; and ask questions about the data.

---

## Course 2, Module 3: Glossary

* **AVERAGE:** A spreadsheet function that calculates and returns the average of the values from a selected range of cells.
* **Borders:** Lines that can be added around individual cells or groups of cells on a spreadsheet to improve visual organization.
* **Cell reference:** A reference to a specific cell or a range of cells in a worksheet, typically used in formulas and functions.
* **COUNT:** A spreadsheet function that counts the number of cells in a specified range that meet a certain criteria, such as containing numbers or text.
* **Equation (Math expression):** A formula that performs a calculation involving mathematical operations like addition, subtraction, multiplication, or division.
* **Fill handle:** A small square box in the lower-right corner of a selected spreadsheet cell. Dragging the fill handle allows you to copy the cell's formatting or formula to neighboring cells.
* **Filtering:** The process of temporarily hiding rows that don't meet specific criteria, allowing you to focus on relevant data without altering the original spreadsheet.
* **Header:** The top row in a spreadsheet that labels the type of data contained in each column. Headers provide context and improve readability.
* **Math function:** A pre-defined function within a spreadsheet program performing a specific mathematical calculation, like SUM or AVERAGE.
* **MAX:** A spreadsheet function that returns the largest numeric value from a selected range of cells.
* **MIN:** A spreadsheet function that returns the smallest numeric value from a selected range of cells.
* **Open data:** Data sets that are freely available to the public and can be used by anyone without restrictions.
* **Operator:** A symbol that represents a specific operation or calculation to be performed in a formula, like "+" for addition or "-" for subtraction.
* **Order of operations (PEMDAS):** A set of rules that defines the order in which mathematical operations (Parentheses, Exponents, Multiplication and Division, Addition and Subtraction) are performed within a formula to ensure accurate calculations.
* **Problem domain:** The specific area of analysis that encompasses every activity affecting or affected by the problem you're trying to solve.
* **Range:** A rectangular block of cells in a spreadsheet consisting of two or more cells. 
* **Report:** A static collection of data, often presented in a table format, that is periodically generated and shared with stakeholders.
* **Return on investment (ROI):** A financial metric used to evaluate the success of an investment by comparing the profit gained to the cost of the investment. 
* **Revenue:** The total income generated by a business through the sale of goods or services.
* **Scope of work (SOW):** A formal document that outlines the tasks, deliverables, and timelines agreed upon for a project. 
* **Sorting:** The process of rearranging data in a spreadsheet based on specific criteria (e.g., alphabetical order, numerical value) to facilitate analysis and visualization.
* **SUM:** A spreadsheet function that adds the values of all the cells within a selected range. 


---
