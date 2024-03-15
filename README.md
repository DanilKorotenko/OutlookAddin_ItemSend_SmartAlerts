# OutlookAddin_ItemSend_SmartAlerts

What is working and what is not.

|      | ItemSend Manifest <p> install by hands | ItemSend Manifest <p> install via admin panel | SmartAlerts Manifest <p> install by hands | SmartAlerts Manifest <p> install via admin panel
|-----:|-----------|---|-|-|
|Mac Outlook Application| Working. Possible to install. <p> Panel is visible.||Installation success. Panle invisible. Not working.||
|https://outlook.office365.com/|Possible to install. Panel is invisible. Not Working.||After installing in mac app. impossible to uninstall.||
|     3|        ||||

#### Link to install addin for outlook.com

https://aka.ms/olksideload

#### steps to reproduce

1. Install manifest
2. Choose any message in inbox.
3. Create and send message

Expected result:
1. Installation success
2. In reading, addin button is visible. User can see addin panel.
3. In composing message, addin button is visible. User can see addin panel.
4. Addin blocks message send.
