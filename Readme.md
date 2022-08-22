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
