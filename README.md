# Ruby-Icons
Ruby Icon set for desktop personalisation.
HOW TO SET UP!

For general icons!!! 
    For Games, launchers, internet browsers, Simply right click current icon 
    Properties 
    Customization 
    Change Icon: Select image with (.ICO) file.
    
For Recycle Bin!!!
    Windows Key 
    Type 'Themes' and select 
    Select 'Desktop Icon Settings' 
    Change BOTH recycle bin icons
    
For Hard drive icons!!! 
    For Hard drive icons like C Drive, D drive, etc. 
    use Win+R 
    Type 'REGEDIT' 
    Hit 'YES' 
    Type or copy 'HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\DriveIcons' 
    Right click and select 'KEY' 
    Rename to drive letter, i.e. 'C', 'D', 'H', etc. 
    Right click Drive Letter and select 'NEW STRING VALUE' 
    Rename to 'DefaultIcon' 
    Double click '(Default)' and change 'VALUE' to the .ICO file LOCATION path, I.E. C:\Icon Folder\ICO Files\Image.ico
    
To Remove Shortcut 'Arrow' Icon!!!
    Use Win+R
    Type 'REGEDIT'
    Hit 'YES'
    Type or copy 'Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Shell Icons'
    Right click and select 'NEW STRING VALUE'
    Rename to '29'
    Change 'VALUE' to '%windir%\System32\shell32.dll,-50'
    Restart PC to view effects.
    
T Remove Desktop Icon Names!!!
    First use a keyboard with a NUMPAD or Google 'Invisible text characters'
    On a keyboard with NUMPAD:
    Right click icon
    Select 'Rename'
    HOLD ALT key and type '255'
    This creates ONE (1) invisible character
    Repeat 'LINE 44' for second icon OR use spaces inbetween INVISIBLE CHARACTERS
    EXAMPLE: (ALT+255, SPACE, ALT+255) or (ALT+255, SPACE, SPACE, ALT+255, ALT+255) etc.
