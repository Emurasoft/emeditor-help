# Delete Left Line command

### Summary

> Deletes the line to the left of the cursor.

### Description

> Deletes text from the cursor position to the beginning of the logical line.

### How to Run

- Default Menu: None
- [All Commands](../tools/all_commands): **Edit** \> **Delete**
\> **Delete Left Line**
- Toolbar: None
- Status Bar: None
- Default Keyboard Shortcut: None

### Plug-in Command ID

- EEID\_DELETE\_LEFT\_LINE (4302)

### Macros

#### \[JavaScript\]

> document.selection.StartOfLine(true,eeLineLogical);
>
> document.selection.Delete(1);

#### \[VBScript\]

> document.selection.StartOfLine true,eeLineLogical
>
> document.selection.Delete 1