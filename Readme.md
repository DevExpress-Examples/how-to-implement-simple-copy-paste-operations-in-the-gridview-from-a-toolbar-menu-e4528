<!-- default file list -->
*Files to look at*:

* [EditForm.cs](./CS/DXGridCRUDoperations/EditForm.cs) (VB: [EditForm.vb](./VB/DXGridCRUDoperations/EditForm.vb))
* [Main.cs](./CS/DXGridCRUDoperations/Main.cs) (VB: [Main.vb](./VB/DXGridCRUDoperations/Main.vb))
* [Person.cs](./CS/DXGridCRUDoperations/Person.cs) (VB: [Person.vb](./VB/DXGridCRUDoperations/Person.vb))
* [Program.cs](./CS/DXGridCRUDoperations/Program.cs) (VB: [Program.vb](./VB/DXGridCRUDoperations/Program.vb))
<!-- default file list end -->
# How to implement simple copy/paste operations in the GridView from a toolbar menu


<p><br />
This example illustrates how to implement simple copy/paste/delete operations in the GridView.<br />
You can find more in the article <a href="https://www.devexpress.com/Support/Center/p/A1266">How to implement a Copy/Paste feature</a></p>


<h3>Description</h3>

Starting with version 17.2, pasting data from the Clipboard is supported out of the box. To enable this feature, set the&nbsp;<strong>GridView.OptionsClipboard.PasteMode</strong>&nbsp;property to Update or Append. It should be possible to paste data by pressing CTRL+V or using the&nbsp;<strong>GridView.PasteFromClipboard</strong>&nbsp;method.

<br/>


