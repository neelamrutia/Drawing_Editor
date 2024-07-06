# Ease Drawing Editor Instructions

## Running the Editor

To run the application, execute the following command in your terminal:


```sh
python3 src/main.py

```

Upon running, the editor window will open.

## Drawing Shapes

- Click on the **Line** icon to draw a line.
- Click on the **Rectangle** icon to draw a rectangle.
  - The default line color for shapes is **BLACK**.

## Selecting Parts

- Click on the **dashed_rectangular** icon and enclose the ENTIRE desired area in the dashed rectangle.
- Upon releasing the mouse, additional options will be displayed:
  1. **Group**: Forms a group of selected items.
  2. **Ungroup**: Removes one layer of grouping from the selected part.
  3. **Ungroup All**: Ungroups all layers, making all objects individual entities.
  4. **Move**: Allows moving the selected object by dragging and dropping.
  5. **Delete**: Deletes the selected part entirely.
  6. **Copy**: Creates a separate copy of the selected part indicated by a dashed line.

### Important Notes:
1. Perform desired operations after a selection and then deselect. **DO NOT** perform multiple selections at a single time.
2. Also, do not draw while a selection is open.

After any operation on a selected part, it remains selected. Deselect by clicking on the select option again.

## Edit Options

- **Single Line**: Click on **Edit** to change line color. Changes reflect after closing the dialog box.
- **Single Rectangle**: Click on **Edit** to change line color and corner style. Changes reflect after closing the dialog box.

## Saving/Opening/Exporting

- **Saving**: Click **Save** in the **FILE** menu to save the drawing in ASCII code in `.txt` format.
- **Opening**: Start the program with a specific file name or use **File -> Open** to open a `.txt` file.
- **Exporting**: Click **File -> Export to XML** to export to XML format.

### Note: To deselect a selected part, click on the **dashed_rectangular** icon again.



