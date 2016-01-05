# SwiftyDDHotKey [中文](http://)
####How to use DDHotKey with swift (OS X).

[DDHotKey](https://github.com/davedelong/DDHotKey) is an easy-to-use Cocoa class for registering an application to respond to system key events, or "hotkeys". ----DDHotKey


# Step 1
### include DDHotKey files in your project
Copy DDHotKey files in your project 

* DDHotKeyCenter.h
* DDHotKeyCenter.m
* DDHotKeyUtilities.h
* DDHotKeyUtilities.m
* DDHotKeyTextField.h
* DDHotKeyTextField.m

# Step 2
* add **" #import <AppKit/AppKit.h> "** to DDHotKeyUtilities.m

# Step 3
* add **Bridging-Header.h** file in project
* add **#import "DDHotKeyCenter.h"** to Bridging-Header.h

# Step 4
* use DDHotKey easily with DDHotKey API	
