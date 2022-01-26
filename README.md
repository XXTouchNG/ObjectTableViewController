# ObjectTableViewController

A simple property list viewer in Objective-C.

## Usage

```objective-c
ObjectTableViewController *objCtrl = [[ObjectTableViewController alloc] initWithObject:aPropertyListObject];
objCtrl.pressToCopy = YES;
objCtrl.showTypeHint = YES;
objCtrl.allowSearch = YES;
[aNavigationController pushViewController:objCtrl animated:YES];
```
