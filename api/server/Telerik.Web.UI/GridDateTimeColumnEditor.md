---
title: Telerik.Web.UI.GridDateTimeColumnEditor
page_title: Telerik.Web.UI.GridDateTimeColumnEditor
description: Telerik.Web.UI.GridDateTimeColumnEditor
---

# Telerik.Web.UI.GridDateTimeColumnEditor

The editor for the Telerik.Web.UI.GridDateTimeColumn column.

## Inheritance Hierarchy

* System.Object
* System.Web.UI.Control
* Telerik.Web.UI.GridColumnEditorBase : IGridColumnEditor
* Telerik.Web.UI.GridTextColumnEditor
* Telerik.Web.UI.GridDateTimeColumnEditor

## Properties

###  ContainerControl `Control`

Gets the instance of the Container control (generally a TableCell), after the last call of InstantiateInControl method

###  ImagesPath `String`

Gets or sets default path for the GridDateTimeColumnEditor images when EnableEmbeddedSkins is set to false.

###  IsInEditMode `Boolean`

Get a value indicating whether the current row/column editor is in edit mode.

###  IsInitialized `Boolean`

Get value if the editor has been initialized after an InitializeInControl or InitializeFromControl method call

###  PickerControl `RadDatePicker`

Gets The text box instance created of extracted from a cell after calls to AddControlsToContainer or LoadControlsFromContainer methods.

###  SharedCalendar `RadCalendar`

Gets the shared calendar used for all  picker controls.

###  SharedTimeView `RadTimeView`

Gets the shared time view used for all  controls using TimeView.

###  Text `String`

Gets or sets the cell text.

###  Text `String`

Gets or sets the cell text.

###  TextBoxControl `RadDateInput`

Gets The text box instance created of extracted from a cell after calls to AddControlsToContainer or LoadControlsFromContainer methods.

###  TextBoxStyle `Style`

Gets the instace of the Style that would be applied to the TextBox control, when initializing in a TableCell.

###  ToolTip `String`

The ToolTip that will be applied to the  control.

## Methods

###  AddControlsToContainer

Implement this member to create the edit controls in the grid cell.
            This method is called from each column's InitializeCell method, when a  initializes its cells.

#### Returns

`System.Void` 

###  CopySettingsFrom

Copy setting from given column editor

#### Parameters

#### editor `Telerik.Web.UI.IGridColumnEditor`

#### Returns

`System.Void` 

###  CreateControls

Create the input/edit controls belonging to the editor and prepare for AddControlsToContainer call.

#### Returns

`System.Void` 

###  LoadControlsFromContainer

This method should recrteate the state of the column editor (edit controls, etc) from the container.
            This method is called when  method is called, or when
            GridEditableItem.EditManager.GetColumnEditor is called.

#### Remarks
This method is should prepare the column editor to extract values from the edit controls residign in a TableCell of the grid.

#### Returns

`System.Void` 

