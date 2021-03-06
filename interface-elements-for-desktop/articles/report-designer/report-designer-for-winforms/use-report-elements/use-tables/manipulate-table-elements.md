---
title: Manipulate Table Elements
author: Anna Gubareva
---
# Manipulate Table Elements

## Select Table Elements

You can click a table cell to select it and [access its settings](../manipulate-report-elements/select-report-elements-and-access-their-settings.md). To select multiple cells, hold the SHIFT or CTRL key and click cells.

![](../../../../../images/eurd-win-table-control-multiple-selected-cells.png)

Use the arrow that appears when a mouse cursor hovers over the table edges to select an entire row or column.

![](../../../../../images/eurd-win-table-control-select-rows-and-columns.png)

Click the ![](../../../../../images/eurd-win-table-control-select-table-button.png) button at the table's left bottom corner to select the whole table. You can also use this button to move the table.

The **Select** group in the [toolbar](../../report-designer-tools/toolbar.md)'s **Table Tools** contextual tab also enables you to select the current row, the current column or the entire table.

![](../../../../../images/eurd-win-table-select-toolbar-group.png)


## Resize Table Elements

You can resize a table or its cell by dragging the rectangle drawn on its edge or corner. 

The following column resizing modes are supported:

* Resizing a column changes the next column's width without affecting the other columns (keeps the table dimensions intact).
	
	![](../../../../../images/eurd-win-table-control-column-resizing.png)

* Resizing a column while holding the CTRL key changes the next columns' width while maintaining their proportion to the overall table (keeps the table dimensions intact).
	
	![](../../../../../images/eurd-win-table-control-column-resizing-with-ctrl.png)

* Resizing a column while holding the SHIFT key shifts the next columns without changing their size.
	
	![](../../../../../images/eurd-win-table-control-column-resizing-with-shift.png)

The following row resizing modes are supported:

* Resizing a row changes the next row's width without affecting the other rows (keeps the table dimensions intact).
	
	![](../../../../../images/eurd-win-table-control-row-resizing.png)

* Resizing a row while holding the SHIFT key shifts the next rows without changing their size.
	
	![](../../../../../images/eurd-win-table-control-row-resizing-with-shift.png)

You can set the same size for multiple table columns or rows. Select the required rows or the whole table, right-click the selected area and choose **Distribute Rows Evenly**.

![](../../../../../images/eurd-win-table-control-distribute-rows-evenly.png)

If the cell's content is partially visible in the resulting row, this row automatically increases its height to fit its content and also adjusts the other rows accordingly.

You can resize columns equally in a similar way by selecting the columns or the table itself and choosing **Distribute Columns Evenly** in the context menu.

![](../../../../../images/eurd-win-table-control-distribute-columns-evenly.png)

## Reorder Table Rows and Cells

You can change the order of table rows and cells. Switch to the [Report Explorer](../../report-designer-tools/ui-panels/report-explorer.md) window, select a row or cell and drag it to a new position.

![](../../../../../images/reorder-table-cells.gif)

The Report Explorer highlights the possible drop targets when you drag an element over them.

> [!NOTE]
> You can move table rows and cells only within the same parent control.

## Apply Styles to Table Elements

Select a table element and switch to the **Property Grid**. Expand the **Styles** group and set the **Style** property to the style name.

![design-time-select-style](../../../../../images/eurd-win-select-style-table.png)

As an alternative, you can drag a style from the Report Explorer onto an element.

![design-time-drag-style](../../../../../images/eurd-win-drag-style.gif)

## Stretch Table Cells

You can stretch a cell so that it occupies several rows and columns.

- Stretch a cell across several columns  
  Remove a neighboring cell by pressing DELETE or selecting **Delete** | **Cell** in the context menu and resize the remaining cells.

  ![](../../../../../images/eurd-win-table-control-cell-column-span.png)

- Stretch a cell across several columns  
  Use a table cell's **Row Span** property to specify the number of rows the table cell spans.

  ![](../../../../../images/eurd-win-table-control-cell-rows-span.png)

  > [!NOTE]
  > For the **RowSpan** property to work properly, the spanned cells should have the same width.