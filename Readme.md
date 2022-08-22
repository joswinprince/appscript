## Appscript

### Send quote
```
function sendquote() 
{
  SpreadsheetApp.getActive().toast("Sending quote.");
}
```

### set value
```
function myfunction()
{
  SpreadsheetApp.getActiveSheet().getRange("A22").setValue("rerere");
}
```
### creating menus and sub menus
```
function onOpen() {
  var ui = SpreadsheetApp.getUi();
  // Or DocumentApp or FormApp.
  ui.createMenu('Custom Menu')
      .addItem('First item', 'menuItem1')
      .addSeparator()
      .addSubMenu(ui.createMenu('Sub-menu')
          .addItem('Second item', 'menuItem2'))
      .addToUi();
}
```
