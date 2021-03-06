![Excel Logo Banner](https://i2.wp.com/blog.discudemy.com/wp-content/uploads/2017/11/connector-excel-logo.png)

Excel VBA Functions Package for Business Data Analysts
===
Created to facilitate data processing and analysis at the business operations level. Common functions used for Excel-based projects / reports / apps requiring extensive data manipulation. 

Drag and drop the .bas file as a module in the VBA editor.

Requires a basic understanding of how to use functions within VBA. For an overview, please visit http://www.excel-vba-easy.com/vba-programming-function-sub.html or http://www.excelfunctions.net/VBA-Functions-And-Subroutines.html.

Note that most functions included in this package require a worksheet object as the first argument.

### Example using the lastRow function: ###

If the last row of data is located on row 15, this routine will select cells A1:C15
```vba
Set ws = workbooks("currentOpenWorkbook.xlsx").worksheets("Sheet1")
ws.cells(lastRow(ws),3).select
```
Where `lastRow(ws)` returns the **last row number** of worksheet **ws**, and **`3`** is Column C (the third column in a worksheet).

Please feel free to contact me for any help/clarification.

# License #

This software is available under the MIT license.
